<svelte:head>
    <title>NSI | Sciences Informatiques</title>
</svelte:head>
<div>
    <div class="container">
        <div class="cta">
            <small>NSI Terminale</small>
            <h2>Rejoignez des centaines d'apprenants gratuitement.</h2>
            <p>
                Abonnez-vous et recevez des fiches de révisions par chapitre
                ainsi que
                <br />des sujets type bac chaque semaine avec l'essentiel du
                cours!
            </p>
            <div class="action">
                <input
                    type="email"
                    name="email"
                    id="email"
                    placeholder="Entrée votre email"
                />
                <button class="abonner">S'abonner</button>
            </div>
        </div>
        <div class="cours">
            <a class="lien-carte" href="/notion-de-programme">
                <div class="carte">
                    <img
                        src="./notion_de_programme.jpg"
                        alt="Notion de programme"
                    />
                    <div class="h3">Notion de programmation</div>
                </div>
            </a>
            <a class="lien-carte" href="/structure-de-données">
                <div class="carte">
                    <img
                        src="./structure_de_données.jpg"
                        alt="Structure de données"
                    />
                    <div class="h3">Structure de données</div>
                </div>
            </a>
        </div>
    </div>
</div>

<style>
    #email {
        margin-top: 22px;
        margin-bottom: 7px;
        background: #ffffff;
        border: 1px solid #d0d5dd;
        height: 35px;
        width: 20%;
        padding: 15px;
        box-shadow: 0px 1px 2px rgba(16, 24, 40, 0.05);
        border-radius: 8px;
    }
    .abonner {
        background: #f6826bc5;
        height: 35px;
        width: 7%;
        border: 1px solid #f6826bc5;
        box-shadow: 0px 1px 2px rgba(16, 24, 40, 0.05);
        border-radius: 8px;
        margin-left: 16px;
        cursor: pointer;
    }

    small {
        color: #333;
    }
    .cta {
        margin-top: 55px;
        display: flex;
        justify-content: center;
        flex-direction: column;
        gap: 10px;
    }
    .cta > h2 {
        margin-bottom: 10px;
    }

    .cours {
        margin-top: 70px;
        display: flex;
        gap: 50px;
        flex-wrap: wrap;
    }
    /*.image {
        height: 220px;
        background-color: rgba(51, 51, 51, 0.192);
        border-radius: 8px;
        margin-bottom: 15px;
    }*/
    .carte {
        box-shadow: 0px 0px 3px rgba(16, 24, 40, 0.233);
        width: 250px;
        border-radius: 15px;
        text-align: center;
        padding: 15px;
    }
    .carte > img {
        border: 1px solid rgba(63, 63, 63, 0.2);
        border-radius: 8px;
        margin-bottom: 10px;
    }
    .lien-carte {
        color: black;
        text-decoration: none;
    }

    @media (max-width: 400px) {
        .action {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 10px;
        }
        #email,
        .abonner {
            width: 100%;
        }
        #email {
            margin-left: 15px;
        }
        .carte > img {
            border-radius: 10px;
            margin-bottom: 15px;
            border: 1px solid rgba(0, 0, 0, 0.2);
        }
        .cta {
            text-align: center;
        }
        .cta > h2 {
            font-size: 1.2rem;
        }
        .cta > small {
            font-size: 0.8rem;
        }
        p {
            font-size: 0.95rem;
        }
        .cours {
            display: flex;
            justify-content: center;
        }
    }
</style>
