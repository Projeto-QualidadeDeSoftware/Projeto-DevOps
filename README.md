# Stack Tecnológica

## API

O projeto utiliza:

* **Java** como linguagem de programação;
* **Spring Boot** como framework para desenvolvimento da API REST;
* **Spring Web** para criação dos endpoints e comunicação HTTP;
* **Spring Data JPA** e **Hibernate** para o mapeamento objeto-relacional e persistência dos dados;
* **Bean Validation** para validação das informações recebidas pela API.

## Banco de Dados

O banco de dados utilizado é o **MySQL**, sendo sua estrutura gerenciada pela aplicação por meio do **JPA/Hibernate**.

A aplicação realiza a conexão e a persistência dos dados automaticamente, conforme as entidades e seus relacionamentos definidos no código.

## Ferramentas

O gerenciamento das dependências e do processo de compilação é realizado pelo **Maven**.

Para testes e validação dos endpoints da API, foi utilizado o **Insomnia**.

## Front-end Web - Melissa

A interface web oferece uma experiência de usuário (UX) fluida e responsiva, integrando os fluxos do sistema de vendas, exibição de catálogo de produtos, gerenciamento de carrinho de compras e controle de estoque. O desenvolvimento adota uma arquitetura modular baseada em componentes limpos e reaproveitáveis, garantindo alta performance e facilidade de manutenção.

* **React** como biblioteca core para a construção de interfaces;
* **JavaScript (ES6+)** como linguagem base para o desenvolvimento da lógica da aplicação;
* **Tailwind CSS** como framework CSS utilitário para a criação de designs rápidos, customizados e responsivos;
* **HTML5** e **CSS3** para a estruturação semântica e estilizações base da web;
* **React Icons** como biblioteca centralizada de ícones para os componentes da interface.

## Front-end Desktop - Luiz

A interface Desktop será voltada para operações de PDV (Ponto de Venda) e gestão administrativa, integrada com os endpoints da API REST e focada em performance, uso assíncrono para evitar travamentos de tela e alta testabilidade de software.

* **Java 21 / JavaFX** como tecnologia principal para a construção da interface gráfica;
* **FXML & SceneBuilder** para a estruturação declarativa e componentização das telas;
* **HttpClient & Jackson** para consumo assíncrono da API REST e serialização de dados;
* **JUnit 5 & TestFX** para automação de testes unitários e testes de interface (UI).

## Front-end Mobile - Diego

A interface Mobile terá integração com os endpoints da api, utilizando-se de estratégias de UI e UX para a mais flúida experiência de navegação para usuários que utilizarão dispositivos celulares ou tablets.

* **React Native** Como framework principal;
* **Type-script JSX** como principal linguagem para o desenvolvimento do projeto;

* **HttpClient & Jackson para consumo assíncrono da API REST e serialização de dados;

* **JUnit 5 & TestFX para automação de testes unitários e testes de interface (UI).


