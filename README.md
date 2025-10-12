<div align="center">
  <h1>Refactor Packages</h1>
  
  <p>
    <img src="https://img.shields.io/badge/Unity-2021.3+-black?logo=unity" />
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" />
    <img src="https://img.shields.io/badge/Language-C%23-239120?logo=c-sharp" />
  </p>
  
  <!-- <p>
    <a href="#快速开始">快速开始</a> •
    <a href="#贡献指南">贡献指南</a> •
  </p> -->
</div>

## 包

- **[cn.refactor.pool](https://github.com/refactor-op/cn.refactor.pool)**: 高性能 0GC 对象池 ![完成](https://img.shields.io/badge/状态-完成-brightgreen)
- **[cn.refactor.pool.extra](https://github.com/refactor-op/cn.refactor.pool.extra)**: 额外的对象池功能 ![完成](https://img.shields.io/badge/状态-完成-brightgreen)
- **时钟 & 调度器**: 高精度时间管理和任务调度 ![进行中](https://img.shields.io/badge/状态-进行中-yellow)
- **[cn.refactor.fsm](https://github.com/refactor-op/cn.refactor.fsm)**: 高性能有限状态机 ![完成](https://img.shields.io/badge/状态-完成-brightgreen)
- **响应式 & 事件系统**: 基于 R3 的事件处理 ![计划中](https://img.shields.io/badge/状态-计划中-lightgrey)
- **依赖注入**: 轻量级 DI 容器 ![计划中](https://img.shields.io/badge/状态-计划中-lightgrey)
- **UI 框架**: MVVM 模式的 UI 解决方案 ![计划中](https://img.shields.io/badge/状态-计划中-lightgrey)
- **本地化**: 多语言支持系统 ![计划中](https://img.shields.io/badge/状态-计划中-lightgrey)
- **序列化**: 高性能序列化库 ![计划中](https://img.shields.io/badge/状态-计划中-lightgrey)
- **数学库扩展**: 游戏数学工具集 ![计划中](https://img.shields.io/badge/状态-计划中-lightgrey)
- **编辑器扩展**: Unity 编辑器增强工具 ![计划中](https://img.shields.io/badge/状态-计划中-lightgrey)
- **背包系统**: 完整的物品管理系统 ![计划中](https://img.shields.io/badge/状态-计划中-lightgrey)
- **音频管理**: 3D 音频和音效管理 ![计划中](https://img.shields.io/badge/状态-计划中-lightgrey)
- **存档回放**: 游戏状态保存和回放 ![计划中](https://img.shields.io/badge/状态-计划中-lightgrey)
- **资源加载**: 异步资源管理系统 ![计划中](https://img.shields.io/badge/状态-计划中-lightgrey)
- **热更新**: 代码和资源热更新 ![计划中](https://img.shields.io/badge/状态-计划中-lightgrey)
- **网络通信**: 高性能网络库 ![计划中](https://img.shields.io/badge/状态-计划中-lightgrey)

## 安装

### 一, 通过 Scoped Registry (推荐)

1. 打开 Unity Package Manager.
2. 在项目的 `Packages/manifest.json` 中添加 Scoped Registry:

```json
{
  "scopedRegistries": [
    {
      "name": "Refactor Packages",
      "url": "https://npm.pkg.github.com",
      "scopes": ["refactor-op"]
    }
  ],
  "dependencies": {
    "@refactor-op/cn.refactor.xxx": "1.x.x"
  }
}
```

### 二, 通过 Git URL

1. 打开 Unity Package Manager.
2. 点击 `+` → `Add package from git URL`.
3. 输入包的 Git URL:
   ```
   https://github.com/refactor-op/cn.refactor.xxx.git
   ```

## 贡献指南

欢迎 PR & Issue!

<div align="center">
  <p><i>Your time is limited, so don't waste it living someone else's life.</i></p>
</div>