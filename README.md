# 云

IaaS指提供系统（可以自己选）或者储存空间之类的硬件，软件要自己手动装；PaaS提供语言环境和框架（可以自己选）；SaaS只能使用开发好的软件（卖软件本身）；BaaS一般类似于非关系数据库，但各家不通用，有时还有一些其它东西。

## 其他人的集合

* https://education.github.com/pack GitHub学生包，需用教育邮箱验证。各种福利，可从DigitalOcean上手
* https://github.com/ripienaar/free-for-dev 本文尽量不与此项目重复
* https://github.com/AchoArnold/discount-for-student-dev
* https://github.com/ivmm/Student-resources
* https://www.freeforstudents.org/
* https://github.com/255kb/stack-on-a-budget
* https://github.com/Ibexoft/awesome-startup-tools-list
* https://www.cokemine.com/
* https://freestuff.dev/

## Paas

* https://www.heroku.com/ java go py docker。国内访问不佳。现在没有免费的了
* https://fly.io/docs/pricing/ py node go 静态，感觉很完美
* https://www.deta.sh/ py3.9 node14 内存128MB，依赖250MB，支持定时任务。有类dict数据库和10GB存储且可独立使用
* https://www.pythonanywhere.com/ 限制非常多，免费账户不允许访问白名单之外的网站。但好歹能提供一个自动https的web app
* https://www.divio.com/ docker
* https://render.com/ 曾经免费plan只有静态网页，现在提供service和database了。有node py go pg
* https://www.clever-cloud.com/en/pricing 看介绍送20€，但应该只会送一次，可以用4个月；数据库好像有完全免费的
* https://cloud.google.com/appengine/docs/ 标准环境有一点储存空间和流量，要求启用API即要求绑卡，柔性环境(.NET)必须启用结算。国内无法访问
* https://clustered.com/pricing 现在只免费14天，永久免费的plan还没出，但至少从2020年11月就是这样了
* https://www.koyeb.com docker node py go，首页被RST
* https://railway.app/ node py go java，用了类似于heroku的buildpacks，RST
* https://qoddi.com/
* https://appwrite.io/cloud 至少从2021年10月就说有了，但一直没出
* https://adaptable.io/ node py go
* https://appliku.com/ django 可能直接打不开

### .net

* https://freeasphosting.net/ 网站说了一大堆学习的东西，不过说支持.NET5
* https://www.gearhost.com/ 看起来比较好，支持3.1。还支持PHP7和node。现在开了CF屏蔽大陆IP
* https://order.aspify.com/en/freehosting/ 100MB硬盘100MB数据库，支持5。但之前不让注册说服务在中国不可用
* https://somee.com/ 被墙了，且IP被封了
* https://www.myasp.net/hosting_plans 免费两个月但好像能免费续期

## 云端空间/IDE

* https://cloudstudio.net VSC，服务器在上海，每月免费1000分钟=16.7小时，4G内存，8G硬盘（但/tmp很大）
* https://mydev.csdn.net/product/ide/dashboard 与coding的非常类似，目前每月免费5000分钟。没有cpptools
* https://www.gitpod.io/ VSC，免费版每月50小时，支持在本地打开；专业版在学生包里免费6个月但要求Primary Email是学校的账户
* https://repl.it/ 有免费版，专业版在学生包里免费3个月。支持许多语言，支持类Heroku的hosting，只要监听0.0.0.0上任意端口即可。自带kv数据库。配置文件为隐藏的.replit和nix，内容参考configuring-repl
* GitHub Codespaces：可能收费，目前个人版暂时是免费的
* https://workspaces.openshift.com/ 魔改VSC，不支持扩展，国内访问慢；之前是codenvy和che.openshift.io
* https://paiza.cloud/en/ 日产，好像还支持SSH连上去
* https://codetasty.com/
* https://next.tech/ 学生包中有
* https://ide.goorm.io/pricing 可以建立五个工作区，可以用SSH连上去。好像是自制的，界面完成度蛮高的，有终端，但没有intellisense，只能玩玩。好像可以运行docker容器？
* https://www.tutorialspoint.com/codingground.htm http://codepad.org/ https://ideone.com/ https://coliru.stacked-crooked.com/ https://wandbox.org/ https://tio.run https://code.xueersi.com/ide/code/1 https://jsrun.net/ https://www.jdoodle.com/ https://rextester.com/  https://ide.progman.in https://glot.io/ 无需登录，能执行许多语言，但只能说能运行代码，称不上IDE。https://www.codiva.io 有一点intellisense
* https://www.keil.arm.com/
* https://www.jetbrains.com/zh-cn/space/
* https://lightly.teamcode.com/ 国产，新出的

### 前端在线IDE

* https://jsbin.com 简洁，无需注册，开源。国内搭建的：https://code.h5jun.com http://http://js.jirengu.com
* https://codepen.io/ 可不注册
* https://stackblitz.com/
* https://codesandbox.io/
* https://bit.dev/ RST
* https://runkit.com 类似于jupyter notebook，也能创建api，以及把js的codeblock变得可运行
* https://www.codeply.com/
* https://plnkr.co/ 比较简陋
* https://jsfiddle.net/ 我这里打不开，且感觉是他们封的我们

### Jupyter Notebook/Lab 大数据机器学习平台

* https://colab.research.google.com/ 有免费gpu额度，国内无法直接打开。免费版无终端
* https://tianchi.aliyun.com/notebook-ai/home 免费gpu 60小时/年。登录要用阿里云账号，不想记住密码，每次都要用手机扫很麻烦，有时还要短信二次验证
* https://aistudio.baidu.com/aistudio/projectoverview/private 内存8G，磁盘100G，work目录永久保存，实名认证有一些GPU资源；长时间不用无法自动重连
* https://www.kaggle.com 验证电话后有免费gpu和外网，能连续运行9小时，有机器学习的教程
* https://www.heywhale.com/home/project 国产
* https://datalore.jetbrains.com/
* https://cocalc.com/doc/jupyter-notebook.html
* https://jupyter.org/try 官方，资源非常少，有C++；mybinder可以从GitHub仓库建立临时NB
* ~~https://kogence.com/app/landing/pricing~~
* https://deepnote.com 免费额度750小时，5G空间
* https://www.dclab.run/project_list.html 国产
* https://software.intel.com/content/www/cn/zh/develop/tools/devcloud.html
* https://lab.datafountain.cn/ 国产，CCF
* https://www.datacastle.cn 国产

## 数据库DBaaS

