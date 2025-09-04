# round2_Data_Science_Competition
Introduction: 
- Thư mục data chứa:
  + data_2019_2025.zip: chứa data_2019_2025.csv lưu data VN30, VNMidcap đã crawl về.
  + vnindex_equity.csv: chứa VNINDEX đã crawl về.
  + SVM_selected.csv: chứa các mã được mô hình SVM dự đoán sẽ tăng 5% trong 20 ngày tới. (Kết quả việc chạy file SVM.ipynb)  
  + wyckoff_selected.csv: chứa các mã được chấm điểm theo phương pháp wyckoff mà nhóm xây dựng
  + final.csv: chứa các mã được chấm điểm bằng phương pháp wyckoff & SVM.
  + fundamental_ratios_2019_2025.csv: chứa kết quả lấy về từ hàm get_ratios
  + fundamental_ratios_extracted_2019_2025.csv: parsing file trên, để lấy được các chỉ số PE, PB, ROE, EPS.

Hướng dẫn chạy: 
- B1: git clone https://github.com/ShenHiYe/round2_Data_Science_Competition
- B2: giải nén data_2019_2025.zip, đặt file data_2019_2025.csv vào folder data. 
- B3 (optional, vì đã có file data_2019_2025.csv, vnindex_equity.csv và fundamental_ratios_extracted_2019_2025.csv ): Chạy file fetch.ipynb
- B4 (optional, vì đã có file SVM_selected.csv): Chạy file SVM.ipynb
- B5: chạy file problem2_FTUTECH.ipynb
