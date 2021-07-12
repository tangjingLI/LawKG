# 法律知识图谱后端

**项目结构**
```
.
├── IntelligentKG
│   └── src
├── Jenkinsfile
├── README.md
└── SpringbootBackend
    ├── pom.xml
    ├── src
```
后端由2个部分组成  
1. SpringBoot项目：实现知识图谱的增删改查
2. Python项目：实现知识图谱的智能化应用

**数据库**  

使用图形数据库`neo4j`.配置在`application.yml`中修改  

**Jenkins**  

部署脚本在`Jenkinsfile`中  

通过`http://114.215.202.211:8082`访问Jenkins

迭代三时迁移到了`http://172.29.7.103:8082`    账户和密码都是SiegeLion

前端使用nginx部署，可以直接通过`172.29.7.103`访问
