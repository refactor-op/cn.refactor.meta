# Refactor Packages

[![Unity](https://img.shields.io/badge/Unity-2021.3+-black?logo=unity)](https://unity.com)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 包

| 包名 | 描述 | 源码仓库 |
| :--- | :--- | :--- |
| **com.refactor.fsm** | 轻量级、高性能的状态机实现，支持状态栈、分层状态机与流式建造 | [refactor-op/com.refactor.fsm](https://github.com/refactor-op/com.refactor.fsm) |
| **com.refactor.gas** | 基于字节码的属性与公式系统，支持 Float/Double 精度 | [refactor-op/com.refactor.gas](https://github.com/refactor-op/com.refactor.gas) |
| **com.refactor.pooling** | 零分配、确定性生命周期管理的对象池，支持自定义策略与 RAII 模式 | [refactor-op/com.refactor.pooling](https://github.com/refactor-op/com.refactor.pooling) |

## 安装

### 通过 Package Manager (推荐)

1. 打开管理界面 `Edit/Project Settings/Package Manager`
2. 添加 Scoped Registry：

```text
Name: package.openupm.com
URL: https://package.openupm.com
Scope(s): com.refactor
```

3. 打开管理界面 `Window/Package Manager`
4. 切换到 `My Registries`，搜索 `com.refactor` 即可安装

### 通过 Packages

直接修改 Packages 文件夹下的清单文件 `manifest.json`：

```json
{
  "dependencies": {
    "com.refactor.xxx": "x.y.z"
  },
  "scopedRegistries": [
    {
      "name": "package.openupm.com",
      "url": "https://package.openupm.com",
      "scopes": [
        "com.refactor"
      ]
    }
  ]
}
```

> **注意**：请根据需求选择版本号

### 通过 Github 下载安装

在发布的 [Release](https://github.com/refactor-op/com.refactor.main/releases) 版本中，选择最新版本下载 Source Code 压缩包

或者使用 Git URL 安装：

```text
https://github.com/refactor-op/com.refactor.xxx.git
```

## 贡献指南

欢迎提交 PR & Issue
