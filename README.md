# FT_IRC

Este é um projeto que estou desenvolvendo para a escola 42. Estou criando um servidor IRC (Internet Relay Chat) simples do zero, escrito em C++. Este servidor segue a especificação RFC 2812 e pode ser usado com clientes IRC existentes.

O servidor não suporta comunicação entre servidores e é melhor usado com `irssi` ou qualquer cliente que envie pacotes terminados com `\r\n`. Se você quiser testar o servidor sem ter que construí-lo, você pode se conectar ao servidor público `shibrc.fr` usando a senha `password`.

O projeto está disponível no GitHub, e você pode encontrar várias implementações de diferentes estudantes.

## Como usar

1. Clone o repositório
2. Construa o servidor usando o Makefile
3. Execute o servidor
4. Conecte-se ao servidor usando um cliente IRC
