# Dahua Cloud Open Skills

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/)

本仓库是基于[大华云开发者平台](https://open.cloud-dahua.com/) API 封装的实用技能（Skills）集合。旨在提供开箱即用的 Python 工具包，帮助开发者快速将大华 IoT 设备能力集成到大模型应用、自动化运维脚本或智能安防项目中。

## 📂 已收录技能

| 技能目录 | 描述 | 核心功能标签 |
| :--- | :--- | :--- |
| **[dahua-cloud-open-iot-basic-general-kit](./dahua-cloud-open-iot-basic-general-kit)** | 大华云 IoT 设备管理技能 | `设备管理` `GB28181` `SD卡` `WiFi配置` `图片解密` |
| **[dahua-cloud-open-device-image-analysis](./dahua-cloud-open-device-image-analysis)** | 大华云 IoT 设备图像智能分析技能 | `AI视觉` `抓图分析` `安全帽检测` `火焰识别` `行为分析` |

### 1. 设备基础管理套件 (dahua-cloud-open-iot-basic-general-kit)
**适用场景：** 设备批量运维、国标设备上云、回调服务配置。

**核心能力：**
- 支持摄像头/NVR/DVR 的增删改查与状态监控。
- 内置 43 个 API 接口，涵盖 GB28181 接入、SD 卡格式化、WiFi 修改。
- **特性：** 单文件 Python 实现，自动 Token 刷新，支持 CLI 命令行与 SDK 两种调用模式。

### 2. 设备图像分析技能 (dahua-cloud-open-device-image-analysis)
**适用场景：** 安全生产监控、园区异常巡检、连锁门店看护。

**核心能力：**
- 远程触发设备抓拍，并调用大模型进行实时图像分析。
- 支持检测人/车/物，以及安全帽、口罩、火焰、摔倒、区域入侵等特定事件。
- 返回结构化分析结果，便于二次预警联动。

## 🚀 快速开始

每个子目录均包含独立的 `README.md` 和示例代码，请进入具体技能文件夹查看详细配置。

**通用步骤：**
1.  **克隆仓库：**
    ```bash
    git clone https://github.com/DoLynkDeveloper/DahuaCloudOpenSkills.git
    ```
2.  **安装依赖：**
    ```bash
    pip install -r requirements.txt
    ```
3.  **配置密钥：** 配置你的大华云开发者平台`Product ID`、`AppKey` 和 `AppSecret`。

## 📅 更新计划

本仓库将持续更新，计划逐步覆盖大华云开放平台的以下方向：
- [ ] 实时拉流
- [ ] 云台控制
- [ ] 云端录像与回放管理
- [ ] 更多内容


欢迎 **Watch** 本仓库获取最新动态。

## 📄 License
本项目基于 MIT License 开源，详情请见 [LICENSE](LICENSE) 文件。

---

*本仓库中的 Skills 均需配合[大华云开发者平台](https://open.cloud-dahua.com/)账号使用。*
