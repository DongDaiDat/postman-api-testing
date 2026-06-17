# Báo cáo thực hành kiểm thử API bằng Postman

## 1. Giới thiệu

Bài thực hành này nhằm tìm hiểu và sử dụng công cụ Postman để kiểm thử API. Postman hỗ trợ gửi request đến server, kiểm tra response, viết test script và chạy tự động nhiều request thông qua Collection Runner.

## 2. Công cụ sử dụng

- Postman
- GitHub
- API demo: https://reqres.in/

## 3. Nội dung thực hiện

Trong bài thực hành, em đã tạo một collection trên Postman để kiểm thử các API cơ bản, bao gồm:

| STT | Method | API | Mục đích |
|---|---|---|---|
| 1 | GET | /api/users?page=2 | Lấy danh sách người dùng |
| 2 | GET | /api/users/2 | Lấy thông tin một người dùng |
| 3 | POST | /api/users | Tạo người dùng mới |
| 4 | PUT | /api/users/2 | Cập nhật người dùng |
| 5 | DELETE | /api/users/2 | Xóa người dùng |

## 4. Kết quả thực hiện

### 4.1. Tạo Collection trong Postman

![Collection](images/01_collection.png)

### 4.2. Kiểm thử request GET

![GET Request](images/02_get_request.png)

### 4.3. Kiểm thử request POST

![POST Request](images/03_post_request.png)

### 4.4. Viết test script và kiểm tra kết quả

![Tests Passed](images/04_tests_passed.png)

### 4.5. Chạy Collection Runner

![Runner Result](images/05_runner_result.png)

## 5. Nhận xét

Thông qua bài thực hành, em đã hiểu cách sử dụng Postman để gửi các request HTTP như GET, POST, PUT và DELETE. Ngoài ra, em cũng biết cách viết test script để kiểm tra status code, dữ liệu trả về và chạy tự động nhiều request bằng Collection Runner.

## 6. Kết luận

Postman là công cụ hữu ích trong kiểm thử API, giúp kiểm tra nhanh chức năng của backend, xác minh dữ liệu phản hồi và hỗ trợ tự động hóa kiểm thử ở mức cơ bản.
