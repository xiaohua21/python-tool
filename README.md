🛠️ Python工具箱
一个功能强大的Python自动化工具集合，包含桌面自动化和栅格数据处理工具

https://img.shields.io/badge/%E8%AE%B8%E5%8F%AF%E8%AF%81-MIT-blue.svg
https://img.shields.io/badge/Python-3.6%252B-brightgreen.svg

✨ 包含的工具
🖥️ 桌面自动化工具
✅ 录制功能 - 精确捕捉鼠标移动、点击、滚动和键盘操作

✅ 回放功能 - 支持0.1x至10000x的速度调整和重复播放

✅ 文件管理 - 保存和加载JSON格式的自动化脚本

✅ 全局快捷键 - F9录制、F10播放、F12紧急停止

🗺️ 栅格归一化工具
✅ 批处理功能 - 批量处理栅格数据文件

✅ ArcGIS集成 - 作为Python工具箱(.pyt)集成到ArcGIS中

✅ 多种格式 - 支持常见的栅格数据格式

✅ 可视化界面 - 在ArcGIS中提供友好的参数设置界面

📋 系统要求
Python 3.6 或更高版本

桌面自动化工具：Windows / macOS / Linux

栅格处理工具：ArcGIS Pro 或 ArcMap（必需）

📦 快速安装
bash
# 克隆仓库
git clone https://github.com/xiaohua21/python-tool.git
cd python-tool

# 安装桌面自动化工具依赖
cd desktop-automation
pip install -r requirements.txt

# 或安装栅格处理工具依赖
cd ../raster-normalization
pip install -r requirements.txt
🚀 快速开始
桌面自动化工具
bash
cd desktop-automation
python zidonghua.py
快捷键：

F9：开始/停止录制

F10：开始/停止播放

F12：紧急停止所有操作

栅格归一化工具
打开 ArcGIS Pro 或 ArcMap

在目录窗口中右键 → 添加工具箱

选择 raster-normalization/RasterNormalization.pyt

双击工具图标开始使用

📂 项目结构
text
python-tool/
├── desktop-automation/          # 🖥️ 桌面自动化工具
│   ├── zidonghua.py            # 主程序文件
│   ├── README.md               # 详细使用说明
│   └── requirements.txt        # Python依赖包
├── raster-normalization/       # 🗺️ 栅格处理工具
│   ├── RasterNormalization.pyt # ArcGIS工具箱
│   ├── README.md               # ArcGIS使用说明
│   └── requirements.txt        # 数据处理依赖包
├── README.md                   # 📋 本项目总说明
└── LICENSE                     # ⚖️ MIT许可证
💡 使用场景
桌面自动化工具应用
办公自动化：批量处理文档、表格填充

软件测试：自动化UI测试脚本

游戏辅助：重复任务自动化执行

数据录入：自动填写表单和系统

栅格处理工具应用
遥感分析：卫星影像数据处理

地理研究：DEM、土地利用数据分析

环境监测：气象、水文数据归一化

城市规划：空间数据批量处理

⚠️ 注意事项
桌面自动化工具
权限要求：某些系统需要管理员权限才能使用全局快捷键

安全机制：移动鼠标到屏幕四角可紧急停止操作

性能建议：高重复次数建议使用较快的播放速度

栅格处理工具
软件要求：必须安装ArcGIS Pro或ArcMap

数据兼容：确保输入数据格式与工具兼容

处理时间：大文件处理可能需要较长时间

🎓 常见问题
Q: 桌面工具的快捷键不起作用怎么办？
A: 尝试以管理员身份运行程序，或检查是否有其他程序占用了相同快捷键。

Q: 栅格工具在ArcGIS中不显示怎么办？
A: 检查ArcGIS版本是否兼容，确保.pyt文件没有损坏。

Q: 如何同时使用两个工具？
A: 两个工具相互独立，可以分别安装在各自的Python环境中。

Q: 可以在没有ArcGIS的电脑上使用栅格工具吗？
A: 不可以，栅格处理工具依赖ArcGIS的运行环境。

🤝 贡献指南
欢迎为Python工具箱贡献力量！

Fork 本仓库

创建特性分支 (git checkout -b feature/新功能)

提交更改 (git commit -m '添加新功能')

推送分支 (git push origin feature/新功能)

创建Pull Request

📄 许可证
本项目采用 MIT 许可证 - 详见 LICENSE 文件。

👨‍💻 作者
xiaohua21 - 项目创建者和维护者

🙏 致谢
感谢所有用户和贡献者的支持

借鉴了Python和GIS社区的最佳实践

📞 反馈和支持
如有任何问题或建议，请：

在GitHub上提交 Issue

查看各工具目录中的详细文档

用 ❤️ 开发 | Made with ❤️ by xiaohua21
