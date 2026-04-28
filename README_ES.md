<div align="center">

# 🖼️ Image Inspirer.skill

<br>

> **668+ casos de prompts de imagen GPT-Image2 verificados en combate, cubriendo 13 categorías principales — tu fuente de inspiración y referencia creativa para la generación de imágenes con IA**

[![License: Apache-2.0](https://img.shields.io/badge/License-Apache--2.0-orange.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>

**¿Luchando con los prompts de imagen?** <br>
**¿No encuentras ejemplos confiables en ningún lado?** <br>
**Toda la inspiración que necesitas está aquí.**

<br>

Más que simples plantillas de prompts — una **metodología creativa verificada en combate**. <br>
Cada caso incluye una imagen de referencia terminada, para que puedas verla, aprenderla y adaptarla.

---

**Navegación Rápida**

[Demos](#demos) | [Instalación](#instalación) | [Estadísticas](#estadísticas) | [Casos Destacados](#casos-destacados) | [Estructura](#estructura) | [Guía de Errores](#guía-de-errores) | [Sobre Mí](#sobre-mí)

<br>

**Idiomas**

[中文](README.md) · [English](README_EN.md) · [日本語](README_JA.md) · [한국어](README_KO.md)

<br>

</div>

---

## Demos

### Escenario 1: Buscar y Reutilizar

¿Ya sabes lo que necesitas? Busca referencias directamente:

```
Usuario    ❯ ¿Hay ejemplos de visualización infográfica?

image-inspirer  ❯ Leyendo 图表与信息可视化/prompt.md, encontré 55 casos infográficos

                  【Caso 1】Urban Metabolism Atlas
                  Tipo: Infografía | Relación: 9:16

                  城市生命系统图谱 / Urban Metabolism Atlas
                  Vertical 9:16 isometric cutaway infographic "城市生命系统图谱"。
                  Smart city from sky to bedrock: skyscrapers, streets, subway...
                  Style: engineering white paper + scientific atlas, 8K.

                  【Caso 2】Diagrama de Red Neuronal IA
                  ...
```

### Escenario 2: Necesidades Vagas, Descubrimiento Guiado

¿No sabes qué quieres? Te ayudo a definirlo:

```
Usuario    ❯ Dame una imagen bonita

image-inspirer  ❯ Iniciando marco de inspiración, preguntando paso a paso:

                  Q1: ¿Qué tipo quieres?
                  → Póster / Fotografía / Ilustración / UI / Otro

                  Q2: ¿Cuál es el caso de uso?
                  → Redes sociales / E-commerce / Colección personal / Propuesta comercial

                  Q3: ¿Preferencia de estilo?
                  → Fotorrealista / Cinematográfico / Minimalista / Ilustración / Estética china

                  Según tus respuestas, propongo 2-3 direcciones.
```

### Escenario 3: Creación Personalizada

Requisitos claros pero necesitas un prompt a medida:

```
Usuario    ❯ Diseña un póster de marca para la empresa tecnológica "AI之道"

image-inspirer  ❯ Leyendo casos de póster en 海报与排版/prompt.md
                  ↓ Creación personalizada

                  Genera un póster de marca premium para empresa tech, vertical 9:16.
                  Logo: Bagua-Taiji fusionado con red neuronal, líneas negras puras + brillo cian
                  Título: "AI之道" (tipografía Song, peso ultra ligero)
                  Subtítulo: "Dao of Artificial Intelligence"
                  Colores: Fondo blanco puro + negro puro + acento cian
                  Estilo: Minimalista, amplio espacio negativo, sensación premium
                  Restricción: El texto debe ser claramente legible, sin efectos neón
```

### Escenario 4: Póster de Marca Deportiva

```
Usuario    ❯ Genera un póster comercial de marca deportiva con sensación de poder

image-inspirer  ❯ Leyendo casos de póster deportivo en 海报与排版/prompt.md

                  Diseña un póster Campaign comercial de marca deportiva.
                  Sujeto: Atleta/hombre musculoso, pose de poder.
                  Accesorio clave: Mancuerna/guantes de boxeo, proporciones exageradas como ancla visual.
                  Titular: "ROMPE EL LÍMITE"
                  Estilo visual: Anuncio premium de marca deportiva, iluminación dramática, suelo reflectante.
                  Restricciones: Sujeto nítido, texto legible, tono unificado.
                  Salida: 4:5, visual comercial deportivo optimizado para redes sociales.
```

---

## Instalación

### Método 1: CLI (para desarrolladores)

Instala directamente con npx:

```bash
npx skills add wukongnotnull/image-inspirer
```

Después de instalar, dile a tu Agent:

```markdown
> Encuentra ejemplos de visualización infográfica
> Genera un prompt de póster estilo chino
> Dame una imagen bonita
```

### Método 2: Conversacional (para no desarrolladores)

Copia esto a tu Agent:

```bash
Instalar este skill: https://github.com/wukongnotnull/image-inspirer
```

---

## Estadísticas

| Categoría | Cant. | Descripción |
|-----------|:-----:|-------------|
| UI e Interfaces | 122 | UI de apps, páginas web, capturas de streaming, componentes |
| Pósters y Maquetación | 91 | Pósters comerciales, de cine, de eventos, portadas |
| Otras Aplicaciones | 82 | Composiciones creativas, escenas divertidas, mashups |
| Ilustración y Arte | 78 | Anime, tinta china, acuarela, garabato, sci-fi |
| Infografía y Visualización | 76 | Infografías, diagramas de flujo, despieces, visualización de datos |
| Fotografía y Realismo | 55 | Retratos, fotografía de producto, editoriales de moda |
| E-commerce y Productos | 54 | Imágenes principales, páginas de detalle, anuncios de producto |
| Personajes y Roles | 36 | Diseño de personajes, cartas, desgloses de acción |
| Branding y Logos | 21 | Diseño de logos, visuales de marca, fuentes de iconos |
| Arquitectura y Espacio | 17 | Diseño de interiores, renders arquitectónicos, escenas urbanas |
| Escenas y Narrativa | 14 | Escenas cinematográficas, marcos de historia, guiones gráficos |
| Estilos Históricos y Antiguos | 13 | Estilos dinásticos, figuras históricas, chic chino |
| Documentos y Publicaciones | 9 | Maquetación de revistas, menús, periódicos, libros de texto, notas |

**Total: 668 casos verificados, cada uno con imagen de referencia**

---

## Casos Destacados

### 🖥️ UI e Interfaces

| Caso | Descripción | Destacado |
|------|-------------|-----------|
| Capturas de App | Diseño UI iOS/Android | Plataforma clara + relación + maquetación |
| Capturas de Redes Sociales | Posts, diseño de perfil | Simulación UI realista |
| Landing Pages | Diseño de página de producto | Jerarquía de información clara |

### 📊 Infografía y Visualización

| Caso | Descripción | Destacado |
|------|-------------|-----------|
| Urban Metabolism Atlas | Infografía isométrica de corte | Estilo libro blanco de ingeniería |
| Diagramas de Flujo | Visualización comparativa de datos | Lógica clara, codificación por colores |
| Diagrama de Red Neuronal IA | Visualización de concepto técnico | Conceptos complejos hechos intuitivos |

### 🎨 Pósters y Maquetación

| Caso | Descripción | Destacado |
|------|-------------|-----------|
| Campaign Comercial | Visuales de marketing de marca | Sujeto nítido, texto legible |
| Pósters de Cine | Visuales promocionales de películas | Atmósfera fuerte, composición refinada |
| Pósters Chic Chino | Visuales comerciales estilo chino | Elementos tradicionales modernizados |

### 📸 Fotografía y Realismo

| Caso | Descripción | Destacado |
|------|-------------|-----------|
| Retrato | Tomas de retrato de personaje | Textura de piel realista |
| Fotografía de Producto | Tomas comerciales de producto | Iluminación refinada, materiales precisos |
| Fotografía de Escena | Fotografía atmosférica de espacio | Iluminación cinematográfica |

### 🎭 Ilustración y Arte

| Caso | Descripción | Destacado |
|------|-------------|-----------|
| Ilustración Estilo Japonés | Personajes estilo anime | Estilo de pincel fijado, evita look plástico |
| Ilustración Estilo Chino | Estética tradicional china | Tinta/gongbi/color intenso |
| Ilustración Plana | Estilo minimalista moderno | Bloques de color limpios, capas claras |

---

## Estructura

```
image-inspirer/
├── README.md                    # Docs + guía de errores
├── SKILL.md                     # Definición del skill
├── db/
│   ├── UI与界面/                # prompt.md + images/
│   ├── 图表与信息可视化/         # prompt.md + images/
│   ├── 海报与排版/              # prompt.md + images/
│   ├── 商品与电商/              # prompt.md + images/
│   ├── 品牌与标志/              # prompt.md + images/
│   ├── 建筑与空间/              # prompt.md + images/
│   ├── 摄影与写实/              # prompt.md + images/
│   ├── 插画与艺术/              # prompt.md + images/
│   ├── 人物与角色/              # prompt.md + images/
│   ├── 场景与叙事/              # prompt.md + images/
│   ├── 历史与古风题材/           # prompt.md + images/
│   ├── 文档与出版物/             # prompt.md + images/
│   └── 其他应用场景/             # prompt.md + images/
└── LICENSE
```

13 directorios de categoría, cada uno con `prompt.md` (colección de prompts) e `images/` (imágenes terminadas).

---

## Guía de Errores

### Principios Generales

| Principio | Descripción |
|-----------|-------------|
| Tipo Claro | Define claramente: póster / UI / fotografía, etc. |
| Sujeto Específico | Describe la persona/objeto/escena específica, evita vaguedad |
| Estilo Fijado | Especifica explícitamente: ilustración / fotográfico / cinematográfico |
| Parámetros Completos | Incluye relación, resolución, composición y otros parámetros clave |
| Texto Legible | Si se necesita texto, exige explícitamente que sea claramente legible |

### Puntos Clave por Tipo

| Tipo | Enfoque | Errores Comunes |
|------|---------|-----------------|
| UI | Plataforma clara + relación + maquetación | Instrucciones vagas causan caos en maquetación |
| Póster | Visual principal específico, fijar título/subtítulo | Texto borroso, errores de maquetación |
| Fotografía | Añadir textura de piel, grano de película | Look plástico de IA, excesivamente suave |
| Ilustración | Fijar estilo de pincel | Look plástico por defecto, deriva de estilo |
| E-commerce | Prominencia del producto + iluminación realista | Deformación del producto, iluminación inconsistente |
| Logo | Reconocibilidad + escalabilidad | Demasiado complejo, no escalable |

---

## Sobre Mí

**悟空非空也 (wukongnotnull)** — Fundador de AI之道 (Way to AI), desarrollador indie, creador de contenido.

| Plataforma | Enlace |
|------------|--------|
| 🌐 Sitio Web | [waytoai.cn](https://waytoai.cn) |
| 𝕏 Twitter | [@wukongnotnull](https://x.com/wukongnotnull) |
| 📺 Bilibili | [悟空非空也](https://space.bilibili.com/456634391) |
| ▶️ YouTube | [悟空非空也](https://www.youtube.com/@wukongnotnull) |
| 📕 Xiaohongshu | [悟空非空也](https://www.xiaohongshu.com/user/profile/5ca89c2f000000001100952b) |
| 💬 WeChat | Buscar "悟空非空也" |

---

## Agradecimientos

Materiales parcialmente obtenidos de:

- [YouMind](https://youmind.com/)
- [OpenNana](https://opennana.com/)
- [awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2)

---

<div align="center">

Apache-2.0 license © [悟空非空也](https://github.com/wukongnotnull)

</div>
