# What If the Joker Won? Kịch bản sản xuất cho Givemotion (3 phần)

**16:9 · 1080p · 3 phần, tổng khoảng 7–8 phút · nhịp nhanh · lời đọc tiếng Anh**

> ⚠️ **Givemotion không tạo được giọng đọc.** Mỗi phần cần một file giọng đọc riêng: `voiceover-p1.mp3`, `voiceover-p2.mp3`, `voiceover-p3.mp3`, làm bằng công cụ chuyển văn bản thành giọng nói hoặc tự thu.

## Mục lục
1. Nhân vật
2. Prompt ảnh cho ChatGPT (13 ảnh mẫu, 42 tư thế, 26 đạo cụ, 24 nền)
3. Kịch bản 3 phần, có ghi rõ ảnh dùng cho từng cảnh
4. Âm thanh
5. Cấu trúc thư mục
6. Bản giao việc cho agent Givemotion

---

# 1. Nhân vật
Các nhân vật **chỉ gợi** hình ảnh trong phim, không vẽ lại trang phục gốc và **không dùng biểu tượng** (logo dơi…). Không dùng ảnh, nhạc hay đoạn phim gốc.

| Mã | Mô tả |
|---|---|
| `zeke` | Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and thin black stick limbs. |
| `joker` | Joker-inspired villain: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs; pale white face with dark smudged rings around the eyes, a wide red painted smile drawn around the mouth, messy shoulder-length green hair, a long purple coat over a green vest, purple trousers. Suggestive cartoon design, not a copy of any film costume. |
| `batman` | Masked vigilante: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, wearing a plain dark-grey bodysuit, a black cowl covering the head with two short pointed ears (only the white lower face visible), a long black cape and a plain grey utility belt. No chest emblem. |
| `gordon` | Police commissioner: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, middle-aged, thick grey-brown mustache, round glasses, a tan trench coat over a white shirt and brown tie. |
| `suit` | Businessman passenger: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, neatly combed dark hair, a dark-blue suit and tie. |
| `inmate` | Big inmate: a very large, tall, broad-shouldered version of a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, shaved head, an orange prison jumpsuit, calm serious expression. |
| `warden` | Prison warden: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, a dark-blue uniform with a peaked cap. |
| `civilian` | Ferry passenger (crowd member): a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, short brown hair, a muted green jacket and grey trousers. (For variety, also make a version with a ponytail and a muted red coat.) |
| `prisoner` | Prisoner (crowd member): a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, short dark hair, an orange prison jumpsuit. |
| `diver` | Diver: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, a black wetsuit, round diving mask and a small air tank on the back. |
| `teacher` | Teacher: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, hair tied in a bun, a light-blue cardigan and a long skirt. |
| `kids` | A small group of four child stick figures with round white heads, black dot eyes and thin black limbs, wearing matching yellow caps and backpacks. |
| `shadow` | A completely dark silhouette of a stick figure person in a hooded coat, face not visible, neutral gender. |

- **Hướng màn hình:** phà dân thường luôn ở **bên trái**, phà tù luôn ở **bên phải**.
- **Màu sắc:** đêm xanh đen và sương mù ở phần 1. Xám lạnh ở phần 2. Từ giữa phần 3 chuyển sang vàng ấm và nắng.
- **Nhạy cảm:** không có vụ nổ, lửa hay thương vong. Đèn phà chỉ tắt dần trong sương.

---

# 2. Prompt ảnh cho ChatGPT

**Cách làm:**
1. Tạo **ảnh mẫu** (mục 2.1) trước, mỗi nhân vật chọn 1 bản đẹp nhất.
2. Tạo các tư thế trong **cùng cuộc trò chuyện**, mỗi lần đính kèm lại ảnh mẫu của nhân vật đó.
3. Ảnh nhân vật và đạo cụ phải **nền trong suốt** (PNG). Ảnh nền chọn khung ngang rộng nhất có thể.
4. Đặt tên file **đúng như mã**.

## 2.1 Ảnh mẫu nhân vật

**ref-zeke.png**
```text
Character reference sheet: front, side and back views side by side at the same scale. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and thin black stick limbs. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Plain transparent background. No text, no labels, no watermark.
```

**ref-joker.png**
```text
Character reference sheet: front, side and back views side by side at the same scale. Joker-inspired villain: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs; pale white face with dark smudged rings around the eyes, a wide red painted smile drawn around the mouth, messy shoulder-length green hair, a long purple coat over a green vest, purple trousers. Suggestive cartoon design, not a copy of any film costume. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Plain transparent background. No text, no labels, no watermark.
```

**ref-batman.png**
```text
Character reference sheet: front, side and back views side by side at the same scale. Masked vigilante: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, wearing a plain dark-grey bodysuit, a black cowl covering the head with two short pointed ears (only the white lower face visible), a long black cape and a plain grey utility belt. No chest emblem. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Plain transparent background. No text, no labels, no watermark.
```

**ref-gordon.png**
```text
Character reference sheet: front, side and back views side by side at the same scale. Police commissioner: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, middle-aged, thick grey-brown mustache, round glasses, a tan trench coat over a white shirt and brown tie. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Plain transparent background. No text, no labels, no watermark.
```

**ref-suit.png**
```text
Character reference sheet: front, side and back views side by side at the same scale. Businessman passenger: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, neatly combed dark hair, a dark-blue suit and tie. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Plain transparent background. No text, no labels, no watermark.
```

**ref-inmate.png**
```text
Character reference sheet: front, side and back views side by side at the same scale. Big inmate: a very large, tall, broad-shouldered version of a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, shaved head, an orange prison jumpsuit, calm serious expression. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Plain transparent background. No text, no labels, no watermark.
```

**ref-warden.png**
```text
Character reference sheet: front, side and back views side by side at the same scale. Prison warden: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, a dark-blue uniform with a peaked cap. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Plain transparent background. No text, no labels, no watermark.
```

**ref-civilian.png**
```text
Character reference sheet: front, side and back views side by side at the same scale. Ferry passenger (crowd member): a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, short brown hair, a muted green jacket and grey trousers. (For variety, also make a version with a ponytail and a muted red coat.) Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Plain transparent background. No text, no labels, no watermark.
```

**ref-prisoner.png**
```text
Character reference sheet: front, side and back views side by side at the same scale. Prisoner (crowd member): a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, short dark hair, an orange prison jumpsuit. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Plain transparent background. No text, no labels, no watermark.
```

