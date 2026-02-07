## 前言

随着互联网技术的发展，企业信息化管理需求日益增强。在企业人力资源管理的诸多环节中，薪资管理是非常重要的一环。为了便于企业职工随时查询个人薪资信息，我们基于微信小程序开发了一套企业职工薪资查询系统。本项目使用SSM框架（Spring、SpringMVC、MyBatis）进行开发，前端采用JS、Vue、CSS3等技术，实现了企业职工薪资的便捷查询。

## 内容介绍

本项目主要针对企业职工薪资查询的需求，提供了一套基于微信小程序的解决方案。系统具有以下特点：

1. 界面简洁，操作便捷，便于职工快速查询薪资信息；
2. 采用SSM框架，确保系统的高效、稳定运行；
3. 支持多种查询条件，如按月份、部门等；
4. 数据实时更新，保证薪资信息的准确性。

## 技术介绍

- 语言：Java
- 使用框架：Spring、SpringMVC、MyBatis，微信小程序
- 前端技术：JS、Vue、CSS3，Uniapp
- 开发工具：IDEA/Eclipse，Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下为薪资查询接口的核心代码：

```java
@RestController
@RequestMapping("/salary")
public class SalaryController {

    @Autowired
    private SalaryService salaryService;

    @GetMapping("/query")
    public ResponseEntity<List<Salary>> querySalary(@RequestParam String empId, @RequestParam String month) {
        List<Salary> salaryList = salaryService.querySalary(empId, month);
        return new ResponseEntity<>(salaryList, HttpStatus.OK);
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/345280/32/2993/79072/68c5a999F5061a183/a49f5f51eb10ff6e.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/346743/3/3078/11542/68c5a971F9412f144/92c883805a974548.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/330189/31/12960/11385/68c5a971Fb9cc891d/9f25a8204be22eb7.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/334639/26/12792/23634/68c5a972F707cbf44/bc542f913977a970.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/344038/21/3133/17091/68c5a972F5fe42866/8bdb7b551b897b77.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/330727/3/13011/30125/68c5a973Fb5df756f/1c3f420426faa6e8.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/341811/26/2958/20670/68c5a973F084b376c/822fd90df11e86c2.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/345896/9/3071/32398/68c5a974Fc63ff965/c9d7fb0f64bf567e.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/336317/29/10472/27249/68c5a974F26765440/32e258a955a53741.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/351114/11/2979/47235/68c5a974F5d067b2c/fce29220fd0547c6.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
