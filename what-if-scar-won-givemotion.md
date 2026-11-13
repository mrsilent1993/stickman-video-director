# What If Scar Won? Kịch bản sản xuất cho Givemotion

**16:9 · 1080p · khoảng 3 phút · 18 cảnh · lời đọc tiếng Anh · phong cách người que tối giản, nền điện ảnh nhiều màu**

> ⚠️ **Givemotion không tạo được giọng đọc.** Givemotion chỉ ghép âm thanh có sẵn (giọng đọc, nhạc, hiệu ứng) vào video và tạo phụ đề khớp với giọng đọc. Bạn cần một file **giọng đọc mp3** làm từ công cụ chuyển văn bản thành giọng nói (ChatGPT, ElevenLabs, Gemini…) hoặc tự thu. Phần 4 có hướng dẫn chi tiết.

## Mục lục
1. Nhân vật
2. Danh sách ảnh và prompt cho ChatGPT
3. Kịch bản 18 cảnh
4. Âm thanh
5. Cấu trúc thư mục
6. Bản giao việc dán cho agent Givemotion

---

# 1. Nhân vật

| Mã | Vai | Mô tả |
|---|---|---|
| ZEKE | Zeke | a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and simple thin black stick arms and legs. |
| SCAR | Scar | a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, a narrow sly brow line and a long thin tail ending in a black tuft. |
| OLD | Old Scar | the same lean dark-brown lion with the diagonal scar across his left eye, but now old: his black mane streaked with grey, his body thinner, his tail tuft greying. |
| SIMBA | Simba | a strong young adult male lion with golden fur, a full reddish-brown mane, a determined brow line and a tail with a reddish-brown tuft. |
| NALA | Nala | a sleek adult lioness with pale cream-gold fur, a small notch cut into the tip of her left ear, a calm steady brow line and no mane. |
| LIONESS | Lioness | a sleek sandy-gold lioness with no mane and no ear notch. |
| HYENA | Hyena | a scrawny grey hyena with black spots, a sloped back, round ears and a wide toothy grin drawn simply. |
| CUB | Lion cub | a small round sandy-gold lion cub. |

- **Zeke** là "du khách xuyên thời gian": quan sát và phản ứng, **không nói**. Lời đọc là người dẫn chuyện không xuất hiện trên hình.
- Các con vật **chỉ gợi** nhân vật trong phim, không vẽ lại y hệt thiết kế gốc. Không dùng ảnh, nhạc hay đoạn phim gốc.
- **Hướng màn hình:** mỏm đá ngai vàng ở giữa, đồi xanh ở **bên phải**. Ai rời vương quốc thì đi sang phải.
- **Màu theo câu chuyện:** vàng nắng (chiến thắng), cam bụi và nâu khô (hạn hán), xám tím (cô độc), xanh lá (đồi của Nala), hoàng hôn cam (kết).

---

# 2. Danh sách ảnh và prompt cho ChatGPT

**Cách làm trong ChatGPT:**
1. Tạo ảnh **mẫu nhân vật** trước (mục 2.1). Mỗi nhân vật chọn 1 bản đẹp nhất.
2. Tạo các **tư thế** trong **cùng cuộc trò chuyện**, và lần nào cũng **đính kèm lại ảnh mẫu** của nhân vật đó kèm câu *"Keep exactly the same character design as the attached reference."*
3. Ảnh nhân vật và đạo cụ phải có **nền trong suốt** (PNG). Nếu ChatGPT trả về nền trắng, nhắn thêm *"make the background transparent"*.
4. Ảnh nền nên chọn khung **ngang rộng nhất có thể**. Nếu ảnh ra tỉ lệ 3:2, Givemotion sẽ cắt thành 16:9, nên đừng đặt chi tiết quan trọng sát mép trên hoặc dưới.
5. Đặt tên file **đúng như mã** (ví dụ `scar-roar.png`).

Tổng cộng: **8 ảnh mẫu, 40 tư thế, 10 đạo cụ, 15 ảnh nền.** Có thể bớt tư thế nếu muốn tiết kiệm, Givemotion có thể dùng lại một tư thế nhiều lần.

## 2.1 Ảnh mẫu nhân vật (8 ảnh)

**ref-zeke.png**
```text
Character reference sheet: front view, side view and back view side by side at the same scale. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and simple thin black stick arms and legs. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Plain transparent background. No text, no labels, no watermark.
```

**ref-scar.png**
```text
Character reference sheet: front view, side view and back view side by side at the same scale. Scar: a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, a narrow sly brow line and a long thin tail ending in a black tuft. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Plain transparent background. No text, no labels, no watermark.
```

**ref-old.png**
```text
Character reference sheet: front view, side view and back view side by side at the same scale. Old Scar: the same lean dark-brown lion with the diagonal scar across his left eye, but now old: his black mane streaked with grey, his body thinner, his tail tuft greying. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Plain transparent background. No text, no labels, no watermark.
```

**ref-simba.png**
```text
Character reference sheet: front view, side view and back view side by side at the same scale. Simba: a strong young adult male lion with golden fur, a full reddish-brown mane, a determined brow line and a tail with a reddish-brown tuft. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Plain transparent background. No text, no labels, no watermark.
```