* https://db4free.net/ mysql 200M
* https://dbhub.io/ SQLite，以HTTPAPI使用，基本上是用git存文件，不过允许用API查询，修改则要下下来
* https://memfiredb.com/ 兼容PG11，国产，5GB，目前在公测，管理员说后续收费计划还没决定
* ~~https://remotemysql.com/ mysql 8.0 100M，需要花不少时间回答调查问卷，允许常见的DQL和DML和创建索引，不能创建Proc 视图 触发器~~ 挂了
* https://www.freemysqlhosting.net/ mysql 5.5，5MB，每周会收到要手动操作来延期的邮件
* https://www.datastax.com/products/datastax-astra/pricing ApacheCassandra(NoSQL)
* ~~https://www.freesqldatabase.com/ mysql 5MB~~ 会过期且就不能再用了
* http://sqlpub.com/ MySQL，国产
* https://freedb.tech/ MySQL8 50MB
* https://tidbcloud.com/ 兼容MySQL，国产
* https://neon.tech/ PG，EA

## BaaS

* ~~https://bmob.cn/~~ https://www.bmobapp.com/
* https://leancloud.cn/pricing/
* https://firebase.google.cn/pricing 用处：https://zhuanlan.zhihu.com/p/95334890
* https://www.zhihu.com/question/34124789/answer/72495188
* https://maxleap.cn/s/web/zh_cn/devcenter-pricing.html
* https://www.8base.com GraphQL
* https://www.easycsv.io/pricing
* JSON
  * https://jsonstores.com/ 100个JSON对象，每个最大2MB
  * https://jsonbin.io/
  * https://extendsclass.com/json-storage.html
  * ~~https://json.psty.io/~~
  * https://www.jsonstorage.net/ 有无需注册的
  * https://db.neelr.dev/ 无需注册，打开网页时自动生成一个TOKEN。但国内打不开

## Managed K8S

* https://www.openshift.com/products/online/ 每60天清除
* https://okteto.com/pricing 免费版2CPU，4G内存，10G储存。刚注册送一个月pro，不付款自动降到免费版。免费版24小时不活动就sleep。原意是为开发者日常开发使用的
* https://usekrucible.com 一个月能用25小时，自己分配
* https://labs.play-with-k8s.com/ 好像每天只有四小时；https://labs.play-with-docker.com/
* zarvis.ai staroid.com 网页都用的是Google的服务器，无法直接访问
* https://kubesail.com/ 停止免费版了，不过还是能作为管理平台
* https://loft.sh/ 好像只是客户端或者管理平台
* ~~https://kubernauts.sh/~~ 宣传免费版有1CPU，1G内存；申请注册后没收到任何邮件，无法登录。现在会跳转到https://kubernautic.com/ 打不开
* 挂了的：k8spin.cloud tryk8s.com

## Serverless/Node Paas（无状态的api）

* https://glitch.com/
* https://workers.cloudflare.com/ ；https://github.com/xiaoyang-sde/reflare
* https://vercel.com/ node go py
* https://deno.com/deploy
* https://pipedream.com/
* https://keen.io/
* ~~https://www.openode.io/pricing~~
* https://www.cloud66.com/node/ 免费一个月
* ~~https://www.jexia.com/~~
* https://encore.dev/ RST
* 谷歌的functions有一些免费额度，但一定会产生部署费用，最少$0.03/mo
* 国内的云服务厂商一般都有FaaS服务，也有一定的免费额度，但问题是公网流出流量是没有免费额度的
* https://www.slappforge.com/sigma 仅开发平台
* https://catalyst.zoho.com/ 有免费的
* ~~https://hook.io/pricing~~
* https://jotcode.io/
* https://wundergraph.com/ 免费版还没出
* https://www.val.town/

## 静态网页托管（必须要能自动更新）

* https://surge.sh/
* https://www.netlify.com/
* https://cloudcannon.com
* https://tiiny.host 只能存活7天？
* https://pages.cloudflare.com/
* https://cloud.digitalocean.com/apps starter版本免费3个静态网站，用了cf的cdn国内可能无法访问

## 也许可用的IaaS

* euserv，德国的，只有IPV6，亲测确实可以，但硬盘很慢 https://github.com/YG-tsj/EUserv-warp
* https://activity.xinruiyun.cn/free/ 新睿云，发个广告可以免费用一个月的ECS
* https://www.oracle.com/cn/cloud/free/ 体验文章：https://51.ruyo.net/14138.html 不支持prepaid card；https://www.blueskyxn.com/202109/5232.html
* https://51.ruyo.net/14583.html Azure
* https://www.atlantic.net/ ~~免费12个月~~现在好像变成免费一个月了，需要信用卡，
* https://hax.co.id/ https://woiden.id/ https://blog.kermsite.com/p/hax/
* https://evolution-host.com/
* https://microlxc.net/ https://nanokvm.net/ 需要注册 https://lowendtalk.com/ 满足一定条件才能申请
* 谷歌云、Amazon、Azure、Yandex Cloud：注册后都会送一些额度
* https://open.iot.10086.cn OneNET移动的，目前没啥免费的内容

### [IBM Cloud](https://www.ibm.com/cn-zh/cloud/free)

* Lite(轻量)版无需信用卡，没有到期时间，完全不会变到付费套餐上，额度到了就无法使用，30天不活动自动删除，一共44项服务
* Cloud Foundry：PaaS 256M内存，支持Java Node .NET GO PHP Py。10天不活动就休眠。apic.mybluemix.net和mybluemix.net都被墙了。要用ibmcloud命令行
* 对象储存：25GB储存，5GB出站；Cloudant JSON文档数据库：1GB；DB2数据库：200MB，每90天要邮件延期
* 机器翻译：但无ja-zh模型，只能和en互转，每月100万字符
* ~~API Gateway：转发一次到另一个endpoint上，能用于静态文件的反代，能设定密钥验证和限制速率，显示调用频率。免费调用100万次但是没写每月，之后限速~~ 他们关闭此服务了，说要迁移到API Connect Reserved，然而这东西是付费的，介绍中的Lite能用的V5版也不存在
* Cloud for Education：持续时间一小时的ECS，能用RDP连上但卡到完全无法使用，好像无外部互联网连接
* 机器学习
* Docker Registry：储存0.5GB，流量5GB
* Event Streams：Kafka
* 那些“软件”虽然有非常多免费的，但必须部署到k8s上；k8s也有免费套餐，但lite无法创建，因为流量和IP可能要收费
* 函数计算：虽然有一点免费额度，但是无lite版

### [腾讯云](https://cloud.tencent.com/act/free)

* 对象储存：免费半年
* CDN：免费半年
* Serverless：免费一年
* 文件储存：免费10G
* 机器翻译：免费500万字符/月，开通免费版必不会收任何费用
* 云托管 CloudBase Run：不知道干什么用的

### [阿里云](https://free.aliyun.com)

* ECS：https://www.aliyun.com/daily-act/ecs/free 需要实名认证且未购买过任何产品，有个t6的ECS可以免费试用一年
* MaxCompute大数据计算服务开发者版https://www.aliyun.com/product/odps
* 云效DevOps有一些免费额度，包括5GB Maven仓库
* 机器翻译通用版：每月100万字符免费额度
* FaaS一年免费额度

