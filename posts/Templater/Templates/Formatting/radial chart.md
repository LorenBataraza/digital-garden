````ad-flex

<div>

<br>

职业：射手
派系：长城守卫军
标签：输出
特性：超远攻击

</div>



<div>

```dataviewjs
const chartData = {
  type: 'radar',
  data: {
    labels: ['生命', '攻击', '射程', '防御', '移速', '暴击'],
    datasets: [{
      label: '王者英雄六维',
      data: [2,5,5,2,4,0],
      backgroundColor: [
        'rgba(255, 99, 132, 0.2)'
      ],
      borderColor: [
        'rgba(255, 99, 132, 1)'
      ],
      borderWidth: 1
    }]
  },
	options: {
    fill: true,
		scales: {
			r: {
				min: 0,
				max: 5,
				ticks: { display: false }
			},
		},
    plugins: {
		  legend: {
		    display: false
		  },
		}
	},
};

const c = this.container.createEl('div');
c.style.width = '60%';
window.renderChart(chartData, c);
```

</div>

````