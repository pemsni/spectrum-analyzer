# Spectrum Analyzer 光谱分析器

A web-based spectrum analyzer tool that visualizes spectral data from CSV files. 
一个基于网页的光谱分析工具，用于可视化CSV文件中的光谱数据。

## Features 功能
- Upload and visualize spectral data from CSV files 上传并可视化CSV文件中的光谱数据
- Real-time wavelength to color conversion 实时波长到颜色的转换
- Toggle between raw and smoothed data 在原始数据和平滑数据之间切换
- Export visualization as JPG 导出可视化结果为JPG图片

## Usage 使用方法
1. Click the "Choose File" button to upload a CSV file 点击"选择文件"按钮上传CSV文件
2. The CSV file should contain two columns: wavelength and intensity CSV文件应包含两列：波长和强度
3. Use the "Show Raw Data" button to toggle between raw and smoothed data 使用"显示原始数据"按钮在原始数据和平滑数据之间切换
4. Click "Save as JPG" to export the visualization 点击"保存为JPG"导出可视化结果

## CSV Format CSV格式
The CSV file should be formatted as follows: CSV文件应按以下格式：
```
wavelength,intensity
400,0.5
401,0.6
...
```

## Live Demo 在线演示
[View Demo](https://spectrum-analyzer.vercel.app)

## License 许可证
MIT 