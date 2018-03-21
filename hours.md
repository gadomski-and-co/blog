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
            categories: ['8/28 - 9/3', '9/4 - 9/10', '9/11 - 9/17', '9/18 - 9/24', '9/25 - 10/1', '10/2 - 10/8', '10/9 - 10/15', '10/16 - 10/22', '10/23 - 10/29', '10/30 - 11/5', '11/6 - 11/12', '11/13 - 11/19', '11/20 - 11/26', '11/27 - 12/3', '12/4 - 12/10', '12/11 - 12/17', '1/15 - 1/21', '1/22 - 1/28', '1/29 - 2/4', '2/5 - 2/11', '2/12 - 2/18', '2/19 - 2/25', '2/26 - 3/4', '3/5 - 3/11'] //TODO: Update this
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
            data: [17, 17.75, 24.50, 20.50, 14.00, 15.5, 32.5, 59.5, 26, 20, 33, 66.5, 12.5, 31, 31, 9, 15, 12.5, 28.25, 25.5, 15, 12, 10, 19.5] //TODO: Update this
        }]
    });
</script>

### Hour Breakdowns
[2/26 - 3/4 Hours]({{site.root}}{% post_url 2018-3-21-hours %})<br>
[2/26 - 3/4 Hours]({{site.root}}{% post_url 2018-3-5-hours %})<br>
[2/19 - 2/25 Hours]({{site.root}}{% post_url 2018-2-26-hours %})<br>
[2/12 - 2/18 Hours]({{site.root}}{% post_url 2018-2-19-hours %})<br>
[2/5 - 2/11 Hours]({{site.root}}{% post_url 2018-2-12-hours %})<br>
[1/29 - 2/5 Hours]({{site.root}}{% post_url 2018-2-5-hours %})<br>
[1/22 - 1/28 Hours]({{site.root}}{% post_url 2018-1-29-hours %})<br>
[1/15 - 1/21 Hours]({{site.root}}{% post_url 2018-1-22-hours %})<br>
[12/11 - 12/17 Hours]({{site.root}}{% post_url 2017-12-18-hours %})<br>
[12/04 - 12/10 Hours]({{site.root}}{% post_url 2017-12-11-hours %})<br>
[11/27 - 12/03 Hours]({{site.root}}{% post_url 2017-12-04-hours %})<br>
[11/20 - 11/26 Hours]({{site.root}}{% post_url 2017-11-27-hours %})<br>
[11/13 - 11/19 Hours]({{site.root}}{% post_url 2017-11-20-hours %})<br>
[11/6 - 11/12 Hours]({{site.root}}{% post_url 2017-11-13-hours %})<br>
[10/30 - 11/5 Hours]({{site.root}}{% post_url 2017-11-06-hours %})<br>
[10/23 - 10/29 Hours]({{site.root}}{% post_url 2017-10-30-hours %})<br>
[10/16 - 10/22 Hours]({{site.root}}{% post_url 2017-10-24-hours %})<br>
[10/9 - 10/15 Hours]({{site.root}}{% post_url 2017-10-16-hours %})<br>
[10/2 - 10/8 Hours]({{site.root}}{% post_url 2017-10-09-hours %})<br>
[9/25 - 10/1 Hours]({{site.root}}{% post_url 2017-10-02-hours %})<br>
[9/18 - 9/24 Hours]({{site.root}}{% post_url 2017-09-25-hours %})<br>
[9/11 - 9/17 Hours]({{site.root}}{% post_url 2017-09-18-hours %})<br>
[9/4 - 9/10 Hours]({{site.root}}{% post_url 2017-09-10-hours %})<br>
[8/28 - 9/3 Hours]({{site.root}}{% post_url 2017-09-02-hours %})