<script>
    import echarts from "../modules/echarts";
    export let config = undefined;    

    export let height = '291px'
    export let width = '100%'

</script>

<div 
    class="chart" 
    style="
        height: {height};
        width: {width};
        margin-left: 0;
        margin-top: 15px;
        margin-bottom: 15px;
        overflow: visible;
    "
    use:echarts={config}
/>

<style>
  @media print {
    .chart {
      break-inside: avoid;
    }
  }
  .chart {
    -moz-user-select: none;
    -webkit-user-select: none;
    -ms-user-select: none;
    user-select: none;
  }
</style>