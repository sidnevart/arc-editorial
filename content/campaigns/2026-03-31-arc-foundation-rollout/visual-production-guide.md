# Visual Production Guide

## Общий визуальный стиль серии

### Настроение

- взрослый
- инженерный
- спокойный, но дерзкий
- не “AI magic”, а “designed system”

### Что избегаем

- неон
- киберпанк
- роботы
- humanoid AI
- стоковые “светящиеся мозги”
- псевдофутуристические dashboards без смысла

### Что держим

- светлый фон
- графитовые поверхности
- глубокий зелёный
- тёплый песочный / терракотовый акцент
- ощущение продукта, которому можно доверять

## Правило выбора визуала

### Используем GPT image prompt, если:

- тема абстрактная или архитектурная
- важен концепт, а не буквальный UI

### Используем реальный скриншот, если:

- продуктовая сила именно в интерфейсе
- нужно доказать, что это реально уже существует

## Первая волна: конкретные визуалы

### 1. Runtime over model

- Asset:
  - `agent runtime over model`
- Format:
  - hero image 16:9
- Type:
  - GPT image
- Prompt:

Create a premium editorial illustration for a technical article about an AI runtime built on top of a strong reasoning model. Show a layered system: at the bottom a compact powerful reasoning core, above it distinct layers for context, policy, budget, artifacts, environment rules, and desktop surfaces. The visual must communicate “operating layer over intelligence”, not competition between products. Avoid robots, faces, sci-fi neon, and fantasy dashboards. Use a calm, mature product-design aesthetic with a light background, graphite structure, deep green accents, and warm sand or terracotta details. High trust, high clarity, serious engineering mood. Horizontal 16:9.

### 2. ARC over Codex LinkedIn framing

- Asset:
  - `arc over codex operating layer`
- Format:
  - square or 4:5
- Type:
  - GPT image
- Prompt:

Create a visual for a LinkedIn post about a local-first AI runtime operating above a reasoning engine. The composition should show a clean central core with surrounding system rings labeled conceptually as context, environment, budget, and artifacts, without using logos or visible brand names. Make it feel premium, sharp, and product-like, not like sci-fi concept art. Use light background, graphite and forest green tones, with subtle warm accents. The image should communicate control, discipline, and scalability.

### 3. Local miniapps from chat

- Asset:
  - `local miniapps from chat`
- Type:
  - real screenshot first, GPT fallback
- Preferred screenshot:
  - открытый чат ARC
  - в сообщении видна карточка миниаппа
  - рядом или поверх видно, что миниапп реально открыт внутри ARC
  - важно, чтобы было видно именно переход “сообщение -> живой результат”
- Screenshot notes:
  - чистый viewport
  - без лишних системных элементов
  - оставить тему, заголовок миниаппа, один живой экран симуляции
- GPT fallback prompt:

Create a premium product editorial image showing an AI chat that turns directly into a live local mini app. On the left, a structured chat message; on the right, an embedded mini simulation running inside the same application. The mood should communicate immediacy, ownership, and local execution. Avoid robots and generic AI clichés. Use a modern product aesthetic with a light background, clean glass and paper surfaces, deep green accents, and soft warm highlights. Horizontal 16:9.

### 4. Rich outputs

- Asset:
  - `rich outputs make chat a workspace`
- Type:
  - real screenshot first
- Preferred screenshot:
  - один чат, где одновременно видно:
    - обычный текст ответа
    - диаграмму или документную карточку
    - карточку демо/симуляции
  - нужно, чтобы читалось: “одно сообщение даёт несколько типов результата”
- Screenshot notes:
  - не перегружать
  - если всё в один кадр не влезает, взять композицию с 2–3 соседними structured outputs
- GPT fallback prompt:

Create an editorial product illustration showing one AI message unfolding into multiple result types: text, diagram, document, and mini app. The goal is to communicate that rich outputs are functional work surfaces, not decoration. Keep the style modern, premium, calm, and trustworthy. Light background, elegant cards, deep green and warm neutral accents, no cyberpunk.

### 5. Go desktop

- Asset:
  - `why we built desktop in go`
- Type:
  - screenshot + GPT overlay optional
- Preferred screenshot:
  - desktop ARC app in clean chat-first state
  - желательно с видимым local-first feel:
    - left rail
    - thread
    - details or runtime surface
  - без clutter
- Secondary visual:
  - простой schema-like GPT image про desktop surface над local runtime
- Prompt:

