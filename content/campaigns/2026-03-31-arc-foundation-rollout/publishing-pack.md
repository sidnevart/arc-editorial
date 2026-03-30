# Publishing Pack

## Цель

Превратить уже написанный контент не в “папку с файлами”, а в серию публикаций, которая:

- последовательно объясняет ARC
- не повторяется слишком сильно
- чередует продукт, UX, архитектуру и cost/control
- постоянно возвращает аудиторию к главной мысли:
  - **ARC — это runtime над Codex, а не ещё один AI-чат**

## Главный narrative

### Базовая формула

- Codex даёт reasoning
- ARC даёт context, budget, environment, artifacts, local runtime и рабочие surfaces

### Что аудитория должна вынести после всей серии

1. ARC — это не wrapper ради wrapper’а
2. local miniapps и rich outputs меняют тип AI UX
3. context management у нас — это отдельная система, а не helper
4. multi-agent growth требует environment rules
5. token efficiency — это вопрос качества системы
6. desktop на Go здесь логичен, потому что ядро local-first и процессное

## Первая волна: 15 публикаций

### 1. Большая статья

- File: `content/editorial/articles/2026-03-31-01-pochemu-agentu-nuzhen-runtime-a-ne-prosto-model.md`
- Цель:
  - задать главный framing
- Каналы:
  - сайт
  - Habr
  - VC
  - Substack

### 2. LinkedIn framing post

- File: `content/editorial/linkedin/2026-03-31-01-arc-nad-codex-eto-ne-obvyortka-a-operating-layer.md`
- Цель:
  - быстро объяснить product positioning

### 3. Short post

- File: `content/editorial/posts/2026-03-31-01-model-bez-runtime-eto-dorogoy-khaos.md`
- Цель:
  - дать punchy short version для X / Telegram

### 4. Большая статья

- File: `content/editorial/articles/2026-03-31-02-kak-my-podnimaem-lokalnye-miniappy-pryamo-iz-chata.md`
- Цель:
  - показать самый зрелищный UX-угол

### 5. LinkedIn post

- File: `content/editorial/linkedin/2026-03-31-02-lokalnye-miniappy-iz-chata-menyayut-sam-tip-ai-ux.md`
- Цель:
  - привязать миниаппы к продуктовой ценности

### 6. Short post

- File: `content/editorial/posts/2026-03-31-23-restartuemye-miniappy-vazhnee-chem-odnorazovoe-wow-demo.md`
- Цель:
  - увести разговор из “demo wow” в “product truth”

### 7. Большая статья

- File: `content/editorial/articles/2026-03-31-03-pochemu-bogatye-soobshcheniya-v-chate-eto-ne-kosmetika.md`
- Цель:
  - объяснить rich outputs как рабочую форму результата

### 8. LinkedIn post

- File: `content/editorial/linkedin/2026-03-31-03-rich-chat-outputs-eto-ne-krasivosti-a-produkty-vnutri-soobshcheniya.md`
- Цель:
  - product angle для широкой инженерной аудитории

### 9. Большая статья

- File: `content/editorial/articles/2026-03-31-05-context-tool-eto-ne-ficha-a-sistema-upravleniya-vnimaniem.md`
- Цель:
  - зацепить инженерную аудиторию на `ctx`

### 10. Short post

- File: `content/editorial/posts/2026-03-31-15-ctx-bench-nuzhen-chtoby-ne-sporit-vkusami.md`
- Цель:
  - дать быстрый угол про benchmark discipline

### 11. Большая статья

- File: `content/editorial/articles/2026-03-31-06-kak-ne-slomat-sredu-kogda-agentov-stanovitsya-mnogo.md`
- Цель:
  - показать depth платформенного мышления

### 12. LinkedIn post

- File: `content/editorial/linkedin/2026-03-31-06-multi-agent-sreda-lomaetsya-bez-pravil-ranshe-chem-vam-kazhetsya.md`
- Цель:
  - выйти на техлидов и platform builders

### 13. Большая статья

- File: `content/editorial/articles/2026-03-31-07-kak-my-ekonomim-tokeny-ne-deshevim-kachestvo.md`
- Цель:
  - завести cost/control discussion

### 14. LinkedIn post

- File: `content/editorial/linkedin/2026-03-31-07-ekonomiya-tokenov-eto-ne-bukhgalteriya-a-kachestvo-sistemy.md`
- Цель:
  - дать зрелый budget framing

### 15. Founder-style closer

- File: `content/editorial/posts/2026-03-31-32-ne-stroyte-eshe-odin-ai-chat-stroyte-sredu.md`
- Цель:
  - завершить первую волну сильной фразой

## Вторая волна

Во второй волне добиваем более “системные” и менее зрелищные, но очень сильные темы:

- Go desktop
- ARC over Codex positioning article
- provider footprint
- low-limit mode
- hook runner
- sandbox profile
- deterministic artifacts
- provenance
- source diversity
- path-family weighting
- subtree dominance
- fingerprint-aware reuse

## Ритм публикации

### Спокойный устойчивый ритм

- 2 больших материала в неделю
- 2 LinkedIn-поста в неделю
- 4–5 short posts в неделю

### Агрессивный ритм

- 3 больших материала в неделю
- 3 LinkedIn-поста в неделю
- 1 short post почти каждый день

## Лучшие связки

### Связка 1

- article: runtime over model
- LinkedIn: operating layer
- short post: model without runtime is chaos

### Связка 2

- article: local miniapps
- LinkedIn: miniapps change AI UX
- short post: restartable miniapps beat one-off demos

### Связка 3

- article: rich outputs
- LinkedIn: products inside the message
- short post: rich outputs make chat a workspace

### Связка 4

- article: context tool
- LinkedIn: context tool as moat
- short posts:
  - `ctx bench`
  - explainable context selection
  - noise reduction

### Связка 5

- article: multi-agent environment rules
- LinkedIn: why multi-agent systems need rules
- short posts:
  - presets must also constrain
  - hook runner
  - sandbox profile

### Связка 6

- article: token efficiency
- LinkedIn: token efficiency is system quality
- short posts:
  - local-first is not anti-model
  - provider footprint matters
  - budget overrides
  - low-limit mode is discipline

## Где нужен скриншот, а где лучше GPT image

### Лучше скриншот

- local miniapps
- rich chat outputs
- Go desktop
- chat details / live runtime truth
- agent chooser / short guidance

### Лучше GPT image

- runtime over model
- context tool as system of attention
- multi-agent environment rules
- token efficiency as noise reduction
- ARC over Codex positioning

## Чего не делать

- не постить 5 очень похожих budget-постов подряд
- не перегружать одну неделю только deep-архитектурой
- не использовать абстрактные sci-fi картинки
- не делать visual language разным на каждом втором материале

## Главная редакторская проверка перед публикацией

Перед каждым материалом спросить:

1. Это звучит как человек, а не как корпоративная копирайтинг-масса?
2. Тут есть одна сильная мысль?
3. Мы не врём про реализованность?
4. Из материала понятно, почему ARC нужен именно поверх Codex?
5. Визуал реально усиливает тезис, а не просто “чтобы было красиво”?
