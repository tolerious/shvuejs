<template>
  <div class="menu-container">
    <ul>
      <li>加入我们</li>
    </ul>
  </div>
</template>

<script>
import { mapState, mapGetters, mapMutations } from "vuex";
export default {
  data() {
    return {};
  },
  methods: { ...mapMutations([]) },

  mounted() {},
  watch: {},
  computed: { ...mapState({}), ...mapGetters([]) },
  components: {}
};
</script>

<style lang='less' scoped>
.menu-container {
  height: 40px;
  position: absolute;
  right: 30px;
  top: 30px;
  ul,
  li {
    list-style: none;
    margin: 0;
    padding: 0;
  }
  ul {
    display: flex;
    flex-direction: row;
    width: 500px;
    justify-content: flex-end;
    align-items: center;
  }
  li {
    height: 100%;
    line-height: 40px;
    color: white;
    cursor: pointer;
    padding: 0 5px;
  }
}
</style>