Create a serious editorial illustration about a desktop application built directly on top of a local AI runtime. Show a clean desktop surface above underlying local processes, artifacts, and runtime blocks. The image should feel grounded and engineering-oriented, not flashy. Light background, graphite structure, deep green accents, subtle warm tones. No robots, no code rain, no neon.

### 6. Context tool article

- Asset:
  - `context tool controls model attention`
- Type:
  - GPT image
- Prompt:

Create a technical editorial image about a standalone context tool that filters noise and directs model attention. Show a broad, messy source field on the left—docs, code, notes, memory, indexes—and a compact, sharp context pack on the right, as if the system precisely focused the flow. No AI brains or humanoids. Premium engineering aesthetic, light background, graphite, deep green, warm sand accents. Horizontal 16:9.

### 7. Context tool short posts

- Assets:
  - `ctx bench`
  - `context selection must be explainable`
  - `noise reduction is a core context metric`
- Type:
  - simple text card or clean GPT graphic
- Prompt:

Create a clean social card for a technical post about context selection quality in an AI runtime. Show a comparison between a noisy candidate pool and a smaller selected context pack, with subtle signals of benchmarking, evidence, and filtering. Minimal, premium, product-oriented, light background, deep green and graphite colors.

### 8. Multi-agent environment rules

- Asset:
  - `multi-agent environment rules`
- Type:
  - GPT image
- Prompt:

Create an editorial illustration about environment rules in a multi-agent platform. Show several agent modules inside one controlled system, each with clear boundaries for hooks, memory scopes, runtime permissions, and policy layers. The message should be “scalable because constrained”, not “chaotic swarm”. Mature engineering visual language, light background, graphite structure, deep green, restrained warm accents. Horizontal 16:9.

### 9. Token efficiency article

- Asset:
  - `token efficiency without quality loss`
- Type:
  - GPT image
- Prompt:

Create a refined editorial illustration for an article about token efficiency in an AI runtime. Show a noisy input flow being filtered and routed: some work stays local, some goes to the model, and the final context becomes smaller and cleaner without losing structure. Avoid money clichés. The message is “noise reduction and routing discipline”, not finance. Light background, green and graphite palette, premium product-tech look. Horizontal 16:9.

### 10. Budget / low-limit / provider footprint posts

- Assets:
  - `provider footprint matters`
  - `low-limit mode is discipline`
  - `budget overrides make policy manageable`
- Type:
  - text cards or GPT social images
- Prompt:

Create a LinkedIn/X-ready visual about budget policy and routing discipline in an AI runtime. Show a clean decision flow with policy layers, routing branches, and execution traces. Emphasize control and explainability rather than cost dashboards. No charts overloaded with numbers. Mature product design, light background, deep green, graphite, warm neutrals.

### 11. Sandbox / hooks / environment operations

- Assets:
  - `hook runner is where platform begins`
  - `hook memory needs a mediated path`
  - `sandbox profile builds trust`
- Type:
  - GPT image
- Prompt:

Create a premium editorial illustration about controlled execution of extensions in an AI platform. Show a bounded execution box, lifecycle stages, audit traces, and mediated system interfaces, all in a clean technical composition. The image should communicate trust through boundaries. Avoid sci-fi motifs. Light background, graphite structure, deep green accents, understated warm highlights.

### 12. Founder-style closing post

- Asset:
  - `don’t build another AI chat, build an environment`
- Type:
  - text-forward poster
- Preferred format:
  - typographic card with one punchline
- Text:
  - “Не стройте ещё один AI-чат. Стройте среду.”
- Visual note:
  - сделать очень чисто
  - много воздуха
  - минимальный product grid или тонкая системная подложка

## Что можно добрать реальными скринами позже

### Strong screenshot targets

1. Чат с miniapp card + запущенная симуляция
2. Чат со structured outputs: текст + диаграмма + карточка
3. `Детали чата` со `Сейчас запущено`
4. Список тем + chat-first shell
5. Agent chooser / short agent guidance

## Screenshot production checklist

- убрать случайные старые темы/личные данные
- использовать один и тот же visual scale
- не оставлять сломанные или промежуточные UI states
- если в скрине есть miniapp, он должен реально выглядеть рабочим, а не пустым контейнером
- не публиковать слишком мелкие скрины, где ничего не читается

## Final rule

Каждый визуал должен усиливать один тезис.

Если картинка просто “про AI вообще”, она для этой серии слабая.
