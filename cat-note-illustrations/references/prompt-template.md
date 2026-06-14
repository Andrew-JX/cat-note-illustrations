# 生图提示词模板

每张图单独生成。根据正文内容替换变量，不要把多张图拼在一起。默认主角始终是 Specimen 0 双色猫，除非用户明确要求多只猫或换猫型。

```text
Generate one standalone 16:9 horizontal Chinese article illustration.

Core visual style:
Journal sticker style mixed with modern simple cute comic style. Clean white or near-white background. Medium-thick uneven hand-drawn black ink outline, closed sticker-like cutout shapes, rounded line ends, slightly damp pen feel. Low-saturation warm flat colors with very subtle recycled-paper or colored-pencil grain inside the colored areas. Minimal shadows only in ears, tongue, or fur patch edges. No watercolor bleeding, no pixel art, no 3D, no glossy vector mascot, no product sketch, no PPT infographic, no catalog/specification sheet.

Default recurring character, mandatory:
Use Specimen 0 as the main cat, not a generic cat. Specimen 0 is a short-haired bicolor cow-pattern cat: warm white body, irregular dark brown/black-gray patches on the crown/ears, one dark patch on the back, mostly dark tail. Very large yellow irises with narrow vertical black slit pupils are the soul of the character. The eyes feel blank, hyper-aware, deadpan, and funny, like the cat has emptied its brain but sees everything. Small pale pink nose, hidden mouth unless licking paw, optional tiny pink tongue, short straight black whiskers. Triangular ears with soft pink inner ears. Body is loose and slightly awkward, not a round chibi mascot.

Theme:
{正文配图主题}

Structure type:
{结构类型：Workflow / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core idea:
{这张图要表达的核心意思}

Composition:
{具体画面：Specimen 0 在哪里、正在做什么、主要物件是什么、信息如何流动。让猫用爪子、尾巴、嘴巴或身体承担核心动作。}

Suggested elements:
{元素1} / {元素2} / {元素3} / {元素4}

Chinese labels, only if useful:
{标注词1} / {标注词2} / {标注词3} / {可选标注词4}

Color use:
Warm white body. Dark brown, black-gray, or olive-brown patches on crown, ears, back, and tail. Yellow eyes with thin vertical black slit pupils. Soft pale pink for inner ears, tiny nose, tongue, or optional paw pads. Muted earth tones only. Use soft orange/blue/red only for tiny article annotations if necessary.

Constraints:
One image explains only one core structure. Keep the main subject around 35%-60% of the canvas. Preserve generous blank space. Use at most 3-5 short Chinese labels, each 2-6 characters. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, dense infographic, UI screenshot, character reference sheet, cross-section view, stamp catalogue, or English specification poster. Do not generate random cat breeds. Do not make a round chibi/kawaii mascot. Do not copy reference poses; preserve the character DNA: bicolor patches, yellow slit eyes, thick hand-drawn outline, loose awkward posture, subtle flat-fill texture.
```

## 图像编辑提示

修正为 Specimen 0：

```text
Edit the provided image while preserving the same composition and meaning. Replace the cat with Specimen 0: warm white short-haired bicolor cat, irregular dark crown/ear patch, one dark back patch, mostly dark tail, very large yellow eyes with thin vertical black slit pupils, tiny pale pink nose, short straight whiskers, triangular ears with soft pink inner ears, thick uneven hand-drawn black outline, muted flat colors with subtle colored-pencil grain. Avoid round chibi mascot proportions. Preserve background, layout, labels, and aspect ratio.
```

增强猫猫参与感：

```text
Regenerate this illustration with the same core meaning and simple layout, but make Specimen 0 central to the conceptual action. The bicolor yellow-eyed slit-pupil cat should push, hold, lick, bite, drag, connect, block, sort, or unfold the key object so the idea is visible through its action. Keep journal sticker style, thick uneven black outline, muted warm flat colors, subtle fill texture, clean white background.
```