## 低代码平台/aPaaS

* 指不用写很多代码就能设计出软件，有可视化工具
* 大部分都是BPM平台，即 表单+工作流审批，适合企业建立业务逻辑在线办公
* 往往与平台本身严重绑定，难以复用和维护，切换平台代价大，开发者自身难以提升

### 国内的

* https://github.com/taowen/awesome-lowcode 收集
* https://www.aliwork.com/ 宜搭，阿里+钉钉
* https://www.apicloud.com/ 云端开发管理类
* https://www.mingdao.com/ 明道云
* https://www.jiandaoyun.com/ 简道云
* https://www.huoban.com/ 伙伴云
* https://qingflow.com/ 轻流
* https://www.steedos.com/pricing/platform/ 华炎魔方，开源，私有部署免费
* https://baidu.gitee.io/amis/docs/index 开源，偏程序员
* https://modao.cc/ 墨刀，原型设计工具
* https://www.imgcook.com/ 淘宝，由设计稿生成界面
* https://www.huaweicloud.com/product/appcube.html 华为云应用魔方，太新
* https://www.informat.cn/ 织信
* https://seatable.cn/ 在线协同表格和信息管理工具，类似于excel，本体不开源但开源了一些组件
* https://www.baishuyun.com/ 百数云
* https://kalacloud.com/ 卡拉云
* https://js.design/ 即时设计，原型设计工具
* https://code.fun/
* https://yesapi.cn/
* https://www.jijyun.cn/ 集简云，相当于内置了常见应用的爬虫数据源，获取后根据需要执行动作
* 网页感觉不太好的
  * https://www.iyunbiao.com/ 云表
  * https://www.grapecity.com.cn/solutions/huozige 活字格
  * https://www.learun.cn/ 力软敏捷框架
  * https://www.ivx.cn 号称零代码开发Web App和小程序，前身是ih5.cn，不是BPM
  * https://wuyuan.io/ https://enhancer.io/ 无远开发平台，个人使用免费，商业收费
  * https://www.wudaima.com/ 宜创无代码，官网的footer的链接都是废的，一点也不透明
  * https://www.bn100.com/ 柏思科技/Workfine
* 收费的
  * https://h3yun.com/ 氚云，只免费15天，集成钉钉
  * https://www.newdao.net/ 牛刀，免费两周
  * https://www.clickpaas.com/ 不支持个人
  * https://www.dadayun.cn/ 搭搭云 没有注册的地方
* 没有https的： http://www.joget.cn/ 捷得 、http://www.putdb.com/ WebBuilder 、http://www.mf999.com/ 魔方网表(纯表单类)、http://www.delit.cn/ 度量快速开发平台、http://www.jinyunweb.com 进云、http://dev.easydo.cn 易开发、http://www.jepaas.com/ 、

### 国外的

* https://anvil.works/ py全栈，前端Drag and Drop UI，后端和数据储存用的是该网站的库
* https://www.outsystems.com/pricing-and-editions/ 开发移动应用，是该行的老大；前端组件比较多，后台相对弱一点儿；注册需要姓名，邮箱
* https://www.mendix.com/ 开发移动应用，后台能力比较强（有微流系统）
* https://free.caspio.com/ Database-Powered Apps
* https://thunkable.com 开发移动应用
* https://www.appsheet.com/ 无法直接打开
* https://www.zoho.com/creator/ 网页在我这里打开巨慢。可以一直用免费版只要不使用高级特性
* https://airtable.com/
* https://zenkit.com/ 无法直接打开
* Google的App Maker（G Suite收费）、微软的PowerApps（收费10$/mo）
* https://www.dronahq.com/
* https://zhuanlan.zhihu.com/p/375252561
* https://www.odoo.com/zh_CN/ 开源
* https://bubble.io/ 新出的
* https://github.com/appsmithorg/appsmith
* https://www.ragic.com.cn/ 表格类
* https://www.airtable.com/
* https://www.make.com

## 定时任务

* https://www.cronjobservices.com/ 收集
* EasyCron：每月要重新激活
* https://cronitor.io/

## 未分类

* https://www.litespeedtech.com/experience-litespeed-for-free 一个月有效？需要姓名，电话，邮箱，地址。好像只有wordpress，还是只有软件？
* https://github-students.educationhost.co.uk/ 免费一年
* 有可能与Jupyter有关：
  * https://www.dataquest.io/plans-pricing/
  * https://mode.com/compare-plans/
  * https://kyso.io/pricing
* https://studio.azureml.net/ 可视化机器学习实验工具，可不登陆使用
* https://quic.cloud/ Wordpress cache cdn
* https://apis.baidu.com/
* https://platform.sh/pricing/ 好像只免费30天
* API聚合
 * https://rapidapi.com/ 只是一个平台，经过它反代到各个提供者的服务器上，大部分质量很低，速度超慢。作为提供者大概简化了收费和验证途径吧。有点用的：simple-file-storage、secure-storage、postput。各种cors-proxy反代。ProxyPage代理ip
 * https://promptapi.com https://apilayer.com/
 * https://www.lafyun.com/

# 有云服务器时能自建的项目

* https://github.com/awesome-selfhosted/awesome-selfhosted
* ss：https://github.com/lrinQVQ/script https://github.com/mritd/dockerfile/tree/master/shadowsocks
* 网盘
  * Seafile：国产，C，同步盘，但必须依赖Py2.7
  * https://github.com/nextcloud/docker https://docs.nextcloud.com/server/17/user_manual/ ：owncloud的同作者，PHP。https://github.com/e-alfred/ocdownloader 离线下载插件
  * Cloudreve：国产，GO，支持OSS
  * zFile：国产，Java
  * https://github.com/syncthing/syncthing GO
  * BTSync
  * oneindex
  * OLAINDEX：使用OneDrive API
  * https://github.com/zhaojun1998/zfile 评测：https://xiaoyou66.com/archives/769
  * https://www.directorylister.com/ indexer，PHP
  * https://github.com/prasathmani/tinyfilemanager PHP
  * sparkleshare
  * rclone
  * https://freefilesync.org/
* 文件浏览器：https://larsjung.de/h5ai/ （PHP）、https://github.com/filebrowser/filebrowser （GO）
* gitlab
* 爬虫
* 论坛：discuz（PHP，维护不快），Flarum（PHP），vanilla (PHP)
* 监控程序/API
  * https://github.com/ivbeg/awesome-status-pages 合集
  * https://cachethq.io/ 合集中最活跃的但是PHP
  * https://github.com/hunterlong/statping GO
  * https://github.com/bazzite/statusfy JS
  * https://uptimerobot.com/ 不开源有免费版
  * https://www.atlassian.com/zh/software/statuspage 有免费版
  * https://github.com/nicolargo/glances Py
  * https://eheh.org/ 国产
  * https://www.fundebug.com/
  * https://betteruptime.com/pricing 不开源有免费版
