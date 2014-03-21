ng-xCharts
==========

Directive allowing you to add xCharts to your app

Instructions:
--------------------------
1. Add xCharts style
<link rel="stylesheet" href="bower_components/ng-xCharts/xcharts.min.css"/>
2. Add xCharts.js and ng-xCharts.js
<script type="text/javascript" src="bower_components/ng-xCharts/xcharts.min.js"></script>
<script type="text/javascript" src="bower_components/ng-xCharts/ng-xCharts.js"></script>
3. Take care that id is defined, data type and opts are available on scope
<xchart id='myChart' style="height: 300px;" data="data" type="type" opts="opts"></xchart>

Note:
--------------------------
The "id" attribute is mandatory!
