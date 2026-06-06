# 生图提示词模板（不二版）

每张图单独生成。根据正文内容替换变量，不要把多张图拼在一起。必须附带参考图。

```text
Generate one standalone 16:9 horizontal Chinese article illustration. Match the EXACT same art style as the reference image provided.

Visual style (CRITICAL — match the reference):
- Pure white background
- Warm crayon/marker texture fills — all colored areas have visible diagonal hatching strokes, NOT flat solid fills
- Thick dark blue outlines (2-3px) with hand-drawn wobble
- Children's picture-book illustration feeling: warm, cute, textured, hand-colored
- Color blocks are filled with visible crayon/marker strokes showing texture

IP Character 不二 (MUST match reference exactly):
- Fluffy voluminous shoulder-length wavy/curly LIGHT BLUE hair, flipping outward on both sides like petals/wings
- Hair has internal fine lines showing strand direction + crayon texture fill
- Red butterfly bow on top center (with hatching texture)
- Round black-framed glasses
- Large round eyes: white sclera + ORANGE-YELLOW pupils + highlight dots
- Small dot nose, tiny smile or "o" mouth
- Orange circle blush on cheeks
- Yellow A-line sleeveless dress (with crayon hatching texture inside)
- Simplified round ball hands
- Red round shoes (with texture)
- Head-to-body ratio about 1:1.3
- Peach/light skin tone

Theme: {正文配图主题}

Core idea: {这张图要表达的核心意思}

Composition: {具体画面：不二在哪里、正在做什么、主要物件是什么}

Chinese handwritten labels: {标注词1} / {标注词2} / {标注词3}

Constraints: Match reference art style exactly. One concept per image. 40-60% of canvas for subject. 35%+ white space. No title top-left. No PPT look. No gradient/shadow. All color fills MUST have crayon texture hatching.
```

## 关键注意

- **必须附带参考图**：每次生成都要带一张已确认风格的参考图作为reference_image，否则风格会跑偏。
- **蜡笔纹理是核心**：如果生成出来是纯色平涂，说明prompt没生效，需要强调 "crayon/marker texture fills with visible diagonal hatching strokes"。
- **不是极简线条**：这个风格有饱满的色块填充，不是小黑那种黑白极简线条。
