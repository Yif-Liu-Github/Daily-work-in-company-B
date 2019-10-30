# Daily-Work-In-Company-B
在B公司的日常记录
## 写在前面的话
从小到大没养成记录的好习惯，语文成绩从来都是比及格高一丢丢。近期找实习工作时回想过去的履历，零零散散，回忆不完整更不精确，甚至有很多以前做过的事情就像没做过一样的感觉，很可怕。所以新实习，新气象，开始每天的日常记录，一是为了以后需要时能翻出来用，二是为以后留个念想吧。  
懒癌晚期，因为域账号没有管理员权限，无法更新Chrome，就一直没注册成功GitHub账号，现在实习的第三周终于下了新版的火狐才开始了日常记录。  

## Week01-02（19.7.30~19.8.11）
第1、2两周也没做什么，主要就是通过文档和视频了解业务。  
先说一下我对B公司的了解（了解的应该不是很准确），B公司是个超级大的餐饮企业，供应伙伴多、人多、系统多且老，关系复杂。同时身为甲方，系统应该多是买来的，所以虽然我是IT实习生，奔着Java研发来的，但我感觉从颗粒砂石到摩天大楼的系统研发过程，在这里我是不可能经历到了。我有点失落，再加上当时我的直接主管G特别特别忙，就给文档让我慢慢看，对话不超过20句，身边没有同龄人，吃饭也没人一起，我就很莽撞的跟G提了辞职。G人很好，解释说这两天太忙了，九月上新项目会带着我一起做，会教我很多东西的。  
我开始接手一些简单的运维，用户增删，权限更改，数据合并预处理等，量不多，但是繁琐耗时，我边做边写了SOP，方便以后交接。其它时间G让我自由了解业务，或学习知识，并给了我电子合同系统的源代码。后来认识了同事P和F，P让我接触他的系统，给了我测试环境。F给我讲解公司业务，相关技术。  
一时间，我要熟悉系统业务，学习Linux操作系统，重拾SQL、MySQL、Oracle数据库，Java和前端开发技能，拓展学习Uibot、Uipath和ETL工具，有点头大，既然有事可做了，那就开始做吧。  

## week03（19.8.11~19.8.18）
第3周小结。
  1.处理完了3,4月份的数据，开始5月份数据处理，修复报错，学习使用ETL工具进行数据整理迁移；  
  2，参与B公司财务EMP系统的招标会，听取4家行业领头企业介绍自家产品，体验了招标会，涨了财务系统的见解。  
  3.开始试用学习azure。
### Monday
今天除了处理3月份的数据外，听了两个会，一天就过去了。一个是同事D的离职工作交接，一个是EPM Vendor Introduction。
#### 同事D的工作交接：
首先介绍了一下Oracle的EMP产品；然后介绍了B公司的EMP架构；最后介绍了日常维护工作（数据导入导出，服务启停顺序）。    
主要涉及到两个软件：Hyperion Planning：基于数据，作计划预算等；Essbase多维数据库，单位是立方体（cube）。    
#### Oracle的Hyperion Vendor Introduction
用途：分析客户、订单、店铺、财务等等数据，作数据展示，回归分析，方便预测。  
用户有：星巴克、麦当劳、自如等等  
体会就是系统集成业务非常多，功能也很多。颗粒度可以做到每日，甚至于每个订单，但颗粒度太细的话需要进行升级软硬件等措施，以提高处理速度（其中提到了数据库读写分离，麒麟巴拉巴拉，有时间了解一下）。        

### Tuesday
今天上午处理4月份数据，下午是IBM TM1 Vendor Introduction  
#### IMB planning Analutics新一代计划于分析平台 汪帮本  
##### 产品介绍：前身TM1，现叫 Planning  
用途：满足企业战略财务运营层面的计划；计划预算编制人员，建立多维度业务模式和分析结果；具备协作能力替代自动化;基于电子表格的计划预算需求。    
用户有：Amazon nike lv等    
1.个人沙箱空间测试，不会跟别人有纠纷；    
2.web端和移动端；    
3.Excel整合度高；    
4.可视化分析和报表；  
5.弹性应变能力（比如组织结构变化）；    

