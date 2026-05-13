# Python数据分析学习

本项目包含Python数据分析的核心内容，从NumPy科学计算到Pandas数据处理，再到数据可视化，最后通过房地产市场分析进行实战演练。

## 内容结构

### 1. NumPy科学计算 (`code/1.numpy学习.ipynb`)
NumPy是Python科学计算的基础库，提供了高性能的多维数组对象。
- ndarray对象创建与属性
- 数组索引与切片
- 数据类型与广播机制
- 常用数学与统计函数

### 2. Pandas核心数据结构 (`code/2.series学习.ipynb`)
Pandas是基于NumPy构建的数据处理库，其Series对象是处理一维数据的利器。
- Series创建与访问
- 索引与数据筛选
- 运算与对齐机制
- 常用统计方法

### 3. DataFrame数据处理 (`code/3.DataFrame学习.ipynb`)
DataFrame是Pandas最核心的数据结构，适合处理二维表格数据。
- DataFrame创建与属性
- 数据访问方法
- 数据清洗与处理
- 数据变形与聚合

### 4. 数据分析实战 (`code/4.数据分析.ipynb`)
综合运用Pandas进行数据分析的完整流程。
- 数据导入导出
- 缺失值与异常值处理
- 时间数据处理
- 数据分箱与特征工程

### 5. Matplotlib可视化 (`code/5.matplotlib学习.ipynb`)
Matplotlib是Python最基础的可视化库。
- 折线图、柱状图、饼图
- 散点图、箱线图
- 组合图与样式设置

### 6. Seaborn高级可视化 (`code/6.seaborn学习.ipynb`)
Seaborn是基于Matplotlib的高级可视化库，适合统计图形绘制。
- 分布图与核密度估计
- 分类数据可视化
- 关系图与热力图

### 7. 房地产市场分析 (`code/7.房地产市场分析.ipynb`)
综合实战项目，使用真实房地产数据进行全流程分析。
- 数据清洗与特征工程
- 多维度数据分析
- 可视化仪表盘

### 8. PyEcharts交互可视化 (`code/8.pyecharts学习.ipynb`)
PyEcharts生成交互式图表，适合数据仪表盘和报告展示。
- 折线图、柱状图、饼图
- 地图、词云、雷达图
- 组合图表与主题

## 文档

详细的学习文档位于 `docs/` 目录：
- `01-numpy.md` - NumPy详细教程
- `02-pandas-series.md` - Pandas Series教程
- `03-pandas-dataframe.md` - DataFrame教程
- `04-data-analysis.md` - 数据分析实战
- `05-matplotlib.md` - Matplotlib教程
- `06-seaborn.md` - Seaborn教程
- `07-real-estate.md` - 房地产市场分析
- `08-pyecharts.md` - PyEcharts教程

## 数据文件

示例数据位于 `code/data/` 目录：
- `penguins.csv` - 企鹅数据集
- `weather.csv` - 天气数据
- `employees.csv` - 员工数据
- `sleep.csv` - 睡眠数据
- `house_sales.csv` - 房产销售数据
- `products.json` - 产品数据

## 环境配置

推荐使用Anaconda创建虚拟环境：

```bash
conda create -n data_analysis python=3.9
conda activate data_analysis
pip install numpy pandas matplotlib seaborn pyecharts jupyter
```

## 运行notebook

```bash
jupyter notebook
```

然后在浏览器中打开对应的notebook文件即可学习。
