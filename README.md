# 前言

欢迎来到本基于Java的公寓报修管理系统的Gitee仓库！本项目是针对毕业设计的实战项目，基于Java语言开发，集成了Spring Boot框架、JavaScript、Vue、CSS3等技术。以下将为您详细介绍本项目的相关内容。

# 内容介绍

本公寓报修管理系统旨在为公寓管理人员提供一个便捷、高效的管理平台，实现报修工单的在线提交、派单、进度跟踪等功能。系统主要包括以下模块：用户模块、报修模块、工单模块、管理员模块等。通过本系统，可以大大提高公寓报修工作的效率，降低管理成本。

# 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

# 核心代码

以下为一段关于报修功能的核心代码：

```java
@RestController
@RequestMapping("/api/repair")
public class RepairController {

    @Autowired
    private RepairService repairService;

    @PostMapping("/submit")
    public ResponseEntity<?> submitRepair(@RequestBody Repair repair) {
        repairService.submitRepair(repair);
        return ResponseEntity.ok("报修成功！");
    }
}
```

# 免费源码获取

```
8000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/325661/16/4464/107448/689db5e5F0e61a895/eb01fab8489356b4.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/316873/27/24953/43895/689db5cbF172296bc/0335d15ac0b12fa6.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/306921/9/26703/47224/689db5cbF5ca90d7c/c89d894aabcee669.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/311177/24/26415/33600/689db5ccF8ef9cb4e/13ddbd62b50ee691.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/321144/30/24578/56938/689db5ccF41d76cc4/ed0b0facf9058ea7.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/326984/9/4469/47880/689db5cdFb67c9c97/05e4e9cb917dd38b.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/324736/37/4587/25071/689db5cdF428208a1/28728be989d25586.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/309364/19/26438/74500/689db5ceFe0712c54/ec29763a343c95ea.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/328920/21/4551/44410/689db5ceFf2bca7fa/ea0d29eb0765176b.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/321438/2/25097/88387/689db5cfF324d92d6/b8c2f213a287660a.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