**ref-nala.png**
```text
Character reference sheet: front view, side view and back view side by side at the same scale. Nala: a sleek adult lioness with pale cream-gold fur, a small notch cut into the tip of her left ear, a calm steady brow line and no mane. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Plain transparent background. No text, no labels, no watermark.
```

**ref-lioness.png**
```text
Character reference sheet: front view, side view and back view side by side at the same scale. Lioness: a sleek sandy-gold lioness with no mane and no ear notch. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Plain transparent background. No text, no labels, no watermark.
```

**ref-hyena.png**
```text
Character reference sheet: front view, side view and back view side by side at the same scale. Hyena: a scrawny grey hyena with black spots, a sloped back, round ears and a wide toothy grin drawn simply. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Plain transparent background. No text, no labels, no watermark.
```

**ref-cub.png**
```text
Character reference sheet: front view, side view and back view side by side at the same scale. Lion cub: a small round sandy-gold lion cub. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Plain transparent background. No text, no labels, no watermark.
```

## 2.2 Tư thế nhân vật (PNG nền trong suốt)

### ZEKE  (đính kèm `ref-zeke.png`)

**zeke-binoculars.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and simple thin black stick arms and legs. Pose: standing in three-quarter view, holding binoculars up to his eyes with both hands. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**zeke-shocked.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and simple thin black stick arms and legs. Pose: standing, mouth dropped open in a small round shock shape, both arms slightly raised. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**zeke-pull.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and simple thin black stick arms and legs. Pose: leaning back and pulling down on something with both hands above his head, as if pulling a rope or lever. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**zeke-peek.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and simple thin black stick arms and legs. Pose: tiptoeing and leaning forward with curiosity, one hand raised as if lifting a curtain corner. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**zeke-reading.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and simple thin black stick arms and legs. Pose: sitting cross-legged, holding a large open picture book with blank pages on his lap, looking down at it. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**zeke-cover-eyes.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and simple thin black stick arms and legs. Pose: standing and covering his eyes with both hands, flinching. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**zeke-clap.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and simple thin black stick arms and legs. Pose: clapping slowly with an awkward sideways glance. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**zeke-counting.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and simple thin black stick arms and legs. Pose: counting on his fingers with a confused expression, a small question-mark-shaped wobble in his posture (no actual symbol). Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**zeke-crown.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and simple thin black stick arms and legs. Pose: standing proudly with chest out, wearing a blank yellow paper crown on top of his red beanie. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**zeke-umbrella.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and simple thin black stick arms and legs. Pose: holding an open blue umbrella above his head, looking up at the sky hopefully. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**zeke-headshake.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and simple thin black stick arms and legs. Pose: standing with arms crossed, head tilted, disapproving expression. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**zeke-wave.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and simple thin black stick arms and legs. Pose: waving goodbye with one raised arm, gentle smile. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**zeke-lying.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and simple thin black stick arms and legs. Pose: lying on his back with hands behind his head, smiling, side view. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**zeke-walk.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and simple thin black stick arms and legs. Pose: walking in side view facing right, hands in pockets. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**zeke-shrug.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and simple thin black stick arms and legs. Pose: facing the viewer and doing a big exaggerated shrug with both palms up. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

### SCAR  (đính kèm `ref-scar.png`)

**scar-roar.png**
```text
Keep exactly the same character design as the attached reference. Scar: a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, a narrow sly brow line and a long thin tail ending in a black tuft. Pose: standing on all fours in side view facing left, head raised high, mouth open in a mighty roar. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**scar-proud.png**
```text
Keep exactly the same character design as the attached reference. Scar: a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, a narrow sly brow line and a long thin tail ending in a black tuft. Pose: standing tall in three-quarter view, chin up, smug half-smile. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**scar-uneasy.png**
```text
Keep exactly the same character design as the attached reference. Scar: a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, a narrow sly brow line and a long thin tail ending in a black tuft. Pose: sitting, glancing sideways nervously, ears slightly back. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**scar-glare.png**
```text
Keep exactly the same character design as the attached reference. Scar: a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, a narrow sly brow line and a long thin tail ending in a black tuft. Pose: lying with front paws crossed, eyes narrowed in suspicion, looking to the right. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**scar-command.png**
```text
Keep exactly the same character design as the attached reference. Scar: a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, a narrow sly brow line and a long thin tail ending in a black tuft. Pose: standing and pointing one front paw forward as if giving an order. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**scar-thin.png**
```text
Keep exactly the same character design as the attached reference. Scar: a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, a narrow sly brow line and a long thin tail ending in a black tuft. Pose: sitting alone, visibly thinner, shoulders sagging, staring ahead. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

### OLD  (đính kèm `ref-old.png`)

