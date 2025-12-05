<script setup>
import { onMounted } from 'vue'
import Highcharts from 'highcharts'

onMounted( () => {
    Highcharts.chart('LineChart', {
      chart: { type: 'line' },
      title: { 
        text: '圖表名稱',
        style: {
            fontSize: '18px',
            color: '#00a19b',
            fontWeight: 'bold'
        }
      },
      xAxis: {
        categories: ['Jan', 'Feb', 'Mar'],
        gridLineWidth: 1,
        labels: {
            align: 'left',
            style: {
                fontSize: '14px'
            }
        }
      },
      yAxis: [{
        title: {
            text: null
        },
        labels: {
            style: {
                fontSize: '14px'
            }
        },
        showFirstLabel: false,
      },{
        linkedTo: 0,
        gridLineWidth: 0,
        opposite: true,
        title: {
            text: null
        },
        labels: {
            style: {
                fontSize: '14px'
            }
        },
        showFirstLabel: false
      }],
      legend: {
        align: 'left',
        margin: 50,
        verticalAlign: 'top',
        borderWidth: 0,
        itemStyle: {
        fontWeight: 'medium',
        color: '#1C1C1C',
        fontSize: '16px'
        }
      },
      tooltip: {
        shared: true,
        crosshairs: true,
        borderColor: '#d9d9d9',
        style: {
            fontSize: '14px'
        }
      },
      plotOptions: {
        series: {
            cursor: 'pointer',
            className: 'popup-on-click',
            marker: {
                lineWidth: 1
            }
        }
      },
      series: [{ 
        name: '銀行賣出',
        color: '#1DA4EF',
        data: [1, 3, 2],
        lineWidth: 2,
        market: {
            radius: 4
        },
        
      },{
        name: '銀行買入',
        color: '#FD9A01',
        data: [2, 1, 3],
        lineWidth: 2,
        market: {
            radius: 4
        },
      }
      ],
      credits: {
        enabled: false
      }

    })
})
</script>

<template>
  <div id="LineChart"></div>
</template>
