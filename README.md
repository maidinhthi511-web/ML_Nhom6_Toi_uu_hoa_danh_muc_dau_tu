# ML_Nhom6
# Tên dự án: Ứng dụng mô hình học máy trong tối ưu hóa danh mục đầu tư 

## 📝 Mô tả ngắn
Dự án này sử dụng các thuật toán Học máy(Machine Learning): LSTM và Prophet để dự đoán lợi nhuận kỳ vọng và rủi ro cho từng cổ phiếu. Mục tiêu của dự án là xây dựng một mô hình học máy để lựa chọn danh mục đầu tư và dự đoán tỷ trọng tối ưu cho các mã cổ phiếu trong danh mục.
***
## 🚀 Cài đặt
Thực hiện các bước sau :
1.  **Cài đặt môi trường (Clone Repository):**
    ```bash
    git clone https://github.com/maidinhthi511-web/ML_Nhom6_Toi_uu_hoa_danh_muc_dau_tu.git cd ML_Nhom6_Toi_uu_hoa_danh_muc_dau_tu
    ```

2.  **Cài đặt các thư viện cần thiết:**
    ```bash
    pip install -r requirements.txt
    ```

***

## 🛠️ Hướng Dẫn Sử Dụng (Usage)

Sau khi cài đặt thành công, bạn có thể huấn luyện mô hình và thực hiện dự đoán:

1.  **Huấn luyện Mô hình:**
    ```bash
    python src/train.py
    ```

2.  **Thực hiện Dự đoán:**
    ```bash
    python src/predict.py --input_file [file_dữ_liệu_mới]
    ```

***

## 🌳 Cấu Trúc Dự Án (Project Structure)

ML_project-name/                             
├── README.md                 # File giới thiệu tổng quan dự án, hướng dẫn cài đặt và chạy code                                                 
├── requirements.txt          # Liệt kê các thư viện cần thiết (tạo bằng pip freeze > requirements.txt)                                      
├── data/                     # Chứa dữ liệu                           
│   ├── unprocessed/          # Chứa dữ liệu thô, không chỉnh sửa                                   
│   └── processed/            # Chứa dữ liệu đã qua tiền xử lý                                  
├── notebooks/                # Chứa các file Jupyter Notebook cho EDA, thử nghiệm nhanh                                   
│   ├── 1.0-EDA.ipynb         # EDA, thử nghiệm nhanh                                        
│   └── 2.0-model-prototyping.ipynb # Thử nghiệm, xây dựng và so sánh các mô hình                                    
├── src/                      # Chứa mã nguồn chính của dự án                          
│   ├── data_processing.py    # Các hàm tiền xử lý dữ liệu                                  
│   ├── train.py              # Script để huấn luyện mô hình                               
│   └── predict.py            # Script để đưa ra dự đoán từ mô hình đã lưu                                  
├── models/                   # Chứa các file mô hình đã được huấn luyện và lưu lại (ex: joblib .pkl)              
└── reports/                  # Chứa báo cáo, hình ảnh, biểu đồ                                
    └── figures/              # Các biểu đồ, hình ảnh đã tạo
    
## Thông tin tác giả (Author)
Nhóm tác giả:                   
Nguyễn Thị Nguyên                                       
Đinh Thị Mai _ Mail: maidinhthi511@gmail.com                               
Lê Thị Thùy Dương                                              
Nguyễn Thị Trà