**oldscar-sitting.png**
```text
Keep exactly the same character design as the attached reference. Old Scar: the same lean dark-brown lion with the diagonal scar across his left eye, but now old: his black mane streaked with grey, his body thinner, his tail tuft greying. Pose: sitting alone in side view facing right, head slightly lowered, tired eyes. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**oldscar-soft.png**
```text
Keep exactly the same character design as the attached reference. Old Scar: the same lean dark-brown lion with the diagonal scar across his left eye, but now old: his black mane streaked with grey, his body thinner, his tail tuft greying. Pose: sitting, looking up and to the right with a softened, relaxed brow for the first time. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**oldscar-walk.png**
```text
Keep exactly the same character design as the attached reference. Old Scar: the same lean dark-brown lion with the diagonal scar across his left eye, but now old: his black mane streaked with grey, his body thinner, his tail tuft greying. Pose: walking slowly in side view facing right. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**oldscar-bow.png**
```text
Keep exactly the same character design as the attached reference. Old Scar: the same lean dark-brown lion with the diagonal scar across his left eye, but now old: his black mane streaked with grey, his body thinner, his tail tuft greying. Pose: sitting with his head bowed slightly, calm and humble. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

### SIMBA  (đính kèm `ref-simba.png`)

**simba-face.png**
```text
Keep exactly the same character design as the attached reference. Simba: a strong young adult male lion with golden fur, a full reddish-brown mane, a determined brow line and a tail with a reddish-brown tuft. Pose: standing in side view facing right in a defiant stance, mane lifted by wind. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**simba-slip.png**
```text
Keep exactly the same character design as the attached reference. Simba: a strong young adult male lion with golden fur, a full reddish-brown mane, a determined brow line and a tail with a reddish-brown tuft. Pose: off-balance, sliding backward with front paws scrambling, surprised expression, unhurt. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

### NALA  (đính kèm `ref-nala.png`)

**nala-stalk.png**
```text
Keep exactly the same character design as the attached reference. Nala: a sleek adult lioness with pale cream-gold fur, a small notch cut into the tip of her left ear, a calm steady brow line and no mane. Pose: crouching low in side view facing right, stalking with focused eyes. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**nala-look.png**
```text
Keep exactly the same character design as the attached reference. Nala: a sleek adult lioness with pale cream-gold fur, a small notch cut into the tip of her left ear, a calm steady brow line and no mane. Pose: sitting upright with her head turned over her shoulder, looking back with a serious expression. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**nala-walk.png**
```text
Keep exactly the same character design as the attached reference. Nala: a sleek adult lioness with pale cream-gold fur, a small notch cut into the tip of her left ear, a calm steady brow line and no mane. Pose: walking calmly in side view facing right, head held high, leading. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**nala-rest.png**
```text
Keep exactly the same character design as the attached reference. Nala: a sleek adult lioness with pale cream-gold fur, a small notch cut into the tip of her left ear, a calm steady brow line and no mane. Pose: lying down relaxed, head lifted, calm expression. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

### LIONESS  (đính kèm `ref-lioness.png`)

**lioness-crouch.png**
```text
Keep exactly the same character design as the attached reference. Lioness: a sleek sandy-gold lioness with no mane and no ear notch. Pose: crouching low in side view facing right. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**lioness-walk.png**
```text
Keep exactly the same character design as the attached reference. Lioness: a sleek sandy-gold lioness with no mane and no ear notch. Pose: walking in side view facing right. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**lioness-glance.png**
```text
Keep exactly the same character design as the attached reference. Lioness: a sleek sandy-gold lioness with no mane and no ear notch. Pose: sitting and glancing sideways with a quiet worried expression. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

### HYENA  (đính kèm `ref-hyena.png`)

**hyena-cheer.png**
```text
Keep exactly the same character design as the attached reference. Hyena: a scrawny grey hyena with black spots, a sloped back, round ears and a wide toothy grin drawn simply. Pose: jumping and dancing with joy, tongue out. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**hyena-bowl.png**
```text
Keep exactly the same character design as the attached reference. Hyena: a scrawny grey hyena with black spots, a sloped back, round ears and a wide toothy grin drawn simply. Pose: sitting up and begging, holding an empty wooden bowl with both front paws. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**hyena-guard.png**
```text
Keep exactly the same character design as the attached reference. Hyena: a scrawny grey hyena with black spots, a sloped back, round ears and a wide toothy grin drawn simply. Pose: standing stiffly at attention in side view facing right. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**hyena-leave.png**
```text
Keep exactly the same character design as the attached reference. Hyena: a scrawny grey hyena with black spots, a sloped back, round ears and a wide toothy grin drawn simply. Pose: slinking away in side view facing left, head low, tail down. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

### CUB  (đính kèm `ref-cub.png`)

**cub-play.png**
```text
Keep exactly the same character design as the attached reference. Lion cub: a small round sandy-gold lion cub. Pose: tumbling playfully on its back, paws in the air. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

**cub-chase.png**
```text
Keep exactly the same character design as the attached reference. Lion cub: a small round sandy-gold lion cub. Pose: pouncing forward in side view, chasing something. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin around the character. No text, no letters, no watermark.
```

## 2.3 Đạo cụ (PNG nền trong suốt)

**prop-lever.png**
```text
a tall wooden post with a big lever topped by a glowing brass handle, softly glowing. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Isolated on a transparent background, no scenery. No text, no letters, no watermark.
```

**prop-curtain.png**
```text
a giant red theatre stage curtain panel with golden fringe at the bottom, hanging straight (one half only, it will be mirrored). Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Isolated on a transparent background, no scenery. No text, no letters, no watermark.
```

