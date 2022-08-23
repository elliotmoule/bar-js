# bar-js
Lightweight, configurable, and simple, bar chart library in JavaScript.

[![GitHub license](https://img.shields.io/github/license/elliotmoule/bar-js)](https://github.com/elliotmoule/bar-js/blob/master/LICENSE.md)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/elliotmoule/bar-js)
![GitHub top language](https://img.shields.io/github/languages/top/elliotmoule/bar-js)


## Description
bar.js is a Canvas-based, simple, JavaScript Bar Chart Library to provide a configurable, lightweight, and dependency-free experience.

![](https://raw.githubusercontent.com/elliotmoule/bar-js/master/bar.PNG)

## Installation
Download the `bar.min.js` file and include it within your project:

```html
<script src="bar.min.js"></script>
```

## Usage
To create the bar chart, you need a block level container like a 'div' or 'p'.

```html
<div id="chart">This will be a bar chart</div>
```

```js
var barChart = new BarChart(chartId, chartWidth, chartHeight, data);
```

### Parameters
- `chartId - containerId (String)`
Defines the id of the container (e.g. "chart").

- `chartWidth (Integer)`
Defines the width of the chart (e.g. 500).

- `chartHeight (Integer)`
Defines the height of the chart (e.g. 400)

- `data (Objects Array)`
Defines the data objects. The Objects should have two (2) Key-Value pairs: label and value. Example:

```js
    var data = [
        {label: 'Jan', value: 123},
        {label: 'Feb', value: 11},
        {label: 'March', value: 55},
        {label: 'April', value: 293},
        {label: 'May', value: 180},
    ];
```

## License
[MIT](LICENSE.md) (c) [Elliot Moule](https://github.com/elliotmoule)
