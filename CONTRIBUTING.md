# Contributing to iterx

[简体中文](#简体中文)

Thanks for helping make hardware creation easier. This guide is the default for every repository in the iterxlabs organization; a repository's own CONTRIBUTING file takes precedence.

## Open an issue first

- **Bugs**: include the command, the full `--json` output (with `error.code` and `error.fix`), your OS and Node.js version.
- **New boards, templates, or part data fixes**: our favorite contributions. Open an issue with the model and the source datasheet first.
- **Larger changes**: agree on the approach in an issue before writing code.

## Pull requests

- One change per pull request, with tests; `npm test` must pass.
- Commit messages say what problem is solved and why.
- Sign off every commit (DCO) to certify you wrote the code and agree to release it under the repository license:

  ```bash
  git commit -s -m "Fix dropped UART bytes in ESP32-C3 simulation"
  ```

## License and trademarks

Contributions are released under the license of the repository they land in. "iterx", "词元开物" and the Evan character are trademarks of IterXAI; modified distributions must use their own name.

---

## 简体中文

感谢你愿意一起让硬件创造更简单。本文件是 iterxlabs 组织下所有仓库的默认指南；仓库自带 CONTRIBUTING 时以仓库为准。

- **先开 issue 再写代码**：Bug 请附上命令、`--json` 完整输出（含 `error.code` 与 `error.fix`）、操作系统与 Node 版本；新板卡、新模板、元件资料纠错最受欢迎，先说明型号与来源资料；较大改动先在 issue 里对齐方案。
- **提交 PR**：一个 PR 只做一件事并附带测试，`npm test` 全部通过；提交信息说清楚解决了什么问题、为什么这样改；每个提交用 `git commit -s` 加 DCO 签名。
- **协议与品牌**：代码贡献按所在仓库的开源协议发布。iterx、词元开物与 Evan 形象是 IterXAI 的品牌，修改后的分发版本请使用自己的名称。
