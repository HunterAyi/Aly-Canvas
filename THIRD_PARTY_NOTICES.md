# 第三方组件与许可材料

Aly画布自有源码暂未开放；第三方组件保留各自许可证、署名及合法替换权利。

- 画布核心与安装器：各自组件内的 `THIRD_PARTY_NOTICES.txt`、`third-party-inventory.json` 和 `licenses/` 按实际编译依赖登记；包括Python及相关运行库。
- 小A：官方 OpenAI Codex CLI `rust-v0.166.0`，Apache-2.0；LICENSE和NOTICE在 `canvas-assistant-0.8.0.zip`。
- 本地CPU环境：Python3.11.9、PyTorch2.9.0+cpu、ONNX Runtime1.31.1等。原始许可证在 `canvas-python-cpu-0.8.0.zip` 的 `licenses/`、发行包许可目录及 `workers/BEN2-LICENSE.txt`。
- 本地模型：BEN2和MobileSAM的准确权重与原始许可随 `canvas-models-0.8.0.zip` 提供。模型保留各自许可，不适用Aly自有代码的许可状态。
- 音视频：独立的FFmpeg8.1 LGPL构建、OpenH2642.7、dav1d1.5.4、zlib1.3.2、LAME3.100及运行库，未启用GPL/nonfree。对应源码、构建配置和原始许可随 `canvas-media-0.8.1.zip` 提供；安装后仍为独立可替换组件。GCC运行库许可及Runtime Library Exception也包含在内。

第三方材料不表示公开Aly自有源码。第三方来源和许可变更须按具体组件重新核对。