**ref-diver.png**
```text
Character reference sheet: front, side and back views side by side at the same scale. Diver: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, a black wetsuit, round diving mask and a small air tank on the back. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Plain transparent background. No text, no labels, no watermark.
```

**ref-teacher.png**
```text
Character reference sheet: front, side and back views side by side at the same scale. Teacher: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, hair tied in a bun, a light-blue cardigan and a long skirt. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Plain transparent background. No text, no labels, no watermark.
```

**ref-kids.png**
```text
Character reference sheet: front, side and back views side by side at the same scale. A small group of four child stick figures with round white heads, black dot eyes and thin black limbs, wearing matching yellow caps and backpacks. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Plain transparent background. No text, no labels, no watermark.
```

**ref-shadow.png**
```text
Character reference sheet: front, side and back views side by side at the same scale. A completely dark silhouette of a stick figure person in a hooded coat, face not visible, neutral gender. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Plain transparent background. No text, no labels, no watermark.
```

## 2.2 Tư thế (PNG nền trong suốt)

### zeke (đính kèm `ref-zeke.png`)

**zeke-lever.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and thin black stick limbs. Pose: pulling down a tall lever with both hands. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**zeke-explain.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and thin black stick limbs. Pose: raising one finger as if explaining a rule. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**zeke-worried.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and thin black stick limbs. Pose: standing with sweat drops, looking left and right nervously. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**zeke-hands-up.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and thin black stick limbs. Pose: both hands raised, squinting as if in a bright spotlight. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**zeke-look-hand.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and thin black stick limbs. Pose: staring at his own open hand, worried. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**zeke-chalk.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and thin black stick limbs. Pose: holding a piece of chalk, pointing at something to the side. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**zeke-flowers.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and thin black stick limbs. Pose: crouching and placing a small bouquet of flowers. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**zeke-throw.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and thin black stick limbs. Pose: throwing a small grey box far away with one arm. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**zeke-raise-hand.png**
```text
Keep exactly the same character design as the attached reference. Zeke: a minimalist stick figure with a hollow round white head and two black dot eyes, a bright red beanie (smooth rounded knit, no pom-pom), a yellow t-shirt, black shorts and thin black stick limbs. Pose: facing the viewer, one hand half-raised hesitantly. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

### joker (đính kèm `ref-joker.png`)

**joker-arms-wide.png**
```text
Keep exactly the same character design as the attached reference. Joker-inspired villain: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs; pale white face with dark smudged rings around the eyes, a wide red painted smile drawn around the mouth, messy shoulder-length green hair, a long purple coat over a green vest, purple trousers. Suggestive cartoon design, not a copy of any film costume. Pose: arms spread wide theatrically, grinning. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**joker-laugh.png**
```text
Keep exactly the same character design as the attached reference. Joker-inspired villain: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs; pale white face with dark smudged rings around the eyes, a wide red painted smile drawn around the mouth, messy shoulder-length green hair, a long purple coat over a green vest, purple trousers. Suggestive cartoon design, not a copy of any film costume. Pose: head thrown back, laughing. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**joker-sit.png**
```text
Keep exactly the same character design as the attached reference. Joker-inspired villain: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs; pale white face with dark smudged rings around the eyes, a wide red painted smile drawn around the mouth, messy shoulder-length green hair, a long purple coat over a green vest, purple trousers. Suggestive cartoon design, not a copy of any film costume. Pose: sitting on a bench with legs crossed, smug smile. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**joker-chess.png**
```text
Keep exactly the same character design as the attached reference. Joker-inspired villain: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs; pale white face with dark smudged rings around the eyes, a wide red painted smile drawn around the mouth, messy shoulder-length green hair, a long purple coat over a green vest, purple trousers. Suggestive cartoon design, not a copy of any film costume. Pose: holding a chess piece above a board, sly grin. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**joker-frown.png**
```text
Keep exactly the same character design as the attached reference. Joker-inspired villain: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs; pale white face with dark smudged rings around the eyes, a wide red painted smile drawn around the mouth, messy shoulder-length green hair, a long purple coat over a green vest, purple trousers. Suggestive cartoon design, not a copy of any film costume. Pose: frowning and annoyed, arms crossed. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**joker-point.png**
```text
Keep exactly the same character design as the attached reference. Joker-inspired villain: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs; pale white face with dark smudged rings around the eyes, a wide red painted smile drawn around the mouth, messy shoulder-length green hair, a long purple coat over a green vest, purple trousers. Suggestive cartoon design, not a copy of any film costume. Pose: pointing accusingly forward. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**joker-radio.png**
```text
Keep exactly the same character design as the attached reference. Joker-inspired villain: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs; pale white face with dark smudged rings around the eyes, a wide red painted smile drawn around the mouth, messy shoulder-length green hair, a long purple coat over a green vest, purple trousers. Suggestive cartoon design, not a copy of any film costume. Pose: sitting still and listening intently, no smile. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

### batman (đính kèm `ref-batman.png`)

**batman-run.png**
```text
Keep exactly the same character design as the attached reference. Masked vigilante: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, wearing a plain dark-grey bodysuit, a black cowl covering the head with two short pointed ears (only the white lower face visible), a long black cape and a plain grey utility belt. No chest emblem. Pose: running in side view facing right, cape flowing. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**batman-watch.png**
```text
Keep exactly the same character design as the attached reference. Masked vigilante: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, wearing a plain dark-grey bodysuit, a black cowl covering the head with two short pointed ears (only the white lower face visible), a long black cape and a plain grey utility belt. No chest emblem. Pose: crouching on a ledge, watching, cape draped. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

### gordon (đính kèm `ref-gordon.png`)

**gordon-desk.png**
```text
Keep exactly the same character design as the attached reference. Police commissioner: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, middle-aged, thick grey-brown mustache, round glasses, a tan trench coat over a white shirt and brown tie. Pose: sitting at a desk, looking down at something. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**gordon-glasses-off.png**
```text
Keep exactly the same character design as the attached reference. Police commissioner: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, middle-aged, thick grey-brown mustache, round glasses, a tan trench coat over a white shirt and brown tie. Pose: taking off his glasses with a thoughtful expression. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**gordon-press.png**
```text
Keep exactly the same character design as the attached reference. Police commissioner: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, middle-aged, thick grey-brown mustache, round glasses, a tan trench coat over a white shirt and brown tie. Pose: standing and holding up a small grey box toward the viewer. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

### suit (đính kèm `ref-suit.png`)

**suit-hold-box.png**
```text
Keep exactly the same character design as the attached reference. Businessman passenger: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, neatly combed dark hair, a dark-blue suit and tie. Pose: holding a small grey box with a switch, hand trembling, sweating. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**suit-put-down.png**
```text
Keep exactly the same character design as the attached reference. Businessman passenger: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, neatly combed dark hair, a dark-blue suit and tie. Pose: setting the box down, head bowed. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**suit-face-hands.png**
```text
Keep exactly the same character design as the attached reference. Businessman passenger: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, neatly combed dark hair, a dark-blue suit and tie. Pose: sitting with his face in his hands. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

