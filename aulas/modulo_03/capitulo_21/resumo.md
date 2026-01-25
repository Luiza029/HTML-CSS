## Tabelas

## Hierarquia de tabelas (simples)
    TABLE = tabela 
        TABLE ROW = Linha de tabela
            TABLE HEADER = Cabeçalho de tabela
            TABLE DATA = Dado de tabela

## ANATOMIA DE TABELAS GRANDES
    TABLE
        CAPTION
        THEAD
            TR, TD, TH
        TBODY
            TR, TD, TH
        TFOOT
            TR, TD, TH

## Tags
- TH: Título
- TD: Dados

## Efeito Zebrado

- :nth-child
    - (2n) - Efeito zebrado (ou vai de acordo com o número colocado)
    - odd - Linhas impares ficaram cinzas
    - evan - Linhas pares ficam cinzas

## Mesclagem de Células

- rowsoan="x" - Vai ocupar x quantidas de linhas
- colspam="x" - vai ocupar x quantidas de colunas

## Scopo
- "Col" - Diz que este título comanda todos os dados que estão ABAIXO dele (Na coluna)
- "colgroup" - Um grupo maior de colunas

- "Row" - Diz que este título comanda todos os dados que estão a sua Direita (Naquela Linha)
- rowgroup - Um grupo maior de linhas

- Resumo de group:
    - Quando se usa rowspan, geralmente se usa rowgroup e msm coisa com col

- Resumo:
    - col: Título do topo (vertical)
    - row: Título do canto esquerdo (horizontal)

** Se o rowspan for usado apenas para desing, ele ainda é apenas uma linha

![alt text](image.png)
* Disciplina é apenas scope="row", apesar de ter rowspan="2", diferente de notas, notas é um grupo de nota 1 e nota 2, logo um scope="colgruop"