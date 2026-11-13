# What If Scar Won? Bộ prompt cho Google Flow

Video 16:9, dài 3 phút, gồm 18 đoạn × 10 giây, phong cách A2B (điện ảnh nhiều màu), lời đọc tiếng Anh.

---

# PHẦN 1: Prompt ảnh nhân vật (làm trước)

**Mục đích:** tạo ảnh tham chiếu để nhân vật giống nhau qua 18 đoạn video.
**Tạo ở đâu:** trong Flow (chức năng tạo ảnh) hoặc ứng dụng Gemini.
**Cách làm:**
1. Mỗi nhân vật tạo 2–4 lần, chọn **1 ảnh đẹp nhất**, đúng mô tả, nhìn rõ ba góc trước, nghiêng, sau, và không có chữ trong ảnh.
2. Đặt tên file rõ ràng: `zeke.png`, `scar.png`, `scar-old.png`, `simba.png`, `nala.png`, `lioness.png`, `hyena.png`, `cub.png`.
3. Khi tạo video, đính kèm ảnh của **những nhân vật xuất hiện trong đoạn đó** (danh sách ở mỗi prompt), nếu công cụ có hỗ trợ ảnh tham chiếu.

Ảnh tham chiếu chỉ là ảnh hỗ trợ, không dùng làm khung hình mở đầu. Ảnh giúp nhân vật ổn định hơn nhưng không đảm bảo giống 100%.

## Ảnh 1: Zeke (người que dẫn chuyện)

```text
Character reference sheet, three full-body views side by side at the same scale: front view, side profile facing left, and back view. Plain flat light-grey background, even soft lighting, no scenery. Minimalist 2D vector cartoon style with simple clean black outlines and flat vibrant colors, minimal black dot eyes, smooth shapes, no realistic texture. No text, no labels, no numbers, no watermark.

A minimalist 2D animated stick figure wearing a bright red beanie (smooth rounded knit, no pom-pom) and a yellow t-shirt, with simple black stick limbs and shorts. Simple black lines, vibrant colors, smooth 2D animation style. Hollow circular head with minimal dot eyes only; he is a silent time-travelling observer and never speaks.
```

## Ảnh 2: Scar (bình thường)

```text
Character reference sheet, three full-body views side by side at the same scale: front view, side profile facing left, and back view. Plain flat light-grey background, even soft lighting, no scenery. Minimalist 2D vector cartoon style with simple clean black outlines and flat vibrant colors, minimal black dot eyes, smooth shapes, no realistic texture. No text, no labels, no numbers, no watermark.

SCAR (villain lion): a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, minimal black dot eyes under a narrow sly brow line, and a long thin tail ending in a black tuft. Walks on four legs like a real lion, no clothing.
```

## Ảnh 3: Scar (già, 10 năm sau)

```text
Character reference sheet, three full-body views side by side at the same scale: front view, side profile facing left, and back view. Plain flat light-grey background, even soft lighting, no scenery. Minimalist 2D vector cartoon style with simple clean black outlines and flat vibrant colors, minimal black dot eyes, smooth shapes, no realistic texture. No text, no labels, no numbers, no watermark.

SCAR (villain lion): a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, minimal black dot eyes under a narrow sly brow line, and a long thin tail ending in a black tuft. Walks on four legs like a real lion, no clothing. Now old: his black mane streaked with grey and his body thinner, same scar and same face design.
```

## Ảnh 4: Simba

```text
Character reference sheet, three full-body views side by side at the same scale: front view, side profile facing left, and back view. Plain flat light-grey background, even soft lighting, no scenery. Minimalist 2D vector cartoon style with simple clean black outlines and flat vibrant colors, minimal black dot eyes, smooth shapes, no realistic texture. No text, no labels, no numbers, no watermark.

SIMBA (young hero lion): a strong young adult male lion with golden fur, a full reddish-brown mane, minimal black dot eyes under a determined brow line, and a tail ending in a reddish-brown tuft. Four legs, no clothing.
```

## Ảnh 5: Nala

```text
Character reference sheet, three full-body views side by side at the same scale: front view, side profile facing left, and back view. Plain flat light-grey background, even soft lighting, no scenery. Minimalist 2D vector cartoon style with simple clean black outlines and flat vibrant colors, minimal black dot eyes, smooth shapes, no realistic texture. No text, no labels, no numbers, no watermark.

NALA (lioness leader): a sleek adult lioness with pale cream-gold fur, a small notch cut into the tip of her left ear, minimal black dot eyes under a calm steady brow line, no mane. Four legs, no clothing.
```

## Ảnh 6: Bầy sư tử cái (1 con mẫu)

```text
Character reference sheet, three full-body views side by side at the same scale: front view, side profile facing left, and back view. Plain flat light-grey background, even soft lighting, no scenery. Minimalist 2D vector cartoon style with simple clean black outlines and flat vibrant colors, minimal black dot eyes, smooth shapes, no realistic texture. No text, no labels, no numbers, no watermark.

LIONESSES (group sample): one sleek sandy-gold lioness with minimal black dot eyes, no manes and no ear notches.
```

## Ảnh 7: Linh cẩu (1 con mẫu)

```text
Character reference sheet, three full-body views side by side at the same scale: front view, side profile facing left, and back view. Plain flat light-grey background, even soft lighting, no scenery. Minimalist 2D vector cartoon style with simple clean black outlines and flat vibrant colors, minimal black dot eyes, smooth shapes, no realistic texture. No text, no labels, no numbers, no watermark.

HYENAS (group sample): one scrawny grey hyena with black spots, sloped backs, round ears, minimal black dot eyes and wide toothy grins drawn simply.
```

## Ảnh 8: Sư tử con (1 con mẫu)

```text
Character reference sheet, three full-body views side by side at the same scale: front view, side profile facing left, and back view. Plain flat light-grey background, even soft lighting, no scenery. Minimalist 2D vector cartoon style with simple clean black outlines and flat vibrant colors, minimal black dot eyes, smooth shapes, no realistic texture. No text, no labels, no numbers, no watermark.

LION CUBS (group sample): one small round sandy-gold lion cub with minimal black dot eyes.
```

## Ảnh 9: Ảnh so tỷ lệ (tùy chọn)
Dùng để kiểm tra kích thước giữa người que và các con vật.

```text
Character lineup for scale, all standing side by side on a plain flat light-grey background, facing the viewer at three-quarter angle: A minimalist 2D animated stick figure wearing a bright red beanie (smooth rounded knit, no pom-pom) and a yellow t-shirt, with simple black stick limbs and shorts. Simple black lines, vibrant colors, smooth 2D animation style. Next to him: SCAR (villain lion): a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, minimal black dot eyes under a narrow sly brow line, and a long thin tail ending in a black tuft. Walks on four legs like a real lion, no clothing. NALA (lioness leader): a sleek adult lioness with pale cream-gold fur, a small notch cut into the tip of her left ear, minimal black dot eyes under a calm steady brow line, no mane. Four legs, no clothing. HYENAS one scrawny grey hyena with black spots, sloped backs, round ears, minimal black dot eyes and wide toothy grins drawn simply. A real lion is much larger than the stick figure: his head reaches about the lion's shoulder. Minimalist 2D vector cartoon style, simple clean black outlines, flat vibrant colors. No text, no labels, no watermark.
```

---

# PHẦN 2: 18 prompt video

Chép **toàn bộ** từng khối prompt, dán vào Flow, chọn khung 16:9. Tạo **theo thứ tự**, và **thử đoạn 1 trước** khi tạo các đoạn sau.

## Đoạn 1
**Ảnh tham chiếu cần đính kèm:** zeke.png, scar.png

```text
OUTPUT: A stickman animated video, approximately 10 seconds, 16:9 landscape, 720p target, 24 FPS, synchronized audio. Rapid scene changes and frequent visual events, while preserving an identical stick-figure design, constant line weight, and strict temporal consistency.

ENVIRONMENT: in a rich full-color cinematic environment: a vast African savanna with tall grass, flat-topped acacia trees and one towering jutting rock outcrop that serves as the king's throne. Cinematic volumetric lighting, soft depth of field, atmospheric narrative mood. Lighting and palette for this clip: Golden sunrise light, warm gold palette.

CHARACTERS:
A minimalist 2D animated stick figure wearing a bright red beanie (smooth rounded knit, no pom-pom) and a yellow t-shirt, with simple black stick limbs and shorts. Simple black lines, vibrant colors, smooth 2D animation style. Hollow circular head with minimal dot eyes only; he is a silent time-travelling observer and never speaks.
SCAR (villain lion): a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, minimal black dot eyes under a narrow sly brow line, and a long thin tail ending in a black tuft. Walks on four legs like a real lion, no clothing.
All animals share the same drawing style as the stick figure: simple clean black outlines, flat vibrant colors, minimal black dot eyes, simple brow lines for expression, smooth 2D vector animation. No realistic fur texture, no detailed irises.

COMPOSITION (16:9): stage action across left, center and right thirds. The throne rock stands at center; the green hills lie off to the right. Use lateral tracking, deliberate negative space in the upper-left area, and keep screen direction consistent: anyone leaving the kingdom moves toward the right.

FIRST FRAME: Sunrise over the savanna. The stick figure stands on a grassy hill in the left foreground, back half-turned to camera.

TIMED ACTION:
[0-3s] The stick figure raises a pair of binoculars to his eyes and slowly pans them toward the center of the frame.
[3-7s] Binocular-shaped vignette view: Scar stands alone on the summit of the throne rock, chest out, and roars toward the sky; dust and birds scatter from the acacia trees.
[7-10s] Cut back: the stick figure lowers the binoculars, jaw dropping, then grabs a tall wooden lever with a glowing brass handle planted in the grass beside him.

NARRATION (audio voiceover only, strictly no speech bubbles, no dialogue boxes): "Scar won. Simba lost the final fight on Pride Rock. And that is exactly when Scar's real nightmare began." Speak exactly these words once, in this order. Do not add, omit, paraphrase, repeat or reorder words, and do not show them as captions, subtitles or any visible text. No animal or character speaks or lip-syncs.

VOICE: One off-screen adult male narrator throughout. General American accent, warm clean baritone, medium-low pitch, gentle chest resonance, no raspiness or breathiness. Calm conversational delivery, restrained pitch variation, steady speaking pace, and close, dry studio sound. Keep the same vocal timbre, register, accent, pace, and recording quality throughout. Emotional progression belongs to the visuals and music; do not change the narrator's voice or switch to character dialogue.

Audio: Voiceover clearly audible over quiet, thoughtful piano and subtle soft ambient synth, building gentle optimistic momentum. SFX: wind over grass, a deep echoing lion roar, birds flapping away, a mechanical click as the lever is gripped. Voice-first mix.

FINAL FRAME: The stick figure gripping the glowing lever, ready to pull.

Negative constraints: no photorealistic human skin or faces, no 3D humanoid CGI uncanny valley models, no chaotic line glitches, no speech bubbles, no dialogue text boxes. No visible words, letters, numbers, captions, subtitles, logos or watermarks; books, signs and crowns stay blank or icon-only. No blood, gore or injury. No realistic animal fur or photorealistic animals. No extra limbs, no pom-pom on the beanie, no missing t-shirt, no costume changes, no extra characters, no abstract liquid or shape morphing.
```

