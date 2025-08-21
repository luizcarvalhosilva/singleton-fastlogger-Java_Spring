<h1 align="left">📌 Projeto: Singleton com Spring Boot</h1>

###

<h2 align="left">Descrição</h2>

###

<p align="left">Aplicação prática do padrão de desenvolvimento Singleton com abstrações do Spring Framework.<br><br>A ideia foi criar um serviço de Logger que é utilizado em toda a aplicação de forma centralizada, garantindo que apenas uma instância exista durante todo o ciclo de vida da aplicação.</p>

###

<h2 align="left">🛠 Tecnologias utilizadas</h2>

###

<p align="left">⚊ Java 17+<br>⚊ Spring Boot 3.5.4<br>⚊ Maven<br>⚊ Visual Studio Code (IDE)</p>

###

<h2 align="left">📐 Estrutura do projeto</h2>

###

<p align="left"><strong>LoggerService</strong> → Bean Singleton responsável por registrar logs (utiliza @Component).<br><br><strong>UserService</strong> → Serviço que consome o LoggerService para registrar ações sobre usuários (@Service).<br><br><strong>SingletonDemoApplication</strong> → Classe principal que inicializa o contexto Spring Boot e executa testes práticos.</p>

###

<h3 align="left">▶️ Como executar</h3>

###

1. Clone o repositório ou baixe o projeto.
2. No terminal, rode:

  ```shell
mvn spring-boot:run
