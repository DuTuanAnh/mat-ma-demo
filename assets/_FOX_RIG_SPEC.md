# Spec con cáo mới (thiết kế + tách lớp để rig cử động như Dragon City)

## BƯỚC 1 — Thiết kế con cáo MỚI (quan trọng, đừng dùng con cũ)

Con cáo cũ bị chê "bê đê" (quá điệu/thanh mảnh/đuôi 9 cái lượt thượt). Cáo mới cần:

> "Vẽ 1 chú cáo **mascot cartoon chibi dễ thương + TINH NGHỊCH** (kiểu nhân vật Dragon City /
> Duolingo): thân **mập tròn đáng yêu**, **mắt to lanh lợi**, nụ cười **láu cá/nhếch mép**, dáng
> nghịch ngợm (1 tai cụp, đầu nghiêng). Màu cam-kem ấm. **KHÔNG điệu đà, KHÔNG thanh mảnh, KHÔNG
> đuôi 9 cái lượt thượt.** Nhìn vào thấy vui nhộn, tinh nghịch, con nít mê."

Vẽ **nhìn NGANG (side/3-4 view)**, nền trong suốt, để sau rig đi/vẫy dễ.

## BƯỚC 2 — Tách con cáo mới đó thành các LỚP rời

> "Từ con cáo vừa vẽ, tách thành các LỚP rời, mỗi lớp 1 file PNG **nền trong suốt**,
> **CÙNG kích thước** và **CÙNG vị trí** (chỉ xóa phần không thuộc lớp, giữ nguyên phần của lớp
> tại đúng chỗ). Xếp chồng tất cả lớp lên nhau phải ra lại con cáo y hệt."

## Các file cần (tên ĐÚNG y, bỏ vào thư mục `assets/`)

| File | Gồm gì | Bắt buộc? |
|------|--------|-----------|
| `fox_tail.png` | CHỈ cái đuôi (9 đuôi vàng) | ✅ bắt buộc |
| `fox_body.png` | Thân + 4 chân + cổ + vòng cổ (KHÔNG đuôi, KHÔNG đầu) | ✅ bắt buộc |
| `fox_head.png` | Đầu + mặt (gồm cả tai cũng được) | ✅ bắt buộc |
| `fox_ear.png` | 2 tai (nếu muốn tai giật riêng) | ⬜ tuỳ chọn |

## Lưu ý quan trọng

- **Cùng 1 khung** cho mọi file (vd 600×680), mỗi mảnh nằm ĐÚNG chỗ như ảnh gốc → xếp đè = ra con cáo nguyên.
- Nền **trong suốt** (PNG có alpha).
- Chỗ **gắn khớp** (gốc đuôi, gốc cổ) nên **dư ra một chút** để lúc cử động không bị hở.
- Tối thiểu cần **3 file**: tail + body + head. Có thêm ear thì tai giật sinh động hơn.

## Khi có file

Bỏ vào `E:\matma-game\assets\` → báo CC → CC push. Vào màn **Thú cưng** cáo sẽ:
đuôi vẫy · đầu gật nhẹ · thân thở phồng-xẹp · tai giật (nếu có ear).
Thiếu file thì app tự dùng cáo cũ (idle thở), KHÔNG vỡ.
