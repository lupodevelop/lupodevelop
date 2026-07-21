# Code, noise and strange ideas

I make small Gleam libraries, but the real work happens in a messy workshop of
experiments. Based in Italy, I travel when I can and learn places by eating food.
I scatter prototypes, scribbles, and tiny tools across projects. I follow stubborn
curiosity, loud Italian punk, and strong coffee.

Somewhere in that workshop lives [Skeg](https://github.com/skegdb/skeg): a
multi-tenant vector database in Rust, obsessed with using very little RAM. It is
the closest thing here to a serious product. Please do not tell the other projects.

This is not a product page. Expect rough edges, quick ideas, and things that work
well enough to be interesting.

## ✨ Things worth opening first

- 🚀 [skeg](https://github.com/skegdb/skeg) — a RAM-efficient, multi-tenant vector
  database for AI workloads. **Rust**.
- 🐶 [woof](https://github.com/lupodevelop/woof) — straightforward logging, without
  turning every log line into a personal journey. **Gleam**.
- 🧭 [hexplorer](https://github.com/lupodevelop/hexplorer) — browse the Hex package
  registry from a terminal, because apparently that needed to exist. **Rust**.
- 📬 [distribute](https://github.com/lupodevelop/distribute) — typed distributed
  messaging for the BEAM. **Gleam**.
- 🧱 [amber](https://github.com/lupodevelop/amber) — a small, fast microVM for
  arm64. A normal hobby, obviously. **Rust**.
- 🧠 [echo-1.58](https://github.com/lupodevelop/echo-1.58) — native ternary QAT for
  language models. **Python**.

## 📚 The small library shelf

### Gleam 💜

Most of these are **Gleam** libraries. They are small on purpose: useful pieces,
not a framework wearing a trench coat.

**Everyday bits**

- 🔗 [woof](https://github.com/lupodevelop/woof) — straightforward logging
- 🔗 [str](https://github.com/lupodevelop/str) — Unicode-aware string operations
- 🔗 [cmp](https://github.com/lupodevelop/cmp) — explicit equality and ordering
- 🔗 [humanize](https://github.com/lupodevelop/humanize) — friendlier numbers, bytes,
  durations, and lists
- 🔗 [fio](https://github.com/lupodevelop/fio) — safe, ergonomic file operations
- 🔗 [envie](https://github.com/lupodevelop/envie) — type-safe environment variables
- 🔗 [cowl](https://github.com/lupodevelop/cowl) — secrets that do not escape into logs

**Backend, protocols, and data**

- 🔗 [distribute](https://github.com/lupodevelop/distribute) — typed distributed
  messaging on the BEAM
- 🔗 [radiant](https://github.com/lupodevelop/radiant) — focused, type-safe HTTP routing
- 🔗 [sparkling](https://github.com/lupodevelop/sparkling) — composable ClickHouse client
- 🔗 [thrifty](https://github.com/lupodevelop/thrifty) — Apache Thrift Compact Protocol

**Testing with real containers, because mocks eventually lie**

- 🔗 [testcontainer](https://github.com/lupodevelop/testcontainer) — run real Docker
  containers from tests and dev tooling
- 🔗 [testcontainer_formulas](https://github.com/lupodevelop/testcontainer_formulas) —
  ready-to-use typed container formulas
- 🔗 [testcontainer_dockerfile](https://github.com/lupodevelop/testcontainer_dockerfile) —
  build Docker images as part of a test setup
- 🔗 [testcontainer_compose](https://github.com/lupodevelop/testcontainer_compose) —
  reuse an existing Compose file in tests

**Terminal things**

- 🔗 [etui](https://github.com/lupodevelop/etui) — pure, composable TUI widgets with
  correct Unicode support

### Rust 🦀

These are **Rust** projects, where I occasionally make computers do suspiciously
low-level things.

- 🔗 [amber](https://github.com/lupodevelop/amber) — small, fast arm64 microVM
- 🔗 [hexplorer](https://github.com/lupodevelop/hexplorer) — terminal browser for Hex
- 🔗 [lockedenv](https://github.com/lupodevelop/lockedenv) — type-safe, freeze-on-load
  environment management

### JavaScript 🟡 and TypeScript 🔵

- 🔗 [remark-blackout](https://github.com/lupodevelop/remark-blackout) — **JavaScript**:
  turns directives into blacked-out elements
- 🔗 [quick-logtime](https://github.com/lupodevelop/quick-logtime) — **TypeScript**:
  timestamps `console.*` output
- 🔗 [testcontainer_formulas_builder](https://github.com/lupodevelop/testcontainer_formulas_builder) —
  **TypeScript**: a web-based constructor for testcontainer formulas

Each repository has its own README and examples; this profile points the torch.

Also: my dog Echo (yes, like the bash command) moonlights as a code reviewer.
Subtle approval example:

```bash
# Echo's review (canine logic)
# TAIL_WAG=1 if tail wagged, WOF=1 if 'wof' observed
TAIL_WAG=1
WOF=1

if [ "$TAIL_WAG" -eq 1 ] && [ "$WOF" -eq 1 ]; then
	echo "wof woof Approved ✅"
else
	echo "nope"
fi

# -> wof woof Approved ✅   (if both true)
```

**Contact**

- GitHub: `https://github.com/lupodevelop`
- Email: (not provided) 🐶📫

**Elsewhere**

- 🌙 [altumdream.com](https://www.altumdream.com) — apps and other things I publish
- 🍄 [amanitaproject.com](https://www.amanitaproject.com) — serious technical articles
  about difficult things

lupodevelop 🖐️
