# 基于SpringBoot+Vue3的社区健康档案管理系统

![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![Vue3](https://img.shields.io/badge/-Vue3-grey?style=flat-square) ![ElementPlus](https://img.shields.io/badge/-ElementPlus-grey?style=flat-square) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) 

## 项目介绍

一个面向社区卫生服务中心的健康档案数字化管理平台，支持管理员、医生、居民三种角色。实现了居民健康档案的全生命周期管理，涵盖建档、体检、慢性病跟踪、随访计划、就诊记录、健康宣教等核心业务。

## 功能模块

- **用户管理**：三角色权限控制（管理员/医生/居民），支持实名认证审核，按角色分类展示
- **健康档案**：居民基本信息建档、档案详情查看与编辑，覆盖各年龄段
- **健康服务**：体检记录管理、随访记录管理、就诊记录管理
- **慢性病管理**：慢性病登记、随访计划制定、健康指标持续监测
- **健康宣教**：健康教育文章发布与管理、知识库浏览
- **统计分析**：首页数据概览、性别分布、年龄分布、慢性病类型分布图表
- **消息通知**：系统消息推送与管理
- **居民端**：个人档案查看、体检报告、就诊记录、随访记录

## 技术架构

- **后端**：Spring Boot 2.7.18 + MyBatis-Plus 3.5.3.1 + JWT 认证
- **前端**：Vue 3.5 + Element Plus 2.13 + Vite 7 + ECharts 6 + Pinia
- **数据库**：MySQL 8.0

<!-- screenshots-start -->
## 系统截图

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/commhealth/01-%E7%99%BB%E5%BD%95%E9%A1%B5%E9%9D%A2.png" alt="01-登录页面" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/commhealth/02-%E9%A6%96%E9%A1%B5%E6%A6%82%E8%A7%88.png" alt="02-首页概览" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/commhealth/03-%E7%94%A8%E6%88%B7%E7%AE%A1%E7%90%86.png" alt="03-用户管理" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/commhealth/04-%E5%81%A5%E5%BA%B7%E6%A1%A3%E6%A1%88.png" alt="04-健康档案" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/commhealth/05-%E6%85%A2%E6%80%A7%E7%97%85%E7%AE%A1%E7%90%86.png" alt="05-慢性病管理" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/commhealth/06-%E4%BD%93%E6%A3%80%E8%AE%B0%E5%BD%95.png" alt="06-体检记录" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/commhealth/07-%E5%81%A5%E5%BA%B7%E5%AE%A3%E6%95%99.png" alt="07-健康宣教" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/commhealth/08-%E6%88%91%E7%9A%84%E6%A1%A3%E6%A1%88.png" alt="08-我的档案" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/commhealth/UML%E5%9B%BE%E5%88%97%E8%A1%A8.png" alt="UML图列表" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/commhealth/%E8%AE%BA%E6%96%87%E5%9B%BE1.png" alt="论文图1" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/commhealth/%E8%AE%BA%E6%96%87%E5%9B%BE2.png" alt="论文图2" width="600" />

<!-- screenshots-end -->

## 接毕业设计和论文

### 作者微信：vvsgxmn  (支持修改、 部署调试、 支持代做毕设)

### 接网站建设、小程序

### 选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt 都可以做

### 购买地址：[https://www.vvxx.love](https://www.vvxx.love)（vv毕设网）

### 支持 **一键生成 UML 图**：上传项目压缩包即可自动产出功能模块图、用例图、流程图、E-R 图、时序图等全套毕设图表。

### 提供 **免费配套软件下载 + 安装说明 + 部署教程**

![vv毕设网 - 一键画图](https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/uml-draw.png)

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/image-20260825133349317.png" alt="image-20260825133349317" />

⚠️ Bug添加微信**免费修复**，免费修复。其他平台的私信一律不管（微信方便发送文件）