* 监控服务器状态：https://github.com/netdata/netdata C+Python，star非常多，有中文翻译。https://github.com/grafana/grafana TS+GO，star数稍少，但commit数和贡献者数非常多。https://github.com/open-falcon/falcon-plus GO，相对而言star数少很多，但是国产的，需要mysql；https://github.com/CokeMine/ServerStatus-Hotaru
* 各种可以装的软件的收集：https://github.com/Kickball/awesome-selfhosted 、https://www.softaculous.com/softaculous/apps 、 https://github.com/luong-komorebi/Awesome-Linux-Software 、https://statusfy.co/
* 自己挂广告
* 图床：https://xiaoyou66.com/archives/774 https://molunerfinn.com/PicGo/ https://github.com/wisp-x/lsky-pro https://github.com/chevereto/Chevereto-Free
* 可视化日志：https://goaccess.io
* BT下载：https://github.com/jpillora/cloud-torrent
* 创建网页版的Shell：https://github.com/instantbox/instantbox
* jupyter notebook: https://xiaoyou66.com/archives/1095
* OSS: https://github.com/minio/minio https://www.digitalocean.com/community/tutorials/how-to-set-up-an-object-storage-server-using-minio-on-ubuntu-18-04 但协议是最严格的AGPL
* 短链接：UOURLS（PHP，需要二次开发）Polr（也是PHP，不过偏向开箱即用）https://github.com/ellisonleao/pyshorteners https://shlink.io/ https://dub.sh/
* https://apex.sh/up/ 一键部署几种语言的Serverless应用到AWS
* https://github.com/chrislusf/seaweedfs 分布式文件系统，支持S3的API；https://github.com/syncthing/syncthing
* 当我有服务器时我做了什么（别人的集合）：https://shanyue.tech/op
* 后台控制面板：https://www.jianshu.com/p/3bc7404af887
* 搜索引擎：https://github.com/benbusby/whoogle-search https://github.com/milvus-io/milvus https://github.com/meilisearch/MeiliSearch
* 控制面板：https://github.com/cockpit-project/cockpit
* 性能测试：`curl -L bench.sh | bash`
* CMS: https://www.storyblok.com/
* CI
  * https://www.jetbrains.com/teamcity/
  * https://drone.io/
  * https://devtron.ai/

## 自建Paas

集合：https://paasfinder.org

* https://dokku.com/
* openstack，开源IaaS，机器最好有10G以上的内存
* rancher, openshift, CloudFoundry, flynn
* https://www.rainbond.com/ 国产的
* https://letscoded.com
* https://www.koding.com/
* https://kodcloud.com/ 有使用者表示“每次访问都会采集服务端和客户端的隐私信息，里面流氓脚本一大堆”
* https://github.com/caprover/caprover
* https://convox.com/
* https://nanobox.io/
* https://caprover.com/
* https://rio.io/
* https://github.com/teamhephy/workflow
* https://www.kintohub.com/ 基于k8s
比IaaS高层（无法重装或指定系统），比PaaS低层（可以访问文件系统，有的可以SSH连上去），一般使用cPanel。

感觉比较好的：

* https://alwaysdata.com 支持多种语言，版本也比较新，注册只需要邮箱
* https://www.accuwebhosting.com/about/free-students-hosting
https://www.ukhost4u.com/free-website-hosting-uk/
https://3001.host/pricing/ 现在会自动跳到https://status.3001.host/
https://www.2makeu.com/pricing 522

---

听说你在找免费虚拟主机？：
速度、数据安全、网页安全（修改源代码、挂广告病毒）、随时消失（删库跑路）、难SEO、无客服、无法退出（要求付迁移费）、乱用信用卡

---
国内的，基本上都要实名+备案：
热铁盒 https://host.retiehe.com/ https://rthe.cn/ 静态和单文件PHP
乐云空间 https://www.renzhijia.com/buy/index/7/ ：2元/月，明说了稳定性差；注册需要姓名、手机号、地址

酷番云 https://www.kcloudidc.com/freehost ：注册需要手机号、QQ号，需要实名认证，有效期一个月，联系客服免费续到最长一年
主机蛋 http://www.idcegg.com/free/ ：有效期3个月，注册需要姓名、手机号、QQ号、邮箱、地址、身份证号
金泰联 http://www.iiddcc.com/ ：注册需要姓名、手机号、QQ号、邮箱、地址、身份证号
恒爱网络 http://www.zzhidc.com/freehost.html 两种方式，一种是发广告，另一种是充五块钱保证金
番茄互联 https://www.fqidc.cn/free/ 每年2元；https://www.fqidc.cn/index.php/buy/index/10/
蓝队云 https://www.landui.com/project/freehost/ 每天限额放出
我的免费云 https://www.myfreeyun.com/ 不支持TLS1.2
百度智能建站 https://aipage.baidu.com/ 可能收费
强人网络 https://www.qiangren.net/html/active/vhost-free/ 好像从2020年5月开始就暂停申请了
景安网络 https://www.zzidc.com/main/huodong/freehost 号称每天9点100台免费主机，现在好像没了
https://www.henghost.com/sponsor.shtml
https://www.xiaoji.la/ 签到得积分开通，可能缺货

---
国外的：

https://neocities.org/ 网站本体开源
https://www.nodehost.ca/ php mysql 访问很慢
https://my.nexusbytes.com/cart.php?gid=1 python node php

评测网站：https://hostingfacts.com/
收集：http://www.100bestfreewebspace.com/searchPage0/Free-Host.html

https://infinityfree.net/ ：单文件上限10MB；说是禁止使用广告拦截器，不过好像只是Dashboard等有广告，实际自己的网页不会插广告
https://x10hosting.com/ ：有很多被莫名其妙删掉的网站
https://www.awardspace.com/free-hosting/ ：慢、TOS中说可以把数据出售
https://www.freehosting.com/ ：速度慢、删网站
https://www.freehostia.com/ ：速度慢
https://www.freewebhostingarea.com/
http://www.zymic.com/free-web-hosting/ 无法直接打开。现在好像挂了
https://googiehost.com/freehosting.html 有人打广告；需要填 WHY DO YOU NEED THIS ACCOUNT?
https://freehostingnoads.net/ 好像存在推广；需要填姓名，手机，邮箱，地址
https://www.biz.nf/
https://www.lima-city.de/
https://www.zzz.com.ua/en
https://viewen.com/free-cloud-hosting/ https://dashboard.viewen.com/?language=chinese 好像quora的人评价比较高，但网站没有明显说免费
https://wpnode.net/free-hosting/ 有wp，php和mysql，空间1G；但要信用卡；无法直接打开
https://www.myownfreehost.net/
https://www.xrea.com/ 日本的
http://sitemix.jp/ 日本的
https://www.krypt.com/zh/cloud/wordpress 只有wp，免费版暂时卖光了；无法直接打开
https://www.uhostall.com/free-hosting.php
https://pipni.cz/
https://www.heliohost.org Community powered free hosting for everyone 感觉比较好
https://woomhost.com/
https://www.instafree.com/ 封了国内的IP
https://www.hostpoco.com/
https://profreehost.com/
https://www.websitebuilder.com/pricing
http://razyhosting.com/
http://0fees.us/hosting.php
--
二次售卖https://ifastnet.com/的：
http://olab.in
https://byet.host/free-hosting
http://efreehost.com

