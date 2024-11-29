# DSList - Frontend com React

Aplicação frontend desenvolvida para consumir uma API REST voltada para organização de jogos em coleções. Este projeto utiliza React para construção de interfaces modernas e responsivas, com integração ao back-end para exibição e manipulação de dados.

## Funcionalidades Principais
- Exibição de coleções de jogos organizadas por gêneros.
- Listagem detalhada de jogos com informações como título, ano, descrição e imagem.
- Alteração da posição de jogos dentro de uma lista diretamente na interface do usuário.
- Navegação responsiva e intuitiva.

## Aprendizados Principais  

### **Desenvolvimento Frontend**  
- Criação de componentes reutilizáveis com React.
- Gerenciamento de estado utilizando React Hooks.
- Consumo de APIs REST utilizando axios para integração ao back-end.

### **Estilização**  
- Construção de interfaces amigáveis com CSS Modules e Bootstrap.
- Design responsivo, adaptando-se a diferentes tamanhos de tela.

### **Integração com Back-end**  
- Consumo de endpoints do back-end para exibição dinâmica de dados.
- Tratamento de erros e exibição de mensagens claras para o usuário.
- O frontend consome os seguintes endpoints do back-end:
  - Buscar listas de jogos: GET /lists
  - Buscar jogos por ID da lista: GET /lists/{listId}/games
  - Alterar posição de jogos: POST /lists/{listId}/replacement

## Tecnologias Utilizadas  
- **React 18++**
- **Axios**
- **Bootstrap**
- **CSS Modules**  
- **JavaScript ES6+**  
  
