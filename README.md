<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Enquête habitat et bien-être</title>

<style>

body{
    margin:0;
    padding:0;
    background:#f1f1ef;
    font-family: Arial, Helvetica, sans-serif;
    color:#0047B3;
}

.container{
    max-width:1000px;
    margin:auto;
    padding:40px 25px 60px 25px;
}

h1{
    text-align:center;
    font-size:3.5rem;
    color:#0047B3;
    margin-bottom:50px;
    font-weight:700;
}

.intro{
    font-size:2rem;
    line-height:1.4;
    text-align:center;
    margin-bottom:50px;
}

.question{
    text-align:center;
    color:#D97B5C;
    font-size:4rem;
    font-weight:bold;
    font-style:italic;
    line-height:1.3;
    margin:60px 0;
}

.paragraph{
    font-size:2rem;
    line-height:1.5;
    margin-bottom:35px;
}

.orange{
    color:#D97B5C;
}

.events{
    margin-top:40px;
}

.event{
    font-size:1.9rem;
    margin-bottom:30px;
    line-height:1.4;
}

.mail-display{
    text-align:center;
    font-size:2rem;
    font-weight:bold;
    margin-top:60px;
    margin-bottom:20px;
    color:#0047B3;
}

.bubbles{
    display:flex;
    justify-content:center;
    gap:60px;
    flex-wrap:wrap;
    margin-top:40px;
}

.bubble{
    width:260px;
    height:260px;
    border-radius:50%;
    text-decoration:none;
    color:white;
    background:#D97B5C;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:25px;
    font-size:1.5rem;
    font-weight:bold;
    transition:0.3s;
}

.bubble:hover{
    transform:scale(1.05);
}

.footer{
    margin-top:70px;
    background:#0047B3;
    color:white;
    text-align:center;
    padding:18px;
    font-size:1.4rem;
    font-weight:bold;
    letter-spacing:2px;
}

@media(max-width:768px){

    h1{
        font-size:2.3rem;
    }

    .intro,
    .paragraph,
    .event,
    .mail-display{
        font-size:1.4rem;
    }

    .question{
        font-size:2.6rem;
    }

    .bubble{
        width:200px;
        height:200px;
        font-size:1.2rem;
    }
}

</style>

</head>
<body>

<div class="container">

    <h1>Enquête habitat et bien-être</h1>

    <div class="intro">
        Nous sommes une équipe de chercheurs et nous étudions les liens entre l’état de l’habitat et le bien-être des locataires.
    </div>

    <div class="question">
        Êtes-vous content quand vous rentrez chez vous ?
    </div>

    <div class="paragraph">
        <span class="orange">Pour avancer, nous avons besoin de vous !</span>
        Si vous voulez vous exprimer et parler des problématiques liées à votre logement, n’hésitez pas !
    </div>

    <div class="events">

        <div class="event">
            Des entretiens seront conduits par notre équipe courant juin 2026 !
        </div>

        <div class="event">
            Rencontres collectives prévues dans le quartier, près de chez vous le 24 et 25 juin 2026 !
        </div>

    </div>

    <div class="mail-display">
        Contact : whaoucnrs@gmail.com
    </div>

    <div class="bubbles">

        <a class="bubble"
           href="mailto:whaoucnrs@gmail.com?subject=Participation%20%C3%A0%20l%27enqu%C3%AAte%20habitat%20et%20bien-%C3%AAtre">
            Nous contacter<br>par mail
        </a>

        <a class="bubble"
           href="https://docs.google.com/forms/d/e/1FAIpQLScXlb-k1AlUgO0_f-R29YzN_gTRfIA0Chgc72HyyWTOa-t_Iw/viewform?usp=header"
           target="_blank">
            Accéder au<br>formulaire
        </a>

    </div>

</div>

<div class="footer">
    POUR PARTICIPER À NOTRE RECHERCHE : WHAOUCNRS@GMAIL.COM
</div>

</body>
</html>
