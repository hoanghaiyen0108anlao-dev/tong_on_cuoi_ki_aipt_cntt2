# BÀI LÀM PHA 2 

- **Họ tên:Hoang Hai Yen**
- **Lớp:**
- **Link repository Pha2:**
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):**

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt vé ra JSON

**KET QUA AI**

```text
[
  {
    "ma_goi": "SVT",
    "ngay_su_kien": "2026-12-20",
    "nguoi_lon": 2,
    "tre_em": 1,
    "loai_ve": "thuong",
    "ghi_chu": null
  },
  {
    "ma_goi": "FZ",
    "ngay_su_kien": "2027-01-05",
    "nguoi_lon": 3,
    "tre_em": 0,
    "loai_ve": "thuong",
    "ghi_chu": "hỗ trợ xe lăn"
  },
  {
    "ma_goi": "VIP",
    "ngay_su_kien": null,
    "nguoi_lon": 4,
    "tre_em": 0,
    "loai_ve": "vip",
    "ghi_chu": "hỗ trợ tìm chỗ cho người khiếm thị"
  }
]
```

**Link trò chuyện:**

## 4.3. Báo giá vé bằng Chain-of-Thought

**KET QUA AI**

```text
Đối chiếu 6 bước với bảng giá và quy tắc tính giá:
- Tiền người lớn: 6.000.000 đồng.
- Tiền trẻ em: 1.680.000 đồng (bé 3 tuổi được miễn phí).
- Tổng tiền vé trước giảm giá: 7.680.000 đồng.
- Giảm giá nhóm 5%: 384.000 đồng.
- Phụ thu ghế ưu tiên: 300.000 đồng.
- Tổng tiền phải thanh toán: 7.596.000 đồng.


```

**Link trò chuyện:**

### b) Kiểm tra kết quả AI
Không phát hiện bước tính sai. Kết quả cuối cùng chính xác là 7.596.000 đồng.


## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_su_co": "sai_khu_vuc",
  "so_khach": 2,
  "so_hiep_bi_anh_huong": 2,
  "tom_tat": "Hai khán giả bị xếp khu không mái che trong hai hiệp đầu dù đã cam kết có mái che."
}
```

**Link trò chuyện:**

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
Kết quả chấm bài mẫu
Tiêu chí	Điểm tối đa	Điểm đạt
Đúng thông tin	5	0
Đầy đủ	       3	         1
Giọng điệu	2	1
Tổng điểm	10	2
```

**Link trò chuyện:**
