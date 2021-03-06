# Geektime Todo

## 简介

这是《极客时间》的[《程序员的测试课》](https://time.geekbang.org/column/intro/433) 专栏的 [Todo 项目](https://github.com/dreamhead/geektime-todo) ，本人跟着练习一遍的仓库。

## 基本用法

* 生成 IDEA 工程

```shell
./gradlew idea
```

* 检查

```shell
./gradlew check
```

* 数据库迁移

```shell
./gradlew migrate
```

* 生成构建产物

```shell
./gradlew build
```

* 生成发布包

对于 CLI 项目，运行如下命令
```shell
./gradlew uberJar
```

在 todo-cli/build/libs 下就会生成一个 Uber JAR，它是可以独立运行的。

```shell
java -jar todo-uber-<version>.jar
```