## Đoạn 2
**Ảnh tham chiếu cần đính kèm:** zeke.png

```text
OUTPUT: A stickman animated video, approximately 10 seconds, 16:9 landscape, 720p target, 24 FPS, synchronized audio. Rapid scene changes and frequent visual events, while preserving an identical stick-figure design, constant line weight, and strict temporal consistency.

ENVIRONMENT: in a rich full-color cinematic environment: a vast African savanna with tall grass, flat-topped acacia trees and one towering jutting rock outcrop that serves as the king's throne. Cinematic volumetric lighting, soft depth of field, atmospheric narrative mood. Lighting and palette for this clip: Warm gold light.

CHARACTERS:
The same minimalist 2D animated stick figure in a bright red beanie and yellow shirt... Simple black lines, vibrant colors, smooth 2D animation style. Hollow circular head with minimal dot eyes only; he is a silent time-travelling observer and never speaks.
All animals share the same drawing style as the stick figure: simple clean black outlines, flat vibrant colors, minimal black dot eyes, simple brow lines for expression, smooth 2D vector animation. No realistic fur texture, no detailed irises.

COMPOSITION (16:9): stage action across left, center and right thirds. The throne rock stands at center; the green hills lie off to the right. Use lateral tracking, deliberate negative space in the upper-left area, and keep screen direction consistent: anyone leaving the kingdom moves toward the right.

FIRST FRAME: The stick figure stands beside the glowing lever in the left foreground of the savanna.

TIMED ACTION:
[0-3s] A giant red theatre curtain drops from the sky across the savanna; the stick figure pulls a rope and the curtain closes with a heavy swoosh.
[3-7s] He tiptoes to the curtain, lifts one corner and peeks behind it.
[7-10s] Behind the curtain the savanna is still alive: grass sways, a herd of antelope grazes, clouds drift; he opens the curtain wide, surprised.

NARRATION (audio voiceover only, strictly no speech bubbles, no dialogue boxes): "We all assume the story ends when the villain wins. The hero falls, the credits roll. But a kingdom doesn't stop at the credits." Speak exactly these words once, in this order. Do not add, omit, paraphrase, repeat or reorder words, and do not show them as captions, subtitles or any visible text. No animal or character speaks or lip-syncs.

VOICE: One off-screen adult male narrator throughout. General American accent, warm clean baritone, medium-low pitch, gentle chest resonance, no raspiness or breathiness. Calm conversational delivery, restrained pitch variation, steady speaking pace, and close, dry studio sound. Keep the same vocal timbre, register, accent, pace, and recording quality throughout. Emotional progression belongs to the visuals and music; do not change the narrator's voice or switch to character dialogue.

Audio: Voiceover seamlessly continues the identical quiet, thoughtful piano and subtle soft ambient synth from clip 1, maintaining identical tempo, instrumentation, and optimistic narrative momentum. Synchronized crisp SFX on physical actions. SFX: heavy curtain swoosh, rope creak, soft savanna wind and grazing herd sounds. Voice-first mix.

FINAL FRAME: The curtain pulled fully open, revealing the living savanna; the stick figure sits down on a rock holding a large picture book.

Negative constraints: no photorealistic human skin or faces, no 3D humanoid CGI uncanny valley models, no chaotic line glitches, no speech bubbles, no dialogue text boxes. No visible words, letters, numbers, captions, subtitles, logos or watermarks; books, signs and crowns stay blank or icon-only. No blood, gore or injury. No realistic animal fur or photorealistic animals. No extra limbs, no pom-pom on the beanie, no missing t-shirt, no costume changes, no extra characters, no abstract liquid or shape morphing.
```

## Đoạn 3
**Ảnh tham chiếu cần đính kèm:** zeke.png

```text
OUTPUT: A stickman animated video, approximately 10 seconds, 16:9 landscape, 720p target, 24 FPS, synchronized audio. Rapid scene changes and frequent visual events, while preserving an identical stick-figure design, constant line weight, and strict temporal consistency.

ENVIRONMENT: in a rich full-color cinematic environment: a vast African savanna with tall grass, flat-topped acacia trees and one towering jutting rock outcrop that serves as the king's throne. Cinematic volumetric lighting, soft depth of field, atmospheric narrative mood. Lighting and palette for this clip: Warm gold light, then dusty amber inside the book's illustrations.

CHARACTERS:
The same minimalist 2D animated stick figure in a bright red beanie and yellow shirt... Simple black lines, vibrant colors, smooth 2D animation style. Hollow circular head with minimal dot eyes only; he is a silent time-travelling observer and never speaks.
All animals share the same drawing style as the stick figure: simple clean black outlines, flat vibrant colors, minimal black dot eyes, simple brow lines for expression, smooth 2D vector animation. No realistic fur texture, no detailed irises.

COMPOSITION (16:9): stage action across left, center and right thirds. The throne rock stands at center; the green hills lie off to the right. Use lateral tracking, deliberate negative space in the upper-left area, and keep screen direction consistent: anyone leaving the kingdom moves toward the right.

FIRST FRAME: The stick figure sits on a rock in the savanna with a large picture book on his lap.

TIMED ACTION:
[0-3s] He opens the picture book; its blank-captioned illustrations come alive and fill the frame.
[3-7s] Inside the illustration: a huge cloud of dust rolls across a canyon as a stampede of wildebeest thunders past; no animal is shown being hurt.
[7-10s] Still inside the illustration: a small golden lion cub runs away alone toward a distant orange horizon, growing smaller; the page turns.

NARRATION (audio voiceover only, strictly no speech bubbles, no dialogue boxes): "Remember the original. Scar caused Mufasa's death, blamed young Simba, and sent him running into exile, far from home." Speak exactly these words once, in this order. Do not add, omit, paraphrase, repeat or reorder words, and do not show them as captions, subtitles or any visible text. No animal or character speaks or lip-syncs.

VOICE: One off-screen adult male narrator throughout. General American accent, warm clean baritone, medium-low pitch, gentle chest resonance, no raspiness or breathiness. Calm conversational delivery, restrained pitch variation, steady speaking pace, and close, dry studio sound. Keep the same vocal timbre, register, accent, pace, and recording quality throughout. Emotional progression belongs to the visuals and music; do not change the narrator's voice or switch to character dialogue.

Audio: Voiceover seamlessly continues the identical quiet, thoughtful piano and subtle soft ambient synth from clip 1, maintaining identical tempo, instrumentation, and optimistic narrative momentum. Synchronized crisp SFX on physical actions. SFX: page flip, rumbling hooves, wind, small paw steps fading into distance. Voice-first mix.

FINAL FRAME: The page turns to reveal the throne rock at dusk.

Negative constraints: no photorealistic human skin or faces, no 3D humanoid CGI uncanny valley models, no chaotic line glitches, no speech bubbles, no dialogue text boxes. No visible words, letters, numbers, captions, subtitles, logos or watermarks; books, signs and crowns stay blank or icon-only. No blood, gore or injury. No realistic animal fur or photorealistic animals. No extra limbs, no pom-pom on the beanie, no missing t-shirt, no costume changes, no extra characters, no abstract liquid or shape morphing.
```

## Đoạn 4
**Ảnh tham chiếu cần đính kèm:** zeke.png, scar.png, simba.png

