# Psychology & Philosophy

Interactive presentations exploring foundational thinkers in psychology and philosophy — from depth psychology to phenomenology, process thought to aesthetics.

**Live site:** [brendanjameslynskey.github.io/Psychology_Philosophy](https://brendanjameslynskey.github.io/Psychology_Philosophy)

## Presentations

### Psychology

| # | Topic | Slides | Status |
|---|-------|--------|--------|
| 01 | [Carl Jung — The Architecture of the Psyche](Jung/) | 17 | Complete |
| 02 | [Sigmund Freud — The Foundations of Psychoanalysis](Freud/) | 17 | Complete |
| 03 | [Carl Rogers — The Person-Centred Approach](Rogers/) | 17 | Complete |
| 04 | [Alfred Adler — Individual Psychology & the Striving for Significance](Adler/) | 17 | Complete |
| 05 | [Viktor Frankl — The Search for Meaning](Frankl/) | 17 | Complete |
| 06 | [Jean Piaget — Genetic Epistemology & Cognitive Development](Piaget/) | 17 | Complete |
| 07 | [Erich Neumann — The Origins & History of Consciousness](Neumann/) | 17 | Complete |
| 08 | [Joseph Campbell — Myth, Meaning & the Hero's Journey](Campbell/) | 17 | Complete |
| 09 | [Friedrich Nietzsche — The Psychology of the Depths](Nietzsche/) | 17 | Complete |
| 10 | [Fyodor Dostoevsky — The Novelist as Psychologist](Dostoevsky/) | 17 | Complete |
| 11 | [Jordan Peterson — Maps of Meaning & the Psychology of Belief](Peterson/) | 17 | Complete |
| 12 | [Arthur Schopenhauer — The World as Will & Representation](Schopenhauer/) | 17 | Complete |

### Philosophy & Phenomenology

| # | Topic | Slides | Status |
|---|-------|--------|--------|
| 13 | [Martin Heidegger — Being, Time & the Question of Existence](Heidegger/) | 17 | Complete |
| 14 | [Edmund Husserl — Phenomenology & the Return to Things Themselves](Husserl/) | 17 | Complete |
| 15 | [Alfred North Whitehead — Process, Reality & the Philosophy of Organism](Whitehead/) | 17 | Complete |
| 16 | [William James — Pragmatism, Consciousness & the Varieties of Experience](James/) | 17 | Complete |
| 17 | [Roger Scruton — Beauty, Belonging & the Sacred](Scruton/) | 17 | Complete |
| 18 | [Iain McGilchrist — The Divided Brain & the Making of the Western World](McGilchrist/) | 17 | Complete |

## Historical Influences

The thinkers in this collection form a deeply interconnected web of intellectual inheritance. The landing page includes an interactive SVG influence map tracing these connections.

### The Depth Psychology Lineage
**Schopenhauer → Nietzsche → Freud → Jung → Neumann → Campbell → Peterson**

Schopenhauer's discovery of the blind, irrational Will beneath the surface of rational representation is the headwater of the entire depth psychology tradition. His insight that unconscious striving, not conscious reason, is the primary force in human life directly shaped Nietzsche (who transformed Schopenhauer's pessimism into life-affirmation), Freud (who acknowledged that Schopenhauer had anticipated repression and the unconscious through philosophical intuition), and Jung (whose collective unconscious parallels Schopenhauer's transpersonal Will). The tradition then flowed through Neumann, Campbell, and into Peterson's neo-Jungian synthesis.

### The Phenomenological Lineage
**Husserl &rarr; Heidegger &rarr; McGilchrist & Scruton**

Husserl's phenomenological method was radicalised by Heidegger into an analysis of Dasein and the question of technology. McGilchrist draws on Heidegger's tool-analysis to articulate hemisphere differences. Scruton inherits Husserl's intentionality and Heidegger's dwelling to ground his philosophy of beauty and the sacred.

### The Process & Experience Lineage
**William James &rarr; Whitehead &rarr; McGilchrist**

James's radical empiricism inspired Whitehead's process philosophy. Whitehead's "fallacy of misplaced concreteness" is central to McGilchrist's thesis about left-hemisphere dominance. James also influenced Jung, Husserl, and Frankl.

### The Convergence
**McGilchrist & Scruton**

Both argue that Western modernity has become pathologically one-sided — dominated by abstraction and instrumentalism at the expense of embodied presence, beauty, and the sacred. McGilchrist frames this through neuroscience; Scruton through aesthetics. Both draw on Heidegger, Whitehead, and the depth psychological tradition.

## Architecture

Each presentation is a single-file HTML deployment using [Reveal.js](https://revealjs.com/) loaded from CDN. No build step, no bundler, no local dependencies.

```
Psychology_Philosophy/
├── index.html              ← Landing page with influence map
├── README.md
├── Jung/index.html
├── Freud/index.html
├── Rogers/index.html
├── Adler/index.html
├── Frankl/index.html
├── Piaget/index.html
├── Neumann/index.html
├── Campbell/index.html
├── Nietzsche/index.html
├── Dostoevsky/index.html
├── Peterson/index.html
├── Schopenhauer/index.html
├── Heidegger/index.html
├── Husserl/index.html
├── Whitehead/index.html
├── James/index.html
├── Scruton/index.html
└── McGilchrist/index.html
```

## Design

Dark theme with consistent visual language across all presentations:

- **Fonts:** Playfair Display (headings) · DM Sans (body) · JetBrains Mono (code/labels)
- **Background:** `#0a0a0f`
- **Accents:** Amber `#d4a053` · Green `#4ecca3` · Purple `#9b72cf` · Rose `#cf7272` · Blue `#5b8cd4`
- **Diagrams:** Inline SVG with layered models, concept maps, and process flows
- **Slides:** 17 per presentation — title, biography, timeline, core concepts with diagrams, legacy, readings, closing quote