### inmate (đính kèm `ref-inmate.png`)

**inmate-walk.png**
```text
Keep exactly the same character design as the attached reference. Big inmate: a very large, tall, broad-shouldered version of a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, shaved head, an orange prison jumpsuit, calm serious expression. Pose: walking forward calmly in side view facing left. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**inmate-throw.png**
```text
Keep exactly the same character design as the attached reference. Big inmate: a very large, tall, broad-shouldered version of a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, shaved head, an orange prison jumpsuit, calm serious expression. Pose: throwing a small grey box with one arm toward the side. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**inmate-sit.png**
```text
Keep exactly the same character design as the attached reference. Big inmate: a very large, tall, broad-shouldered version of a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, shaved head, an orange prison jumpsuit, calm serious expression. Pose: sitting on a bench with arms crossed. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

### warden (đính kèm `ref-warden.png`)

**warden-hold-box.png**
```text
Keep exactly the same character design as the attached reference. Prison warden: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, a dark-blue uniform with a peaked cap. Pose: holding a small grey box nervously. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

### civilian (đính kèm `ref-civilian.png`)

**civilian-shout.png**
```text
Keep exactly the same character design as the attached reference. Ferry passenger (crowd member): a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, short brown hair, a muted green jacket and grey trousers. (For variety, also make a version with a ponytail and a muted red coat.) Pose: shouting with arms raised. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**civilian-raise-hand.png**
```text
Keep exactly the same character design as the attached reference. Ferry passenger (crowd member): a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, short brown hair, a muted green jacket and grey trousers. (For variety, also make a version with a ponytail and a muted red coat.) Pose: raising one hand as if voting. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**civilian-scared.png**
```text
Keep exactly the same character design as the attached reference. Ferry passenger (crowd member): a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, short brown hair, a muted green jacket and grey trousers. (For variety, also make a version with a ponytail and a muted red coat.) Pose: standing tense and scared. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**civilian-walk.png**
```text
Keep exactly the same character design as the attached reference. Ferry passenger (crowd member): a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, short brown hair, a muted green jacket and grey trousers. (For variety, also make a version with a ponytail and a muted red coat.) Pose: walking in side view, head down. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**civilian-tv.png**
```text
Keep exactly the same character design as the attached reference. Ferry passenger (crowd member): a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, short brown hair, a muted green jacket and grey trousers. (For variety, also make a version with a ponytail and a muted red coat.) Pose: sitting on a sofa watching something, sad. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**civilian-listen.png**
```text
Keep exactly the same character design as the attached reference. Ferry passenger (crowd member): a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, short brown hair, a muted green jacket and grey trousers. (For variety, also make a version with a ponytail and a muted red coat.) Pose: sitting cross-legged and listening calmly. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**civilian-whisper.png**
```text
Keep exactly the same character design as the attached reference. Ferry passenger (crowd member): a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, short brown hair, a muted green jacket and grey trousers. (For variety, also make a version with a ponytail and a muted red coat.) Pose: leaning to the side, whispering behind a hand. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**civilian-hold-button.png**
```text
Keep exactly the same character design as the attached reference. Ferry passenger (crowd member): a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, short brown hair, a muted green jacket and grey trousers. (For variety, also make a version with a ponytail and a muted red coat.) Pose: holding a small grey box, glancing suspiciously sideways. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

### prisoner (đính kèm `ref-prisoner.png`)

**prisoner-sit.png**
```text
Keep exactly the same character design as the attached reference. Prisoner (crowd member): a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, short dark hair, an orange prison jumpsuit. Pose: sitting on a bench, looking down. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

### diver (đính kèm `ref-diver.png`)

**diver-light.png**
```text
Keep exactly the same character design as the attached reference. Diver: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, a black wetsuit, round diving mask and a small air tank on the back. Pose: swimming in side view holding a flashlight. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

**diver-lift.png**
```text
Keep exactly the same character design as the attached reference. Diver: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, a black wetsuit, round diving mask and a small air tank on the back. Pose: holding up a small muddy grey box. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

### teacher (đính kèm `ref-teacher.png`)

**teacher-models.png**
```text
Keep exactly the same character design as the attached reference. Teacher: a minimalist stick figure with a round white head, black dot eyes and thin black stick arms and legs, hair tied in a bun, a light-blue cardigan and a long skirt. Pose: holding two small toy ferry models, explaining. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

### kids (đính kèm `ref-kids.png`)

**kids-group.png**
```text
Keep exactly the same character design as the attached reference. A small group of four child stick figures with round white heads, black dot eyes and thin black limbs, wearing matching yellow caps and backpacks. Pose: standing together and listening, one child raising a hand. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

### shadow (đính kèm `ref-shadow.png`)

**shadow-door.png**
```text
Keep exactly the same character design as the attached reference. A completely dark silhouette of a stick figure person in a hooded coat, face not visible, neutral gender. Pose: pushing open a door, seen from behind. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Full body, isolated on a transparent background, no ground shadow, no scenery, centered with margin. No text, no letters, no watermark.
```

## 2.3 Đạo cụ (PNG nền trong suốt)

**prop-ferry-civ.png**
```text
a white passenger ferry in side view with warm yellow lit windows. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-ferry-prison.png**
```text
a white passenger ferry in side view with lit windows and small orange figures visible inside. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-ferry-dark.png**
```text
the same white ferry in side view with all lights off, dim and grey in fog. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-detonator.png**
```text
a small grey handheld box with one switch under a flip-up safety cover, no writing. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-hand-reach.png**
```text
a single stick-figure hand (solid black stroke arm ending in a simple round hand) reaching toward the switch of a small grey box. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-chain.png**
```text
a heavy loop of dark chain. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-explosive-icon.png**
```text
a simple flat icon of a crate with a warning lightning symbol, no writing. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-clock.png**
```text
a round wall clock with hands near twelve and only tick marks, no numbers. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-lever.png**
```text
a tall wooden post with a big lever and a glowing brass handle. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-ballot-box.png**
```text
a wooden ballot box with paper slips flying in. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-giant-buttons.png**
```text
two giant red push buttons on pedestals. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-smile-icon.png**
```text
a crude red painted smiley face graffiti shape, no writing. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-chessboard.png**
```text
a small chessboard with a few pieces. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-broken-mirror.png**
```text
a cracked mirror with sharp shards. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-padlock.png**
```text
a heavy padlock snapping shut. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-camera-pole.png**
```text
a street pole with three security cameras. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-barrier.png**
```text
a striped road checkpoint barrier. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-dilemma-grid.png**
```text
a 2x2 grid of four icons: handshake, broken handshake, broken handshake, two crossed red buttons; no writing. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-heart-city.png**
```text
a glowing heart shape containing a tiny city skyline. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-poster-hope.png**
```text
a torn wall poster showing only a bright sunrise drawing, no writing. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-monster-mask.png**
```text
a scary cartoon monster mask falling, cracked. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-envelope.png**
```text
a stack of white envelopes with red hearts, no writing. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-radio.png**
```text
an old small brown radio. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-scale.png**
```text
a balance scale with two pans. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-bird.png**
```text
a white bird flying upward. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

