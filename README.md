# Kuma Bot

![Fundador](https://img.shields.io/badge/Fundador-Tur1st4-red.svg?style=for-the-badge&logo=arch-linux) ![Linguagem](https://img.shields.io/badge/Linguagem-JavaScript-yellow.svg?style=for-the-badge&logo=JavaScript) [![Discloud](https://img.shields.io/badge/Host-Discloud%20%E2%9D%A4%EF%B8%8F-blue.svg?style=for-the-badge)](https://discloudbot.com/)

## Status :~

[![Discord Bots](https://discordbots.org/api/widget/599693638523551904.svg)](https://discordbots.org/bot/599693638523551904)

Bot criado em JavaScript para ajudar a cuidar do seu servidor!

[![Adicionar o Kuma no seu servidor](https://i.imgur.com/mvYkymB.png)](https://discordapp.com/api/oauth2/authorize?client_id=599693638523551904&permissions=8&scope=bot)

[![Suporte](https://i.imgur.com/sTHMEI4.png)](https://discordapp.com/invite/dtw2VXY)

## Funções

Use todos os comandos com o prefixo :~ `>_`

Se o bot não estiver respondendo no servidor, pode ser que esteja customizado.

Praticamente todos os comandos tem seus aliases, como por exemplo, o comando ajuda pode ser executado somente com o prefixo e a letra `a`, assim :~ `>_a`.
Para ver os aliases de um comando digite :~ `>_a [nome do comando]` -> exemplo :~ `>_a prefixo`

* `ajuda`  
*uso alternativo* :~ [nome do comando]  
*resposta* :~ envia todos os comandos no seu DM ou envia como usar um comando específico.  
*exemplos* :~ `>_ajuda`, `>_ajuda prefixo`

* `bot`   
*resposta* :~ envia o link para me convidar para o seu servidor.

* `criador`  
*resposta* :~ envia as informações do criador.

* `ping`  
*resposta* :~ Envia o ping da API.

* `bee`  
*resposta* :~ Boop!

* `avatar`  
*uso alternativo* :~ [mencione um usuario]  
*resposta* :~ envia o seu avatar ou do usuário mencionado.  
*exemplos* :~ `>_avatar`, `>_avatar @Membro`

* `uinfo`  
*resposta* :~ envia suas informações.

* `bater`  
*uso* :~ [mencione um membro]  
*resposta* :~ bate em um membro.  
*exemplo* :~ `>_bater @Membro`

* `dinheiro`  
*resposta* :~ mostra a quantia de dinheiro que você possui.

* `doar`  
*uso* :~ [mencione um membro]  
*resposta* :~ doa uma quantia de dinheiro para o membro mencionado.  
*exemplo* :~ `>_doar @Membro`

* `bonusdiario`  
*resposta* :~ recebe seu bônus diário.

* `servidor`  
*resposta* :~ envia as informações do servidor.

* `convidarservidor`   
*resposta* :~ cria um convite compartilhável para as pessoas entrarem no servidor.

* `nivel`  
*uso* :~ [ativar(a), remover(rm)]  
*resposta* :~ define ou remove os niveis dos usuários no servidor.  
*exemplos* :~ `>_nivel ativar`, `>_nivel remover`

* `bemvindo`  
*uso* :~ [id do canal, remover(rm)]  
*resposta* :~ define ou remove o canal para enviar uma mensagem de boas-vindas.  
*exemplos* :~ `>_bemvindo 123456789101112`, `>_bemvindo remover`

* `cargobv`  
*uso* :~ [id do cargo, remover(rm)]  
*resposta* :~ define ou remove o cargo que será dado quando um usuário entrar.  
*exemplos* :~ `>_cargobv 123456789101112`, `>_cargobv remover`

* `cargobot`  
*uso* :~ [id do cargo, remover(rm)]  
*resposta* :~ define ou remove o cargo que será dado quando adicionar um bot.  
*exemplos* :~ `>_cargobot 123456789101112`, `>_cargobot remover`

* `verificacao`  
*uso* :~ [ativar(a), remover(rm)]  
*resposta* :~ ativa ou desativa a verificação ao entrar um usuário.  
*exemplos* :~ `>_verificacao ativar`, `>_verificacao remover`

* `cargo`
*uso* :~ [mencione um membro] [id do cargo]  
*resposta* :~ atribui o cargo citado para o membro mencionado.  
*exemplo* :~ `>_cargo @Membro 123456789101112`

* `removercargo`
*uso* :~ [mencione um membro] [id do cargo]  
*resposta* :~ remove o cargo citado do membro mencionado.  
*exemplo* :~ `>_cargo @Membro 123456789101112`

* `chutar`  
*uso* :~ [mencione um membro] [motivo]  
*resposta* :~ expulsa o membro e envia uma mensagem com as informações.  
*exemplo* :~ `>_cargo @Membro Enviou imagens impróprias`

* `banleve`
*uso* :~ [mencione um membro] [motivo]  
*resposta* :~ bane e remove o ban quase instantaneamente.  
*exemplo* :~ `>_banleve @Membro Enviou imagens imprórias`

* `banir`  
*uso* :~ [mencione um membro] [motivo]  
*resposta* :~ bane o membro e envia uma mensagem com as informações.  
*exemplo* :~ `>_cargo @Membro Enviou imagens impróprias`

* `apagar`  
*uso* :~ [número de 1 a 100]  
*resposta* :~ exclui mensagens conforme o número colocado.  
*exemplo* :~ `>_purge 55`

* `prefixo`  
*uso* :~ [novo prefixo]  
*resposta* :~ muda o prefixo do bot.  
*exemplo* :~ `>_prefixo $`

* `criar`  
*uso* :~ [nome do canal] [text, voice, category]  
*resposta* :~ cria um canal ou categoria.  
*exemplos* :~ `>_criar chat-programação text`, `>_criar Programação voice`, `>_criar Programação category`

* `vincular`  
*uso* :~ [id da categoria]  
*resposta* :~ vincula o canal que você usou o comando na categoria citada.  
*exemplo* :~ `>_vincular 123456789101112`

* `deus`  
*uso* :~ [confirme para usar]  
*resposta* :~ configura um servidor inteiro.  
*exemplo* :~ `>_deus`, o bot enviará uma mensagem explicando como funciona, se estiver de acordo digite `sim`, ou se quiser cancelar digite `não`.

**Obs**: O cargo `Kuma` precisa estar acima de todos os cargos para executar o comando `deus`.
