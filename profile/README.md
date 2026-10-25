# Tangware

Truly personal devices, mixed in everyday life.

**The only end-to-end AI studio for hardware development.**

Consumer electronics, from idea to shipped: design, electronics, firmware, marketing and manufacturing, all as code.

*The source code of reality.*

### Start here

- [**library**](https://github.com/Tangware/library): the open CAD library behind Tangware Studio. Model consumer electronics as code with build123d.
- [**claude-plugin**](https://github.com/Tangware/claude-plugin): the Claude Code plugin for Tangware Studio.

Needs git and [uv](https://docs.astral.sh/uv/).

```sh
git clone https://github.com/Tangware/library
cd library/model
uv sync
uv run cad new ../../my-product --name "My product"
uv run cad export ../../my-product --out ../../my-product/exports
```

[tangware.com](https://tangware.com) · [Tangware Studio](https://tangware.com/studio)
