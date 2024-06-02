# Course-Stack

> 这是 CS3321 数据库技术课程的小组作业仓库。我们设计了一个课程信息查询和可视化的数据库网络应用，名称是 Course-Stack

 <p align="center">
<a href="https://sm.ms/image/D5Mrkx2NJZztaSO" target="_blank"><img src="https://s2.loli.net/2024/05/26/D5Mrkx2NJZztaSO.png" ></a>
</p>

[在线演示地址](http://59.78.18.202:5173/mainpage)

## 项目贡献

小组成员如下：

| 姓名   | 学号         | 邮箱                                                         | 成员 | 贡献度 |
| ------ | ------------ | ------------------------------------------------------------ | ---- | ------ |
 |王梓萌 | 521030910015 | [@dongyunpeng-sjtu](https://github.com/dongyunpeng-sjtu)     | 组员 |  33%   |
| 孙州玥 |  | [@every-breaking-wave](https://github.com/every-breaking-wave) | 组员 |   33%  |
| 刘洺皓 | 521030910014 | [@Musicminion](https://github.com/Musicminion)               | 组员 | 33%    |

详细分工：
- 前端: 王梓萌
- Neo4j & 知识图谱：刘洺皓
- Mongodb & 用户系统：孙州玥

项目仓库的地址：

- Github: https://github.com/Simonwzm/CS3321-Course-Stack/

项目的CI/CD主要在Github上面运行，所以如有需要查看，请移步到Github查看。



### 项目架构

![](https://s2.loli.net/2024/06/02/idScL2tUQxzTPNA.png)

`Course-Stack` 是 CS3321 数据库课程的集大成项目，它结合了前沿的网页技术和复杂的数据管理系统来提供一个多层次的教学与学习平台。此项目不仅包括前端和后端的交互逻辑，还深入到了数据持久化层，采用 Vue.js、MongoDB 以及 Neo4j 等技术栈，打造出一个响应迅速、功能全面的教育工具。项目的核心在于利用知识图谱技术来探索和实现课程内容的深度关联及个性化学习路径，从而优化教学流程并提升学生的学习体验。

## 技术栈与项目架构简述

### [前端技术详解](https://github.com/Simonwzm/CS3321-Course-Stack/)
- **Vue 3 + Vite**: 利用 Vue 3 的响应式框架和 Vite 的快速冷启动特性，提供即时的页面更新和优化的开发体验。
- **UI 框架 - naive-ui**: 选择 naive-ui 为用户提供一致而现代的界面元素。
- **样式处理 - Tailwind CSS**: 使用功能类优先的 CSS 框架来构建定制的设计系统，快速响应不同组件的样式需求。
- **路由管理 - vue-router**: 管理复杂的页面路由，保持用户界面与URL的同步。
- **状态管理 - pinia**: 替代传统的 Vuex，为 Vue 3 提供更简洁和强大的状态管理解决方案。

### [Mongodb后端技术分析](https://github.com/UnderOC/CS3321-Course-Database/tree/new-feature-branch)
- **JavaScript & Node.js**: 使用 JavaScript 运行在 Node.js 环境下，处理服务器逻辑与数据流。
- **MongoDB**: 采用非关系型数据库MongoDB，以其高性能和高可扩展性处理大量动态数据。
- **Express.js**: 利用 Express.js 构建 RESTful API，简化后端路由和中间件的管理。
- **Docker**: 通过 Docker 容器化技术，确保开发和生产环境的一致性。

### [知识图谱后端（Neo4j）综述](https://github.com/Learner209/neo4j-courses/tree/CRUD)
- **Python & Shell**: 结合使用 Python 和 Shell 脚本来操控 Neo4j 数据库，处理复杂的查询和数据转换任务。
- **Neo4j**: 使用图形数据库 Neo4j 来存储和管理复杂的课程关系，通过其高效的图查询语言 Cypher 进行数据操作。
- **FastAPI**: 使用 FastAPI 构建高性能的 API 服务，支持异步处理，提高系统的并发处理能力。


## 亮点介绍

- [x]快速部署，便捷客制化
- [x]全文检索，高效查询
- [x]知识点提取查询，打通课程壁垒
- [x]用户系统，权限管理
- [x]多数据库后端整合框架，高可扩展性
<!-- - **动态探索**: 学生可以通过点击和拖动操作，探索课程之间的复杂关系。该地图支持放大、缩小功能，使学生能够根据需要查看不同层级的课程和知识点详情。
- **快速搜索**: 配备了高效的搜索功能，学生可以迅速找到特定课程或知识点，并通过可视化的方式展示课程之间的连接和依赖关系。

### 知识点探索器
- **深度连接**: 学生选择一个知识点后，系统自动展示与此知识点相关联的其他知识点及课程。这种互联网式的知识探索机制加深了学生对学科网络的理解。
- **信息展示**: 通过弹出窗口或侧边栏形式提供知识点的详细信息，包括概念解释、相关的课程作业、讨论话题等，增加互动性和教育深度。

### 可视化数据分析
- **数据洞察**: 教师可以通过系统提供的图表和仪表板，分析学生的学习成绩、课程难度评估等多维度数据。这些数据可用于评估教学效果和课程调整。
- **实时反馈**: 助力教师实时获取课程反馈，以图形化数据显示，帮助教师更好地理解学生的学习状态和课程的接受度。 -->

<!-- ## 知识图谱的未来展望

### 资源推荐图谱
- **个性化推荐**: 结合学生的学习历史和偏好，系统通过自然语言处理等技术，自动推荐相关的课件、参考资料和作业。这一功能帮助学生获得最适合其学习需求的资源。
- **推荐可视化**: 通过雷达图或热力图形式展示资源的推荐度和相关性，使学生能够直观地了解各类资源的价值和适用性。

### 学习路径规划器
- **目标导向学习**: 学生可以输入自己的学习目标和兴趣，系统基于知识图谱和算法推荐，生成个性化的学习路径。这不仅提升了学习的效率，还确保了学习的针对性和深度。
- **路径优化**: 系统提供最优的学习顺序和资源，帮助学生按照科学的路径达成学习目标，优化学习过程。

### 协作学习网络
- **社区学习互动**: 显示学生之间的学习互动，如论坛帖子、小组作业等，通过社区图谱的形式促进学生之间的交流和合作。这种社区学习环境能够激发学生的学习兴趣和团队合作能力。
- **网络搭建**: 通过构建一个互动的学习网络，不仅增强学生间的联系，还可以形成有效的知识共享和问题解决的平台。

## 总结
`Course-Stack` 通过结合现代前端技术和强大的后端数据库系统，以及创新的知识图谱应用，提供了一个全面的教学管理解决方案。我们的目标是通过这个平台不仅简化教师的教学工作，还能显著提升学生的学习效率和体验。详细信息和进一步的资源，请访问我们的 [GitHub 仓库](https://github.com/your-repository-url)。


![](./assets/upload_2684ba3c6f31c714360855ca1387f4eb.png) -->


### 项目管理

**项目分支**：我们的开发采用多子模块，单主仓库进行，子模块中采用多分支进行项目管理。每一个功能点对应一个Feature分支(对于比较复杂的功能分支可能会有不同组员自己的Branch)，所有的推送都在子模块中经过校验，然后更新主仓库中指向子模块commit的记录，然后进行CI测试，并可以在github actions中查看详细的情况。

项目一共包含主要分支包括


**软件测试介绍**：
![](https://s2.loli.net/2024/06/02/3wcSmk6rvBAhpTU.png)

CI/CD作为我们软件质量的重要保证之一。我们通过Git Action添加了自己的Runner，并编写了项目的测试脚本来实现CI/CD。保证每次运行前环境全部初始化。

- 所有的日常代码的推送都会被发送到我们自己的服务器，运行单元测试，并直接显示在单次推送的结果后方
- 当发起Pr时，自动会再一次运行单元测试，测试通过之后才可以合并
- 运行单元测试通过之后，构建可执行文件，发布到机器的bin目录下
- 以上2,3条通过之后，对于合并到Master的情况，会构建docker相关的镜像(例如mongodb后端,neo4j后端,vue前端).

**功能开发流程**：

- 我们的软件开发基于迭代开发、敏捷开发。小组成员[TODO: the detail of cooperation/ how hard do we grind]，减少沟通障碍，做到有问题及时解决、沟通，有困难相互请教，这也大大的提高了我们小组的效率。截止15周周末，我们已经完成了所有的功能的开发。基本符合预期进度。
- 对于新功能开发，我们采用"动态分配"方法，根据进度灵活分配成员的任务。项目框架搭建好之后，基本上在任何时间点小组同时在开发两个或者两个以上的需求。一人开发完成之后，交给另外一个组员完成代码的审查和测试，测试通过之后合并到Master
- 功能开发的过程主要是：简要的需求分析->设计API对象->编写该需求的运行逻辑代码->编写相关代码->最终测试
- 具体如下图所示，在整个开发的流程中，我们基本都是在重复下面的流程图。

[TODO: our workflow with repetition]

- 当然我们在开发的过程中也在及时更新文档，如下图所示，是我们的API-Server的详细接口文档，便于组员之间了解对方的开发情况


**开发简介**：

- 项目代码体量大约7000行代码，开发周期大约1.5月
- 完成要求里面的全部功能, 包括需求分析文档,逻辑/概念/物理设计文档, 系统实现演示, 和主要流程图.


## 开箱即用指南

大作业提供开箱即用的配置方式，需要用户设备安装支持 docker 和 docker-compose

1. 下拉仓库，更新子模块

    ```bash
    git clone --recurse-submodules https://github.com/Simonwzm/CS3321-Course-Stack

    git submodule update --remote

    ```

2. 安装 docker && docker-compose

    具体请参考docker[官方文档](https://docs.docker.com/engine/install/)

3. 创建镜像

    ```bash
    # in root directory
    docker-compose build
    ```

4. 启动容器

    ```bash
    # in root directory
    docker-compose up
    ```

通过访问 http://localhost:5173 可以看到前端应用，检查所有服务是否正常拉起

## 开发指南

前后端各部件通过子模块形式连接到主仓库，因此建议首先下拉本仓库，然后按照 git 建议的子模块标准工作流开发，自动同步到子模块自己的仓库，使用示例如下

- 下拉仓库和子模块
  ```bash
    git clone --recurse-submodules https://github.com/Simonwzm/CS3321-Course-Stack

    git submodule update --remote

  ```

- 修改子模块
    ```bash
    cd path/to/submodule
    git checkout -b new-feature-branch
    # Make changes to submodule
    git add .
    git commit -m "Your commit message"
    git push origin new-feature-branch
    ```


- 更新主仓库
    ```bash
    cd ../  # Go back to the main repository
    git add path/to/repo-1
    git commit -m "Update submodule repo-1 to latest commit"
    ```


