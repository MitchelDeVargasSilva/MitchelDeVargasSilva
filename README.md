<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mitchel Vargas | Desenvolvedor Full Stack</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Segoe UI,Tahoma,Geneva,Verdana,sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#0f172a;
    color:#fff;
}

.container{
    width:90%;
    max-width:1200px;
    margin:auto;
}

/* MENU */

header{
    position:fixed;
    width:100%;
    background:#111827;
    z-index:1000;
    box-shadow:0 3px 10px rgba(0,0,0,.3);
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 0;
}

.logo{
    font-size:28px;
    font-weight:bold;
    color:#38bdf8;
}

.menu{
    list-style:none;
    display:flex;
    gap:30px;
}

.menu a{
    text-decoration:none;
    color:#fff;
    transition:.3s;
}

.menu a:hover{
    color:#38bdf8;
}

/* HERO */

.hero{
    height:100vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    background:linear-gradient(135deg,#0f172a,#1e293b);
}

.hero h1{
    font-size:60px;
    margin-bottom:20px;
}

.hero h1 span{
    color:#38bdf8;
}

.hero p{
    font-size:22px;
    color:#cbd5e1;
    margin-bottom:40px;
}

.btn{
    display:inline-block;
    padding:15px 35px;
    background:#38bdf8;
    color:#fff;
    text-decoration:none;
    border-radius:8px;
    transition:.3s;
    font-weight:bold;
}

.btn:hover{
    background:#0284c7;
}

/* TITULOS */

section{
    padding:100px 0;
}

.title{
    text-align:center;
    margin-bottom:60px;
    font-size:38px;
}

/* SOBRE */

.sobre{
    display:grid;
    grid-template-columns:300px 1fr;
    gap:60px;
    align-items:center;
}

.avatar{
    width:280px;
    height:280px;
    border-radius:50%;
    background:#1e293b;
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:90px;
    margin:auto;
}

.sobre p{
    color:#cbd5e1;
    line-height:30px;
    font-size:18px;
}

/* HABILIDADES */

.skills{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:25px;
}

.skill{
    background:#1e293b;
    padding:30px;
    border-radius:10px;
    text-align:center;
    transition:.3s;
}

.skill:hover{
    transform:translateY(-8px);
}

.skill h3{
    margin-bottom:15px;
    color:#38bdf8;
}

/* PROJETOS */

.projects{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(320px,1fr));
    gap:30px;
}

.card{
    background:#1e293b;
    border-radius:10px;
    overflow:hidden;
}

.thumb{
    height:180px;
    background:#334155;
}

.card-body{
    padding:25px;
}

.card h3{
    margin-bottom:15px;
}

.card p{
    color:#cbd5e1;
    margin-bottom:20px;
}

.card a{
    color:#38bdf8;
    text-decoration:none;
}

/* EXPERIÊNCIA */

.timeline{
    max-width:900px;
    margin:auto;
}

.item{
    border-left:4px solid #38bdf8;
    padding-left:25px;
    margin-bottom:40px;
}

.item h3{
    margin-bottom:10px;
}

.item span{
    color:#38bdf8;
    font-size:14px;
}

/* CONTATO */

.contact{
    text-align:center;
}

.contact p{
    margin:15px 0;
    color:#cbd5e1;
}

footer{
    background:#111827;
    text-align:center;
    padding:30px;
    color:#94a3b8;
}

@media(max-width:800px){

.hero h1{
font-size:40px;
}

.sobre{
grid-template-columns:1fr;
text-align:center;
}

.menu{
display:none;
}

}
</style>

</head>
<body>

<header>

<div class="container">

<nav>

<div class="logo">
MV
</div>

<ul class="menu">
<li><a href="#sobre">Sobre</a></li>
<li><a href="#skills">Tecnologias</a></li>
<li><a href="#projetos">Projetos</a></li>
<li><a href="#experiencia">Experiência</a></li>
<li><a href="#contato">Contato</a></li>
</ul>

</nav>

</div>

</header>

<section class="hero">