**prop-phone-chat.png**
```text
a smartphone screen showing chat bubbles filled with only angry emoji-style icons, no writing. Minimalist 2D vector cartoon, simple clean black outlines, flat colors with a slightly dark cinematic mood, minimal black dot eyes with simple brow lines for expression, smooth shapes, no realistic texture, no logos or emblems. Isolated on a transparent background. No text, no letters, no numbers, no watermark.
```

## 2.4 Ảnh nền

**bg-harbor-night.png**
```text
A foggy city harbor at night with dark water, distant city skyline lights, and a long pier on the side. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-harbor-map.png**
```text
A stylized top-down cartoon map of a harbor at night in dark blue tones, simple water ripples. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-gotham-night.png**
```text
A dark gothic city skyline at night with tall towers, lit windows and low clouds. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-rooftop-night.png**
```text
A city rooftop at night with a ledge, water tower and glowing skyline behind. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-book-page.png**
```text
An open storybook with blank pale pages filling the frame, warm lamp light. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-cabin-civ.png**
```text
Inside a ferry passenger cabin at night: rows of benches, round windows, fluorescent lights, tense mood. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-cabin-prison.png**
```text
Inside a ferry cabin at night with metal benches and barred windows, harsh light. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-void-dark.png**
```text
A dark moody empty stage with a single soft spotlight from above and subtle fog. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-chalkboard.png**
```text
A big dark-green chalkboard wall in a simple classroom, blank board. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-underwater.png**
```text
Murky green underwater harbor floor with mud, small rocks and faint light rays from above. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-gotham-morning.png**
```text
A gothic city skyline at early morning under a flat grey overcast sky. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-city-street.png**
```text
A grey city street at daytime with closed shop fronts, lamp posts and sidewalks. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-cell.png**
```text
A plain prison cell with a bench, a small barred window and cold light. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-ferry-terminal.png**
```text
An empty ferry terminal waiting hall with rows of empty seats and large windows facing the water. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-city-snow.png**
```text
A city street at dusk with light snow falling, cold blue tones. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-gordon-office.png**
```text
A small police office at night with a desk, a warm desk lamp and window blinds. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-press-room.png**
```text
A press conference room with a podium (no logo) and blurred camera flashes. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-living-room.png**
```text
A cozy living room at night with a sofa and a glowing TV screen showing nothing readable. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-city-street-day.png**
```text
A brighter city street on a sunny morning with trees and open shops. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-visiting-room.png**
```text
A prison visiting room with tables and chairs and warm daylight. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-harbor-memorial.png**
```text
A sunny harbor promenade with a simple stone memorial shaped like a small box with a switch, flowers at its base, a ferry docked behind. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-police-door.png**
```text
The entrance of a police station at night, a glass door with warm light inside, no signs. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-office.png**
```text
A modern open-plan office with desks and computers, daytime. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

**bg-harbor-aerial.png**
```text
A high aerial view of the harbor at night with two lit ferries on dark water and the city skyline. Wide 16:9 landscape background, NO people or characters, rich full-color 2D cartoon environment with cinematic volumetric light and soft depth of field, minimalist vector style with clean outlines. Leave open space in the lower center for characters. No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

---

# 3. Kịch bản 3 phần

**Quy tắc nhịp nhanh:** mỗi cảnh 3–6 giây, hình thay đổi mỗi 2–3 giây. Cắt cảnh theo nhịp nhạc, có tiếng "hit" ở câu chốt. Chữ trên hình 2–4 từ, giữ khoảng 1,5 giây. Ở các khoảnh khắc lớn để im lặng 1 nhịp. 3 giây đầu mỗi phần phải có chuyển động mạnh. Mỗi phần kết bằng thẻ 3–5 giây.

## Phần 1: The Button (Nút bấm)

