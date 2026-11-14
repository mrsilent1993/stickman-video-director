# Kiểm tra bản quyền: toàn bộ nội dung (14/11/2026)

Kiểm tra theo quy tắc trong `CLAUDE.md`, bằng script tự động kết hợp đọc lại thủ công. Kết quả chỉ để tham khảo khi làm nội dung, **không phải tư vấn pháp lý**.

## Tổng quan

| File | Prompt ảnh | Lời đọc (tên nhại) | Trích dẫn | Mục bắt buộc | Kết luận |
|---|---|---|---|---|---|
| `what-if-loki-won-proposal.md` | — | ✅ Đã dùng tên nhại | ✅ | ✅ Đủ | **✅ Đạt** |
| `what-if-loki-won-givemotion.md` | ✅ 84 prompt sạch | ✅ | ✅ | ⚠️ Thiếu bảng "Nhân vật thiết kế gốc" và mục "Kiểm tra bản quyền" (nội dung có ở file đề xuất) | **✅ Đạt** (chỉ thiếu giấy tờ) |
| `what-if-joker-won-givemotion.md` | ✅ 106 prompt sạch | ❌ Còn tên gốc: Joker ×32, Gotham ×26, Batman ×6, Gordon ×4, Harvey Dent ×2, *The Dark Knight* ×2 | ✅ | ❌ Thiếu bảng tên nhại, mục kiểm tra | **⚠️ Cần sửa lời đọc** |
| `what-if-joker-won-3parts.md` | — | ❌ Như trên | ✅ | ❌ | **⚠️ Cần sửa** |
| `what-if-joker-won-proposal.md` | — | ❌ Tên gốc; bảng nhân vật cũ (áo tím, tóc xanh, tai nhọn) | ✅ | ❌ | **⚠️ Cần sửa** (đã có bản 3 phần thay thế) |
| `what-if-thanos-won-proposal.md` | — (chưa có) | ❌ Thanos ×19, Avengers, Infinity War/Stones, Endgame, Captain America | ✅ | ⚠️ Thiếu bảng tên nhại | **⚠️ Cần sửa lời đọc** |
| `what-if-scar-won-10min-proposal.md` | — (chưa có) | ❌ Scar ×25, Simba ×12, Nala ×8, Pride Rock ×6, Mufasa ×3 | ❌ *"circle of life"* (tên bài hát của phim), *"no worries"* (dịch câu khẩu hiệu nổi tiếng của phim) | ⚠️ Thiếu bảng tên nhại | **⚠️ Cần sửa** |
| `what-if-scar-won-givemotion.md` (3 phút) | ❌ **Rủi ro cao:** tên Scar, Simba, Nala nằm trong prompt; thiết kế gần bản gốc (lông nâu sẫm, bờm đen, sẹo ở mắt trái) | ❌ Tên gốc | ❌ *"circle of life"* | ❌ | **❌ Không nên dùng** |
| `what-if-scar-won-prompts.md` (Flow 3 phút) | ❌ **Rủi ro cao:** như trên, tên nằm ngay trong prompt video | ❌ | ❌ | ❌ | **❌ Không nên dùng** |
| `hooks-3s.md` | — | ⚠️ Hook Thanos, Joker, Scar còn tên gốc | ✅ | — | **⚠️ Cập nhật theo tên nhại** |
| `bach-dang-938-prompts.md` | ✅ | ✅ Sự kiện lịch sử, không có bản quyền | ✅ | — | **✅ Đạt** |

**Âm thanh:** tất cả các file đều ghi rõ *không dùng nhạc phim gốc*, chỉ dùng nhạc có giấy phép, và không nhái giọng diễn viên. ✅

## Vấn đề chi tiết

1. **Tên gốc trong lời đọc** (Joker, Thanos, Scar 10 phút). Quy tắc mới yêu cầu dùng tên nhại. Tên đề xuất:
   - Joker → **Jokker**, Batman → **the Night Guardian**, Gotham → **Gothmore**, Gordon → **Chief Gordan**, Harvey Dent → **Harlan Dane**, *The Dark Knight* → *"one famous movie"*.
   - Thanos → **Thanex**, Avengers → **the Vanguards**, Infinity Stones → **the Six Runes**, Captain America → *"one of the heroes"*, *Infinity War*/*Endgame* → *"the movies"*.
   - Scar → **Skar**, Simba → **Simbo**, Nala → **Nalia**, Mufasa → **Mufaro**, Pride Rock → **King's Rock**.
2. **Trích dẫn hoặc cụm từ đặc trưng của phim (Scar):**
   - *"a king is part of the circle of life"* → đổi thành *"a king is part of the great cycle, not above it"*.
   - *"a simple motto: no worries"* → đổi thành *"a simple motto: forget the past"*.
3. **Hai file Scar 3 phút** (`what-if-scar-won-prompts.md`, `what-if-scar-won-givemotion.md`) viết trước khi có quy tắc. Tên nhân vật nằm ngay trong prompt, thiết kế lại sát bản gốc, nên **ChatGPT và Flow rất dễ từ chối**. Bản Scar 10 phút đã thay thế hai file này. Đề xuất: **xóa** hoặc **đánh dấu "không dùng"**.
4. **Joker, tỷ lệ tóm tắt phim:** phần 1 kể lại cảnh hai chiếc phà khá kỹ (khoảng 17% tổng thời lượng, hơi vượt mức 15%). Đề xuất rút gọn 3–4 cảnh tóm tắt (cảnh người mặc vest và cảnh tù nhân ném kíp nổ gộp lại).
5. **Giấy tờ thiếu:** thêm bảng "Nhân vật thiết kế gốc", bảng tên nhại và mục "Kiểm tra bản quyền" vào các file Joker và Thanos.

## Việc cần làm (theo thứ tự ưu tiên)
1. Xóa hoặc đánh dấu "không dùng" 2 file Scar 3 phút.
2. Đổi tên nhại trong Joker (cả 3 file), Thanos, Scar 10 phút và `hooks-3s.md`.
3. Diễn đạt lại 2 cụm từ trong Scar.
4. Rút gọn phần tóm tắt Joker phần 1.
5. Bổ sung các mục bắt buộc còn thiếu.
