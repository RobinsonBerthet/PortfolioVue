<template>
    <div class="widget-box">
        <h3>AP3 Hackat'Innov</h3>
        <p>
            Ce projet est une évolution de l'application web Hackat'Innov.
            Cette application à pour but l'inscription à des hackathons(concours de code) pour différentes équipes.
        </p>
        <br>
        <br>
        <h3>Les Évolutions demandées étaient:</h3>
        <p>
            L'amélioration du profil des équipes (gestion des membres, désinscription, hackathons suivis) sur le web
            Connexion sécurisée aux données;
            Finalisation de la gestion des hackathons;
            Gestion des équipes et des membres par les administrateurs;
            Gestion de documents statistiques en aide aux administrateurs;
        </p>
        <br>
        <div class="flex flex-col lg:flex-row items-center">
            <img class="imgPart imgUser" src="..\..\..\public\images\userStory.png" />
            <p>User Stories données pour la réalisation des évolutions du site.</p>
            
        </div>
        <a href="/userStory">voir plus</a>
        <br>
        <hr>
        <br>
        <div class="flex flex-col lg:flex-row items-center">
            <img class="imgPart" src="..\..\..\public\images\img_participants.png" />
            <p>Consultation des membres de chaque équipe quand on est connecté en tant qu’équipe</p>
        </div>
        <br>
        <hr>
        <br>
        <div class="flex flex-col lg:flex-row items-center">
            <img class="imgPart" src="..\..\..\public\images\imgCGU.png" />
            <p>Page à Propos avec des CGU basiques</p>
        </div>
        <br>
        <hr>
        <br>
        <h3 class="text-center">Sécurisation de l'accès aux administrateurs</h3>
        <br>
        <div class="flex flex-col lg:flex-row items-center">
            <img class="imgPart" src="..\..\..\public\images\pageconnexion.png" />
            <p>Accès sécurisé au menu API en Admin (page identique à la connexion en tant qu'équipe, mais différente route
                et différents droits)</p>
        </div>
        <br>
        <div class="flex flex-col lg:flex-row items-center">
            <img class="imgPart" src="..\..\..\public\images\pageaccueil.png" />
            <p>Une Fois connecté en tant qu’Admin</p>
        </div>
        <br>
        <hr>
        <br>
        <h3 class="text-center">gestion complète de l'équipe</h3>
        <br>
        <div class="flex flex-col lg:flex-row items-center">
            <img class="imgPart" src="..\..\..\public\images\profilEquipe.png" />
            <p>
                Une Fois connecté en tant qu’Équipe l'utilisateur peut se déconnecter,
                se désincrire de l'hackathon en cours(possible réinscription à l'accueil si il reste des places).
                Il peut aussi modifier le profil de son équipe, supprimer/ajouter des membres.
            </p>
        </div>
        <br>
        <div class="flex flex-col lg:flex-row items-center">
            <img class="imgPart" src="..\..\..\public\images\modifMembre.png" />
            <p>
                L'utilisateur peut ajouter des membres à son équipe.
            </p>
        </div>
    </div>
</template>
