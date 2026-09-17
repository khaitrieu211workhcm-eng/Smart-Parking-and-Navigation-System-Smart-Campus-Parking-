**Smart-Parking-and-Navigation-System-Smart-Campus-Parking-**

**Bài toán & Mục tiêu:** 
Khắc phục tình trạng ùn tắc giờ cao điểm, sai sót dữ liệu và hạn chế của quản lý thủ công; xây dựng kiến trúc phần mềm bằng ngôn ngữ C với nguyên lý phân tách tầng giao diện và tầng logic.

**Mô hình hóa không gian:** 
- Bãi xe được mô hình hóa dưới dạng đồ thị trọng số (tối đa 305 đỉnh gồm các cổng và 300 vị trí đỗ phân khu Giảng viên/Sinh viên).
- Thuật toán Dijkstra được dùng để tính toán lộ trình tối ưu từ cổng đến vị trí trống.
  
**Cơ chế kiểm soát & Điều tiết:**
- Bảng băm (Hash Table) kết hợp Separate Chaining giúp kiểm soát xe ra/vào với thời gian truy xuất đạt O(1).
- Hàng đợi (Queue - FIFO) tự động điều tiết luồng phương tiện tại cổng khi bãi đạt sức chứa tối đa.
  
**Xử lý đặc thù & Tối ưu:**
Hàng đợi ưu tiên (Min-Heap) và Ngăn xếp (Stack): Giải quyết bài toán chia sẻ không gian (sinh viên đỗ tạm khu giảng viên), mô phỏng dời xe cản đường và ưu tiên giải phóng xe đỗ tạm lâu nhất.
- Tìm kiếm mờ (Fuzzy Search): Ứng dụng khoảng cách Levenshtein để đề xuất 3 biển số tương đồng nhất, khắc phục lỗi nhiễu camera hoặc mất thẻ.
  
**Kết quả:**

Xây dựng ứng dụng cốt lõi ổn định, quản lý bộ nhớ động chặt chẽ, đảm bảo toàn vẹn dữ liệu làm tiền đề tích hợp giao diện đồ họa.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/53dbe8fa-272f-484a-be3a-89112ba14d12" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d6168512-9aee-4953-8831-a80880f87f7b" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7db27807-2f04-4083-a34c-b82918396e16" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7881d456-2bad-41ca-a4f8-90b5d8e73b73" />



