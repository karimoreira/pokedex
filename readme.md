# Pokédex app

Este é um projeto de uma Pokédex, construída usando HTML, CSS e JavaScript. O projeto consome a [PokeAPI](https://pokeapi.co/) para exibir informações sobre os pokémons. Desenvolver essa Pokédex foi uma experiência extremamente prazerosa, aprendi muito e me diverti ao mesmo tempo.

## Funcionalidades

- **Busca de Pokémon:** O usuário pode buscar Pokémons pelo nome ou número diretamente na barra de pesquisa.
- **Navegação entre Pokémons:** Existem botões "Prev" e "Next" que permitem navegar entre os Pokémons em sequência.
- **Exibição dinâmica:** Quando um Pokémon é carregado, nome e número são exibidos na interface.
- **Feedback visual:** Caso o Pokémon buscado não seja encontrado, uma mensagem informando "Não encontrado :c" é exibida.

## Estrutura do Projeto

O projeto é composto pelos seguintes arquivos principais:

- `index.html`: estrutura básica da minha aplicação e conexão com os estilos e scripts.
- `styles.css`: Estilos para a interface da Pokédex.
- `scripts.js`: Criação da lógica principal do aplicativo, buscando os dados da API e manipulando o DOM para exibir as informações.

## Como o Projeto Funciona (para exercitar meu conhecimento e também explicar o que foi feito)

1. **Busca de dados na API:** Utilizando a função `fetchPokemon`, fiz uma requisição à PokeAPI para buscar as informações do Pokémon baseado no nome ou número digitado pelo usuário

2. **Renderização dinâmica:** A função `renderizandoPokemon` é responsável por atualizar a interface com as informações retornadas da API. Se um Pokémon for encontrado, sua imagem e detalhes são exibidos; senão, é feito um tratamento de erro.


3. **Navegação entre Pokémons:** O projeto inclui botões para navegar para o Pokémon anterior e o próximo, atualizando a exibição automaticamente.

### Vídeo do app
[Assista ao vídeo/gif da minha Pokédex](https://www.veed.io/view/3b139c54-2bbf-46bb-a5ef-1c832fe6005f)


### Deploy
[Brinque com a Pokédex](https://real-pokedex-fun.vercel.app/)
