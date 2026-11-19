# MOShowRange

《心灵终结 3.3.6》（Mental Omega 3.3.6）的客户端插件。

## 功能

按热键显示选中单位的范围圈（实心半透明）：

- 蓝 = 攻击范围（当前武器最大射程）
- 红 = 最小攻击范围
- 绿 = 警戒范围

## 安装

1. 需要先安装 [Syringe](https://github.com/Ares-Developers/Syringe)（心灵终结自带）。
2. 把 `MOShowRange.dll`、`MOShowRange.dll.inj`、`MOShowRange.ini` 放进游戏根目录。
3. 启动游戏，按 `Alt+Q` 切换显示。

## 配置

```ini
[ShowRange]
Enable=1
Hotkey=Alt+Q
```

## 说明

- 纯渲染插件：只在本地画圈，不修改模拟数据，联机安全。
- 只对当前选中的单位显示。

## 兼容

- 心灵终结 3.3.6（gamemd + Syringe 0.7.3 + Ares 3.0p1）
