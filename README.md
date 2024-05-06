# todo-ngx-chars

<p align='center'><strong>Official Repo https://github.com/swimlane/ngx-charts</strong></p>

### Improvement

- (https://github.com/swimlane/ngx-charts/pull/1905) X/Y Axis Label
  - [x] Max length
  - [x] enable trim
  - [x] enable wrap
  - [x] Tooltip
- Animation
  - [x] animated transitions between common statistical data graphics (http://vis.berkeley.edu/papers/animated_transitions/)
    - [x] Stacked-to-grouped bars (https://observablehq.com/@d3/stacked-to-grouped-bars)

- [x] Heat Map doesn't support custom color
  - 这个问题不存在，可以直接修改 props 中的 `scheme`

### Customization

- [x] Chart overlay customization & style
- Custom marker
  - [ ] Map Chart
    - https://observablehq.com/@d3/stacked-to-grouped-bars
    - https://observablehq.com/@d3/kernel-density-estimationOr
    - https://github.com/swimlane/ngx-charts/pull/1895
  - other chart types
    - [x] show bubble (size represents value weight)
- Custom series style
  - [x] Line chart style customizaation
  - [x] (https://github.com/swimlane/ngx-charts/pull/1907) Curve fitting （平滑处理）(Line/Area)
    - Curve Fitting, smoothing https://swimlane.github.io/ngx-charts/#/ngx-charts/combo-chart
      - https://observablehq.com/@d3/kernel-density-estimation （bar-line combo，transparency）


### Action

- [x] (https://github.com/swimlane/ngx-charts/pull/1903) Export as an image

### New Feature

- [ ] Map based on D3.js + Natural Source (Implement a new map chart type with pure D3.js)
  - https://github.com/swimlane/ngx-charts/pull/1895
- [x] (https://github.com/swimlane/ngx-charts/pull/1917) Chart combination (share data between line & pie): https://echarts.apache.org/examples/en/editor.html?c=dataset-link
- [x] (https://github.com/swimlane/ngx-charts/pull/1919) Calendar(heat map/pie): https://echarts.apache.org/examples/en/editor.html?c=calendar-pie
