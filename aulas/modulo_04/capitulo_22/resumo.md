## Iframe
- tamanho padrão: 300x150px
- scolling: 
    - Auto: Se o contúdo passar do tamanho do frame, vai criar uma barra de rolagem (padrão)
    - yes: Msm o conteúdo cabendo dentro do frame ia criar uma barra de rolagem
    - no: não deixa rolar o frame

## Segurança
- Para bloquear ações que são possivelmente maliciosas
    - sandbox: config. básica, ele bloqueia todo e qualquer acesso que outros sites estejam dentro do iframe
    - referrerpolicy="no-refere": o conteúdo dentro do iframe não vai coletar nenhum tipo de informação do usuário
    - sandbox="allow-same-origin allow-forms allow-scripts": Vai permitir coisas da msm origem, formuláios e scripts

        