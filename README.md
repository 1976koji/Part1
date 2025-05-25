

---

# 🐱 Cat Corpus Analysis using Symplectic Prompt (EN/JP)

This repository provides Python scripts for analyzing a Japanese "cat corpus" using embeddings and symplectic prompt techniques with OpenAI's API.

---

## 🌟 English

### 📖 Overview

* **Cat corpus (`cats_corpus_100.py`)**:
  A Japanese corpus containing 100 cat-related sentences.

* **Analysis script (`symplectic_prompt_cat_analysis.py`)**:
  Generates symplectic prompts, evaluates semantic drift, and calculates symplectic information (`I_xi`) using OpenAI models.

### 🛠️ Setup

#### Requirements

Python >= 3.8 recommended.

Install dependencies:

```bash
pip install -r requirements.txt
```

#### `requirements.txt`

```
openai
tqdm
janome
numpy
```

### 🔑 API Key Setup (Important!)

Obtain your own OpenAI API key from [OpenAI](https://platform.openai.com/api-keys) and set it as an environment variable:

* **macOS/Linux:**

```bash
export OPENAI_API_KEY='your-api-key-here'
```

* **Windows (PowerShell):**

```powershell
$env:OPENAI_API_KEY = "your-api-key-here"
```

* **Google Colab/Jupyter:**

```python
import os
os.environ["OPENAI_API_KEY"] = "your-api-key-here"
```

**Never share your API key publicly!**

### 🚀 How to Run

Execute the analysis script:

```bash
python symplectic_prompt_cat_analysis.py
```

### 📊 Output

The script will print semantic drift metrics (`D_drift`) , symplectic variance (`Var(I_xi)`) to your terminal.

---

## 🌟 日本語

### 📖 概要

* **猫コーパス (`cats_corpus_100.py`)**:
  猫に関する100文の日本語コーパスです。

* **分析スクリプト (`symplectic_prompt_cat_analysis.py`)**:
  シンプレクティック・プロンプトを生成し、意味的ドリフトおよびシンプレクティック情報量 (`I_xi`)をOpenAIのモデルで分析します。

### 🛠️ 環境設定

#### 必要条件

Python は3.8以上を推奨。

パッケージのインストール：

```bash
pip install -r requirements.txt
```

#### `requirements.txt`

```
openai
tqdm
janome
numpy
```

### 🔑 APIキー設定（重要！）

[OpenAI APIキーを取得](https://platform.openai.com/api-keys)し、環境変数にセット：

* **macOS/Linuxの場合:**

```bash
export OPENAI_API_KEY='あなたのAPIキー'
```

* **Windowsの場合 (PowerShell):**

```powershell
$env:OPENAI_API_KEY = "あなたのAPIキー"
```

* **Google Colab/Jupyterの場合:**

```python
import os
os.environ["OPENAI_API_KEY"] = "あなたのAPIキー"
```

**APIキーは絶対に公開しないでください。**

### 🚀 実行方法

以下を実行してください：

```bash
python symplectic_prompt_cat_analysis.py
```

### 📊 結果の確認

意味的ドリフト（`D_drift`）、シンプレクティック情報量の分散（`Var(I_xi)`）が出力されます。

---
