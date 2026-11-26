# Spec bộ ảnh ô cho chế độ TRẺ EM (thay emoji "giả")

Hiện tại dùng emoji = tạm, nhìn rẻ tiền. Thay bằng **1 bộ tranh cartoon dễ thương, đồng bộ**.

## Cách làm (đưa ChatGPT)

> "Vẽ 1 BỘ icon cartoon dễ thương cho trẻ em, **CÙNG phong cách** (cùng nét, cùng độ bo tròn, cùng ánh sáng).
> Mỗi vật = **1 file PNG riêng, nền TRONG SUỐT**, vuông ~512×512, vật nằm giữa.
> **KHÔNG khung, KHÔNG viền, KHÔNG chữ, KHÔNG huy hiệu** (lỗi bộ Đại Dương trước là bị dính khung + badge)."

## "Lưu database/API" — giải thích [suy luận]

- Bản demo giờ: **không cần server**. Bỏ ảnh vào thư mục `assets/tiles_kids/` + 1 file `tiles.json` (CC tự tạo) ghi file→nhãn. Đó CHÍNH là "database" bản nhẹ.
- Lên thật sau (nhiều người chơi): mới cần **server/API + CDN** host ảnh (phase 2). Giờ làm server là thừa.

## Danh sách cần vẽ (CC đã chọn để game chạy đúng luật)

Tên file đặt y hệt (bỏ vào `assets/tiles_kids/`). Nhãn để CC gán — ChatGPT **không cần lo nhãn**, chỉ cần vẽ đúng con vật.

| File | Vẽ gì | (nhãn CC dùng) |
|------|-------|----------------|
| kids_lion | Sư tử | con vật |
| kids_elephant | Voi | con vật |
| kids_rabbit | Thỏ | con vật |
| kids_bear | Gấu | con vật |
| kids_cat | Mèo | con vật |
| kids_dog | Chó | con vật |
| kids_pig | Heo | con vật |
| kids_horse | Ngựa | con vật |
| kids_fish | Cá | con vật · dưới nước |
| kids_crab | Cua | con vật · dưới nước · ĐỎ |
| kids_turtle | Rùa | con vật · dưới nước · XANH LÁ |
| kids_octopus | Bạch tuộc | con vật · dưới nước |
| kids_dolphin | Cá heo | con vật · dưới nước |
| kids_bird | Chim | con vật · chim · BAY |
| kids_duck | Vịt | con vật · chim |
| kids_owl | Cú | con vật · chim · BAY |
| kids_chicken | Gà | con vật · chim (KHÔNG bay — bẫy) |
| kids_bee | Ong | con vật · BAY · VÀNG |
| kids_butterfly | Bướm | con vật · BAY |
| kids_apple | Táo | trái cây · ăn được · ĐỎ · TRÒN |
| kids_banana | Chuối | trái cây · ăn được · VÀNG |
| kids_orange | Cam | trái cây · ăn được · TRÒN |
| kids_strawberry | Dâu | trái cây · ăn được · ĐỎ |
| kids_watermelon | Dưa hấu | trái cây · ăn được |
| kids_carrot | Cà rốt | rau · ăn được |
| kids_corn | Bắp | rau · ăn được · VÀNG |
| kids_pizza | Pizza | ăn được |
| kids_cake | Bánh kem | ăn được |
| kids_icecream | Kem | ăn được |
| kids_sun | Mặt trời | TỰ PHÁT SÁNG · VÀNG · TRÒN |
| kids_moon | Mặt trăng | TRÒN (KHÔNG tự sáng — bẫy) |
| kids_star | Ngôi sao | TỰ PHÁT SÁNG · VÀNG |
| kids_fire | Lửa | TỰ PHÁT SÁNG · ĐỎ |
| kids_rainbow | Cầu vồng | (bẫy nhiều màu) |
| kids_car | Xe hơi | người làm · ĐỎ |
| kids_plane | Máy bay | người làm · BAY |
| kids_house | Nhà | người làm |
| kids_ball | Quả bóng | người làm · TRÒN |
| kids_lamp | Bóng đèn | người làm · TỰ PHÁT SÁNG |
| kids_boat | Thuyền | người làm |

Có bộ này (tối thiểu ~30 cái) → CC viết `tiles.json` + đổi engine Trẻ em dùng ảnh thay emoji → nhìn xịn như game thật.
