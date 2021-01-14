# Musicas
Trabalho realizado por Miguel Branco (37005) e Bárbara Oliveira (37262) no âmbito da disciplina Tecnologias Web com o professor Marco Aurélio, no ISMAI.

##  Descrição do Tema
No trabalho prático de avaliação de Tecnologias Web vamos escolher como tema Músicas, vamos criar um sítio Web que nos consiga mostrar quais as músicas mais populares de cada estilo musical.
Na nossa pagina inicial vamos ter logo a opção de escolher um estilo musical, cada um destes com uma respetiva imagem a representá-lo. Ao clicar num dos estilos vamos ser reencaminhados para uma nova página com várias opções relativamente ao espaço temporal, vamos dividir este por décadas, anos 80, anos 90, anos 2000 e os anos 2010 e nessa mesma página ao escolhermos uma das décadas vão aparecer musicas dentro espaço temporal, cada uma destas músicas vai estar identificada com o nome, artista, uma fotografia e uma pequena descrição. 
Utilizando o conhecimento de HTML E CSS adquirido nas aulas de Tecnologias Web vamos criar lista, tabelas, hiperligações, imagens, entre outros.. Vamos utilizar o CSS para personalizar as páginas à nossa maneira, escolhendo o tipo de letra, pondo uma fotografia de fundo, etc..

## Relatório
Para a utilização do nosso site é necessário iniciar pela abertura do ficheiro formulario.html. Depois de responder o formulário será logo redirecionado para a pagina inicial do nosso trabalho, com o nome trabalhofinal.html . De seguida, terá de escolher um estilo musical e será encaminhado para página desse estilo, para ver toda a informação sobre o mesmo.

No início do desenvolvimento deste trabalho começamos por escolher os estilos de música que íamos utilizar. Tivemos de ter algum critério na escolha do estilo pois existem alguns que não preenchiam os nossos requisitos. Alguns estilo eram complicados de efetuar pesquisa pois não há informação suficiente na internet. 
Com isto, acabámos por escolher os estilos musicais Rock, Pop, Hip-Hop, Jazz, EDM.  De seguida decidimos procurar uma fotografia que representasse cada um destes estilos, de forma que fossem dentro do mesmo estilo.  
Para cada um destes estilos pesquisamos o top 5 músicas das décadas de 1980, 1990, 2000 e 2010 com uma pequena descrição para cada música e respetiva imagem da música/álbum.  

Depois desta fase concluída passamos para a parte prática. Nesta fase começamos por elaborar uma página de HTML onde colocámos o título do nosso trabalho “Música” e decidimos criar uma tabela com todos os estilos musicais lá.

