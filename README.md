# Bài tập lớp học phần "Lập trình cho trí tuệ nhân tạo"
## Đề tài "Phân tích dữ liệu Covid-19"
### Dữ liệu
Dữ liệu được lấy từ <a href='https://www.kaggle.com/datasets/georgesaavedra/covid19-dataset'>COVID-19 dataset</a>, dữ liệu thu thập thêm được lấy từ trang https://ourworldindata.org/covid-vaccinations
### Mục đích
- **Phân tích** tình hình chung của **đại dịch Covid-19** trên toàn thế giới
- **Tập trung** vào việc phân tích và xây dựng mô hình dự đoán tại Việt Nam
- **Sử dụng** các phương thức chuẩn hóa dữ liệu như _MinMaxScaler, StandardScaler, ..._
- **Sử dụng** một số mô hình **thống kê** như _ARIMA, SARIMA_ và mô hình **học máy** như _Linear Regression, AdaBoostRegressor, ElasticNet, ..._
- **Đánh giá** mô hình thông qua các giá trị _RMSE, AIC, ..._
### Cấu trúc bài tập lớn
- `dataset`: tệp các dữ liệu dùng trong bài tập lớn.
- `img`: tệp các ảnh đầu ra từ việc trực quan hóa dữ liệu
- `requirement.txt`: các thư viện đã được cài đặt
- `data_preprocessing.ipynb`: tệp notebook dùng cho việc tiền xử lý dữ liệu (tách thành các tệp data nhỏ hơn, chọn ra các cột cần sử dụng)
- `data-analyst.ipynb`: tệp notebook dùng cho việc phân tích dữ liệu(đưa ra những câu hỏi từ dữ liệu, trực quan hóa dữ liệu)
- `data-build-model.ipynb`: Xây dựng mô hình, đánh giá mô hình
### Hướng dẫn sử dụng
```
git clone https://github.com/manh0387/BTL_LapTrinhAI.git
```
hoặc tải về trực tiếp repository
```
virtualenv -p python3 my_env //tạo môi trường ảo
```
Cài đặt các thư viện cần dùng
```
pip install -r requirements. txt
```
## Giới thiệu về nhóm và lời cảm ơn
**Nhóm 10** bao gồm 03 thành viên:
- Nguyễn Đông Mạnh
- Lê Hải Yến
- Đào Minh Quân

Thay mặt nhóm xin chân thành cảm ơn thầy Nguyễn Văn Thiệu đã giảng dạy và hướng dẫn trong quá trình hoàn thành bài tập lớn.