```text
OUTPUT: A stickman animated video, approximately 10 seconds, 16:9 landscape, 720p target, 24 FPS, synchronized audio. Rapid scene changes and frequent visual events, while preserving an identical stick-figure design, constant line weight, and strict temporal consistency.

ENVIRONMENT: in a rich full-color cinematic environment: a vast African savanna with tall grass, flat-topped acacia trees and one towering jutting rock outcrop that serves as the king's throne. Cinematic volumetric lighting, soft depth of field, atmospheric narrative mood. Lighting and palette for this clip: Dramatic dusk light with smoke and orange-violet sky.

CHARACTERS:
The same minimalist 2D animated stick figure in a bright red beanie and yellow shirt... Simple black lines, vibrant colors, smooth 2D animation style. Hollow circular head with minimal dot eyes only; he is a silent time-travelling observer and never speaks.
SCAR (villain lion): a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, minimal black dot eyes under a narrow sly brow line, and a long thin tail ending in a black tuft. Walks on four legs like a real lion, no clothing.
SIMBA (young hero lion): a strong young adult male lion with golden fur, a full reddish-brown mane, minimal black dot eyes under a determined brow line, and a tail ending in a reddish-brown tuft. Four legs, no clothing.
All animals share the same drawing style as the stick figure: simple clean black outlines, flat vibrant colors, minimal black dot eyes, simple brow lines for expression, smooth 2D vector animation. No realistic fur texture, no detailed irises.

COMPOSITION (16:9): stage action across left, center and right thirds. The throne rock stands at center; the green hills lie off to the right. Use lateral tracking, deliberate negative space in the upper-left area, and keep screen direction consistent: anyone leaving the kingdom moves toward the right.

FIRST FRAME: The throne rock at dusk, wisps of smoke drifting across the summit.

TIMED ACTION:
[0-3s] On the summit, Simba and Scar circle each other face to face, manes lifted by the wind.
[3-7s] Simba steps back toward the edge; his paw slips on loose stones, and he slides down the steep rocky slope and disappears into the drifting smoke, unhurt and out of view.
[7-10s] Scar stands alone at the edge, staring down; cut to the stick figure in the left foreground covering his eyes with both hands.

NARRATION (audio voiceover only, strictly no speech bubbles, no dialogue boxes): "Years later, Simba returned to fight. In our story, his paw slips at the edge, and Scar is left standing alone." Speak exactly these words once, in this order. Do not add, omit, paraphrase, repeat or reorder words, and do not show them as captions, subtitles or any visible text. No animal or character speaks or lip-syncs.

VOICE: One off-screen adult male narrator throughout. General American accent, warm clean baritone, medium-low pitch, gentle chest resonance, no raspiness or breathiness. Calm conversational delivery, restrained pitch variation, steady speaking pace, and close, dry studio sound. Keep the same vocal timbre, register, accent, pace, and recording quality throughout. Emotional progression belongs to the visuals and music; do not change the narrator's voice or switch to character dialogue.

Audio: Voiceover seamlessly continues the identical quiet, thoughtful piano and subtle soft ambient synth from clip 1, maintaining identical tempo, instrumentation, and optimistic narrative momentum. Synchronized crisp SFX on physical actions. SFX: low growls, gusting wind, stones clattering down the slope, a sudden hush. Voice-first mix.

FINAL FRAME: Scar alone on the summit edge, silhouetted against the dusk sky.

Negative constraints: no photorealistic human skin or faces, no 3D humanoid CGI uncanny valley models, no chaotic line glitches, no speech bubbles, no dialogue text boxes. No visible words, letters, numbers, captions, subtitles, logos or watermarks; books, signs and crowns stay blank or icon-only. No blood, gore or injury. No realistic animal fur or photorealistic animals. No extra limbs, no pom-pom on the beanie, no missing t-shirt, no costume changes, no extra characters, no abstract liquid or shape morphing.
```

## Đoạn 5
**Ảnh tham chiếu cần đính kèm:** zeke.png, scar.png, hyena.png

```text
OUTPUT: A stickman animated video, approximately 10 seconds, 16:9 landscape, 720p target, 24 FPS, synchronized audio. Rapid scene changes and frequent visual events, while preserving an identical stick-figure design, constant line weight, and strict temporal consistency.

ENVIRONMENT: in a rich full-color cinematic environment: a vast African savanna with tall grass, flat-topped acacia trees and one towering jutting rock outcrop that serves as the king's throne. Cinematic volumetric lighting, soft depth of field, atmospheric narrative mood. Lighting and palette for this clip: Night turning to bright golden morning, warm gold palette.

CHARACTERS:
The same minimalist 2D animated stick figure in a bright red beanie and yellow shirt... Simple black lines, vibrant colors, smooth 2D animation style. Hollow circular head with minimal dot eyes only; he is a silent time-travelling observer and never speaks.
SCAR (villain lion): a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, minimal black dot eyes under a narrow sly brow line, and a long thin tail ending in a black tuft. Walks on four legs like a real lion, no clothing.
HYENAS (uniform group, identical design): scrawny grey hyenas with black spots, sloped backs, round ears, minimal black dot eyes and wide toothy grins drawn simply.
All animals share the same drawing style as the stick figure: simple clean black outlines, flat vibrant colors, minimal black dot eyes, simple brow lines for expression, smooth 2D vector animation. No realistic fur texture, no detailed irises.

COMPOSITION (16:9): stage action across left, center and right thirds. The throne rock stands at center; the green hills lie off to the right. Use lateral tracking, deliberate negative space in the upper-left area, and keep screen direction consistent: anyone leaving the kingdom moves toward the right.

FIRST FRAME: Scar alone at the summit edge, the sky brightening into morning.

TIMED ACTION:
[0-3s] Scar climbs the last steps to the very top of the throne rock and roars.
[3-7s] Below, the hyena pack leaps and dances in celebration, tails wagging, kicking up dust.
[7-10s] In the left foreground the stick figure claps slowly and awkwardly, glancing sideways at the camera.

NARRATION (audio voiceover only, strictly no speech bubbles, no dialogue boxes): "Day one. Scar climbs Pride Rock and roars. The hyenas cheer. For one night, he finally has everything he wanted." Speak exactly these words once, in this order. Do not add, omit, paraphrase, repeat or reorder words, and do not show them as captions, subtitles or any visible text. No animal or character speaks or lip-syncs.

VOICE: One off-screen adult male narrator throughout. General American accent, warm clean baritone, medium-low pitch, gentle chest resonance, no raspiness or breathiness. Calm conversational delivery, restrained pitch variation, steady speaking pace, and close, dry studio sound. Keep the same vocal timbre, register, accent, pace, and recording quality throughout. Emotional progression belongs to the visuals and music; do not change the narrator's voice or switch to character dialogue.

Audio: Voiceover seamlessly continues the identical quiet, thoughtful piano and subtle soft ambient synth from clip 1, maintaining identical tempo, instrumentation, and optimistic narrative momentum. Synchronized crisp SFX on physical actions. SFX: triumphant roar, hyena cackling and yipping, scattered awkward clapping. Voice-first mix.

FINAL FRAME: Hyenas crowding at the foot of the rock, looking up.

Negative constraints: no photorealistic human skin or faces, no 3D humanoid CGI uncanny valley models, no chaotic line glitches, no speech bubbles, no dialogue text boxes. No visible words, letters, numbers, captions, subtitles, logos or watermarks; books, signs and crowns stay blank or icon-only. No blood, gore or injury. No realistic animal fur or photorealistic animals. No extra limbs, no pom-pom on the beanie, no missing t-shirt, no costume changes, no extra characters, no abstract liquid or shape morphing.
```

## Đoạn 6
**Ảnh tham chiếu cần đính kèm:** zeke.png, scar.png, hyena.png

```text
OUTPUT: A stickman animated video, approximately 10 seconds, 16:9 landscape, 720p target, 24 FPS, synchronized audio. Rapid scene changes and frequent visual events, while preserving an identical stick-figure design, constant line weight, and strict temporal consistency.

ENVIRONMENT: in a rich full-color cinematic environment: a vast African savanna with tall grass, flat-topped acacia trees and one towering jutting rock outcrop that serves as the king's throne. Cinematic volumetric lighting, soft depth of field, atmospheric narrative mood. Lighting and palette for this clip: Hot midday light, the gold starting to fade toward dusty orange.

CHARACTERS:
The same minimalist 2D animated stick figure in a bright red beanie and yellow shirt... Simple black lines, vibrant colors, smooth 2D animation style. Hollow circular head with minimal dot eyes only; he is a silent time-travelling observer and never speaks.
SCAR (villain lion): a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, minimal black dot eyes under a narrow sly brow line, and a long thin tail ending in a black tuft. Walks on four legs like a real lion, no clothing.
HYENAS (uniform group, identical design): scrawny grey hyenas with black spots, sloped backs, round ears, minimal black dot eyes and wide toothy grins drawn simply.
All animals share the same drawing style as the stick figure: simple clean black outlines, flat vibrant colors, minimal black dot eyes, simple brow lines for expression, smooth 2D vector animation. No realistic fur texture, no detailed irises.

COMPOSITION (16:9): stage action across left, center and right thirds. The throne rock stands at center; the green hills lie off to the right. Use lateral tracking, deliberate negative space in the upper-left area, and keep screen direction consistent: anyone leaving the kingdom moves toward the right.

FIRST FRAME: Hyenas crowded at the foot of the throne rock, looking up.

TIMED ACTION:
[0-3s] The hyenas form a long line, licking their lips and holding up empty wooden bowls toward Scar.
[3-7s] The line keeps growing, snaking back across the savanna as more hyenas arrive; Scar shifts uneasily on the rock.
[7-10s] The stick figure counts the hyenas on his fingers, gets lost, and throws up his hands in confusion.

NARRATION (audio voiceover only, strictly no speech bubbles, no dialogue boxes): "Day two. The hyenas are hungry. Scar promised them food, and the pack keeps growing, waiting for him to deliver." Speak exactly these words once, in this order. Do not add, omit, paraphrase, repeat or reorder words, and do not show them as captions, subtitles or any visible text. No animal or character speaks or lip-syncs.

VOICE: One off-screen adult male narrator throughout. General American accent, warm clean baritone, medium-low pitch, gentle chest resonance, no raspiness or breathiness. Calm conversational delivery, restrained pitch variation, steady speaking pace, and close, dry studio sound. Keep the same vocal timbre, register, accent, pace, and recording quality throughout. Emotional progression belongs to the visuals and music; do not change the narrator's voice or switch to character dialogue.

Audio: Voiceover seamlessly continues the identical quiet, thoughtful piano and subtle soft ambient synth from clip 1, maintaining identical tempo, instrumentation, and optimistic narrative momentum. Synchronized crisp SFX on physical actions. SFX: stomach rumbles, bowls clattering, hyenas whining, footsteps of more arriving. Voice-first mix.

FINAL FRAME: The stick figure with arms raised in confusion, then picks up a blank paper crown from the grass.

Negative constraints: no photorealistic human skin or faces, no 3D humanoid CGI uncanny valley models, no chaotic line glitches, no speech bubbles, no dialogue text boxes. No visible words, letters, numbers, captions, subtitles, logos or watermarks; books, signs and crowns stay blank or icon-only. No blood, gore or injury. No realistic animal fur or photorealistic animals. No extra limbs, no pom-pom on the beanie, no missing t-shirt, no costume changes, no extra characters, no abstract liquid or shape morphing.
```

