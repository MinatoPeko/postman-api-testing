# Hướng dẫn chụp và lưu ảnh minh họa (Screenshots Guide)

Để báo cáo `README.md` hiển thị đầy đủ hình ảnh, bạn chỉ cần mở phần mềm Postman trên máy, thực hiện theo các bước sau và lưu ảnh chụp màn hình vào thư mục `images/` này với đúng tên file tương ứng:

| Tên file ảnh | Mô tả màn hình cần chụp | Cách thao tác trên Postman |
| :--- | :--- | :--- |
| `01_import_collection.png` | Giao diện sau khi Import Collection và Environment | Chọn nút **Import** ở góc trên bên trái -> kéo thả 2 file `.json` vào -> Chụp lại thanh sidebar bên trái thấy Collection `DummyJSON Product API Testing` và góc trên bên phải chọn đúng môi trường `DummyJSON Environment`. |
| `02_get_request_test_pass.png` | Request `TC01 - Lấy danh sách sản phẩm` chạy PASS | Mở request `TC01` -> Nhấn nút **Send** -> Ở khung kết quả bên dưới, chọn tab **Test Results** (hiển thị 3/3 PASS màu xanh lá) -> Chụp màn hình. |
| `03_post_request_test_pass.png` | Request `TC04 - Thêm mới sản phẩm` chạy PASS | Mở request `TC04` -> Nhấn nút **Send** -> Chụp màn hình thấy rõ Body JSON gửi đi và tab **Test Results** PASS (Status 200/201). |
| `04_collection_runner.png` | Kết quả chạy tự động toàn bộ Collection (Runner) | Chuột phải vào Collection `DummyJSON Product API Testing` -> Chọn **Run collection** -> Bấm **Run** -> Chụp lại bảng tổng kết kết quả (Run Summary hiển thị danh sách tất cả các test case đều PASS). |

*(Gợi ý: Trên Windows bạn có thể dùng phím tắt `Windows + Shift + S` để chụp vùng màn hình mong muốn, sau đó lưu ảnh dạng PNG vào thư mục `images/`).*
