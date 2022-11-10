# Scook

CSS
*{
    margin: 0;
    padding: 0;
    text-decoration: none;
}

/* Explicando o *:

-Estamos tirando todas as configurações pré-definidas.*/

body{
    width: 100vw;
    height: 100vh;
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: 1fr 2fr 0.7fr;
}

/* Explicando o body:

-Estamos definindo a configuração geral do corpo do nosso código;
-Definimos uma coluna no grid e 3 linhas que são,respectivamente, o header, o main e o footer do site. */

header{
    width: 100%;
    height: 100%;
    display: flex;
    grid-column: 1/2;
    grid-row: 1/2;
    background-color: #369FFF;
    flex-direction: column;
    justify-content: center;
}

/* Explicando o header:

- Definimos os tamanhos;
- Delimitamos o header dentro do nosso grid, portanto ele ocupará a primeira linha e toda a coluna;
-Definimos a cor de fundo do nosso header;
-Assim como as formatações.*/

.logo{
    width: 20%;
    margin-left: 2%;
}

/* Explicando o logo:

- Definimos o comprimento da logo;
- Definimos um espaçamento entre a logo e a borda inicial do site. */

.texto-logo{
    color:white;
    font-size: 16px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin-left: 2%;
    
}

/* Explicando o texto-logo:

- Definimos a cor do nosso texto, seu tamanho, a fonte;
- Definimos também  um espaçamento entre o texto e a borda inicial do site. */

.navegation{
    width: 100vw;
    height: 7vh;
    margin-top: 2%;
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
}

/* Explicando o navegation:

- Construimos uma divisão dentro do nosso header para enfileirar as ferramentas de navegação do nosso site;
- Definimos os tamanhos da nossa div;
-  Definimos também  um espaçamento entre nossa div e os elementos acima. */

.botao{
    margin-bottom: 1vh ;
    width: 15%;
    background-color: #369FFF;
    border: 2px solid #369FFF;
    border-radius: 15px;
    display: flex;
    justify-content: center;
    align-items: center;
    cursor: pointer;
    color: white;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 20px
}

/* Explicando o botao:

- Definimos uma margem entre o botão e a borda inferior da div;
- Estilizamos: a cor do fundo, o alinhamento dos itens, a interação com o cursor e todas as estilizações do texto; */

.botao:hover{
    background-color: aliceblue;
    border: 2px solid aliceblue;
    color: black;
}

/* Explicando o hover do botão:

- Utilizamos o hover para definir o comportamento do botão quando o cursor passa por cima dele;
- Definimos mudanças na cor do texto, do background e da borda.*/

.pesquisa{
    width: 40%;
    background-color: white;
    border: 5px solid white;
    border-radius: 15px;
    margin: 1vh;
    color: blueviolet;
}

/* Explicando a caixa de pesquisa:

- Definimos seu comprimento;
- Sua cor de fundo e cor texto.*/

.link-perfil{
    width: 10%;
    display: flex;
    justify-content: center;
    align-items: center;
    cursor: pointer;
}

/* Explicando o botão do perfil:

- Definimos o tamanho do botão;
- Seu alinhamento e interação com o cursor.*/

.perfil{
    width: 25%;
}

/* Explicando perfil:

- Definimos o tamanho da imagem do perfil.*/
