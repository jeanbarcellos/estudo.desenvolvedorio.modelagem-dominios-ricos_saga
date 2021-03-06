_Repositório apenas para estudo_

# Projeto: Sagas

Este projeto é uma DEMO da Aula **09-13 - Trabalhando com Sagas, Service Bus e Filas MSMQ** do curos **Modelagem de Domínios Ricos**

.....

O curso Modelagem de Domínios Ricos foi criado para atender uma grande necessidade de todos os programadores:

Escrever aplicações corporativas complexas e com foco no negócio. E para isso é necessário mais do que tecnologia, é preciso conhecer muitos conceitos e padrões como DDD, CQRS, Event Sourcing e etc. São esses os pilares necessários para projetar arquiteturas modernas e distribuídas.

Neste curso você aprenderá todo conceito de forma prática e teórica e irá aprender a desenvolver uma aplicação separada em contextos independentes que se comunicam por eventos.

Apesar da complexidade de regras e de conceitos você será capaz de desenvolver aplicações fáceis de manter e estender, pois utilizaremos as práticas recomendadas que tornam o código desacoplado, simples de entender e fácil de testar.

Todos os códigos deste curso foram escritos com .NET Core (última versão)

Instrutor:

- [Eduardo Pires](https://www.eduardopires.net.br/)

Referências:

- https://desenvolvedor.io/curso-online-modelagem-de-dominios-ricos/

<br>
<br>
<br>

## Instalação do RabitMQ

- Download/Instalação no Windows

  https://www.rabbitmq.com/download.html

  - Pré-requisito:
    - [erlang](https://www.erlang.org/downloads)

- Habilitar o Management Plugin [Documentação](https://www.rabbitmq.com/management.html)

  - Ir até o diretório dp instalação

  ```
  C:\Program Files\RabbitMQ Server\rabbitmq_server-3.8.14\sbin
  ```

  - Abrir o terminal neste local

  - Executar o seguinte comando:

  ```bash
  rabbitmq-plugins enable rabbitmq_management
  ```

  - Acesso loclhoast

  ```
  http://localhost:15672
  ```