| # | Lời đọc | Ảnh sử dụng | Chuyển động | Chữ trên hình |
|---|---|---|---|---|
| 1 | Two ferries. Two bombs. One deal from the Joker. | bg-harbor-night · prop-ferry-civ · prop-ferry-prison | Đêm, cảng sương mù, 2 phà sáng đèn · zoom nhanh | JOKER'S BET |
| 2 | And tonight, someone actually pushes the button. | bg-void-dark · prop-hand-reach · prop-detonator | Cận ngón tay lơ lửng trên công tắc · nhịp trống dội |  |
| 3 | In The Dark Knight, the Joker had one goal: prove that scared people become monsters. | bg-gotham-night · joker-arms-wide · civilian-walk | Joker xòe tay cười · bóng người thường kéo dài thành bóng quái vật |  |
| 4 | So he trapped two ferries in Gotham Harbor. | bg-harbor-map · prop-ferry-civ · prop-ferry-prison · prop-chain | 2 phà trên bản đồ cảng, xích trói xuất hiện |  |
| 5 | One full of ordinary citizens. One full of prisoners. | bg-harbor-map · civilian-scared ×3 · prisoner-sit ×3 | Phà trái bật lên người thường · phà phải bật lên áo tù cam |  |
| 6 | Both packed with explosives. Each holding the detonator for the other boat. | bg-harbor-map · prop-explosive-icon · prop-detonator ×2 | Thùng thuốc nổ (biểu tượng) dưới hầm · mũi tên chéo giữa 2 kíp nổ |  |
| 7 | The rule was simple. Blow up the other ferry, and you live. | bg-chalkboard · zeke-explain · prop-ferry-prison | Zeke giơ 1 ngón tay, phà kia nhấp nháy đỏ |  |
| 8 | If nobody presses by midnight, the Joker destroys them both. | bg-harbor-night · prop-clock · 2 phà | Đồng hồ kim gần 12 · cả 2 phà nhấp nháy |  |
| 9 | Batman is racing across the city to find him. The clock keeps ticking. | bg-rooftop-night · batman-run · prop-clock | Batman lướt qua mái nhà, áo choàng bay · đồng hồ tích tắc |  |
| 10 | In the movie, nobody pressed it. Gotham proved him wrong. | bg-book-page · inmate-throw · joker-frown | Trang sách: tù nhân ném hộp · Joker nhăn mặt |  |
| 11 | But what if one hand didn't hesitate? What if the Joker won? | bg-book-page · zeke-lever · prop-lever | Zeke kéo cần gạt, trang sách lật ngược, màn hình rung | WHAT IF |
| 12 | Civilian ferry. Panic. Someone shouts: let's vote. | bg-cabin-civ · civilian-shout ×3 | Trong khoang phà · đám đông la hét · cắt nhanh 3 khuôn mặt |  |
| 13 | Most of them vote yes. Press the button. | bg-cabin-civ · prop-ballot-box · civilian-raise-hand ×5 | Phiếu bay vào thùng · rừng tay giơ lên |  |
| 14 | They're not evil. They're terrified. And the other boat is full of criminals. | bg-cabin-civ · civilian-scared · prop-ferry-prison (qua cửa sổ) | Cận mắt hoảng sợ · cửa sổ nhìn sang phà áo cam |  |
| 15 | Someone yells: why should we die for them? | bg-cabin-civ · civilian-shout | Một người que đập bàn, các người khác gật |  |
| 16 | A man in a suit picks up the detonator. His hand shakes. | bg-cabin-civ · suit-hold-box | Người vest xanh cầm hộp xám, tay run (rung nhẹ) |  |
| 17 | In the movie, he puts it down. | bg-cabin-civ · suit-put-down · prop-detonator | Hộp đặt xuống bàn, âm thanh 'cạch' |  |
| 18 | Meanwhile, on the prisoner ferry, a huge inmate walks up to the warden. | bg-cabin-prison · inmate-walk · warden-hold-box · prisoner-sit ×3 | Khoang phà tù · tù nhân to lớn bước tới quản ngục |  |
| 19 | He takes their detonator, and throws it out the window. Into the river. | bg-cabin-prison · inmate-throw · prop-detonator | Hộp bay qua cửa sổ, rơi tõm xuống nước · vòng sóng |  |
| 20 | No speech. No drama. Just a choice. | bg-cabin-prison · inmate-sit | Tù nhân ngồi xuống lại, khoanh tay |  |
| 21 | But the civilians can't see that. All they can see is the clock. | bg-cabin-civ | bg-cabin-prison (chia đôi) · prop-clock | Chia đôi màn hình · đồng hồ phóng to dần |  |
| 22 | Nobody wants to be a killer. | bg-void-dark · zeke-worried · prop-giant-buttons | Zeke đứng giữa 2 nút khổng lồ |  |
| 23 | But nobody wants to be the one who waited too long. | bg-void-dark · zeke-worried · prop-giant-buttons | Zeke nhìn qua lại, mồ hôi bay |  |
| 24 | Every second, the fear gets louder than the conscience. | bg-cabin-civ · civilian-scared (phóng cận) | Tiếng tim đập to dần · khung hình co lại |  |
| 25 | Eleven fifty-nine. | bg-void-dark · prop-clock | Cận đồng hồ, kim nhích · im lặng 1 nhịp | 11:59 |
| 26 | A hand reaches for the box. And this time, it doesn't stop. | bg-cabin-civ · prop-hand-reach | Bàn tay vươn tới · cắt đen |  |
| 27 | Across the water, the prison ferry's lights go dark. | bg-harbor-night · prop-ferry-prison → prop-ferry-dark | Đèn phà phải tắt dần trong sương (không nổ, không lửa) |  |
| 28 | No fire. No sound. Just darkness where a boat used to be. | bg-harbor-night (trống) | Mặt nước trống, sương trôi |  |
| 29 | The harbor goes silent. Somewhere in Gotham, the Joker starts to laugh. | bg-gotham-night · joker-laugh | Joker ngửa cổ cười · bóng hắn phủ lên thành phố |  |
| 30 | He thinks he just won. But the river is hiding something. Part two is next. | bg-underwater · prop-detonator | Camera lặn xuống nước, thấy bóng chiếc hộp trong bùn · thẻ kết | PART 2 → |

**Lời đọc gộp sẵn:**
```text
Two ferries. Two bombs. One deal from the Joker.
And tonight, someone actually pushes the button.
In The Dark Knight, the Joker had one goal: prove that scared people become monsters.
So he trapped two ferries in Gotham Harbor.
One full of ordinary citizens. One full of prisoners.
Both packed with explosives. Each holding the detonator for the other boat.
The rule was simple. Blow up the other ferry, and you live.
If nobody presses by midnight, the Joker destroys them both.
Batman is racing across the city to find him. The clock keeps ticking.
In the movie, nobody pressed it. Gotham proved him wrong.
But what if one hand didn't hesitate? What if the Joker won?
Civilian ferry. Panic. Someone shouts: let's vote.
Most of them vote yes. Press the button.
They're not evil. They're terrified. And the other boat is full of criminals.
Someone yells: why should we die for them?
A man in a suit picks up the detonator. His hand shakes.
In the movie, he puts it down.
Meanwhile, on the prisoner ferry, a huge inmate walks up to the warden.
He takes their detonator, and throws it out the window. Into the river.
No speech. No drama. Just a choice.
But the civilians can't see that. All they can see is the clock.
Nobody wants to be a killer.
But nobody wants to be the one who waited too long.
Every second, the fear gets louder than the conscience.
Eleven fifty-nine.
A hand reaches for the box. And this time, it doesn't stop.
Across the water, the prison ferry's lights go dark.
No fire. No sound. Just darkness where a boat used to be.
The harbor goes silent. Somewhere in Gotham, the Joker starts to laugh.
He thinks he just won. But the river is hiding something. Part two is next.
```

## Phần 2: Joker's City (Thành phố của Joker)