### Wednesday
今天上午是SAP介绍BPC Vendor Introduction，下午是Jebot Vendor Introduction  
#### sap的BPC预算管理方案探讨  
用户有：永达汽车 华能集团 泸州老窖  汾酒集团 可口可乐 永辉超市  康师傅 蔚来 海底捞 融创 万科 绿地 全家 小米 清华紫光 猎豹 艾玛 广大 中车四方等  

预算管理最终目标出发，构建从预算编制到执行控制到总结分析完整的预算管理闭环  
管理角度:预算组织、制度、流程、编制、分析、控制、调整、绩效考核、目标分解、  
系统视角：性能优化，运行维护没权限管理，系统集成，安装备份迁移  
业务视角：指标体系，年度预算，战略预算，滚动预算，分析检测  

sap的BPC系统要结合自家的erp等等软件，捆绑度高  

#### jedox全面预算&报表合并解决方案
用户有：宝马 福特 飞利浦 迪士尼 麦德龙 满记甜品 Seire 携程 途牛 长安 大众 横店集团 复旦大学  

预算管理最终目标出发，构建从预算编制到执行控制到总结分析完整的预算管理闭环  
管理角度:预算组织、制度、流程、编制、分析、控制、调整、绩效考核、目标分解、  
系统视角：性能优化，运行维护没权限管理，系统集成，安装备份迁移  
业务视角：指标体系，年度预算，战略预算，滚动预算，分析检测  


#### 企业绩效管理系统体会
三天听了EPM四大软件商的产品介绍，第一次参与招标会，感受良多。    
1.企业财务部门分管对接的项目多，人员及业务复杂。财务系统也很庞大，中国上市公司与美国上市公司财务报表要求不同，报表合并冲销项仍需人工解决。    
2.企业级数据量巨大，通过数据库读写分离，多维数据库cube拆分关联，开辟内存空间计算，还有个叫麒麟的东东？？等方法来提高响应速度。    
3.实时更新会导致脏数据，固定时间更新影响正常业务进行，需要平衡。    
4.数据分析需要贴标签，抽维度，聚类，回归，哈哈哈上课有学过。    
5.初识成熟系统的庞大，前端交互，后台逻辑，底层存储，业务关系等，颗粒度很细，还要做好备份及日志，可将数据还原到某个时间点，并且权限也应回滚，系统集成很多先进功能如画布、story、BI、数据挖掘，新流行的东西基本都做进去了。成熟团队对接一个项目，初版提交时间也要6个月，软件系统开发难啊。     
6.初识软件系统招标，见识了4个大系统，对开发的整体观念有所了解。每制作一个客制化能卖几百几千万，也是个多金行业。    
7.产品品类不断增加，不用了也没有删除，占用了大量资源，导致响应速度越来越慢。    
8.餐饮关注点：预算模式选择，业务预算，费用预算，利润运算，产品科目体系、组织架构、费用分摊。  

### Thursday
今天就比较闲了，主要工作就是查找周二处理4月份数据时报错问题。其次就是提交实习工时表，终于可以拿到工资了（这个结算周期内请了一天半的假，自己给自己扣掉工资了，上司说请点假很正常，不用扣工资的，哈哈哈哈哈哈开心）。     
今天跟上司小聊了一会儿，说道如果实习做满2年的话，转正是肯定没问题的，目前工作仍是运维为主，可能涉及到的编程就是遇到小bug能修补就修补一下，但运维要学的东西也很多，ETL工具 RPA工具，Azure，网络，域控等，B公司马上要进行IOT二期项目，到时候带着我一起做。  
个人还是不太想要做两年运维实习的，趁着年轻，趁着仅剩不多的学生身份福利期，还是想多体验些公司和行业，一是在不同公司丰富见解，学到更多东西；二是找到自己的喜好，才好决定自己的终生追求。还没进过BAT呢，在B公司做1年，跟完IOT项目后我可能就要考虑去留问题了，先好好学，好好干着吧。

