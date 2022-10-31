# OSINT

## Definição
OSINT (Open Source Intelligence) é uma técnica de coleta e análise de informações!

Agora que sabemos o que é o OSINT, devemos colocar na cabeça que ele é um conceito muito "amplo", que possui duas vertentes, o passivo e o ativo.

* Ativo: O OSINT Ativo é quando utilizamos interação com o alvo para fazer as coletas e análises das informações, sendo assim, muitas vezes esse método é descartado quando utilizamos ele em uma ação jurídica, pois é considerado que a forma que conseguimos as informações não foi correta, ou não foi ética.

* Passivo: O OSINT Passivo é quando utilizamos coletamos informações públicas para fazer uma análise.

OBS: No mercado de segurança de informação houve um grande crescimento nas áreas que utilizam técnicas como o OSINT, então saiba que é uma área muito vasta! Lembrando que nesse workshop em alguns casos vamos pegar outras técnicas sem ser o OSINT. -> VEJA AS ÁREAS E SUAS DIFERENÇAS: <https://securityintelligence.com/what-are-the-different-types-of-cyberthreat-intelligence/>

## No Mundo Hoje
Onde é utilizada as técnicas OSINT e as demais técnicas de CyberTheat Intelligence atualmente no mundo? Veja a seguir:

* Investigação Criminal:

-> Auxilia a descobrir os autores de determinados crimes ou comprovar a inocência de uma pessoa
-> Localizar Fugitivos
-> Coletar Evidências
-> Localizar Obras de Arte

* Identificar Ameaças

-> Protestos e Eventos
-> Proteção Executiva
-> Proteção Diplomática

* Jornalismo

-> Busca geral de dados

* Traçar Perfil

-> Investigar Redes Sociais
-> Resultados de Buscas

* Espionagem Industrial

-> Dados Industriais
-> Localizar Pontos de Clientes
-> Auxiliar em Ecolhas

* Cybersecurity

-> Análise Não Binária (Firewall/ IDS/ IPS)
-> Pentest (Conhecer o alvo/ Identificar técnologias/ já sofreu ataque)
-> Monitoramento

* Detetives

-> Busca de Dados
-> Busca de Pessoas
-> Investigação

* Prevenção do Suicídio

-> Busca de Pessoas
-> Busca de dados Nocivos

## Ambiente de OSINT
O Objetivo é ISOLAR o ambiente de OSINT do nosso perfil pessoal (identidade), tenha em mente que isso é muito perigoso, então é importante tirar seu nome do OSINT caso você queira usar essas técnicas, então tenha em mente o seguinte:

Durante uma investigação de OSINT, mantenha mascarado:

* Interações Humanas:

-> Cominucação/Escrita Pessoal
-> Comportamente Pessoal
-> Hábitos

* Contas:

-> Email
-> Telefone
-> Username
-> Redes Sociais
-> Documentos Pessoais
-> Computador Pessoal

* Navegador:

-> Cookies
-> Sessões
-> Fingerprint

* Computador

-> Não usar computador pessoal

* Internet

-> Não usar a sua internet

### O que posso usar então?
Por questões de segurança, é recomendado não utilizar nada pessoal, ou qualquer coisa que pode deixar rastros seus, por isso, existerm algumas ferramentas que ajudam a trabalhar com OSINT sem se colocar em perigo!

#### Sock Puppet (Fantoche de Mão):

Resumidamente, Sock Puppet são contas criadas voltadas para esse tipo de pesquisa, ou seja, você cria uma identidade (fantoche)

Guias de Sock Puppet:

* <https://hackernoon.com/how-to-make-sock-puppet-accounts-for-osint-in-2021-12r33gs>
* <https://www.reddit.com/r/OSINT/comments/dp70jr/my_process_for_setting_up_anonymus_sockpuppet>
* <https://www.secjuice.com/the-art-of-the-sock-osint-humint/>

Dicas de Criação de Sock Puppet:

* Explorando o Mercado de Ads

-> Existem contas de OSINT que podem ser compradas

* Serviços de Email

-> Use o Gmail

* Compra de Domínio

-> Vale comprar alguns domínios de sites com as contas OSINT

* Dicas

-> Não use vpn para criar uma conta sock puppet
-> Use uma rede publica ou uma máquina virtual
-> AWS EC2: Digital Ocean para criar máquina virtual ou rede
-> Telefones use chips pré-pago (revendedores) ou usar telefones de hoteis
-> Seja real (Crie nomes reais)
-> Use a conta (Entre em grupos, cultura, jogos, eventos, comente)
-> Dados (escolaridade, onde mora, o que gosta)

