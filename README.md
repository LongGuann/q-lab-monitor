# Q-Lab Monitor

Q-Lab Monitor 是一个小型实验数据监测系统。第一版先使用静态网页建立项目骨架，后续再加入模拟数据、趋势展示、异常提醒和 CSV 导出。

## 当前版本

- 版本：v0.1 骨架版
- 日期：2026-06-05
- 状态：页面可以显示 `Q-Lab Monitor 正在运行`

## 文件结构

```text
q-lab-monitor/
  index.html
  styles.css
  app.js
  README.md
```

## 运行方法

直接用浏览器打开 `index.html`。

## 首个可展示证据

2026-06-05 已完成项目骨架：

- 创建 `index.html`、`styles.css`、`app.js`、`README.md`
- 页面标题为 `Q-Lab Monitor`
- 页面运行状态显示 `Q-Lab Monitor 正在运行`
- 验证方式：浏览器打开 `index.html` 后能看到运行状态文本

## 下一步

加入模拟数据源，每 2 秒生成一条温度、湿度、光照数据，并显示在页面上。
