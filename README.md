# Client Room

Projeto Front end utilizando Angular na versão 12.2.2.

BootStrap 5 e jquary 

A api roda localmente no endereço http://localhost:4200/

___

## Motivação

A API foi construida para o Projeto de conclusão do BootCamp Santander Full Stack ministrado pela DIO(Digital Innovation One).

Ela se destina ao gerenciamento da Sala de Reunião exibindo as reservas e o assunto a ser tratado na reserva, traz a possibilidade de editar excluir e adicionar novo agendamento

---

A API faz integração com o BeckEnd pelo endereço http://localhost:8082/api/v1/room

---

## Rotas

Ao acessar a API ela redireciona automaticamente para para http://localhost:4200/rooms  onde é listado todas as reservas ja realizadas.

Ao acessar http://localhost:4200/add traz a possibilidade de adicionar uma nova reserva.

Ao acessar http://localhost:4200/update/:id ela exibe um formulario onde é possivel atualizar a reserva, onde id é a indentificaçao da reserva obtida automaticamente pela api

Ao acessar http://localhost:4200/details/:id ela exibe uma tela com todas as informações da reserva especifica, onde id é a indentificaçao da reserva obtida automaticamente pela api

---
Ficou alguma duvida ou tem sugestão para melhorias  me chame no linkedin https://www.linkedin.com/in/rafael-chaves-b5a515213/

Meu Perfil na DIO https://www.linkedin.com/in/rafael-chaves-b5a515213/