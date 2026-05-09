# Nezha Catppuccin Mocha 主题

**语言：** [English](README.md) | 简体中文

一个适用于哪吒监控面板的 Catppuccin Mocha 自定义代码主题。

这个主题面向 Nezha v2，覆盖 `nezha-dash` 用户前台和官方后台管理页面。主题使用官方 Catppuccin Mocha 配色，并避免装饰性渐变，让界面尽量贴近 Mocha 原始色彩体系。

## 预览

![首页概览](assets/home.png)

![服务监控](assets/services.png)

![机器详情](assets/server-detail.png)

## 安装

打开哪吒后台管理：

```text
Dashboard -> Settings -> System Settings
```

把下面两个文件的内容分别粘贴到对应的自定义代码输入框：

| 哪吒字段 | 文件 |
| --- | --- |
| `自定义代码（样式和脚本）` | [`dist/user-custom-code.html`](dist/user-custom-code.html) |
| `仪表板的自定义代码` | [`dist/admin-custom-code.html`](dist/admin-custom-code.html) |

然后点击 `确认` 保存。

## 配色

主题遵循官方 Catppuccin Mocha 配色：

| Token | Hex |
| --- | --- |
| Base | `#1e1e2e` |
| Mantle | `#181825` |
| Crust | `#11111b` |
| Surface0 | `#313244` |
| Surface1 | `#45475a` |
| Overlay1 | `#7f849c` |
| Subtext0 | `#a6adc8` |
| Text | `#cdd6f4` |
| Mauve | `#cba6f7` |
| Blue | `#89b4fa` |
| Green | `#a6e3a1` |
| Red | `#f38ba8` |

参考：[Catppuccin palette](https://catppuccin.com/palette/)。

## 覆盖范围

自定义 CSS 覆盖：

- 用户前台首页卡片、按钮、服务器列表、服务监控卡片、地图视图和机器详情图表。
- 后台管理页面的表单控件、标签页、输入框、卡片、按钮和选中状态。
- Nezha 主题中使用 Tailwind `stone`、`neutral`、`emerald`、`green` 以及图表相关工具类的区域。

## 测试环境

- Nezha `2.0.7`
- 用户前台主题 `nezha-dash` commit `e4ba96e`
- 当前 Nezha v2 官方后台管理页面

## 说明

这个仓库只提供自定义代码片段，不修改哪吒源代码。

本项目与 Catppuccin 和 Nezha 官方无隶属关系。

## 开源协议

MIT License。
