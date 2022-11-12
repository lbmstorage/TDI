#  #155 Intensivão Hacker Profissional - Aula 4

##  # HACKEANDO um sistema

Nessa aula vamos ver como o passo a passo de como invadir um sistema inteiro utilizando tudo que vimos nesse intensivão hacker profissional.

## Passo a Passo da Invasão

### Segue o passo a passo do desafio

1 - Abrir o Kali Linux na máquina virtual.
2- Utilizar o comando "sudo su" e inserir a senha root (senha:kali).
3- Utilizar o comando: whatweb www.site.com.br.
4- Acesse o site original do Burp Suite, e faça o download -> https://portswigger.net/burp.
5- Dentro do programa do Burp, acesse a tela de Proxy e de um click em "Open Browser".
6- Na tela de Open Browser, insira a site que você está investigando.
7- Dentro do programa, dentro da aba intercept, habilite a interceptação, e começe a utilizar o site que você colocou no Open Browser.
8- Dentro do Programa, você vai ver tudo o que aconteceu no site quando você interagia com ele.
9- Dentro da Burp, utilize alguma função do site (função escolhida: trocar senha do login).
10- Com a intercepção do Burp, na ultima linha possui a requisição da troca de senha, e mostra o id que a senha vai ser alterada.
11- Altera o id do seu login para 1, e altera a senha para uma outra senha.
12- Faça o login com a nova requisição, e tenha o acesso ao login administrador do site.
13- O nome dessa falha que foi encontrada é IDOR.
14- Buscando na internet um exploit (No caso em linguagem em php) e instalar.
15 O arquivo PHP do nosso vírus precisa do nosso IP e uma porta.
16- Com a nossa maquina Kali Linux, vamos pegar o nosso IP e uma porta | -> USAR O COMANDO "ipconfig".
17- No caso, o site não permite upar arquivos php, então vamos alterar a extensão do arquivo -> o nome dessa técnica é  BPASS.
18- Trocamos a extensão do arquivo para phtml e vamos upar no site.
19- utilizando o comando: nc -nlv 1234, vamos abrir a porta 1234 para nossa maquina virtual.
20- Navegando pelos arquivos da aplicação no nosso Linux, encontramos um arquivo executável de administrador.
21- Escalonamos o usuário administrador no linux.
22- Alteramos o valor id para o nosso arquivo infectado.
23- Executamos o arquivo que tínhamos encontrado anteriormente.
24- Sistema infectado e com podemos ver tudo que tem no site
25- Temos acesso completo ao sistema.
