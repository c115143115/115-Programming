# AGENTS.md

Course repo for 115-1 computer programming. Mostly Python coursework + notebooks. No build, test, lint, or CI config.

## Structure

- `README.md`: course codebase marker, no setup docs.
- `迴圈/loopcode.ipynb`: currently 0-byte empty file, untracked (`git status` shows `迴圈/`). New topic folders follow this pattern.
- `.gitignore`: default Python template. `.venv/`, `__pycache__/`, `.ipynb_checkpoints` ignored.
- Remote: `https://github.com/c115143115/115-Programming.git`, branch `main`.

## Commands

- 語言為 Python；用 conda 管理套件，環境為 `iem_python`。
- 執行前先 `conda activate iem_python`；驗證用 `python -c "..."` 或 `jupyter notebook`。
- 無 task runner、test framework、lint、CI 設定。

## Rules

- 所有的回應都使用繁體中文。

## Gotchas

- Paths contain CJK characters (e.g. `迴圈/`). Quote paths in shell and prefer file tools over raw `shell` for reads/edits.
- Shell is Windows PowerShell: no `ls -la` / `cat`; use `Get-ChildItem`, `Get-Content`, or file tools.
- Empty `.ipynb` files are placeholders, not valid JSON — don't try to parse them until they have content.