## Đoạn 7
**Ảnh tham chiếu cần đính kèm:** zeke.png, scar.png, nala.png, lioness.png

```text
OUTPUT: A stickman animated video, approximately 10 seconds, 16:9 landscape, 720p target, 24 FPS, synchronized audio. Rapid scene changes and frequent visual events, while preserving an identical stick-figure design, constant line weight, and strict temporal consistency.

ENVIRONMENT: in a rich full-color cinematic environment: a vast African savanna with tall grass, flat-topped acacia trees and one towering jutting rock outcrop that serves as the king's throne. Cinematic volumetric lighting, soft depth of field, atmospheric narrative mood. Lighting and palette for this clip: Late afternoon light, dusty orange palette.

CHARACTERS:
The same minimalist 2D animated stick figure in a bright red beanie and yellow shirt... Simple black lines, vibrant colors, smooth 2D animation style. Hollow circular head with minimal dot eyes only; he is a silent time-travelling observer and never speaks.
SCAR (villain lion): a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, minimal black dot eyes under a narrow sly brow line, and a long thin tail ending in a black tuft. Walks on four legs like a real lion, no clothing.
NALA (lioness leader): a sleek adult lioness with pale cream-gold fur, a small notch cut into the tip of her left ear, minimal black dot eyes under a calm steady brow line, no mane. Four legs, no clothing.
LIONESSES (uniform group, identical design): sleek sandy-gold lionesses with minimal black dot eyes, no manes and no ear notches.
All animals share the same drawing style as the stick figure: simple clean black outlines, flat vibrant colors, minimal black dot eyes, simple brow lines for expression, smooth 2D vector animation. No realistic fur texture, no detailed irises.

COMPOSITION (16:9): stage action across left, center and right thirds. The throne rock stands at center; the green hills lie off to the right. Use lateral tracking, deliberate negative space in the upper-left area, and keep screen direction consistent: anyone leaving the kingdom moves toward the right.

FIRST FRAME: The stick figure in the left foreground holding a blank yellow paper crown.

TIMED ACTION:
[0-3s] The stick figure places the paper crown on his beanie and stands proudly, waiting; nothing happens, a tumbleweed rolls past.
[3-7s] Cut to the tall grass: the lionesses crouch low, stalking prey with focused eyes, Nala in front.
[7-10s] Nala lifts her head and turns to look toward Scar on the distant throne rock; Scar notices and narrows his eyes.

NARRATION (audio voiceover only, strictly no speech bubbles, no dialogue boxes): "Here's the secret every king learns: a crown doesn't hunt. The lionesses do. And they are watching Scar very closely." Speak exactly these words once, in this order. Do not add, omit, paraphrase, repeat or reorder words, and do not show them as captions, subtitles or any visible text. No animal or character speaks or lip-syncs.

VOICE: One off-screen adult male narrator throughout. General American accent, warm clean baritone, medium-low pitch, gentle chest resonance, no raspiness or breathiness. Calm conversational delivery, restrained pitch variation, steady speaking pace, and close, dry studio sound. Keep the same vocal timbre, register, accent, pace, and recording quality throughout. Emotional progression belongs to the visuals and music; do not change the narrator's voice or switch to character dialogue.

Audio: Voiceover seamlessly continues the identical quiet, thoughtful piano and subtle soft ambient synth from clip 1, maintaining identical tempo, instrumentation, and optimistic narrative momentum. Synchronized crisp SFX on physical actions. SFX: tumbleweed rustle, silent tense grass rustling, a soft wary growl. Voice-first mix.

FINAL FRAME: Nala staring toward the throne rock.

Negative constraints: no photorealistic human skin or faces, no 3D humanoid CGI uncanny valley models, no chaotic line glitches, no speech bubbles, no dialogue text boxes. No visible words, letters, numbers, captions, subtitles, logos or watermarks; books, signs and crowns stay blank or icon-only. No blood, gore or injury. No realistic animal fur or photorealistic animals. No extra limbs, no pom-pom on the beanie, no missing t-shirt, no costume changes, no extra characters, no abstract liquid or shape morphing.
```

## Đoạn 8
**Ảnh tham chiếu cần đính kèm:** zeke.png, nala.png, lioness.png

```text
OUTPUT: A stickman animated video, approximately 10 seconds, 16:9 landscape, 720p target, 24 FPS, synchronized audio. Rapid scene changes and frequent visual events, while preserving an identical stick-figure design, constant line weight, and strict temporal consistency.

ENVIRONMENT: in a rich full-color cinematic environment: a vast African savanna with tall grass, flat-topped acacia trees and one towering jutting rock outcrop that serves as the king's throne. Cinematic volumetric lighting, soft depth of field, atmospheric narrative mood. Lighting and palette for this clip: Dusty orange and dry brown palette, harsh sunlight.

CHARACTERS:
The same minimalist 2D animated stick figure in a bright red beanie and yellow shirt... Simple black lines, vibrant colors, smooth 2D animation style. Hollow circular head with minimal dot eyes only; he is a silent time-travelling observer and never speaks.
NALA (lioness leader): a sleek adult lioness with pale cream-gold fur, a small notch cut into the tip of her left ear, minimal black dot eyes under a calm steady brow line, no mane. Four legs, no clothing.
LIONESSES (uniform group, identical design): sleek sandy-gold lionesses with minimal black dot eyes, no manes and no ear notches.
All animals share the same drawing style as the stick figure: simple clean black outlines, flat vibrant colors, minimal black dot eyes, simple brow lines for expression, smooth 2D vector animation. No realistic fur texture, no detailed irises.

COMPOSITION (16:9): stage action across left, center and right thirds. The throne rock stands at center; the green hills lie off to the right. Use lateral tracking, deliberate negative space in the upper-left area, and keep screen direction consistent: anyone leaving the kingdom moves toward the right.

FIRST FRAME: Nala in the grass staring toward the throne rock.

TIMED ACTION:
[0-3s] The lionesses spring into a hunt; dust explodes, but the antelope escape and the lionesses skid to a stop empty-pawed.
[3-7s] The pride walks to a waterhole that has dried into cracked mud; Nala paws at the dry cracks.
[7-10s] Nala looks at the other lionesses; they exchange silent glances one by one in a slow lateral pan.

NARRATION (audio voiceover only, strictly no speech bubbles, no dialogue boxes): "Nala leads them. Every failed hunt, every empty waterhole, they quietly ask the same question: why are we following him?" Speak exactly these words once, in this order. Do not add, omit, paraphrase, repeat or reorder words, and do not show them as captions, subtitles or any visible text. No animal or character speaks or lip-syncs.

VOICE: One off-screen adult male narrator throughout. General American accent, warm clean baritone, medium-low pitch, gentle chest resonance, no raspiness or breathiness. Calm conversational delivery, restrained pitch variation, steady speaking pace, and close, dry studio sound. Keep the same vocal timbre, register, accent, pace, and recording quality throughout. Emotional progression belongs to the visuals and music; do not change the narrator's voice or switch to character dialogue.

Audio: Voiceover seamlessly continues the identical quiet, thoughtful piano and subtle soft ambient synth from clip 1, maintaining identical tempo, instrumentation, and optimistic narrative momentum. Synchronized crisp SFX on physical actions. SFX: thundering chase, skidding paws, cracking dry mud, a long dry wind. Voice-first mix.

FINAL FRAME: The lionesses' silent glances; camera tilts up toward a dry cloudy sky.

Negative constraints: no photorealistic human skin or faces, no 3D humanoid CGI uncanny valley models, no chaotic line glitches, no speech bubbles, no dialogue text boxes. No visible words, letters, numbers, captions, subtitles, logos or watermarks; books, signs and crowns stay blank or icon-only. No blood, gore or injury. No realistic animal fur or photorealistic animals. No extra limbs, no pom-pom on the beanie, no missing t-shirt, no costume changes, no extra characters, no abstract liquid or shape morphing.
```

## Đoạn 9
**Ảnh tham chiếu cần đính kèm:** zeke.png, scar.png

