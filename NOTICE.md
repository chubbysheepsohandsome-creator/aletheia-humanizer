# 来源与使用说明

本项目是本次为用户创建的私人本机工作台，版本 0.1.0。

- `detector/` 六个文件来自用户提供的 ALETHEIA 当前站点代码包：`engine.js`、`model.js`、`deep.js`、`deep_model.js`、`deep_model_v182.js`、`deep_model_seg06.js`。这些文件按原样复制，沿用原权利与适用条件；本交付不额外授予其公开或商业再分发许可。原项目资料注明，部分训练数据/权重在商业使用前需要许可审查。
- `lib/docx-reader.js` 来自同一代码包，保留原有说明。
- `public/vendor/pdf.min.js`、`pdf.worker.min.js` 为原包内 pdf.js 3.11.174，Apache-2.0，保留原文件许可头，完整许可在 `LICENSE-pdfjs.txt`。
- Inter、Cormorant Garamond 字体文件来自原代码包的本地字体，许可见 `LICENSE-fonts-OFL.txt`。
- 新增工作台代码与原创 AI 演示文本用于本次私人交付。未包含捐赠者原文、私有检查集、真实密钥或原项目训练数据。
- 若同级附带 Ollama 运行文件与 Qwen3 权重，它们独立于工作台源代码，依各自许可使用。Ollama 官方项目为 MIT，Qwen3 4B 模型页标注 Apache-2.0；随下载文件保留其许可。模型权重不放入工作台源代码压缩包。

公开发布、商业化或再分发前应按实际依赖和权重来源完成相应许可确认。本工具没有替你做公开发布。