| # | Lời đọc | Ảnh sử dụng | Chuyển động | Chữ trên hình |
|---|---|---|---|---|
| 1 | Previously: the Joker's ferry bet. Someone pressed the button. | bg-harbor-night · 2 phà · prop-hand-reach · prop-ferry-dark | Tua nhanh 3 hình: 2 phà, bàn tay, đèn tắt | PREVIOUSLY |
| 2 | Now Gotham wakes up, and nothing feels the same. | bg-gotham-morning | Bình minh xám trên Gotham |  |
| 3 | Morning. Grey sky. Quiet streets. | bg-city-street | Lia nhanh qua phố vắng |  |
| 4 | Nobody knows exactly who pressed the button. | bg-city-street · civilian-walk ×4 | Đám đông bước, đầu cúi |  |
| 5 | But everyone knows someone did. | bg-city-street · civilian-walk ×2 | Mỗi người que liếc nhau |  |
| 6 | Batman caught the Joker that night. It doesn't feel like a win. | bg-rooftop-night · batman-watch | Batman trên mái, vai trĩu |  |
| 7 | Because the Joker already got what he wanted. | bg-cell · joker-sit | Joker trong xà lim, vắt chân |  |
| 8 | From his cell, he doesn't need bombs anymore. His message is out there: | bg-gotham-morning · prop-smile-icon ×4 | Mặt cười lan ra các màn hình thành phố |  |
| 9 | You're no better than me. | bg-cell · joker-laugh (phóng cận) | Cận nụ cười Joker · nhạc dội | NO BETTER THAN ME |
| 10 | The passengers go home. They don't talk about the vote. | bg-ferry-terminal · civilian-walk ×3 | Hành khách rời bến, quay lưng nhau |  |
| 11 | They don't look each other in the eye. | bg-city-street · civilian-walk ×2 | Hai người que đi ngang, cùng nhìn xuống |  |
| 12 | And every single one of them asks the same question: did I raise my hand? | bg-void-dark · zeke-look-hand | Zeke nhìn bàn tay mình · bóng tay giơ trên tường |  |
| 13 | That's the Joker's real genius. He didn't need to destroy Gotham. | bg-void-dark · joker-chess · prop-chessboard | Joker đặt quân cờ lên bàn cờ thành phố |  |
| 14 | He just needed Gotham to doubt itself. | bg-void-dark · prop-broken-mirror | Gương vỡ phản chiếu thành phố |  |
| 15 | Week one. Nobody rides the ferries. | bg-ferry-terminal | Bến phà vắng tanh | WEEK 1 |
| 16 | Neighbors lock their doors. Strangers become threats. | bg-city-street · prop-padlock ×3 · civilian-scared | Ổ khóa bật lên liên tiếp · người lạ liếc nhau |  |
| 17 | Clown faces start showing up on walls and screens. Copycats. | bg-city-street · prop-smile-icon | Hình mặt cười hiện lên tường, nhanh dần |  |
| 18 | They don't need a plan. They just need people to believe the Joker was right. | bg-city-street · civilian-scared ×3 | Đám đông xem màn hình, im lặng |  |
| 19 | The city answers with more walls. More cameras. More checkpoints. | bg-city-street · prop-camera-pole · prop-barrier | Tường, camera, rào chắn mọc theo nhịp |  |
| 20 | Everyone is watched. Nobody feels safer. | bg-city-street · zeke-hands-up | Zeke bị đèn soi, giơ tay |  |
| 21 | Here's the thing about fear. It doesn't just make you act badly. | bg-chalkboard · zeke-chalk | Zeke cầm phấn trước bảng đen |  |
| 22 | It convinces you that everyone else will act worse. | bg-chalkboard · zeke-chalk · civilian-scared ×2 | Vẽ 2 người que, bong bóng nghĩ đầu kia là quái vật |  |
| 23 | There's a name for this trap: the prisoner's dilemma. | bg-chalkboard · prop-dilemma-grid | Bảng 2×2 biểu tượng bật lên | PRISONER'S DILEMMA |
| 24 | Two sides. Neither can trust the other. So betrayal starts to look logical. | bg-chalkboard · prop-dilemma-grid · zeke-chalk | Mũi tên trỏ vào ô 'cả hai phản bội' |  |
| 25 | The Joker built the ferries as a perfect prisoner's dilemma. | bg-harbor-map · prop-ferry-civ · prop-ferry-prison | Bảng 2×2 biến thành 2 phà |  |
| 26 | And the prize was the soul of the city. | bg-void-dark · joker-chess · prop-heart-city | Joker cầm trái tim thành phố (biểu tượng) như quân cờ |  |
| 27 | Gotham's hero, Harvey Dent, once promised a city that could trust itself. Now that promise sounds like a joke. | bg-city-street · prop-poster-hope | Áp phích hy vọng (không chữ) bị gió xé |  |
| 28 | Month three. Gotham is still standing. | bg-city-snow | Tuyết rơi trên thành phố | MONTH 3 |
| 29 | But it's colder. Quieter. Like everyone carries an invisible detonator in their pocket. | bg-city-snow · civilian-walk ×3 (túi áo phát sáng) | Túi áo người qua đường phát sáng hình hộp |  |
| 30 | The Joker sits in his cell, smiling. He thinks the story is over. | bg-cell · joker-sit | Joker cười, camera lùi |  |
| 31 | Month four. A diver is clearing the harbor, right where the prison ferry was anchored. | bg-underwater · diver-light | Dưới nước, thợ lặn rọi đèn | MONTH 4 |
| 32 | His light hits something in the mud. A small grey box. | bg-underwater · diver-light · prop-detonator | Đèn chiếu trúng hộp xám · zoom gấp |  |
| 33 | And it changes everything. Part three is next. | bg-underwater · prop-detonator | Thẻ kết | PART 3 → |

**Lời đọc gộp sẵn:**
```text
Previously: the Joker's ferry bet. Someone pressed the button.
Now Gotham wakes up, and nothing feels the same.
Morning. Grey sky. Quiet streets.
Nobody knows exactly who pressed the button.
But everyone knows someone did.
Batman caught the Joker that night. It doesn't feel like a win.
Because the Joker already got what he wanted.
From his cell, he doesn't need bombs anymore. His message is out there:
You're no better than me.
The passengers go home. They don't talk about the vote.
They don't look each other in the eye.
And every single one of them asks the same question: did I raise my hand?
That's the Joker's real genius. He didn't need to destroy Gotham.
He just needed Gotham to doubt itself.
Week one. Nobody rides the ferries.
Neighbors lock their doors. Strangers become threats.
Clown faces start showing up on walls and screens. Copycats.
They don't need a plan. They just need people to believe the Joker was right.
The city answers with more walls. More cameras. More checkpoints.
Everyone is watched. Nobody feels safer.
Here's the thing about fear. It doesn't just make you act badly.
It convinces you that everyone else will act worse.
There's a name for this trap: the prisoner's dilemma.
Two sides. Neither can trust the other. So betrayal starts to look logical.
The Joker built the ferries as a perfect prisoner's dilemma.
And the prize was the soul of the city.
Gotham's hero, Harvey Dent, once promised a city that could trust itself. Now that promise sounds like a joke.
Month three. Gotham is still standing.
But it's colder. Quieter. Like everyone carries an invisible detonator in their pocket.
The Joker sits in his cell, smiling. He thinks the story is over.
Month four. A diver is clearing the harbor, right where the prison ferry was anchored.
His light hits something in the mud. A small grey box.
And it changes everything. Part three is next.
```