```text
OUTPUT: A stickman animated video, approximately 10 seconds, 16:9 landscape, 720p target, 24 FPS, synchronized audio. Rapid scene changes and frequent visual events, while preserving an identical stick-figure design, constant line weight, and strict temporal consistency.

ENVIRONMENT: in a rich full-color cinematic environment: a vast African savanna with tall grass, flat-topped acacia trees and one towering jutting rock outcrop that serves as the king's throne. Cinematic volumetric lighting, soft depth of field, atmospheric narrative mood. Lighting and palette for this clip: Dry brown and dusty orange palette, pale washed-out sky.

CHARACTERS:
The same minimalist 2D animated stick figure in a bright red beanie and yellow shirt... Simple black lines, vibrant colors, smooth 2D animation style. Hollow circular head with minimal dot eyes only; he is a silent time-travelling observer and never speaks.
SCAR (villain lion): a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, minimal black dot eyes under a narrow sly brow line, and a long thin tail ending in a black tuft. Walks on four legs like a real lion, no clothing.
All animals share the same drawing style as the stick figure: simple clean black outlines, flat vibrant colors, minimal black dot eyes, simple brow lines for expression, smooth 2D vector animation. No realistic fur texture, no detailed irises.

COMPOSITION (16:9): stage action across left, center and right thirds. The throne rock stands at center; the green hills lie off to the right. Use lateral tracking, deliberate negative space in the upper-left area, and keep screen direction consistent: anyone leaving the kingdom moves toward the right.

FIRST FRAME: A dry sky with thin pale clouds drifting over the savanna.

TIMED ACTION:
[0-3s] Dry clouds drift past without rain; herds of antelope and zebra walk away in a long line toward the right side of the frame.
[3-7s] Scar roars after them from the throne rock; none of the herds turn back.
[7-10s] The stick figure opens an umbrella and holds it up, waiting for rain; not a single drop falls, and he peeks out from under it.

NARRATION (audio voiceover only, strictly no speech bubbles, no dialogue boxes): "Month six. The rains are late. Herds walk away to find grass. Scar can't roar them back. No speech can bring the clouds." Speak exactly these words once, in this order. Do not add, omit, paraphrase, repeat or reorder words, and do not show them as captions, subtitles or any visible text. No animal or character speaks or lip-syncs.

VOICE: One off-screen adult male narrator throughout. General American accent, warm clean baritone, medium-low pitch, gentle chest resonance, no raspiness or breathiness. Calm conversational delivery, restrained pitch variation, steady speaking pace, and close, dry studio sound. Keep the same vocal timbre, register, accent, pace, and recording quality throughout. Emotional progression belongs to the visuals and music; do not change the narrator's voice or switch to character dialogue.

Audio: Voiceover seamlessly continues the identical quiet, thoughtful piano and subtle soft ambient synth from clip 1, maintaining identical tempo, instrumentation, and optimistic narrative momentum. Synchronized crisp SFX on physical actions. SFX: dry wind, distant hooves walking away, a hoarse roar, umbrella snapping open. Voice-first mix.

FINAL FRAME: The stick figure lowering the empty umbrella, looking toward the kingdom's border.

Negative constraints: no photorealistic human skin or faces, no 3D humanoid CGI uncanny valley models, no chaotic line glitches, no speech bubbles, no dialogue text boxes. No visible words, letters, numbers, captions, subtitles, logos or watermarks; books, signs and crowns stay blank or icon-only. No blood, gore or injury. No realistic animal fur or photorealistic animals. No extra limbs, no pom-pom on the beanie, no missing t-shirt, no costume changes, no extra characters, no abstract liquid or shape morphing.
```

## Đoạn 10
**Ảnh tham chiếu cần đính kèm:** zeke.png, scar.png, hyena.png

```text
OUTPUT: A stickman animated video, approximately 10 seconds, 16:9 landscape, 720p target, 24 FPS, synchronized audio. Rapid scene changes and frequent visual events, while preserving an identical stick-figure design, constant line weight, and strict temporal consistency.

ENVIRONMENT: in a rich full-color cinematic environment: a vast African savanna with tall grass, flat-topped acacia trees and one towering jutting rock outcrop that serves as the king's throne. Cinematic volumetric lighting, soft depth of field, atmospheric narrative mood. Lighting and palette for this clip: Dry brown palette, harsh low sun.

CHARACTERS:
The same minimalist 2D animated stick figure in a bright red beanie and yellow shirt... Simple black lines, vibrant colors, smooth 2D animation style. Hollow circular head with minimal dot eyes only; he is a silent time-travelling observer and never speaks.
SCAR (villain lion): a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, minimal black dot eyes under a narrow sly brow line, and a long thin tail ending in a black tuft. Walks on four legs like a real lion, no clothing.
HYENAS (uniform group, identical design): scrawny grey hyenas with black spots, sloped backs, round ears, minimal black dot eyes and wide toothy grins drawn simply.
All animals share the same drawing style as the stick figure: simple clean black outlines, flat vibrant colors, minimal black dot eyes, simple brow lines for expression, smooth 2D vector animation. No realistic fur texture, no detailed irises.

COMPOSITION (16:9): stage action across left, center and right thirds. The throne rock stands at center; the green hills lie off to the right. Use lateral tracking, deliberate negative space in the upper-left area, and keep screen direction consistent: anyone leaving the kingdom moves toward the right.

FIRST FRAME: The stick figure lowering the umbrella, looking toward the border of the kingdom.

TIMED ACTION:
[0-3s] Scar points his paw and hyenas line up as guards along the border in a long row.
[3-7s] A fence of thorny branches rises along the border as hyenas drag branches into place.
[7-10s] Behind the fence the ground cracks wider and the grass turns brown; the stick figure shakes his head slowly.

NARRATION (audio voiceover only, strictly no speech bubbles, no dialogue boxes): "Scar tries what villains always try. More rules. More guards. More hyenas at the border. The land only grows thinner." Speak exactly these words once, in this order. Do not add, omit, paraphrase, repeat or reorder words, and do not show them as captions, subtitles or any visible text. No animal or character speaks or lip-syncs.

VOICE: One off-screen adult male narrator throughout. General American accent, warm clean baritone, medium-low pitch, gentle chest resonance, no raspiness or breathiness. Calm conversational delivery, restrained pitch variation, steady speaking pace, and close, dry studio sound. Keep the same vocal timbre, register, accent, pace, and recording quality throughout. Emotional progression belongs to the visuals and music; do not change the narrator's voice or switch to character dialogue.

Audio: Voiceover seamlessly continues the identical quiet, thoughtful piano and subtle soft ambient synth from clip 1, maintaining identical tempo, instrumentation, and optimistic narrative momentum. Synchronized crisp SFX on physical actions. SFX: thorny branches dragging, hyenas grunting, dry ground cracking. Voice-first mix.

FINAL FRAME: The thorn fence casting long shadows as night falls and dawn begins.

Negative constraints: no photorealistic human skin or faces, no 3D humanoid CGI uncanny valley models, no chaotic line glitches, no speech bubbles, no dialogue text boxes. No visible words, letters, numbers, captions, subtitles, logos or watermarks; books, signs and crowns stay blank or icon-only. No blood, gore or injury. No realistic animal fur or photorealistic animals. No extra limbs, no pom-pom on the beanie, no missing t-shirt, no costume changes, no extra characters, no abstract liquid or shape morphing.
```

## Đoạn 11
**Ảnh tham chiếu cần đính kèm:** zeke.png, nala.png, lioness.png

```text
OUTPUT: A stickman animated video, approximately 10 seconds, 16:9 landscape, 720p target, 24 FPS, synchronized audio. Rapid scene changes and frequent visual events, while preserving an identical stick-figure design, constant line weight, and strict temporal consistency.

ENVIRONMENT: in a rich full-color cinematic environment: a vast African savanna with tall grass, flat-topped acacia trees and one towering jutting rock outcrop that serves as the king's throne. Cinematic volumetric lighting, soft depth of field, atmospheric narrative mood. Lighting and palette for this clip: Soft pale dawn light, dry land on the left turning toward green hills on the right.

CHARACTERS:
The same minimalist 2D animated stick figure in a bright red beanie and yellow shirt... Simple black lines, vibrant colors, smooth 2D animation style. Hollow circular head with minimal dot eyes only; he is a silent time-travelling observer and never speaks.
NALA (lioness leader): a sleek adult lioness with pale cream-gold fur, a small notch cut into the tip of her left ear, minimal black dot eyes under a calm steady brow line, no mane. Four legs, no clothing.
LIONESSES (uniform group, identical design): sleek sandy-gold lionesses with minimal black dot eyes, no manes and no ear notches.
All animals share the same drawing style as the stick figure: simple clean black outlines, flat vibrant colors, minimal black dot eyes, simple brow lines for expression, smooth 2D vector animation. No realistic fur texture, no detailed irises.

COMPOSITION (16:9): stage action across left, center and right thirds. The throne rock stands at center; the green hills lie off to the right. Use lateral tracking, deliberate negative space in the upper-left area, and keep screen direction consistent: anyone leaving the kingdom moves toward the right.

FIRST FRAME: Pale dawn over the thorn fence and the dry kingdom.

TIMED ACTION:
[0-3s] Nala rises first and starts walking; the lionesses stand up one after another and follow her in a single line.
[3-7s] Lateral tracking shot: the pride walks quietly past the sleeping hyenas, moving toward the right, where green hills glow in the distance.
[7-10s] The stick figure in the left foreground waves goodbye; the last lioness glances back once, then keeps walking.

NARRATION (audio voiceover only, strictly no speech bubbles, no dialogue boxes): "Year one. The lionesses don't fight him. They do something worse. One morning, they simply walk away, together, toward the green hills." Speak exactly these words once, in this order. Do not add, omit, paraphrase, repeat or reorder words, and do not show them as captions, subtitles or any visible text. No animal or character speaks or lip-syncs.

VOICE: One off-screen adult male narrator throughout. General American accent, warm clean baritone, medium-low pitch, gentle chest resonance, no raspiness or breathiness. Calm conversational delivery, restrained pitch variation, steady speaking pace, and close, dry studio sound. Keep the same vocal timbre, register, accent, pace, and recording quality throughout. Emotional progression belongs to the visuals and music; do not change the narrator's voice or switch to character dialogue.

Audio: Voiceover seamlessly continues the identical quiet, thoughtful piano and subtle soft ambient synth from clip 1, maintaining identical tempo, instrumentation, and optimistic narrative momentum. Synchronized crisp SFX on physical actions. SFX: soft paw steps on dry grass, gentle dawn birds, hyena snoring. Voice-first mix.

FINAL FRAME: The empty space where the pride used to rest, with the throne rock behind.

Negative constraints: no photorealistic human skin or faces, no 3D humanoid CGI uncanny valley models, no chaotic line glitches, no speech bubbles, no dialogue text boxes. No visible words, letters, numbers, captions, subtitles, logos or watermarks; books, signs and crowns stay blank or icon-only. No blood, gore or injury. No realistic animal fur or photorealistic animals. No extra limbs, no pom-pom on the beanie, no missing t-shirt, no costume changes, no extra characters, no abstract liquid or shape morphing.
```

