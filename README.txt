SITE — JUNTAR PDF POR CNPJ

Como funciona:
1. Abra index.html no navegador.
2. Selecione vários PDFs.
3. Clique em "Processar e criar PDFs".
4. O sistema extrai o texto dos PDFs e procura CNPJs válidos.
5. PDFs com o mesmo CNPJ são unidos em um único arquivo.
6. PDFs com CNPJs diferentes são separados automaticamente em arquivos diferentes.
7. PDFs sem CNPJ ficam em PDF_SEM_CNPJ.pdf.
8. Um arquivo que contenha mais de um CNPJ é marcado para revisão e não é misturado automaticamente.

Observação:
- Esta primeira versão funciona melhor com PDFs que possuem texto selecionável.
- PDFs que são apenas imagens/escaneados podem precisar de OCR em uma próxima versão.
- As bibliotecas PDF.js e pdf-lib são carregadas por CDN, portanto é necessário internet ao abrir o site.
- O processamento ocorre no navegador; os PDFs não são enviados para um servidor por este código.
