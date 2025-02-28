#BTC Volume Comparison ratio 
#BTC交易所成交量比较指标

## 简介
这是一个用于比较不同加密货币交易所BTC交易量的TradingView指标。该指标通过计算各大交易所与Binance的成交量比值，帮助交易者了解不同交易所之间的交易活跃度差异。

基于白酒哥（@Felix_Hsu）的推文：https://x.com/Felix_Hsu/status/1894970269535813959

## 功能特点
- 支持5个主要加密货币交易所的数据比较：
  - Binance (基准交易所)
  - Coinbase
  - OKX
  - Bitfinex
  - Bybit
- 实时显示各交易所与Binance的成交量比值
- 直观的图表展示，包含不同颜色的曲线标识
- 右上角实时数据表格显示

## 使用方法
1. 将指标添加到TradingView图表中
2. 指标会自动在图表下方显示成交量比值曲线
3. 观察右上角的数据表格，可以看到实时的量差比数据
4. 基准线（值为1）表示与Binance相同的成交量水平

## 数据解读
- 当比值 > 1：表示该交易所成交量大于Binance
- 当比值 = 1：表示该交易所成交量等于Binance
- 当比值 < 1：表示该交易所成交量小于Binance
- 当比值 = na：表示数据无效（通常是因为Binance成交量为0）

## 图表说明
- 蓝色线：Coinbase/Binance比值
- 白色线：OKX/Binance比值
- 绿色线：Bitfinex/Binance比值
- 橙色线：Bybit/Binance比值
- 虚线：基准线（1.0）和零线（0.0）

## 应用场景
- 分析不同交易所的市场活跃度
- 寻找潜在的套利机会
- 评估交易所流动性差异
- 监控异常交易活动
- 用于判断价格反转

## 作者
- 作者：Sumin
- 版本：v1
