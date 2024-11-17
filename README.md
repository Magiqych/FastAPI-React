# FastAPI-React プロジェクト

このプロジェクトは、バックエンドにFastAPI、フロントエンドにReactを組み合わせて、フルスタックのWebアプリケーションを作成します。

## プロジェクト構成

```
/x:/test/FastAPI-React/
├── back/
│   ├── app/
│   │   ├── main.py
│   │   └── ...
│   └── requirements.txt
├── front/
│   ├── src/
│   │   ├── App.js
│   │   ├── index.js
│   │   └── ...
│   ├── package.json
│   └── ...
└── README.md
```

## はじめに

### バックエンドのセットアップ

1. 仮想環境を作成します:
    ```bash
    python -m venv .venv
    ```
    - このコマンドは、現在のディレクトリに `.venv` という名前の仮想環境を作成します。仮想環境は、Pythonプロジェクトの依存関係をシステム全体のPythonインストールとは別に管理するための隔離された環境です。

2. 仮想環境を有効にします:
    - Windowsの場合: `.\.venv\Scripts\activate`
    - UnixまたはMacOSの場合: `source .venv/bin/activate`

3. 必要な依存関係をインストールします:
    ```bash
    pip install -r requirements.txt
    ```

4. バックエンドディレクトリに移動します:
    ```bash
    cd back
    ```

5. FastAPIアプリケーションを実行します:
    ```bash
    uvicorn app.main:app --reload
    ```

6. ブラウザを開き、`http://127.0.0.1:8000` にアクセスしてアプリケーションが動作していることを確認します。

### フロントエンドのセットアップ

1. フロントエンドディレクトリに移動します:
    ```bash
    cd front
    ```

2. 必要なNode.jsパッケージをインストールします:
    ```bash
    npm install
    ```

3. React開発サーバーを起動します:
    ```bash
    npm start
    ```

## 使用方法

- FastAPIバックエンドにアクセス: `http://localhost:8000`
- Reactフロントエンドにアクセス: `http://localhost:3000`

