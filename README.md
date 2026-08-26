# 距离 Emily 登机时间 · CA994 Countdown

[![Live App](https://img.shields.io/badge/Live_App-打开倒计时-0969da?style=for-the-badge)](https://xudaniel.github.io/ca994-countdown/)
[![Deploy to GitHub Pages](https://github.com/xudaniel/ca994-countdown/actions/workflows/pages.yml/badge.svg)](https://github.com/xudaniel/ca994-countdown/actions/workflows/pages.yml)

一个电子登机牌风格的实时登机倒计时应用。无需后端，可直接通过 GitHub Pages 访问。

## Live App

### [打开实时倒计时 →](https://xudaniel.github.io/ca994-countdown/)

| 项目 | 时间 |
| --- | --- |
| Emily 登机时间 | **2026年8月28日 01:15（北京时间）** |
| 对应多伦多时间 | 2026年8月27日 13:15（EDT） |
| CA994 计划起飞 | 2026年8月28日 04:15（北京时间） |

## 功能

- 实时显示剩余小时、分钟和秒
- 高级登机牌界面，突出 YYZ → PEK、Emily 与 CA994
- 真实 Code 128 登机牌条码与动态航线进度
- 使用带时区的绝对时间计算，不受访客设备显示时区影响
- 支持桌面和手机浏览器
- 静态单页应用，无追踪、无登录、无后端
- 通过 GitHub Actions 自动部署到 GitHub Pages

## 本地打开

下载仓库后，直接使用浏览器打开 `index.html` 即可。

## 自动部署

每次更新 `main` 分支后，`Deploy to GitHub Pages` 工作流会自动发布最新版本。

## License

[MIT](LICENSE)

第三方素材说明见 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)。