## Đoạn 12
**Ảnh tham chiếu cần đính kèm:** zeke.png, scar.png, hyena.png

```text
OUTPUT: A stickman animated video, approximately 10 seconds, 16:9 landscape, 720p target, 24 FPS, synchronized audio. Rapid scene changes and frequent visual events, while preserving an identical stick-figure design, constant line weight, and strict temporal consistency.

ENVIRONMENT: in a rich full-color cinematic environment: a vast African savanna with tall grass, flat-topped acacia trees and one towering jutting rock outcrop that serves as the king's throne. Cinematic volumetric lighting, soft depth of field, atmospheric narrative mood. Lighting and palette for this clip: Dusty orange light fading toward grey.

CHARACTERS:
The same minimalist 2D animated stick figure in a bright red beanie and yellow shirt... Simple black lines, vibrant colors, smooth 2D animation style. Hollow circular head with minimal dot eyes only; he is a silent time-travelling observer and never speaks.
SCAR (villain lion): a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, minimal black dot eyes under a narrow sly brow line, and a long thin tail ending in a black tuft. Walks on four legs like a real lion, no clothing.
HYENAS (uniform group, identical design): scrawny grey hyenas with black spots, sloped backs, round ears, minimal black dot eyes and wide toothy grins drawn simply.
All animals share the same drawing style as the stick figure: simple clean black outlines, flat vibrant colors, minimal black dot eyes, simple brow lines for expression, smooth 2D vector animation. No realistic fur texture, no detailed irises.

COMPOSITION (16:9): stage action across left, center and right thirds. The throne rock stands at center; the green hills lie off to the right. Use lateral tracking, deliberate negative space in the upper-left area, and keep screen direction consistent: anyone leaving the kingdom moves toward the right.

FIRST FRAME: The empty resting place below the throne rock.

TIMED ACTION:
[0-3s] The hyenas wake up and look around the empty rock, sniffing the bare ground.
[3-7s] They look up at Scar, now visibly thin, sitting on the rock; they glance at each other.
[7-10s] One by one the hyenas turn their backs and slink away toward the left edge of the frame.

NARRATION (audio voiceover only, strictly no speech bubbles, no dialogue boxes): "Now the hyenas see what's left: an empty rock, a thin king, and nothing to eat. Loyalty runs out with the food." Speak exactly these words once, in this order. Do not add, omit, paraphrase, repeat or reorder words, and do not show them as captions, subtitles or any visible text. No animal or character speaks or lip-syncs.

VOICE: One off-screen adult male narrator throughout. General American accent, warm clean baritone, medium-low pitch, gentle chest resonance, no raspiness or breathiness. Calm conversational delivery, restrained pitch variation, steady speaking pace, and close, dry studio sound. Keep the same vocal timbre, register, accent, pace, and recording quality throughout. Emotional progression belongs to the visuals and music; do not change the narrator's voice or switch to character dialogue.

Audio: Voiceover seamlessly continues the identical quiet, thoughtful piano and subtle soft ambient synth from clip 1, maintaining identical tempo, instrumentation, and optimistic narrative momentum. Synchronized crisp SFX on physical actions. SFX: sniffing, uneasy whines, paws padding away, wind picking up. Voice-first mix.

FINAL FRAME: Scar alone; the stick figure grabs the glowing lever.

Negative constraints: no photorealistic human skin or faces, no 3D humanoid CGI uncanny valley models, no chaotic line glitches, no speech bubbles, no dialogue text boxes. No visible words, letters, numbers, captions, subtitles, logos or watermarks; books, signs and crowns stay blank or icon-only. No blood, gore or injury. No realistic animal fur or photorealistic animals. No extra limbs, no pom-pom on the beanie, no missing t-shirt, no costume changes, no extra characters, no abstract liquid or shape morphing.
```

## Đoạn 13
**Ảnh tham chiếu cần đính kèm:** zeke.png, scar-old.png

```text
OUTPUT: A stickman animated video, approximately 10 seconds, 16:9 landscape, 720p target, 24 FPS, synchronized audio. Rapid scene changes and frequent visual events, while preserving an identical stick-figure design, constant line weight, and strict temporal consistency.

ENVIRONMENT: in a rich full-color cinematic environment: a vast African savanna with tall grass, flat-topped acacia trees and one towering jutting rock outcrop that serves as the king's throne. Cinematic volumetric lighting, soft depth of field, atmospheric narrative mood. Lighting and palette for this clip: Grey-violet dusk palette, swirling dust.

CHARACTERS:
The same minimalist 2D animated stick figure in a bright red beanie and yellow shirt... Simple black lines, vibrant colors, smooth 2D animation style. Hollow circular head with minimal dot eyes only; he is a silent time-travelling observer and never speaks.
SCAR (villain lion): a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, minimal black dot eyes under a narrow sly brow line, and a long thin tail ending in a black tuft. Walks on four legs like a real lion, no clothing.
All animals share the same drawing style as the stick figure: simple clean black outlines, flat vibrant colors, minimal black dot eyes, simple brow lines for expression, smooth 2D vector animation. No realistic fur texture, no detailed irises.

COMPOSITION (16:9): stage action across left, center and right thirds. The throne rock stands at center; the green hills lie off to the right. Use lateral tracking, deliberate negative space in the upper-left area, and keep screen direction consistent: anyone leaving the kingdom moves toward the right.

FIRST FRAME: The stick figure gripping the glowing brass lever beside the dry kingdom.

TIMED ACTION:
[0-3s] The stick figure yanks the lever hard; the sky streaks with fast-moving clouds as years pass in a few seconds.
[3-7s] Scar is now old: the same lean dark-brown lion with the scar across his left eye, his black mane streaked with grey and his body thinner; he sits alone on the summit.
[7-10s] Dust swirls around him in grey-violet dusk light; slow push-in on his still, lonely silhouette.

NARRATION (audio voiceover only, strictly no speech bubbles, no dialogue boxes): "Ten years later. Scar still sits on Pride Rock. Technically, he is king. King of dust, wind, and silence." Speak exactly these words once, in this order. Do not add, omit, paraphrase, repeat or reorder words, and do not show them as captions, subtitles or any visible text. No animal or character speaks or lip-syncs.

VOICE: One off-screen adult male narrator throughout. General American accent, warm clean baritone, medium-low pitch, gentle chest resonance, no raspiness or breathiness. Calm conversational delivery, restrained pitch variation, steady speaking pace, and close, dry studio sound. Keep the same vocal timbre, register, accent, pace, and recording quality throughout. Emotional progression belongs to the visuals and music; do not change the narrator's voice or switch to character dialogue.

Audio: Voiceover seamlessly continues the identical quiet, thoughtful piano and subtle soft ambient synth from clip 1, maintaining identical tempo, instrumentation, and optimistic narrative momentum. Synchronized crisp SFX on physical actions. SFX: whooshing time-lapse wind, then near silence with a lonely dusty wind. Voice-first mix.

FINAL FRAME: Old Scar's silhouette; camera whip-pans to the right.

Negative constraints: no photorealistic human skin or faces, no 3D humanoid CGI uncanny valley models, no chaotic line glitches, no speech bubbles, no dialogue text boxes. No visible words, letters, numbers, captions, subtitles, logos or watermarks; books, signs and crowns stay blank or icon-only. No blood, gore or injury. No realistic animal fur or photorealistic animals. No extra limbs, no pom-pom on the beanie, no missing t-shirt, no costume changes, no extra characters, no abstract liquid or shape morphing.
```

## Đoạn 14
**Ảnh tham chiếu cần đính kèm:** zeke.png, nala.png, lioness.png, cub.png