**prop-crown.png**
```text
a simple blank yellow paper crown with five points, no decoration. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Isolated on a transparent background, no scenery. No text, no letters, no watermark.
```

**prop-bowl.png**
```text
a small empty wooden bowl. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Isolated on a transparent background, no scenery. No text, no letters, no watermark.
```

**prop-beetle.png**
```text
a small dung beetle pushing a round ball, side view facing right. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Isolated on a transparent background, no scenery. No text, no letters, no watermark.
```

**prop-butterfly.png**
```text
a small orange butterfly with wings open. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Isolated on a transparent background, no scenery. No text, no letters, no watermark.
```

**prop-birds.png**
```text
a small flock of five simple dark birds in flight facing right. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Isolated on a transparent background, no scenery. No text, no letters, no watermark.
```

**prop-tumbleweed.png**
```text
a round dry tumbleweed. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Isolated on a transparent background, no scenery. No text, no letters, no watermark.
```

**prop-thornfence.png**
```text
a horizontal segment of fence made of tangled thorny branches. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Isolated on a transparent background, no scenery. No text, no letters, no watermark.
```

**prop-herd.png**
```text
a line of antelope and zebras walking in side view facing right, simple silhouettes with flat color. Minimalist 2D vector cartoon, simple clean black outlines, flat vibrant colors, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic fur or texture. Isolated on a transparent background, no scenery. No text, no letters, no watermark.
```

## 2.4 Ảnh nền (không có nhân vật)

**bg01-sunrise.png**
```text
A vast African savanna at sunrise with golden grass, flat-topped acacia trees and one towering jutting rock outcrop at the center that serves as a king's throne; a grassy hill in the left foreground; warm gold sunrise light and morning mist. Wide landscape background in 16:9 framing, NO characters and NO animals, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, matching a minimalist vector cartoon style with clean outlines. Leave open space in the lower center for characters to be placed. No text, no letters, no watermark.
```

**bg02-savanna-day.png**
```text
A lively golden savanna in warm daylight with grazing-land grass, acacia trees and drifting white clouds; open and peaceful. Wide landscape background in 16:9 framing, NO characters and NO animals, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, matching a minimalist vector cartoon style with clean outlines. Leave open space in the lower center for characters to be placed. No text, no letters, no watermark.
```

**bg03-book-stampede.png**
```text
An open storybook page shown full frame, with an illustration of a rocky canyon filled with a huge rolling cloud of dust from a stampede, in dusty amber tones; no animals visible inside the dust, no writing on the page. Wide landscape background in 16:9 framing, NO characters and NO animals, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, matching a minimalist vector cartoon style with clean outlines. Leave open space in the lower center for characters to be placed. No text, no letters, no watermark.
```

**bg04-summit-dusk.png**
```text
The summit of the towering rock outcrop at dusk, steep rocky edge on the left, wisps of smoke drifting, orange-violet dramatic sky. Wide landscape background in 16:9 framing, NO characters and NO animals, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, matching a minimalist vector cartoon style with clean outlines. Leave open space in the lower center for characters to be placed. No text, no letters, no watermark.
```

**bg05-rock-base-day.png**
```text
The foot of the towering rock outcrop in hot midday light, dusty flat ground in front, grass starting to fade from gold toward dusty orange. Wide landscape background in 16:9 framing, NO characters and NO animals, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, matching a minimalist vector cartoon style with clean outlines. Leave open space in the lower center for characters to be placed. No text, no letters, no watermark.
```

**bg06-tall-grass.png**
```text
Tall dry savanna grass in late afternoon, dusty orange light, the towering rock outcrop small in the far distance. Wide landscape background in 16:9 framing, NO characters and NO animals, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, matching a minimalist vector cartoon style with clean outlines. Leave open space in the lower center for characters to be placed. No text, no letters, no watermark.
```

**bg07-dry-waterhole.png**
```text
A dried waterhole of cracked brown mud under harsh sunlight, dead grass around it, dry brown palette. Wide landscape background in 16:9 framing, NO characters and NO animals, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, matching a minimalist vector cartoon style with clean outlines. Leave open space in the lower center for characters to be placed. No text, no letters, no watermark.
```

**bg08-dry-sky.png**
```text
A dry pale sky with thin clouds over a brown, withered savanna, the towering rock outcrop on the left, washed-out light. Wide landscape background in 16:9 framing, NO characters and NO animals, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, matching a minimalist vector cartoon style with clean outlines. Leave open space in the lower center for characters to be placed. No text, no letters, no watermark.
```

**bg09-border.png**
```text
The edge of a dry kingdom: cracked brown ground and dead grass under a harsh low sun with long shadows. Wide landscape background in 16:9 framing, NO characters and NO animals, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, matching a minimalist vector cartoon style with clean outlines. Leave open space in the lower center for characters to be placed. No text, no letters, no watermark.
```

**bg10-dawn-hills.png**
```text
Pale soft dawn over the dry kingdom on the left side, with green hills glowing faintly on the far right horizon. Wide landscape background in 16:9 framing, NO characters and NO animals, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, matching a minimalist vector cartoon style with clean outlines. Leave open space in the lower center for characters to be placed. No text, no letters, no watermark.
```

