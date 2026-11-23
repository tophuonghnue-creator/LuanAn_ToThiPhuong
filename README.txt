GEOPORTAL VÙNG VEN BIỂN TỈNH THANH HÓA
Tác giả: Tô Thị Phượng

1. Cấu trúc
   index.html   – trang geoportal (mở bằng Chrome, Edge hoặc Firefox)
   data/        – dữ liệu lõi và các lớp vector hóa (tải khi cần)
   img/         – ảnh các lớp bản đồ, ảnh vệ tinh đối chiếu (img/anh) và bản đồ gốc của bài báo nước biển dâng (img/gal)
   Phải giữ nguyên ba thành phần trên trong cùng một thư mục.

2. Mở trên máy: bấm đúp index.html. Khi có mạng sẽ có thêm nền OpenStreetMap và ảnh vệ tinh Esri.

3. Đưa lên web: tải cả thư mục (index.html, data, img) lên một dịch vụ trang tĩnh (GitHub Pages, Netlify, máy chủ của trường).

4. Nội dung
   - 5 lớp chuyên đề: biến động sử dụng đất, biến động đường bờ, nước biển dâng, quy hoạch sử dụng đất, đô thị hóa – công nghiệp hóa.
     Mỗi lớp hiển thị sẵn bản đồ kết quả; các bản đồ khác trong bài nằm ở mục «Các bản đồ trong bài».
   - Nước biển dâng: khu vực ngập 4 kịch bản, lớp phủ và mô hình số độ cao được số hóa từ bản đồ gốc của bài báo, nắn chỉnh
     theo lưới kinh vĩ độ trên khung bản đồ (sai số trung phương 0,33 pixel ≈ 11 m); xem bản đồ gốc ở mục «Bản đồ gốc trong bài báo».
   - Ảnh vệ tinh đối chiếu phủ toàn vùng nghiên cứu: Landsat 2015, 2025 (30 m); Sentinel-2 2015, 2020, 2025 (khoảng 15 m).
     Ảnh Sentinel-2 năm 2015 còn vệt mây mỏng ở một số nơi do khi đó mới có vệ tinh Sentinel-2A; có thể đối chiếu thêm bằng Landsat 2015.
