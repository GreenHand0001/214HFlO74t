# 前言

大家好，今天我要分享的是一个基于SpringBoot的医院药品管理系统。这是一个适用于毕业设计的实战项目，使用Java语言开发，搭配MySQL数据库，前端采用JS、Vue和CSS3技术。本项目不仅包含了完整的源码和文档报告，还有详细的代码讲解，帮助大家更好地理解和学习。

# 内容介绍

本项目主要针对医院药品管理进行设计，旨在提高药品管理的效率和准确性。系统主要包括以下几个模块：药品信息管理、库存管理、供应商管理、采购管理、销售管理等。通过这些模块，可以实现对药品的全面管理，包括药品的采购、入库、出库、销售、库存预警等功能。

# 技术介绍

## 语言：Java
## 使用框架：Spring Boot
## 前端技术：JS、Vue、CSS3
## 开发工具：IDEA/Eclipse
## 数据库：MySQL 5.7/8.0
## 数据库管理工具：phpstudy/Navicat
## JDK版本：jdk1.8
## Maven: apache-maven 3.8.1-bin
## 前端环境：Node.Js 12\14\16

# 核心代码

以下是本项目中的一段核心代码，展示了如何使用Spring Boot实现药品信息的查询功能：

```java
@RestController
@RequestMapping("/drug")
public class DrugController {

    @Autowired
    private DrugService drugService;

    @GetMapping("/list")
    public ResponseEntity<List<Drug>> listDrugs() {
        List<Drug> drugs = drugService.listDrugs();
        return ResponseEntity.ok(drugs);
    }
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/304346/6/24109/172219/689ddfafF3c17d0de/a9b4720e8ee664a9.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/311221/38/26533/110547/689ddf98F6d03086c/53fbba44cbefefc3.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/313016/18/26412/74030/689ddf98Ff4ae4044/66ca3bda27f7ce27.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/308307/13/26314/49905/689ddf99Fd4564dd2/d5a26a3782567456.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/310047/8/26225/52912/689ddf99Fa53e3a5a/7becc2b08338e74c.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/307342/25/26327/49713/689ddf9aF7902b09e/9e4d8d4bbc8c71b1.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/310065/37/26715/62706/689ddf9aF14888bad/b75d552265dd5360.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/313947/13/26187/48732/689ddf9bFac6e2670/098e92834b2940d8.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/313549/31/26522/48720/689ddf9bFfd991301/515ba2c3a130cc21.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/316427/20/26263/64590/689ddf9cF6025ef01/77a3701def214a07.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