**bg11-empty-rock.png**
```text
The base of the towering rock outcrop, bare and empty, dusty ground, light fading from orange toward grey. Wide landscape background in 16:9 framing, NO characters and NO animals, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, matching a minimalist vector cartoon style with clean outlines. Leave open space in the lower center for characters to be placed. No text, no letters, no watermark.
```

**bg12-summit-dust.png**
```text
The summit of the towering rock outcrop wrapped in swirling dust under a grey-violet dusk sky, lonely and silent. Wide landscape background in 16:9 framing, NO characters and NO animals, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, matching a minimalist vector cartoon style with clean outlines. Leave open space in the lower center for characters to be placed. No text, no letters, no watermark.
```

**bg13-green-hills.png**
```text
Lush green rolling hills with a flowing stream, wildflowers and a large shady tree, warm late-afternoon sunlight. Wide landscape background in 16:9 framing, NO characters and NO animals, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, matching a minimalist vector cartoon style with clean outlines. Leave open space in the lower center for characters to be placed. No text, no letters, no watermark.
```

**bg14-border-sunset.png**
```text
The line where dry cracked brown ground meets lush green grass, running across the frame, under a warm orange sunset; green hills in the distance on the right. Wide landscape background in 16:9 framing, NO characters and NO animals, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, matching a minimalist vector cartoon style with clean outlines. Leave open space in the lower center for characters to be placed. No text, no letters, no watermark.
```

**bg15-aerial.png**
```text
A high aerial view at sunset: the bare towering rock outcrop on the left side of a dry plain and glowing green hills on the right side, a winding river between. Wide landscape background in 16:9 framing, NO characters and NO animals, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, matching a minimalist vector cartoon style with clean outlines. Leave open space in the lower center for characters to be placed. No text, no letters, no watermark.
```

---

# 3. Kịch bản 18 cảnh

Mỗi cảnh **khoảng 10 giây**. Thời lượng thật của từng cảnh **khớp theo giọng đọc**: Givemotion lấy mốc thời gian từng chữ bằng lệnh `words` rồi chia cảnh theo đó.