---
Drag and Drop的：

https://zh.wix.com/
https://webflow.com/
https://www.weebly.com/ 无法直接打开
https://www.squarespace.com/
https://www.ucraft.com/free-web-hosting
https://sites.google.com
https://www.ucoz.com 无法直接打开
--
国内的：
https://www.qifeiye.com/
https://www.strikingly.com/ https://www.sxl.cn/
https://jz.fkw.com/
http://www.wqdian.com/
http://www.zhuzi.me/
https://www.zhihu.com/question/19665744

---
号称免费VPS：
host1free/haphost
https://www.gigarocket.net/free-vps.php 也有free hosting
zulutrade
Vpswala.org
Xrea：https://www.freehao123.com/xrea-ssl/

---
Wordpress:
https://www.accuwebhosting.com/web-hosting/free-wordpress-hosting
https://pantheon.io/plans/pricing
https://wordify.com/wordpress-hosting/wp-devsites/
https://www.getshifter.io/
DDNS需要公网IP，基本上就是隔一段时间访问一下接口，连接和传输数据是不会消耗服务商的流量的。
内网穿透需要消耗服务器的流量。
还有点对点/内网打洞的技术，但是需要两边都安装软件：xtcp，n2n，moon，zerotier one

## frp

* https://www.natfrp.org/ Sakura Frp
* https://www.lu8.win/ ngrok、frp、n2n、nps、免费域名
* https://mefrp.cn/ 之前是 https://frp.msrx.online/
* https://liulifrp.cn
* https://www.openfrp.net/

## ngrok

1.x开源但现在已经停止维护了；2.x不开源。

* https://ngrok.com/ 官网，服务器在国外
* https://natapp.cn/ 免费的需实名认证
* https://www.ngrok.cc/ Sunny Ngrok，不过官网说也支持frp
* https://www.tunnelnat.com/ 虽然也写了frp，但好像只有ngrok有免费通道

## 其它开源的

* https://github.com/ffay/lanproxy Java
* http://wdom.net/ 免费20分钟
* https://github.com/inlets/inlets

## 其它不开源的

* https://hsk.oray.com/ 花生壳，注册需要手机号；DDNS和内网穿透都支持？后者免费速度1M。
* https://www.kingdriod.cn/ 神卓，免费速度1M；需要实名认证上传身份证
* http://www.luyouxia.com/ 路由侠
* https://www.notr.tech/ 免费3小时
* https://www.nsloop.com/ 量子互联，写的不限流量
* http://www.mofasuidao.cn/ 魔法隧道，写的是“免费创建账户”
* http://www.youtusoft.com/ 网络通
* https://xiaomy.net/ 网云穿
* https://localhost.run/ 无需注册？
* https://www.cpolar.com/
* https://pinggy.io/

## 免费DDNS

* https://dyndnss.net/eng/
* https://freedns.afraid.org/
* https://www.duckdns.org/
* https://www.noip.com/
* https://www.spdyn.de/ 只有德语？
* https://dynv6.com/
## 网页

### 域名

* 理论上DDNS也会提供，不过不是二级的
* https://my.freenom.com/clientarea.php  tk、ml、ga、cf、gq顶级域名
* https://nic.eu.org/ 欧盟下的，个人免费注册；http会被重置
* https://dns.txizd.cn/ 三级
* https://dns.yzjia.xin/ 三级
* http://cc.1xie.xyz
* https://github.com/fransallen/thedev.id https://github.com/js-org/js.org 要开PR
* https://www.freedomain.pro/ co.nr
* http://www.com.nu/
* https://domainoji.com/ https://www.punycoder.com/ emoji/idn域名转换；https://emojipedia.org/ emoji搜索
* https://nic.ua/en/domains 乌克兰 pp.ua
* https://www.azote.org 法国 asso.st，fr.nf，fr.cr，ze.cx，infos.st
* https://www.nom.za 南非
* https://www.sitelutions.com 纽埃 rr.nu
* https://www.ipq.co 哥伦比亚共和国
* https://fofa.so/ 用来搜索域名的

### 证书

* https://freessl.cn
* https://freessl.org
* https://allinssl.com/zh/
* https://zerossl.com/

### DNS

* https://www.dns.la/
* https://www.bajiedns.com/
* https://www.dnsdun.com/
* https://nip.io/ 自动根据域名中的IP返回DNS查询结果。xip.io挂了
* https://dnsmadeeasy.com/

### [Cloudflare CNAME/IP/NS 接入](https://github.com/ZE3kr/Cloudflare-CNAME-Setup/blob/master/README.zh.md)

* https://cdn.liang.ke/
* https://cf.tlo.xyz/
* https://dns.porta1.net/
* https://cdn.bnxb.com/
* https://cdn.wzfou.com/
* https://cdn.moeelf.com/

### CDN

* https://su.baidu.com/product/cdn.html
* http://cdn.meierlian.net/
* https://www.yunaq.com/jsl/ 仅限80端口
* https://www.cdnfine.com/
* https://wangzhan.qianxin.com/ 前身是360网页卫士
* https://www.merlincdn.com/ 注册送$10，不清楚有没有限时，额度有个自选的
* https://github.com/EtherDream/freecdn 自动选择合适的CDN的程序

### 短网址

* https://1t.click/ 、https://sina.lt/ 新浪的
* https://u.nu/
* http://suo.im/
* https://tinyurl.com/
* https://bitly.com/ 无法直接访问
* https://sl.iyong.com/
* https://v.ht 国外的
* https://ulvis.net/
* https://reurl.cc
* https://fars.ee/

## 国内源/镜像

* https://github.com/china-speed/china-speed.github.io apt/docker/pip/npm收集
* https://www.7ed.net Google Fonts/Libraries、CDNJS、Gravatar、Github RAW、Imgur、SM.MS反代；曾用cdn.staticdn.net cdn.con.sh
* https://cdn.geekzu.org/cached.html Google Fonts/Libraries、Gravatar反代
* https://sb.sb/blog/css-cdn/ loli.net域名，Google Fonts/Libraries、Gravatar反代
* https://npm.taobao.org/mirrors 一部分GitHub开源项目的release
* https://cdn.ews1.com/ Google Fonts、Gravatar
* https://github.com/eryajf/Thanks-Mirror 收集
* https://cravatar.cn/avatar/

