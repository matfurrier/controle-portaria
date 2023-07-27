# Controle de Visitantes 🏢🔒

Bem-vindo ao projeto Controle de Visitantes. 

## 🏢 Conhecendo o Processo

O objetivo do projeto é informatizar o processo de registro e administração de visitantes da nossa empresa. Atualmente, utilizamos um processo manual e planilhas para registrar informações dos visitantes, e a informatização desse processo visa ganhar tempo, melhorar a experiência dos porteiros e garantir o armazenamento seguro e confiável das informações.

O projeto consiste em uma ou mais páginas web que possibilitam o registro de visitantes, sua visualização e algumas funcionalidades que seguem o fluxo de entrada e saída do visitante nas dependências da empresa.

## 🔍 Principais Funcionalidades

### Registro de Visitantes 📝

O formulário de registro de visitantes abstrai a etapa 01 do processo, onde o visitante informa **nome completo**, **CPF**, **data de nascimento**, **departamento** que deseja visitar e a **placa do veículo**, caso esteja utilizando durante a visita. O formulário salva automaticamente o **horário de chegada** do visitante.

![Tela de registro de visitante](docs/images/screenshot-from-2020-05-11-14-09-52.png)

### Listagem de Visitantes 📋

A listagem de visitantes exibe, por meio de uma tabela, os visitantes recentes classificados por horário de chegada, do mais recente ao mais antigo.

![Tela com lista de visitantes recentes](docs/images/screenshot-from-2020-05-11-16-26-59.png)

### Widgets para Resumo de Informações 📊

Os widgets na página inicial da dashboard exibem um resumo dos números referentes aos visitantes em cada status e o número total de visitantes registrados no mês.

![Captura de tela de widgets para resumo de informações de visitantes](docs/images/screenshot_2020-04-08_12-21-52%20%281%29.png)

### Visualização de Informações de Visitante 👀

A partir da tabela que lista os visitantes recentes, é possível acessar a página que exibe as informações detalhadas de cada visitante.

![Tela de informações de visitante](docs/images/screenshot-from-2020-05-11-16-41-43.png)

### Autorização de Entrada 🚪

A tela de informações de visitante permite a autorização de entrada do visitante, através do preenchimento de um formulário com o nome do colaborador que autorizou a entrada.

![Tela de informações de visitante com botão para autorizar a entrada](docs/images/screenshot-from-2020-05-11-16-42-04.png)

### Finalização de Visita 🚪🚶

A tela de informações de visitante também permite a finalização da visita, com a confirmação da ação sem necessidade de informações adicionais.

![Tela de informações de visitante com botão para finalizar visita](docs/images/screenshot-from-2020-05-11-16-42-56.png)

## 🛠️ Tecnologias Utilizadas

O projeto utiliza as seguintes tecnologias e recursos de código aberto:

* [Django framework](https://www.djangoproject.com/)
* [Django widget tweaks](https://github.com/jazzband/django-widget-tweaks)
* [Start Bootstrap - SB Admin 2](https://github.com/BlackrockDigital/startbootstrap-sb-admin-2)

## 📚 Requisitos Desejáveis

* Conhecimentos básicos da linguagem Python
  * Funções
  * Programação Orientada a Objetos
* Conhecimentos básicos em HTML, CSS e JS
  * Noções de [Bootstrap](https://getbootstrap.com/)
* Sistema operacional baseado em Unix
* Conhecimentos básicos em terminal