| # | Thời điểm | Nền | Nhân vật và đạo cụ | Chuyển động | Chữ trên hình | Hiệu ứng âm thanh | Chuyển cảnh |
|---|---|---|---|---|---|---|---|
| 1 | 0:00 | `bg01-sunrise` | zeke-binoculars (trái, tiền cảnh) → zeke-shocked; scar-roar trên đỉnh đá (giữa); prop-lever (trái) | Mở đầu bằng khung ống nhòm (viền đen hình 2 vòng tròn) zoom vào Scar trên đỉnh đá, Scar nhún nhẹ khi gầm; cắt về Zeke đổi sang tư thế shocked; lever trượt vào bên cạnh. | VILLAIN WINS | Gió, tiếng sư tử gầm vang, chim bay | Zoom nhanh |
| 2 | 0:10 | `bg02-savanna-day` | zeke-pull → zeke-peek; prop-curtain (2 nửa) | Hai nửa rèm trượt từ hai bên vào khép kín; Zeke kéo dây; rèm hé một góc, Zeke ngó; rèm mở toang lộ đồng cỏ sống động (mây trôi chậm). | — | Tiếng rèm sột soạt, gió đồng cỏ | Rèm mở |
| 3 | 0:20 | `bg02-savanna-day → bg03-book-stampede` | zeke-reading; cub-chase (đóng vai sư tử con chạy trốn, thu nhỏ dần về chân trời) | Zeke ngồi đọc sách; camera zoom vào trang sách thành bg03; bụi cuộn (lớp bụi trượt ngang); bóng nhỏ chạy về chân trời và nhỏ dần. | — | Lật trang, tiếng vó rền, gió | Lật trang |
| 4 | 0:30 | `bg04-summit-dusk` | simba-face (phải) đối mặt scar-proud (trái) → simba-slip trượt xuống mép đá, mờ dần vào khói; zeke-cover-eyes (góc trái dưới) | Hai con xoay nhẹ đối mặt; Simba đổi sang slip, trượt chéo xuống và mờ dần (opacity) vào khói; Scar còn một mình; Zeke che mắt bật vào góc. | — | Gầm gừ, gió giật, đá lăn, rồi im bặt | Mờ sang trắng |
| 5 | 0:40 | `bg01-sunrise` | scar-roar trên đỉnh; hyena-cheer ×5 dưới chân đá; zeke-clap (trái) | Linh cẩu nhún nhảy so le (stagger); Scar nhún khi gầm; Zeke vỗ tay lắc nhẹ. | DAY 1 | Gầm chiến thắng, linh cẩu cười khúc khích, vỗ tay lẹt đẹt | Cắt |
| 6 | 0:50 | `bg05-rock-base-day` | hyena-bowl ×8 xếp hàng, thêm dần; scar-uneasy trên đá; zeke-counting | Hàng linh cẩu xuất hiện từng con nối đuôi (stagger), camera lia ngang theo hàng dài; Scar đổi sang uneasy; Zeke counting. | DAY 2 | Bụng réo, bát lách cách, rên rỉ | Lia ngang |
| 7 | 1:00 | `bg05-rock-base-day → bg06-tall-grass` | zeke-crown + prop-tumbleweed; nala-stalk + lioness-crouch ×3; scar-glare (nhỏ, xa) | Zeke đội vương miện đứng chờ, tumbleweed lăn qua; cắt sang cỏ cao, sư tử cái bò chậm; Nala đổi sang nala-look; chèn khung nhỏ Scar glare. | — | Tumbleweed sột soạt, cỏ xào xạc, gầm gừ nhỏ | Cắt |
| 8 | 1:10 | `bg06-tall-grass → bg07-dry-waterhole` | lioness-walk ×3, nala-walk; nala-look; lioness-glance ×3 | Bụi bung (particle burst) săn hụt; chuyển nền vũng nước khô; các sư tử cái lần lượt đổi sang glance (stagger), camera lia chậm. | — | Chạy rầm rập, đất nứt, gió khô | Ngửa camera lên trời |
| 9 | 1:20 | `bg08-dry-sky` | prop-herd trượt sang phải; scar-roar (trái, trên đá); zeke-umbrella | Đàn thú trượt chậm sang phải và ra khỏi khung; Scar gầm; Zeke giơ ô, không có mưa. | MONTH 6 | Gió khô, vó bước xa dần, tiếng gầm khàn, bật ô | Cắt |
| 10 | 1:30 | `bg09-border` | scar-command; hyena-guard ×6 xếp hàng; prop-thornfence mọc lên; zeke-headshake | Linh cẩu bật vào thành hàng (stagger); hàng rào trượt từ dưới lên; vết nứt (đường vẽ tự vẽ) lan trên mặt đất; Zeke lắc đầu. | — | Kéo cành gai, linh cẩu càu nhàu, đất nứt | Mờ qua đêm |
| 11 | 1:40 | `bg10-dawn-hills` | nala-walk dẫn đầu + lioness-walk ×5 nối đuôi đi sang phải; zeke-wave (trái) | Hàng sư tử cái trượt sang phải nối đuôi (stagger), camera lia theo; Zeke vẫy tay; con cuối dừng 0,5s rồi đi tiếp. | YEAR 1 | Bước chân nhẹ, chim bình minh | Cắt |
| 12 | 1:50 | `bg11-empty-rock` | hyena-guard ×4 → hyena-leave; scar-thin trên đá | Linh cẩu nhìn quanh, rồi lần lượt đổi sang leave và trượt ra trái; Scar thin ở lại, ánh sáng ngả xám. | — | Đánh hơi, rên, bước chân rời đi, gió | Zeke kéo cần gạt |
| 13 | 2:00 | `bg12-summit-dust` | zeke-pull + prop-lever (mở đầu); oldscar-sitting | Zeke kéo cần gạt, bầu trời chớp nhanh (hiệu ứng tua thời gian); hiện Scar già; bụi bay (particles); camera đẩy chậm vào. | 10 YEARS LATER | Vù vù tua thời gian, rồi gió cô độc | Lia nhanh sang phải |
| 14 | 2:10 | `bg13-green-hills` | nala-rest, lioness-walk ×2, cub-play ×2, cub-chase + prop-butterfly; zeke-lying | Sư tử con lăn, vồ (nhún, xoay nhẹ); bướm bay theo đường cong; Zeke nằm cười. | — | Suối chảy, chim hót, sư tử con kêu | Bướm bay sang trái |
| 15 | 2:20 | `bg12-summit-dust (ánh sáng ấm dần)` | oldscar-sitting → oldscar-soft; prop-beetle; prop-butterfly; prop-birds | Bọ hung lăn qua chân Scar; bướm và đàn chim bay sang phải; Scar đổi sang soft; nền chuyển dần từ xám tím sang hổ phách. | — | Bọ lăn, cánh vỗ, tiếng thở dài | Cắt |
| 16 | 2:30 | `bg09-border (ánh hổ phách)` | oldscar-walk sang phải; zeke-walk theo sau | Hai nhân vật trượt sang phải, nhún nhẹ theo bước (bob); camera lia theo. | — | Bước chân nặng chậm, gió nhẹ | Cắt |
| 17 | 2:40 | `bg14-border-sunset` | oldscar-walk → oldscar-bow ở ranh giới; nala-rest + cub-play (xa, bên phải) | Scar dừng ở vạch ranh giới, đổi sang bow; Nala ngẩng đầu nhìn; hoàng hôn cam. | — | Dế kêu, gió nhẹ, tiếng sư tử gọi xa | Cắt |
| 18 | 2:50 | `bg11-empty-rock → bg15-aerial` | zeke-walk → prop-crown đặt lên đá → zeke-shrug | Zeke đặt vương miện lên đá, quay ra nhún vai; camera kéo lên thành cảnh từ trên cao bg15; nhạc kết. | Kêu gọi bình luận (tùy chọn) | Giấy sột soạt, gió, nốt nhạc cuối | Kết |

## Lời đọc theo cảnh (dùng để tạo giọng và phụ đề)

**1.** Scar won. Simba lost the final fight on Pride Rock. And that is exactly when Scar's real nightmare began.
*Scar đã thắng. Simba thua trận cuối trên Pride Rock. Và đó chính là lúc ác mộng thật sự của Scar bắt đầu.*

