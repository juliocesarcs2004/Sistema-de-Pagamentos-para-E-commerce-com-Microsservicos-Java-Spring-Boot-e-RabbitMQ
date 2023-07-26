# Projeto Java com Spring Boot e RabbitMQ

Este projeto é uma aplicação Java com o framework Spring Boot e RabbitMQ. Ele implementa um serviço de avaliação para o , permitindo que os usuários avaliem os pedidos feitos no aplicativo.

## Requisitos

Certifique-se de ter instalado em sua máquina:

- Java 17
- Maven

## Instalação e Execução

1. Faça o clone deste repositório para o seu ambiente local.

2. Navegue até o diretório do projeto.

3. Execute o comando a seguir para compilar o projeto e baixar as dependências:

```
mvn clean install
```

4. Após a conclusão da compilação, execute o seguinte comando para iniciar o aplicativo:

```
java -jar target/avaliacao-0.0.1-SNAPSHOT.jar
```

## Configuração do RabbitMQ

O projeto utiliza o RabbitMQ como sistema de mensageria para processar as avaliações. Certifique-se de ter o RabbitMQ instalado e em execução na sua máquina.

## Descrição do Projeto

```

### Classes Principais

#### AvaliacaoAMQPConfiguration.java

Esta classe é uma configuração do Spring para a comunicação com o RabbitMQ. Ela define os beans necessários para a troca de mensagens e criação de filas.

## Contribuição

Sinta-se à vontade para contribuir com melhorias, correções de bugs ou novos recursos para este projeto. Basta fazer um fork do repositório, implementar suas alterações e enviar um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para obter mais detalhes.

## Contato

Em caso de dúvidas ou sugestões, você pode entrar em contato com os desenvolvedores responsáveis pelo projeto:

- Nome do Desenvolvedor 1 - juliocesarcs2004@gmail.com

Agradecemos o seu interesse em nosso projeto! :)