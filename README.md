# dsh-tool-planner

A DSH skill that helps non-programmers plan and build a tool by interview.

It walks the user through how they do the task by hand today, one plain-language step at a time, turning each step into a flowchart node. Then a short round of automation questions, a plain-language plan, and explicit approval before building.

## Install

**Desktop app:** open **Plugins → Add Plugin**, paste the source below, click install, then restart the app.

```
github:WasifAlamDip/dsh-fde-tool-planner
```

**Terminal:**

```sh
dsh plugin --profile web add github:WasifAlamDip/dsh-fde-tool-planner
```

If `dsh` is not on your PATH, put `npx @deepseek-ai/dsh` in place of `dsh`. Restart dsh after installing.

To pin a release, add a tag: `github:WasifAlamDip/dsh-fde-tool-planner#v0.1.0`.

## Usage

Describe what you want in 3–4 lines. Answer in plain language — no technical knowledge needed.

## Uninstall

```sh
dsh plugin --profile web remove dsh-tool-planner
```

## Credits

Built by [Wasif Alam Dip](https://github.com/WasifAlamDip).

## License

MIT
