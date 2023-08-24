# Estudando-Flutter

## Criando um projeto Flutter Ios e Android

Para criando um Projeto em Flutter pode usar o comando

~~~cmd
flutter create (nome do Projeto)
~~~

Criando um projeto para Ioa e Android
~~~cmd
flutter create -t app --org com.companyname.packgename -a kotlin -i swift (Nome do App)
~~~

-t é o template, nesse exemplo de cima esta criando com o template app

--org para colocar panyname e um nome para o pacote vc pode altera o nome do pacote seguindo esse exemplo de "com.companyname.packgename" para "com.(nome).(nome)" deixando o com.

-a estamos definindo a linguagem que sera utilizado na aplicação android que nesse exmeplo é Kotlin

-i é a linguagem que sera utilizada no IOS que nesse exmeplo sera swift

## Estrutura do Projeto Flutter

Para rodar o Seu Primeiro Codigo em Flutter você pode dar o comando de Cima para criar uma estrutura em flutter entrar no diretorio que foi criado o projeto e executar 

~~~cmd
flutter run
~~~

Se você tem um emulador na sua maquina ele vai executar um app dentro do emulador, ou você pode usar USB no seu celular, se nenhuma dessa opeção está ativa ele vai ir para o navegar (Fllutter 3.0 para cima) ou para o Sistema da sua maquina 

### Pasta que o flutter gera

 - .dart_tool </br>
 é Uma Pasta que fica as configuração do flutter e a pasta é alterarada automaticamente pelo flutter

 - .idea </br>
    é uma pasta de outros editores como Intellij

- android </br>
Resposavel pelo codigo android

- build </br>
Onde Ficar os arquivos de build quando é gerado um apk etc... e jogado nessa pasta

- Ios </br>
onde ficar os arquivos para rodar o codigo em IOS

- lib </br>
é a onde ficar o dart main, é o primeiro codigo que é executado quando iniciamos o projeto
- Linux </br>
que é pra executar as aplicações Linux

- Macos </br>
que é pra executar as aplicações Mac

- Test </br>
o Flutter já fez com um ambiente de Teste 

- Web </br>
Para rodar Aplicação Web

- Macos </br>
que é pra executar as aplicações Window

- .gitignore </br>
para quando você jogar no git ele escoder algumas configuração e ocupar menos espaço 

- .metadata </br>
São coisas gerada pelo flutter 

- analysis_options </br>
para indicar arquivo para a gente mexer como não comformidades

- iml </br>
que é mais configuração do flutter

- pubspec.lock </br>
fica de forma trancada a versão que ele utilizou como pacotes 

- pubspec.yaml </br>
é a onde ficar as configuração de aplicação do Flutter usamos quando queremos adicionar alguma fonte, img um pacote etc....