### GitHub

* jsdelivr、statically：相当于只支持raw
* https://doc.fastgit.org/zh-cn/node.html 主站网页、assets、~~raw、release~~
* https://gitclone.com/ 支持http clone
* https://github.com/XIU2/UserScript/blob/master/GithubEnhanced-High-Speed-Download.user.js
* https://www.toolzl.com/tools/githubjiasu.html 支持release
* https://github.com/zwc456baby/file-proxy https://pd.zwc365.com/
* https://github.wuyanzheshui.workers.dev/ https://github.rc1844.workers.dev/ 网页版
* https://github.com/nulastudio/mclone 安装后用git mclone即可自动用mirror
* https://shrill-pond-3e81.hunsh.workers.dev/ https://gh.api.99988866.xyz/ https://g.ioiox.com/ (https://github.com/hunshcn/gh-proxy)
* https://gh.haval.gq 没处理css和js的网页版
* https://ghproxy.com/
* https://git.aya1.top/ 网页，https://note.aya1.top/#/r 任意网页。基于CF Worker
* https://d.serctl.com/ 活着但是日本Linode，IP干扰大。支持release
* https://github-do.panbaidu.cn/ github.do
* https://combinatronics.io/ 国外的，相当于只支持raw，com后缀被污染+RST了
* https://raw.iqiq.io/ 仅raw
* https://hub.nuaa.cf/
* https://github.com/fhefh2015/Fast-GitHub/issues/44
* ~~github.com.cnpmjs.org~~ 网页版，触发了滥用检测
* ~~zll.us~~
* ~~https://githubd.com~~
* ~~widora：http://gg.widyun.com http://g.widyun.com/ http://g.widora.cn/ 支持release~~
* ~~https://git.best/~~
* ~~http://gitd.cc/~~
* ~~https://www.toolwa.com/github/~~ 网站本身活着，但线路一是用不了的jsproxy，线路二是fastgit
* ~~https://github.bajins.com/ 网页版~~

### 前端库

* 国内的，基本都是同步的cdnjs，否则要么不全要么老；链接格式只有bootcdn.cn的与cdnjs完全相同，其余的都没有ajax/libs/部分，字节的还多一部分。版本排序原本就是按字符串顺序，如1.1 1.10 1.2，太蠢了
  * https://www.bootcdn.cn/ 由bootcss网站支持
  * https://www.staticfile.org/ 七牛云。版本默认选的最老的，不知道怎么想的。版本排序按字符串顺序
  * https://cdn.baomitu.com/ 360
  * https://cdn.bytedance.com/ 字节跳动，直接把所有库按首字母列出来
  * https://jshub.com 有点旧，感觉是模仿bootcdn的
  * https://cdnjs.net/ 有可能2019年后就没更新了
  * https://lib.sinaapp.com/ 新浪，少且旧，jq最新3.1
  * http://jscdn.upai.com/ 又拍云，极少且极旧，无https
  * https://apps.bdimg.com/libs/jquery/2.1.4/jquery.min.js 非公开，不更新
* 国外的
  * https://www.jsdelivr.com/ 有国内CDN。支持GitHub。https://esm.run 支持ESM
  * https://cdnjs.com/ CF自己的，访问慢
  * https://unpkg.com/ 用的CF的CDN，实验性支持ESM
  * https://statically.io/ 用的Fastly的CDN。只支持GitHub，加min后缀自动压缩，还有图片压缩服务和网页快照截图功能。现在cdn.statically.io被RST了
  * https://jspm.org/ 仅ESM
  * https://www.skypack.dev/ snowpack团队的，ESM，高度为浏览器优化
  * https://esm.sh/ 仅ESM，自动转换的
  * https://ajax.aspnetcdn.com 微软的，只有jq相关的很少几个，但路径格式与jq官网相同方便替换
* Font Awesome
  * 前面那些前端库仍可用，但是某些版本不在cdnjs上，如5.0.x
  * https://use.fontawesome.com/releases/v5.15.0/css/all.css 官方的打开慢，且注意它其实对应的是min.css
  * http://apps.bdimg.com/libs/fontawesome/4.4.0/css/font-awesome.min.css 非公开，不更新

## 储存

* 那些明显是其他人自建的使用时要小心跑路，不建议放重要内容

### OSS

* https://www.zhihu.com/question/51309695 有哪些优秀且免费的云存储服务？
* https://www.zhihu.com/question/34445630/answer/449868590 网易云，免费50G空间，20G流量
* https://developer.qiniu.com/af/kb/1574/free-credit-information https://www.qiniu.com/events/free 七牛云
* https://www.upyun.com/league 又拍云，10G储存15G流量
* https://www.ucloud.cn/site/product/ufile.html 实名认证用户20GB免费云存储空间和20GB/月免费下载流量
* http://www.cuplayer.com/price/ 酷播云，视频储存
* https://u-file.cn/ 好像需要申请
* https://get.robin.io/ 5GB

### 网盘

* https://www.quqi.com/ 曲奇云盘，但好像没有电脑端
* https://cowtransfer.com/ 奶牛快传，~~现在也提供网盘功能~~
* https://www.wenshushu.cn/
* https://www.liupan.net/
* https://teracloud.jp 10G空间，支持 WebDAV；推荐码NDMSQ
* https://www.furk.net/ 很慢，1G/D且5G/W
* https://www.lanzou.com/ 蓝奏云，单个文件限100M
* 亿方云
* 天翼云盘、沃家云盘、和彩云
* https://www.zoho.com.cn/workdrive/
* 超星云盘
* 腾讯微云
* https://www.asuswebstorage.com
* https://pan.bitqiu.com/ 比特球云盘
* https://github.com/xausky/DockerRegisterCloud 把docker registry变成网盘
* https://www.mediafire.com/
* https://github.com/apachecn/CDNDrive
* https://ondisk.fuyeor.com/login
* https://internxt.com/

### Onedrive

* https://products.office.com/en-us/student?tab=students
* https://xkx.me/
* https://xyxywan.gitee.io/web/ 有桌面office但需审批
* https://get.porta1.net/
* https://zhuanlan.zhihu.com/p/105438817 免费申请office E5开发者订阅，附无限续期+私人网盘教程
* Index：https://github.com/spencerwooo/onedrive-vercel-index https://github.com/vcheckzen/FODI https://github.com/qkqpttgf/OneManager-php

### 文件分享

