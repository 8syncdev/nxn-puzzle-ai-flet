# Game Puzzle với Thuật toán A* và Flet UI

![](./docs/demo.png)

[Xem demo tại đây](./docs/short-n-puzzle.mp4)

<video style="width: 100%;" height="240" controls>
  <source src="./docs/short-n-puzzle.mp4" type="video/mp4">
</video>

## Giới thiệu
Dự án này là một trò chơi puzzle được phát triển bằng Python, tích hợp thuật toán tìm đường A* (A Star) và giao diện người dùng được xây dựng bằng công nghệ Flet UI. Trò chơi này không chỉ mang tính giải trí mà còn minh họa cách áp dụng thuật toán AI vào một ứng dụng thực tế.

## Tính năng chính
- Giao diện người dùng thân thiện được xây dựng bằng Flet UI
- Tích hợp thuật toán A* để giải quyết puzzle tự động
- Có thể tùy chỉnh kích thước bảng và độ khó của puzzle
- Hiển thị số bước di chuyển và thời gian giải
- Chế độ chơi thủ công và tự động giải

## Cài đặt
1. Clone repository này về máy local:
   ```
   git clone https://github.com/8syncdev/nxn-puzzle-ai-flet.git
   ```
2. Di chuyển vào thư mục dự án:
   ```
   cd puzzle-game-astar
   ```
3. Cài đặt các thư viện cần thiết:
   ```
   pip install -r requirements.txt
   ```

## Cách sử dụng
1. Chạy file `app.py` để khởi động trò chơi:
   ```
   python app.py
   ```
2. Sử dụng giao diện để tạo puzzle mới hoặc chọn một puzzle có sẵn
3. Chơi thủ công bằng cách click vào các ô để di chuyển
4. Sử dụng nút "Giải tự động" để xem thuật toán A* giải quyết puzzle

## Cấu trúc dự án
- `app.py`: File chính để chạy ứng dụng
- `src/`: Thư mục chứa mã nguồn chính
  - `components/`: Các thành phần UI
  - `utils/`: Các hàm tiện ích
    - `solver.py`: Cài đặt thuật toán A*
    - `board.py`: Xử lý logic bảng puzzle
- `requirements.txt`: Danh sách các thư viện cần thiết

## Đóng góp
Mọi đóng góp đều được hoan nghênh. Vui lòng mở issue hoặc gửi pull request nếu bạn muốn cải thiện dự án.

## Giấy phép
Dự án này được phân phối dưới giấy phép MIT. Xem file `LICENSE` để biết thêm chi tiết.