# Population-by-city
Highcharts.chart('container', {
  chart: { type: 'column' },
  title: { text: 'Population by City' },
  xAxis: { categories: ['New York','London','Tokyo','Sydney'] },
  yAxis: { title: { text: 'Population (millions)' } },
  series: [
    { name: '2020', data: [8.4, 9.0, 14.0, 5.3] },
    { name: '2024', data: [8.8, 9.3, 14.2, 5.5] }
  ],
  legend: { align: 'center', verticalAlign: 'bottom' },
  accessibility: { enabled: true }
});
