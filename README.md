#### Ghi chú:
+ Thư mục raw_data: chứa dữ liệu đã crawl cho tập train và test, đồng thời cũng chứa các file clean đặt tên bằng
tiền tố clean_.
+ Thư mục feature_engineering_data: chứa dữ liệu đã qua các bước feature engineering cho cả 2 tập train và test.
+ Thư mục data_for_training: là hậu xử lý của file feature_engineering_data sau khi đi qua bước trích chọn đặc trưng.

- Cách chạy chương trình:
+ Crawl data: chạy file crawl_all_clubs.ipynb và crawl_for_test.ipynb để crawl data cho tập train, tập test
+ Sau đó chạy cac file clean_data_train.ipynb và clean_data_test.ipynb để clean data cho tập train và tập test
+ Thư mục data_analysis: chứa các file để phân tích dữ liệu
+ Thư mục feature_engineering: chứa các file để thực hiện feature engineering
+ Thư mục clustering: chứa các file để thực hiện phân cụm dữ liệu
+ Thư mục train_model: sẽ chứa xây dựng model cho 2 đội là Arsenal và MU.
#### Note: 
+ File train_model_clustered.ipynb sẽ training model mà có sử dụng các đặc trưng có được từ phân cụm dữ liệu.
còn file train_model_no_clustered.ipynb sẽ training model mà không sử dụng các đặc trưng có được từ phân cụm dữ liệu.
+ File testing.ipynb sẽ testing model sử dụng model từ file train_model_no_clustered.ipynb
+ File testing_clustered.ipynb sẽ testing model sử dụng model từ file train_model_clustered.ipynb
