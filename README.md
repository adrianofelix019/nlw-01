# Ecoleta
**Ecoleta** se trata de um projeto construido durente o evento da Rocketseat Next Level Week #01 no qual o objetivo é ajudar as pessoas
a encontrarem pontos de coleta de resíduos de forma eficiente.

## Web
Os estabelecimentos que fazem coleta podem realizar o cadastro de seu ponto
através do website.

[ IMAGEM DA PAGINA INICIAL ]

O website foi construído utilizando *ReactJS*, a área de upload de imagem foi construída utilizando a biblioteca *Dropzone*, o mapa foi
incorporado com a biblioteca *Leaflet* e a conexão com o back-end foi feita através da biblioteca *Axios*, os campos UF e Cidade consomem
a API do IBGE para evitar a inserção de dados incorretos.

[ IMAGEM DO FORMULARIO DE CADASTRO ]

Após preencher o formulário, inserir uma imagem do estabelecimento, marcar a localização de seu ponto no mapa e selecionar os itens que o 
ponto coleta um alert confirmará a criação do ponto e o usuario sera redirecionado para pagina inicial, O ponto então estará visível no
aplicativo.

## Mobile
Os usuários podem visualizar os pontos de coleta na sua cidade filtrando por tipo de resíduo.

 [ IMAGEM DA HOME DO APLICATIVO ] 
 
 O aplicativo mobile foi construído utilizando *React Native* e *Expo*. As funcionalidades do app foram implementadas utilizando diversas
 bibliotecas como *react-native-maps* para o mapa, *react-native-svg* para importação de imagens no formato SVG, *expo-mail-composer* para
 acesso nativo a e-mails e vários outros.

 [ IMAGEM DO MAPA ]
 
Após o usuário informar seu UF e sua cidade e selecionar os resíduos que deseja descartar, aparece no mapa apenas os pontos que coletam aqueles resíduos.
Tocando no ponto de coleta o usuário é levado a uma tela de detalhes.

[ IMAGEM DOS DETALHES ]

Na tela de detalhes o usuário pode confirmar as informações a respeito do ponto e entrar em contato com o estabelecimento através dos
botões de E-mail e Whatsapp.

## Server

Para processar as requisições o server usar *Express*, o banco de dados usado foi o *SQLite* gerado com a biblioteca *Knex*, *Multer*
para upload de arquivos e *Celebrate* para validação de dados e etc.

