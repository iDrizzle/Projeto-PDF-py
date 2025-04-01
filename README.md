# Combinar PDFs com PyPDF2

## Descrição
Este script Python combina vários arquivos PDF presentes na pasta **"arquivos"** em um único documento chamado **"PDF Final.pdf"**. Ele usa a biblioteca **PyPDF2** para realizar a fusão dos PDFs.

## Requisitos
- Python instalado (versão 3.x recomendada)
- Biblioteca **PyPDF2** instalada

### Instalação da Biblioteca
Se ainda não tiver o **PyPDF2**, instale-o com:
```bash
pip install PyPDF2
```

## Como Usar
1. Certifique-se de que todos os arquivos **.pdf** que deseja combinar estão dentro da pasta **"arquivos"**.
2. Execute o script Python:
```bash
python script.py
```
3. O arquivo **"PDF Final.pdf"** será gerado na pasta do script.

## Funcionamento do Script
1. Lista todos os arquivos dentro da pasta **"arquivos"**.
2. Ordena os arquivos alfabeticamente.
3. Filtra apenas os arquivos que contêm **".pdf"** no nome.
4. Adiciona cada arquivo PDF ao objeto **PdfMerger**.
5. Salva o PDF combinado como **"PDF Final.pdf"**.

## Observação
O script pode ser ajustado para lidar com diferentes ordenações ou para excluir determinados arquivos, caso necessário.

