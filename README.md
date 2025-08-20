### 小项目描述

基于pixi.js做一个简单的圆形温度计，显示实时温度值，就像汽车仪表盘那样。
参考：
[Introduction | PixiJS](https://pixijs.com/8.x/guides/getting-started/intro)
[开始 | Vite 官方中文文档](https://cn.vite.dev/guide/)
[TypeScript: JavaScript With Syntax For Types.](https://www.typescriptlang.org/)
[Configuring Vitest | Vitest](https://vitest.dev/config/#setupfiles)
#### 要求
- 使用的技术栈包括typescript、pixi.js、HTML、CSS、vite构建工具
- 使用git管理这个小项目
- 使用vitest做单元测试（注意不要测试涉及pixi的部分，涉及pixi的部分因为使用了浏览器的API，需要更复杂的配置）
### 指南

- 基于vite和vue得typescript项目
- 添加pixi.js依赖
- vitest测试逻辑部分
- 画一个背景和刻度
- 美化可以使用加载SVG作为pixi精灵方式，美化的SVG可以去互联网上搜
- 指针和数字是变化的表示温度
- 模拟温度数据（15-45度随机变化）
- 指针平滑转动动画
- 温度超过35度时变红色报警

### 最终效果：

- 一个圆形温度计仪表
- 指针实时转动显示温度
- 数字显示当前温度值
- 超温报警（颜色变化）