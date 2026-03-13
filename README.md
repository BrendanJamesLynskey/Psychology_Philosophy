# Psychology

Interactive presentations exploring foundational thinkers and concepts in psychology.

**Live site:** [brendanjameslynskey.github.io/Psychology](https://brendanjameslynskey.github.io/Psychology)

## Presentations

| # | Topic | Slides | Status |
|---|-------|--------|--------|
| 01 | [Carl Jung — The Architecture of the Psyche](https://brendanjameslynskey.github.io/Psychology/Jung/) | 17 | ✅ Complete |
| 02 | [Sigmund Freud — The Foundations of Psychoanalysis](https://brendanjameslynskey.github.io/Psychology/Freud/) | 17 | ✅ Complete |
| 03 | [Carl Rogers — The Person-Centred Approach](https://brendanjameslynskey.github.io/Psychology/Rogers/) | 17 | ✅ Complete |
| 04 | [Alfred Adler — Individual Psychology & the Striving for Significance](https://brendanjameslynskey.github.io/Psychology/Adler/) | 17 | ✅ Complete |
| 05 | [Viktor Frankl — The Search for Meaning](https://brendanjameslynskey.github.io/Psychology/Frankl/) | 17 | ✅ Complete |
| 06 | [Jean Piaget — Genetic Epistemology & Cognitive Development](https://brendanjameslynskey.github.io/Psychology/Piaget/) | 17 | ✅ Complete |
| 07 | [Erich Neumann — The Origins & History of Consciousness](https://brendanjameslynskey.github.io/Psychology/Neumann/) | 17 | ✅ Complete |
| 08 | [Joseph Campbell — Myth, Meaning & the Hero's Journey](https://brendanjameslynskey.github.io/Psychology/Campbell/) | 17 | ✅ Complete |
| 09 | [Friedrich Nietzsche — The Psychology of the Depths](https://brendanjameslynskey.github.io/Psychology/Nietzsche/) | 17 | ✅ Complete |
| 10 | [Fyodor Dostoevsky — The Novelist as Psychologist](https://brendanjameslynskey.github.io/Psychology/Dostoevsky/) | 17 | ✅ Complete |
| 11 | [Jordan Peterson — Maps of Meaning & the Psychology of Belief](https://brendanjameslynskey.github.io/Psychology/Peterson/) | 17 | ✅ Complete |

## Architecture

Each presentation is a single-file HTML deployment using [Reveal.js](https://revealjs.com/) loaded from CDN. No build step, no bundler, no local dependencies.

```
Psychology/
├── index.html          ← Landing page
├── README.md
├── Jung/
│   └── index.html      ← Reveal.js presentation
├── Freud/
│   └── index.html
├── Rogers/
│   └── index.html
├── Adler/
│   └── index.html
├── Frankl/
│   └── index.html
├── Piaget/
│   └── index.html
├── Neumann/
│   └── index.html
├── Campbell/
│   └── index.html
├── Nietzsche/
│   └── index.html
├── Dostoevsky/
│   └── index.html
└── Peterson/
    └── index.html
```

## Design

Dark theme with consistent visual language across all presentations:

- **Fonts:** Playfair Display (headings) · DM Sans (body) · JetBrains Mono (code/labels)
- **Background:** `#0a0a0f`
- **Accents:** Amber `#d4a053` · Green `#4ecca3` · Purple `#9b72cf` · Rose `#cf7272` · Blue `#5b8cd4`
- **Diagrams:** Inline SVG with layered psyche models, function compasses, and process flows
- **Slides:** 17 per presentation — title, biography, timeline, core concepts with diagrams, legacy, readings, closing quote
