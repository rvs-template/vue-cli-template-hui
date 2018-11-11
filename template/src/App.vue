<template>
  <div id="app">
    <h-cell-group class="item-list">
      <h-cell is-link icon="points" title="我的积分" />
      <h-cell is-link icon="gift" title="我收到的礼物" />
    </h-cell-group>
  </div>
</template>

<script>
import { Cell, CellGroup, Icon } from 'hui';

export default {
  components: {
    [Cell.name]: Cell,
    [CellGroup.name]: CellGroup,
    [Icon.name]: Icon
  }
};
</script>

<style>
body {
  background-color: #f8f8f8;
}

.h-cell__title .h-icon {
  font-size: 18px;
}
</style>
