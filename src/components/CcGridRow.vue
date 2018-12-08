<template>
    <div class="cc-row cc-row-no-focus cc-row-no-animation cc-row-level-0 cc-row-odd" row="23" style="top: 598px; height: 26px;">
        <div class="cc-cell-no-focus cc-cell cc-cell-not-inline-editing cc-cell-value ng-scope" v-for="col in columns" v-bind:key="col.colid" :colid="col.colid" :class="col.class" :style="col.style">{{ col.value }}</div>
    </div>
</template>

<script>
export default {
  name: 'CcGridRow',
  components: {
  },
  props: {
    columns: Array,
  },
  data: () => ({
    columnsX: [
        { colid: '0', clsss: { 'cc-column-hover': false, 'text-center': true }, style: { 'left': '0px', 'width': '30px', 'font-size': '9px', 'margin-top': '2px' }, value: '24' },
        { colid: 'urlName', clsss: { 'cc-column-hover': true, 'text-center': false }, style: { 'left': '30px', 'width': '250px' }, value: 'blau-l-silber' },
        { colid: 'productType', clsss: { 'cc-column-hover': false, 'text-center': true }, style: { 'left': '280px', 'width': '106px' }, value: 'Postpaid-Tarif' },
        { colid: 'tariffName', clsss: { 'cc-column-hover': false, 'text-center': true }, style: { 'left': '386px', 'width': '105px' }, value: 'Blau L' },
        { colid: 'tariffVariationCode', clsss: { 'cc-column-hover': false, 'text-center': true }, style: { 'left': '491px', 'width': '105px' }, value: '9875083' },
        { colid: 'segment', clsss: { 'cc-column-hover': false, 'text-center': true }, style: { 'left': '596px', 'width': '105px' }, value: 'Privatkunden' },
        { colid: 'frameContractNumber', clsss: { 'cc-column-hover': false, 'text-center': true }, style: { 'left': '701px', 'width': '105px' }, value: '70000600' },
        { colid: 'tariffProduct', clsss: { 'cc-column-hover': false, 'text-center': true }, style: { 'left': '806px', 'width': '176px' }, value: 'blau-l' },
        { colid: 'period.from', clsss: { 'cc-column-hover': false, 'text-center': false }, style: { 'left': '982px', 'width': '105px' }, value: '07.12.2016' },
        { colid: 'period.till', clsss: { 'cc-column-hover': false, 'text-center': false }, style: { 'left': '1087px', 'width': '105px' }, value: '23.01.2017' },
    ],
  }),
}
</script>

<style>
</style>
