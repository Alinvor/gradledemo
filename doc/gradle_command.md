# Gradle Command

- [一. Gradle 命令](#一-gradle-命令)
- [二. gradlew 命令](#二-gradlew-命令)
  - [2.1 查看项目/任务命令](#21-查看项目任务命令)

## 一. Gradle 命令

属性命令:

```groovy
gradle hello -Pabc
```

## 二. gradlew 命令

```gradle
// 安装命令
gradle wrapper

// 运行命令
./gradlew hello
```

### 2.1 查看项目/任务命令

```gradle
// 项目命令
./gradlew -q project

// 任务命令
./gradlew <project-path>:tasks
```
