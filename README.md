# Weekly Marketing Report — Claude Skill (reconstruction)

A Claude Skill scaffold for producing a weekly marketing report, rebuilt by
Vy from a public community post by Liên Lê (Cơm AI lo group, 2026-11-07).
The author's original template is NOT public — it is only shared with people
who comment "SKILLS" on the post — so this is a structural reconstruction:
the file layout, the role of each file, and the Query Provenance Trace
fields, with placeholders (`[ĐIỀN ...]`) wherever the original would carry
team-specific formulas or rules. Nothing here is presented as the author's
original content. Full provenance: [README-SOURCE.md](README-SOURCE.md).

## Layout

```
.claude/skills/weekly-marketing-report/
├── SKILL.md                            # the report workflow
├── metrics.md                          # fixed metric definitions
├── data-quirks.md                      # data exceptions to watch for
└── templates/
    └── query-provenance-trace.md       # traceability table for every figure
```

The Query Provenance Trace is the heart of it: every number in the report
must be traceable to the exact query that produced it.
