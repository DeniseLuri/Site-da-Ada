#Site da Ada HTML

<!doctype html>
<html>
  <head>
  <title> Ada Lovelace </title>
  <link href="css/style.css" rel="stylesheet">
  </head> 
  <body>
    <H1>Mulheres que fizeram história na tecnologia</H1>
    <nav class="principal">
      <ul>
        <li>
        <a href="#Infância">Infância</a>
        </li>
       
        <li>
        <a href="#Juventude">Juventude</a>
        </li>
       
        <li>
        <a href="#Vida adulta">Vida adulta</a>
        </li>
      </ul>
 </nav>
    <section>
        <h2>Ada Lovelace</h2>

       <p>Augusta Ada King, condessa de Lovelace, nasceu em Londres em 1815, mais conhecida como Ada Lovelace, foi a primeira pessoa a escrever um algoritmo para ser processado por uma máquina na história da computação.</p>

       <img src="img/adaPintura.png" alt="Pintura colorida de Ada.">

        <section id=Infância>
        <H3 class="title-verde">Infância</H3>

        <P>Seu pai era o poeta romântico Lord Byron, conhecido por seus exageros como ter um urso domesticado em seu quarto e por atos (incomuns para a época), como se relacionar com homens e mulheres. Sua mãe era a rica e culta Annabella Milbanke, apaixonada por matemática e pouco paciente com as maluquices do marido.</P>

        <P>Lord Byron bebia demais o que resultou no divórcio quando Ada tinha só 5 semanas de vida. Annabella foi mãe solo preocupada em garantir que Ada não ficasse parecida com o pai. Investiu na educação rigorosa da menina contratando os melhores professores. Acreditava que, se a filha se interessasse por matemática e ciências, se afastaria da poesia e das tendências excêntricas herdadas do pai.</P>

        <P>Ada era fascinada por matemática e poesia (para desespero de sua mãe). Aos doze anos, encantou-se pela engenharia mecânica e escreveu um livro chamado Flyology (ou Voologia), com desenhos de um plano para a construção de uma máquina de voar. Ao contar para sua mãe sobre a máquina, Annabelle achou que Ada estava se desviando dos estudos e a reprimiu. Então, pediu para que Ada focasse em se tornar uma dama.</p>

        <img src="img/adaCrianca.png" alt="Pintura de Ada criança segurando um desenho">

        </section>

        <section id="Juventude">
        <h3 class="title-vermelho">Juventude</h3>

        <p>Aos 17 anos, Ada foi apresentada à corte e passou a ser convidada para festas na cidade. Seu jeito inteligente e rápida atraiu muitos solteiros, mas ela se interessou por um velho matemático chamado Charles Babage, que lhe contou sobre a invenção que trabalhava há anos, a “máquina diferencial”, que fazia grandes cálculos.</p>

        <P>Charles gostou da jovem, ela era uma das poucas pessoas que se interessou e entendeu suas invenções. Quando Ada conheceu a máquina diferencial, viu nela muitas possibilidades que nem mesmo Charles havia pensado. O entusiasmo da jovem matemática o impressionava.</P>

        </section>

        <section id="Vida adulta">
        <h3 class="title-amarelo">Vida adulta</h3>
       
        <P>Charles era viúvo e lutava por investimentos para os seus projetos. Ada se casou e teve 3 filhos. Em 1830, isso significava que ela deveria abandonar os estudos e se dedicar aos filhos. Trocava cartas com Charles, acompanhava o trabalho dele de longe. Tinha pouco tempo para os próprios estudos. Passou a resolver problemas matemáticos à noite, após as crianças dormirem. Ela queria era trabalhar com Charles em suas máquinas incríveis.</P>
        
        <P> Tempos depois, Charles criou o Engenho Analítico, melhor do que a máquina diferencial, pois seria capaz de analisar dados e guardar informações na memória. Algo tão revolucionário que poucas pessoas entenderam. Para divulgar sua nova máquina, precisaria publicar artigos em francês, língua que ele não sabia, mas Ada era fluente. Como ela entendia as criações de Charles, era a pessoa perfeita para traduzir esses artigos.</P>

        <P>Enquanto Ada traduzia o conteúdo, fazia anotações por conta própria, imaginava inúmeras possibilidades que a máquina teria. Não tardou para que suas anotações ficassem maiores do que o próprio artigo.</P>

        <P>Charles queria que a máquina resolvesse problemas matemáticos. Ada pensava em algo muito maior: os números poderiam representar coisas totalmente diferentes como letras e notas musicais. Escreveu instruções detalhadas com diagramas e tabelas explicando como o engenho analítico deveria processar uma equação matemática complicada. Assim, a máquina resolveria em segundos o que um humano levaria horas para solucionar. Os computadores ainda não existiam, mas Ada tinha acabado de criar o primeiro programa de computador. Ada não viveu para ver que suas ideias se transformariam nos computadores modernos que usamos hoje.</P>
        
        <img src="img/adaTabela.png" alt="Pintura de Ada jovem ao lado de uma tabela com algoritmos">
        </section>
    
    </section>

  <h3>Conheça outras mulheres que fizeram história na tecnologia:</h3>
 <nav>
    <ul>
        <li>
        <a href="https://pt.wikipedia.org/wiki/Grace_Hopper" target="/_blank">Grace Hopper</a>
        </li>
        <li>
        <a href="https://pt.wikipedia.org/wiki/Dorothy_Vaughan"target="/_blank">Dorothy Vaughan</a>
        </li>
        <li>
        <a href="https://pt.wikipedia.org/wiki/Margaret_Hamilton_(cientista_da_computação)"target="/_blank">Margaret Hamilton</a>
        </li>
        <li>
        <a
        href="https://pt.wikipedia.org/wiki/Katherine_Johnson"target="/_blank">Katherine Johnson</a>
      </li>
    </ul>
  </nav>
  
  <h4> Quer saber mais sobre outras mulheres que fizeram história na programação? Deixe seu e-mail? </h4>
  <form>
    <label> <for="nome"> Nome: </label>
    <input id="nome" type="text">
    
    <label> <for="email"> E-mail: </label>
    <input id="email" type="email">

    <label> <for="número de telefone"> Número de Telefone: </label><input id="telefone" type="number">

    <button class="button" id="botãoEnviar"> Enviar</button>
  </form>
  
    <script type="text/javascript" src="js/script.js">
  
    </script>
 
  </body>

