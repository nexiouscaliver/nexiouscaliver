# Shahil Kadia

AI System Architect, consulting since August 2026, before that an AI developer intern from January 2025. Two shapes of work recur in everything I ship: software that runs entirely on your machine, and multi-agent systems that plan work, verify it against reality, and write down what they learned.

B.Tech in computer science, Amity Mumbai, 2026, CGPA 9.20.

```text
shahil@shahilkadia.me:~$ repos --public
46 public, 33 showcased
shahil@shahilkadia.me:~$ upstream --status
5 merged, 7 open
shahil@shahilkadia.me:~$ flagship --list
voxbar  mission-control  OmniForge
shahil@shahilkadia.me:~$ voxbar --releases
27 public, latest v1.6.9
shahil@shahilkadia.me:~$ █
```

## Flagship work

- [VoxBar](https://github.com/nexiouscaliver/voxbar): privacy-first dictation for macOS. On-device recognition, a local LLM that cleans up the transcript, and a phone companion, built in Rust and Tauri. 27 public releases, latest v1.6.9. Upstream: [Handy](https://github.com/cjpais/Handy).
- [mission-control](https://github.com/nexiouscaliver/mission-control): the master session that runs my multi-agent programs. It plans them, forges red-teamed prompts for the worker sessions, verifies results against reality instead of trusting them, and distills what held up into knowledge.
- [OmniForge](https://github.com/nexiouscaliver/OmniForge): merge requests as an assembly line. Adversarial review agents tear diffs apart in isolated worktrees, fixes land as commits, and the MR arrives with a description written from the actual changes.

## Open source

Five pull requests merged upstream, titles verbatim:

- [pyWhat #266](https://github.com/bee-san/pyWhat/pull/266): fix: update IPv6 regex to support hexadecimal characters
- [mem0 #7300](https://github.com/mem0ai/mem0/pull/7300): fix(examples): migrate OSS Memory search/get_all calls to v3 filters API
- [camel #4117](https://github.com/camel-ai/camel/pull/4117): fix(toolkits): MCPToolkit connects once when max_retries=0
- [zimfarm #1956](https://github.com/openzim/zimfarm/pull/1956): Fix worker dashboard boxes inconsistent sizing
- [dify #37417](https://github.com/langgenius/dify/pull/37417): refactor: accept db.session explicitly in RecommendedAppService

Seven more sit open: a camel follow-up that makes sub-agent tool inheritance explicit, an agentscope fix so orphan tool calls stop bricking sessions, an agno migration of the A2A client to the official SDK, and four others listed on the site.

## Links

- [shahilkadia.me](https://shahilkadia.me): the portfolio, including a phosphor terminal page
- [LinkedIn](https://www.linkedin.com/in/shahil-kadia)
- [GitHub](https://github.com/nexiouscaliver)
- [Contact](<mailto:shahilkadia@gmail.com?subject=[portfolio]%20>): email lands with subject [portfolio]
- [dotfiles](https://github.com/nexiouscaliver/dotfiles): zsh, git, and vim defaults behind one idempotent POSIX sh installer
