# 生图提示词模板（不二版）

每张图单独生成。根据正文内容替换变量，不要把多张图拼在一起。

```text
Generate one standalone 16:9 horizontal Chinese article illustration.

Visual DNA:
Pure white background. Hand-drawn line art with thick colored outlines (dark blue or orange, 2-3px). Slightly wobbly pen lines with hand-drawn feel. Lots of empty white space. Sparse handwritten Chinese annotations in red/orange/blue. Clean, cute but absurd product-sketch feeling. Warm color palette (blue, yellow, red, orange). No gradients, no shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no children's illustration, no realistic UI.

Recurring IP character required:
不二 (Buer), a small cute chibi girl character with: large fluffy blue curly hair (half-sphere shape covering both sides of head), red butterfly bow on top of head, round glasses with dark blue frames, orange circle blush on cheeks, tiny "o" shaped mouth, pale skin face, yellow triangle/trapezoid dress, simple line-art limbs, red round shoes. Head-to-body ratio about 1:1.1. Thick dark blue or orange outline with hand-drawn wobble. 不二 must perform the core conceptual action, not decorate the scene. Make her serious and focused while doing something slightly absurd — cute but not trying to be cute, a bit silly but earnest.

Theme:
{正文配图主题}

Structure type:
{结构类型：Workflow / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core idea:
{这张图要表达的核心意思}

Composition:
{具体画面：不二在哪里、正在做什么、主要物件是什么、信息如何流动}

Suggested elements:
{元素1} / {元素2} / {元素3} / {元素4}

Chinese handwritten labels:
{标注词1} / {标注词2} / {标注词3} / {标注词4} / {可选标注词5}

Color use:
Dark blue for main outlines, 不二's hair and glasses frames. Yellow for 不二's dress and secondary fills. Red/orange for bow, key warnings, main flow/arrows/paths. Light blue for secondary notes or system state.

Constraints:
One image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank white space. Use at most 5-8 short handwritten Chinese labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, or dense explainer. Do not copy prior examples or reuse known case compositions unless explicitly requested; invent a fresh visual metaphor for this specific article. It should be cute but not saccharine, absurd but clean, silly but structurally clear.
```

## 图像编辑提示

去掉左上角标题：

```text
Edit the provided image. Remove only the handwritten title "{要删除的文字}" from the top-left corner. Fill that area with the same clean white background. Preserve everything else exactly: characters, labels, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

增强不二的参与感：

```text
Regenerate this illustration with the same core meaning and simple layout, but make 不二 more central to the conceptual action. 不二 should be doing the strange work that explains the idea, not standing beside the diagram. Keep it clean, sparse, hand-drawn, cute but absurd.
```