## Phần 3: The Box in the River (Chiếc hộp dưới sông)

| # | Lời đọc | Ảnh sử dụng | Chuyển động | Chữ trên hình |
|---|---|---|---|---|
| 1 | Previously: someone pressed the button, and the Joker broke Gotham's trust. | bg-void-dark · prop-hand-reach · prop-padlock · prop-smile-icon | Tua nhanh: bàn tay, ổ khóa, mặt cười | PREVIOUSLY |
| 2 | But a diver just found something in the river. | bg-underwater · diver-lift | Thợ lặn nhấc hộp khỏi bùn |  |
| 3 | A small grey box. One switch. | bg-void-dark · prop-detonator | Cận hộp xoay chậm |  |
| 4 | The second detonator. The one meant for the civilians. | bg-harbor-map · prop-detonator · prop-ferry-civ | Mũi tên từ hộp chỉ về phà dân thường |  |
| 5 | The switch has never been pressed. The safety is still on. | bg-void-dark · prop-detonator (phóng cận) | Cận nắp an toàn đóng |  |
| 6 | It hit the water before midnight. | bg-harbor-night · prop-detonator · prop-clock | Tua lại: hộp rơi xuống nước, đồng hồ chưa tới 12 |  |
| 7 | Commissioner Gordon stares at it for a long time. | bg-gordon-office · gordon-desk · prop-detonator | Gordon, hộp trên bàn, đèn vàng |  |
| 8 | Then he understands. | bg-gordon-office · gordon-glasses-off | Gordon tháo kính |  |
| 9 | The prisoners had the power to save themselves. | bg-cabin-prison · inmate-walk · warden-hold-box | Hồi tưởng: tù nhân cầm hộp |  |
| 10 | They chose not to use it. | bg-cabin-prison · inmate-throw | Ném qua cửa sổ |  |
| 11 | They gave the civilians their lives. | bg-harbor-night · prop-ferry-civ | Phà dân thường sáng đèn ấm |  |
| 12 | Gordon walks out in front of the cameras, and tells Gotham the truth. | bg-press-room · gordon-press | Họp báo, đèn flash dồn dập |  |
| 13 | The people we called monsters were the ones who chose mercy. | bg-void-dark · prop-monster-mask · inmate-sit | Mặt nạ quái vật rơi khỏi bóng tù nhân | THEY CHOSE MERCY |
| 14 | The city goes silent again. But this time, it isn't fear. | bg-living-room · civilian-tv | Người que xem TV trong nhà |  |
| 15 | It's shame. And shame can change people. | bg-gotham-night (đèn cửa sổ bật dần) | Đèn cửa sổ bật sáng dần |  |
| 16 | The Joker hears the news on a radio in his cell. | bg-cell · joker-radio · prop-radio | Joker bên radio |  |
| 17 | And for the first time, he isn't laughing. | bg-cell · joker-radio (phóng cận) | Nụ cười tắt · nhạc dừng 1 nhịp |  |
| 18 | Here's the twist. The Joker won the bet. | bg-void-dark · prop-scale · prop-hand-reach | Cán cân: nút bấm bên trái | THE TWIST |
| 19 | But he lost the argument. | bg-void-dark · prop-scale · prop-detonator | Hộp chưa bấm bên phải nặng xuống |  |
| 20 | His experiment was supposed to prove everyone is a monster. | bg-void-dark · joker-point · civilian-scared ×3 | Joker chỉ vào đám đông |  |
| 21 | Instead, it proved monsters aren't always who we think. | bg-void-dark · civilian-scared ×3 · inmate-sit | Đám đông quay sang nhìn tù nhân, ánh mắt đổi |  |
| 22 | Year one. Gotham starts doing things that sounded crazy before. | bg-city-street-day | Thành phố nắng sáng hơn | YEAR 1 |
| 23 | People visit the prison. They write letters. | bg-visiting-room · prop-envelope · civilian-walk | Phong bì bay qua song sắt |  |
| 24 | Ferry passengers build a memorial on the harbor. No clown face. Just an empty box and a switch. | bg-harbor-memorial | Đài tưởng niệm hình hộp và công tắc · hoa |  |
| 25 | And the person who pressed the button? One night, they walk into a police station. | bg-police-door · shadow-door | Bóng người không rõ mặt đẩy cửa đồn |  |
| 26 | Three words: it was me. | bg-police-door · shadow-door | Đặt tay lên bàn · im lặng |  |
| 27 | No one cheers. But for the first time, Gotham listens. | bg-living-room · civilian-listen ×5 | Người que ngồi vòng tròn lắng nghe |  |
| 28 | Batman watches from a rooftop. He couldn't stop the bet. But the city found its own answer. | bg-rooftop-night · batman-watch | Batman trên mái, thành phố đèn ấm |  |
| 29 | Ten years later, kids on a school trip ride the ferry and ask what happened. | bg-harbor-memorial · kids-group · teacher-models | Học sinh mũ vàng trên phà nắng | 10 YEARS LATER |
| 30 | Their teacher tells them about two boats, two buttons, one choice made in fear, and one made in mercy. | bg-harbor-memorial · teacher-models | Cô giáo cầm 2 phà mô hình |  |
| 31 | The Joker wanted to be remembered. Instead, Gotham remembers the man who threw a detonator into the river. | bg-harbor-memorial · zeke-flowers | Tượng tù nhân ném hộp · Zeke đặt hoa |  |
| 32 | So what's the lesson? Fear makes good people do terrible things. | bg-chalkboard · zeke-chalk | Zeke trước bảng đen: sợ → hành động xấu |  |
| 33 | But one act of trust can break the spell. | bg-chalkboard · zeke-chalk · prop-chain | Vẽ: tin tưởng → xích đứt |  |
| 34 | We face little ferries every day. A rumor about a coworker. A group chat turning on someone. | bg-office · civilian-whisper ×2 · prop-phone-chat | Văn phòng, người que thì thầm · điện thoại bong bóng chat (biểu tượng) |  |
| 35 | We assume they'll press first, so we press ours. We call it self-defense. | bg-office · civilian-hold-button ×2 | 2 người que cầm nút, liếc nhau |  |
| 36 | The braver move is to throw the detonator away, without knowing what the other boat will do. | bg-void-dark · zeke-throw · prop-detonator · prop-bird | Zeke ném hộp, nó hóa thành con chim bay |  |
| 37 | That isn't weakness. It's the one thing the Joker never saw coming. | bg-void-dark · joker-frown · prop-chessboard | Joker nhìn bàn cờ đổ |  |
| 38 | So be honest: if you were on that ferry, would you have raised your hand? | bg-void-dark · zeke-raise-hand | Zeke nhìn thẳng máy quay, tay giơ lửng | WOULD YOU? |
| 39 | Tell me in the comments. And tell me which villain should win next. | bg-harbor-aerial | Kéo lên toàn cảnh cảng đêm, 2 phà sáng đèn · thẻ kết |  |