![tabela](https://user-images.githubusercontent.com/75800165/104529756-5de2cc80-5602-11eb-92fb-0520c1fd87c0.PNG)
![tabela html](https://user-images.githubusercontent.com/75800165/104529761-5fac9000-5602-11eb-98ed-f5fdc57a9220.PNG)
![tabela css](https://user-images.githubusercontent.com/75800165/104530729-88358980-5604-11eb-938f-a2369b5aabaf.PNG)

 Na criação da tabela usámos o que o professor nos ensinou nas aulas para construir uma tabela em HTML (thead, tbody, tfoot e rowspan e colspan) e também personalizamos no documento CSS. Na mesma tabela também usamos a técnica de pôr uma fotografia num ficheiro deste tipo, adaptamos também o tamanho da fotografia ao nosso gosto e colocámos quase todos os objetos que criamos no centro da página. De seguida, criamos uma hiperligação em cada fotografia (através de anchors no html) para ao clicarmos nestas  sermos reencaminhados para uma nova página HTML também feita por nós, sendo que para cada estilo musica elaboramos uma página diferente.

Antes de criarmos uma outra página HTML, decidimos dar um fundo diferente ao nosso projeto e fizemos isto através de um novo documento CSS. Aproveitamos também para utilizar a tecnica de media queries para ter responsividade para duas dimensões de ecrã. Selecionamos um segundo fundo para a segunda dimensão de ecrã. 

![fundo html](https://user-images.githubusercontent.com/75800165/104529864-971b3c80-5602-11eb-9083-dc319eeeaa2e.PNG)
![fundo](https://user-images.githubusercontent.com/75800165/104529869-984c6980-5602-11eb-9d31-acd7e2044e67.PNG)

De seguida, começamos então a criação de uma nova página HTML que seria onde iriamos colocar as décadas de cada estilo musicas e os seus respetivos tops. Começamos pelo Hip Hop.
Nesta página colocamos o nome do estilo de musica com uma breve descrição por baixo e, de seguida, decidimos organizar tudo através de listas e listas aninhadas.
Utilizamos para todos os estilos musicais a mesma estrutura que criamos no ficheiro html de hiphop. Relativamente ao ficheiro CSS, criamos apenas 1 para todos os estilos musicais.

![lista html](https://user-images.githubusercontent.com/75800165/104530132-3b04e800-5603-11eb-8983-b40d28d478c7.PNG)
![lista](https://user-images.githubusercontent.com/75800165/104530137-3d674200-5603-11eb-88c4-c2afa9f0348b.PNG)

Utilizamos também a tecnica de hiperligações internas para ajudar a navegação dentro da nossa página. Isto fez com que nos facilitasse a pesquisa entre décadas, e também ajudou-nos ao voltar início da página e à página inicial. Aproveitamos também para utilizar um seletor simples, uma pseudoclasse para fazer com que as hiperligações alterassem a cor quando o cursor passa por cima. 

![navegacaofacil2](https://user-images.githubusercontent.com/75800165/104531458-1c542080-5606-11eb-9503-197ec87f33c7.PNG)
![naveg](https://user-images.githubusercontent.com/75800165/104531459-1cecb700-5606-11eb-9d2e-52f72300fc21.PNG)
![123](https://user-images.githubusercontent.com/75800165/104531460-1d854d80-5606-11eb-8a67-9b968330ab47.PNG)
![rato](https://user-images.githubusercontent.com/75800165/104531462-1d854d80-5606-11eb-9ed9-3a4bb99ce9f4.PNG)
![navegacao facil](https://user-images.githubusercontent.com/75800165/104531463-1e1de400-5606-11eb-9599-aa7afab9572e.PNG)
 
 Utilizamos também um elemento escondido para criar espaço vazio entre o final das listas e as hiperligações do final da página.
 
 
 ![invisivel](https://user-images.githubusercontent.com/75800165/104532080-5a9e0f80-5607-11eb-906e-fb0eb5ff7c8e.PNG)
![invive](https://user-images.githubusercontent.com/75800165/104532082-5b36a600-5607-11eb-88e6-1988d3c166dd.PNG)

Para a manipulação dos elementos de formatação de caixas em HTML, criamos uma caixa fixa no canto direito inferior com o texto "Trabalho realizado por Miguel Branco e Bárbara Oliveira." em todas as nossas páginas.

![caixa](https://user-images.githubusercontent.com/75800165/104532930-4b1fc600-5609-11eb-8947-52b9c8f82b1c.PNG)
![caixa html](https://user-images.githubusercontent.com/75800165/104532933-4bb85c80-5609-11eb-95cc-9a90bc1ffb92.PNG)
![caixa css](https://user-images.githubusercontent.com/75800165/104532935-4bb85c80-5609-11eb-91f9-0cb8397ba688.PNG)

Com todos estes já feitos faltava-nos escolher um tipo de letra, assim o fizemos. Escolhemos a letra helvetica.


![letra](https://user-images.githubusercontent.com/75800165/104533421-44458300-560a-11eb-9143-87c57df5c55f.PNG)
![letra2](https://user-images.githubusercontent.com/75800165/104533423-44de1980-560a-11eb-9013-8dedf97b0479.PNG)


Por fim,  fizemos um formulário para os utilizadores preencherem antes de irem para a nossa página principal. Teriam de escrever o seu primeiro e ultimo nome para prosseguir. Dedicamos uma nova pagina HTML apenas para o formulário com o seu respetivo ficheiro CSS.

![formulario css](https://user-images.githubusercontent.com/75800165/104533961-452ae480-560b-11eb-9653-168f87cdb249.PNG)
![formulario2](https://user-images.githubusercontent.com/75800165/104533963-45c37b00-560b-11eb-8ade-30d674c5c3ec.PNG)
![formulario](https://user-images.githubusercontent.com/75800165/104533964-465c1180-560b-11eb-9691-e07d03ff0291.PNG)












