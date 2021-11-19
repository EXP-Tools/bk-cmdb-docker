# bk-cmdb-docker

> docker 一键部署 蓝鲸 CMDB

------


[![license](https://img.shields.io/badge/license-mit-brightgreen.svg?style=flat)](https://github.com/Tencent/bk-cmdb/blob/master/LICENSE.txt)
[![Release Version](https://img.shields.io/badge/release-3.2.19-brightgreen.svg)](https://github.com/Tencent/bk-cmdb/releases)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/Tencent/bk-cmdb/pulls)
[![BK Pipelines Status](https://api.bkdevops.qq.com/process/api/external/pipelines/projects/cc/p-c02db56ac633447eb2e740b3fd0b6d2b/badge?X-DEVOPS-PROJECT-ID=cc)](http://api.bkdevops.qq.com/process/api-html/user/builds/projects/cc/pipelines/p-c02db56ac633447eb2e740b3fd0b6d2b/latestFinished?X-DEVOPS-PROJECT-ID=cc)



## 使用说明

- 执行 `docker-compose up -d` 运行
- 第一次启动可能前端会报错 `rewrite request failed, oops, there is no topo can be used`，但会成功初始化数据库
- 这时执行 `docker-compose down` 停止，再执行 `docker-compose up -d` 重启即可
- 打开 [http://127.0.0.1:8090](http://127.0.0.1:8090) 访问 CMS


## 相关资料

- 官方文档：https://bk.tencent.com/docs/document/6.0/152/6962
- Github 仓库：https://github.com/Tencent/bk-cmdb