**Lời đọc gộp sẵn:**
```text
Previously: someone pressed the button, and the Joker broke Gotham's trust.
But a diver just found something in the river.
A small grey box. One switch.
The second detonator. The one meant for the civilians.
The switch has never been pressed. The safety is still on.
It hit the water before midnight.
Commissioner Gordon stares at it for a long time.
Then he understands.
The prisoners had the power to save themselves.
They chose not to use it.
They gave the civilians their lives.
Gordon walks out in front of the cameras, and tells Gotham the truth.
The people we called monsters were the ones who chose mercy.
The city goes silent again. But this time, it isn't fear.
It's shame. And shame can change people.
The Joker hears the news on a radio in his cell.
And for the first time, he isn't laughing.
Here's the twist. The Joker won the bet.
But he lost the argument.
His experiment was supposed to prove everyone is a monster.
Instead, it proved monsters aren't always who we think.
Year one. Gotham starts doing things that sounded crazy before.
People visit the prison. They write letters.
Ferry passengers build a memorial on the harbor. No clown face. Just an empty box and a switch.
And the person who pressed the button? One night, they walk into a police station.
Three words: it was me.
No one cheers. But for the first time, Gotham listens.
Batman watches from a rooftop. He couldn't stop the bet. But the city found its own answer.
Ten years later, kids on a school trip ride the ferry and ask what happened.
Their teacher tells them about two boats, two buttons, one choice made in fear, and one made in mercy.
The Joker wanted to be remembered. Instead, Gotham remembers the man who threw a detonator into the river.
So what's the lesson? Fear makes good people do terrible things.
But one act of trust can break the spell.
We face little ferries every day. A rumor about a coworker. A group chat turning on someone.
We assume they'll press first, so we press ours. We call it self-defense.
The braver move is to throw the detonator away, without knowing what the other boat will do.
That isn't weakness. It's the one thing the Joker never saw coming.
So be honest: if you were on that ferry, would you have raised your hand?
Tell me in the comments. And tell me which villain should win next.
```

---

# 4. Âm thanh

| Phần | Gợi ý |
|---|---|
| **Giọng đọc** | Nam trưởng thành, giọng Mỹ, baritone ấm. **Đọc nhanh và dứt khoát**, khoảng 150–155 từ/phút. Mỗi phần một file, xuống dòng giữa các câu để có khoảng ngắt ngắn. |
| **Nhạc nền** | Nhạc không lời có bản quyền, ví dụ từ YouTube Audio Library: phần 1 dùng nhạc căng thẳng, nhịp tim, synth trầm. Phần 2 dùng nhạc lạnh, ambient tối. Phần 3 bắt đầu tối rồi chuyển sang piano và dây ấm áp. **Không dùng nhạc phim gốc.** |
| **Hiệu ứng âm thanh** | Pixabay, Freesound (kiểm tra giấy phép): tích tắc, nhịp tim, whoosh, trống "hit", sóng nước, ổ khóa, đèn flash, radio rè, tiếng bút phấn, chim bay. **Không dùng tiếng nổ.** |
| **Phụ đề** | Dùng lệnh `givemotion words` trên từng file giọng đọc. |

---

# 5. Cấu trúc thư mục

```
joker-won/
├── images/ref/  images/chars/  images/props/  images/bg/
├── audio/
│   ├── voiceover-p1.mp3  voiceover-p2.mp3  voiceover-p3.mp3
│   ├── music-p1.mp3  music-p2.mp3  music-p3.mp3
│   └── sfx/
└── script.md   ← file này
```

---

# 6. Bản giao việc cho agent Givemotion
Dán đoạn dưới cho **từng phần**, thay `N` bằng 1, 2 hoặc 3.

```text
Build Part N of a 3-part 16:9, 1080p, 30fps video with givemotion from this folder.
- Read script.md: section 1 (characters), section 3 "Phần N" table (narration line, assets, motion, overlay text).
- audio/voiceover-pN.mp3 is the master timeline. Run `givemotion words` on it and give each table row exactly the duration of its narration line (typically 3-6 s). Add a 0.5-1 s silent beat only where the motion column asks for silence.
- FAST PACING: something must visibly change every 2-3 s (punch-in zoom, quick pan, pop-in, pose swap by quick cross-fade, shake on impact lines). The first 3 s must open with strong motion, no logo intro. Use quick cuts or whip transitions between rows; no slow fades except where noted.
- Visuals: background from images/bg (cover-fit 16:9, split screen where the table says "|"); layer transparent PNGs from images/chars and images/props as listed in the "Ảnh sử dụng" column; "×3" means duplicate that layer with slight offsets and staggered entrances.
- Keep screen direction: civilian ferry on the LEFT, prison ferry on the RIGHT.
- Overlays: the "Chữ trên hình" text as bold pop-up title cards (e.g. Bebas Neue, white with dark shadow), max ~1.5 s, top-left area. Word-synced English captions at the bottom, one line.
- Audio: audio/music-pN.mp3 under the voice at ~12%, use `givemotion audio` to land cuts on beats; SFX from audio/sfx at key actions, a punchy hit on each overlay. No explosion sounds.
- End card (3-5 s): "PART N+1 →" (Part 3: comment prompt) with a subscribe button area.
- Never show explosions, fire or injury; the ferry lights simply fade out in fog.
- Run `givemotion check` and `snapshot`, fix issues, render a 20-second preview first for approval, then the full part.
```
