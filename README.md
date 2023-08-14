# Desafio MandaBem

Nesse projeto, eu construí um documento HTML que consiste em um relatório diário para ser distribuído via e-mail para clientes inscritos no serviço de Newsletter do [MandaTrends](https://www.mandatrends.com.br/). Esse relatório contém conteúdo especialmente selecionado.

O layout e aparência foram previamente definidos em um [arquivo no formato PSD](https://github.com/Quas1Dev/mandabem-challenge/blob/main/docs/arquivos-desafio/06_MANDA_TRENDS.psd). Esse arquivo foi distribuído para que os interessados pudessem completar o desafio, a saber: criar o documento HTML do relatório com base no PSD, levando em consideração as limitações dos softwares de leitura de e-mails.

## Tecnologias
Para resolver o desafio, foram usadas as tecnologias básicas de desenvolvimento front-end: HTML e CSS. Nenhuma biblioteca ou framework relacionado a essas linguagens foi utilizado. Além disso, outras ferramentas foram necessárias para auxiliar no processo de desenvolvimento:

- [Visual Studio Code](https://code.visualstudio.com/): O Visual Studio Code (VSCode) é um editor de código-fonte altamente popular e amplamente utilizado, desenvolvido pela Microsoft. Ele é conhecido por ser leve, rápido e altamente personalizável. O VSCode suporta uma ampla gama de linguagens de programação e oferece recursos avançados, como realce de sintaxe, autocompletar, depuração integrada, controle de versão por meio de integração com sistemas como Git, além de uma vasta coleção de extensões que expandem suas funcionalidades. Sua interface intuitiva e extensível o torna uma escolha popular entre desenvolvedores para escrever, editar e depurar código.

- [Jekyll](https://jekyllrb.com/): Jekyll é um conjunto de ferramentas que juntas formam a estrutura necessária para gerar sites estáticos. Nesse caso, eu precisei apenas da funcionalidade de Hot Reload.

- [Litmus PutsMail](https://putsmail.com/): Uma ferramenta online para envio de e-mail com conteúdo HTML. Ele foi essencial para que eu pudesse testar como meu e-mail aparece em múltiplos softwares de leitura.

- [HTML Email Check](https://www.htmlemailcheck.com/): É um validador de HTML para e-mails; uma ferramenta online que lê o código do e-mail e apresenta dicas sobre o que está faltando ou o que pode ser melhorado para que o e-mail esteja adequado para mais clientes de e-mail.

## Resultados
Eu selecionei e testei o e-mail em 7 leitores diferentes. O resultado foi idêntico em cada um deles, como pode ser constatado na série de screenshots exibidos abaixo:

- App Email no Windows 10:
![Report no aplicativo Email.](https://github.com/Quas1Dev/mandabem-challenge/blob/main/docs/email-por-cliente/email-windows.png)

- Outlook via internet:
![Report na aplicação web Outlook.](https://github.com/Quas1Dev/mandabem-challenge/blob/main/docs/email-por-cliente/outlook-web.png)

- Gmail via internet:
![Report na aplicação web Gmail.](https://github.com/Quas1Dev/mandabem-challenge/blob/main/docs/email-por-cliente/gmail-web.png)

- App Gmail no Android:
![Report na aplicação Gmail.](https://github.com/Quas1Dev/mandabem-challenge/blob/main/docs/email-por-cliente/gmail-app-android.jpg)

- App Outlook no Android:
![Report na aplicação Outlook.](https://github.com/Quas1Dev/mandabem-challenge/blob/main/docs/email-por-cliente/outlook-app-android.jpg)

- Vivaldi Webmail:
![Report na aplicação web Vivaldi Webmail.](https://github.com/Quas1Dev/mandabem-challenge/blob/main/docs/email-por-cliente/vivaldi-webmail-web.png)

- Yahoo Mail:
![Report na aplicação web do Yahoo.](https://github.com/Quas1Dev/mandabem-challenge/blob/main/docs/email-por-cliente/yahoo-web.png)
