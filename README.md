# Daily-Work-In-Company-B
在B公司的日常记录
## 写在前面的话
从小到大没养成记录的好习惯，语文成绩从来都是比及格高一丢丢。近期找实习工作时回想过去的履历，零零散散，回忆不完整更不精确，甚至有很多以前做过的事情就像没做过一样的感觉，很可怕。所以新实习，新气象，开始每天的日常记录，一是为了以后需要时能翻出来用，二是为以后留个念想吧。  
懒癌晚期，因为域账号没有管理员权限，无法更新Chrome，就一直没注册成功GitHub账号，现在实习的第三周终于下了新版的火狐才开始了日常记录。  

## Week01-02（19.7.30~19.8.11）
第1、2两周也没做什么，主要就是通过文档和视频了解业务。  
先说一下我对B公司的了解（了解的应该不是很准确），B公司是个超级大的餐饮企业，供应伙伴多、人多、系统多且老，关系复杂。同时身为甲方，系统应该多是买来的，所以虽然我是IT实习生，奔着Java研发来的，但我感觉从颗粒砂石到摩天大楼的系统研发过程，在这里我是不可能经历到了。我有点失落，再加上当时我的直接主管G特别特别忙，就给文档让我慢慢看，对话不超过20句，身边没有同龄人，吃饭也没人一起，我就很莽撞的跟G提了离职。G人很好，解释说这两天太忙了，九月上新项目会带着我一起做，会教我很多东西的。  
慢慢的我开始做一些简单的运维，用户增删，权限更改，数据合并预处理等，量很小，我边做边写了SOP，方便以后交接。其它时间G让我自由了解业务，或学习知识，并给了我电子合同系统的源代码。后来认识了同事P和F，P让我接触他的系统，给了我测试环境。F给我讲解公司业务，相关技术。  
一时间，我要熟悉系统业务，同时熟悉SQL、MySQL、Oracle三大数据库，熟悉Linux操作系统，重拾Java和前端开发技能，学习spring-boot和Vue框架，学习Uibot和Uipath，学习ETL工具，有点头大，慢慢学吧。  

## week03（19.8.11~19.8.18）
### Monday
今天除了处理3月份的数据外，听了两个会，一天就过去了。一个是同事D离职工作交接，一个是EPM Vendor Introduction，都是关于EMP（Oracle Enterprise Performance Management）    
#### 同事D的工作交接：
首先介绍了一下Oracle的EMP架构；然后介绍了B公司的EMP架构；然后介绍了日常维护工作（数据导入导出，服务启停顺序）。    
主要涉及到两个软件：Hyperion Planning：基于数据，作计划预算等；Essbase多维数据库，单位是立方体（cube）。    
感觉就是Oracle公司的关系数据库上搭了个多维数据库，然后利用数据作分析和预算用。具体等看过相关文档后再补充。  
### Oracle的Hyperion Vendor Introduction分析客户、订单、店铺、财务等等数据，作数据展示，回归分析，方便预测
用户有：星巴克、麦当劳、自如等  
体会就是系统集成业务非常多，功能也很多。颗粒度可以做到每日，甚至于每个订单，但颗粒度太细的话需要进行升级软硬件等措施，提高处理速度（其中提到了数据库读写分离，麒麟巴拉巴拉，有时间了解一下）。    
还有提到了打标签问题，数据分析需要给数据打上不同的标签，比如新门店、老门店、大门店、小门店等等。可能最初数据库设计时没考虑到缺少字段，需要补。    

### Tuesday
今天上午处理4月份数据，下午是IBM TM1 Vendor Introduction  
#### IMB planning Analutics新一代计划于分析平台 汪帮本  
##### 产品介绍：前身TM1，现叫 Planning  
用户有：Amazon nike lv等    
满足企业战略财务运营层面的计划；计划预算编制人员，建立多维度业务模式和分析结果；具备协作能力替代自动化;基于电子表格的计划预算需求。    
1.个人沙箱空间测试，不会跟别人有纠纷；    
2.web端和移动端；    
3.Excel整合度高；    
4.可视化分析和报表；  
5.弹性应变能力（比如组织结构变化）；    

