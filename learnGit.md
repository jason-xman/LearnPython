## 文件管理的现状
   引入： 日常的文件管理，例编写毕业论文，可能会存在多个版本，但是每个版本里面具体修改了什么内容，无法得知
   若论文由多个人编写，则存在版本新旧问题/更新/内容冲突/，随着协作人员越多，版本管理越困难
   问题：版本管理/协作
## 版本管理历史
  集中版VS分布式
  * 集中版：一台中央版本控制器，所有分支需要先从中心上下载版本，然后进行内容更新
  * 分布式：无中心节点，所有节点保留整个库的完整版本（实际执行中，会建立一个中心节点，目的是方便协作，其实不要他也ok）
## git基础概念
  * repository(master branch)
  * clone
  * commit
  * pull
  * push
  * megra
  * revser
## git流程图
   ![git完整操作流程图，包括基本概念组](.\Image\git-process.png)
## git工具
1.  客户端 **[git下载地址](https://git-scm.com/downloads)**   推荐前期命令行工具，熟悉运行原理，后续使用GUI工具
2. 服务端**[github](https://github.com)** 全球著名代码托管网站，邮箱即可注册

## git实战（git+github）
   按照服务器使用github，本地使用git建立项目并上传到服务器，开始进行文件编辑，并更新文件， 回退文件，合并项目，检测冲突
   * git-建立项目
   * git-已有项目获取-pull
   * git-commit
   * git-push
   * git-merge
   * git-resvrt
   * git-协作
## git使用原则
   * master上保留最终稳定可用代码
   * 建立独立的branch
   * 维修，功能更新，测试，建议新开branch
   * 
