# playbook

> Small setups that give outsized output.

A living, build-in-public collection of productivity and AI-workflow tricks — real configs I actually run, with honest trade-offs and copy-paste commands. No framework, just static HTML; deployed on Vercel.

## Entries

| Entry | Topic | Status |
|-------|-------|--------|
| [Running DeepSeek inside Claude Code](posts/deepseek-on-claude-code.html) | AI workflow | live |

## Structure

```
index.html                          # landing page — lists entries
posts/
  deepseek-on-claude-code.html      # one self-contained page per entry
```

Each post is a single self-contained HTML file (inline CSS + JS, no build step). Open `index.html` locally to browse, or visit the deployed site.

## Local preview

```bash
open index.html          # macOS
# or serve it:
python3 -m http.server 8000   # then visit localhost:8000
```

## License

[MIT](LICENSE)
