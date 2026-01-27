## Formulário
- input type="text": Para a pessoa escrever na caixa
- input type="submit" value="Enviar": Para a pessoa mandar o formulário
- label: Pode estar associado a um campo de formulário usando o atributo for (que referencia o id), ele cria uma relação com a caixa de nome e sobrenome

## Métodos de Envio de Formulário
- GET: Para dados públicos, buscas e URLs compartilháveis. (padrão)
- POST: Para dados sensíveis, envios de arquivos ou formulários extensos. (os dados n ficam visiveis na URL)
- Quando Usar:
    - GET: quando seus dados n forem sensíveis (nome, peso, etc...), n podem passar de 3.000 bytes ou 3.000 letras
    - POST: Quando seus dados forem sensíveis, +3.000 bytes

## Tipos / input
- password: senha, vai ficar com os pontinhos
- submit: Botão para enviar o formulário
- reset: Botão para limpar o formulário
- number: Só aceita números
- tel: Para telefones
- email: Para emails
- range: Valor em escala númerica (deslizando uma barrinha)
- checkbox: Vai criar uma caixa de cheklist
- radio: Botão de opção única 
    * Para que no radio o usuário possa marcar apenas uma opção, no 'name', tem que por o msm nome para ambos
- Cor: Vai aparecer uma tabela de cor
- File: Pode colocar uma foto
    * Não pode usar o método GET, apenas o POST

## Outros Tipos
- select e option: Criado para criar listas suspensas
- datalist: Permitir criar caixas de texto com sugestões, onde o usuário pode digitar livremente ou escolher entre as opções pre-definidas
- textarea: Um campo de texto multlinha, ideal para mensagens ou comentários
    * Quando for usar o textarea, n pode usar o metodo get, apenas post

## Atributos
- minlength="x": Vai dizer a quantidade minima de caracteres 
- maxlength="x": vai dizer a quantidade máxima de caracteres
- required, deixa um campo obrigatório
- placeholder: Uma frase que vai aparecer dentro da caixa do formulário
- step: O quanto um número vai variar de um para o outro (se ele cresce de 1 em 1, 0.5 em 0.5 ...)
- pattern="^(\d{2}\)\d{4,5}-\d{4}$: Serve para que o formulário do celular aceite apenas (xx)xxxxx-xxxx (Estudar mais sobre RegEx)
- checked: Já deixa uma opção marcada

## AutoComplete
- autocomplete="off / on": Se vai aparecer a caixa de sujestão quando o usuário digite o nome
* Dentro do input:
    - autocomplete="username": Para completar o nome do usuário
    - autocomplete="current-password": Para aparecer a senha atual

## Output
- oniput: "Quando eu entrar com os dados"
- output: Ele n serve para enviar dados, apenas para mostrar na tela
- oninput="i'variavel'.innerHTML = Number'variavel' (código padrão)