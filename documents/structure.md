# ARIA — Project Structure

Status legend: ✅ Done · 🔲 Not started

Note: checkmarks below are reset to 🔲 across the board — the previous code files were lost, and this tree now also reflects the merged repo structure (`aria/engine` + `aria/bot` instead of two separate repos).

---

## aria (single repo)

```
aria/
├── 🔲 index.js
├── 🔲 .env
├── 🔲 package.json
│
├── engine/
│   ├── core/
│   │   ├── 🔲 clock.js
│   │   ├── 🔲 mood.js
│   │   ├── 🔲 residue.js
│   │   ├── 🔲 cycle.js
│   │   ├── 🔲 fatigue.js
│   │   ├── 🔲 lifecycle.js
│   │   ├── 🔲 contagion.js
│   │   ├── 🔲 attention.js
│   │   ├── 🔲 atmosphere.js
│   │   ├── 🔲 typing.js
│   │   └── 🔲 personality.js
│   │
│   ├── jobs/
│   │   ├── 🔲 cycle_update.js
│   │   ├── 🔲 schedule_gen.js
│   │   ├── 🔲 decay.js
│   │   ├── 🔲 knowledge_decay.js
│   │   ├── 🔲 memory_prune.js
│   │   ├── 🔲 reflect.js
│   │   ├── 🔲 mood_baseline.js
│   │   └── 🔲 reach_out.js
│   │
│   ├── personas/
│   │   ├── 🔲 chaotic_loveable.js
│   │   ├── 🔲 sarcastic_witty.js
│   │   ├── 🔲 sweet_moody.js
│   │   └── 🔲 chill_observant.js
│   │
│   └── utils/
│       ├── 🔲 descriptors.js
│       ├── 🔲 sentiment.js
│       ├── 🔲 vocabulary_parser.js
│       ├── 🔲 moment_detector.js
│       └── 🔲 log_dispatcher.js
│
└── bot/
    ├── 🔲 index.js
    ├── 🔲 configdata.json
    │
    ├── db/
    │   ├── 🔲 core.js
    │   ├── 🔲 users.js
    │   ├── 🔲 knowledge.js
    │   └── 🔲 schema.js
    │
    ├── engine_bridge/
    │   └── 🔲 client.js
    │
    ├── ai/
    │   └── 🔲 provider.js
    │
    ├── jobs/
    │   └── 🔲 scheduler.js
    │
    ├── handlers/
    │   ├── 🔲 message.js
    │   ├── 🔲 outbound.js
    │   ├── 🔲 reaction.js
    │   ├── 🔲 ping.js
    │   ├── 🔲 dm.js
    │   └── 🔲 vouch.js
    │
    ├── commands/
    │   └── 🔲 (slash commands, added later)
    │
    ├── session/
    │   └── 🔲 context.js
    │
    └── utils/
        ├── 🔲 log_dispatcher.js
        ├── 🔲 formatter.js
        ├── 🔲 typing.js
        ├── 🔲 cooldown.js
        ├── 🔲 validator.js
        ├── 🔲 classifier.js
        ├── 🔲 verify.js
        └── 🔲 queue.js
```

---

## iris (separate repo)

```
iris/
├── 🔲 index.js
├── 🔲 .env
├── 🔲 package.json
│
├── config/
│   └── 🔲 routes.json
│
├── handlers/
│   ├── 🔲 log.js
│   └── 🔲 consent.js
│
└── utils/
    └── 🔲 formatter.js
```

---

## Documents

```
docs/
├── ✅ project.md
├── ✅ strategy.md
├── ✅ data-policy.md
└── ✅ structure.md
```
