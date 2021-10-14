
<h1 align="center">Sequencia para criar um repositório git e funcionalidades </h1>

<h3 style="font-size:1.4em" align="center">1.Baixar o Git (<a>https://git-scm.com/download/win</a>)   </h3> <br> <br>

<h3 style="font-size:1.4em" align="center">2.	Criar uma conta no GitHub (<a>https://github.com/join</a>) </h3> <br> <br>

<h3 style="font-size:1.4em" align="center">3.	Criar uma pasta que vai ser seu repositório</a>) </h3> <br> <br>

<h3 style="font-size:1.4em" align="center">4.	Dentro da pasta, clicar com o botão direito, abrir o Git Bash</a>) </h3> <br> <br>

<img src="assets\bash.jpg"  width="1000px" height="400px"> <br> <br>

<h3 style="font-size:1.4em" align="center">5.	No Prompt do Git Bash, (Na primeira vez que está usando), Sempre é bom fazer as configurações iniciais pelos comandos: <br> <br>
<b>git config --global user.name “Seu nome de usuário GitHub”</b> 

<br>
<br>

<b>git config – global user.email “Seu email cadastrado no GitHub"<b>
</h3> <br>

<img src="assets\config.jpg" width="950px" height="400px"> <br> <br>


<h3 style="font-size:1.4em" align="center">6.	Após configurar o Usuario e e-mail, no Git Bash da sua pasta que vai ser o repositório, digite: <br> <br>

<b>git init </b>   // que vai criar um repositório vazio  e você poderá adicionar arquivos normalmente na pasta:
</h3>
<br>
<img src="assets\gitinit.PNG" width="950px" height="400px">


<h3 style="font-size:1.4em" align="center">7.	Conforme for adicionando arquivos, você pode acompanhar pelo Git Bash os arquivos que adicionou/alterou com o comando:<br><br>

<b>git status</b> <br> <br>
 </h3>
<img src="assets\ststus.PNG"width="950px" height="400px"> <br> <br>


<h3 style="font-size:1.4em" align="center">8.	Antes de fazer o commit, é necessário adicionar os arquivos pelo GITBASH, utilizando o comando: <br><br>

<b>git add . </b> &#160;  //(. Ou *)  no final do comando
</h3>
<br><br>

<img src="assets\gitadd.PNG" width="850px" height="200px"><br><br>

<h3 style="font-size:1.4em" align="center">9.	Após adicionar os arquivos, para salva-los, utilize o comando: <br><br>

<b>git commit -m “Nome da atualização”</b> &#160; // Tem que ser entre “ ”</h3> <br><br>

<img src="assets\commit.PNG" width="950px" height="200px"> <br><br>


<h3 style="font-size:1.4em" align="center">10.	Alterar Branchs, para alterar as branchs (Master/Main) utilize o comando:<br><br>

<b>git branch -m “main” </b> &#160; // tem que ser o nome da Branch <u>(main ou master)</u> entre “ ” <br> <br>
</h3>

<img src="assets\branch.PNG" width="950px" height="200px" ><br><br><br>

<h1 align="center">Criar Repositório no site GitHub</h1>

<h3 style="font-size:1.4em">
1. No site, irá aparecer um botão verde com <b><u>“New”</u></b> escrito nele, ao clicar você será redirecionado á outra pagina <br> <br>
<img src="assets\rep1.PNG">
<img src="assets\rep2.PNG">
 </h3><br>
<h3 style="font-size:1.4em">  2.	Após configurar seu repositório e cria-lo, você sera redirecionado a outra pagina que contém os comandos para utilizar no GitBash, e também ira conter o <u>LINK</u> do seu repositório, copie ele: </h3> <br>
<img src="assets\rep3.PNG"><br>

<h3 style="font-size:1.4em" align="center">3.	Para relacionar o  Repositório criado no desktop com o Repositorio criado no GitHub, no GitBash utilize o comando : <br><br>
	
  <b>git remote add origin</b> (cole o link do repositorio) <br> <br>
  <img src="assets\remote.PNG" width="850px" height="200px">
 </h3>
<h3 style="font-size:1.4em" align="center"> 4.	Para enviar os aqruivos do desktop para o Github, no GitBash utilize o comando: <br><br>
<b>git push -u origin (main ou master)</b> &#160; //dependendo da sua Branch
</h3> <br>
<img src="assets\push.PNG" width="850px" height="300px"><br>
<h3 align="center" style="font-size:1.4em">5.	Para pegar os arquivos do repositório do GitHub e mandar para o repositório do Desktop utilize: <br>

<b >git pull</b>
 </h3>
 <img src="assets\pull.PNG" width="850px" height="200px"><br>
<h3 align="center" style="font-size:1.4em">6.	Para clonar o repositório de qualquer usuário GitHub, na pagina do repositório dele aparecera um botão verde escrito “Code”, ao clicar aparecerá o link do repositório, para clonar utilize:<br><br>

<b>git clone (link do repositório)</b>
 </h3> <br>

 <img src="assets\clone.PNG" width="850px" height="200px"><br>


<h2 align="center">Alguns vídeos/sites para mais comandos do GitHub </h2> <br>
<a>https://www.youtube.com/watch?v=UBAX-13g8OM&t=834s </a> <h3>Criando reposiório - Rafaella Ballerini</h3> <br><br>
<a>https://www.hostinger.com.br/tutoriais/comandos-basicos-de-git?ppc_campaign=google_performance_max&gclid=CjwKCAjwh5qLBhALEiwAioods5NDRzd7o3feKGElfCL_UEPplPsAH1sxAt5lstK8kLzlsNk9TGfDQxoCGJIQAvD_BwE</a> <h3>Coamndos Git - Hostinger</h3> <br><br>
<a>http://gabsferreira.com/criando-e-enviando-arquivos-para-seu-repositorio-no-github/</a><h3>Enviando e criando arquivos Git - GFbsferreira</h3>



