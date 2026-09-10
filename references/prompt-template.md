# 生图提示词模板

每张图单独生成。根据正文内容替换变量，不要把多张图拼在一起。

```text
Generate one standalone 16:9 horizontal Chinese article illustration.

Visual DNA:
Pure white background. Colorful Chinese sticker-style hand-drawn illustration, not black-and-white line art. Use 小刘鸭's original palette: white duck body, orange-yellow beak and feet, soft gray/black thin outlines, low-saturation yellow/green/blue/pink/orange props and grounding blocks. Slightly wobbly pen lines. Lots of empty white space. Sparse handwritten Chinese annotations. Clean funny article-illustration feeling. No gradients, no shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no children's poster, no realistic UI.

Recurring IP character required:
Match the provided 小刘鸭 reference character exactly. 小刘鸭 is NOT a realistic duck and NOT a newly designed generic duck mascot. 小刘鸭 has a simple white rounded bean-shaped body with no separate neck, no feathers, no tail, and no realistic wings. The face has two oversized round eyes with tiny black pupils, and a small orange-yellow flat beak patch placed in the lower middle of the face. Use a thin gray/black wobbly outline. Tiny line-like arms and tiny feet only when needed. Keep the same sticker-emoticon proportions, expression language, and color palette from the reference. 小刘鸭 must perform the core conceptual action, not decorate the scene. Make 小刘鸭 funny, earnest, slightly awkward, warm, and emotionally expressive, but do not redesign the character. Optional side character only when useful: 鼻孔喵, a round white cat-like companion with tiny ears and a deadpan face.

Theme:
{正文配图主题}

Structure type:
{结构类型：Workflow / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core idea:
{这张图要表达的核心意思}

Composition:
{具体画面：小刘鸭在哪里、正在做什么、主要物件是什么、信息如何流动}

Suggested elements:
{元素1} / {元素2} / {元素3} / {元素4}

Chinese handwritten labels:
{标注词1} / {标注词2} / {标注词3} / {标注词4} / {可选标注词5}

Color use:
Use 小刘鸭 IP colors, not black-and-white. White for 小刘鸭's body. Orange-yellow for 小刘鸭's beak and feet. Thin gray/black only for outlines, eyes, small text, and necessary structure lines. Pale yellow, mint green, light blue, soft pink, and warm orange for props, chairs, desks, speech bubbles, grounding blocks, and small emotional accents. Orange for main flow/path/arrows. Red/pink only for key warnings/problems/results/emotional emphasis. Blue only for secondary notes or feedback/system state.

Constraints:
One image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank white space. Use at most 5-8 short handwritten Chinese labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it black-and-white line art, a formal diagram, course slide, dense explainer, sticker sheet, or meme collage. Do not turn 小刘鸭 into a real duck, bird, goose, penguin, or generic mascot. Do not add a long neck, pointed beak, feathers, tail, realistic duck feet, complex clothes, or new facial design. Do not copy existing 小刘鸭 sticker compositions, captions, poses, or props exactly; invent a fresh visual metaphor for this specific article while preserving the exact character identity. It should be clear but not instructional, funny but not childish, expressive but clean.
```

## 图像编辑提示

去掉左上角标题：

```text
Edit the provided image. Remove only the handwritten title "{要删除的文字}" and its underline from the top-left corner. Fill that area with the same clean white background, matching the surrounding blank paper. Preserve everything else exactly: characters, labels, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

增强小刘鸭参与感：

```text
Regenerate this illustration with the same core meaning and simple layout, but make 小刘鸭 more central to the conceptual action. Match the provided 小刘鸭 reference character exactly: white rounded bean-shaped body, no separate neck, oversized round eyes, tiny black pupils, small orange-yellow flat beak patch in the lower middle of the face, thin gray/black outline, tiny line-like arms and tiny feet only when needed. Use low-saturation yellow/green/blue/pink/orange props, clean sparse hand-drawn sticker style, and pure white background. Do not make it black-and-white. Do not turn 小刘鸭 into a realistic duck or redesigned duck mascot.
```
