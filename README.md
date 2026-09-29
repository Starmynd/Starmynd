### Hi, Its EA 👋

SysAdmin / DevOps engineer. Linux servers, automation, and the fine art of not touching prod on Friday.

- 🖥️ **Systems** — Linux (Debian / Ubuntu), LAMP stacks, Docker
- 🌐 **Networking** — netplan, VPN, DNS, TLS debugging
- ⚙️ **Automation** — bash, Python, cron pipelines
- 🎬 **Media** — Plex automation, music library tooling

I build small, sharp, single-purpose tools: one file, standard library
only, self-tested, no frameworks. Everything below runs in production
somewhere.

---

## Featured projects

| | Project | What it does |
|---|---|---|
| 📚 | [sonic-librarian](https://github.com/Starmynd/sonic-librarian) | Organizes music folders by embedded tags into `Artist / Year - Album`; dry-run first, never deletes or overwrites |
| 💾 | [memqueue](https://github.com/Starmynd/memqueue) | Persistent disk-backed job queue in pure Python: visibility timeouts, requeue, crash-safe replay |
| 🪝 | [hook-receiver](https://github.com/Starmynd/hook-receiver) | Minimal webhook receiver with HMAC-SHA256 verification and JSONL logging |
| 📊 | [csv-summary](https://github.com/Starmynd/csv-summary) | Profiles CSV files from the terminal: column types, stats, fill rates, duplicates |
| 📈 | [termplot](https://github.com/Starmynd/termplot) | ASCII charts in the terminal: bars, histograms, sparklines, line plots |
| 🌍 | [bufferbloat-probe](https://github.com/Starmynd/bufferbloat-probe) | Bufferbloat test in bash: latency idle vs under load, graded A..F |
| 🧰 | [runfile](https://github.com/Starmynd/runfile) | Tiny task runner with dependencies — make-lite in one Python file |
| 🎶 | [fft-peak](https://github.com/Starmynd/fft-peak) | Dominant period of a signal via radix-2 FFT with Hann windowing |

---

## All projects

### Monitoring & ops

| Project | What it does |
|---|---|
| [oom-watch](https://github.com/Starmynd/oom-watch) | Watch Linux OOM killer events and summarize memory pressure |
| [bufferbloat-probe](https://github.com/Starmynd/bufferbloat-probe) | Ping idle vs under load, latency grade A..F, fq_codel advice |
| [cron-next](https://github.com/Starmynd/cron-next) | Parse cron expressions, show the next scheduled run times |
| [dotenv-lint](https://github.com/Starmynd/dotenv-lint) | Lint .env files: duplicates, syntax, missing keys, weak secrets |
| [tg-notify](https://github.com/Starmynd/tg-notify) | Telegram notifications from scripts and cron via curl |

### Networking & provisioning

| Project | What it does |
|---|---|
| [ssh-triangle](https://github.com/Starmynd/ssh-triangle) | SSH jump host helper: latency direct vs via jump, `ssh -J` config generator |
| [lan-sync](https://github.com/Starmynd/lan-sync) | LAN folder sync over rsync/SSH with neighbor auto-discovery |
| [ubuntu_change_ip_script](https://github.com/Starmynd/ubuntu_change_ip_script) | Netplan static-IP switcher with automatic config backup |
| [fast_lamp](https://github.com/Starmynd/fast_lamp) | One-shot LAMP installer (Apache + MySQL + PHP) for Debian/Ubuntu |
| [Lamp4ubuntu](https://github.com/Starmynd/Lamp4ubuntu) | LAMP installer for Ubuntu with PHP 8.3 via ondrej PPA |
| [docker](https://github.com/Starmynd/docker) | Dockerfile experiments — LAMP and utility images |

### Data & backend

| Project | What it does |
|---|---|
| [csv-summary](https://github.com/Starmynd/csv-summary) | Terminal CSV profiler: types, stats, top values, duplicates |
| [dirhash](https://github.com/Starmynd/dirhash) | SHA-256 checksum manifests for directory trees, with verify mode |
| [schema-drift](https://github.com/Starmynd/schema-drift) | Detect schema drift across JSON / JSONL datasets |
| [memqueue](https://github.com/Starmynd/memqueue) | Persistent disk-backed job queue in pure Python |
| [pg-partition-gen](https://github.com/Starmynd/pg-partition-gen) | Generate PostgreSQL range partition DDL for date-keyed tables |
| [fetch-retry](https://github.com/Starmynd/fetch-retry) | Stdlib HTTP client with retries, backoff and Retry-After |
| [hook-receiver](https://github.com/Starmynd/hook-receiver) | Webhook receiver with HMAC signature verification |
| [phone-e164](https://github.com/Starmynd/phone-e164) | Normalize phone numbers to E.164 (US/CA/RU/KZ rules) |

### Algorithms & math

| Project | What it does |
|---|---|
| [termplot](https://github.com/Starmynd/termplot) | ASCII charts: bar charts, histograms, sparklines, line plots |
| [strsim](https://github.com/Starmynd/strsim) | String similarity: Levenshtein, Jaro-Winkler, Dice, LCS |
| [fft-peak](https://github.com/Starmynd/fft-peak) | Dominant period detection via radix-2 FFT |
| [laplace-solver](https://github.com/Starmynd/laplace-solver) | 2D Laplace equation: Jacobi, Gauss-Seidel, SOR + ASCII rendering |
| [bitmask-utils](https://github.com/Starmynd/bitmask-utils) | Bit-twiddling: popcount, submasks, Gosper k-subsets, flag codec |
| [abcalc](https://github.com/Starmynd/abcalc) | A/B test statistics: sample size, power, significance |
| [mini-lexer](https://github.com/Starmynd/mini-lexer) | Arithmetic lexer: hand-written scanner vs regex, with benchmark |
| [cache-patterns](https://github.com/Starmynd/cache-patterns) | Cache-Aside, Read-Through, Write-Through, Write-Behind in one file |

### Developer tooling

| Project | What it does |
|---|---|
| [runfile](https://github.com/Starmynd/runfile) | Task runner with dependencies and shell lines (make-lite) |
| [license-scan](https://github.com/Starmynd/license-scan) | Identify project licenses: fingerprints + SPDX tags |

### Media

| Project | What it does |
|---|---|
| [sonic-librarian](https://github.com/Starmynd/sonic-librarian) | Music folders organized by tags into `Artist / Year - Album` |
| [mmdc](https://github.com/Starmynd/mmdc) | MP3 metadata cleaner: strips feat./remix junk and cover art |
| [Plex](https://github.com/Starmynd/Plex) | Scripts for my Plex media server |
| [dynamic_cannon](https://github.com/Starmynd/dynamic_cannon) | Single-file HTML5 canvas game with sound |

---

![GitHub stats](https://github-readme-stats.vercel.app/api?username=Starmynd&show_icons=true&hide_border=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Starmynd&layout=compact&hide_border=true)