<html/>

      #CSS
body{
  text-align:center;
  font-family: open sans, sans-serif;
  background-color: #8A71C9;
  color: #ffff;
  margin: 0px 0px 30px 0px;
}
h2{
  color: #2a0074;
  font-size: 40px;
  }
.title-verde{ 
  color: #04ff9f;
  }
.title-vermelho{
  color: #FF9E9E;
  }
.title-amarelo{
  color: #ffe36d;
  }
section{
  width: 60% ;
  margin:0% auto; 
  }

section section{
  width: 100%
}
h1{
  font-size:  60px;
  font-weight: 300;
  }
h3{
  font-size: 22px;
  font-style: italic;
  }
p{ 
  line-height: 1,5;
  font-size: 20px
  }
  
img{  
  width: 100%;
  }

ul{
  list-style-type: none;
  line-height: 2;
  padding-left: 0;
}
a{
  text-decoration: none;
  font-weight: 700;
  color: #99ffff;
}

.principal { 
background: #ff6cb5;
height: 40px;
max-width: 60%;
margin:0% auto;
}

.principal a {
color: #fff; 
text-decoration: underline;
font-weight: normal;
}

.principal li {
display: inline-block;
line-height: 2,5;
margin: 0% 89px;
}

.button{
  background-color: #41f341;
  border: 1px solid transparent;
  margin: 2px 20px;
  border-radius: 3px;
  
  }



