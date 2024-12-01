Documentação Projeto Sistem de chamados

Este documento descreve a implementação de um sistema de chamados simples utilizando tecnologias web modernas. O sistema foi desenvolvido para permitir a criação e o gerenciamento de chamados de forma eficiente e intuitiva.

Características principais:
Frontend: Desenvolvido com HTML, CSS e JavaScript, garantindo uma interface limpa e responsiva.
Backend: Implementado com Node.js, utilizando APIs REST para comunicação eficiente entre cliente e servidor.
Banco de Dados: Um arquivo JSON foi utilizado para armazenar os dados dos chamados, adequado para cenários com baixo volume de informações.
Descrição do Sistema

1. Funcionalidades Principais
Criação de Chamados:
Um formulário simples permite que os usuários registrem novos chamados, preenchendo informações básicas como título, descrição e prioridade.

Exibição de Chamados:
Os chamados criados são exibidos em uma lista dinâmica, atualizada em tempo real.

2. Estrutura do Projeto
Frontend:
HTML: Estrutura básica da página, incluindo o formulário de entrada e a lista de exibição.
CSS: Estilo visual responsivo e atraente, garantindo usabilidade.
JavaScript: Scripts para interação do usuário, validação de formulário e comunicação com o backend via chamadas AJAX.
Backend:
Node.js:

Servidor HTTP configurado para lidar com requisições e fornecer os dados necessários para o frontend.
APIs RESTful implementadas para manipulação de dados (GET, POST, PUT e DELETE).
JSON como Banco de Dados:

Arquivo JSON para persistência de dados.
Adequado para aplicações de pequeno porte com baixa complexidade de dados.
3. Comunicação Cliente-Servidor
API REST:
GET: Recuperar lista de chamados.
POST: Criar um novo chamado.
PUT: Atualizar informações de um chamado.
DELETE: Excluir um chamado.
4. Fluxo de Uso
Usuário acessa o sistema e visualiza os chamados existentes na lista.

Novo chamado:
O usuário preenche o formulário com os detalhes do chamado.
O frontend envia os dados via POST para o servidor.
O backend grava os dados no arquivo JSON e retorna a lista atualizada.
Edição ou exclusão de chamados:

Ações realizadas diretamente na lista com opções disponíveis em cada item.
Exibição em tempo real:

A lista é atualizada dinamicamente sem recarregar a página.
5. Benefícios do Sistema
Simplicidade: Estrutura leve e fácil de usar.
Escalabilidade: Pode ser adaptado para um banco de dados mais robusto, como MySQL ou MongoDB, conforme a necessidade.
Agilidade no desenvolvimento: Uso de tecnologias bem estabelecidas e integradas.