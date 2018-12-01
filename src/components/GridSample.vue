<template>
  <div class="cc-fresh" style="height: 337px" ng-style="Ctrl.tableHeight">
    <div class="cc-bl cc-bl-full-height cc-ltr">
      <div class="cc-bl-center cc-bl-full-height-center" style="margin-left: 0px;width: 1123px;" id="center">
        <div class="cc-bl cc-bl-full-height">
          <div class="cc-bl-center cc-bl-full-height-center" style="margin-left: 0px;width: 1123px;" id="center">
            <div class="cc-root cc-scrolls cc-font-style">
              <div class="cc-header" style="height: 25px">
                <div class="cc-header-viewport" style="margin-left: 0px; margin-right: 0px">
                  <div class="cc-header-container" style="left: 0px" :style="headerContainerStyle">
                    <div class="cc-header-row" style="top: 0px; height: 25px; width: 1500px">
                      <div class="cc-header-cell" v-for="day in days" v-bind:key="day.label" :style="day.style">{{ day.label }}</div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="cc-body" style="top: 25px; height: 312px;">
                <div class="cc-body-viewport-wrapper" style="margin-left: 0px; margin-right: 0px;">
                  <div class="cc-body-viewport" style="overflow-y: auto;" v-on:scroll.native.passive="onScroll" @scroll.exact="onScroll">
                    <div class="cc-body-container" style="height: 200928px; top: 0px; width: 1192px;">
                      <div class="cc-row cc-row-no-focus cc-row-no-animation cc-row-level-0 cc-row-even" row="0" style="top: 0px; height: 26px;">
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value ng-scope cc-column-hover" colid="urlName" style="width: 250px; left: 30px;">blau-9-ct-prepaid</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="productType" style="width: 106px; left: 280px;">Prepaid-Tarif</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="tariffName" style="width: 105px; left: 386px;">Blau 9ct Prepaid</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="tariffVariationCode" style="width: 105px; left: 491px;">TARIFF:201</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="segment" style="width: 105px; left: 596px;">Privatkunden</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="frameContractNumber" style="width: 105px; left: 701px;"></div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="tariffProduct" style="width: 176px; left: 806px;">blau-9ct-prepaid</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value ng-scope" colid="period" style="width: 105px; left: 982px;">07.12.2016</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value ng-scope" colid="period_1" style="width: 105px; left: 1087px;">28.11.2018</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="0" style="width: 30px; left: 0px; font-size: 9px; margin-top: 2px;">1</div>
                      </div>
                      <div class="cc-row cc-row-no-focus cc-row-no-animation cc-row-level-0 cc-row-odd" row="1" style="top: 26px; height: 26px;">
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value ng-scope cc-column-hover" colid="urlName" style="width: 250px; left: 30px;">blau-allnet-l-bk</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="productType" style="width: 106px; left: 280px;">Postpaid-Tarif</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="tariffName" style="width: 105px; left: 386px;">Blau All-In</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="tariffVariationCode" style="width: 105px; left: 491px;">9875085</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="segment" style="width: 105px; left: 596px;">Privatkunden</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="frameContractNumber" style="width: 105px; left: 701px;">63002390</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="tariffProduct" style="width: 176px; left: 806px;">blau-allnet-l</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value ng-scope" colid="period" style="width: 105px; left: 982px;">07.12.2016</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value ng-scope" colid="period_1" style="width: 105px; left: 1087px;">16.01.2017</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="0" style="width: 30px; left: 0px; font-size: 9px; margin-top: 2px;">2</div>
                      </div>
                      <div class="cc-row cc-row-no-focus cc-row-no-animation cc-row-level-0 cc-row-even" row="2" style="top: 52px; height: 26px;">
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value ng-scope cc-column-hover" colid="urlName" style="width: 250px; left: 30px;">blau-allnet-l-bk2</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="productType" style="width: 106px; left: 280px;">Postpaid-Tarif</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="tariffName" style="width: 105px; left: 386px;">Blau All-In</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="tariffVariationCode" style="width: 105px; left: 491px;">9875085</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="segment" style="width: 105px; left: 596px;">Privatkunden</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="frameContractNumber" style="width: 105px; left: 701px;">63002380</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="tariffProduct" style="width: 176px; left: 806px;">blau-allnet-bk</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value ng-scope" colid="period" style="width: 105px; left: 982px;">07.12.2016</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value ng-scope" colid="period_1" style="width: 105px; left: 1087px;">23.01.2017</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="0" style="width: 30px; left: 0px; font-size: 9px; margin-top: 2px;">3</div>
                      </div>
                      <div class="cc-row cc-row-no-focus cc-row-no-animation cc-row-level-0 cc-row-odd" row="3" style="top: 78px; height: 26px;">
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value ng-scope cc-column-hover" colid="urlName" style="width: 250px; left: 30px;">blau-allnet-l</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="productType" style="width: 106px; left: 280px;">Postpaid-Tarif</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="tariffName" style="width: 105px; left: 386px;">Blau All-In</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="tariffVariationCode" style="width: 105px; left: 491px;">15852846</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="segment" style="width: 105px; left: 596px;">Privatkunden</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="frameContractNumber" style="width: 105px; left: 701px;"></div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="tariffProduct" style="width: 176px; left: 806px;">blau-allnet-l</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value ng-scope" colid="period" style="width: 105px; left: 982px;">07.12.2016</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value ng-scope" colid="period_1" style="width: 105px; left: 1087px;">18.06.2017</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="0" style="width: 30px; left: 0px; font-size: 9px; margin-top: 2px;">4</div>
                      </div>
                      <div class="cc-row cc-row-no-focus cc-row-no-animation cc-row-level-0 cc-row-even" row="4" style="top: 104px; height: 26px;">
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value ng-scope cc-column-hover" colid="urlName" style="width: 250px; left: 30px;">blau-9-ct-prepaid-bundle</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="productType" style="width: 106px; left: 280px;">Prepaid-Tarif</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="tariffName" style="width: 105px; left: 386px;">Blau 9ct Prepaid</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="tariffVariationCode" style="width: 105px; left: 491px;">TARIFF:201</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="segment" style="width: 105px; left: 596px;">Privatkunden</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="frameContractNumber" style="width: 105px; left: 701px;"></div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="tariffProduct" style="width: 176px; left: 806px;">blau-9ct-prepaid</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value ng-scope" colid="period" style="width: 105px; left: 982px;">07.12.2016</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value ng-scope" colid="period_1" style="width: 105px; left: 1087px;">09.08.2017</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="0" style="width: 30px; left: 0px; font-size: 9px; margin-top: 2px;">5</div>
                      </div>
                      <div class="cc-row cc-row-no-focus cc-row-no-animation cc-row-level-0 cc-row-odd cc-row-hover" row="5" style="top: 130px; height: 26px;">
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value ng-scope cc-column-hover" colid="urlName" style="width: 250px; left: 30px;">blau-allnet-l-platin</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="productType" style="width: 106px; left: 280px;">Postpaid-Tarif</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="tariffName" style="width: 105px; left: 386px;">Blau All-In</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="tariffVariationCode" style="width: 105px; left: 491px;">9875085</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="segment" style="width: 105px; left: 596px;">Privatkunden</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="frameContractNumber" style="width: 105px; left: 701px;">70000800</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="tariffProduct" style="width: 176px; left: 806px;">blau-allnet-l</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value ng-scope" colid="period" style="width: 105px; left: 982px;">07.12.2016</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value ng-scope" colid="period_1" style="width: 105px; left: 1087px;">23.01.2017</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="0" style="width: 30px; left: 0px; font-size: 9px; margin-top: 2px;">6</div>
                      </div>
                      <div class="cc-row cc-row-no-focus cc-row-no-animation cc-row-level-0 cc-row-odd" row="23" style="top: 598px; height: 26px;">
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value ng-scope cc-column-hover" colid="urlName" style="width: 250px; left: 30px;">blau-l-silber</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="productType" style="width: 106px; left: 280px;">Postpaid-Tarif</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="tariffName" style="width: 105px; left: 386px;">Blau L</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="tariffVariationCode" style="width: 105px; left: 491px;">9875083</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="segment" style="width: 105px; left: 596px;">Privatkunden</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="frameContractNumber" style="width: 105px; left: 701px;">70000600</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="tariffProduct" style="width: 176px; left: 806px;">blau-l</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value ng-scope" colid="period" style="width: 105px; left: 982px;">07.12.2016</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value ng-scope" colid="period_1" style="width: 105px; left: 1087px;">23.01.2017</div>
                        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value text-center ng-scope" colid="0" style="width: 30px; left: 0px; font-size: 9px; margin-top: 2px;">24</div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
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
    days: Array.from({length: 31}, (value, key) => key).map(n => ({ label: n + 1, style: `width: 40px; left: ${n * 40}px` })),
    headerContainerStyle: 'left: 0px',
  }),
  methods: {
    onScroll (event) {
      // Any code to be executed when the window is scrolled
      console.log(event, event.target.scrollLeft, event.target.scrollTop);
      this.headerContainerStyle = `left: ${-event.target.scrollLeft}px`;
    }
  },
  created () {
    //window.addEventListener('scroll', this.onScroll);
  },
  destroyed () {
    //window.removeEventListener('scroll', this.onScroll);
  },
}
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.cc-fresh {
    line-height: 1.4;
    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    font-size: 14px;
    color: #222;
}
.cc-fresh .cc-root {
    border: 1px solid #808080;
}
.cc-fresh .cc-header {
    color: #000;
    background: -webkit-linear-gradient(#fff, #d3d3d3);
    background: -moz-linear-gradient(#fff, #d3d3d3);
    background: -o-linear-gradient(#fff, #d3d3d3);
    background: -ms-linear-gradient(#fff, #d3d3d3);
    background: linear-gradient(#fff, #d3d3d3);
    border-bottom: 1px solid #808080;
    font-weight: normal;
}
.cc-fresh .cc-ltr .cc-header-cell {
    border-right: 1px solid #808080;
}
.cc-fresh .cc-body {
    background-color: #f6f6f6;
}
.cc-fresh .cc-row-odd {
    background-color: #f6f6f6;
}
.cc-fresh .cc-row-even {
    background-color: #fff;
}
cc-fresh .cc-cell-not-inline-editing {
    padding: 2px;
}
.cc-fresh .cc-cell-no-focus {
    border-top: 1px solid transparent;
    border-bottom: 1px solid transparent;
}
.cc-fresh .cc-ltr .cc-cell-no-focus {
    border-right: 1px dotted #808080;
    border-left: 1px solid transparent;
}

.cc-bl {}

.cc-bl-full-height {
    height: 100%;
    overflow: auto;
    position: relative;
}

.cc-ltr {
    direction: ltr;
}

.cc-bl-center {}

.cc-bl-full-height-center {
    height: 100%;
}

.cc-root {
    position: relative;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
    overflow: hidden;
}

.cc-font-style {
    cursor: default;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
}

.cc-scrolls {
    height: 100%;
}
.cc-scrolls .cc-header-container {
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
    position: relative;
    white-space: nowrap;
    height: 100%;
}
.cc-scrolls .cc-header-row {
    position: absolute;
}
.cc-scrolls .cc-body-container {
    position: relative;
    display: inline-block;
}
.cc-scrolls .cc-row {
    white-space: nowrap;
    position: absolute;
    width: 100%;
}

.cc-header {
    position: absolute;
    top: 0px;
    left: 0px;
    white-space: nowrap;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
    overflow: hidden;
    width: 100%;
}

.cc-header-viewport {
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
    overflow: hidden;
    height: 100%;
}

.cc-header-row {
    position: absolute;
}

.cc-header-cell {
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
    vertical-align: bottom;
    text-align: center;
    display: inline-block;
    height: 100%;
    position: absolute;
}

.cc-body {
    height: 100%;
    width: 100%;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
    position: absolute;
}

.cc-body-viewport-wrapper {
    height: 100%;
}

.cc-body-viewport {
    overflow-x: auto;
    overflow-y: auto;
    height: 100%;
}

.cc-row {
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
}

.cc-row-no-animation {
    -webkit-transition: background-color 0.1s;
    -moz-transition: background-color 0.1s;
    -o-transition: background-color 0.1s;
    -ms-transition: background-color 0.1s;
    transition: background-color 0.1s;
}

.cc-cell {
    display: inline-block;
    white-space: nowrap;
    height: 100%;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
    -o-text-overflow: ellipsis;
    text-overflow: ellipsis;
    overflow: hidden;
    position: absolute;
}

</style>