### Winsday
今天上午是SAP介绍BPC Vendor Introduction，下午是Jebot Vendor Introduction  
#### sap的BPC预算管理方案探讨  
用户有：永达汽车 华能集团 泸州老窖  汾酒集团 可口可乐 永辉超市  康师傅 蔚来 海底捞 融创 万科 绿地 全家 小米 清华紫光 猎豹 艾玛 广大 中车四方等  

预算管理最终目标出发，构建从预算编制到执行控制到总结分析完整的预算管理闭环  
管理角度:预算组织、制度、流程、编制、分析、控制、调整、绩效考核、目标分解、  
系统视角：性能优化，运行维护没权限管理，系统集成，安装备份迁移  
业务视角：指标体系，年度预算，战略预算，滚动预算，分析检测  

餐饮关注点：预算模式选择，业务预算，费用预算，利润运算，科目体系、组织架构、费用分摊  

sap的BPC系统要结合自家的erp等等软件，捆绑度高  

#### jedox全面预算&报表合并解决方案
用户有：宝马 福特 飞利浦 迪士尼 麦德龙 满记甜品 Seire 携程 途牛 长安 大众 横店集团 复旦大学  

预算管理最终目标出发，构建从预算编制到执行控制到总结分析完整的预算管理闭环  
管理角度:预算组织、制度、流程、编制、分析、控制、调整、绩效考核、目标分解、  
系统视角：性能优化，运行维护没权限管理，系统集成，安装备份迁移  
业务视角：指标体系，年度预算，战略预算，滚动预算，分析检测  

餐饮关注点：预算模式选择，业务预算，费用预算，利润运算，科目体系、组织架构、费用分摊  


##### 企业绩效管理系统体会
三天听了EPM四大软件商的产品介绍，第一次体会了一次招标，感受良多。    
1.企业财务部门分管对接的项目多，人员及业务复杂。财务系统也很庞大，中国上市公司与美国上市公司财务报表要求不同，报表合并冲销项仍需人工解决。    
2.企业级数据量巨大，通过数据库读写分离，多维数据库cube拆分关联，开辟内存空间计算，还有个叫麒麟的东东？？等方法来提高响应速度。    
3.实时更新会导致脏数据，固定时间更新影响正常业务进行，需要平衡。    
4.数据分析需要贴标签，抽维度，聚类，回归。    
5.初识成熟系统的庞大，前端交互，后台逻辑，底层存储，业务关系等，颗粒度很细，还要做好备份，可将数据还原到某个时间点，并且权限也应回滚，系统集成很多先进功能如画布、story、BI、数据挖掘，新流行的东西基本都做进去了。成熟团队对接一个项目，初版提交时间也要6个月，软件系统开发难啊。     
6.初识软件系统招标，见识了4个大系统，对开发的整体观念有所了解。每制作一个客制化能卖几百几千万，也是个多金行业。    
7.品类不断增加，不用了也没有删除，会占用大量资源，并拖累响应速度。    
8.成见是座大山，任你怎么努力也无法移开。    

### Thursday
今天就比较闲了，主要工作就是查找周二处理4月份数据时报错问题。其次就是提交实习工时表，终于可以拿到工资了（这个结算周期内请了一天半的假，自己给自己扣掉工资了，上司说请点假很正常，不用扣工资的，哈哈哈哈哈哈开心）。     
今天跟上司小聊了一会儿，说道如果实习做满2年的话，转正是肯定没问题的，目前工作仍是运维为主，可能涉及到的编程就是遇到小bug能修补就修补一下，但运维要学的东西也太多了，ETL工具 RPA工具，Azure，网络，域控等，B公司马上要进行IOT二期项目，带着我一起做一下。  
个人还是不太想要做两年运维实习的，趁着年轻，趁着仅剩不多的学生身份福利期，还是想多体验些公司和行业，一是在不同公司丰富见解，学到更多东西；二是找到自己的喜好，才好决定自己的终生追求。还没进过BAT呢，在B公司做1年，跟完IOT项目后我可能就要考虑去留问题了，先好好学，好好干着吧。

### Friday
今天完结了4月份数据和报表（编码出了问题，一波三折），开始处理5月份数据，下午开始学习Azure
