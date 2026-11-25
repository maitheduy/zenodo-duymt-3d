# Bản đồ 3D công trình S.S DUYMT trên Zenodo

Ứng dụng HTML độc lập để khám phá các công trình công khai gắn với [ORCID 0009-0009-8735-6264](https://orcid.org/0009-0009-8735-6264).

## Mở ứng dụng

1. Trên GitHub, chọn **Code → Download ZIP** rồi giải nén.
2. Mở `index.html` bằng Chrome, Cốc Cốc hoặc trình duyệt hiện đại. Ứng dụng không cần cài đặt hay API key.
3. Bản dữ liệu ngày 25/11/2026 có 157 bản ghi, trong đó 62 công trình hiện ở bộ lọc mặc định. Bấm **Cập nhật từ Zenodo** khi có Internet để tải danh mục mới cho phiên đang mở.

## Khám phá bản đồ

- Kéo để xoay, cuộn để phóng to. Bấm nút hoặc chọn nhan đề trong danh sách để xem DOI, tác giả và mở bản ghi Zenodo.
- Tìm bằng nhan đề, từ khóa hoặc DOI. Chọn **Mọi ấn phẩm** hoặc **Mọi bản ghi** để mở rộng phạm vi.
- **Đường liền** biểu thị quan hệ được khai báo trong metadata Zenodo. **Đường đứt** gợi ý gần chủ đề theo độ tương đồng từ vựng của nhan đề, từ khóa và mô tả. Điểm cosine không biểu thị trích dẫn.
- **Xuất CSV** lưu công trình và các liên kết đang hiển thị. Snapshot đi kèm vẫn mở được ngoại tuyến.

Ứng dụng lấy dữ liệu từ [Zenodo Records API](https://developers.zenodo.org/#records), xác nhận ORCID trong danh sách tác giả và gộp phiên bản theo mã công trình. Các loại tài liệu dựa trên nhãn Zenodo, vì vậy preprint có thể là bản thảo chưa qua phản biện.
