# 商业分析 (Commercial Analysis Playground)

> **项目愿景：** 利用 Python 数据流与 AI 逻辑推理，重构商业分析工作流。本项目旨在探索自动化获取金融数据、清洗处理及可视化呈现的完整闭环。

## 核心项目 (Featured Projects)

### 001. NVIDIA (NVDA) 股价趋势分析
* **背景：** 针对 AI 硬件龙头企业，追踪其过去一年的二级市场表现。
* **技术栈：** `yfinance` (数据源), `matplotlib` (可视化), `pandas` (数据处理)
* **分析结果：**
    ![NVIDIA Stock Price 24-25](https://github.com/haoqianli-glitch/Commercial-Analysis-Playground/blob/520cf6bfa6acf740f7c9b695522c63558acbe746/%20NVIDIA_Chart.png))
    *股价在2025年11月达到了高峰，几乎是2025年Q1-Q2的两倍

## 技术栈 (Tech Stack)
* **Language:** Python 3.10+
* **Tools:** Cursor, VS Code
* **AI Assistants:** Gemini 3.0 Pro

## 如何运行 (How to Run)
```bash
# 克隆仓库
git clone [https://github.com/haoqianli-glitch/Commercial-Analysis-Playground.git](https://github.com/haoqianli-glitch/Commercial-Analysis-Playground.git)

# 安装依赖
pip install -r requirements.txt

# 运行脚本
python3 nvidia_analysis.py