**2.** We all assume the story ends when the villain wins. The hero falls, the credits roll. But a kingdom doesn't stop at the credits.
*Ta luôn nghĩ câu chuyện kết thúc khi phản diện thắng. Anh hùng ngã xuống, phim hết. Nhưng một vương quốc không dừng lại theo phim.*

**3.** Remember the original. Scar caused Mufasa's death, blamed young Simba, and sent him running into exile, far from home.
*Nhớ lại phim gốc: Scar gây ra cái chết của Mufasa, đổ tội cho Simba nhỏ và khiến cậu phải trốn đi lưu vong, xa quê hương.*

**4.** Years later, Simba returned to fight. In our story, his paw slips at the edge, and Scar is left standing alone.
*Nhiều năm sau, Simba quay về chiến đấu. Trong câu chuyện của chúng ta, chân cậu trượt ở mép đá, và chỉ còn Scar đứng đó.*

**5.** Day one. Scar climbs Pride Rock and roars. The hyenas cheer. For one night, he finally has everything he wanted.
*Ngày thứ nhất. Scar leo lên Pride Rock và gầm vang. Bầy linh cẩu reo hò. Trong một đêm, hắn có tất cả những gì hắn muốn.*

**6.** Day two. The hyenas are hungry. Scar promised them food, and the pack keeps growing, waiting for him to deliver.
*Ngày thứ hai. Bầy linh cẩu đói. Scar đã hứa cho chúng thức ăn, và bầy cứ đông thêm, chờ hắn thực hiện lời hứa.*

**7.** Here's the secret every king learns: a crown doesn't hunt. The lionesses do. And they are watching Scar very closely.
*Đây là bí mật mà vị vua nào cũng phải học: vương miện không biết săn mồi. Sư tử cái mới săn. Và họ đang theo dõi Scar rất kỹ.*

**8.** Nala leads them. Every failed hunt, every empty waterhole, they quietly ask the same question: why are we following him?
*Nala dẫn đầu họ. Mỗi cuộc săn hụt, mỗi vũng nước cạn, họ lặng lẽ hỏi cùng một câu: sao ta lại theo hắn?*

**9.** Month six. The rains are late. Herds walk away to find grass. Scar can't roar them back. No speech can bring the clouds.
*Tháng thứ sáu. Mưa đến muộn. Các đàn thú bỏ đi tìm cỏ. Scar không thể gầm cho chúng quay lại. Không lời hô hào nào gọi được mây về.*

**10.** Scar tries what villains always try. More rules. More guards. More hyenas at the border. The land only grows thinner.
*Scar làm điều mà phản diện nào cũng làm: thêm luật, thêm lính canh, thêm linh cẩu ở biên giới. Còn đất đai thì cứ cằn cỗi dần.*

**11.** Year one. The lionesses don't fight him. They do something worse. One morning, they simply walk away, together, toward the green hills.
*Năm thứ nhất. Các sư tử cái không chống lại hắn. Họ làm điều còn tệ hơn: một sáng nọ, họ cùng nhau lặng lẽ bỏ đi, về phía những ngọn đồi xanh.*

**12.** Now the hyenas see what's left: an empty rock, a thin king, and nothing to eat. Loyalty runs out with the food.
*Giờ bầy linh cẩu thấy những gì còn lại: một mỏm đá trống, một ông vua gầy gò và chẳng có gì ăn. Lòng trung thành cạn cùng thức ăn.*

**13.** Ten years later. Scar still sits on Pride Rock. Technically, he is king. King of dust, wind, and silence.
*Mười năm sau. Scar vẫn ngồi trên Pride Rock. Về danh nghĩa, hắn là vua. Vua của bụi, gió và sự im lặng.*

**14.** And far away, in the green hills, Nala's pride is thriving. Cubs are born who have never heard Scar's name.
*Còn ở xa, trên những ngọn đồi xanh, bầy của Nala sinh sôi. Những chú sư tử con ra đời chưa từng nghe tên Scar.*

**15.** Here's the twist. Scar finally understands what Mufasa believed: a king is part of the circle of life, not above it.
*Và đây là cú twist: Scar cuối cùng cũng hiểu điều Mufasa từng tin: vua là một phần của vòng đời, chứ không đứng trên nó.*

**16.** So old Scar does something no one expects. He walks down from Pride Rock, alone, toward the hills.
*Thế là Scar già làm điều không ai ngờ: hắn bước xuống khỏi Pride Rock, một mình, về phía những ngọn đồi.*

**17.** He didn't lose to a hero. He lost to the one thing he never respected: everyone who quietly kept the kingdom alive.
*Hắn không thua một người hùng. Hắn thua thứ duy nhất hắn chưa bao giờ tôn trọng: tất cả những ai lặng lẽ giữ cho vương quốc sống.*

**18.** Winning the throne was easy. Keeping a kingdom was impossible. So, was Scar a villain, or just a terrible boss? Tell me below.
*Giành ngai vàng thì dễ. Giữ vương quốc mới là bất khả thi. Vậy Scar là phản diện, hay chỉ là một ông sếp tồi? Bình luận cho mình biết nhé.*

