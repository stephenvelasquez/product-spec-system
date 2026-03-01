# Product Spec System

The complete product development system. From opportunity to post-launch review — every artifact a product team needs to ship well.

## Why this exists

Product development isn't one document. It's a chain of decisions, each building on the last. Most teams have a PRD template and nothing else. This system connects the full lifecycle:

```
Opportunity → RFC → Spec → Launch Review → Post-Launch
```

Each stage has a template, clear entry/exit criteria, and links to the previous stage.

## The lifecycle

| Stage | Document | Purpose | When |
|-------|----------|---------|------|
| 1. Discovery | [Opportunity Assessment](templates/opportunity-assessment.md) | Should we invest in this? | Before committing resources |
| 2. Design | [RFC (Request for Comments)](templates/rfc.md) | How should we build it? | Before engineering starts |
| 3. Build | [Product Spec](templates/product-spec.md) | What exactly are we building? | During development |
| 4. Ship | [Launch Review](templates/launch-review.md) | Are we ready to ship? | Before launch |
| 5. Learn | [Post-Launch Review](templates/post-launch-review.md) | Did it work? What's next? | 2-4 weeks after launch |

## Quick start

1. Start with `templates/opportunity-assessment.md` when evaluating a new idea
2. If the opportunity is worth pursuing, write an `templates/rfc.md`
3. Once the RFC is approved, detail the implementation in `templates/product-spec.md`
4. Before launch, run through `templates/launch-review.md`
5. After launch, schedule `templates/post-launch-review.md`

## Project structure

```
product-spec-system/
├── README.md
├── templates/
│   ├── opportunity-assessment.md
│   ├── rfc.md
│   ├── product-spec.md
│   ├── launch-review.md
│   └── post-launch-review.md
└── examples/
    └── search-redesign/        # Worked example
```

## Principles

1. **Every document answers one question.** If it answers two, split it.
2. **Templates are starting points, not bureaucracy.** Delete sections that don't apply.
3. **Writing is thinking.** The act of writing the spec IS the product work.
4. **Decisions decay.** Link to context so future you understands why.
5. **Ship the system, not the doc.** A perfect spec that doesn't ship is worthless.

## License

MIT
