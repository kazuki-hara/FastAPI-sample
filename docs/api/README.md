# API

### 要件

### 環境

- Python 3.12
- ライブラリ管理方法：uv
- フレームワーク：FastAPI
- ORM：SQLModel
- テスト：pytest
- Lint：Ruff
- フォーマッタ：Ruff

### ディレクトリ構造

- `api/`
  - `Dockerfile`: APIサーバのDockerイメージを構築するための設定ファイル。
  - `pyproject.toml`: Pythonプロジェクトの設定ファイル。
  - `Taskfile.yml`: タスク定義ファイル。
  - `api/`: FastAPIのルートモジュール。
  - `app/`: アプリケーションロジックを含むディレクトリ。
  - `tests/`: テストコードを含むディレクトリ。
  - `.venv/`: 仮想環境用ディレクトリ。
  - `.ruff_cache/`: Lintツール`Ruff`のキャッシュ。