### Friday
今天完结了4月份数据和报表（编码出了问题，一波三折，总算是没出乱子），接着就开始处理5月份数据。  
下午注册了azure试用账号，开始Azure的学习，看了虚机的创建，硬盘和网络的创建配置，这让我回想起了在微软实习的经历，想起了在那里学习的虚机，域控和私有云VMASS，所以对Azure这套东西不是很陌生，直接上手了。因为买公有云太贵了，B公司自有很多服务器，只是缺乏管理，所以上司G构想给B公司搭建一套私有云，就在看开源项目rainbond,然后我也挺感兴趣的，因为知道那套管理系统的复杂程度之高，也深刻体会到了它的管理便捷性，如果能自己尝试一点点的实现它，也是超级有成就感的事情了。

## week04（19.8.19~19.8.23）
第四周请了两天假处理点私事，工作上就是完成日常运维（5、6月数据和报表），没有学习也没有提高！堕落了。

## week05（19.8.26~19.8.30）

处理7月份数据和报表,看完azure基础教学;精改IOT二期项目PPT;开始学习azureIOT和rainbond私有云搭建，门外汉什么都不懂，所以先了解一些概念定义：
1. UGC、PGC和OGC：  
+ UGC（User-generated Content，用户生产内容，也称UCC，User-created Content）
+ PGC（Professionally-generated Content，专业生产内容，也称PPC，Professionally-produced Content）
+ OGC（Occupationally-generated Content，职业生产内容）。

2.ProcFile：程序文件

