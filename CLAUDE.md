# Hướng dẫn cho Claude: kênh "Villain Wins / What If"

Kênh YouTube người que, lời đọc tiếng Anh, bình luận theo kiểu "What if" về các phim nổi tiếng. Quy trình làm video: ChatGPT tạo ảnh, công cụ chuyển văn bản thành giọng đọc (TTS) tạo lời đọc, Givemotion dựng video. Người dùng trao đổi bằng tiếng Việt.

## QUY TẮC BẮT BUỘC: tránh vi phạm bản quyền
Áp dụng cho **mọi** kịch bản, prompt ảnh, thumbnail và file sản xuất mới. Đây là cách làm an toàn trong thực tế, không phải tư vấn pháp lý.

### 1. Hình ảnh và prompt ảnh
- **Mọi nhân vật đều là thiết kế gốc**, chỉ gợi **kiểu nhân vật** (vai trò và tính cách), ví dụ "hoàng tử lừa lọc dùng ảo ảnh", không phải bản sao nhân vật.
- **Đổi ít nhất 3 dấu hiệu nhận diện** so với bản gốc: bảng màu, kiểu tóc hoặc mũ, trang phục, vũ khí hoặc đạo cụ đặc trưng, hình dáng tổng thể.
- **Không có logo, biểu tượng hay huy hiệu** (dơi, chữ S, khiên…) và không dùng phông chữ đặc trưng của phim.
- **Prompt ảnh không chứa** tên nhân vật, tên phim, tên hãng hay thương hiệu (Marvel, Disney, Pixar, DC, Star Wars, Harry Potter…), không có tên vật phẩm riêng (Tesseract, Infinity Stones…), và không dùng chữ "inspired by", "-inspired", "like [tên]".
- **Không tái tạo cảnh nổi tiếng theo đúng bố cục gốc**, không dùng ảnh chụp từ phim, poster hay khung hình gốc.
- Sinh vật hoặc nhân vật nổi tiếng (Hulk, Thanos…) chỉ thể hiện bằng **bóng mờ, bộ phận chung chung** (nắm đấm xám như đá) hoặc thiết kế khác hẳn.
- **Kiểm tra trước khi giao file:** chạy grep trên các khối prompt ảnh để chắc không còn tên nhân vật, tên phim hay tên hãng.

### 2. Lời đọc và kịch bản
- **Dùng tên nhại gần giống bản gốc** cho nhân vật, địa danh hư cấu, nhóm và vật phẩm trong lời đọc (ví dụ: Loki → Lokin, Thor → Thoren, Asgard → Ashgard, Avengers → the Vanguards, Tesseract → the Tesser Cube). Đọc phải dễ, TTS phát âm được, và **không trùng tên nhân vật nổi tiếng khác**. Nhân vật phụ quá đặc trưng thì không đặt tên ("a titan", "a giant brute").
- Mỗi đề xuất có **bảng tên nhại**: bản gốc, tên trong video, cách đọc.
- Tên phim chỉ nhắc chung ("one famous movie"). Câu thoại nổi tiếng thì diễn đạt lại.
- Video phải mang tính **bình luận và biến đổi**: phần lớn thời lượng là **tưởng tượng gốc, phân tích và bài học**. Phần tóm tắt phim chỉ chiếm **khoảng 15% thời lượng hoặc ít hơn**.
- Tiêu đề và mô tả YouTube: hỏi người dùng muốn dùng tên nhại hay tên gốc. Tên gốc giúp tìm kiếm tốt hơn, tên nhại an toàn hơn.
- **Không trích dài lời thoại phim.** Tối đa một cụm từ rất ngắn, nổi tiếng, có ghi rõ ngữ cảnh. Ưu tiên diễn đạt lại bằng lời của mình. Không dùng lời bài hát của phim.
- Tách rõ **sự kiện trong phim** với **phần tưởng tượng "What if"**, và không bịa sự kiện, lời thoại hay số liệu.

### 3. Âm thanh
- **Không dùng nhạc phim, nhạc nền gốc hay đoạn âm thanh trích từ phim.** Chỉ dùng nhạc và hiệu ứng có giấy phép rõ ràng (YouTube Audio Library, Pixabay…).
- **Không mô phỏng hay nhái giọng diễn viên.** Người dẫn chuyện dùng giọng TTS chung chung.

### 4. Thumbnail, tiêu đề, mô tả
- Thumbnail dùng **nhân vật thiết kế gốc**, không dùng ảnh phim, logo hay phông chữ của phim.
- Tiêu đề kiểu *"What If [Tên phản diện] Won?"* là được. Không ghi "Official", không khiến người xem tưởng là sản phẩm của hãng.
- Gợi ý ghi trong phần mô tả: *"Fan-made commentary and parody. Not affiliated with or endorsed by the original rights holders. All characters are original stick-figure designs."*
- Tránh hình thức khiến video bị xếp vào mục **"dành cho trẻ em"**, và giữ mức an toàn cho quảng cáo: không máu me, không chiếu vụ nổ hay thương vong.

### 5. Mỗi đề xuất mới phải có
- Bảng **"Nhân vật thiết kế gốc"**: vai trò trong phim, thiết kế mới, và những dấu hiệu đã thay đổi.
- Mục **"Phần lấy từ phim và phần tưởng tượng"**.
- Mục **"Kiểm tra bản quyền"**: prompt ảnh không chứa tên riêng, không có logo, không có nhạc phim.

## Quy trình mặc định
1. Đề xuất (kịch bản, lời đọc tiếng Anh kèm bản dịch tiếng Việt, hình ảnh) → chờ người dùng duyệt.
2. File sản xuất Givemotion: prompt ảnh ChatGPT (ảnh mẫu, tư thế PNG nền trong suốt, đạo cụ, nền), kịch bản ghi rõ ảnh cho từng cảnh, lời đọc gộp sẵn, âm thanh, bản giao việc.
3. Định dạng ưa thích: **mini-series 3 phần nhịp nhanh**, mỗi cảnh 3–6 giây, **hook 3 giây đầu** (tối đa 8 từ, tiếng "hit" ở giây 0,0, chữ to trên hình), cliffhanger cuối mỗi phần. Zeke (người que mũ len đỏ, áo vàng) là người quan sát không nói.
4. Commit và push lên nhánh làm việc sau mỗi file mới.
