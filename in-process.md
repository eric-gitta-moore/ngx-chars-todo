# in-process

- [ ] Map based on D3.js + Natural Source (Implement a new map chart type with pure D3.js)
  - 需求
    - https://github.com/swimlane/ngx-charts/pull/1895
    - 脱离 leaflet，使用 TopoJSON or GeoJSON 构建地图
  - 问题
    - https://github.com/eric-gitta-moore/ngx-charts/discussions/3
      - JSON 数据对标到经纬度问题尝试用 d3-geo 中提供的墨卡托投影
      - 无极放大暂时不需要
      - 暂时不提供预设 TopoJSON，只需要在 playground 里面内置 demo
      - 使用类似 echarts 的 option 范式开发会比较方便一些，不然要 context 挺麻烦

- nested-pie