#Brunch for newbies. 
Официальный сайт - http://brunch.io/

Для того, чтобы мы смогли поднять brunch нужно:

- [Node.js](http://nodejs.org)
- [git-bash](http://git-scm.com/downloads)

Запускаем "node.js command promt" и пишем следующие команды:

- npm install -g bower
- npm install -g brunch

Далее выбираем папку, в которой мы будем работать (for Win - cd path/to/work) и пишем следующее (лично я работаю с этим):

- git clone https://github.com/molefrog/brunch-for-homeless

> http://git.io/skeletons - здесь можно найти другие сборки, удобные для вас

После того, как мы склонировали репозиторий %name% со скелетом, который нас устраивает (в моем случае, это brunch-for-homeless), прописываем путь к этому скелету

- cd path/to/work/__brunch-for-homeless__/

Далее используем команды npm install и bower install для того, чтобы развернуть проект. После данных действий можно приступать к работе.
Для того, чтобы заставить brunch работать, мы пишем следующее:
- brunch w -s

