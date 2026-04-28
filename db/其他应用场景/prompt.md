# 其他应用场景 — 提示词合集


> 57 个案例

---


## 例 4：老干妈风味

**来源：** 小红书号989137706

![case4.jpg](images/case4.jpg)


```text
特朗普在抖音直播间卖老干妈，手里举着「老干妈风味」新品，背景还是 SpaceX 那种科技感，左下角弹幕飘着「特斯拉车主：求上链接」。
```


---


## 例 25：综合应用场景图

**来源：** [@nicdunz](https://x.com/nicdunz)

![case25.jpg](images/case25.jpg)


```text
create a minecraft skin inspired by {argument name="reference" default="my look"}
```


---


## 例 37：综合应用场景图

**来源：** [@midori\_tatsuta](https://x.com/midori_tatsuta)

![case37.jpg](images/case37.jpg)


```text
Create {argument name="quantity" default="24"} LINE stickers of {argument name="animals" default="animals"} in a quirky hand-drawn style. Target {argument name="target audience" default="Japanese Gen Z"} with a trendy style that can aim for top downloads.
```


---


## 例 38：综合应用场景图

**来源：** [@midori\_tatsuta](https://x.com/midori_tatsuta)

![case38.jpg](images/case38.jpg)


```text
Create {argument name="quantity" default="24"} LINE stickers of {argument name="animals" default="animals"} in a quirky hand-drawn style. Target {argument name="target audience" default="Japanese Gen Z"} with a trendy style that can aim for top downloads.
```


---


## 例 39：综合应用场景图

**来源：** [@midori\_tatsuta](https://x.com/midori_tatsuta)

![case39.jpg](images/case39.jpg)


```text
Create {argument name="quantity" default="24"} LINE stickers of {argument name="animals" default="animals"} in a quirky hand-drawn style. Target {argument name="target audience" default="Japanese Gen Z"} with a trendy style that can aim for top downloads.
```


---


## 例 40：综合应用场景图

**来源：** [@midori\_tatsuta](https://x.com/midori_tatsuta)

![case40.jpg](images/case40.jpg)


```text
Create {argument name="quantity" default="24"} LINE stickers of {argument name="animals" default="animals"} in a quirky hand-drawn style. Target {argument name="target audience" default="Japanese Gen Z"} with a trendy style that can aim for top downloads.
```


---


## 例 78：图像生成案例图

**来源：** [@WOZ1Tx2JZ3kCeBj](https://x.com/WOZ1Tx2JZ3kCeBj)

![case78.jpg](images/case78.jpg)


```text
[CORE TASK]
Transform the provided input image into a pose-and-light analysis sheet.

This is NOT a finished character illustration.
This is NOT a clothing sheet.
This is NOT a beauty-preserving redraw.

This is a white-line rough mannequin conversion.

[PRIMARY GOAL]
Extract and visualize only:
- pose structure
- body balance
- camera angle
- body line flow
- inferred light source placement
- illuminated areas and light intensity

[INPUT ROLE]
Use the provided image as the strict anchor for:
- pose
- camera angle
- body tilt
- weight distribution
- approximate lighting situation

Do NOT preserve:
- face rendering
- hairstyle rendering
- clothing detail
- accessories
- weapon detail
- background architecture
- character identity
- emotional expression

[FIGURE CONVERSION]
single rough mannequin-like human figure
white body contour lines
white internal construction lines
simple mannequin head
no face
no eyes
no mouth
no eyelashes
no personality
no individual identity

human figure should look like:
- rough pose mannequin
- anatomy proxy
- line-based body guide
- structural sketch
- white-line rough dummy

keep:
- pose readability
- silhouette flow
- head tilt
- torso direction
- pelvis direction
- limb placement

[BACKGROUND]
pure black background
negative-style dark field
no scenery
no props
no architecture
no environmental storytelling

[LINE STYLE]
rough white line drawing
clean but sketch-like
construction-line feeling
anatomy guide lines visible
joint flow visible
body contour emphasized
no polished illustration finish

[LIGHT ESTIMATION]
predict the likely light source positions from the input image
visualize the light sources and illuminated areas using green glow only

use green light intensity with variation:
- strongest green where the light directly hits
- medium green for wrap light
- soft green for reflected or fading light

mark the estimated light sources with labels and arrows such as:
- Main Light
- Rim Light
- Fill Light
- Floor Bounce
- Back Light
only if appropriate

IMPORTANT:
do not invent random lights
infer lighting from the original input image
if the lighting is ambiguous, keep the annotations simple and plausible

[GREEN LIGHT VISUALIZATION]
show green glow on:
- head / skull plane
- neck
- shoulders
- chest plane
- ribcage direction
- pelvis edge
- thigh planes
- knee contact points
- floor contact bounce if applicable

use green light not as decoration,
but as lighting analysis information

[POSE PRIORITY]
1. preserve pose structure
2. preserve camera angle
3. preserve body balance
4. preserve head-torso relationship
5. visualize likely light direction
6. show illuminated areas with readable green intensity variation

[NEGATIVE]
finished person,
cute girl,
detailed face,
hair rendering,
clothing rendering,
weapon emphasis,
beautiful anatomy
```


---


## 例 79：图像生成案例图

**来源：** [@WOZ1Tx2JZ3kCeBj](https://x.com/WOZ1Tx2JZ3kCeBj)

![case79.jpg](images/case79.jpg)


```text
[CORE TASK]
Transform the provided input image into a pose-and-light analysis sheet.

This is NOT a finished character illustration.
This is NOT a clothing sheet.
This is NOT a beauty-preserving redraw.

This is a white-line rough mannequin conversion.

[PRIMARY GOAL]
Extract and visualize only:
- pose structure
- body balance
- camera angle
- body line flow
- inferred light source placement
- illuminated areas and light intensity

[INPUT ROLE]
Use the provided image as the strict anchor for:
- pose
- camera angle
- body tilt
- weight distribution
- approximate lighting situation

Do NOT preserve:
- face rendering
- hairstyle rendering
- clothing detail
- accessories
- weapon detail
- background architecture
- character identity
- emotional expression

[FIGURE CONVERSION]
single rough mannequin-like human figure
white body contour lines
white internal construction lines
simple mannequin head
no face
no eyes
no mouth
no eyelashes
no personality
no individual identity

human figure should look like:
- rough pose mannequin
- anatomy proxy
- line-based body guide
- structural sketch
- white-line rough dummy

keep:
- pose readability
- silhouette flow
- head tilt
- torso direction
- pelvis direction
- limb placement

[BACKGROUND]
pure black background
negative-style dark field
no scenery
no props
no architecture
no environmental storytelling

[LINE STYLE]
rough white line drawing
clean but sketch-like
construction-line feeling
anatomy guide lines visible
joint flow visible
body contour emphasized
no polished illustration finish

[LIGHT ESTIMATION]
predict the likely light source positions from the input image
visualize the light sources and illuminated areas using green glow only

use green light intensity with variation:
- strongest green where the light directly hits
- medium green for wrap light
- soft green for reflected or fading light

mark the estimated light sources with labels and arrows such as:
- Main Light
- Rim Light
- Fill Light
- Floor Bounce
- Back Light
only if appropriate

IMPORTANT:
do not invent random lights
infer lighting from the original input image
if the lighting is ambiguous, keep the annotations simple and plausible

[GREEN LIGHT VISUALIZATION]
show green glow on:
- head / skull plane
- neck
- shoulders
- chest plane
- ribcage direction
- pelvis edge
- thigh planes
- knee contact points
- floor contact bounce if applicable

use green light not as decoration,
but as lighting analysis information

[POSE PRIORITY]
1. preserve pose structure
2. preserve camera angle
3. preserve body balance
4. preserve head-torso relationship
5. visualize likely light direction
6. show illuminated areas with readable green intensity variation

[NEGATIVE]
finished person,
cute girl,
detailed face,
hair rendering,
clothing rendering,
weapon emphasis,
beautiful anatomy
```


---


## 例 80：图像生成案例图

**来源：** [@WOZ1Tx2JZ3kCeBj](https://x.com/WOZ1Tx2JZ3kCeBj)

![case80.jpg](images/case80.jpg)


```text
[CORE TASK]
Transform the provided input image into a pose-and-light analysis sheet.

This is NOT a finished character illustration.
This is NOT a clothing sheet.
This is NOT a beauty-preserving redraw.

This is a white-line rough mannequin conversion.

[PRIMARY GOAL]
Extract and visualize only:
- pose structure
- body balance
- camera angle
- body line flow
- inferred light source placement
- illuminated areas and light intensity

[INPUT ROLE]
Use the provided image as the strict anchor for:
- pose
- camera angle
- body tilt
- weight distribution
- approximate lighting situation

Do NOT preserve:
- face rendering
- hairstyle rendering
- clothing detail
- accessories
- weapon detail
- background architecture
- character identity
- emotional expression

[FIGURE CONVERSION]
single rough mannequin-like human figure
white body contour lines
white internal construction lines
simple mannequin head
no face
no eyes
no mouth
no eyelashes
no personality
no individual identity

human figure should look like:
- rough pose mannequin
- anatomy proxy
- line-based body guide
- structural sketch
- white-line rough dummy

keep:
- pose readability
- silhouette flow
- head tilt
- torso direction
- pelvis direction
- limb placement

[BACKGROUND]
pure black background
negative-style dark field
no scenery
no props
no architecture
no environmental storytelling

[LINE STYLE]
rough white line drawing
clean but sketch-like
construction-line feeling
anatomy guide lines visible
joint flow visible
body contour emphasized
no polished illustration finish

[LIGHT ESTIMATION]
predict the likely light source positions from the input image
visualize the light sources and illuminated areas using green glow only

use green light intensity with variation:
- strongest green where the light directly hits
- medium green for wrap light
- soft green for reflected or fading light

mark the estimated light sources with labels and arrows such as:
- Main Light
- Rim Light
- Fill Light
- Floor Bounce
- Back Light
only if appropriate

IMPORTANT:
do not invent random lights
infer lighting from the original input image
if the lighting is ambiguous, keep the annotations simple and plausible

[GREEN LIGHT VISUALIZATION]
show green glow on:
- head / skull plane
- neck
- shoulders
- chest plane
- ribcage direction
- pelvis edge
- thigh planes
- knee contact points
- floor contact bounce if applicable

use green light not as decoration,
but as lighting analysis information

[POSE PRIORITY]
1. preserve pose structure
2. preserve camera angle
3. preserve body balance
4. preserve head-torso relationship
5. visualize likely light direction
6. show illuminated areas with readable green intensity variation

[NEGATIVE]
finished person,
cute girl,
detailed face,
hair rendering,
clothing rendering,
weapon emphasis,
beautiful anatomy
```


---


## 例 165：清冷佳人夜市烧烤三刀流

**来源：** [@BubbleBrain](https://x.com/BubbleBrain/status/2046564674112831920)

![case165.jpg](images/case165.jpg)


```text
[中文]
一个有着清冷孤傲气质的绝美佳人，精致的面部特征，一张冷酷且精致的高级时装面容，长发，以及优雅苗条的身材；烧烤“三刀流”姿势：嘴里叼着一根烧烤串，每只手各拿一根烧烤串交叉以模仿索隆的三刀流；街头夜景氛围，温暖黄色的夜市灯光，模糊的背景，胶片般的质感，柔焦光晕，电影般的叙事感，时髦高端网红风格的时尚拍摄，清晰发光的肌肤，清晰细致的发丝，生动的动态表情，低角度广角镜头，情绪化的暗调氛围，浅景深，超高清8K，极致细节，电影级光照

[English]
a stunning beauty with a cool, aloof atmosphere, delicate facial features, a cold and sophisticated high-fashion face, long hair, and a graceful slender figure; barbecue “three-sword style” pose: one barbecue skewer held in her mouth, one skewer in each hand crossed to mimic Zoro’s three-sword style; street night scene ambiance, warm yellow night market lighting, blurred background, film-like texture, soft-focus glow, cinematic storytelling feel, trendy high-end influencer-style fashion shoot, clear luminous skin, sharply detailed strands of hair, lively dynamic expression, low-angle wide-angle shot, moody dark-toned atmosphere, shallow depth of field, ultra HD 8K, extreme detail, cinematic lighting
```


---


## 例 193：千手观音化身打工人

**来源：** [@johnAGI168](https://x.com/johnAGI168/status/2046565555025367392)

![case193.jpg](images/case193.jpg)


```text
[中文]
一幅高度详细的千手观音菩萨工笔画。

然而，千手并没有拿着神圣的宗教法器，而是拿着现代办公和家用物品：**笔记本电脑、智能手机、成堆的文件、咖啡杯、印章、计算器、拖把和奶瓶**。它代表了终极的多任务处理现代工作者。

脑后的金色光环由旋转的时钟齿轮组成。

**在右下角，一个单一的红色竖排艺术家印章写着“吴先生”（Mr. Wu），风格化得像水印一样。** --ar 3:4

[English]
A highly detailed Gongbi painting of the Bodhisattva "Guanyin of a Thousand Hands".

However, instead of sacred religious artifacts, the thousand hands are holding modern office and household items: **laptops, smartphones, stacks of paperwork, coffee cups, stamps, calculators, mops, and baby bottles**. It represents the ultimate multi-tasking modern worker.

The golden aura behind the head is made of spinning clock gears.

**In the bottom right corner, a single red vertical artist chop seal reads "吴先生" (Mr. Wu), stylized like a watermark.** --ar 3:4
```


---


## 例 197：英雄联盟特朗普中路对决哈梅内伊

**来源：** [@underwoodxie96](https://x.com/underwoodxie96/status/2046529342415790275)

![case197.jpg](images/case197.jpg)


```text
[中文]
帮我生成一张特朗普对战哈梅内伊在英雄联盟中路对线的截图。

[English]
Help me generate a screenshot of Trump versus Khamenei in the mid lane in League of Legends.
```


---


## 例 203：杠精视角的独特文案创意

**来源：** [@joshesye](https://x.com/joshesye/status/2046596222505361866)

![case203.jpg](images/case203.jpg)


```text
[中文]
杠精视角文案 + GPT Image 2

[English]
Troll perspective copywriting + GPT Image 2
```


---


## 例 205：皇宫深处的御用快递驿站

**来源：** [@joshesye](https://x.com/joshesye/status/2046596222505361866)

![case205.jpg](images/case205.jpg)


```text
[中文]
生成一张古代皇宫 × 快递驿站

[English]
Generate an ancient imperial palace × express delivery station
```


---


## 例 233：蒙娜丽莎畅饮可乐的趣味油画

**来源：** [@liyue\_ai](https://x.com/liyue_ai/status/2045058142858555733)

![case233.jpg](images/case233.jpg)


```text
[中文]
生成一张蒙娜丽莎喝可乐的油画。

[English]
Generate an oil painting of Mona Lisa drinking cola.
```


---


## 例 259：精致女孩背后的网贷真相

**来源：** [@MrLarus](https://x.com/MrLarus/status/2045373105041007013)

![case259.jpg](images/case259.jpg)


```text
[中文]
生成小红书内容截图，主题：精致女孩背后都有网贷，iPhone尺寸

[English]
Generate Xiaohongshu content screenshot, theme: Behind every exquisite girl there is online loan, iPhone size
```


---


## 例 262：苹果园远观库克发布新机

**来源：** [@austinit](https://x.com/patrickassale/status/2044687244368441742)

![case262.jpg](images/case262.jpg)


```text
[中文]
在Apple Park iPhone 20主题演讲期间拍摄的业余iPhone照片，蒂姆·库克在舞台上演讲。从远处的观众人群中拍摄

[English]
Amateur iPhone photo at Apple Park during the iPhone 20 keynote, Tim Cook presenting on stage. Shot from the crowd at a distance
```


## 例 263：帮我生成xxxx真迹图片

**来源：** [@MrLarus](https://x.com/MrLarus/status/2046201836525302032)

```text
帮我生成xxxx真迹图片
```


---

## 例 264：1、生成不知火舞和貂蝉的游戏对战海报图...

**来源：** [@joshesye](https://x.com/joshesye/status/2046493442428039212)

```text
1、生成不知火舞和貂蝉的游戏对战海报图
2、生成一张K-pop团体时尚专辑封面
3、请你生成 《斗破苍穹》 的关键人物关系图
4、帮我截一张上传图片的抖音首页的女网红图
```


---

## 例 265：生成一个抖音直播的截图 里面是一个美女在直播，在卖丝袜和内衣，她的在线人数是99996，热度是18+，有个叫小互的大哥，给她刷了一个飞机礼物

**来源：** [@xiaohu](https://x.com/xiaohu/status/2046536551681954207)

```text
生成一个抖音直播的截图 里面是一个美女在直播，在卖丝袜和内衣，她的在线人数是99996，热度是18+，有个叫小互的大哥，给她刷了一个飞机礼物
```


---

## 例 266：an ingame screenshot of rust

**来源：** [@FixlationAI](https://x.com/FixlationAI/status/2046272578705068476)

```text
an ingame screenshot of rust
```


---

## 例 267：画像のプロンプトはALTに載せてます。

**来源：** [@yudotanaka](https://x.com/yudotanaka/status/2046188377524076915)

```text
画像のプロンプトはALTに載せてます。
```


---

## 例 268：在りそうでないサービスの広告を10サービズ(1サービス1枚)作成して下さい

**来源：** [@Yuupapa_free](https://x.com/Yuupapa_free/status/2046388238982771123)

```text
在りそうでないサービスの広告を10サービズ(1サービス1枚)作成して下さい
```


---

## 例 269：generate image: Selfie of Sam Altman riding a bear...

**来源：** [@JustinGorya](https://x.com/JustinGorya/status/2046510831832006970)

```text
generate image: Selfie of Sam Altman riding a bear

Edit prompt: Remove the background make it transparent
```


---

## 例 270：AmongUsの精密な実際のゲーム画像を生成して

**来源：** [@ReYYYYoking](https://x.com/ReYYYYoking/status/2046502217843376292)

```text
AmongUsの精密な実際のゲーム画像を生成して
```


---

## 例 271：プロンプトはリプに最終ページとまとめて掲載します↓

**来源：** [@minesan_ai](https://x.com/minesan_ai/status/2046215187678790140)

```text
プロンプトはリプに最終ページとまとめて掲載します↓
```


---

## 例 272：在计算机博物馆里，一个程序员在展厅中央，正在演示C语言编程，很多参观者在围观，屏幕上的代码清晰可见。旁边的牌子写着：古法编程，现场表演。2D卡通画风，16:9

**来源：** [@XiaohuiAI666](https://x.com/XiaohuiAI666/status/2046515319947354603)

```text
在计算机博物馆里，一个程序员在展厅中央，正在演示C语言编程，很多参观者在围观，屏幕上的代码清晰可见。旁边的牌子写着：古法编程，现场表演。2D卡通画风，16:9
```


---

## 例 273：A dusk shindig  with multiple fake imagination projections all aligned in the 14...

**来源：** [@workingclassbud](https://x.com/workingclassbud/status/2046506783850815703)

```text
A dusk shindig  with multiple fake imagination projections all aligned in the 14th dimensions
```


---

## 例 274：アザラシが重税プラットフォーマーから逃げている映像を作って。

**来源：** [@seedsbiz](https://x.com/seedsbiz/status/2046114427972600131)

```text
アザラシが重税プラットフォーマーから逃げている映像を作って。
```


---

## 例 275：in ALT and comment.

**来源：** [@fy360593](https://x.com/fy360593/status/2046517653431545956)

```text
in ALT and comment.
```


---

## 例 276：戦前日本の怪しげな研究所を探検しているマイクラのスクリーンショット画像を作成して

**来源：** [@RitaStar1128](https://x.com/RitaStar1128/status/2046406024303976904)

```text
戦前日本の怪しげな研究所を探検しているマイクラのスクリーンショット画像を作成して
```


---

## 例 277：この画像のプロンプト↓

**来源：** [@hiro_ai_auto](https://x.com/hiro_ai_auto/status/2046542225358917945)

```text
この画像のプロンプト↓
```


---

## 例 278：Prompt见评论。

**来源：** [@EurekaLuyao](https://x.com/EurekaLuyao/status/2046540642634047868)

```text
Prompt见评论。
```


---

## 例 279：in ALT &amp; comment.

**来源：** [@fy360593](https://x.com/fy360593/status/2046512133295452363)

```text
in ALT &amp; comment.
```


---

## 例 280：(cheak in Comment)

**来源：** [@Gdthainakub](https://x.com/Gdthainakub/status/2046508044528582861)

```text
(cheak in Comment)
```


---

## 例 281：サムアルトマンがメジャーリーガーでバットを構えている。よくあるようなテレビ画面の構図

**来源：** [@16kthir0GRXgNqn](https://x.com/16kthir0GRXgNqn/status/2046507362266259832)

```text
サムアルトマンがメジャーリーガーでバットを構えている。よくあるようなテレビ画面の構図
```


---

## 例 282：counter strike in game screenshot, mixed with Terraria

**来源：** [@yssrski](https://x.com/yssrski/status/2046410519595348397)

```text
counter strike in game screenshot, mixed with Terraria
```


---

## 例 283：Anachronistic Beauty Tutorial

**来源：** awesome-gpt-image-2

```text
{argument name="character" default="Pan Jinlian"} posting a beauty tutorial on {argument name="platform" default="Bilibili"} titled "{argument name="topic" default="How to Conceal Blemishes Using Ancient Methods"}," with bullet comments saying "Sister-in-law's technique is amazing!"
```


---

## 例 284：Dramatic Soccer Cinematic Action Shot

**来源：** awesome-gpt-image-2

```text
A dramatic cinematic action shot of a {argument name="child" default="12-year-old boy"} with messy dark hair powerfully kicking a soccer ball on a {argument name="setting" default="green grass stadium field"} at golden hour sunset. The soccer ball is massively oversized and zoomed-in in the foreground, dominating the lower part of the frame like viral "giant object" photos, extremely detailed texture, black and white panels, sharp focus. The boy is captured mid-kick with his right leg extended, dirt and grass particles flying dramatically. He wears a {argument name="clothing" default="crisp white t-shirt"} with bold black text "GPT IMAGE 2.0" printed on the chest, black athletic shorts, white socks with black stripes. Dynamic low-angle perspective, vibrant saturated colors, ultra-sharp clarity, high contrast, cinematic lighting with warm golden sun rays breaking through dramatic clouds, shallow depth of field, 8k photorealistic, hyper-detailed, National Geographic style --ar 3:4 --stylize 250 --v 6
```


---

## 例 285：Anime BL Promo Thumbnail

**来源：** awesome-gpt-image-2

```text
A bright, polished anime-style promotional thumbnail with a summer romance atmosphere. The composition is split visually, with large typography on the left and two handsome young men on the right. On the left side, place layered translucent white panels with soft glow and sparkles over a sky-blue background, featuring large elegant serif text "GPT" in a blue gradient at the top and "BL" in a lavender-to-violet gradient below. Add three lines of Japanese text arranged between and under them: "最新の画像生成で", "作って", and "遊んでみた", in deep blue calligraphic Japanese type. Include subtle decorative accents such as small star glints, diagonal light streaks, dotted texture, and a cyan underline swoosh beneath the middle text. On the right side, show 2 anime boys from the waist up, leaning casually together beside a chain-link fence under leafy trees. The taller boy has tousled dark brown hair, a navy overshirt worn open over a white T-shirt, layered silver necklaces, and holds 1 plastic cup of iced coffee with a straw. The shorter boy has messy silver-white hair, a white T-shirt with a small crest emblem on the chest, black backpack straps over both shoulders, layered silver necklaces, and one small earring. Their poses are relaxed and intimate, with the dark-haired boy’s arm resting around the other. Use a luminous blue-and-white palette with soft sunlight, lens flare, bokeh, and a faint cityscape in the background, creating a clean social-media header or article thumbnail aesthetic.
```


---

## 例 286：Restaurant POV Change Comparison

**来源：** awesome-gpt-image-2

```text
A side-by-side comparison graphic on a black background demonstrating a camera-angle change in the same restaurant scene. At the top, large white sans-serif text reads: "Show me the POV from someone standing behind the bar looking out over this crowded restaurant. Change NOTHING in the scene other than the pov". Below, place 2 stacked rectangular photos centered vertically: the top image labeled "Source" in large white text on the left, and the bottom image labeled "Output" in large white text on the left. The top photo shows a warmly lit, upscale, crowded restaurant interior seen from the dining room side, facing a tall back bar filled with many illuminated liquor bottles on wall-to-wall shelves, with bartenders and guests in front, amber lighting, globe pendant lights, wood ceiling, beige columns, and tightly packed seated diners in the foreground. The bottom photo shows the exact same restaurant, same crowd density, same warm lighting, same decor, same bar shelving, same globe pendant lights, and same overall composition elements, but now from the point of view of someone standing behind the bar and looking outward across the crowded restaurant; the foreground includes the bar counter with glassware, metal bar tools, bottles, and a point-of-sale screen visible at the lower left, while guests and staff fill the middle ground and the dining room extends into the background. Preserve the sense that only the camera position changed between the 2 images, with no other scene alterations.
```


---

## 例 287：Anime Crowd POV Comparison

**来源：** awesome-gpt-image-2

```text
{"type":"comparison graphic","style":"anime cinematic demonstration image on a black presentation background","canvas":{"aspect_ratio":"4:3","background":"solid black"},"text_elements":[{"text":"{argument name=\"headline text\" default=\"Move the camera POV to be at ground level in the crowd.\"}","position":"top center","style":"large white sans-serif"},{"text":"Source","position":"left of upper image","style":"large white sans-serif"},{"text":"Output","position":"left of lower image","style":"large white sans-serif"}],"layout":{"sections":[{"title":"Source","position":"upper center","count":1,"labels":["overhead crowd scene"]},{"title":"Output","position":"lower center","count":1,"labels":["ground-level crowd POV scene"]}],"image_frames":2},"images":[{"role":"source image","composition":"busy top-down view of a densely packed historical street crowd, seen from above","scene":"a chaotic crowd gathered around a wagon and a horse-drawn carriage, people pressed shoulder to shoulder, many wearing caps and muted early-20th-century or old-European clothing, bundles and sacks visible, one brown horse at the right edge, wooden wagon wheel and cart structure partially visible","camera":"high overhead bird's-eye angle looking down into the crowd","lighting":"soft daylight","color_palette":"muted earthy browns, dusty blues, beige, olive, warm gray","rendering":"hand-painted anime film still, detailed crowd illustration, slightly soft shading"},{"role":"output image","composition":"the same crowded historical street reimagined from inside the mass of people at near-ground height","scene":"view from within the crowd beside a carriage wheel, bodies filling the foreground and midground, a person in dark maroon clothing bent forward at left, a crouched figure in green near the bottom center, a woman in a light blue dress at right-center turning back, tightly packed figures, horse and cart implied nearby, dramatic sense of compression and closeness","camera":"very low ground-level POV from inside the crowd, upward and forward through people, emphasizing complex occlusion and depth","lighting":"soft daylight with warm cinematic shadows","color_palette":"muted earthy browns, dusty blues, beige, olive, warm gray","rendering":"hand-painted anime film still, cinematic perspective shift, detailed character crowding, soft painterly shading"}],"overall_goal":"show a before-and-after camera angle transformation of the same anime crowd scene, with the output moving from an overhead view to a low immersive POV inside the crowd"}
```


---

## 例 288：Neon AI Thumbnail Comparison

**来源：** awesome-gpt-image-2

```text
Create a dramatic Japanese YouTube thumbnail in a futuristic neon cyberpunk style, 16:9 landscape. Use a dark tech-city background with faint skyscrapers, digital grid lines, glowing particles, and high-contrast blue, pink, and gold lighting. In the exact center, place a young woman from the waist up with long straight pastel blue hair, wearing a plain white short-sleeve T-shirt and a light pink skirt, posing thoughtfully with one hand near her chin and the other arm folded; anonymize her face with a soft rectangular blur. Across the very top, add huge distressed bold white Japanese headline text reading 主導権が揺れた, and directly below it add large bold yellow text reading {argument name="subheadline text" default="Nano Bananaから"}. On the left side, create a glowing blue hexagonal-framed panel titled Nano Banana with a smaller subtitle 画像生成. Inside that panel, include exactly 4 image tiles in a 2x2 grid: 1) a fantasy floating island landscape at sunset, 2) a sunlit forest path with tall trees, 3) a neon futuristic city street at night, 4) an outer-space planet scene with stars and a spacecraft. Beneath the left panel, add a blue glowing ribbon label reading かつては優位だった. On the right side, create a glowing magenta hexagonal-framed panel titled {argument name="right panel title" default="GPT Image 2"} with a smaller subtitle 実務で使える出力へ. Inside it, include exactly 4 example thumbnail cards in a 2x2 grid, each featuring the same blue-haired woman with a blurred face and bold Japanese text. The 4 card labels above the tiles are: サムネイル画像, 記事のアイキャッチ画像, LPのセクション画像, SNS投稿画像. The large text inside the 4 cards should read respectively: 1) AIで変わるクリエイティブの未来, 2) AI時代のクリエイティブ戦略 成功する企業の条件, 3) AIで加速するビジネス成長, 4) 未来をつくるのは AI×あなたのアイデア. Between the left and right panels, place a bright glowing gold arrow pointing from left to right with spark-like particle trails, indicating transition or superiority shift. Along the bottom, add a very large black banner with a glowing gold border and massive bold gold text reading {argument name="bottom banner text" default="GPT Image 2へ"}. Overall composition should feel like a comparison graphic showing a shift from older image generation to more practical commercial output, with aggressive thumbnail typography, strong glow effects, metallic texture on major text, and polished social-media marketing visuals.
```


---

## 例 289：Cyberpunk AI Tools Comparison Poster

**来源：** awesome-gpt-image-2

```text
A futuristic Japanese tech comparison poster in a dark cyberpunk control-room setting, wide 16:9 composition. Large distressed white Japanese headline text at the upper left reading "三つ巴", with a bold gold subtitle directly below reading "それぞれの武器". Across the center-left are 3 glowing holographic comparison panels arranged horizontally and connected by neon arrows: a blue panel labeled "Google", an amber-gold panel labeled "Claude", and a purple-magenta panel labeled "OpenAI". The Google panel contains 4 inner cards: 2 larger top cards labeled "Gemini" and "Antigravity", plus 2 smaller bottom cards showing analytics/dashboard-like visuals and a blue isometric cube graphic. The Claude panel contains 4 inner cards: 1 large top card labeled "Claude Code", plus 3 smaller bottom cards showing a network diagram, text/code list, and chart analytics. The OpenAI panel contains 5 inner cards: 2 larger top cards labeled "ChatGPT" and "Codex", plus 3 smaller bottom cards showing interface/code windows and a geometric wireframe cube. Add glowing bidirectional arrows between Google and Claude, and between Claude and OpenAI. At the bottom center, place a large neon-framed banner with gold text reading "Google / Claude / OpenAI". On the right side, include a young woman standing and pointing left toward the panels, with long straight split-dyed hair in pastel pink and cyan blue, a plain white t-shirt with black text reading "{argument name="shirt text" default="OKIHIRO AI Creative"}", and a soft pink pleated skirt. Her face is obscured by a smooth rectangular blur block. Use cinematic sci-fi lighting, glossy hologram UI details, high contrast, vivid blue-gold-purple accents, and a polished YouTube thumbnail aesthetic.
```


---

## 例 290：Japanese AI Battle YouTube Thumbnail

**来源：** awesome-gpt-image-2

```text
A bold Japanese YouTube thumbnail about the AI competition era, 16:9 widescreen, high contrast, dramatic tech-news style. Use a dark futuristic control-room background filled with 3 glowing holographic dashboard screens and blue cyber interface elements around the edges. On the left and center, place a luminous circular hub labeled “AI” in bright blue, with 3 directional glowing energy arrows branching outward to competing platforms: “Google” on the left in a blue electric region, “Claude” on the upper right in a gold electric region, and “OpenAI” at the bottom center in a magenta-purple electric region. Add a subtle world-map or territory-battle visualization effect under each brand region, like illuminated digital land masses or influence zones. On the right side, show a young Japanese-looking woman from waist up, facing forward, wearing a long straight split-color wig with pastel pink on one side and pastel blue on the other, a plain white T-shirt with the printed text “OKIHIRO AI Creative”, and a light pink skirt. She raises one index finger beside her face in a presenter pose. Her face is fully obscured by a large soft-edged rectangular blur block. Across the top, add huge distressed white Japanese headline text: {argument name="headline text" default="AI戦国時代"}. Beneath it, add a second line in bold gold Japanese text: {argument name="subheadline text" default="性能だけの話じゃない"}. Across the bottom, place a wide black banner with massive bold gold Japanese text: {argument name="bottom text" default="空気を取った側が勝つ"}. Make the typography oversized, gritty, and attention-grabbing, with slight glow and drop shadow. Use a color palette of black, electric blue, gold, magenta, and neon white, with intense contrast and thumbnail readability.
```


---

## 例 291：Monika Anime Banner Illustration

**来源：** awesome-gpt-image-2

```text
A highly polished anime banner illustration in a warm golden classroom-literature-club setting, wide cinematic composition. On the left half, a large elegant glowing script title reads {argument name="headline text" default="Monika"} in oversized calligraphy, colored white and pale green with a soft neon glow, metallic highlights, decorative flourishes, hearts, sparkles, and swirling ornamental lines around it. On the right half, a beautiful anime schoolgirl inspired by {argument name="character name" default="Monika"} sits at a wooden desk, facing slightly left, with long flowing {argument name="hair color" default="chestnut brown"} hair, a very large white ribbon bow, warm brown eyes, and a thoughtful, confident expression. She wears a Japanese high school uniform with exactly 4 visible clothing pieces: a brown blazer, white shirt, red ribbon tie, and brown argyle sweater vest. She holds a fountain pen over papers on the desk with one hand while the other rests near her face in a poised writing pose. The room is filled with sunset light streaming through tall windows, dust motes, trailing green ribbons, floating petals, handwritten notes pinned and hanging in the background, and a dark chalkboard covered with faint cursive writing and geometric doodles. Include exactly 9 prominent desk and room props: a bouquet of white roses at lower left, a stack of books at left, an hourglass near the center-left, a sealed envelope with a small green leaf emblem, scattered manuscript pages on the desk, a pen cap near the writing hand, a green-upholstered chair, a piano in the back right, and a stack of 4 books on the right. The 4 right-side book spines read, from top to bottom: "Save Me", "My Feelings", "Poems for the Literature Club", and "Just Monika." Add lush volumetric lighting, glittering particles, green-and-gold color harmony, delicate linework, ultra-detailed painterly shading, romantic visual-novel key art quality, and a premium polished thumbnail/banner aesthetic.
```


---

## 例 292：Purple Anime Yuri Banner

**来源：** awesome-gpt-image-2

```text
A polished anime-style banner illustration in a dreamy violet palette, wide cinematic composition, showing a quiet literary room at twilight. On the right side, a beautiful teenage anime girl named {argument name="character name" default="Yuri"} sits at a wooden desk beside a large window with purple curtains, holding a dark ornate hardcover book close to her chest and gazing softly downward with a shy, introspective expression. She has very long straight {argument name="hair color" default="deep violet"} hair with glossy highlights, side bangs, a small hair clip, and violet eyes, wearing a Japanese school uniform with a gray blazer, white shirt, red ribbon tie, and dark skirt. Across the left-center of the image, the glowing calligraphic word {argument name="title text" default="Yuri"} appears large in luminous neon-lavender script with elegant flourishes, a small heart, and decorative filigree, integrated into the scene like magical typography. The desk contains exactly 8 visible item groups: 1 open book in the foreground center, 1 black inkwell with a white feather quill, 1 closed book near the candle, 1 stack of books under papers, 1 loose handwritten page in front, 1 small purple flower on the desk, 1 floral porcelain teacup with saucer on the right, and 1 dark book stack at the far right. Additional background details include exactly 6 decorative environmental elements: 1 lit candle in a glass holder on the left, 1 cluster of purple flowers in the left foreground, 1 hanging spray of purple blossoms in the upper left, 1 pinned botanical note in the upper right, 1 bookshelf with books and flowers in the right background, and 1 sunset sky visible through the window. Add drifting flower petals, faint handwritten script textures, ornate gold border lines around the frame, soft volumetric window light, subtle sparkles, rich shadows, and a romantic melancholic atmosphere. Highly detailed, clean line art, glossy anime rendering, premium visual-novel key art, perfect for a niche anime banner or character-themed thumbnail.
```


---

## 例 293：Pink Anime Natsuki Banner

**来源：** awesome-gpt-image-2

```text
A glossy pastel pink anime banner in a wide cinematic layout, themed around cute romance and sweets. Place a confident teenage anime girl on the right side, shown from about thigh-up, with short fluffy bob hair in {argument name="hair color" default="soft pink"}, large pink-magenta eyes, a small gentle smile, and arms crossed. She wears a Japanese school uniform: 1 brown blazer, 1 white shirt, 1 red ribbon bow at the collar, and 1 dark navy-and-purple plaid skirt. Add 2 red ribbon hair accessories, one larger bow on the side and one smaller ribbon accent. On the left half, feature the large handwritten script name {argument name="character name" default="Natsuki"} in bold glossy 3D cursive, white-to-pink fill with bright pink outline, soft bevel, subtle drop shadow, sparkles, and a small heart flourish integrated into the lettering. The background should be a layered scrapbook collage in blush pink tones with notebook paper texture, faint grid and torn paper details, scattered doodled hearts, flower petals, sparkles, and cute bakery motifs. Include exactly 4 pinned or taped sketch-style portrait cards of the same girl behind her on the upper-right and mid-right, arranged like overlapping polaroids. Add exactly 2 cupcakes in the foreground near the bottom left and lower center-left, both with pink frosting, striped wrappers, and tiny heart toppers or candy accents. Frame the composition with flowing satin ribbons and bows: exactly 4 major ribbon elements visible, including 1 bow near the top left, 1 bow near the bottom left, and 2 long curling ribbons sweeping across the top and right edges. Use a soft high-detail anime illustration style, polished lighting, dreamy bloom, romantic Valentine palette, delicate textures, and a clean impactful thumbnail-like composition.
```


---

## 例 294：Dreamy Anime Sayori Banner

**来源：** awesome-gpt-image-2

```text
A wide anime banner illustration of {argument name="character name" default="Sayori"} in a bright dreamy classroom, rendered in a polished, high-end visual novel style with soft painterly lighting, warm pastel colors, and sparkling atmosphere. Show a cheerful teenage schoolgirl with short fluffy coral-pink hair, messy bob layers, and a large red bow on the right side of her head, wearing a Japanese school uniform with a light brown blazer, white shirt, red ribbon tie, brown sweater vest, and pleated navy skirt. She stands slightly left of center with arms open wide in an inviting, joyful pose, as if welcoming the viewer, with dynamic perspective and gentle motion in her hair and clothes. Her face is intentionally obscured by a flat rectangular skin-tone censor block. Behind her, tall classroom windows reveal a vivid blue sky with soft white clouds and warm sunlight streaming in. The right half of the image features a large decorative handwritten script reading {argument name="headline text" default="Sayori"}, cream-white lettering with a soft orange-gold outline and glow, integrated into a scrapbook-like wall background. Surround the scene with hanging photo prints clipped to string, including sky photos and a sunflower photo, plus hand-drawn doodles of clouds, stars, hearts, and a sun. Add blue and yellow paper stars, ribbons, floating confetti, a blue paper airplane, notebook pages, a spiral sketchbook, and scattered stationery elements. Place sunflowers prominently in the foreground and edges, with warm golden bokeh and soft depth of field. Make the composition energetic, cute, nostalgic, and emotionally uplifting, like a premium anime-themed YouTube banner or character tribute header, ultra-detailed, clean, stylish, luminous, and impact-focused.
```


---

## 例 295：Cyberpunk 404 Witch Summoning

**来源：** awesome-gpt-image-2

```text
A dramatic anime-style cyberpunk witch standing on a dark rooftop high above a dense futuristic city at night, viewed from a slightly elevated angle. The main subject is a petite young witch girl with pale skin, short icy blue bobbed hair, pointed elf-like ears, and glowing red eyes, wearing a sly confident smile. She raises a black wand overhead in her right hand, with a dangling orb charm at the tip glowing faintly purple and red. Her oversized crooked witch hat is black with purple lining and covered in stitched patches, warning labels, straps, and white graphics including a large “404” and a skull emblem. She wears a black and purple techwear outfit: oversized hooded jacket with many straps and tags, black crop top with “404” on the chest, layered belts, short bottoms, fishnet on one leg, black lace-up combat boots, chokers, and metallic accessories. Several hanging straps and tags visibly read words like “WITCH 404,” “404,” and glitch-themed markings. Beneath and beside her, a large glowing violet magic circle mixed with hacker interface aesthetics is projected on the rooftop floor, filled with occult rings, sigils, a central skull symbol, and scattered neon system text such as error-code fragments, creating a fusion of sorcery and digital corruption. Emerging from the circle is 1 large armored summoned figure: a black futuristic demon-knight or robotic familiar with jagged reflective armor, a narrow purple-lit visor, and a heavy weapon held in one hand, partially dissolving into purple energy shards and smoke. The background shows a sprawling rainy megacity of apartment towers and industrial rooftops, packed with windows, balconies, cables, signs, and haze. On a nearby building wall is a giant vertical graffiti-style sign with 3 readable elements: “404”, “Witch”, and “ERROR NOT FOUND”, plus a smaller “E404”. Additional purple neon glitch text and symbols are scattered across rooftops and in the air. Use a dark palette of black, indigo, and deep violet with sharp magenta-purple highlights, cinematic contrast, reflective wet surfaces, dense detail, and a high-end polished illustration style. The mood is occult, edgy, stylish, and dangerous, combining urban fantasy, hacker aesthetics, and magical summoning.
```


---

## 例 296：Anime Fantasy Travel Movie Poster

**来源：** awesome-gpt-image-2

```text
A cinematic anime movie poster for a fictional film titled {argument name="headline text" default="EL VIAJE DE LA LUNA DE PLATA"}, in polished modern Japanese animation style with a natural, less over-detailed look. Center a teenage anime girl from mid-thigh up, facing forward, with a short silver bob haircut, pale skin, a black choker, small black geometric earrings, a white tank top, and a dark navy oversized zip hoodie with two yellow stripes running down the sleeves. She has a backpack strap over one shoulder and both hands tucked casually into the hoodie pockets. Her face is obscured by a flat rectangular censor block in a muted beige tone, covering the entire face area. Place her in a dramatic twilight coastal city setting that blends travel, nostalgia, and fantasy: on the left, a lit train platform with a commuter train approaching, its destination sign showing Japanese characters; behind it, a glowing city skyline with a ferris wheel. In the distance and lower left, layered mountains and a winding illuminated valley road. On the right, a cliffside coast at sunset with the sea reflecting warm light, a crescent moon in the sky, several flying seabirds, and a curving highway descending along the hillside. Also on the right, include a wooden signpost with exactly 3 directional signs labeled "NUEVOS CAMINOS", "VIEJOS RECUERDOS", and "SIN LÍMITES". At the top center, add the Spanish tagline {argument name="tagline text" default="CADA DESTINO CAMBIA SU HISTORIA"} in elegant serif capitals. On the upper left, create an awards column in gold typography with laurel wreaths and exactly 4 award blocks: one text block reading "GANADORA DE MÚLTIPLES PREMIOS" with 5 gold stars beneath it, then three laurel award sections reading "MEJOR PELÍCULA ANIMADA / FESTIVAL INTERNACIONAL DE ANIMACIÓN / 2024", "PREMIO DEL PÚBLICO / FESTIVAL INTERNACIONAL DE CINE / 2024", and "MEJOR BANDA SONORA ORIGINAL / ACADEMIA DE CINE ANIMADO / 2024". Place the film title large across the lower center in luminous ornate serif lettering with a magical glow and sweeping flourishes, layered partly over the character. Beneath it, add the Spanish quote {argument name="quote" default="A veces, para encontrarte... tienes que perderte en el mundo."}. Below that, add "UNA PELÍCULA DE ESTUDIO LUMINARIA" in small caps. At the bottom, add the release line {argument name="release text" default="PRÓXIMAMENTE EN CINES"} in large gold serif capitals, plus tiny production logos and credits along the footer, including a small studio emblem on the left. Rich blue, violet, and warm sunset orange palette, glossy poster lighting, romantic adventure mood, balanced composition, highly polished theatrical key art, vertical one-sheet film poster.
```


---

## 例 297：Tokyo DisneySea Front-Row Battle UI

**来源：** awesome-gpt-image-2

```text
Create a hyper-detailed comedic Japanese arcade fighting game screenshot styled like a versus battle scene, using a real-world photo aesthetic with game UI overlaid on top. The scene shows an intense mock battle between two groups of theme-park fans competing for the front row at an outdoor show plaza in Tokyo DisneySea. Use a wide 16:9 composition. In the background, clearly show Mediterranean Harbor and Mount Prometheus under bright daytime skies, with the waterfront and DisneySea architecture visible. In the foreground, show exactly 10 young adult people in winter casual clothing, split into 2 opposing teams of 5, physically leaning, grabbing, reaching, and shoving in a tug-of-war-like scrum over position, with exaggerated competitive body language and frozen action as if in a fighting game. Faces should be anonymized with soft blurred blocks. Add floating character labels above each person with levels and names in Japanese. The overall tone is absurdly realistic, like a real candid photo transformed into a polished arcade game battle screen.
Add a full Japanese fighting-game HUD with glossy blue-versus-red interface styling. At the very top, place a center stage title bar reading "東京ディズニーシー　ミッキー広場　ショー最前列バトル" and a large timer in the middle reading "TIME 89". In the top left, add a blue team header "PLAYER1" and team name "最前列ガチ勢A". In the top right, add a red team header "RIVAL" and team name "ライバルグループB". On the left side, stack exactly 5 blue player status panels with portraits, level, Japanese class-like nicknames, HP, SP, and BURST meters. The 5 left-side labels are: "Lv.25 ガチ勢リーダー ユウキ", "Lv.24 筋肉マン タケシ", "Lv.23 眼鏡オタク シンジ", "Lv.23 開角心MAX ケント", "Lv.22 サポート要員 リョウ". On the right side, stack exactly 5 red rival status panels with the labels: "Lv.27 ライバルリーダー ダイキ", "Lv.26 パワフル代表 マサル", "Lv.24 戦略家 コウジ", "Lv.23 熱血漢 リク", "Lv.22 サポート女子 サキ". Each panel should include numeric HP and SP values and segmented BURST gauges, styled like a Japanese arcade RPG-fighter interface.
Place exactly 10 in-battle nameplates above the fighters in the center scene, color-coded blue for the left team and red for the right team. The 10 labels are: "Lv.24 タケシ", "Lv.25 ユウキ", "Lv.23 シンジ", "Lv.23 ケント", "Lv.22 リョウ", "Lv.27 ダイキ", "Lv.26 マサル", "Lv.23 リク", "Lv.22 サキ", "Lv.22 ミサキ".
At the lower left, add a skill menu titled "スキル" listing exactly 5 skills with SP costs: "ダッシュ突撃 SP 20", "肩押し強奪 SP 25", "荷物で場所確保 SP 15", "ロープくぐり SP 10", "本気の根性 SP 50". Beneath that, add a dark description box explaining the highlighted skill "本気の根性" with the Japanese text: "気合で相手を威圧し、どかす！ 一定時間、相手が怯みやすくなる！ （バーストゲージを大きく消費する） 効果時間：10秒".
At the bottom center, add an item menu titled "アイテム" with exactly 5 item slots showing icons and counts: a water bottle "x3", a folded purple towel "x2", a blue drawstring bag "x1", a gray backpack "x1", and a boxed meal "x2". At the lower right, add a quest panel titled "クエスト" with the mission text "ショー開始までに最前列を死守しろ！" and condition text "条件：ライバルグループを全員後ろに押し戻せ！" and countdown text "ショー開始まで：02:30". Beside it, add a mini-map titled "ミッキー広場MAP" showing red and blue dots for both teams in the plaza. Along the very bottom edge, include small controller prompts in Japanese for actions such as skill use, item use, grab/push, and dash.
Use dramatic, saturated lighting, crisp detail, realistic clothing folds, authentic plaza stone pavement, and a high-end Japanese game screenshot look. The image should feel like a ridiculous but believable crossover between a real Tokyo DisneySea crowd photo and a competitive arcade battle game interface.
```


---

## 例 298：Anime Music Bootcamp Promo Poster

**来源：** awesome-gpt-image-2

```text
Create a dramatic Japanese anime-style promotional thumbnail poster for an event, vertical 4:5 composition, ultra-detailed, cinematic, neon-lit, high contrast, designed like a social media announcement image. The main subject is a beautiful anime girl centered slightly right, shown from the waist up, with long flowing {argument name="hair color" default="deep blue"} hair blowing in the wind, decorated with small star hairpins, wearing a dark hoodie and large studio headphones around her neck, against a glowing sunset-to-night city skyline filled with sparkling lights, music-energy particles, lens flares, and flying glowing petals. Her face area is obscured by a soft rectangular blur block. Use a vivid palette of electric blue, violet, magenta, gold, and sunset orange. Fill the design with layered Japanese typography that is crisp, readable, and integrated into the art like a polished event advertisement. Include exactly 8 major text groups: top left copy reading 「始まるのは、キミと創る 音楽の物語。」 with a smaller subcopy beneath reading 「AIを使って、みんなで音楽をつくる特別な3日間。」; top right a glowing marquee sign reading 「GW連休!」 and a smaller neon box below reading 「みんなで最高の音楽をつくろう!」; center main title with small English text 「AI MUSIC BOOTCAMP 2」 above huge Japanese title text 「AI音楽 ブートキャンプ 2」; a gigantic gold metallic announcement across the middle reading 「開催決定!」; a date bar reading 「開催期間」 followed by 「5.2 SAT 土」 and 「5.4 MON 月」; a hashtag callout near the bottom reading 「参加はカンタン!! #AI音楽ブートキャンプ2 をつけて投稿するだけ!」; a lower encouragement line reading 「初心者も大歓迎! みんなで最高の音楽体験を!」; and 3 bottom feature captions with icons reading 「一緒に学ぶ 仲間とつながる」, 「AIで創る 新しい音楽体験」, and 「想いをカタチに 自分だけの1曲を」. On the left edge, add a vertical filmstrip with exactly 4 inset panels showing the same girl in music-related scenes: 1) performing on a stage before a crowd, 2) working at a music production desk with screens and equipment, 3) singing into a microphone, 4) playing an acoustic guitar. Add exactly 2 neon music-themed icon illustrations in the lower area: a tilted smartphone with a music note on the lower left and a glowing microphone with musical notes on the lower right. Make the text effects glossy, luminous, and embossed with gold and white highlights, with energetic streaks and spark explosions around the headline. The overall feeling should be inspiring, celebratory, futuristic, and emotionally uplifting, like a high-impact Japanese Golden Week music bootcamp ad for {argument name="event name" default="AI音楽ブートキャンプ 2"}.
```


---

## 例 299：Spanish GRWM Morning Beauty Thumbnail

**来源：** awesome-gpt-image-2

```text
A vertical 9:16 TikTok-style GRWM beauty thumbnail set in a warm, sunlit Mediterranean-inspired bedroom. A stylish young woman with {argument name="hair color" default="dark brown"} hair in a messy curly updo sits at a marble vanity, leaning forward with one arm folded and the other hand applying lip balm or lipstick to her mouth. Her face is covered by a centered rectangular blur block for privacy, but the rest of her styling is elegant and natural: tan glowing skin, delicate gold necklace with a small round pendant, thin gold bracelet, stacked gold rings, and a white lace camisole with thin straps. In the foreground on the vanity are exactly 7 visible beauty objects: 1 round tabletop vanity mirror on the left, 1 cup holding 5 makeup brushes, 1 clear glass dropper bottle, 1 tall white pump skincare bottle, 1 small black dropper bottle, 1 beige rounded cosmetic sponge or puff, and 1 pale green squeeze tube on the right. The background shows a softly blurred cozy bedroom with 1 arched window on the left, 1 leafy potted plant, 1 bed with white bedding and a mustard accent pillow, exposed wooden ceiling detail, and 1 framed landscape painting on the wall. Use golden-hour sunlight streaming from the left, soft shadows, creamy skin tones, shallow depth of field, luxury lifestyle editorial photography, intimate self-care mood, polished but natural composition. Add bold playful Spanish headline text in the upper left in three stacked lines reading {argument name="headline text" default="Mi rutina de belleza matutina"}, with each line large and rounded, white outline and soft drop shadow, using pastel colors: first line white, second line pink, third line pale yellow. Add 3 pink doodle accent strokes above the headline, 1 curved pink underline-swoosh beneath it, and 1 small yellow sun icon to the right of the last line. Place a clean white {argument name="brand text" default="Pollo.ai"} logo in the upper right. High-end influencer thumbnail aesthetic, crisp product focus in foreground, warm inviting lifestyle scene.
```


---

## 例 300：Cinematic City Explosion Chase

**来源：** awesome-gpt-image-2

```text
A cinematic photorealistic action scene in a rainy downtown city street canyon, showing {argument name="main subject" default="a dark-haired man in his 30s"} sprinting directly toward the camera in the center foreground with a tense survival expression, wearing a soaked dark jacket, dark shirt, and dark pants, mid-stride with one arm pumping forward. Behind him, a massive urban explosion tears through the street and lower facade of a high-rise building, sending a huge cloud of smoke, fire, dust, shattered concrete, glass, and metal debris outward in all directions. The scene includes exactly 3 visible damaged vehicles: 1 dark sedan in the left foreground with headlights on and a crumpled hood splashing through rainwater, 1 wrecked dark car in the right midground with severe front-end damage, and 1 overturned or airborne black SUV tilted upward behind it on the right side. Wet asphalt reflects headlights, firelight, and gray skyscrapers. Dense debris fills the air, with chunks of rubble frozen in motion. Overcast stormy daylight, desaturated blue-gray color palette with orange fire accents, dramatic motion blur in flying debris but sharp focus on the running figure, low-angle wide-lens composition, blockbuster disaster-movie realism, ultra-detailed textures, high contrast, dynamic depth, volumetric smoke, rain spray, cinematic lighting. Add a white {argument name="watermark text" default="Pollo.ai"} logo in the top-right corner.
```


---

## 例 301：Anime VTuber Minecraft Stream Thumbnail

**来源：** awesome-gpt-image-2

```text
A vibrant anime-style YouTube thumbnail for a livestream gaming broadcast, in a wide 16:9 composition, with a neon purple and pink streamer room. Center the scene on a cute catgirl VTuber sitting at a desk, shown from the waist up, leaning forward energetically with one hand on a computer mouse and the other hand reaching toward the viewer. She has {argument name="hair color" default="light orange-blonde"} bob-cut hair with soft bangs, fluffy brown-and-cream cat ears, and a visible cat tail. Her face is intentionally obscured by a solid rectangular censor block in the center. She wears a black-and-white maid-inspired outfit with a frilly white blouse, black dress bodice, puff sleeves, white ruffles, black ribbon bow, and a gold bell choker. Place a mechanical keyboard with bright RGB lighting on the desk, a glowing gaming mouse, and a streamer microphone on the far left with pink-purple LED lighting. Put 2 cat-themed desk items in the foreground: a plush cat face on the bottom left and a black cat-shaped mug on the bottom right. Behind her is a gaming chair with paw-print details. On the left side, add large bold Korean headline text in thick white block letters with black fill shadows and a glowing purple outline, stacked in 2 lines: {argument name="headline text" default="방송중 대참사"}. Below it, add a smaller yellow comic-style burst caption with black outline reading {argument name="sub text" default="> 크리퍼 실화냐"}. On the right side, show 1 large computer monitor angled inward, displaying a Minecraft-like scene with bright blue sky, green trees, water, and a large green Creeper popping out toward the viewer, outlined dramatically like a sticker cutout. Add starburst effects and neon accents around the monitor to heighten the chaos. Use exaggerated thumbnail aesthetics: ultra-saturated colors, sharp cel shading, thick outlines, glossy highlights, high contrast, dynamic perspective, and a clickworthy streamer-disaster mood.
```


---

## 例 302：Cozy Anime ASMR Ear Massage Girl

**来源：** awesome-gpt-image-2

```text
A soft, dreamy anime illustration of a cute young woman doing ASMR in a cozy bedroom at night, seated close to the viewer with her knees pulled up and a black 3Dio-style binaural microphone centered in front of her. She has {argument name="hair color" default="deep violet"} hair in a loose messy updo with wispy bangs framing her face, large sparkling {argument name="eye color" default="blue"} eyes, a gentle blush, and a sweet open-mouth smile. Her head is tilted slightly toward the viewer in a warm, affectionate pose. She wears a delicate white lace camisole with thin straps and an oversized fluffy knit cardigan in {argument name="cardigan color" default="soft pink-lavender"} draped off her shoulders, creating a tender, intimate late-night healing atmosphere. Both hands lightly touch the white silicone ears of the microphone as if about to give an ear massage. The room is softly lit with pink and amber ambient lighting, heavy curtains in the background, a bed or sofa with plush cushions, warm fairy-light bokeh, and a small plant on the right side. Add glowing handwritten Japanese neon text integrated into the composition: on the left, 4 text elements reading "とろける", "耳", "マッサージ", and "ASMR" with 2 small heart symbols; on the right, vertical text reading "いっぱい癒してあげるね…♡". Use a polished modern anime style, highly detailed face and hair, glossy eyes, smooth luminous skin, soft shading, pastel highlights, shallow depth of field, romantic cozy streamer-thumbnail composition, and a soothing feminine color palette dominated by pink, lavender, cream, and warm gold.
```


