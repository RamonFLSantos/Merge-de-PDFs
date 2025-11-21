# Merge de PDFs

Este projeto é um utilitário simples desenvolvido em Python para mesclar diversos arquivos PDF em um único documento final.

A ferramenta percorre automaticamente todos os PDFs presentes na pasta `arquivos/`, ordena-os por nome e os combina em um arquivo chamado `PDF Mesclado.pdf`.

---

## Como funciona

O script utiliza a biblioteca PyPDF2 para realizar a mesclagem dos arquivos PDF.  
Ele segue os seguintes passos:

1. Lê todos os arquivos dentro da pasta `arquivos/`
2. Ordena os nomes dos arquivos
3. Filtra apenas os arquivos com extensão PDF
4. Une todos os PDFs em um único documento final

---

## Tecnologias utilizadas

- Python 3
- PyPDF2
- Manipulação de arquivos com o módulo `os`

---

## Como executar

1. Instale a dependência:
```bash
pip install PyPDF2
```
2. Coloque os PDFs que deseja mesclar dentro da pasta arquivos/.
3. Execute o script:
```bash
python main.py
```
4. O arquivo final será gerado com o nome:
   **PDF Mesclado.pdf**

---

## Objetivo do projeto

Criar uma ferramenta simples e prática para automatizar a mesclagem de arquivos PDF, demonstrando o uso da biblioteca PyPDF2, além de reforçar conceitos de manipulação de arquivos, ordenação e pequenos utilitários em Python.
