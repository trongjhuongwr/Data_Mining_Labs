# Data Mining Labs

Trường Công nghệ và Thiết kế - UEH University  
Repository này lưu trữ các bài thực hành môn Data Mining.

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Data](https://img.shields.io/badge/Dataset-Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white)
![Analysis](https://img.shields.io/badge/Focus-EDA%20%26%20Statistics-2E8B57?style=flat)

## Cấu trúc

```text
Data_Mining_Labs/
|-- README.md
|-- .gitignore
`-- Lab1/
    |-- lab1.ipynb            # Notebook phân tích dữ liệu
    `-- netflix_titles.csv    # Dataset Kaggle (đã ignore khi push git)
```

## Danh sách bài thực hành

| STT | Buổi học | Nội dung chính | Tệp | Trạng thái |
| :---: | :--- | :--- | :--- | :---: |
| 01 | Lab 1 | Descriptive statistics và visualization trên Dataset Tabular từ Kaggle | [Lab1](./Lab1) | Hoàn thành |

## Nội dung đã thực hiện ở Lab 1

- Chọn dataset tabular từ Kaggle: Netflix Titles.
- Tính các chỉ số thống kê:
  Quartiles, Inter-quartile range (IQR), Five-number summary, outlier theo IQR, variance, standard deviation.
- Vẽ các biểu đồ cơ bản:
  distribution (KDE), boxplot, histogram, quantile plot, quantile-quantile (Q-Q) plot, scatter plot.

## Hướng dẫn chạy

1. Clone repository.
2. Mở [Lab1/lab1.ipynb](Lab1/lab1.ipynb) bằng VS Code hoặc Jupyter Notebook.
3. Chọn Python kernel trong môi trường ảo.
4. Chạy lần lượt các cell để tải dữ liệu, tính thống kê và vẽ biểu đồ.

## Yêu cầu môi trường

- Hệ điều hành: Windows 10/11, Linux hoặc macOS.
- Python: 3.10 trở lên (khuyến nghị 3.11+).
- Thư viện chính: numpy, pandas, matplotlib, seaborn, scipy.
- Công cụ: VS Code (Jupyter extension) hoặc Jupyter Notebook/Lab.

---
2026 UEH - Data Mining Labs
