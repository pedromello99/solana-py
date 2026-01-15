# solana-py - Análise Detalhada

## 📋 Informações Gerais
| Campo | Valor |
|-------|-------|
| **Repositório** | solana-py |
| **Tipo** | CLI Tool |
| **Visibilidade** | Privado 🔒 |

---

## 🎯 Descrição do Projeto

<img src="https://raw.githubusercontent.com/michaelhly/solana-py/master/docs/img/solana-py-logo.jpeg" width="25%" height="25%">

---

## 🛠️ Stack Tecnológica

### Linguagens Detectadas
- **Python**: 68.6% (70 arquivos)
- **Markdown**: 25.5% (26 arquivos)
- **YAML**: 2.9% (3 arquivos)
- **JSON**: 1.0% (1 arquivos)
- **Shell**: 1.0% (1 arquivos)
- **CSS**: 1.0% (1 arquivos)


### Frameworks e Bibliotecas
- Nenhum framework específico detectado



---

## 📁 Estrutura do Projeto

```
📄 .bumpversion.cfg
📄 .codecov.yml
📄 .env
📄 .flake8
📄 .pydocstyle
📄 .pylintrc
📁 .vscode/
📄 ANALYSIS.md
📁 bin/
📄 CHANGELOG.md
📁 docs/
📄 LICENSE
📄 Makefile
📄 mkdocs.yml
📄 poetry.lock
📄 poetry.toml
📄 pyproject.toml
📄 pytest.ini
📄 README.md
📁 src/
```

---

## 📖 README Original

<div align="center">
    <img src="https://raw.githubusercontent.com/michaelhly/solana-py/master/docs/img/solana-py-logo.jpeg" width="25%" height="25%">
</div>

---

[![Actions
Status](https://github.com/michaelhly/solanapy/workflows/CI/badge.svg)](https://github.com/michaelhly/solanapy/actions?query=workflow%3ACI)
[![PyPI version](https://badge.fury.io/py/solana.svg)](https://badge.fury.io/py/solana)
[![Codecov](https://codecov.io/gh/michaelhly/solana-py/branch/master/graph/badge.svg)](https://codecov.io/gh/michaelhly/solana-py/branch/master)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/michaelhly/solana-py/blob/master/LICENSE)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

# Solana.py

**🐍 The Solana Python SDK 🐍**

Solana.py is the base Python library for interacting with Solana.
You can use it to build transactions and interact
with the
[Solana JSON RPC API](https://docs.solana.com/apps/jsonrpc-api),
much like you would do with
[solana-web3.js](https://github.com/solana-labs/solana-web3.js/)

It also covers the
[SPL Token Program](https://spl.solana.com/token).

[Latest Documentation](https://michaelhly.github.io/solana-py/).

**⚓︎ See also: [AnchorPy](https://github.com/kevinheavey/anchorpy),**
**a Python client for**
**[Anchor](https://project-serum.github.io/anchor/getting-started/introduction.html)-based**
**programs on Solana. ⚓︎**

## ⚡ Quickstart

### Installation

```sh
pip install solana
```

### General Usage

Note: check out the
[Solana Cookbook](https://solanacookbook.com/)
for more detailed examples!

```py
import solana
```

### API Client

```py
from solana.rpc.api import Client

http_client = Client("https://api.devnet.solana.com")
```

### Async API Client

```py
import asyncio
from solana.rpc.async_api import AsyncClient

async def main():
    async with AsyncClient("https://api.devnet.solana.com") as client:
        res = await clien

---

## 🔗 Links

- **Repositório**: https://github.com/pedromello99/solana-py
- **Clone**: `git clone https://github.com/pedromello99/solana-py.git`

---

*Análise gerada automaticamente em 14/01/2026*
