# Sự kiện lịch sử nào được nhiều người quan tâm? (phân tích lượt xem Wikipedia)

**Dữ liệu:** lượt xem hằng tháng của 27 bài Wikipedia tiếng Anh về các sự kiện ứng viên, chỉ tính người dùng thật (đã loại bot), từ 11/2024 đến 10/2026 (24 tháng). Nguồn: Wikimedia Pageviews API.

**Chỉ số:**
- **Trung vị/tháng:** mức quan tâm điển hình. Dùng trung vị vì ít bị lệch bởi các tháng tăng đột biến.
- **Thay đổi:** so 12 tháng gần nhất với 12 tháng trước. Mỗi tháng được ghép cặp với cùng tháng năm trước, kiểm định Wilcoxon trên log lượt xem, giá trị p hiệu chỉnh theo Holm cho 27 phép so sánh.
- **Đỉnh/trung vị:** tháng cao nhất cao gấp mấy lần trung vị. Chỉ số này lớn nghĩa là quan tâm theo sự kiện (ngày kỷ niệm, phim, game).

**Giới hạn:** lượt xem Wikipedia tiếng Anh là **chỉ báo gần đúng** cho mức quan tâm của người nói tiếng Anh, **không phải** nhu cầu tìm kiếm trên YouTube. Lượt xem Wikipedia nói chung đang giảm, có thể do tìm kiếm bằng AI, nên con số tuyệt đối thấp dần. Hãy so sánh **tương đối** giữa các sự kiện.

| # | Sự kiện | Trung vị/tháng | Thay đổi 12 tháng | p (Holm) | Đỉnh (tháng) | Đỉnh/trung vị | Hợp với kênh? |
|---|---|---|---|---|---|---|---|
| 1 | Waterloo 1815 | 127,030 | -9.5% | 0.195 | 03/2025 | 1.3× | ⚠️ Dễ xoáy vào cá nhân (Napoleon), kể theo hai đạo quân |
| 2 | Midway 1942 | 88,636 | -13.4% | 1.000 | 12/2024 | 1.9× | ❌ Thế chiến II, dễ quy phe ác cho quốc gia ngày nay |
| 3 | Gettysburg 1863 | 79,406 | -0.1% | 1.000 | 07/2026 | 1.6× | ❌ Nội chiến Mỹ, nhạy cảm chính trị |
| 4 | Fall of Constantinople 1453 | 78,863 | -21.1% | 0.013 | 01/2025 | 1.4× | ❌ Nhạy cảm tôn giáo và dân tộc ngày nay |
| 5 | Thermopylae 480 BC | 73,400 | -9.7% | 1.000 | 07/2026 | 1.5× | ✅ Rất hợp (Ba Tư xâm lược, huyền thoại '300') |
| 6 | Hastings 1066 | 71,500 | +2.5% | 1.000 | 09/2025 | 2.3× | ✅ Rất hợp (móc: tiếng Anh sẽ khác hẳn) |
| 7 | Agincourt 1415 | 70,920 | -10.5% | 0.150 | 01/2025 | 1.3× | ✅ Hợp |
| 8 | Gallipoli 1915 | 63,734 | +0.7% | 1.000 | 04/2026 | 1.8× | ❌ Thế chiến I, nhạy cảm với ANZAC và Thổ Nhĩ Kỳ |
| 9 | Trafalgar 1805 | 59,294 | +0.4% | 1.000 | 10/2025 | 2.0× | ✅ Hợp |
| 10 | Siege of Vienna 1683 | 57,338 | -0.3% | 1.000 | 02/2025 | 1.8× | ❌ Bị lạm dụng làm biểu tượng chính trị ngày nay |
| 11 | Cannae 216 BC | 43,485 | -14.6% | 1.000 | 06/2025 | 2.2× | ✅ Rất hợp |
| 12 | Yorktown 1781 | 42,714 | +2.9% | 1.000 | 07/2026 | 1.8× | ⚠️ Được, nhưng gắn chính trị Mỹ |
| 13 | Teutoburg Forest 9 AD | 40,540 | -18.5% | 0.038 | 01/2025 | 1.3× | ✅ Rất hợp (Rome chinh phục Germania) |
| 14 | Spanish Armada 1588 | 33,690 | -8.3% | 0.959 | 07/2026 | 1.2× | ✅ Rất hợp |
| 15 | Lepanto 1571 | 27,708 | -1.0% | 1.000 | 10/2025 | 2.5× | ⚠️ Có yếu tố tôn giáo |
| 16 | Saratoga 1777 | 26,227 | +9.8% | 1.000 | 11/2025 | 1.8× | ⚠️ Được (kỷ niệm 250 năm, 10/2027) |
| 17 | Marathon 490 BC | 26,098 | -7.9% | 1.000 | 05/2026 | 1.6× | ✅ Hợp (gộp với Ba Tư) |
| 18 | Mongol invasions of Japan 1274/1281 | 26,043 | -29.2% | 0.059 | 10/2025 | 1.7× | ✅ Rất hợp |
| 19 | Tours 732 | 23,346 | -12.4% | 0.290 | 10/2025 | 1.5× | ❌ Bị lạm dụng làm biểu tượng chính trị |
| 20 | Salamis 480 BC | 20,938 | -12.8% | 1.000 | 12/2024 | 1.3× | ✅ Gộp với Thermopylae |
| 21 | Sack of Rome 410 | 20,660 | -10.4% | 0.244 | 08/2025 | 1.3× | ✅ Hợp |
| 22 | Gaugamela 331 BC | 20,164 | -8.5% | 0.112 | 01/2025 | 1.5× | ⚠️ Xoáy vào Alexander |
| 23 | Actium 31 BC | 19,594 | -11.6% | 0.038 | 12/2024 | 1.2× | ⚠️ Xoáy vào Cleopatra, Antony |
| 24 | Zama 202 BC | 18,862 | -9.6% | 0.244 | 01/2025 | 3.5× | ✅ Gộp với Cannae |
| 25 | Ain Jalut 1260 | 15,638 | -3.8% | 1.000 | 10/2025 | 1.5× | ✅ Hợp (Mông Cổ thắng ở Trung Đông) |
| 26 | Mongol invasion of Europe 1241 | 15,003 | -16.1% | 0.357 | 11/2025 | 1.2× | ✅ Hợp |
| 27 | Bach Dang 1288 | 1,614 | +10.5% | 0.430 | 04/2025 | 1.4× | ✅ Hợp, nhưng ít người nói tiếng Anh tìm |

