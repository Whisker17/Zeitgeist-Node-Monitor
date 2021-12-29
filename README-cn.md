# Zeitgeist 节点监控程序

[![Telegram Group](https://cdn.rawgit.com/Patrolavia/telegram-badge/8fe3382b/chat.svg)](https://t.me/zeitgeistchina) &nbsp;&nbsp; &nbsp; &nbsp; [![Discord](https://img.shields.io/badge/discord-join%20chat-blue.svg)](https://discord.com/invite/xv8HuA4s8v)

[中文版](https://github.com/Whisker17/Zeitgeist-Node-Monitor/blob/main/README-cn.md) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; [English](https://github.com/Whisker17/Zeitgeist-Node-Monitor/blob/main/README.md)

Zeitgeist 节点监控程序为 Zeitgeist 节点运营商提供一个可视化节点监控平台，基于 [Grafana](https://github.com/grafana/grafana) 以及 [Prometheus](https://github.com/prometheus/prometheus) 设计，旨在给节点运营商一个易用直观的节点信息体现。我们预先设计了一个[仪表盘](https://grafana.com/grafana/dashboards/15424)来可视化部分关键信息，同样我们也支持自己定制化仪表盘来监控个人所需的数据。

## 开始部署

Zeitgeist 节点发布信息：https://github.com/zeitgeistpm/zeitgeist/releases

大家可以通过[这篇文章](./how-to-monitor-node-cn.md)来进行节点监控程序的部署。

## 定制化接口

除了我们预先设计好的仪表盘中的数据，您还可以通过添加或者删除接口来对仪表盘进行定制化。我们在这里提供了一份目前 Zeitgeist 节点支持的[接口文档](./metrics.md)。
