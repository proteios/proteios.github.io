---
layout: single
title: Statistics
author_profile: true
permalink: /statistics/
---
{% javascript %}
  javascript_code
{% endjavascript %}

<script src="https://d3js.org/d3.v5.min.js"></script>
<link rel="stylesheet" href="./images/billboard.css">
<script src="./images/billboard.js"></script>
<link rel="stylesheet" href="./images/datalab.min.css">
<script>
    var chart = bb.generate({
        bindto: "#chart",
        data: {
            type: "bar",
            columns: [
                ["data1", 30, 200, 100, 170, 150, 250],
                ["data2", 130, 100, 140, 35, 110, 50]
            ]
        }
    });
</script>
<div id="chart"></div>
