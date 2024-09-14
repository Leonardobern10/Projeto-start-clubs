# Soccer API

Este projeto é uma API desenvolvida em TypeScript usando Express.js para gerenciar informações relacionadas a clubes e jogadores de futebol. 
A API fornece endpoints para realizar operações CRUD (Create, Read, Update, Delete) em jogadores e clubes, utilizando serviços e repositórios 
para separar a lógica de negócio da interação com os dados.

## Funcionalidades

- **Clubes**: 
  - Listar todos os clubes disponíveis.
  - Inserir, atualizar ou remover clubes.
  
- **Jogadores**:
  - Listar todos os jogadores disponíveis.
  - Buscar jogador por ID.
  - Inserir, atualizar ou remover jogadores.
  - Manipular estatísticas de jogadores.

## Estrutura do Projeto

- **Controllers**: Gerencia as requisições HTTP e responde de acordo com os serviços chamados.
- **Services**: Contém a lógica de negócio e intermedia a comunicação entre os controllers e os repositórios.
- **Repositories**: Responsável pelo acesso e manipulação dos dados.
- **Models**: Define as interfaces e modelos de dados utilizados na aplicação.
- **Utils**: Contém funções auxiliares como manipuladores de respostas HTTP.

## Habilidades Abordadas

- Desenvolvimento de APIs RESTful com Express.js e TypeScript.
- Manipulação de dados estruturados utilizando JSON.
- Implementação de padrões de projeto como separação de camadas (controllers, services, repositories).
- Tratamento de erros e respostas HTTP adequadas.
- Uso de interfaces TypeScript para garantir tipagem segura e consistente.

## Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/football-api.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd football-api
    ```
3. Instale as dependências:
    ```bash
    npm install
    ```
4. Inicie a aplicação:
    ```bash
    npm run start
    ```

## Uso

Após iniciar a aplicação, você pode interagir com os endpoints da API utilizando uma ferramenta como o Postman ou diretamente via cURL.

Exemplo de requisição para listar todos os jogadores:
```bash
GET http://localhost:3000/players
```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests para melhorias e correções de bugs.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

Para mais informações ou dúvidas, entre em contato com:
<br />
- Email: [leonardo.bernardo2658@gmail.com](mailto:leonardo.bernardo2658@gmail.com).
- LinkedIn: [Leonardo](https://www.linkedin.com/in/leonardo-bern/).
