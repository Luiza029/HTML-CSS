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