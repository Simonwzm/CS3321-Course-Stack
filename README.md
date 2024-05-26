# Course-Stack

这是 CS3321 数据库技术课程的小组作业仓库。我们设计了一个课程信息查询和可视化的数据库网络应用，名称是 Course-Stack

[添加小组成员介绍]

[添加项目详细介绍]

[添加使用指南]

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

## TODO(maybe)

[添加亮点/效果展示]

[添加项目总体架构设计]

[添加各模块实现的思路/架构/api设计等]

[添加开发进度记录]

[添加其他材料]

