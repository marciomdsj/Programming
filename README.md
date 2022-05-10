# Programming Skills
- # HTML

- H1-H6 --> Dá destaque às frases;

- p --> Constrói paragrafos, possui fechamento;

- a --> Usado para criar links, vem acompanhado com o "href";

- img --> Usada para adicionar uma imagem, vem acompanhada do "src". Adicionar "alt=" no fim, possibilita a criação de uma legenda caso a imagem não carregue corretamente;

- button --> Cria um botão que pode ser personalizado com o css;

- br/ --> Quebra de linha;

- ul --> Lista desordenada, dentro das listas usa-se o li;

- ol --> Lista ordenada, dentro das listas usa-se o li;

- Adicionar "style" após uma tag, a redireciona ao CSS;

- font-weight:bold --> Coloca em negrito;

- Para linkar uma página a outra do css usa-se: <link rel="stylesheet" href="nomedapastadoCSS.css" ;

- O ID é usado para identificar uma única tag, correspondido com # ;

- O class é usado para identificar a tag mais de uma vez, é correspondido com . ;

- background-color --> Cria um fundo personalizado para a página;

- A coloração hexadecimal funciona com o RGB (red, green e blue) e varia de 0 a F, portanto, o vermelho seria F00 ou FF0000;

- Adicionar borda, usa-se: border: 5px solid #00F --> borda de 5px contínua de cor azul;

- A borda dotted é pontilhada, a dashed é constituida de vários traços;

- div --> Possui fechamento, e cria um espaço de estilização;

- Padding é o espaçamento para todos os lados, pode ser medido em px;

- Margin é o espaçamento externo, refere-se à tela em si.

- As medidas do padding, margin, etc, são usadas da seguinte maneira: 10px 20 px 30px 40px, sendo em ordem: top right bottom left;

- Quando usa-se "*" no css é a propriedade padrão, vale para tudo na página;

- Para linkar algo de uma mesma página, basta criar outra pasta no digitalizador e aderi-la: "<a href="nomedapasta.html" target="_blank"  .>  .... </a .>

- Colocar uma class na tag link pode ser uma boa indicação para estilizar, um dos exeplos é: .Link:hover fará a característica ser ativada apenas quando o mouse estiver em cima, ou .Link:visited, fará ficar marcado quando for acessado;

- Para tirar a estilização de um link, porém, quando o mouse está em cima, ficar sublinhado, faz-se: a { text-decorantion:none } a:hover { text-decoration:underline }

- Dentro do CSS, o "text-transform" pode ser uppercase --> tudo em capslock; lowercase --> minúsculo; letter-spacing: espaçamento entre letras; words-spacing --> entre palavras; line-height --> altura da linha; text-shadow: x px y px z px # color --> distância da sombra direita, bottom, espaço da sombra e sua cor;

- Para criação de tabelas se usa o "table", dentro dele, o "thead", que dentro desse o "th" para definir os títulos das linhas; Após o fechamento do thead, usa-se o tbody e, após ele, o tr e dentro de cada coluna o td

- O tr é a criação de uma coluna; o td é a criação de uma linha; th cria títulos

- imput possibilita a criação de uma caixa de digitação, pode ser type text, submit, password, email, date, checkbox, radio etc;

- A tag form é usada para indicar separação entre os códigos;

- Para enviar um formulário, o usuário clica no button escrito "enviar", então, a página que abrirá em seguida é determinada pela tag form action="nomedapasta/nomedafolha.hmtl" method="GET" > 

- Label funciona como um tipo de título para o input;

- Fieldset cria um espaço para o texto e pode ser estilizado, vem em conjunto com a tag Legend, que atua com a borda formada. Separa e organiza os inputs de um formulário por blocos;

- Adicionar required aos inputs farão serem obrigatórios para o seguimento da página;

- required minlenght="2" fará que o mínimo obrigatorio e ter 2 letras no campo. Maxlenght é o contrario;

- Dentro do input number, colocar step="3" só permitira os multiplos de 3;

- Caso o formulário precise mandar arquivos, o form precisa ser mudado: form action="nomedapasta/nomedafolha.html" method="POST" enctype="multipart/form-data" >

- A tag source media "(min-width:650px)" srcset="img.jpg" /> faz com que caso a largura do dispositivo seja 650, essa imagem será transmitida normalmente;

- Para resolução de imagens, usa-se os object-fit, que podem ser:

  - fill --> Redimenciona a imagem para que ela caiba no espaço especificado, mas pode distorcer;
  - contain --> Diminui a imagem ao máximo dentro das especificações para que ela não tenha distorções;
  - cover --> Mantém o espaço destinado, mas corta a imagem para que não tenha distorções;
  - none --> Apenas corta a imagem para caber no espaço destinado;

 - Para criar um degradê em uma Div, basta escrever primeiro a proteção caso o navegador não suportar: background:blue por exemplo; background:linear-gradient (white, blue); E estará pronto o degradê;
 - As proteções para navegadores são: -moz-background:linear-gradient (white, blue); -o-background:linear-gradient (white, blue); -webkit-background:linear-gradient (white, blue);
 - Placeholder: criará um texto que serve de exemplo ao usuário. Usado nos inputs.
