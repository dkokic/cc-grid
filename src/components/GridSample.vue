<template>
  <div class="cc-fresh" style="height: 545px" ng-style="Ctrl.tableHeight">
    <div style="height: 100%; overflow: auto; position: relative">
      <div style="height: 100%; margin-left: 0px; width: 911px">
        <div class="cc-root cc-scrolls cc-font-style">
          <div class="cc-header" style="height: 25px">
            <div class="cc-header-viewport" style="margin-left: 0px; margin-right: 0px">
              <div class="cc-header-container" style="left: 0px">
                <div class="cc-header-row" style="top: 0px; height: 25px; width: 1500px">
                  <div class="cc-header-cell" v-for="day in days" v-bind:key="day" :style="day.style">{{ day.label }}</div>
                </div>
              </div>
            </div>
          </div>
          <div class="cc-body" style="height: 520px; top: 25px">

          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
export default {
  name: 'GridSample',
  props: {
    args: String,
  },
  data: () => ({
    days: Array.from({length: 31}, (value, key) => key).map(n => ({ label: n + 1, style: `width: 100px; left: ${n * 100}px` })),
  }),
}
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.cc-fresh {
    line-height: 1.4;
    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    font-size: 14px;
    color: #222;
    background: linear-gradient(#fff, #d3d3d3);
    border-bottom: 1px solid #808080;
    font-weight: normal;
}


.cc-root {
    border: 1px solid #808080
}

.cc-scrolls {
    height: 100%;
}

.cc-font-style {
    cursor: default;
}

.cc-header {
    position: absolute;
    top: 0px;
    left: 0px;
    white-space: nowrap;
    box-sizing: border-box;
    overflow: hidden;
    width: 100%;
}

.cc-header-viewport {
    box-sizing: border-box;
    overflow: hidden;
    height: 100%;
}

.cc-header-container {
    box-sizing: border-box;
    position: relative;
    white-space: nowrap;
    height: 100%;
}

.cc-header-row {
    position: absolute;
}

.cc-header-cell {
    box-sizing: border-box;
    vertical-align: bottom;
    text-align: center;
    display: inline-block;
    height: 100%;
    position: absolute;
}

.cc-body {

}

</style>
