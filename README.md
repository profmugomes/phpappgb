# phpappgb
Essa é uma outra versão que desenvolvi do PHPApp, essa versão foi desenvolvida no Gambas3, com o PHPAppGB você consegue rodar e desenvolver aplicativos em PHP para desktop.

O PHPAppGB tem uma única diferença do PHPApp que desenvolvi em Python, as portas são geradas pelo sistema assim que chamado o php para iniciar o servidor embutido, ao usar o localhost:0 automaticamente uma porta é definida, ao invés de usar a função socket para isso.

Requer as dependências do repositório do Gambas3 para funcionar.

Versão do Gambas3: 3.18

Requerimento
- Sistema Operacional: GNU/Linux Lubuntu
- Repositório do Gambas3
- gambas3-gb-image
- gambas3-gb-gtk3
- gambas3-gb-forma
- gambas3-gb-gtk3-webview
- php-cli

Testado no Lubuntu

Instalação

Ative o repositório do Gambas3 (estável)
- sudo add-apt-repository ppa:gambas-team/gambas3
- sudo apt update

Instale as dependências necessárias
- sudo apt install gambas3-dev gambas3-gb-image gambas3-gb-gtk3 gambas3-gb-form gambas3-gb-gtk3-webview php-cli

Pronto! Após a instalação das dependências necessárias é só rodar o PHPApp.

Usando o PHPApp (versão Gambas3)
- Crie um arquivo index.php na pasta www
- Clique duas vezes sobre o phpapp.gambas
