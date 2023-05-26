# escalasuporte

# Projeto "Calendário de Turnos"

## Descrição do Projeto
O projeto "Calendário de Turnos" é uma aplicação web construída com HTML, CSS, JavaScript, jQuery, e a biblioteca FullCalendar.js. Esta aplicação tem como objetivo facilitar o gerenciamento de turnos de trabalho em um calendário interativo.

## Recursos Principais

1. **Interface do Calendário**: O núcleo desta aplicação é um calendário interativo. Cada evento do calendário representa um turno de trabalho atribuído a um funcionário. Os eventos são coloridos de acordo com o turno de trabalho (T1, T2, T3) para melhor visualização.

2. **Adicionar Turnos**: Através do formulário no cabeçalho, os usuários podem adicionar novos turnos de trabalho no calendário. Eles podem selecionar o turno, horário, funcionário e data do novo turno.

3. **Visualizar Detalhes do Turno**: Ao clicar em um evento do calendário, os usuários podem visualizar os detalhes do turno de trabalho (turno, horário, e o nome do funcionário) em uma janela modal.

4. **Editar Turnos**: A janela modal que exibe os detalhes de um turno também permite que os usuários editem esses detalhes. Eles podem modificar o turno, o horário, e o funcionário de um turno existente.

5. **Excluir Turnos**: Os usuários também têm a opção de excluir um turno de trabalho existente através da janela modal de detalhes do turno.

6. **Persistência de Dados**: Todos os turnos de trabalho adicionados ao calendário são armazenados no localStorage do navegador. Isso significa que os turnos de trabalho continuarão a ser exibidos mesmo depois de recarregar a página.

## Como Usar

1. Abra o arquivo HTML em seu navegador.
2. Use o formulário no cabeçalho para adicionar um novo turno de trabalho.
3. Clique em um evento do calendário para visualizar, editar, ou excluir o turno de trabalho.
4. Recarregue a página para verificar se os dados persistem.

## Dependências

Este projeto depende de várias bibliotecas e frameworks, que são:

- [jQuery 3.5.1](https://code.jquery.com/jquery-3.5.1.min.js)
- [jQuery UI 1.12.1](https://cdnjs.cloudflare.com/ajax/libs/jqueryui/1.12.1/jquery-ui.min.js)
- [Bootstrap 4.5.0](https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css)
- [Moment.js 2.29.1](https://cdnjs.cloudflare.com/ajax/libs/moment.js/2.29.1/moment.min.js)
- [FullCalendar 4.2.0](https://fullcalendar.io/)

Certifique-se de ter uma conexão com a internet ao executar este projeto para poder carregar essas bibliotecas a partir dos CDN mencionados.

## Contribuições

Contribuições para este projeto são bem-vindas. Se você tiver alguma ideia para melhorar a aplicação, sinta-se à vontade para fazer um fork do repositório e enviar um pull request.
