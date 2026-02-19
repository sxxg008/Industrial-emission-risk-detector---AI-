# Industrial-emission-risk-detector
# 工业AI-园区空气环保审计项目

This repository is for demonstration purposes only. Sample data included.
本代码仓库仅用于演示，内含示例数据。

实验性质的工业AI项目，主要用于工业AI的落地闭环能力展示。

一、内容：

1.基于全美国的小时级别空气检测数据，进行大数据筛查，**自动识别二氧化硫（SO₂）/二氧化氮（NO₂）排放异常事件，双污染物联动审计**。生成“风险排名表格”。

程序已经封装好，下载release文件，双击 run.exe 即可开始工作，生成outputs文件夹和“risk_table.csv”（双污染物联动风险审计表）。原始数据已放在data文件夹中。

2.example 展示了项目发展过程和基于地理位置筛选审计的可视化成果，与主程序独立。
包含：
   1.houston_case.ipynb
   2.filtering_demo.ipynb
   3.screenshots of results（成果截图）
   	休斯顿风险地图.png
   	risk_table.csv 风险排名表.png
   	休斯顿联动异常动画截图.png
目前开放案例和演示流程，欢迎交流真实场景。

二、替换csv文件必须包含列名：
	site_id  
	datetime  
	SO2  
	NO2
   
三、release v1.0.rar文件结构：
	README.md
	run.exe
	data/raw/演示数据
	examples/
	    houston_case.ipynb
	    filtering_demo.ipynb
	    visualization_demo.ipynb
	screenshots/

四、适用人群/机构：
- 环境监管部门
- 企业合规管理团队
- 环境咨询公司

--------------------------------
Overview

This repository is for demonstration purposes only. Sample data included.

An experimental industrial AI project, mainly designed to demonstrate the **closed-loop implementation capability of industrial AI**.

## I. Content
1. Based on hourly air monitoring data across the United States, the system conducts big data screening to **automatically identify abnormal emission events of sulfur dioxide (SO₂) / nitrogen dioxide (NO₂) and perform dual-pollutant linkage auditing**, and generates a risk ranking table.

The program is fully packaged. Download the release file and double-click `run.exe` to run it, which will generate an `outputs` folder and `risk_table.csv` (Dual-Pollutant Linkage Risk Audit Table). Raw data is stored in the `data` folder.

2. The `example` section shows the project development process and visualized results of location-based screening & auditing, and runs independently of the main program.

It includes:
1. `houston_case.ipynb`
2. `filtering_demo.ipynb`
3. Screenshots of results
    - Houston Risk Map.png
    - risk_table.csv Risk Ranking Table.png
    - Screenshot of Houston Linkage Anomaly Animation.png

The project currently provides open cases and demonstration workflows. Discussions on real-world application scenarios are welcome.

II. Mandatory Columns for Replaced CSV Files
- `site_id`
- `datetime`
- `SO2`
- `NO2`

III. File Structure of `release v1.0.rar`
- `README.md`
- `run.exe`
- `data/raw/` (demo data)
- `examples/`
    - `houston_case.ipynb`
    - `filtering_demo.ipynb`
    - `visualization_demo.ipynb`
- `screenshots/`

IV. Target Users / Organizations
- Environmental regulatory authorities
- Corporate compliance management teams
- Environmental consulting firms
