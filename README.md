# Eureka Marketplace

> Eureka 创新方法论官方插件市场 · 含 **Eureka 创新教练团（8 位专家 + 8 个 Skill）**
>
> 一行添加，永久可用；MIT 开源，免费。

## 里面有什么

| 插件 | 类型 | 说明 |
|---|---|---|
| **eureka-innovation-team** | 专家团（expert team） | 1 位总控 + 8 位创新专家，覆盖 RISE 全旅程：选题 → 洞察 → 创意 → 方案 → 价值 → 验证 → 呈现 → 商业模式 |

专家团成员：顾全程（总控）／寻向远（选题）／察入微（洞察）／思不凡（创意）／谋定行（方案）／价知衡（价值）／验真金（验证）／讲得清（呈现）／赢在算（商业）

内含的 8 个 Skill 也可单独调用：`eureka-ideation` `eureka-insight` `eureka-inspire` `eureka-shape` `eureka-value` `eureka-exam` `eureka-pitch` `eureka-business`

---

## 方式一：添加市场（推荐 · 30 秒）

### WorkBuddy / CodeBuddy 图形界面
1. 打开左侧「插件」（或技能市场）页面
2. 点右上角 **＋ 添加市场**
3. 粘贴下面的地址 → 确定：

```
https://github.com/davidma1973simu/eureka-marketplace
```

### 命令行
```
/plugin marketplace add davidma1973simu/eureka-marketplace
```

添加后安装：
```
/plugin install eureka-innovation-team@eureka-marketplace
```

---

## 方式二：拖进来就用（不用任何命令）

1. 打开本仓库 `plugins/eureka-innovation-team` 文件夹，点右上角 **Code → Download ZIP**，下载后解压
2. 把解压出的 **`eureka-innovation-team` 整个文件夹**复制到本机这个目录里：

```
Windows：C:\Users\你的用户名\.workbuddy\experts\custom\
macOS  ：~/.workbuddy/experts/custom/
```

3. 重启 WorkBuddy → 左侧「专家」面板里就能看到 **Eureka 创新教练团**

---

## 方式三：团队自动安装

在项目或全局 `.codebuddy/settings.json` 里加：

```json
{
  "extraKnownMarketplaces": {
    "eureka-marketplace": {
      "source": {
        "source": "github",
        "repo": "davidma1973simu/eureka-marketplace"
      }
    }
  },
  "enabledPlugins": {
    "eureka-innovation-team@eureka-marketplace": true
  }
}
```

成员一启动 CodeBuddy / WorkBuddy 就自动装好，不用逐个操作。

---

## 怎么用

装好后，在「专家」面板选中 **Eureka 创新教练团**，直接说一句就行：

- 「我有一个想做的方向，帮我走一遍完整的创新流程」
- 「帮我评估一下这个想法值不值得做」
- 「我的创新项目卡住了，帮我理一理下一步做什么」

也可以直接点某个阶段，例如「帮我做个用户访谈提纲」，会自动调用 `eureka-insight`。

---

## 隐私与安全

本插件**全部由 Markdown 定义文件构成**：

- 不含任何可执行代码（无 .js / .py / .sh / 二进制）
- 不发起外部网络请求、不上传任何数据
- 不读取敏感目录、不需要任何密钥

可在 `plugins/eureka-innovation-team` 下自行审阅全部内容。

## 许可证

MIT License © Eureka Lab

## 相关

- 产品与工具地图：https://davidma1973simu.github.io/eureka-hub/
- 联系：870982039@qq.com