**Toàn bộ lời đọc (dán vào công cụ tạo giọng):**
```text
Scar won. Simba lost the final fight on Pride Rock. And that is exactly when Scar's real nightmare began.

We all assume the story ends when the villain wins. The hero falls, the credits roll. But a kingdom doesn't stop at the credits.

Remember the original. Scar caused Mufasa's death, blamed young Simba, and sent him running into exile, far from home.

Years later, Simba returned to fight. In our story, his paw slips at the edge, and Scar is left standing alone.

Day one. Scar climbs Pride Rock and roars. The hyenas cheer. For one night, he finally has everything he wanted.

Day two. The hyenas are hungry. Scar promised them food, and the pack keeps growing, waiting for him to deliver.

Here's the secret every king learns: a crown doesn't hunt. The lionesses do. And they are watching Scar very closely.

Nala leads them. Every failed hunt, every empty waterhole, they quietly ask the same question: why are we following him?

Month six. The rains are late. Herds walk away to find grass. Scar can't roar them back. No speech can bring the clouds.

Scar tries what villains always try. More rules. More guards. More hyenas at the border. The land only grows thinner.

Year one. The lionesses don't fight him. They do something worse. One morning, they simply walk away, together, toward the green hills.

Now the hyenas see what's left: an empty rock, a thin king, and nothing to eat. Loyalty runs out with the food.

Ten years later. Scar still sits on Pride Rock. Technically, he is king. King of dust, wind, and silence.

And far away, in the green hills, Nala's pride is thriving. Cubs are born who have never heard Scar's name.

Here's the twist. Scar finally understands what Mufasa believed: a king is part of the circle of life, not above it.

So old Scar does something no one expects. He walks down from Pride Rock, alone, toward the hills.

He didn't lose to a hero. He lost to the one thing he never respected: everyone who quietly kept the kingdom alive.

Winning the throne was easy. Keeping a kingdom was impossible. So, was Scar a villain, or just a terrible boss? Tell me below.
```

---

# 4. Âm thanh

| Phần | Nguồn | Ghi chú |
|---|---|---|
| **Giọng đọc** | Công cụ tạo giọng: ChatGPT, ElevenLabs, Gemini… hoặc tự thu | Giọng nam trưởng thành, giọng Mỹ, baritone ấm, đọc điềm tĩnh, nhịp đều. Xuất một file liền mạch `voiceover.mp3`, nên ngắt khoảng 0,5 giây giữa các cảnh. |
| **Nhạc nền** | YouTube Audio Library, hoặc nhạc bạn có bản quyền | Piano trầm lắng và synth ambient nhẹ, không lời. **Không dùng nhạc phim gốc.** Đặt âm lượng thấp, khoảng 10–15%. |
| **Hiệu ứng âm thanh** | Pixabay Sound Effects, Freesound (kiểm tra giấy phép từng file) | Cần: sư tử gầm, linh cẩu cười, gió, rèm, lật trang, vó ngựa rền, đất nứt, tiếng tua thời gian (whoosh), chim, suối, dế. |
| **Phụ đề** | Givemotion lệnh `words` | Lấy mốc thời gian từng chữ từ `voiceover.mp3` và tạo phụ đề tiếng Anh tự động. |

Nếu muốn **tiếng Việt**, bạn tạo giọng từ phần *in nghiêng* ở mục 3. Lời đọc tiếng Việt sẽ dài hơn, nên video có thể quá 3 phút.

---

# 5. Cấu trúc thư mục

```
what-if-scar-won/
├── images/
│   ├── ref/          ← ref-zeke.png …
│   ├── chars/        ← zeke-binoculars.png, scar-roar.png …
│   ├── props/        ← prop-lever.png …
│   └── bg/           ← bg01-sunrise.png …
├── audio/
│   ├── voiceover.mp3
│   ├── music.mp3
│   └── sfx/          ← roar.mp3, wind.mp3 …
└── script.md         ← file này
```

---

# 6. Bản giao việc dán cho agent Givemotion
*(Dán đoạn dưới vào Claude Code hoặc Codex đã cài Givemotion, đặt trong thư mục dự án ở trên.)*

```text
Build a 16:9, 1080p, 30fps video with givemotion from this folder.
- Read script.md (section 3 is the scene table, section 1 the characters).
- Audio: audio/voiceover.mp3 is the master timeline. Run `givemotion words` on it and time all 18 scenes to the narration lines in section 3; scenes may vary around 10 s each.
- Visuals: each scene uses its background from images/bg (cover-fit to 16:9) and layers the transparent PNGs from images/chars and images/props as described in the "Chuyển động" column: slides, small bounces/bobs while walking, staggered entrances, pose swaps by cross-fading between pose images, gentle camera pans/zooms. Characters must never stay perfectly still for more than ~2.5 s.
- Keep screen direction: anyone leaving the kingdom moves to the right.
- Overlays: short title cards in the "Chữ trên hình" column (top-left, bold, e.g. Bebas Neue, white with dark shadow), plus word-synced English captions at the bottom, one line at a time.
- Music: audio/music.mp3 under the voice at ~12% volume with fade-out; SFX from audio/sfx at the actions listed, kept below the voice.
- Run `givemotion check` and `snapshot`, fix cut-off/overlapping text, then render a 20-second preview (scenes 1–2) first for my approval before the full render.
```
