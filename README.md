# Lavalink Heroku-Server Filters Enable!

Versão do lavalink: **v1.3.74** FUNCIONANDO!!

- Our [Discord] support server (https://discord.tredux.xyz)

##### Atenção!

The automatic installation will restart your server, so be aware that the repository is open to the public for free use, I will not assume any responsibility for damages, for applications already used in the same instance !!

### One-click installation: - Continue reading below !!
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/kasigamin03/Lavalink-Heroku-24-7)

- Buildpacks should be added automatically, you can change the variable PASSduring installation to change the server password.

## Erros/Advertências:
1. After changing the `PASS`, you must expand again or click on the menu ` More`and click on Restart all dynos .
2. Se o Heroku não puder configurar buildpacks automaticamente, vá para as configurações de seus projetos no site do Heroku e adicione `java e nodejs.`

Atenção, entenda que seu servidor lavalink está **sem memória**. Se você estiver fazendo uma atualização, deve alterar **- Xmx** em `JAVA_TOOL_OPTIONS` para a nova quantidade de RAM disponivel em seu servidor

## ATENÇÃO!!
- Para funcionar 24/7 na heroku você devera fazer um fork desse repositorio e editar as seguintes partes 
- URL dentro do arquivo `lavalink.js` linha 15
- Onde está `seu_nome_aqui` colocar seu usuario do github, para funcionar você deve fazer um fork desse repositorio!!

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/kasigamin03/Lavalink-Heroku-24-7)

- Caso queira contribuir com o projeto envie uma pull request <3

### Meu servidor Lavalink
- Host: lavalink-heroku-prcojs.herokuapp.com
- Password: PrCoJs