```text
OUTPUT: A stickman animated video, approximately 10 seconds, 16:9 landscape, 720p target, 24 FPS, synchronized audio. Rapid scene changes and frequent visual events, while preserving an identical stick-figure design, constant line weight, and strict temporal consistency.

ENVIRONMENT: in a rich full-color cinematic environment: a vast African savanna with tall grass, flat-topped acacia trees and one towering jutting rock outcrop that serves as the king's throne. Cinematic volumetric lighting, soft depth of field, atmospheric narrative mood. Lighting and palette for this clip: Fresh green palette, warm late-afternoon sunlight.

CHARACTERS:
The same minimalist 2D animated stick figure in a bright red beanie and yellow shirt... Simple black lines, vibrant colors, smooth 2D animation style. Hollow circular head with minimal dot eyes only; he is a silent time-travelling observer and never speaks.
NALA (lioness leader): a sleek adult lioness with pale cream-gold fur, a small notch cut into the tip of her left ear, minimal black dot eyes under a calm steady brow line, no mane. Four legs, no clothing.
LIONESSES (uniform group, identical design): sleek sandy-gold lionesses with minimal black dot eyes, no manes and no ear notches.
LION CUBS (uniform group): small round sandy-gold lion cubs with minimal black dot eyes.
All animals share the same drawing style as the stick figure: simple clean black outlines, flat vibrant colors, minimal black dot eyes, simple brow lines for expression, smooth 2D vector animation. No realistic fur texture, no detailed irises.

COMPOSITION (16:9): stage action across left, center and right thirds. The throne rock stands at center; the green hills lie off to the right. Use lateral tracking, deliberate negative space in the upper-left area, and keep screen direction consistent: anyone leaving the kingdom moves toward the right.

FIRST FRAME: A whip-pan arrives on lush green hills on the right side of the kingdom.

TIMED ACTION:
[0-3s] Green rolling hills with flowing streams; Nala's pride rests healthy and strong under a large tree.
[3-7s] Lion cubs tumble and play, chasing butterflies and each other through the grass.
[7-10s] The stick figure lies on his back in the grass nearby, smiling and watching the cubs play.

NARRATION (audio voiceover only, strictly no speech bubbles, no dialogue boxes): "And far away, in the green hills, Nala's pride is thriving. Cubs are born who have never heard Scar's name." Speak exactly these words once, in this order. Do not add, omit, paraphrase, repeat or reorder words, and do not show them as captions, subtitles or any visible text. No animal or character speaks or lip-syncs.

VOICE: One off-screen adult male narrator throughout. General American accent, warm clean baritone, medium-low pitch, gentle chest resonance, no raspiness or breathiness. Calm conversational delivery, restrained pitch variation, steady speaking pace, and close, dry studio sound. Keep the same vocal timbre, register, accent, pace, and recording quality throughout. Emotional progression belongs to the visuals and music; do not change the narrator's voice or switch to character dialogue.

Audio: Voiceover seamlessly continues the identical quiet, thoughtful piano and subtle soft ambient synth from clip 1, maintaining identical tempo, instrumentation, and optimistic narrative momentum. Synchronized crisp SFX on physical actions. SFX: flowing stream, birdsong, playful cub squeaks, butterflies fluttering. Voice-first mix.

FINAL FRAME: A butterfly flies off toward the left, back toward the dry throne rock.

Negative constraints: no photorealistic human skin or faces, no 3D humanoid CGI uncanny valley models, no chaotic line glitches, no speech bubbles, no dialogue text boxes. No visible words, letters, numbers, captions, subtitles, logos or watermarks; books, signs and crowns stay blank or icon-only. No blood, gore or injury. No realistic animal fur or photorealistic animals. No extra limbs, no pom-pom on the beanie, no missing t-shirt, no costume changes, no extra characters, no abstract liquid or shape morphing.
```

## Đoạn 15
**Ảnh tham chiếu cần đính kèm:** zeke.png, scar-old.png

```text
OUTPUT: A stickman animated video, approximately 10 seconds, 16:9 landscape, 720p target, 24 FPS, synchronized audio. Rapid scene changes and frequent visual events, while preserving an identical stick-figure design, constant line weight, and strict temporal consistency.

ENVIRONMENT: in a rich full-color cinematic environment: a vast African savanna with tall grass, flat-topped acacia trees and one towering jutting rock outcrop that serves as the king's throne. Cinematic volumetric lighting, soft depth of field, atmospheric narrative mood. Lighting and palette for this clip: Grey-violet dusk softening into warm amber.

CHARACTERS:
The same minimalist 2D animated stick figure in a bright red beanie and yellow shirt... Simple black lines, vibrant colors, smooth 2D animation style. Hollow circular head with minimal dot eyes only; he is a silent time-travelling observer and never speaks.
SCAR (villain lion): a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, minimal black dot eyes under a narrow sly brow line, and a long thin tail ending in a black tuft. Walks on four legs like a real lion, no clothing.
All animals share the same drawing style as the stick figure: simple clean black outlines, flat vibrant colors, minimal black dot eyes, simple brow lines for expression, smooth 2D vector animation. No realistic fur texture, no detailed irises.

COMPOSITION (16:9): stage action across left, center and right thirds. The throne rock stands at center; the green hills lie off to the right. Use lateral tracking, deliberate negative space in the upper-left area, and keep screen direction consistent: anyone leaving the kingdom moves toward the right.

FIRST FRAME: A butterfly flies in from the right toward the dry throne rock.

TIMED ACTION:
[0-3s] Old Scar (mane streaked with grey, thinner body) watches a dung beetle roll a ball past his paw.
[3-7s] The butterfly and a flock of birds fly past him toward the green hills on the right; his eyes follow them.
[7-10s] Close-up: his narrow brow softens and relaxes for the first time; he breathes out slowly.

NARRATION (audio voiceover only, strictly no speech bubbles, no dialogue boxes): "Here's the twist. Scar finally understands what Mufasa believed: a king is part of the circle of life, not above it." Speak exactly these words once, in this order. Do not add, omit, paraphrase, repeat or reorder words, and do not show them as captions, subtitles or any visible text. No animal or character speaks or lip-syncs.

VOICE: One off-screen adult male narrator throughout. General American accent, warm clean baritone, medium-low pitch, gentle chest resonance, no raspiness or breathiness. Calm conversational delivery, restrained pitch variation, steady speaking pace, and close, dry studio sound. Keep the same vocal timbre, register, accent, pace, and recording quality throughout. Emotional progression belongs to the visuals and music; do not change the narrator's voice or switch to character dialogue.

Audio: Voiceover seamlessly continues the identical quiet, thoughtful piano and subtle soft ambient synth from clip 1, maintaining identical tempo, instrumentation, and optimistic narrative momentum. Synchronized crisp SFX on physical actions. SFX: tiny beetle rolling, wings fluttering, a long slow exhale. Voice-first mix.

FINAL FRAME: Old Scar slowly rising to his feet.

Negative constraints: no photorealistic human skin or faces, no 3D humanoid CGI uncanny valley models, no chaotic line glitches, no speech bubbles, no dialogue text boxes. No visible words, letters, numbers, captions, subtitles, logos or watermarks; books, signs and crowns stay blank or icon-only. No blood, gore or injury. No realistic animal fur or photorealistic animals. No extra limbs, no pom-pom on the beanie, no missing t-shirt, no costume changes, no extra characters, no abstract liquid or shape morphing.
```

## Đoạn 16
**Ảnh tham chiếu cần đính kèm:** zeke.png, scar-old.png

```text
OUTPUT: A stickman animated video, approximately 10 seconds, 16:9 landscape, 720p target, 24 FPS, synchronized audio. Rapid scene changes and frequent visual events, while preserving an identical stick-figure design, constant line weight, and strict temporal consistency.

ENVIRONMENT: in a rich full-color cinematic environment: a vast African savanna with tall grass, flat-topped acacia trees and one towering jutting rock outcrop that serves as the king's throne. Cinematic volumetric lighting, soft depth of field, atmospheric narrative mood. Lighting and palette for this clip: Warm amber light, long shadows.

CHARACTERS:
The same minimalist 2D animated stick figure in a bright red beanie and yellow shirt... Simple black lines, vibrant colors, smooth 2D animation style. Hollow circular head with minimal dot eyes only; he is a silent time-travelling observer and never speaks.
SCAR (villain lion): a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, minimal black dot eyes under a narrow sly brow line, and a long thin tail ending in a black tuft. Walks on four legs like a real lion, no clothing.
All animals share the same drawing style as the stick figure: simple clean black outlines, flat vibrant colors, minimal black dot eyes, simple brow lines for expression, smooth 2D vector animation. No realistic fur texture, no detailed irises.

COMPOSITION (16:9): stage action across left, center and right thirds. The throne rock stands at center; the green hills lie off to the right. Use lateral tracking, deliberate negative space in the upper-left area, and keep screen direction consistent: anyone leaving the kingdom moves toward the right.

FIRST FRAME: Old Scar rising to his feet on the summit.

TIMED ACTION:
[0-3s] Old Scar (mane streaked with grey, thinner body) steps slowly down the rocky slope of the throne rock.
[3-7s] Lateral tracking shot: he walks alone across the dry plain toward the right.
[7-10s] The stick figure follows him quietly at a distance, hands in pockets, matching his pace.

NARRATION (audio voiceover only, strictly no speech bubbles, no dialogue boxes): "So old Scar does something no one expects. He walks down from Pride Rock, alone, toward the hills." Speak exactly these words once, in this order. Do not add, omit, paraphrase, repeat or reorder words, and do not show them as captions, subtitles or any visible text. No animal or character speaks or lip-syncs.

VOICE: One off-screen adult male narrator throughout. General American accent, warm clean baritone, medium-low pitch, gentle chest resonance, no raspiness or breathiness. Calm conversational delivery, restrained pitch variation, steady speaking pace, and close, dry studio sound. Keep the same vocal timbre, register, accent, pace, and recording quality throughout. Emotional progression belongs to the visuals and music; do not change the narrator's voice or switch to character dialogue.

Audio: Voiceover seamlessly continues the identical quiet, thoughtful piano and subtle soft ambient synth from clip 1, maintaining identical tempo, instrumentation, and optimistic narrative momentum. Synchronized crisp SFX on physical actions. SFX: slow heavy paw steps on stones and dry grass, soft wind. Voice-first mix.

FINAL FRAME: Old Scar approaching the edge where dry land meets green grass.

Negative constraints: no photorealistic human skin or faces, no 3D humanoid CGI uncanny valley models, no chaotic line glitches, no speech bubbles, no dialogue text boxes. No visible words, letters, numbers, captions, subtitles, logos or watermarks; books, signs and crowns stay blank or icon-only. No blood, gore or injury. No realistic animal fur or photorealistic animals. No extra limbs, no pom-pom on the beanie, no missing t-shirt, no costume changes, no extra characters, no abstract liquid or shape morphing.
```

## Đoạn 17
**Ảnh tham chiếu cần đính kèm:** zeke.png, scar-old.png, nala.png, lioness.png, cub.png

