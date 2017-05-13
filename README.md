# jClient-1.8

This version was developed to be undetectable (Ghost) by any developed system is a private (Paid) version. In this repository there is a demonstration of how it works and its wiki containing all its functions within the game. It only has the following languages: English, Portuguese, Russian and Spanish.

**[PT]** Essa versão foi desenvolvida para ser indetectável (Fantasma) por qualquer sistema desenvolvido é uma versão privada (Paga). Nesse repositório há uma demonstração de como ele funciona e sua wiki contendo todas suas funções dentro do jogo. Ela apenas tem as seguintes linguagens: Inglês, Português, Russo e Espanhol.

It's working perfectly, without any errors, if it will be fixed as soon as it is reported here in github.

**[PT]** Está funcionando perfeitamente, sem nenhum erro, caso haja será arrumado assim que ele for reportado aqui no github.

### Features:

 * You can install any mod **forge** and **liteloader**
 * Show game data
 * Show player details
 * Account change in game
 * Minimap
 * Macros and keybinds integrated in version
 * Optifine 1.8 HD U H6
 * You can use **Skript** to configure

### Here is a legal code to start! :page_with_curl:

```cson
on join:
	wait 3 ticks
	if player is default:
		if text from "https://api.risemc.com.br/p/jclient/" is not "{@playerID}":
			play "block_note_pling" to player
			message "&fUse &b&l/link &fto add your in-game account to your site's account"
			stop
```

This code was developed for the [RiseMC](http://risemc.com.br) server, in case any server you want to use please contact to be using the server-only api.

Also it's integrated into hypixel's api to use replace `https://api.risemc.com/p/jclient/` for `https://api.hypixel.net/session/uuid`

The placeholder `{@playerID}` is part of the version code, it is used to know if the logged-in id is the same that is registered on the server or on the site.

### Copyright

JabsClient © 2017
