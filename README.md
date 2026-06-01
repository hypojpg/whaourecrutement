<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Le bien-être au quotidien - Programme WHAOU</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f7fa;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 900px;
            margin: 50px auto;
            padding: 30px;
            background-color: white;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            text-align: center;
        }

        h1 {
            color: #2c3e50;
            margin-bottom: 30px;
        }

        p {
            font-size: 1.1em;
            line-height: 1.7;
            color: #444;
            text-align: justify;
        }

        .buttons {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 40px;
            flex-wrap: wrap;
        }

        .bubble {
            width: 220px;
            height: 220px;
            border-radius: 50%;
            background-color: #4a90e2;
            color: white;
            text-decoration: none;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 20px;
            font-size: 1.1em;
            font-weight: bold;
            transition: transform 0.3s, background-color 0.3s;
        }

        .bubble:hover {
            transform: scale(1.08);
            background-color: #357abd;
        }

        @media (max-width: 600px) {
            .bubble {
                width: 180px;
                height: 180px;
                font-size: 1em;
            }
        }
    </style>
</head>
<body>

<div class="container">

    <h1>Le bien-être au quotidien – Le programme WHAOU s'intéresse à votre quartier</h1>

    <p>
        Nous cherchons à comprendre les liens entre l'état de l'habitat et le bien-être des résidents.
        Pour avancer, nous avons besoin de vous !
    </p>

    <p>
        Notre recherche s'implante dans les quartiers de Danube, Solidarité et Marseillaise.
        Nous recherchons des habitants pour participer à des entretiens individuels d'environ une heure,
        entièrement anonymes, afin de parler de votre ressenti sur votre cadre de vie.
    </p>

    <p>
        L'objectif est d'aider les politiques publiques liées au logement à améliorer les conditions
        de votre bien-être.
    </p>

    <p>
        Contactez-nous par mail ou remplissez le formulaire ci-dessous !
    </p>

    <div class="buttons">

        <a class="bubble"
           href="mailto:saphir.crh@gmail.com?subject=Participation%20%C3%A0%20la%20recherche%20WHAOU">
            Nous contacter<br>par mail
        </a>

        <a class="bubble"
           href="https://docs.google.com/forms/d/e/1FAIpQLScXlb-k1AlUgO0_f-R29YzN_gTRfIA0Chgc72HyyWTOa-t_Iw/viewform?usp=header"
           target="_blank">
            Accéder au<br>formulaire
        </a>

    </div>

</div>

</body>
</html>