<div class="container">

<h1>Olá, eu sou <span>Mitchel Vargas</span></h1>

<p>Desenvolvedor Delphi • PHP • CodeIgniter • Go</p>

<a href="#projetos" class="btn">
Ver Portfólio
</a>

</div>

</section>

<section id="sobre">

<div class="container">

<h2 class="title">Sobre Mim</h2>

<div class="sobre">

<div class="avatar">
👨‍💻
</div>

<div>

<p>
Sou desenvolvedor de software com experiência no desenvolvimento de sistemas desktop e aplicações web.
</p>

<br>

<p>
Possuo mais de <strong>5 anos de experiência com Delphi</strong>, desenvolvendo sistemas comerciais, integrações e automações.
</p>

<br>

<p>
Também atuo há <strong>3 anos com PHP utilizando CodeIgniter</strong>, criando sistemas administrativos, ERPs, CRMs, APIs REST e aplicações completas.
</p>

<br>

<p>
Atualmente estou estudando <strong>Go (Golang)</strong>, focando em APIs de alta performance, microsserviços e arquitetura moderna.
</p>

</div>

</div>

</div>

</section>

<section id="skills">

<div class="container">

<h2 class="title">Tecnologias</h2>

<div class="skills">

<div class="skill">
<h3>Delphi</h3>
<p>5 anos de experiência.</p>
</div>

<div class="skill">
<h3>PHP</h3>
<p>CodeIgniter 4, APIs REST e MVC.</p>
</div>

<div class="skill">
<h3>Go</h3>
<p>Aprendizado focado em Back-end.</p>
</div>

<div class="skill">
<h3>Banco de Dados</h3>
<p>MySQL, Firebird e SQLite.</p>
</div>

<div class="skill">
<h3>Front-end</h3>
<p>HTML5, CSS3, JavaScript e Bootstrap.</p>
</div>

<div class="skill">
<h3>Git</h3>
<p>GitHub, versionamento e colaboração.</p>
</div>

</div>

</div>

</section>

<section id="projetos">

<div class="container">

<h2 class="title">Projetos</h2>

<div class="projects">

<div class="card">

<div class="thumb"></div>

<div class="card-body">

<h3>Sistema Imobiliário</h3>

<p>
Sistema administrativo para imobiliárias com cadastro de imóveis, clientes e painel administrativo.
</p>

<a href="#">Ver Projeto →</a>

</div>

</div>

<div class="card">

<div class="thumb"></div>

<div class="card-body">

<h3>ERP Comercial</h3>

<p>
Sistema desenvolvido em Delphi para gestão empresarial.
</p>

<a href="#">Ver Projeto →</a>

</div>

</div>

<div class="card">

<div class="thumb"></div>

<div class="card-body">

<h3>API REST em Go</h3>

<p>
Projeto para gerenciamento de tarefas utilizando Gin Framework.
</p>

<a href="#">Ver Projeto →</a>

</div>

</div>

</div>

</div>

</section>

<section id="experiencia">

<div class="container">

<h2 class="title">Experiência</h2>

<div class="timeline">

<div class="item">

<h3>Desenvolvedor Delphi</h3>

<span>5 anos</span>

<p>
Desenvolvimento de sistemas desktop, integrações com banco de dados, APIs e automações.
</p>

</div>

<div class="item">

<h3>Desenvolvedor PHP</h3>

<span>3 anos</span>

<p>
Desenvolvimento de sistemas web utilizando PHP, CodeIgniter, Bootstrap, JavaScript e MySQL.
</p>

</div>

<div class="item">

<h3>Go Developer</h3>

<span>Atual</span>

<p>
Estudando desenvolvimento de APIs REST, microsserviços e arquitetura escalável.
</p>

</div>

</div>

</div>

</section>

<section id="contato">

<div class="container">

<h2 class="title">Contato</h2>

<div class="contact">

<p>💼 github.com/seuusuario</p>

<p>💬 linkedin.com/in/seuperfil</p>

<br>

</div>

</div>

</section>

</body>
</html>
