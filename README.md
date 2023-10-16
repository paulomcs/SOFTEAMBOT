# SOFTEAM MICROBOT
## Descrição
O projeto consiste numa automação para mensagens da softeam, utilizando o bot do Discord, e se der tempo, um de Whatsapp também. O bot será capaz de enviar mensagens de aniversário, de aviso sobre projetos, e de lembretes de ociosidade.
## Como usar
Para usar o bot, basta digitar o comando !help no chat do Discord, e o bot irá te responder com os comandos disponíveis.
## Comandos
### !help
O comando !help mostra todos os comandos disponíveis.
### !mensagem
O comando !mensagem envia uma mensagem para um grupo de Usuários especifico. Para usá-lo, basta digitar !mensagem + o nome do grupo + a mensagem que deseja enviar entre chaves.
Exemplo: !mensagem {grupo1, grupo2, ... grupoN} {mensagem}
### !aniversario
O comando !aniversario envia uma mensagem de aniversário para todos os aniversariantes cadastrados no banco de dados. Para usá-lo, basta digitar !aniversario + a mensagem que deseja enviar entre chaves.
Exemplo: !aniversario {mensagem}
### !cadastrar
O comando !cadastrar cadastra um novo integrante ao banco de dados. Para usá-lo, basta digitar !cadastrar + o nome do integrante + a data de aniversário do integrante + numero de Whatsapp.
Exemplo: !cadastrar {nome} {xx/xx/xxxx} {(xx) xxxxx-xxxx}

## Código baseado em:
https://github.com/Ast0lf0/Basic-Level-Sytem-for-Discord/tree/master/bot