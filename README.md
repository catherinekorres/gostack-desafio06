#  🚀 Bootcamp GoStack - Desafio 06
[Desafio 06](https://github.com/Rocketseat/bootcamp-gostack-desafio-06/blob/master/README.md#desafio-06-aplica%C3%A7%C3%A3o-com-react-native) do Bootcamp GoStack 2019 da Rocketseat

## Descrição
A aplicação salva uma listagem de usuários do GitHub a partir do seu input de forma local (localStorage), e os lista para que se possa ter acesso aos repositórios favoritados por esses usuários no seu perfil.

No perfil do usuário é apresentada a sua foto, nome e biografia.
Abaixo, na listagem dos repositórios é possível visualizar os mesmos por nome e autor.

A aplicação foi construída em React Native, e para os dados consome a API aberta do Github.

## Objetivos
Esse desafio do bootcamp consiste em adicionar funcionalidades extras ao projeto já desenvolvido durante o [módulo 06](https://github.com/catherinekorres/gostack-modulo06) do bootcamp.

Seguem abaixo as funcionalidades extras:

  - [ ] `Loading de repositórios`: Adicionar um indicador de loading utilizando `<ActivityIndicator />` antes de carregar a lista de repositórios favoritados na tela de perfil do Usuário.

  - [ ] `Scroll infinito`: Assim que o usuário chegar nos 20% do final de lista, buscar pelos items na próxima página (de acordo com a paginação da API do GitHub) e adicionar na lista.

  - [ ] `Pull to Refresh`:  Quando o usuário arrastar a listagem de repositórios favoritados pra baixo atualize a lista resetando o estado, ou seja, volte o estado da paginação para a página 1 exibindo apenas os 30 primeiros itens.

  - [ ] `WebView`:  Criar uma nova página na aplicação que vai ser acessada quando o usuário clicar em um repositório favoritado, essa página deve conter apenas o Header da aplicação. Essa página será uma WebView da página do repositório selecionado.
