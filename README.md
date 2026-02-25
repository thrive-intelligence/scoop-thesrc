# The Source — Scoop Bucket (Windows)

```powershell
scoop bucket add thesrc https://github.com/thrive-intelligence/scoop-thesrc
scoop install thesrc
thesrc init
```

That's it. Scoop handles Python and Git automatically.

---

### Commands

```
thesrc init              # scaffold project (Supabase + Neo4j Aura)
thesrc init --local      # scaffold with local Docker databases
thesrc doctor            # health check
thesrc install-global    # load into all Claude Code sessions
thesrc export-project    # export for Claude.ai web Projects
```

---

[thesrc.ai](https://thesrc.ai) — [Source repo](https://github.com/thrive-intelligence/the-src)
