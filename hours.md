---
layout: page
title: Hours
sitemap:
    priority: 1.0
    changefreq: weekly
    lastmod: 2014-09-07T16:31:30+05:30
---

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.8.2/jquery.min.js"></script>
<script src="https://code.highcharts.com/highcharts.js"></script>
<script src="https://code.highcharts.com/modules/exporting.js"></script>

<div id="container" style="min-width: 310px; height: 400px; margin: 0 auto">
</div>

<script type="text/javascript">
    $('#container').highcharts({
        title: {
            text: 'Hours Logged per Week',
            x: -20 //center
        },
        xAxis: {
            categories: ['8/28 - 9/3', '9/4 - 9/10', '9/11 - 9/17', '9/18 - 9/24', '9/25 - 10/1'] //TODO: Update this
        },
        yAxis: {
            title: {
                text: 'Hours Logged'
            },
            plotLines: [{
                value: 0,
                width: 1,
                color: '#808080'
            }]
        },
        tooltip: {
            valueSuffix: ''
        },
        legend: {
            layout: 'vertical',
            align: 'right',
            verticalAlign: 'middle',
            borderWidth: 0
        },
        series: [{
            name: 'Hours Logged',
            data: [17, 17.75, 24.50, 20.50, 14.00] //TODO: Update this
        }]
    });
</script>

### Hour Breakdowns
[9/25 - 10/1 Hours]({{site.root}}{% post_url 2017-10-02-hours %})<br>
[9/18 - 9/24 Hours]({{site.root}}{% post_url 2017-09-25-hours %})<br>
[9/11 - 9/17 Hours]({{site.root}}{% post_url 2017-09-18-hours %})<br>
[9/4 - 9/10 Hours]({{site.root}}{% post_url 2017-09-10-hours %})<br>
[8/28 - 9/3 Hours]({{site.root}}{% post_url 2017-09-02-hours %})