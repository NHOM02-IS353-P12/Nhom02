﻿# Đánh giá Chất lượng Khóa học trên Nền tảng MOOCs

## Mô tả Dự án
Dự án này tập trung vào việc xây dựng một hệ thống tự động gán nhãn và đánh giá chất lượng khóa học trực tuyến dựa trên dữ liệu được thu thập từ nền tảng MOOCs, cụ thể là **MOOC CubeX**. Hệ thống sử dụng các phương pháp học máy và phân tích dữ liệu để đánh giá khóa học dựa trên nhiều tiêu chí khác nhau, giúp các nhà quản lý giáo dục cải thiện chất lượng giảng dạy và tối ưu hóa trải nghiệm học tập của học viên.

---

## Input và Output
- **Input**:  
  - **Dữ liệu khóa học**: Thông tin khóa học, bình luận, video, bài tập.  
  - **Dữ liệu tương tác học viên**: Xem video, làm bài tập, tỷ lệ hoàn thành khóa học.  
  - **Dữ liệu từ nhiều bảng**: `course`, `user`, `user-problem`, `problem`, `video`, `user-video`, `comment`, `course-comment`.
- **Output**: Chất lượng của khóa học (thang điểm từ 0 đến 2).
  
---

## Data
 - **Link data drive**: https://drive.google.com/drive/u/0/folders/1Kjz6PpsuQ1fk-cLWc5uLfEc4g3E7ao2d

---

## Thách thức
- **Xử lý dữ liệu lớn**: Đa dạng dữ liệu từ nhiều nguồn, yêu cầu xử lý và đồng nhất hóa.
- **Thiếu nhãn dữ liệu**: Việc gán nhãn cần thực hiện thủ công, bán tự động, hoặc thông qua các thuật toán.
- **Tính phức tạp của hệ thống đánh giá**: Yêu cầu tích hợp nhiều tiêu chí như mức độ tương tác, tỷ lệ hoàn thành khóa học, và phản hồi từ học viên.
- **Hiệu suất và khả năng mở rộng**: Hệ thống cần xử lý dữ liệu nhanh và mở rộng linh hoạt.
- **Giải thích và ứng dụng kết quả**: Đảm bảo kết quả rõ ràng, dễ hiểu và cung cấp giá trị thực tiễn.

---

## Mục tiêu Dự án
- Xây dựng mô hình gán nhãn và đánh giá chất lượng khóa học trên thang điểm từ 1 đến 5.
- Cung cấp báo cáo chi tiết dựa trên 5 tiêu chí:
  1. Điểm trung bình khóa học.
  2. Thói quen học qua video.
  3. Nỗ lực làm bài tập.
  4. Mức độ hài lòng của học viên.
  5. Tỷ lệ hoàn thành khóa học.

---

## Dataset
- **Nguồn**: MOOC CubeX (2019-2020).
- **Quy mô**: 986 khóa học được sử dụng trong dự án.
- **Cấu trúc dữ liệu**: Dữ liệu từ nhiều bảng bao gồm `course`, `user`, `video`, `comment`, `user-video`, `user-problem`.

---

## Công nghệ Sử dụng
- **Ngôn ngữ lập trình**: Python
- **Thư viện và Công cụ**:
  - Pandas, NumPy: Xử lý và phân tích dữ liệu.
  - Scikit-learn: Xây dựng các mô hình học máy.
  - Matplotlib, Seaborn: Trực quan hóa dữ liệu.
  - Jupyter Notebook: Tổ chức và thực thi các phân tích.

---

## Hướng dẫn Cài đặt
 Clone repository:
   ```bash
   git clone https://github.com/NHOM02-IS353-P12/Nhom02.git
   ```

---

---

## Kết quả Dự kiến
- Điểm đánh giá chất lượng khóa học theo các tiêu chí.

---

## Đóng góp
Chúng tôi hoan nghênh mọi đóng góp để cải thiện dự án. Hãy gửi pull request hoặc mở issue nếu bạn có đề xuất hoặc gặp vấn đề.


