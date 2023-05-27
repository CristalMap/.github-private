# Projeto de Mapeamento e Previsão de Maus-Tratos e Abandono Animal

Este projeto tem como objetivo mapear animais perdidos, identificar casos de maus-tratos e, com base nesses dados, prever possíveis novos casos. A finalidade é fornecer auxílio às organizações não governamentais (ONGs), departamentos de proteção animal e tutores que perderam seus animais. Será utilizado Aprendizado de Máquina (Machine Learning) para realizar as previsões, e a aplicação será desenvolvida utilizando as tecnologias .NET e Angular.

## Palavras-Chave: Mapeamento de previsões, Maus-tratos, Abandono animal, Aprendizado de Máquina

## 1. INTRODUÇÃO

Segundo a OMS, cerca de 30 milhões de animais estão em situação de rua no Brasil. Esses animais de estimação são curiosos e ativos, tendo uma necessidade inata de explorar o mundo ao seu redor. No entanto, muitos acabam se perdendo e sofrendo maus-tratos. O abandono de animais, principalmente de cães de grande porte, vira-latas e os considerados agressivos, é um problema comum, levando a uma superpopulação e a graves consequências para a saúde animal e pública.

O tráfico de animais também é uma prática ilegal que causa danos à biodiversidade e pode transmitir doenças zoonóticas aos humanos. Essas questões exigem ações efetivas para proteger os animais e combater essas práticas.

Nesse contexto, este projeto visa criar um mapa que apresente denúncias de maus-tratos a animais e tráfico animal em uma determinada região. Utilizando técnicas de Aprendizado de Máquina, especialmente com o uso da biblioteca ML.NET, pretendemos identificar padrões e características que possam ajudar na detecção precoce de futuros casos. Com base nos dados históricos de denúncias, será possível prever novos possíveis casos e mapear as regiões com maior incidência desses crimes.

## 2. METODOLOGIA

Para o desenvolvimento deste projeto, foram utilizadas as seguintes ferramentas e tecnologias:

- Angular: Framework para construção da interface do aplicativo web.
- C# (.NET): Linguagem e framework para desenvolvimento da API (back-end) do site.
- Azure: Plataforma de nuvem utilizada para hospedar o banco de dados, back-end e front-end do site.
- ML.NET: Biblioteca de Aprendizado de Máquina da Microsoft, usada para criar modelos de previsão com base nos dados disponíveis.
- SQL Server: Sistema de gerenciamento de banco de dados utilizado para armazenar as informações do site.

A metodologia adotada envolveu a pesquisa documental e bibliográfica sobre o abandono animal, maus-tratos, impacto na saúde pública e soluções para esses problemas. Foram consultados websites e fontes confiáveis para obter informações relevantes sobre o tema.

## 3. DESENVOLVIMENTO

O projeto consiste em uma aplicação web com as seguintes funcionalidades:

- Tela inicial: Apresenta informações sobre o projeto e detalhes de contato.
- Página de login de usuário: Permite que os usuários façam login utilizando seu

 nome de usuário e senha.
- Página de registro de usuário: Permite que novos usuários se cadastrem no sistema, fornecendo informações básicas e criando um nome de usuário e senha.
- Mapa de denúncias: Exibe um mapa interativo que mostra a localização das denúncias de maus-tratos e abandono animal reportadas pelos usuários. Os marcadores no mapa fornecem informações sobre cada denúncia, como a descrição do incidente e a data de registro.
- Formulário de denúncia: Permite que os usuários registrem novas denúncias de maus-tratos e abandono animal, fornecendo informações sobre o incidente, como localização, descrição e fotos (opcionais).
- Previsão de casos: Utilizando os dados históricos das denúncias registradas, o sistema utiliza técnicas de Aprendizado de Máquina para prever novos casos de maus-tratos e abandono animal. Essas previsões são exibidas no mapa, ajudando a identificar as áreas com maior probabilidade de ocorrência desses casos no futuro.
- Painel administrativo: Os administradores do sistema têm acesso a um painel administrativo onde podem visualizar, revisar e validar as denúncias reportadas pelos usuários. Eles podem marcar uma denúncia como verificada, rejeitá-la ou tomar outras ações apropriadas.

## 4. CONCLUSÃO

Através deste projeto, buscamos criar um sistema que ajude a mapear casos de maus-tratos e abandono animal, permitindo que as autoridades e ONGs atuem de forma mais eficaz na proteção dos animais. A utilização de técnicas de Aprendizado de Máquina para prever casos futuros pode auxiliar na alocação de recursos e no planejamento de ações preventivas.

Esperamos que este projeto contribua para a conscientização sobre a importância do bem-estar animal, incentivando a denúncia de casos de maus-tratos e o engajamento da sociedade na proteção dos animais. Além disso, pretendemos fornecer uma ferramenta eficaz para as autoridades lidarem com essas questões, resultando em melhores condições de vida para os animais e uma sociedade mais responsável e compassiva.

## Referências
