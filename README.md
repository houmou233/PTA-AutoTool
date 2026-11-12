# PTA-AutoTool

PTA（拼题A）自动答题辅助油猴脚本，支持豆包、通义千问、DeepSeek 等多家大模型 API。

## 功能

- **自动答题**：自动遍历题目，调用大模型生成答案
- **打字机模式**：AI 生成答案后逐字输入编辑器，不自动提交，手动检查后再交
- **多家模型**：DeepSeek / 豆包 / 通义千问，自由切换
- **授权系统**：账号注册登录 + 卡密激活，有效期内免登录
- **API 自动同步**：管理员在后台统一配置 API Key，用户登录后自动获取，无需手动填写
- **可拖拽面板**：支持拖拽、边缘吸附、ESC 收起、默认折叠
- **权限管理**：管理员可封禁用户、延长有效期、查看用量统计

## 安装

1. 安装 [Tampermonkey](https://www.tampermonkey.net/) 浏览器扩展
2. 点击安装脚本：[PTA-AutoTool.user.js](https://raw.githubusercontent.com/houmou233/PTA-AutoTool/main/PTA-AutoTool.user.js)
3. 打开 [PTA](https://pintia.cn/)，右下角出现问号图标即安装成功

## 使用

1. 首次使用会弹出登录/注册窗口
2. 注册需要卡密（联系管理员获取）
3. 登录后自动同步 API 配置，直接开始刷题

## 免责声明

**不能在考试中使用，用了考不上大学后果自负。**

本脚本仅供学习交流使用，使用者需遵守 PTA 平台规则和学校考试纪律。

## License

MIT
