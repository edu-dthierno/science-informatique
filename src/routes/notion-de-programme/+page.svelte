<div class="container-cours">
    <div class="banner">
        <img src="./Notion de Programmation.jpg" alt="banner" />
    </div>
    <div class="mobile-banner">
        <h1>Notion de Programmation</h1>
    </div>
    <article>
        <h1 class="titre">Introduction</h1>
        <p>
            En informatique,
            <mark class="blue">
                la programmation est l’art de créer des programmes, qui sont des
                suites d’instructions ordonnées destinées à être exécutées par
                une machine.
            </mark>
            Pour cela il est indispensable d’utiliser des langages qui permettent
            à la machine de comprendre l’humain.
        </p>
    </article>
    <article>
        <h1 class="titre">Différents type de langages</h1>
        <p>
            Au plus bas niveau, le processeur ne comprend que le langage
            machine, qui est une suite d’opérations codées en binaire,
            incompréhensible pour un humain. C’est pourquoi des langages de plus
            haut niveau ont été inventés, mais il est nécessaire de les traduire
            en binaire.
        </p>
        <div>
            <p>
                Il existe pour cela <b>3 méthodes</b> qui correspondent à
                <b>3 types de langage de programmation</b> :
            </p>
            <ul class="list">
                <li>
                    Les <b class="gold">langages compilés</b>, dans lesquels le
                    code source écrit par le programmeur est
                    <mark class="blue">transformé en code binaire</mark>
                    par un logiciel appelé <u>compilateur</u>.
                    <span class="exemple">
                        <b>Exemples :</b> langage C, C++, Pascal et Ocaml.
                    </span>
                </li>
                <li>
                    Les <b class="gold">langages interprétés</b>, dont le code
                    source est utilisé en entrée d’un logiciel appelé
                    interpréteur, qui l’exécute ligne par ligne en
                    <u>décidant à chaque étape ce qu’il va faire ensuite</u>
                    .
                    <span class="exemple">
                        <b>Exemples :</b> Python, JavaScript, PHP.
                    </span>
                </li>
                <li>
                    Les <b class="gold"> langages semi interprétés</b>, qui
                    requièrent une compilation différente de la première : elle
                    ne transforme pas le code en instructions binaires mais se
                    contente de préparer le travail de l’interpréteur en
                    <mark class="blue">
                        réécrivant les instructions dans un langage
                        intermédiaire (byte-code)
                    </mark>
                    , qui sera plus <u>facile à traiter</u> par l’interpréteur
                    lors de son exécution.
                    <span class="exemple">
                        <b>Exemples :</b> Java, C # (C sharp)
                    </span>
                </li>
            </ul>
        </div>
    </article>
    <article>
        <h1 class="titre">Calculabilité et décidabilité</h1>
        <p>
            <mark class="blue"
                >La notion de calculabilité est apparue avec Alan Turing en
                1936.</mark
            >
            Pour la comprendre il est nécessaire d’en savoir plus sur la Machine
            de Turing.
        </p>
        <iframe
            width="100%"
            height="500"
            src="https://www.youtube.com/embed/L5O04P2ASRc?controls=0"
            title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
        />
    </article>
</div>

<style>
    .container-cours {
        width: 900px;
        margin: auto;
    }
    .banner {
        width: 100%;
        height: 300px;
        margin-top: 60px;
        margin-bottom: 50px;
        border-radius: 15px;
        box-shadow: 0px 0px 7px rgba(218, 218, 218, 0.507);
    }
    .mobile-banner {
        display: none;
    }
    img {
        border-radius: 15px;
    }
    .titre {
        margin-bottom: 15px;
        padding-bottom: 10px;
        border-bottom: 1px solid black;
    }
    article {
        margin: 40px 0;
        line-height: 1.8rem;
    }
    .blue {
        background: rgba(231, 243, 248, 1);
    }
    .gold {
        color: rgba(203, 145, 47, 1);
    }
    .list {
        margin: 10px 0;
    }
    li {
        margin: 10px 0;
    }
    .exemple {
        color: green;
    }
    iframe {
        margin: 15px 0;
        border: 5px solid rgba(203, 145, 47, 1);
        border-radius: 5px;
    }
    @media (max-width: 400px) {
        .container-cours {
            width: 300px;
            margin: auto;
        }
        .banner {
            display: none;
        }
        .mobile-banner {
            display: block;
            margin-top: 40px;
            font-size: 0.75rem;
            text-align: center;
            border: 1px solid black;
            padding: 10px 0px;
        }
        iframe {
            margin: 15px 0;
            border: 5px solid rgba(203, 145, 47, 1);
            border-radius: 5px;
            height: 150px;
        }
        .titre {
            font-size: 1.3rem;
        }
    }
</style>
