# 基于规则的SQL审核工具
## 团队：betterdb

## 项目介绍
一款基于规则的事前SQL审核工具

## 背景
业务SQL语句存在不符合SQL规范，或者不够优化的问题
审核业务SQL语句，发现不规范的语句并给出优化建议

## 项目设计
1. 基于tidb parser对SQL语句进行解析
2. 筛选出不符合规则的SQL语句
3. 基于规则列表的动态开关
4. 审核结果存储到tidb中
