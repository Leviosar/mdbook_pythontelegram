# Bots

Assim como no minicurso, o material aqui serve para o desenvolvimento de um bot que envia memes aleatórios que são servidos de uma API externa, depois de ter criado o seu bot com o BotFather, você só precisa garantir que:

- Está com o Python 3.7.x instalado na sua máquina
- Possui permissão para instalar pacotes utilizando o Pip

Tendo essas permissões, você pode rodar em um terminal `pip install --user python-telegram-bot` e esperar a instalação terminar, essa é a única dependendência necessária pra rodar o bot, mas caso você adicione features que tenham dependências externas vai precisar instalar elas também.

O código do bot pode ser encontrado no meu Github, o link para o repositório é [esse](https://github.com/leviosar/memebot), depois de clonar ou baixar o código, crie um arquivo na página inicial do projeto chamado `config.json`, copie e cole o conteúdo de `config.example.json` para dentro desse arquivo e substitua "YOURTOKEN" pela sua chave de API, para garantir que o bot tenha acesso a sua chave.

Por último execute o arquivo `__init__.py` e seu bot deve estar funcionando normalmente.