# ThucHanhJMeter

# Kiểm tra hiệu năng trang web
# Mục tiêu:
Sử dụng jMeter để tạo một kịch bản kiểm tra mô phỏng người dùng truy cập trang web https://phenikaa-uni.edu.vn/vi.
Chạy kịch bản kiểm tra và ghi lại kết quả.
Phân tích kết quả kiểm tra, bao gồm thời gian phản hồi, số lượng yêu cầu thành công, số lượng yêu cầu thất bại, v.v.
Dựa trên kết quả phân tích, đưa ra kết luận về hiệu năng của trang web.

# Kịch bản kiểm tra:
- Thread Group:
    + Số lượng thread: 100
    + Thời gian chạy: 60 giây
    + Ramp-up period: 10 giây
- HTTP Request:
    + URL: https://phenikaa-uni.edu.vn/vi
    + Method: GET
    + Content encoding: UTF-8
- Listeners:
    + View Results Tree
    + Aggregate Report

# Kết quả kiểm tra:
- Phân tích kết quả kiểm tra:
- Số lượng yêu cầu thành công: 998/1000 = 99,8%
- Số lượng yêu cầu thất bại: 2/1000 = 0,2%
- Thời gian phản hồi trung bình: 40 ms
- Thời gian phản hồi trung vị: 38 ms
- Thời gian phản hồi percentil 90: 70 ms
- Chuyển tải: 16 yêu cầu/giây
# Kết luận:

# Hình ảnh tổng quát
