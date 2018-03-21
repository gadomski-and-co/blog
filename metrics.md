---
layout: page
title: Metrics
sitemap:
    priority: 1.0
    changefreq: weekly
    lastmod: 2014-09-07T16:31:30+05:30
---

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.8.2/jquery.min.js"></script>
<script src="https://code.highcharts.com/highcharts.js"></script>
<script src="https://code.highcharts.com/modules/exporting.js"></script>

<div id="hoursWorkDelivered" style="min-width: 310px; height: 400px; margin: 0 auto">
</div>
<div id="hoursLogged" style="min-width: 310px; height: 400px; margin: 0 auto">
</div>
<div id="averageEstimationDeviation" style="min-width: 310px; height: 400px; margin: 0 auto">
</div>
<div id="amountOfEmailCorrespondence" style="min-width: 310px; height: 400px; margin: 0 auto">
</div>
<div id="fourUpBullets" style="min-width: 310px; height: 400px; margin: 0 auto">
</div>

<script type="text/javascript">
    $('#hoursWorkDelivered').highcharts({
        title: {
            text: 'Estimated Hours of Work Delivered',
            x: -20 //center
        },
        xAxis: {
            categories: ['Iteration 1', 'Iteration 2', 'Iteration 3', 'Iteration 4', 'Iteration 5'] //TODO: Update this
        },
        yAxis: {
            title: {
                text: 'Hours Delivered'
            },
            plotLines: [{
                value: 0,
                width: 1,
                color: '#808080'
            }],
            min: 0
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
            name: 'Hours Delivered',
            data: [31, 62, 27, 71, 33] //TODO: Update this
        }]
    });
</script>

<script type="text/javascript">
    $('#hoursLogged').highcharts({
        title: {
            text: 'Hours Logged',
            x: -20 //center
        },
        xAxis: {
            categories: ['Iteration 1', 'Iteration 2', 'Iteration 3', 'Iteration 4', 'Iteration 5'] //TODO: Update this
        },
        yAxis: {
            title: {
                text: 'Hours Logged'
            },
            plotLines: [{
                value: 0,
                width: 1,
                color: '#808080'
            }],
            min: 0
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
            data: [121.5, 145.5, 93, 81.25, 56.5] //TODO: Update this
        }]
    });
</script>

<script type="text/javascript">
    $('#averageEstimationDeviation').highcharts({
        title: {
            text: 'Average Estimation Deviation (%)',
            x: -20 //center
        },
        xAxis: {
            categories: ['Iteration 1', 'Iteration 2', 'Iteration 3', 'Iteration 4', 'Iteration 5'] //TODO: Update this
        },
        yAxis: {
            title: {
                text: 'Estimation Deviation (%)'
            },
            plotLines: [{
                value: 0,
                width: 1,
                color: '#808080'
            }],
            min: -100,
            max: 100
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
            name: 'Estimation Deviation (%)',
            data: [62.4, 48.4, -78.13, -21.25, -12.5] //TODO: Update this
        }]
    });
</script>

<script type="text/javascript">
    $('#amountOfEmailCorrespondence').highcharts({
        title: {
            text: 'Amount of Email Correspondence (in # of email threads)',
            x: -20 //center
        },
        xAxis: {
            categories: ['Iteration 1', 'Iteration 2', 'Iteration 3', 'Iteration 4', 'Iteration 5'] //TODO: Update this
        },
        yAxis: {
            title: {
                text: 'Email Threads'
            },
            plotLines: [{
                value: 0,
                width: 1,
                color: '#808080'
            }],
            min: 0
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
            name: 'Email Threads',
            data: [10, 6, 4, 6, 6] //TODO: Update this
        }]
    });
</script>

<script type="text/javascript">
    $('#fourUpBullets').highcharts({
        title: {
            text: 'Total Four-Up Chart Bullet Items',
            x: -20 //center
        },
        xAxis: {
            categories: ['Iteration 1', 'Iteration 2', 'Iteration 3', 'Iteration 4' 'Iteration 5'] //TODO: Update this
        },
        yAxis: {
            title: {
                text: 'Four-Up Chart Bullet Items'
            },
            plotLines: [{
                value: 0,
                width: 1,
                color: '#808080'
            }],
            min: 0
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
            name: 'Four-Up Chart Bullet Items',
            data: [38, 32, 39, 26, 28] //TODO: Update this
        }]
    });
</script>