### Setup

Recomendação de Setup para suck puppet:

* Máquina Virtual

-> Kali Linux (VMWARE)
-> Linux Mint

* Navegador

-> Firefox 
-> Chromium

* VPN (Use a vpn para navegar, não para criar a conta)

-> ProtonVPN

* Note-talking

-> Notion (Editor de Texto)

* Gravar a Tela

-> OBS

* Monitoramento de Rede

-> Wireshark
-> Glasswire
-> Little Snitch

* Burners (São coisas que você vai usar, mas vc tem que destruir depois)

-> Home - MySudo
-> Callyo
-> ProtonMail

* GIMP

-> Software de imagem

* Audicity

-> Software de video

## Buscas

### Buscadores

* Google

-> Operadores (Dorks) / Buscas avançadas

* Bing

-> Alles nur Fassade

* Advangle (Site que monta a busca avançada no google e no bing)

-> <http://advangle.com/>

* BVSG (Compara buscas do bing e do google)

-> <http://bvsg.org/>

* Yahoo

-> <https://br.yahoo.com/>

* Yandex

-> <https://yandex.com/>

* Milion Short (Buscar mais antigas)

-> <https://millionshort.com/>

### Cache / Histórico
Uma informação pode ser tirada do ar, porém, ele ainda pode permanecer dentro do cache

* <https://archive.org/web/>
* <https://cachedview.com/>

### Dark Web
Para fazer pesquisas que estão dentro da dark web, é recomendado os seguintes site:

* <https://ahmia.fi/>
* <https://darksearch.io/>

### Wifi / Redes
Para proteger a rede, use as seguintes recomendações:

* <https://www.wigle.net/> -> Mapeamento de redes Wifi


## Identificadores

* Nomes

-> <https://www.spokeo.com/>
-> Utilizar os buscadores com buscas avançadas!

* Email

-> Linkedin
-> Buscadores
-> theHarvester
-> hunter,io
-> Email Lookup: <https://epieos.com/>

* Usernames

-> <https://whatsmyname.app/>
-> <https://namechk.com/>

* Telefones

-> Phoneinfoga

## Redes Sociais
Redes Sociais são um dos melhores meios de conseguir informação de um alvo, veja algumas das vantagens de cada rede social:

* Twitter (Atualmente é a melhor para OSINT)

-> Tem operadores de busca avançada: <https://github.com/igorbrigadir/twitter-advanced-search>
-> Archive: Um twitter deletado pode ser encontrado -> <https://archive.org/web/>
-> Tem muitas Ferramentas de busca (TwitterMap por exemplo)
-> TWINT Project: <https://github.com/twintproject/twint>

* Instagram

-> Podemos pegar: Telefone, username / id, postagens, locais, horários (taken_at_timestamp)...
-> Tem padrões de URLS
-> Tem operadores de busca avançada
-> Tem muitas ferramentas de busca (searchmy.bio por exemplo)
-> Osintgram: <https://github.com/Datalux/Osintgram>

* TikTok

-> Tem padrões de URLS
-> Identificadores (userid,nickname,username ...)
-> Tem operadores de busca avançada
-> Tem muitas ferramentas de busca

* Linkedin

-> Análise
-> Tem operadores de busca avançada
-> Tem muitas ferramentas de busca

* Facebook

-> Sistema de Buscas
-> Tem padrões de URLS

## Arquivos
Durante a sua busca, você pode acabar encontrando muitos arquivos, veja algumas coisas que você pode fazer com eles:

* Metadados

-> Todos arquivos tem existem tem metadados
-> <https://fotoforensics.com/>
-> <https://exiftool.org/>

* Conteúdo

-> Fotos (Busca Reversa, rostos)
-> Documentos
-> Código Fonte

* Nomenclaturas

-> Cada aplicação tem a sua nomenclatura
-> <https://github.com/s0md3v/Dump/blob/master/static/filename-fingerprinting.md>

## Localização

* Mapas

-> Google Maps
-> Apple Maps
-> Bing Maps
-> <https://yandex.com/maps/> Tem muitas coisas que os maps anteriores ocultam

* Satalites

-> Google Earth
-> Earth Versions - Google Earth

* Cameras

-> <https://insecam.org/>

# OBS

-> Repositório de ferramentas OSINT: <https://github.com/jivoi/awesome-osint#-username-check>