* https://catbox.moe/ 上传速度不稳定，快的时候有600K，单次上限200MB
* https://www.zippyshare.com/ 上传速度为0
* ~~https://send.firefox.com/ 上传速度能到2M，但有时传到一半会断掉；VPS的下载速度能到21MB/s~~
* https://www.up-4ever.org/ 上传速度不到1M，需要关闭广告过滤扩展才能用，有的后缀不让传，下载等30秒人机验证后倒是能创建出直链，单次上限200MB
* https://transfer.sh/
* https://uguu.se/ 单次上限100MB
* https://anonfiles.com/
* https://letsupload.co/
* https://secufiles.com/
* https://wetransfer.com/
* https://wormhole.app/
* https://filedoge.com/
* https://demo.jirafeau.net/ 也能自建 https://gitlab.com/mojo42/Jirafeau
* https://plik.root.gg 也能自建 https://github.com/root-gg/plik
* https://wormhole.app/
* https://pan.duiai.cc/
* https://oshi.at/
* https://anonfiles.com/ https://filechan.org/
* https://ttm.sh/
* https://send.internxt.com/
* https://bashupload.com/ 有效期3天，只能下载一次
* https://airportal.cn/
* https://musetransfer.com/
* https://snapdrop.net/ 无需APP，仅局域网
* https://termbin.com/
* https://temp.sh/

### 离线下载

* https://www.loadbt.com 免费用户2G
* https://zhuanlan.zhihu.com/p/37785481 19款离线下载服务对比

### 图床

* http://www.zmonster.me/2013/12/06/image-host-service.html 国内外图床及其对比
* https://www.zhihu.com/question/21667151
* https://sm.ms/
* https://postimages.org/
* https://imgbox.com/
* https://imgbb.com/
* https://www.freeimagehosting.net/
* https://pic.xiaojianjian.net/
* https://imgurl.org/
* https://yunjiemi.com/ 之前是img.kuibu.net
* https://www.superbed.cn/ pic.imgdb.cn
* https://www.moepicx.cc
* https://www.hualigs.cn/
* https://jpg.dog/
* https://www.z4a.net/
* https://moetu.org/
* https://imgbb.com/
* https://www.picgd.com/
* https://tuchuang.richuyun.com/
* https://images.weserv.nl/ image cache & resize service 相当于图片的CDN
* https://imgtu.com/ 之前是imgchr.com
* https://imgix.com/ 使用.net的域名
* https://im.ge/

### BT Trackers

* https://github.com/ngosang/trackerslist
* https://github.com/XIU2/TrackersListCollection
* https://github.com/DeSireFire/animeTrackerList

## (盗版)资源

* https://discx.yuntu.io/ 光盘

### 软件

* https://masuit.com/
* https://www.lanzous.com/u/roustar31cn

### 书

* https://t.me/ebookdl 亲测确实能搜到
* http://finelybook.com/ 国产，亲测可以，非注册用户只能用城通网盘
* https://github.com/hoodiearon/w3-goto-world/tree/master/集成实用夹/书籍与文档
* https://smtebooks.com/
* https://foxgreat.com/ 搜不到C#的书
* https://dokumen.pub 网站不是英文的
* https://www.wowebook.org 下载页面为turbobit.net，很慢，而且有的要开会员
* https://www.zhihu.com/question/21202757 有哪些好的电子书下载网站推荐？
* https://zhuanlan.zhihu.com/p/53064677 有了这十几个网站，没有你找不到的电子书！
* https://www.jiumodiary.com/ 鸠摩搜书，也能搜到百度网盘的内容
* https://gist.github.com/baiwfg2/af827b8b75eebf8ab29f5531a0d265ce
* ~~https://www.allitebooks.com/~~ 超好但是挂了，不清楚现在的几个是否有关：https://www.allitebooks.in/ https://allitebook.xyz/ https://allitbooks.net/
* https://www.jb51.net/books/ 下载需要关注公众号获取提取码
* http://sd.blackball.lv/books/
* https://sobooks.cc/ 不是专门计算机的
* http://www.kgbook.com/ 不是专门计算机的
* https://z-lib.org/ 无法直接访问。https://sg1lib.org/ 目前可以直接访问
* https://www.zhihu.com/question/19709630 有哪些网站可以获取免费的国外的原版书籍（电子版）
* https://github.com/EbookFoundation/free-programming-books 免费的
* https://github.com/Jackpopc/CS-Books-Store 该开发者自己收集的一小部分经典的书，百度网盘直接下载
* https://libgen.gs https://1lib.ink/ https://zh.zlib.buzz/ https://www.ooopn.com/tool/zlibrary/

### 音乐

* https://tool.liumingye.cn/music/
* https://www.yijingying.com/html/musictools/
* http://music.moresound.ml/
* 国外的：https://myfreemp3.to/ https://myfreemp3juices.cc/ https://www.myfreemp3.bond/
* https://www.52pojie.cn/thread-929831-1-1.html 集合
* https://listen1.github.io/listen1/ 只是整合可以直接听的
* https://github.com/lyswhut/lx-music-desktop
* https://music.y444.cn/ 需要关注公众号
* 挂了的：https://github.com/maicong/music https://github.com/OJZen/QMD_Android

### GeoIP2数据库

* https://geolite.clash.dev/
* https://github.com/Dreamacro/maxmind-geoip/releases
* https://static.clash.to/GeoIP2/GeoIP2-Country.tar.gz （RixCloud 公共库）
* https://quantumult.crossutility.com/download/geoip/database/GeoLite2-Country.mmdb

### 字体

* https://zenozeng.github.io/Free-Chinese-Fonts/
* https://www.webfont.com/onlinefont/index
* https://www.marksimonson.com/fonts

## 安全

* https://github.com/euphrat1ca/security_w1k1
* https://github.com/No-Github/1earn

### 恶意软件分析沙箱

* https://habo.qq.com/ 腾讯哈勃。现在只能分析很少的一部分，详细报告需要高级会员，而申请通道已经关闭了
* https://www.maldun.com/ 魔盾安全
* https://s.threatbook.com/ 微步
* https://www.hybrid-analysis.com
* https://scan.anxinsec.com/
* https://ata.360.net/ 360安全大脑沙箱云，免费版只有Win7 32位环境

### 服务器安全软件

* https://www.yunsuo.com.cn/download.html 
* https://scanner.baidu.com webshell检测引擎

## Git平台

* https://code.aliyun.com
* https://xiaolvyun.baidu.com
* https://gitcode.net csdn出的，GitLab
* https://gitee.com/
* https://www.gitlink.org.cn/
* https://opendev.org Ubuntu, Gitea
* https://salsa.debian.org/ GitLab
* https://repo.or.cz/
* https://sr.ht/ https://sourcehut.org/

## Paste Bin

* https://pastebin.com/
* https://ghostbin.com/
* https://rentry.co/
* https://hastebin.com/
* https://pastebin.ubuntu.com/
* https://www.cacher.io/ 功能很多
* https://write.as/ 其实是博客
* https://del.dog/
* https://psty.io
* https://telegra.ph RST了

## 搜索引擎

