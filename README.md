# CXFHY-Flow-visualization
创新孵化云流量可视化平台
# 预览
![image](https://github.com/ChinaUnicomRI/CXFHY-Flow-visualization/blob/master/index.png)
# 技术栈
- html
- CSS
- JavaScript
- ECharts
- leaflet
# 部署
- 网络中待监控节点交换机开启sflow agent
- 搭建ELK数据分析环境
- 将sflow数据发送到ELK进行处理
# 接口
- 前后台之间采用json格式进行数据传输，编码采用unicode编码，ELK向前端开发数据查询接口，前端每隔固定周期向ELK查询目前的流量情况。
