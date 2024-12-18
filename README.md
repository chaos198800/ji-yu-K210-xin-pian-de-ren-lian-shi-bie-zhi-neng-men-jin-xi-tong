# 基于K210芯片的人脸识别智能门禁系统

## 项目简介
本项目设计并实现了一个基于K210芯片的人脸识别智能门禁系统。该系统集成了人脸识别、红外测温、门禁控制和蓝牙数据传输等功能，旨在提供一个高效、安全的门禁解决方案。

## 主要功能
1. **人脸识别**：通过Maix Bit开发板实现人脸信息的录入和识别。系统支持在线人脸录入和识别，确保只有授权人员才能通过门禁。
2. **红外测温**：集成90614红外测温模块，实时监测通过人员的体温。体温正常者方可通行，体温异常时触发报警。
3. **门禁控制**：通过闸机动作模拟门禁开关，确保只有满足条件的人员才能通过。
4. **蓝牙数据传输**：系统可通过蓝牙模块将数据上传至电脑，实现数据的实时监测和参数的远程修改。

## 系统流程
1. **模式选择**：通过按键扫描切换系统模式，不同模式下运行不同的代码。
2. **录入模式**：在录入模式下，系统对新录入的人脸信息进行存储，并进行比对分析，防止重复录入。
3. **识别模式**：在识别模式下，系统对欲通过人员进行人脸识别和体温检测，满足条件后闸机动作，允许人员通过。

## 硬件配置
- **主控芯片**：K210芯片
- **开发板**：Maix Bit开发板
- **测温模块**：90614红外测温模块
- **蓝牙模块**：用于数据传输

## 软件环境
- **开发环境**：MaixPy IDE
- **编程语言**：Python

## 使用说明
1. **人脸录入**：在录入模式下，通过Maix Bit开发板录入人脸信息。
2. **人脸识别**：在识别模式下，系统自动进行人脸识别和体温检测，满足条件后闸机打开。
3. **数据监测**：通过蓝牙模块将数据上传至电脑，实时监测门禁系统的状态。

## 注意事项
- 确保开发板和测温模块的连接正确。
- 在录入人脸信息时，避免重复录入相同人员的信息。
- 定期检查系统运行状态，确保门禁系统的正常工作。

## 未来扩展
- 增加语音播报功能，提升用户体验。
- 集成更多传感器，如环境监测传感器，实现多功能一体化。
- 优化算法，提高人脸识别的准确性和速度。

## 联系我们
如有任何问题或建议，请联系项目负责人：[邮箱地址]。

---

通过本项目的实现，我们希望能够为智能门禁系统提供一个高效、安全的解决方案，推动人脸识别技术在实际应用中的普及和发展。

## 下载链接

[基于K210芯片的人脸识别智能门禁系统](https://pan.quark.cn/s/2fb95ed80463)