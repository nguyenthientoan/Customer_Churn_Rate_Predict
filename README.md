# Customer_Churn_Rate_Predict

**1/ Nắm rõ dữ liệu**
Trong suốt project, tôi sử dụng tập data là demographic.csv
Việc tận dụng các feature về thông tin cá nhân sẽ giúp xây dựng mô hình xác định các đối tượng rời bỏ cao, qua đó giúp doanh nghiệp đưa ra các giải pháp hợp lý.


**2/ Output của project**

Sẽ có 2 output chính trong project:
- Mô hình nào sẽ là mô hình hiệu quả (LGBMClassifier)
- Những feature nào sẽ mang lại hiệu quả


**3/ Các mô hình dùng trong project này**

Logistics
LGBMClassifier
RandomForestClassifier
XGBClassifier


**4/ Nắm rõ các chỉ số giúp đánh giá một mô hình tốt**

Precision (Chỉ số Precision):
Precision là tỷ lệ số lượng dự đoán đúng của lớp positive (true positives) trên tổng số lượng dự đoán positive (true positives + false positives).
Precision đo lường mức độ chính xác của các dự đoán positive của mô hình. Một precision cao cho thấy mô hình có khả năng giảm thiểu số lượng false positives, tức là tránh dự đoán sai các trường hợp negative thành positive.

Recall (Chỉ số Recall):
Recall, còn được gọi là true positive rate hoặc sensitivity, là tỷ lệ số lượng dự đoán đúng của lớp positive (true positives) trên tổng số lượng thực sự thuộc lớp positive (true positives + false negatives).
Recall đo lường khả năng của mô hình trong việc bắt được tất cả các trường hợp thuộc lớp positive. Một recall cao cho thấy mô hình có khả năng tránh bỏ sót các trường hợp thực sự thuộc lớp positive.

F1 Score (Chỉ số F1):
F1 score là một trung bình điểm số giữa precision và recall, được tính bằng công thức F1 = 2 * (precision * recall) / (precision + recall).
F1 score kết hợp cả khả năng chính xác của precision và khả năng bắt các trường hợp positive của recall thành một chỉ số đơn để đánh giá hiệu suất tổng thể của mô hình.
Thường thì F1 score được ưa chuộng khi bạn quan trọng cả precision và recall và muốn có một phép đo cân bằng giữa chúng.

Support:
Support đơn giản là số lượng mẫu thực sự thuộc vào mỗi lớp. Nó không phụ thuộc vào dự đoán của mô hình.
Support có thể giúp bạn hiểu rõ hơn về phân phối của các lớp và có thể hữu ích khi cần phân tích hiệu suất của mô hình đối với từng lớp riêng biệt.

**5/ Một số technique để feature engineering**

