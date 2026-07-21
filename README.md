# Code, noise, and useful small things

I build [Skeg](https://github.com/skegdb/skeg), a multi-tenant vector database in Rust
for high-density, RAM-efficient AI workloads.

I also make libraries and developer tools, mostly for **Gleam/BEAM** and **Rust**.
Based in Italy. I follow stubborn curiosity, loud Italian punk, and strong coffee.

## Featured work

| Project | Language | What it is |
|---|---|---|
| [Skeg](https://github.com/skegdb/skeg) | Rust | Multi-tenant vector database optimized for RAM efficiency |
| [woof](https://github.com/lupodevelop/woof) | Gleam | Straightforward logging library |
| [hexplorer](https://github.com/lupodevelop/hexplorer) | Rust | Terminal UI for browsing the Hex package registry |
| [distribute](https://github.com/lupodevelop/distribute) | Gleam | Typed distributed messaging for the BEAM |
| [amber](https://github.com/lupodevelop/amber) | Rust | Small, fast microVM for arm64 |
| [echo-1.58](https://github.com/lupodevelop/echo-1.58) | Python | Native ternary QAT for language models |

## Gleam libraries

### Foundation

| Library | What it does |
|---|---|
| [woof](https://github.com/lupodevelop/woof) | Logging |
| [str](https://github.com/lupodevelop/str) | Unicode-aware string operations |
| [cmp](https://github.com/lupodevelop/cmp) | Explicit equality and ordering |
| [humanize](https://github.com/lupodevelop/humanize) | Human-friendly numbers, bytes, durations, and lists |
| [fio](https://github.com/lupodevelop/fio) | Safe, ergonomic file operations |
| [envie](https://github.com/lupodevelop/envie) | Cross-platform, type-safe environment variables |
| [cowl](https://github.com/lupodevelop/cowl) | Opaque secrets that stay out of logs |

### Backend, protocols, and data

| Library | What it does |
|---|---|
| [distribute](https://github.com/lupodevelop/distribute) | Typed distributed messaging on the BEAM |
| [radiant](https://github.com/lupodevelop/radiant) | Focused, type-safe HTTP router |
| [sparkling](https://github.com/lupodevelop/sparkling) | Composable ClickHouse client |
| [thrifty](https://github.com/lupodevelop/thrifty) | Apache Thrift Compact Protocol implementation |

### Testing with real containers

| Library | What it does |
|---|---|
| [testcontainer](https://github.com/lupodevelop/testcontainer) | Run real Docker containers from tests and dev tooling |
| [testcontainer_formulas](https://github.com/lupodevelop/testcontainer_formulas) | Ready-to-use typed container formulas |
| [testcontainer_dockerfile](https://github.com/lupodevelop/testcontainer_dockerfile) | Build Docker images as part of a test setup |
| [testcontainer_compose](https://github.com/lupodevelop/testcontainer_compose) | Reuse an existing Compose file in tests |

### Terminal UI

| Library | What it does |
|---|---|
| [etui](https://github.com/lupodevelop/etui) | Pure, composable TUI widgets with correct Unicode support |

## Rust projects

| Project | What it is |
|---|---|
| [amber](https://github.com/lupodevelop/amber) | Small, fast arm64 microVM |
| [hexplorer](https://github.com/lupodevelop/hexplorer) | Terminal browser for the Hex package registry |
| [lockedenv](https://github.com/lupodevelop/lockedenv) | Type-safe, freeze-on-load environment management |

## JavaScript and TypeScript

| Project | Language | What it is |
|---|---|---|
| [remark-blackout](https://github.com/lupodevelop/remark-blackout) | JavaScript | Remark plugin that turns directives into blacked-out elements |
| [quick-logtime](https://github.com/lupodevelop/quick-logtime) | TypeScript | Adds timestamps to `console.*` output |
| [testcontainer_formulas_builder](https://github.com/lupodevelop/testcontainer_formulas_builder) | TypeScript | Web-based constructor for testcontainer formulas |

---

My dog Echo, named after the shell command, reviews code when not sleeping.

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

# -> wof woof Approved ✅
```
