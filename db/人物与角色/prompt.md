# 人物与角色 — 提示词合集


> 32 个案例

---


## 例 27：人物角色设定图

**来源：** [@anemone\_sd](https://x.com/anemone_sd)

![case27.jpg](images/case27.jpg)


```text
{
  "type": "collection of instant photos",
  "setting": "laid out flat on a white fabric surface",
  "character": {
    "hair": "{argument name=\"hair color\" default=\"long pink hair with blue inner color\"}",
    "outfit": "{argument name=\"outfit\" default=\"black and white maid uniform with frilly headband and black ribbons\"}",
    "eyes": "reddish-pink"
  },
  "layout": {
    "arrangement": "two rows of five polaroid photos",
    "count": 10,
    "photos": [
      { "position": "top row 1", "description": "holding a pink heart cushion" },
      { "position": "top row 2", "description": "winking, making a peace sign" },
      { "position": "top row 3", "description": "making a hand heart, pink heart doodle on the bottom border" },
      { "position": "top row 4", "description": "resting chin on hands, gentle smile" },
      { "position": "top row 5", "description": "holding a red rose, winking" },
      { "position": "bottom row 1", "description": "finger to lips, shy expression" },
      { "position": "bottom row 2", "description": "holding a small pink cake" },
      { "position": "bottom row 3", "description": "winking, hand near face, signature '{argument name=\"signature text\" default=\"Hanashi\"}' and heart doodle on border" },
      { "position": "bottom row 4", "description": "holding a pink bunny plushie, sparkle doodles, signature '{argument name=\"signature text\" default=\"Hanashi\"}' and bunny doodle on border" },
      { "position": "bottom row 5", "description": "winking, sparkle doodles, message '{argument name=\"message text\" default=\"いつも応援ありがとう！これからもよろしくね♪\"}' and signature '{argument name=\"signature text\" default=\"Hanashi\"}' on border" }
    ]
  }
}
```


---


## 例 54：人物角色设定图

**来源：** [@fukumy\_ai](https://x.com/fukumy_ai)

![case54.jpg](images/case54.jpg)


```text
{
  "type": "4-panel satirical product advertisement grid",
  "layout": {
    "grid": "2x2",
    "panels": [
      {
        "position": "top-left",
        "product_name": "{argument name=\"top left product name\" default=\"座る石\"}",
        "visual": "man in white shirt and dark pants sitting on a large round stone in a park",
        "catchphrase": "いつでも、どこでも、落ち着ける。",
        "sales_badge": "累計販売数 12,000個 突破!",
        "vertical_text": "公園のベンチが埋まっていた日に。",
        "features_count": 3,
        "features_labels": [
          "重さ約8kgで安定感抜群",
          "底面フェルト加工で傷つけにくい",
          "付属の専用ベルトで持ち運び簡単"
        ],
        "extra_visual": "small inset image of the stone with a leather carrying strap",
        "specs": [
          "耐荷重 150kg",
          "安心の日本製"
        ]
      },
      {
        "position": "top-right",
        "product_name": "{argument name=\"top right product name\" default=\"磨きたくない人の歯ブラシ\"}",
        "visual": "sleek light blue toothbrush angled diagonally on a dark blue background",
        "toothbrush_text": "I don't want to brush my yeeth.",
        "catchphrase": "持っているだけで安心感",
        "vertical_text": "歯を磨く代わりに、これを持つ。",
        "sales_badge": "シリーズ累計販売数 85,000本 突破!",
        "features_count": 3,
        "features_labels": [
          "気持ちを落ち着けるお守り代わりに",
          "会議や商談前のエチケットに",
          "磨かない選択を、もっと自由に。"
        ],
        "bottom_banner": "歯磨きストレスから、あなたを解放する。"
      },
      {
        "position": "bottom-left",
        "product_name": "{argument name=\"bottom left product name\" default=\"雲の貯金箱\"}",
        "visual": "hand inserting a coin into a fluffy white cloud-shaped piggy bank",
        "catchphrase": "空気より軽い、安心感。",
        "sales_badge": "累計販売数 23,567個 突破!",
        "features_count": 3,
        "features_labels": [
          "ふわふわの触り心地",
          "割れないから安心",
          "インテリアに馴染むデザイン"
        ],
        "color_variants_count": 3,
        "color_variants_labels": [
          "blue",
          "pink",
          "white"
        ],
        "price": "¥2,980 (税込)",
        "bottom_text": "今日から、空に向かってコツコツ貯めよう。"
      },
      {
        "position": "bottom-right",
        "product_name": "{argument name=\"bottom right product name\" default=\"叱ってくれる石\"}",
        "visual": "round stone on a wooden desk with a pen, text written on the stone",
        "stone_text": "{argument name=\"scolding phrase\" default=\"いいかげんやれ\"}",
        "catchphrase": "やる気が出ないあなたへ。",
        "sales_badge": "累計販売数 18,000個 突破!",
        "features_count": 3,
        "features_labels": [
          "見るたびに心を奮い立たせる",
          "厳選された言葉をランダム表示",
          "電池不要、半永久的に叱ってくれる"
        ],
        "phrase_variants_count": 10,
        "phrase_variants_labels": [
          "甘えるな",
          "考えるな",
          "動け",
          "現実を見ろ",
          "逃げるな",
          "寝るな",
          "やればできる",
          "お前ならできる",
          "寝るな",
          "もう言い訳するな"
        ],
        "price": "¥3,500 (税込)"
      }
    ]
  }
}
```


---


## 例 155：人物角色设定图

**来源：** [@wtry1102](https://x.com/wtry1102)

![case155.jpg](images/case155.jpg)


```text
Create {argument name="items" default="fan goods"} for a standard {argument name="character type" default="Vtuber"} in {argument name="style" default="live-action"}
```


---


## 例 162：人物角色设定图

**来源：** [@nicdunz](https://x.com/nicdunz)

![case162.jpg](images/case162.jpg)


```text
{argument name="voice" default="chatgpt voice"} if it were a character
```


---


## 例 166：十二黄金圣斗士卡牌合集

**来源：** [@songguoxiansen](https://x.com/songguoxiansen/status/2046476566537080849)

![case166.jpg](images/case166.jpg)


```text
[中文]
生成圣斗士星矢12个黄金圣斗士的12宫格卡牌图片，每张卡牌上写上对应的中文名，每行4个，宽高比16:9。

[English]
Generate a 12-grid card image of the 12 Gold Saints from Saint Seiya, with the corresponding Chinese name written on each card, 4 per row, aspect ratio 16:9.
```


---


## 例 271：人物角色设定图

**来源：** [@tsubaki\_ew](https://x.com/tsubaki_ew/status/2045259289993048284)

![case271.jpg](images/case271.jpg)


```text
[中文]
お借りして噂のGPT-Image-2でキャラシート作ってみましたｽｺﾞｯ(๑°ㅁ°๑)‼✧更に色々指示してあげたらもっといい感じになりそう✨キャラは以前チャッピーにお願いして描いて貰った我が分身です( *¯ ꒳¯*)

[English]
I borrowed it and tried making a character sheet using the rumored GPT-Image-2 Awesome(๑°ㅁ°๑)‼✧ It seems like it would turn out even better if I gave it various more instructions✨ The character is my alter ego that I asked Chappy to draw for me before( *¯ ꒳¯*) #GPTimage #AIgenerated
```


---


## 例 290：古风诗人镭射典藏卡牌

**来源：** [@TanShilong](https://x.com/TanShilong/status/2045435090923356415)

![case290.jpg](images/case290.jpg)


```text
[中文]
为中国古代诗人设计一套游戏卡片，并按照SSR SR R 分级，重点卡片有放大展示的效果，包括卡面设计和人物介绍，有很高级的游戏卡片质感，稀有卡片还会有特色的光影例如镭射效果 需要有套卡设计和技能设计，并附带较为详细的说明

[English]
Design a set of game cards for ancient Chinese poets, classified by SSR SR R grades, with key cards having an enlarged display effect, including card face design and character introduction, having a very high-end game card texture, rare cards will also have special light and shadow effects such as holographic laser effects, requiring set card design and skill design, along with relatively detailed descriptions
```


---


## 例 306：官方角色设定资料卡

**来源：** [@MANISH1027512](https://x.com/MANISH1027512/status/2045013913901867334)

![case306.jpg](images/case306.jpg)


```text
[中文]
基于此角色和背景，请制作一份类似官方设定资料的角色资料卡。
・包含三视图：正面、侧面和背面
・添加角色面部表情的变化・分解并展示服装和装备的详细部分
・添加色板・包含世界观设定的简要说明
・总体上，使用有组织的布局（白色背景，插画风格）

[English]
Based on this character and background, please create a character reference sheet similar to official setting materials.
・Includes three-view drawings: front view, side view, and back view
・Add variations of the character's facial expressions
・Break down and display detailed parts of the clothing and equipment
・Add a color palette
・Include a brief explanation of the worldview setting
・Overall, use an organized layout (white background, illustration style)
```


---


## 例 347：4×4 动作分解参考表

**来源：** [@oggii_0](https://x.com/oggii_0/status/2048614158699217302)

![case347.jpg](images/case347.jpg)


```text
[STYLE]
Monochrome grayscale illustration, 3D-rendered character, clean instructional reference sheet, white background, comic-style cell grid layout, technical diagram aesthetic.

[LAYOUT]
4×4 grid layout with a total of 16 panels. Each panel is separated by thin black border lines. Cells are numbered from 1 to 16, with consistent panel sizes.

[CHARACTER]
image1 (the same character appears consistently in all panels)

[PANEL STRUCTURE – per cell]
Top-left: bold number badge + English title text
Center: full-body character pose illustration
Bottom-left: English description text (3–4 lines)
Overlay: directional arrows indicating movement

[ARROWS / MOTION INDICATORS]
Curved arrows, straight arrows, and circular rotation indicators placed around the character to show motion flow and direction.

[RENDERING STYLE]
Highly detailed 3D sculpted style, soft studio lighting, subtle shadows, no color, grayscale shading, clean linework, game concept art quality.

[NEGATIVE]
No background scenery, no color tones, no additional characters, no complex background.
```


## 例 348：A mecha girl mid-teens, pale skin smudged with soot and salt spray, sharp amber ...

**来源：** [@old_pgmrs_will](https://x.com/old_pgmrs_will/status/2046144801071079612)

```text
A mecha girl mid-teens, pale skin smudged with soot and salt spray, sharp amber eyes with glowing HUD reticles, waist-length ash-white hair tied in a high ponytail whipping in the sea wind, matte gunmetal exoskeleton armor plating her shoulders, forearms and shins, exposed hydraulic pistons at the joints, chest rig with glowing cyan coolant lines, oversized oil-stained hangar jacket half slipping off one shoulder, a massive rail cannon resting on her right shoulder, dog tags and frayed red ribbon at her collar , standing off-center to the left on the rusted edge of a tilted steel platform jutting out over dark water, weight shifted onto one leg, left hand gripping the cannon strap, head turned slightly toward camera with a quiet defiant stare, steam venting from her back thrusters, her ponytail and jacket streaming sideways in the salt wind , a vast derelict sea-city at dusk, colossal megastructures of unknown purpose rising from the ocean in staggered silhouettes, bone-white monolithic towers fused with barnacled steel, cyclopean ring-shaped constructs canted at broken angles, rusted skeletal gantries threaded with dead cables, dark swells rolling between the pylons, shipwrecks half-swallowed at their feet, thick sea fog clinging to the bases while the upper structures pierce into a bruised sky, scattered faint lights blinking high in the towers like distant eyes , moody low-key lighting, cold teal ambient from the overcast sky, warm amber sodium glow leaking from a distant structure camera-right, hard backlight from a low sun behind the towers carving her silhouette, volumetric god rays cutting through sea mist, wet specular highlights on her armor , 35mm anamorphic lens, slight low angle looking up past her shoulder toward the structures, medium-wide shot, shallow depth of field with foreground rust in soft focus, horizontal lens flares, fine atmospheric haze compressing the distant megastructures into layered silhouettes , cinematic anime key visual, painterly digital illustration with crisp line art, desaturated oceanic palette of teal, bone-white and rust punched by small warm accent lights, film grain, high-contrast editorial poster aesthetic . Format 16:9.
```


---

## 例 349：生成圣斗士星矢12个黄金圣斗士的12宫格卡牌图片，每张卡牌上写上对应的中文名，每行4个，宽高比16:9。

**来源：** [@songguoxiansen](https://x.com/songguoxiansen/status/2046476566537080849)

```text
生成圣斗士星矢12个黄金圣斗士的12宫格卡牌图片，每张卡牌上写上对应的中文名，每行4个，宽高比16:9。
```


---

## 例 350：# 混沌としたメモ書き・記号の集合体からキャラクターの顔を浮かび上がらせるアート...

**来源：** [@loglogrog](https://x.com/loglogrog/status/2046448773162033240)

```text
# 混沌としたメモ書き・記号の集合体からキャラクターの顔を浮かび上がらせるアート

--- スタイル
- 白い紙の上に黒インクで描かれた大量の手書きメモ、数式、記号、ランダムな線。
- 紙いっぱいに散らばる書き殴り風のカオス。
- 所々に赤インクの強調（ライン、塗り潰し、マーカー風の塊）。
- アナログのノート落書きのような質感。

--- 構図
- ランダムなメモや記号が全体を覆い尽くす。
- 黒インクの線や文字の密度が「キャラクターの顔」の位置に集中する。
- 結果として、混沌の中から「与えられたキャラクターの顔のシルエット・表情」がうっすら浮かび上がる。
- 顔は写実的ではなく、カオスの断片が集まって形を成す。

--- 色彩
- モノクロ（黒・白）を主体に構成。
- 赤インクをアクセントとして散発的に配置。
- 彩度は抑えめ、アナログの紙とインク感を重視。

--- 表現要素
- 読めるようで読めない文字列、日本語や英数字が混在。
- 数式記号、矢印、点、斜線、クロス、ドリップ（インクの飛び散り）。
- キャラクターの顔の目や髪の輪郭は、メモや記号の配置の「余白」や「濃淡」で浮かび上がる。

--- 禁止事項
- 顔を直接的に描き込む写実ポートレート。
- デジタル処理的で整然とした幾何学模様。
- カラフルな彩色や過飽和表現。
- ロゴ、透かし、人工的なCG感。

--- Definition of Done (DoD)
- 全体は「混沌としたメモ・記号の集合体」として成立している。  
- 与えられたキャラクターの顔が、混沌の濃淡・配置から自然に浮かび上がる。  
- 色はモノクロ＋赤アクセントのみ。  
- 紙とインクの手描き的質感を保持している。
```


---

## 例 351：Professional Dark-Background LinkedIn Portrait

**来源：** awesome-gpt-image-2

```text
A polished studio head-and-shoulders LinkedIn profile portrait of a {argument name="subject gender" default="man"} centered in frame, facing straight toward the camera with a neutral, confident expression, cropped from the upper chest to just above the head. He has short {argument name="hair color" default="dark brown"} hair with a slightly textured top, visible ears, and light stubble beard along the jaw and chin. He wears 2 clothing layers: a dark charcoal tailored blazer over a plain white crew-neck t-shirt. The background is a deep black seamless studio backdrop with a subtle soft vignette and no visible props. Use professional corporate portrait photography styling, soft directional key light from above and slightly to one side, gentle rim separation on the shoulders and hair, realistic skin texture, sharp focus on clothing and neck, shallow depth of field, high contrast, clean premium retouching, natural color grading, and a modern executive-yet-approachable look suitable for a {argument name="platform" default="LinkedIn"} profile photo. Compose it symmetrically, minimal and elegant, with the subject isolated against the dark background, photographed as if with an 85mm lens in a high-end studio.
```


---

## 例 352：Enhance Blurry Kitten Photo

**来源：** awesome-gpt-image-2

```text
Using REFERENCE_0, restore the same kitten into a clean, realistic high-resolution portrait while preserving the front-facing composition, white fur with gray-brown markings on the head, blue background, and the beige foreground ledge at the bottom. Sharpen the face and eyes, add natural fur detail and whiskers, correct the proportions into a believable young kitten, improve lighting and contrast, and remove the heavy blur/noise so it looks like a crisp DSLR-style pet photo with shallow depth of field.
```


---

## 例 353：Miss Fortune Realistic Selfie Prompt

**来源：** awesome-gpt-image-2

```text
{argument name="character" default="league of legends miss fortune"} taking a selfie real world style
```


---

## 例 354：3D Vampire Gaming Character

**来源：** awesome-gpt-image-2

```text
this {argument name="character" default="highly detailed 3D gaming character"} sitting on a {argument name="seat" default="red velvet chair with a very high back and black wood finish"}, on the right side 6 bars for different {argument name="powers" default="vapire powers"}
```


---

## 例 355：Cute Cat Selfie

**来源：** awesome-gpt-image-2

```text
a {argument name="cat type" default="cute orange and white cat"}, he looks like hes thinking. taking a selfie inside a {argument name="room lighting" default="dramatically lit room dark room"}. the cat has {argument name="facial features" default="big eyes, a chubby face"}, and a happy expression. the image is a wide-angle shot with sharp focus and high resolution, resulting in a high-definition photograph.
```


---

## 例 356：Double Exposure Motion Blur Portrait

**来源：** awesome-gpt-image-2

```text
portrait of a young woman with {argument name="hair color" default="short curly black"} hair and {argument name="skin tone" default="fair"} skin, wearing transparent safety goggles and a {argument name="clothing" default="blue ribbed turtleneck sweater"}, seated in front of a solid azure blue background, double-exposure motion blur effect to the left side of the face, subtle soft reflections on the glasses, cold ambient lighting, high sharpness on facial features with dreamlike blur trail overlaying second face, fashion editorial studio setup, icy color palette, futuristic retro mood.
```


---

## 例 357：Pixar-Style 3D Character Portrait

**来源：** awesome-gpt-image-2

```text
A stylized Pixar-style 3D portrait of a {argument name="character" default="young person"} with smooth skin, large expressive blue eyes, soft facial features, wearing {argument name="accessory" default="round transparent glasses"}, modern hairstyle (short styled hair / soft bob cut), casual outfit (hoodie or minimal sweater), slight head tilt and warm smile, friendly and approachable expression, ultra-clean character design, {argument name="background" default="vibrant orange-to-pink gradient"} background, soft studio lighting with subtle rim light, cinematic depth of field, ultra-detailed, 8K render, octane render style.
```


---

## 例 358：High-Fidelity Fashion Photography Prompt

**来源：** awesome-gpt-image-2

```text
(9:16) Raw high-fidelity photo, eye-level, medium shot, {argument name="camera" default="iPhone 17 Pro sim"}, 35mm, f/4, sharp subject, natural depth, authentic grain. Framing: Subject ~60%, ~2m, centered, mirrored wall + plants, terrazzo floor. Identity Lock: Preserve ALL facial features; natural skin clarity, soft glow, refined highlights, salon hair, bio-fidelity (pores, vellus hair, hydration). Expression: {argument name="expression" default="Confident, direct gaze"}, neutral lips, slight head tilt (~10° left). Hair: Straight center part, slightly lifted, warm highlights. Makeup: Mauve lip, light base, defined lashes. Accessories: Gold charm necklace, black glossy nails. Outfit: {argument name="outfit" default="Black bodysuit + burgundy sequined mini skirt"}, tight fit, high shine, S-curve. Pose: Torso ~20° right, hips forward, leaning on pot, left hand in hair. Mood: Elegant, warm (black, burgundy, terracotta), ~3200K, moderate-high contrast. Environment: Upscale lounge, mirrored wall, terracotta pots, terrazzo floor, warm light.
```


---

## 例 359：Japanese Influencer Instagram Style Photo

**来源：** awesome-gpt-image-2

```text
A photo of a {argument name="subject" default="beautiful Japanese female influencer"} sitting at {argument name="location" default="a terrace seat of a stylish cafe"}. White dress. Long curly hair. Acai bowl and iced latte on the table. Natural light makes the skin look beautiful. Green plants are blurred in the background. Not a smile, but a slightly cool expression. iPhone-like image quality. Square. Realistic photo.
```


---

## 例 360：Aesthetic Creator Workspace

**来源：** awesome-gpt-image-2

```text
Aesthetic AI workspace scene inside an X (Twitter) profile interface, dark theme UI in the background showing a profile named "Noor 🌸" with a verified badge. In the foreground, a stylized semi-realistic digital girl with {argument name="hair style" default="short messy golden-yellow hair"} and soft glowing skin, wearing a {argument name="outfit" default="sleeveless mustard-yellow top"}, sitting at a desk and working on a laptop with the X logo.
Desk setup includes: a black smartphone with X logo, a minimal glass pen holder with pencil, a yellow pen, sticky notes, stacked notebooks, small yellow cube decor, and a {argument name="decor" default="vase with yellow flowers"}. Lighting is soft, cinematic, warm tones with high contrast against the dark UI.
Composition: centered subject, slightly angled view, sharp focus on the girl, blurred background interface. Hyper-detailed, smooth rendering, 3D + illustration hybrid style, trending on ArtStation, ultra clean, professional, cozy creator workspace vibe.
```


---

## 例 361：Surreal Resin-Split Portrait

**来源：** awesome-gpt-image-2

```text
Ultra-photorealistic 8K RAW, 35mm, f/8, deep focus, no blur, no DOF, no noise, no grain, no haze, no dust, no volumetric light, no soft light, no glow. IMAX stage, 2:3 aspect ratio. Male with my exact face, 181cm 73kg, {argument name="hair style" default="messy dark hair"}, short stubble. Face split: left side — clean skin with {argument name="markings" default="thin amber technical markings (numbers \"6.66\", spiral symbols, hand-drawn)"}; right side — {argument name="skin effect" default="matte black skin covered in thick black resin (glossy, wet-looking, partially dried with stretched glossy strings between skin and fingers)"}. One eye natural dark brown, other faint amber glow (subtle, like light through honey, no beam). Tattoos: small eye on left neck, two horizontal lines on right jaw, tiny cross behind right ear. One mechanical prosthetic hand (black steel with sticky resin residue) raised to chin, fingers pulling a glossy resin string away from right cheek. Clothing: matte black worn jacket, high collar, no hood. Lighting: hard warm amber key from upper left, cool grey fill from lower right, sharp shadows. Color: desaturated grey-black, only amber as accent in resin reflections. Background: solid charcoal grey wall. Clean dry air, no particles. All surfaces sharp.
```


---

## 例 362：HD Photo Restoration Prompt

**来源：** awesome-gpt-image-2

```text
Restore this {argument name="subject" default="old photo"} into {argument name="output style" default="professional portrait of DLSR"} - quality colour and detail, using an advanced upscaling algorithm comparable to the results from {argument name="camera model" default="canon EOS R6 II"}. Ensure the restored the image looks natural, retains exact facial features, has great clarity.
```


---

## 例 363：Hyper-Realistic Stoic Portrait

**来源：** awesome-gpt-image-2

```text
A hyper-realistic, cinematic medium close-up portrait of the uploaded person. The subject is positioned with their torso angled slightly forward, but their head is turned to the side, looking off-camera to the left with a deeply contemplative, serious, and stoic expression. One hand is raised, resting gently against the chin and lower lip in a classic "thinking" gesture, fingers softly curled. On the wrist is a {argument name="accessory" default="prominent, luxurious metallic chronograph watch"} with complex dial details. The subject is wearing a {argument name="outfit" default="sleek, dark black long-sleeved shirt or suit jacket"} that blends into the shadows, with metallic cuff accents catching the light. Background: A minimalist, moody, {argument name="background" default="textured charcoal-grey gradient backdrop"}, featuring a soft, faint vertical strip of light on the far left edge. Camera Angle & Photography: Eye-level angle, amazing high-end commercial portrait photography. Lighting, Editing & Effects: Dramatic chiaroscuro side-lighting illuminating the right side of the subject's face while casting deep, rich shadows on the left. The image features a shallow depth of field with sharp focus on the visible eye and the luxury watch. There is a distinct, heavy foreground blur (a hazy, soft white/grey light leak effect) obscuring the very bottom and bottom-left corner of the frame to create atmospheric depth. High-contrast editing, moody cinematic color grading, and a highly polished, premium aesthetic. ar 4:5
```


---

## 例 364：VTuber Character Prompt

**来源：** awesome-gpt-image-2

```text
{argument name="hair color" default="pink hair"} {argument name="profession" default="vtuber"}
```


---

## 例 365：Censored Monkey Kid in Denim

**来源：** awesome-gpt-image-2

```text
A full-body studio portrait of a stylized anthropomorphic monkey child standing front-facing against a clean pastel light-blue seamless background. The character has a slim small body, brown fur on the arms and tail, oversized protruding ears, and a long curved monkey tail visible on the left side. The face is intentionally obscured by a soft blurred square block centered over the head, creating an anonymous censored look. Dress the character in 5 clearly visible fashion items: a blue denim beret, a medium-wash blue denim jacket with metal buttons and chest pockets, a plain white crew-neck T-shirt, matching blue denim jeans with rolled cuffs, and chunky white low-top sneakers. Add 1 silver pendant necklace over the shirt. The pose is relaxed and symmetrical with arms hanging naturally at the sides, feet apart, and the figure centered in frame from head to shoes. The lighting is soft, diffused, and commercial-studio clean, with subtle shadows under the shoes. Render in a hyper-detailed whimsical fashion-editorial style, mixing realistic clothing textures with cute surreal character design, crisp denim stitching, soft fur detail, and premium toy-like proportions.
```


---

## 例 366：Cherry Blossom Garden Evening Portrait

**来源：** awesome-gpt-image-2

```text
A photorealistic outdoor portrait of an elegant young East Asian woman standing in a traditional Japanese courtyard garden during cherry blossom season. She is shown from a three-quarter back view, turning slightly toward the camera, with her face mostly obscured by her angle. She wears a deep wine-red satin evening dress with thin spaghetti straps and a dramatic low open back, fitted closely through the waist and hips with soft reflective fabric highlights. Her hair is styled in a loose, romantic updo with a few wispy strands, decorated with 3 small pink blossom hair ornaments, and she wears delicate dangling earrings and a fine necklace. Surround her with blooming sakura branches heavy with pale pink flowers, with many individual petals drifting through the air. In the background, place a traditional Japanese wooden building with dark beams, shoji-style windows, and a gray tiled roof, softly blurred with shallow depth of field. Include a calm garden pond and stone edging in the lower background. Use warm spring sunlight, soft cinematic bokeh, high detail skin and fabric rendering, graceful posture, refined luxury fashion photography, natural colors, serene atmosphere, square composition.
```


---

## 例 367：Ink-Etched Family Portrait

**来源：** awesome-gpt-image-2

```text
A black-and-white hand-drawn family portrait in the style of detailed pen-and-ink crosshatching on textured white paper, showing 4 people seated closely together in a casual candid composition. On the left, an adult man in a dark baseball cap worn backward and a dark T-shirt leans into the frame, with a crossbody sling bag worn across his chest and visible zipper details. On the right, an adult woman with curly hair tied up in a loose high bun wears a light T-shirt with large collegiate block letters reading {argument name="shirt text" default="CITY"}. In the center are 2 young children sitting close together, both with short curly hair and matching light-colored T-shirts printed all over with strawberries. The child on the left leans inward with one arm crossing the other child, and the child on the right tilts their head slightly upward. The adults frame the children protectively, creating a warm family snapshot feeling. Render the whole image as a monochrome etched illustration with dense fine-line hatching, engraved shadows, crisp contour lines, and a realistic yet artistic likeness, with no color, no background setting beyond a plain light paper texture, and a vertical portrait crop.
```


---

## 例 368：Vintage Engraved Hoodie Portrait

**来源：** awesome-gpt-image-2

```text
A centered black-and-white vintage engraved portrait of a bearded man wearing a hooded sweatshirt with the hood up and a backward snapback cap visible under the hood. Show only the upper torso and head against a plain off-white paper background with subtle texture. Render the image in detailed pen-and-ink etching style with dense cross-hatching, fine parallel lines, and old book illustration shading. The figure faces forward in a calm, neutral pose. The cap has a visible snap closure band across the forehead area, slicked-back hair is visible above it, and a thick full beard extends below the face. The hoodie has two drawstrings hanging down at the chest. Keep the composition symmetrical and tightly framed like a classic engraved bust portrait, with no color, no modern graphic elements, and no background objects.
```


---

## 例 369：Dreamy Backlit Editorial Portrait

**来源：** awesome-gpt-image-2

```text
A cinematic soft-focus portrait of a woman from behind and slightly in profile, framed from the upper torso up in a vertical composition. She has {argument name="hair color" default="dark brown"} hair styled in a loose messy updo with wispy strands catching the light. Her face is mostly hidden by her pose and hair, with only a small portion of one cheek visible. She wears a {argument name="dress color" default="deep red"} sleeveless dress with an open back or low-cut side, emphasizing her bare shoulder and upper back. One hand is raised delicately near her neck or shoulder, fingers relaxed. Use strong warm backlighting and rim light, with glowing golden highlights around the hair and skin, dreamy lens flare, and large circular bokeh in the blurred background. The image should feel intimate, elegant, and slightly sensual, like a high-end fashion or beauty editorial, with shallow depth of field, creamy blur, warm amber and rose tones, and a soft cinematic glow.
```


---

## 例 370：3D Cartoon Character Render

**来源：** awesome-gpt-image-2

```text
High-quality 3D CGI render of {argument name="character" default="[character]"} in a charming cartoon style, portrait composition showing head and shoulders. Highly stylized caricature with exaggerated, expressive features that are both playful and humorous. Smooth, polished rendering with clean materials and soft ambient lighting creating gentle shadows. Dynamic camera angle with stylish perspective. Minimalist bright {argument name="background color" default="[color]"} background that makes the character pop and stand out. Professional Pixar-like quality with glossy finish and cheerful mood.
```


