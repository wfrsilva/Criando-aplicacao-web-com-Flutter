# Criando-aplicacao-web-com-Flutter
## Criando um aplicação web com Flutter (usando chrome para rodar)
### Usando Google Chorme para substituir os emuladores (AVDs) | Rodando Flutter no Chrome
 
Após desesperadas tentativas de fazer o Flutter rodar nos AVDs do Android Studio, me deparei com esse link:
https://flutter.dev/docs/get-started/web

Que na essencia é para criar um aplicativo Web no Flutter, mas acredito que podemos usar isso para o Chrome substituir, pelo menos de forma provisória, o uso do AVD e suas emulações.

Consiste basicamente em configurar e rodar o fluttter no Google Chrome.

Mudei a ordem do documento original, de forma a ficar mais rapido e didático. 
Também não peguei todo tutorial original, apenas os necessários para uma inicada rápida o seu Flutter no Chrome.

Tambem estou cosniderando que seu projeto já está pelo menso iniciado, mesmo qeu seja o exemplo do Flutter.

<hr>


# Adicionar suporte web para um app Flutter existente

Para adicionar suporte web a um projeto existente, rode o comando abaixo no terminal, na pasta raiz do projeto Flutter:

$ `flutter create .`



# Configuração

Rode os comandos informados abaixo para usar a ultima versão do SDK Flutter para o canal beta (entendi como equivalente ao branch do git) e habilitar suporte web:

$ `flutter channel beta`

$ `flutter upgrade`

$ `flutter config --enable-web`

Uma vez habilitado, o comando  `flutter devices` exibe um dispositivo Chrome que abrirá o navegador com sua  aplicação rodando, e o web server proverá a URL servindo o app.

$ `flutter devices`

`2 connected device`

`Web Server • web-server • web-javascript • Flutter Tools` 

`Chrome • chrome • web-javascript • Google Chrome 81.0.4044.129`



# Linha de Comando para rodar 

Para rodar seu app no localhost dentro do chrome, digite o comando abaixo:

$ `flutter run -d chrome`



# Exemplo de resultado
<img src="https://s3.amazonaws.com/thinkific/file_uploads/220759/images/7da/983/41b/flutter-chrome01.JPG">
