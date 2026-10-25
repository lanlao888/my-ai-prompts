# 📸 AI 商业摄影 Prompt 知识库：奢侈品与商品摄影

> **适用模型**：Midjourney v6, Flux.1, SDXL, ComfyUI
> **核心风格**：极简高级感、商业大片光影、极致材质细节

---

## 🛍️ 1. 核心商品场景（Master Prompts）

### 场景 01：高奢腕表/饰品 - 大理石与静物微距
- **🇬🇧 英文 Prompt：**
  > Studio product photography of a luxury wrist watch, resting on a dark vein white marble block. Elegant rim lighting, subtle caustics reflection, soft shadows. Shot on Hasselblad H6D-100c, 85mm macro lens, f/8, ultra-sharp focus, crisp details, commercial lighting, 8k resolution, photorealistic. --ar 4:3 --v 6.0

- **🇨🇳 中文解释/标注文档：**
  > 适用于手表、珠宝、高档饰品。强调微距锐度、大理石纹理与轮廓光。

---

## 🛠️ 2. 商品摄影常用模块库

### 🅰️ 灯光与布光（Lighting）
- `Studio lighting` —— 影棚专业布光
- `Soft box lighting` —— 柔光箱（光线平滑均匀）
- `Rim lighting / Accent light` —— 轮廓光/强调光（凸显产品边缘立体感）
- `Volumetric lighting` —— 体积光/束光

### 🅱️ 材质与衬托背景（Background & Props）
- `Dark vein white marble` —— 带深色纹理的白色大理石
- `Matte black acrylic reflection` —— 哑光黑丙烯酸反光台
- `Satin silk background` —— 丝绸/缎面背景（适合香水、化妆品）
- `Water droplets on glass` —— 玻璃上的水珠（适合保养品、饮品）

### Ⓒ 摄影设备与参数（Camera & Lens）
- `Hasselblad H6D-100c` / `Phase One XF` —— 哈苏/飞思中画幅相机（商业大片质感）
- `100mm macro lens, f/8` —— 微距镜头，保证全景清晰
- `Ultra-sharp focus, depth of field` —— 极锐聚焦与自然虚化

---

## 🔗 3. 垫图/图生图专属工作流（Image Prompt Workflow）

> **适用场景**：直接引用商品详情图（如 `https://www.luxurymall.cc/item/1`），利用 AI 替换背景并生成商业大片光影。

### ⚙️ 模版公式（Copy & Paste）：
`[商品详情图URL]` + `[保持原样控制词]` + `[光影与背景材质描述]` + `[相机与画质参数]` + `--iw 2.0`

---

### 💡 常用范例（以 Midjourney / Flux 为例）：

1. **手表/高奢饰品大片**：
   > `https://www.luxurymall.cc/item/1` classic round stainless steel and rose gold two-tone watch, exact same dial and bracelet links, rested on a dark vein white marble block, studio product photography, elegant rim lighting, soft caustics reflection, Hasselblad H6D-100c, 85mm macro lens, f/8, ultra-sharp focus, crisp details, commercial lighting, 8k resolution, photorealistic --iw 2.0 --ar 4:3 --v 6.0

2. **皮具/包包高档展示**：
   > `https://www.luxurymall.cc/item/105` exact same leather bag structure and metallic lock hardware, placed on a minimalist dark grey cement pedestal, warm accent spotlight, soft shadows, high-end luxury fashion editorial style, Phase One XF camera, crisp texture details, ultra-photorealistic --iw 2.0 --ar 3:4 --v 6.0

3. **香水/高端护肤品艺术感大片**：
   > `https://www.luxurymall.cc/item/3` exact same bottle silhouette and label, surrounded by smooth water ripples and floating flower petals, backlit studio photography, volumetric light rays, soft satin background, cinematic product shot, 8k, hyper-detailed --iw 2.0 --ar 16:9 --v 6.0

---

## ⚠️ 4. 商品保真防变形最佳实践（Product Precision Guide）

为了防止 AI 将手表表盘、Logo、表带扭曲为其他品牌或款式（例如把欧米茄/圆盘改造成皇家橡树/八角盘），请遵循以下三种解决方案：

### 方案 1：提高参考图权重（最简单，直接垫图）
* 在 Midjourney 结尾必须加上 **`--iw 2.0`**（将图片参考权重拉到最大）。
* 提示词中明确写入产品关键特征，如：`exact same dial design, exact bracelet links, classic round case`。

### 方案 2：局部重绘（MJ Vary Region / Inpaint）
1. 先生成满意的大理石/影棚背景图。
2. 使用 **`Vary (Region)`** 涂抹原图中的手表区域。
3. 输入商品图 URL

## 🎨 5. 预设风格匹配库（Style Presets）

- **[Style-A] 经典奢华黑金（适合：黄金/玫瑰金/正装商务表）**
  > dark vein white marble block, warm accent spotlight, gold reflection, high-end luxury, commercial lighting

- **[Style-B] 赛车/运动极客（适合：理查米尔/碳纤维/彩色陶瓷）**
  > minimalist dark carbon fiber texture background, sharp edge rim light, dramatic shadows, futuristic luxury, athletic vibe

- **[Style-C] 极简冷调金属（适合：全钢表/白金/银色盘面）**
  > matte black acrylic stage, cool frosted glass background, soft diffused light, elegant minimalist

- **[Style-D] 活力缤纷/潮牌大片（适合：Baby Blue/鲜艳胶带款）**
  > clean pastel gradient background, bright softbox lighting, contemporary studio art fashion
