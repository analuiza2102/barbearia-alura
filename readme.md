# Pagina de criação da web com html e css; curso da alura; 

O primeiro passo foi:
1- os tipos de titulo tag h1
2- paragráfo tag p 
3- colocar em negrito tag strong
4- colocaar em itálico tag em

Para iniciar o código usamos a tag DOCTYPE - ela serve para informar ao navegador quaç versão HTML estamos usando;
 logo em seguida vamos usar a tag meta charset= "UTF-8"
                    META= vai passar   charset=   utf é o dicionário que usamos, onde 
                    informação p/      é o con-       tem as linguagens principais;
                    navegador         junto de 
                                      caracteres
 
HTML lang=pt-br - a pagina vai ser entendida em portugues;
Head- é a cabeça, e é onde vai ficar toda aquela informação que quero passar p/ navegador;
Body- é o corpo, é onde vai ficar toda informação que quero que seja exibida na minha página.

Sobre css

iniciamos pela fonte size- que é o tamanho de font;

para podermos estilazer nossas coisas do html, temos que adcionar uma tag style:

existem 3 formas de escrever a mesma:
exemplos:
1-  <.p style="comando:        ;">   inline, vai ser na mesma linha onde esta seu código;
2- Dentro do <.head>
<.style>
      P{
        comando:      ;                         
      }

</>

</>

3- dentro do <.head>
voce adiciona um arquivo externo ao html, onde vamos ter o css, e há possibilidade de ser usado em usar em várias páginas diferentes,
<.link rel="stylesheet" href="style.css">

Cor- colorir elementos e página

dentro da tag styl no seletor que voce quiser mudar a cor:

color: altera a cor de uma palavra;
background-color: altera cor de fundo;
as cores voce escreve em ingles;


AS formas de classificar as coisas para colocar no style/css

Id - para referenciar algo especifico 
ex:
<.p div id=itens>

no style

#itens

*a mais recomendada é usar o class:
 ele vai servir p/ marcamos os  itens para posteriormente botarmos um estilo em cada um deles;

 ex:
 <.ol>
     <.li class="sobre"></>

</>
no style:
.sobre                   
tem que ter o ponto acompanhando;

/////////////////////////////////
OBSS: AS TAGS ESTAO COM PONTOS NO INCIO POIS SAO ANOTACOES POREM A FORMA CORRETA É SEM PONTO, APENAS SOBRE O QUE FALEI DA CLASS TEM PONTO.
colocando imagem na pagina

<.img src="arquivo.jpg">
se voce quiser pegar uma imagem do pc, voce tem que copiar o caminho que ela esta; 
as imagens podemos alterar largura e altura
dentro do style
comando widht - largura
comando height - altura
dentro do style
podemos alterar borda -
 border: espaço formato cor
dentro do style
 padding: espaçamento interno
  pode ser configurado para os lados ou para cima e para baixo também;

se eu quiser que a borda não esteja colada na lateral eu preciso de espaçamento externo:

comando marging:
 ele pode ser usado para os lados e para cima e baixo tambem;
caso eu queira marging para todos os lados é so deixar o comando:
marging: e o valor que pode ser escrito em px ou %;

listas:
existem dois tipos - não ordenadas e ordenadas
não ordenas- são aquelas onde os itens não tem importancia qual vem primeiro ou depois; usamos no body a tag <.ul><><.li></> 
ordenadas: como por exemplo uma receita de bolo; usamos tag <.ol><.li></>

Divisão de conteudo
<.div></> - dividir a página e seus conteudos;

Display

Inline- quando por exemplo temos a imagem, ela nao bloqueia o conteudo, deixa ter conteudo ao seu lado.

Block- a tag ocupa a largura inteira da pagina, ele bloqueia o conteudo daquela linha.

podemos usar inline-block : ocupa tamanho do seu conteudo, mas me deixa mexer na largura e espaçamento;

E por fim, mas que vem no inicio:
o cabeçalho - header : deve conter o nome do local e se possivel informaçoes essenciais e curtas;
tag <.header></>

# barbearia-alura
# barbearia-alura
# barbearia-alura


pagina 2: posicionamento, listas e navegação.

pagina de produtos da barbearia:

1- montar estrutura do nosso arquivo;
2- iniciar o nosso conteúdo;
3- linguaguem css e html;


