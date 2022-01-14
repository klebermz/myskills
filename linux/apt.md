# apt

Para instalar pacotes e programas em distribuições Linux derivadas do Debian utilizamos o comando apt. Segue abaixo alguns dos comandos:



apt install ou apt-get install (instala um pacote)

apt remove ou apt-get remove (remove um pacote)

apt purge ou apt-get purge (remove o pacote com configuração)

apt update apt-get update ( atualiza o índice do repositório)



A lista de repositórios fica em /etc/apt/sources.list ou /etc/apt/sources.list.d/ (neste segundo caso deve-se adicionar os arquivos do repositório usando extensão .list). Para adicionar um repositório através de comando usamos add-apt-repository 

No exemplo abaixo adicionamos o repositório do pacote MongoDB em uma distribuição Ubuntu:

sudo add-apt-repository 'deb https://repo.mongodb.org/apt/ubuntu bionic/mongodb-org/4.0 multiverse'

Após adicionar o repositório utilizamos o comando sudo apt update para atualizar a lista de repositório e em seguida o comando sudo apt install mongodb-org para instalar o pacote.

Assim finalizamos este artigo simples sobre apt , prometo que em breve irei compartilhar mais artigos sobre Linux aqui no Git Hub.