```text
OUTPUT: A stickman animated video, approximately 10 seconds, 16:9 landscape, 720p target, 24 FPS, synchronized audio. Rapid scene changes and frequent visual events, while preserving an identical stick-figure design, constant line weight, and strict temporal consistency.

ENVIRONMENT: in a rich full-color cinematic environment: a vast African savanna with tall grass, flat-topped acacia trees and one towering jutting rock outcrop that serves as the king's throne. Cinematic volumetric lighting, soft depth of field, atmospheric narrative mood. Lighting and palette for this clip: Warm orange sunset palette, green hills glowing.

CHARACTERS:
The same minimalist 2D animated stick figure in a bright red beanie and yellow shirt... Simple black lines, vibrant colors, smooth 2D animation style. Hollow circular head with minimal dot eyes only; he is a silent time-travelling observer and never speaks.
SCAR (villain lion): a lean, bony adult male lion with dark brown fur, a thin shaggy black mane, one diagonal scar line across his left eye, minimal black dot eyes under a narrow sly brow line, and a long thin tail ending in a black tuft. Walks on four legs like a real lion, no clothing.
NALA (lioness leader): a sleek adult lioness with pale cream-gold fur, a small notch cut into the tip of her left ear, minimal black dot eyes under a calm steady brow line, no mane. Four legs, no clothing.
LIONESSES (uniform group, identical design): sleek sandy-gold lionesses with minimal black dot eyes, no manes and no ear notches.
LION CUBS (uniform group): small round sandy-gold lion cubs with minimal black dot eyes.
All animals share the same drawing style as the stick figure: simple clean black outlines, flat vibrant colors, minimal black dot eyes, simple brow lines for expression, smooth 2D vector animation. No realistic fur texture, no detailed irises.

COMPOSITION (16:9): stage action across left, center and right thirds. The throne rock stands at center; the green hills lie off to the right. Use lateral tracking, deliberate negative space in the upper-left area, and keep screen direction consistent: anyone leaving the kingdom moves toward the right.

FIRST FRAME: Old Scar approaching the border where dry land meets green grass.

TIMED ACTION:
[0-3s] Old Scar (mane streaked with grey, thinner body) stops exactly at the line where the dry ground turns green.
[3-7s] In the distance Nala's pride and cubs rest peacefully; Nala lifts her head and sees him, calm and still.
[7-10s] Scar does not step forward; he lowers his head slightly and sits down at the border as the orange sunset glows.

NARRATION (audio voiceover only, strictly no speech bubbles, no dialogue boxes): "He didn't lose to a hero. He lost to the one thing he never respected: everyone who quietly kept the kingdom alive." Speak exactly these words once, in this order. Do not add, omit, paraphrase, repeat or reorder words, and do not show them as captions, subtitles or any visible text. No animal or character speaks or lip-syncs.

VOICE: One off-screen adult male narrator throughout. General American accent, warm clean baritone, medium-low pitch, gentle chest resonance, no raspiness or breathiness. Calm conversational delivery, restrained pitch variation, steady speaking pace, and close, dry studio sound. Keep the same vocal timbre, register, accent, pace, and recording quality throughout. Emotional progression belongs to the visuals and music; do not change the narrator's voice or switch to character dialogue.

Audio: Voiceover seamlessly continues the identical quiet, thoughtful piano and subtle soft ambient synth from clip 1, maintaining identical tempo, instrumentation, and optimistic narrative momentum. Synchronized crisp SFX on physical actions. SFX: evening crickets, gentle breeze, a distant soft lion call. Voice-first mix.

FINAL FRAME: The stick figure walks past Scar back toward the empty throne rock, paper crown in hand.

Negative constraints: no photorealistic human skin or faces, no 3D humanoid CGI uncanny valley models, no chaotic line glitches, no speech bubbles, no dialogue text boxes. No visible words, letters, numbers, captions, subtitles, logos or watermarks; books, signs and crowns stay blank or icon-only. No blood, gore or injury. No realistic animal fur or photorealistic animals. No extra limbs, no pom-pom on the beanie, no missing t-shirt, no costume changes, no extra characters, no abstract liquid or shape morphing.
```

## Đoạn 18
**Ảnh tham chiếu cần đính kèm:** zeke.png

```text
OUTPUT: A stickman animated video, approximately 10 seconds, 16:9 landscape, 720p target, 24 FPS, synchronized audio. Rapid scene changes and frequent visual events, while preserving an identical stick-figure design, constant line weight, and strict temporal consistency.

ENVIRONMENT: in a rich full-color cinematic environment: a vast African savanna with tall grass, flat-topped acacia trees and one towering jutting rock outcrop that serves as the king's throne. Cinematic volumetric lighting, soft depth of field, atmospheric narrative mood. Lighting and palette for this clip: Golden-orange sunset turning to dusk, dry rock on the left and green hills on the right.

CHARACTERS:
The same minimalist 2D animated stick figure in a bright red beanie and yellow shirt... Simple black lines, vibrant colors, smooth 2D animation style. Hollow circular head with minimal dot eyes only; he is a silent time-travelling observer and never speaks.
All animals share the same drawing style as the stick figure: simple clean black outlines, flat vibrant colors, minimal black dot eyes, simple brow lines for expression, smooth 2D vector animation. No realistic fur texture, no detailed irises.

COMPOSITION (16:9): stage action across left, center and right thirds. The throne rock stands at center; the green hills lie off to the right. Use lateral tracking, deliberate negative space in the upper-left area, and keep screen direction consistent: anyone leaving the kingdom moves toward the right.

FIRST FRAME: The stick figure walking toward the empty throne rock holding the blank paper crown.

TIMED ACTION:
[0-3s] The stick figure climbs the empty throne rock and gently places the blank paper crown on the summit.
[3-7s] He turns toward the camera and gives a big exaggerated shrug.
[7-10s] The camera cranes high into an aerial view: the bare throne rock on the left, the glowing green hills on the right, under a fading sunset.

NARRATION (audio voiceover only, strictly no speech bubbles, no dialogue boxes): "Winning the throne was easy. Keeping a kingdom was impossible. So, was Scar a villain, or just a terrible boss? Tell me below." Speak exactly these words once, in this order. Do not add, omit, paraphrase, repeat or reorder words, and do not show them as captions, subtitles or any visible text. No animal or character speaks or lip-syncs.

VOICE: One off-screen adult male narrator throughout. General American accent, warm clean baritone, medium-low pitch, gentle chest resonance, no raspiness or breathiness. Calm conversational delivery, restrained pitch variation, steady speaking pace, and close, dry studio sound. Keep the same vocal timbre, register, accent, pace, and recording quality throughout. Emotional progression belongs to the visuals and music; do not change the narrator's voice or switch to character dialogue.

Audio: Voiceover seamlessly continues the identical quiet, thoughtful piano and subtle soft ambient synth from clip 1, maintaining identical tempo, instrumentation, and optimistic narrative momentum. Synchronized crisp SFX on physical actions. SFX: paper rustle, soft wind, music resolving to a gentle final note. Voice-first mix.

FINAL FRAME: Wide aerial view held for a calm ending.

Negative constraints: no photorealistic human skin or faces, no 3D humanoid CGI uncanny valley models, no chaotic line glitches, no speech bubbles, no dialogue text boxes. No visible words, letters, numbers, captions, subtitles, logos or watermarks; books, signs and crowns stay blank or icon-only. No blood, gore or injury. No realistic animal fur or photorealistic animals. No extra limbs, no pom-pom on the beanie, no missing t-shirt, no costume changes, no extra characters, no abstract liquid or shape morphing.
```

---

# PHẦN 3: Ghép video

| Nối | Điểm chuyển cảnh |
|---|---|
| 1 → 2 | Zeke cầm cần gạt, sang cảnh tấm rèm sân khấu |
| 2 → 3 | Zeke ngồi xuống với cuốn sách ảnh |
| 3 → 4 | Lật trang, mỏm đá lúc chạng vạng |
| 4 → 5 | Scar một mình, trời sáng dần (Ngày 1) |
| 5 → 6 | Bầy linh cẩu dưới chân đá |
| 6 → 7 | Zeke nhặt vương miện giấy |
| 7 → 8 | Nala nhìn về phía mỏm đá |
| 8 → 9 | Camera ngửa lên bầu trời khô |
| 9 → 10 | Zeke hạ ô, nhìn ra biên giới |
| 10 → 11 | Hàng rào gai, đêm chuyển sang bình minh |
| 11 → 12 | Chỗ nằm trống của bầy sư tử cái |
| 12 → 13 | Zeke nắm cần gạt, **nhảy 10 năm** |
| 13 → 14 | Lia nhanh sang đồi xanh bên phải |
| 14 → 15 | Con bướm bay về phía mỏm đá |
| 15 → 16 | Scar già đứng dậy |
| 16 → 17 | Scar đến ranh giới đất khô và cỏ xanh |
| 17 → 18 | Zeke cầm vương miện quay về mỏm đá |

- Cắt bớt 0,2–0,5 giây ở chỗ nối, cho âm thanh mờ dần khoảng 0,3 giây.
- **Chữ chèn (tùy chọn):** "VILLAIN WINS" ở đoạn 1 · "DAY 1" ở đoạn 5 · "DAY 2" ở đoạn 6 · "MONTH 6" ở đoạn 9 · "YEAR 1" ở đoạn 11 · "10 YEARS LATER" ở đoạn 13. Đặt ở góc trên bên trái.
- Phụ đề tiếng Anh: bật tự động trong CapCut, hoặc nhờ mình làm.

# PHẦN 4: Lưu ý về giọng đọc và nhạc
- Cả 18 prompt dùng chung một khối giọng giống hệt nhau. Hãy **nghe** các đoạn liền nhau để kiểm tra.
- Đoạn nào giọng hoặc nhạc lệch thì chỉ tạo lại đoạn đó. Nếu vẫn lệch nhiều, có thể tắt tiếng Flow và lồng một bản giọng đọc liền mạch khi dựng.