## Kết quả chính
1. **Waterloo** được quan tâm nhiều nhất (khoảng 127 nghìn lượt/tháng), gấp khoảng 3,8 lần trung vị của nhóm (khoảng 34 nghìn).
2. **Các sự kiện hợp với kênh và có mức quan tâm cao nhất:** Thermopylae (khoảng 73 nghìn), Hastings (khoảng 72 nghìn), Agincourt (khoảng 71 nghìn), Trafalgar (khoảng 59 nghìn), Cannae (khoảng 43 nghìn), Teutoburg (khoảng 41 nghìn), Armada (khoảng 34 nghìn).
3. **Xu hướng:** sau hiệu chỉnh nhiều phép so sánh, chỉ có 3 sự kiện **giảm có ý nghĩa thống kê**: Constantinople (−21%), Teutoburg (−18%), Actium (−12%). Phần lớn sự kiện còn lại **không đổi có ý nghĩa**. Mức giảm chung khoảng 10% nhiều khả năng do lượt xem Wikipedia nói chung đang giảm, không riêng chủ đề nào. Mông Cổ xâm lược Nhật giảm khoảng 29% nhưng chưa đủ ý nghĩa thống kê (p khoảng 0,06).
4. **Quan tâm theo sự kiện:** Zama (3,5×), Lepanto (2,5×), Hastings (2,3×), Cannae (2,2×) và Trafalgar (2,0×) có đỉnh rõ. Lepanto và Trafalgar đạt đỉnh vào **tháng 10**, đúng tháng kỷ niệm (7/10 và 21/10). Gettysburg, Thermopylae, Yorktown và Armada cùng đạt đỉnh **tháng 7/2026**. Đây chỉ là giả thuyết: có thể do kỷ niệm 250 năm nước Mỹ và phim *The Odyssey* (7/2026) làm tăng quan tâm đến lịch sử nói chung. Cần dữ liệu khác để kiểm chứng.
5. **Bạch Đằng 1288** chỉ khoảng 1,6 nghìn lượt/tháng trên Wikipedia tiếng Anh. Chủ đề này hợp với khán giả Việt hơn là khán giả nói tiếng Anh.

## Đề xuất thứ tự làm (kết hợp mức quan tâm và độ phù hợp)
1. **Thermopylae / Ba Tư xâm lược Hy Lạp, 480 TCN** (gộp Salamis): quan tâm cao, có huyền thoại "300", phe "xâm lược" rõ ràng, không nhạy cảm ngày nay.
2. **Hastings 1066:** quan tâm cao, xu hướng ổn định. Móc mạnh: *"What if the Saxons won? English would sound completely different."* Nên đăng trước ngày 14/10.
3. **Agincourt 1415:** quan tâm cao. Đăng trước ngày 25/10.
4. **Cannae / Hannibal, 216 TCN** (gộp Zama): quan tâm khá, có đỉnh theo sự kiện. Kể theo hai đạo quân, không xoáy vào Hannibal.
5. **Teutoburg 9 SCN / Armada 1588 / Mông Cổ 1281:** quan tâm trung bình, câu chuyện mạnh.

**Tránh:** Midway, Gettysburg, Gallipoli, Constantinople, Vienna 1683, Tours. Các sự kiện này được quan tâm cao, nhưng **nhạy cảm chính trị, tôn giáo hoặc dân tộc ngày nay**, trái với quy tắc của kênh.
