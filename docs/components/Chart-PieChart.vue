
<script setup>
import { onMounted } from 'vue'
import Highcharts from 'highcharts'

onMounted(async () => {
    Highcharts.chart('PieChart', {
      chart: {
        type: 'pie'
      },
      colors: [
        '#00A19B', '#BDE3E2', '#007A7A', '#FF9900', '#FFD77A', '#D97B00',
        '#0083C9', '#93E6FE', '#00497D', '#00C08B', '#87E3BF', '#00735A', '#D9D9D9', '#595959'
      ],
      title: {
        text: '圖表名稱',
        style: {
          fontSize: '18px',
          color: '#00a19b',
          fontWeight: 'bold'
        }
      },
      plotOptions: {
        pie: {
          allowPointSelect: true,
          cursor: 'pointer',
          dataLabels: {
            enabled: true,
            format: '<b>{point.name}</b>: {point.percentage:.1f} %',
            connectorColor: '#acacac',
            style: {
              fontSize: '13px',
            }
          },
        }
      },
      series: [{
        name: '占比',
        data: [
          { name: '項目1', y: 8 },
          { name: '項目2', y: 7 },
          { name: '項目3', y: 10 },
          { name: '項目4', y: 12 },
          { name: '項目5', y: 9 },
          { name: '項目6', y: 6 },
          { name: '項目7', y: 8 },
          { name: '項目8', y: 7 },
          { name: '項目9', y: 5 },
          { name: '項目10', y: 6 },
          { name: '項目11', y: 8 },
          { name: '項目12', y: 4 }
        ]
      }],
      credits: {
        enabled: false
      }
    });
})
</script>

<template>
  <div id="PieChart"></div>
</template>
