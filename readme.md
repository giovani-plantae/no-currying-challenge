# No Currying Challenge

O desafio é uma brincadeira mas representa um problema real, o desafio é como trabalhar com eventos on/off dentro de uma classe. Os callbacks devem receber além do payload do evento um parâmetro adicional. Tudo isso de forma legível que não pareça uma gambiarra gigante.

Se ficar completamente perdido, alguns termos podem lhe ajudar: `Currying`, `Partial Application` e `bind vs call vs apply`;

Existe um arquivo `html` com o código inicial que ilustra o problema.

# Cenário

- Existe um servidor onde clientes podem se conectar de forma livre e enviar mensagens;
- Quando um cliente envia uma mensagem, o servidor ouve a mensagem e registra ela;
- Porem agora algum usuário está de zueira mandando mensagens sacanas;
- É necessário criar um log para saber qual usuário manda as mensagens do tipo [NOME]: MENSAGEM;

