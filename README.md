<!DOCTYPE html>
<html lang="fr">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Enquête habitat et bien-être</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    background:#f3f3f1;
    font-family:Arial, Helvetica, sans-serif;
    color:#0047B3;
}

.container{
    max-width:1000px;
    margin:auto;
    padding:40px 25px 60px 25px;
}

h1{
    text-align:center;
    color:#0047B3;
    font-size:clamp(2.2rem, 5vw, 4rem);
    font-weight:700;
    margin-bottom:50px;
}

.intro{
    text-align:center;
    font-size:clamp(1.2rem, 2.5vw, 2rem);
    line-height:1.5;
    margin-bottom:60px;
}

.question{
    text-align:center;
    color:#D97B5C;
    font-style:italic;
    font-weight:700;
    font-size:clamp(2.3rem, 6vw, 5rem);
    line-height:1.3;
    margin:40px 0 60px 0;
}

.paragraph{
    font-size:clamp(1.2rem, 2.2vw, 2rem);
    line-height:1.6;
    margin-bottom:50px;
    text-align:center;
}

.orange{
    color:#D97B5C;
    font-weight:600;
}

.events{
    display:flex;
    flex-direction:column;
    gap:30px;
    margin-bottom:50px;
}

.event{
    font-size:clamp(1.2rem, 2vw, 1.9rem);
    line-height:1.5;
    text-align:center;
}

.mail-display{
    text-align:center;
    font-size:clamp(1.2rem, 2vw, 1.8rem);
    font-weight:bold;
    margin-bottom:40px;
    line-height:1.6;
    word-break:break-word;
}

.bubbles{
    display:flex;
    justify-content:center;
    gap:40px;
    flex-wrap:wrap;
}

.bubble{
    width:260px;
    height:260px;

    background:#D97B5C;
    color:white;

    border-radius:50%;

    text-decoration:none;

    display:flex;
    align-items:center;
    justify-content:center;

    text-align:center;

    padding:20px;

    font-size:1.4rem;
    font-weight:bold;

    transition:0.3s;
}

.bubble:hover{
    transform:scale(1.05);
}

.footer{
    background:#0047B3;
    color:white;
    text-align:center;

    padding:18px;

    margin-top:60px;

    font-size:clamp(0.9rem, 2vw, 1.3rem);

    letter-spacing:2px;
    font-weight:bold;
}

/* Téléphones */

@media (max-width: 768px){

    .container{
        padding:25px 20px 40px 20px;
    }

    .intro{
        margin-bottom:40px;
    }

    .question{
        margin:30px 0 40px 0;
    }

    .paragraph{
        text-align:left;
    }

    .event{
        text-align:left;
    }

    .bubbles{
        flex-direction:column;
        align-items:center;
        gap:20px;
    }

    .bubble{
        width:100%;
        max-width:340px;
        height:90px;

        border-radius:20px;

        font-size:1.2rem;
    }

    .footer{
        letter-spacing:1px;
        line-height:1.5;
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
        Contact :<br>
        whaoucnrs@gmail.com
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
