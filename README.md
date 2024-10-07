# DAU Prediction Tool

这是一个在线日活跃用户(DAU)预测工具,基于留存率模型预测应用的未来 DAU 趋势,帮助产品经理制定用户增长策略。

## 功能特点

- 输入每日新增用户数、次日留存率、7日留存率和30日留存率,预测未来的 DAU 趋势
- 根据输入的留存率数据自动生成留存率拟合曲线及其数学表达式
- 以表格形式展示 DAU 预测的详细数据,包括每日新增用户数、历史留存用户数和留存率
- 提供预测数据的图表可视化展示
- 支持预测数据的 Excel 文件导出功能

## 使用说明

1. 打开 `index.html` 文件,在浏览器中访问 DAU 预测工具页面。
2. 输入以下参数:
   - 每日新增用户数
   - 新用户次日留存率(%)
   - 新用户7日留存率(%)
   - 新用户30日留存率(%)
   - 预测天数
3. 点击"预测"按钮,工具将根据输入的参数生成 DAU 预测结果。
4. 查看 DAU 预测趋势图表、留存率拟合曲线和详细数据表格。
5. 如需导出预测数据,点击"下载 Excel"链接,将数据保存为 CSV 文件。

## 文件结构

- `index.html`: 项目主页,包含 DAU 预测工具的 HTML 结构和样式
- `script.js`: 包含 DAU 预测工具的 JavaScript 逻辑代码
- `readme.md`: 项目说明文档

## 技术栈

- HTML
- CSS
- JavaScript
- ECharts

## 贡献指南

欢迎对本项目提出改进建议和贡献代码。如果您发现了任何问题或有新的功能请求,请在 GitHub 上提交 Issue。如果您希望贡献代码,请先 Fork 本仓库,然后提交 Pull Request。

## 许可证

本项目采用 MIT 许可证。详情请参阅 [LICENSE](./LICENSE) 文件。