* https://goobe.io/ 程序员搜索
* https://www.sousuoyinqingtijiao.com/ 搜索引擎收录提交入口
* https://www.cn-ki.net/ 文献搜索
* https://www.wuzhuiso.com/ 360的
* https://fsoufsou.com/

## Docker平台（非免费）

* https://www.tenxcloud.com/ 时速云
* https://www.daocloud.io/ 有一点点免费测试环境 http://docs.daocloud.io/app-deploy-mgmt/cloud-limited-resources
* https://www.mopaas.com/ 魔泊云
* https://www.alauda.cn/ 灵雀云
* https://canister.io/solo
* https://hostpresto.com/docker-hosting 免费六个月

## CI

* https://www.shippable.com/pricing.html
* https://codefresh.io/

## 图标

* https://octicons.github.com/

## 云办公相关

* http://www.gleasy.com/ 格子云，到哪都能办公
* http://www.everydo.com/ 文档管理系统

## PDF

* https://www.hipdf.com/
* https://smallpdf.com/cn

## 爬虫

* https://www.bazhuayu.com/ 八爪鱼；国外版 https://www.octoparse.com/
* http://www.houyicaiji.com/
* http://www.gooseeker.com/
* 以下是国外的
* https://www.zyte.com
* https://apify.com/
* https://www.diffbot.com/
* https://www.import.io/

## 微信消息推送

* https://sct.ftqq.com/ Server酱
* http://www.xtuis.cn/ 虾推啥
* https://pushplus.hxtrip.com/ push+
* https://qmsg.zendee.cn/ Qmsg酱
* https://wxpusher.zjiecode.com 开源
* https://letserver.run/ Server饭，开源
* https://github.com/songquanpeng/message-pusher 开源

## CI

* Circle CI 老牌
* AppVeyor 以Win出名
* https://cloud.drone.io 有人说文档烂
* https://semaphoreci.com/
* https://buildkite.com/

## 在线Shell

* https://shell.cloud.google.com/
* https://www.xshellz.com/
* https://freeshell.de/
* https://sdf.org/

## Chat GPT

* https://www.perplexity.ai 只回复英文，只单次问，无交互。会给出消息来源，较偏搜索引擎
* https://you.com 点Chat。国内无法直接访问
* https://beta.character.ai 可以创建某种性格特性的人物来对话。国内无法直接访问

### 写作

* https://writesonic.com
* https://rytr.me
* https://www.peppertype.ai 官网目前没说免费，根据宣传有5000词

### 国内版

* https://chat.forchange.cn/
* https://www.eiefun.com/chatgpt 效果较差，对输入的长度有限制
* https://www.text-to-speech.cn/chatGPT.html 效果较差
* https://ioii.cn xixibot.com 需要扫描公众号登录，扫了后网页版还是说要登录，小程序说服务繁忙
* 挂了的：https://trychatgpt.ssi.plus/ http://119.91.201.57:3000/ https://hi.icu/ https://chatgpt.sbaliyun.com/ http://chat.h2ai.cn/home https://bxs.xiaoz.me https://chat.gptocean.com/

## 其它中的其它

* https://img.xjh.me/ 随机图片 https://api.lolicon.app/#/setu 随机色图
* http://shaofan.org/jetbrains-active/ Jetbrains在线激活工具
* https://apiary.io/ API Design Stack，与Oracle合作
* https://www.sap.cn/products/cloud-platform/pricing.html ERP系统；注册Beta版是免费的，但要填姓名公司电话
* https://developer.okta.com/ adds authentication, authorization, and user management to your web or mobile app within minutes.
* https://www.chanzhi.org/dynamic.html https://www.chanzhi.org/book/chanzhieps/5.html https://www.zentao.net/ 蝉知和禅道，前者是CMS，后者是项目管理系统。不过是PHP
* https://www.kancloud.cn/ https://www.yuque.com/ https://www.baklib.com/ MD平台
* http://www.ypppt.com/ ppt
* https://squoosh.app/ 图片压缩，谷歌出的工具
* http://www.freeyun.net/ 软件授权管理一站式解决方案
* https://prerender.io/ 预渲染动态网页
* https://termible.io 还在内测的在线终端，基于Docker
* https://heyterm.com/zh-cn/ WebSSH
* https://www.freepik.com/ 免费psd图像资源
* https://pyup.io/ 监测Python依赖
* https://waifulabs.com/ AI生成二次元头像
* https://appcenter.ms/ 存放release
* https://dev.to/doobled/listing-the-best-services-for-free-domain-email-addresses-in-2020-3hkb 几个邮箱测评
* https://newrelic.com 遥测？
* https://mailchimp.com/ 群发邮件
* 性能测试：`wget -qO- 86.re/bench.sh | bash`
* https://github.com/fangzesheng/free-api 免费的接口
* https://github.com/zhaojh329/rtty web tty
* https://www.plasticscm.com/ 不同于git的版本控制系统，可以玩玩
* https://trinket.io/ Py的Turtles运行环境，谷歌的Blocks，适合小孩子学
* 手机原生应用推送：https://www.getui.com/push https://www.jiguang.cn/push
* 服务器监控：https://www.oneapm.com https://www.tingyun.com/ https://www.jiankongbao.com/
* https://www.authing.cn/pricing 统一身份验证
* https://hashnode.com/ 博客平台
* https://www.goodwaf.cn/ WAF
* https://pusher.com/ 为网页提供实时信息推送
* https://hex-rays.com/educational/ IDA教育版
* https://www.apponfly.com/ 点trial能获得免费30分钟的Windows
* https://patchbay.pub/ 类似于PIPE
* https://requestbin.com/ 类似于httpbin但可以保留请求的内容

## 别人的收集

* https://www.freehao123.com/
* https://51.ruyo.net/
* https://github.com/Sicmatr1x/Free-Resource
* https://www.producthunt.com/

## 挂了的

* Ohosti “骗人的，去年申请的现在还在Pending中”
* https://vitu.ai
临时短信

https://www.lothelper.com/cn
https://www.materialtools.com/
https://www.receive-sms.com/
https://sms.sellaite.com/
http://receivefreesms.com/
https://www.receivesmsonline.net/ https://www.freeonlinephone.org/
https://smsreceivefree.com/
https://blog.csdn.net/freeking101/article/details/82770470
https://www.textnow.com/ 要注册，应该能发？

临时邮箱

* https://yopmail.com/zh/
* https://www.guerrillamail.com/zh/ https://grr.la
* https://temp-mail.org/
* https://10minutemail.net/
* http://24mail.chacuo.net/
* https://www.moakt.com/
* https://www.zhihu.com/question/23418181/answer/56106667

虚拟电话：https://github.com/hoodiearon/w3-goto-world/tree/master/集成实用夹/临时邮箱与虚拟电话#虚拟电话
虚拟地址：https://www.haoweichi.com/
虚拟信用卡：Yandex.Money
