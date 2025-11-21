# 🔐 Comparador de Desempenho AES vs DES

Este projeto implementa um sistema comparativo de desempenho entre os algoritmos de criptografia **AES (128 e 256 bits)** e **DES (64 bits)** em modo **CBC**, utilizando **padding PKCS7** e **IV aleatório**.

## 📋 Funcionalidades
- Cifrar e decifrar arquivos simulados de diferentes tamanhos:
  - 1 KB
  - 1 MB
  - 10 MB
- Medir tempo de processamento para cada algoritmo.
- Calcular throughput (MB/s) para operações de cifragem e decifragem.
- Gerar relatório comparativo em formato de tabela.
- Plotar gráficos de desempenho usando **matplotlib**.

## ⚙️ Requisitos Técnicos
- Linguagem: **Python 3.9+**
- Bibliotecas:
  - `pycryptodome`
  - `matplotlib`

Instalação:
```bash
pip install pycryptodome matplotlib