3.Nosql：[简介&教程](https://www.runoob.com/mongodb/nosql.html)

4.nginx：Apache很好的替代品，是一个高性能的HTTP和反向代理web服务器，同时也提供了IMAP/POP3/SMTP服务。

5.plugin：插件、外挂

6.Docker:应用容器引擎,让开发者可以打包他们的应用以及依赖包到一个可移植的镜像中，然后发布到任何流行的 Linux或Windows 机器上，也可以实现虚拟化。容器是完全使用沙箱机制，相互之间不会有任何接口。

7.kubernetes：简称K8s，是一个开源的，用于管理云平台中多个主机上的容器化的应用，Kubernetes的目标是让部署容器化的应用简单并且高效（powerful）,Kubernetes提供了应用部署，规划，更新，维护的一种机制。

8.LXC：Linux Container容器是一种内核虚拟化技术，可以提供轻量级的虚拟化，以便隔离进程和资源。

9.etcd：随着CoreOS和Kubernetes等项目在开源社区日益火热，它们项目中都用到的etcd组件作为一个高可用强一致性的服务发现存储仓库，渐渐为开发人员所关注。在云计算时代，如何让服务快速透明地接入到计算集群中，如何让共享配置信息快速被集群中的所有机器发现，更为重要的是，如何构建这样一套高可用、安全、易于部署以及响应快速的服务集群，已经成为了迫切需要解决的问题，etcd为解决这类问题带来了福音。

## week06（19.9.2~19.9.6）
日常运维case处理；处理8月份数据和报表；看rainbond用户手册
### Monday
开始处理8月份数据和报表， 并做了三个添加用户、权限管理的case。接着看rainbond等。
### Tuesday
8月份数据报错，修错；看文档概念定义。
1. Hadoop：Hadoop实现了一个分布式文件系统（Hadoop Distributed File System），简称HDFS。HDFS有高容错性的特点，并且设计用来部署在低廉的（low-cost）硬件上；而且它提供高吞吐量（high throughput）来访问应用程序的数据，适合那些有着超大数据集（large data set）的应用程序。HDFS放宽了（relax）POSIX的要求，可以以流的形式访问（streaming access）文件系统中的数据。

2. ZooKeeper：

3.RAID：磁盘阵列（Redundant Arrays of Independent Drives，RAID），有“独立磁盘构成的具有冗余能力的阵列”之意。磁盘阵列是由很多块独立的磁盘，组合成一个容量巨大的磁盘组，利用个别磁盘提供数据所产生加成效果提升整个磁盘系统效能。利用这项技术，将数据切割成许多区段，分别存放在各个硬盘上。

4.。。。

## week07（19.9.9~19.9.12）  
日常运维case处理；处理9月份数据；尝试在azure上部署云帮  
1. 操作azure在不同site部署windows虚机（部署到国外的话，访问是真的慢），每一个site都有配置限额，基本上一个site只能部署一个像样点的虚机。    
2. 创建linux虚机，ssl连接并使用一些常用指令。  
3. 配置azure网络组，子网、端口等。  
4. 在azure的创建Ubuntu虚机，并安装单节点rainbond。  

## week08（19.9.16~19.9.20）
日常运维case处理；azure上部署云帮成功；学习Linux系统。    
1. 成功部署单节点rainbond，并跑通了示例2048小游戏。    
2. 创建多个虚机，构建rainbond集群，成功创建管理节点，计算节点双节点的rainbond集群。    
演示给上司G看后，上司蛮高兴的，加快了rainbond测试物理服务器的申请。  
## week09（19.9.23~19.9.27）
日常运维case处理；等待rainbond物理机；用UiPath帮frank、nijie解决日常繁琐业务流程。  
本周重点学习和应用UIpath帮frank写了个自动化流程，利用rap机器人自动进行每个月的处理，包含读取excel获得待处理名单，在web系统里挨个执行，最后发送邮件。极大提升frank工作效率与准确率，被推荐给ITteam编写几个流程并指导使用UIpath。  
## week10（19.9.30~19.10.4）
放假  

## week11（19.10.7~19.10.11）
日常运维case处理；处理rainbond部署问题；处理UIpath业务问题。

## week12（19.10.14~19.10.18）
处理9月份报表，日常运维case处理，尝试本地部署EContract。  
linux、rainbond、UIpath、java还有论文到处碰壁，严重打击自信心，怀疑自己。“自己这个东西是看不见的，撞上一些别的什么，反弹回来，才会了解自己。”
处理rainbond安装故障问题，最终平台安装成功。
参与苏州site的rpa需求讨论

## week13（19.10.21~19.10.25）
解决rainbond运行故障问题
### Monday
协助天津site完成第一个rpa流程

### Tuesday
上午：参与沈阳site的rpa需求讨论
下午：IOT项目二期启动会

### Wednesday
一天的 iot需求洽谈会。
冷风机、压缩机、冷气

### Tuesday
解决rainbond的K8s问题，现仅就差域名解析问题了，申请一个新域名。
做UIPath培训ppt，制作“猜数字”演示游戏。
协助部分site解决UIpath应用问题。
和同事F、同事P沟通RPA事宜，交接相关工作。
晚上加班完成了“在线检疫申报”案例演示，培训PPT，以及沈阳site维保流程的解答
### Friday
UIpath培训PPT整修，以及线上培训。
同事P开始交接日常运维工作给我了，正式事从三个主管了，感觉事情有些多了，不能再某个方面精进了，下班后还要看论文，学英语，有些手忙脚乱了。

## week14（19.10.28~19.11.1）
### Monday
1. 成功为rainbond申请到内网域名，创建新应用绑定域名后成功访问。
2. 开始在rainbond上部署EC，重温了SVN的命令及操作指南，成功将本地代码传至svn服务器。
3. 尝试将EC项目代码直接传至svn后进行部署，部署失败。
4. 尝试将EC项目打包成war包后，传至svn进行部署，部署失败。
5. 解答UiPath的问题咨询。
### Tuesday
1. rainbond部署EC失败，测试将git上的官方demo下载，上传到内网svn上，还是部署失败，所以是svn的问题而非代码。经排查日志journalctl -fu rbd-chaos确定rainbond服务器无法访问SVN服务器，已向上申请访问权限。
2. 获L3级工程师权限，正式帮助同事P处理生产环境中的LPS事宜，解决删除订单，导出订单2个case，剩余1个case待下周执行。
### Wednesday
1. 处理运输管理系统case
2. SVN服务器访问申请修改
3. 学习UiPath文档
