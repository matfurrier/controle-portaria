# Controle de Visitantes 🏢🔒

Bem-vindo ao projeto Controle de Visitantes. 

## 🏢 Conhecendo o Processo

O objetivo do projeto é informatizar o processo de registro e administração de visitantes da nossa empresa. Atualmente, utilizamos um processo manual e planilhas para registrar informações dos visitantes, e a informatização desse processo visa ganhar tempo, melhorar a experiência dos porteiros e garantir o armazenamento seguro e confiável das informações.

O projeto consiste em uma ou mais páginas web que possibilitam o registro de visitantes, sua visualização e algumas funcionalidades que seguem o fluxo de entrada e saída do visitante nas dependências da empresa.

## 🔍 Principais Funcionalidades

### Registro de Visitantes 📝

O formulário de registro de visitantes abstrai a etapa 01 do processo, onde o visitante informa **nome completo**, **CPF**, **data de nascimento**, **departamento** que deseja visitar e a **placa do veículo**, caso esteja utilizando durante a visita. O formulário salva automaticamente o **horário de chegada** do visitante.

![2023-07-27 15_57_01-Controle de Visitantes](https://github.com/matfurrier/controle-portaria/assets/30526394/16b80bcd-355b-453d-9018-3c76d797897b)

### Listagem de Visitantes 📋

A listagem de visitantes exibe, por meio de uma tabela, os visitantes recentes classificados por horário de chegada, do mais recente ao mais antigo.

![2023-07-27 15_57_23-Controle de Visitantes](https://github.com/matfurrier/controle-portaria/assets/30526394/64b2fd24-ad1d-4d31-8726-e9216be800f5)

### Widgets para Resumo de Informações 📊

Os widgets na página inicial da dashboard exibem um resumo dos números referentes aos visitantes em cada status e o número total de visitantes registrados no mês.

![2023-07-27 15_57_41-Controle de Visitantes](https://github.com/matfurrier/controle-portaria/assets/30526394/a0f216b3-5ec9-4759-b90b-af7ca56ef813)

### Visualização de Informações de Visitante 👀

A partir da tabela que lista os visitantes recentes, é possível acessar a página que exibe as informações detalhadas de cada visitante.

![2023-07-27 15_58_40-Controle de Visitantes](https://github.com/matfurrier/controle-portaria/assets/30526394/ae29c617-34a0-4302-8c55-18cbfd2ec388)

### Autorização de Entrada 🚪

A tela de informações de visitante permite a autorização de entrada do visitante, através do preenchimento de um formulário com o nome do colaborador que autorizou a entrada.

![2023-07-27 15_59_11-Controle de Visitantes](https://github.com/matfurrier/controle-portaria/assets/30526394/c9f96b52-5be8-43fa-b639-f975cf50eb49)

Assim como quando o porteiro anotava o nome do colaborador responsável por autorizar a entrada e o horário de contato com esse colaborador, a funcionalidade recebe o nome do colaborador através de um formulário e salva o horário de contato e autorização de forma automática ao concluir a ação.

![2023-07-27 15_30_32-Controle de Visitantes](https://github.com/matfurrier/controle-portaria/assets/30526394/935c553c-6047-4151-822d-0499f2d0d557)

### Finalização de Visita 🚪🚶

A tela de informações de visitante também permite a finalização da visita, com a confirmação da ação sem necessidade de informações adicionais.

![2023-07-27 15_59_46-Controle de Visitantes](https://github.com/matfurrier/controle-portaria/assets/30526394/ff9a10dd-56cd-4705-9498-2bbaa9bfc8aa)

### Agendamento de Carga/Descarga 📦🚚

Além das funcionalidades já mencionadas, o projeto Controle de Visitantes também inclui a funcionalidade de Agendamento de Carga/Descarga. Essa funcionalidade permite que os colaboradores e visitantes programem previamente o agendamento de cargas e descargas, facilitando o controle e organização das operações de logística na empresa.

## 🔍 Principais Funcionalidades

### Dashboard Geral com Calendário de Agendamentos 📅

Além de exibir um resumo das informações sobre os agendamentos, o dashboard geral apresenta um calendário que permite visualizar as agendas já realizadas. Dessa forma, os colaboradores e responsáveis pela logística podem ter uma visão abrangente das operações já concluídas, bem como das próximas programadas.

![2023-08-01 13_14_37-](https://github.com/matfurrier/controle-portaria/assets/30526394/8d281f40-82d3-4a4f-b09a-6eaa9cd27f3e)

Essa funcionalidade proporciona uma visão mais abrangente do fluxo de agendamentos ao longo do tempo, facilitando o acompanhamento e a organização das atividades de carga e descarga na empresa. Os agendamentos realizados aparecem no calendário com as respectivas datas e horários em que foram programados.

Além disso, o calendário também pode exibir informações adicionais sobre os agendamentos realizados, como o nome da empresa ou visitante envolvido na operação e quaisquer observações relevantes que tenham sido fornecidas durante o agendamento.

![2023-08-01 13_22_27-Controle de Visitantes](https://github.com/matfurrier/controle-portaria/assets/30526394/15e8f468-745a-4175-8352-081ce2a1cbf8)

Essa visualização no calendário torna o processo de gerenciamento de agendamentos mais intuitivo e eficiente, permitindo que a equipe responsável tenha uma visão geral das atividades e se prepare adequadamente para as próximas operações.

### Como Agendar Carga/Descarga

O agendamento de carga/descarga é feito através do formulário disponível no menu de Agendamento. Os fornecedores devem fornecer as seguintes informações:
- Data e hora do agendamento: Selecione a data e hora desejadas para a carga ou descarga.
- Empresa ou visitante: Informe o nome da empresa ou do visitante que realizará a operação.
- Observações: Forneça quaisquer observações ou instruções adicionais relacionadas ao agendamento.

]![2023-08-01 13_22_00-Controle de Visitantes](https://github.com/matfurrier/controle-portaria/assets/30526394/fddd12aa-c633-40e3-b802-dac8cdc6b25d)


## Como Contribuir 👥

Se você deseja contribuir com melhorias para o Controle de Portaria, fique à vontade para abrir uma [issue](https://github.com/matfurrier/controle-portaria/issues) ou enviar um pull request. Sua colaboração é valiosa para aprimorar a qualidade do aplicativo e oferecer uma ferramenta ainda mais eficiente.

## 📄 Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo `LICENSE` para obter mais informações.

## 📬 Contato

Para mais informações ou dúvidas sobre o Controle de Portaria, entre em contato através do e-mail matfurrier@gmail.com.

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

