# Controle de Visitantes 🏢🔒

Bem-vindo ao projeto Controle de Visitantes. 

## 🏢 Conhecendo o Processo

O objetivo do projeto é informatizar o processo de registro e administração de visitantes da nossa empresa. Atualmente, utilizamos um processo manual e planilhas para registrar informações dos visitantes, e a informatização desse processo visa ganhar tempo, melhorar a experiência dos porteiros e garantir o armazenamento seguro e confiável das informações.

O projeto consiste em uma ou mais páginas web que possibilitam o registro de visitantes, sua visualização e algumas funcionalidades que seguem o fluxo de entrada e saída do visitante nas dependências da empresa.

## 🔍 Principais Funcionalidades

### Registro de Visitantes 📝

O formulário de registro de visitantes abstrai a etapa 01 do processo, onde o visitante informa **nome completo**, **CPF**, **data de nascimento**, **departamento** que deseja visitar e a **placa do veículo**, caso esteja utilizando durante a visita. O formulário salva automaticamente o **horário de chegada** do visitante.

![screenshot-from-2020-05-11-14-09-52](https://github.com/matfurrier/controle-portaria/assets/30526394/cd5c1283-e79f-4805-be9d-ff07ff2a181d)

### Listagem de Visitantes 📋

A listagem de visitantes exibe, por meio de uma tabela, os visitantes recentes classificados por horário de chegada, do mais recente ao mais antigo.

![screenshot-from-2020-05-11-16-26-59](https://github.com/matfurrier/controle-portaria/assets/30526394/a8cd2bef-2cb3-4453-b52b-b2fb75290bdc)

### Widgets para Resumo de Informações 📊

Os widgets na página inicial da dashboard exibem um resumo dos números referentes aos visitantes em cada status e o número total de visitantes registrados no mês.

![screenshot_2020-04-08_12-21-52 (1)](https://github.com/matfurrier/controle-portaria/assets/30526394/6363de6b-0dc2-49f6-9c5f-f458b899e18b)

### Visualização de Informações de Visitante 👀

A partir da tabela que lista os visitantes recentes, é possível acessar a página que exibe as informações detalhadas de cada visitante.

![screenshot-from-2020-05-11-16-41-43](https://github.com/matfurrier/controle-portaria/assets/30526394/1f722b42-e988-48a3-80a2-7136f1d7b7f0)

### Autorização de Entrada 🚪

A tela de informações de visitante permite a autorização de entrada do visitante, através do preenchimento de um formulário com o nome do colaborador que autorizou a entrada.

![screenshot-from-2020-05-11-16-42-04](https://github.com/matfurrier/controle-portaria/assets/30526394/d99a52d1-39d6-45ca-8890-a23f9cdbf14d)

Assim como quando o porteiro anotava o nome do colaborador responsável por autorizar a entrada e o horário de contato com esse colaborador, a funcionalidade recebe o nome do colaborador através de um formulário e salva o horário de contato e autorização de forma automática ao concluir a ação.

![2023-07-27 15_30_32-Controle de Visitantes](https://github.com/matfurrier/controle-portaria/assets/30526394/935c553c-6047-4151-822d-0499f2d0d557)

### Finalização de Visita 🚪🚶

A tela de informações de visitante também permite a finalização da visita, com a confirmação da ação sem necessidade de informações adicionais.

![screenshot-from-2020-05-11-16-42-56](https://github.com/matfurrier/controle-portaria/assets/30526394/50d532fb-5eae-42a6-82f6-30c6c5040014)

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

