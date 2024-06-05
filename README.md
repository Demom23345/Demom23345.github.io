# Como utilizar? 
Para utilizar esses comandos em seu bot crie um arqivo no aplicativo Bot Designer For Discord com o prefixo do bot, Exemplo: S?
E coloque o seguinte codigo nele:
```
$nomention $botTyping
$var[prefix;$toLowercase[$message[1]]]

$eval[$httpGet[https://raw.githubusercontent.com/Demom23345/Quazar-bot/main/Database/Emojis.dbd]$httpResult]

$var[script;$eval[$httpGet[https://raw.githubusercontent.com/Demom23345/Quazar-bot/main/Redirecionardor]$httpResult]]

$eval[$httpGet[https://raw.githubusercontent.com/Demom23345/Quazar-bot/main/Api/Rank.dbd]$httpResult]

$eval[$httpGet[$var[script]]$httpResult]
```
