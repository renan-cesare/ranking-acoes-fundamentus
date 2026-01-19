# Ranking de Ações (Fundamentus) — Selenium + Pandas

Script em Python que acessa o **Fundamentus**, coleta a tabela de ações disponíveis, aplica **filtros fundamentalistas** e gera um **ranking simples** (ex.: Top 15) no terminal.

> Projeto de estudo baseado em aprendizado prático (curso), com **adaptações e filtros próprios**.

---

## O que esse projeto faz

1. Abre o site do Fundamentus (resultado de ações)
2. Coleta a tabela HTML via Selenium
3. Converte para DataFrame (pandas)
4. Trata colunas percentuais (ROIC, ROE, margens, crescimento)
5. Filtra por critérios (ex.: P/VP < 1, ROE/ROIC > 0, etc.)
6. Ordena por preferências e imprime um ranking final

---

## Requisitos

- Python 3.10+ (recomendado)
- Google Chrome instalado

---

## Como rodar

### 1) Instalar dependências
```bash
pip install -r requirements.txt
