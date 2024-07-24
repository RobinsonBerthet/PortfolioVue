<template>
    <div class="widget-box">
        <h3>Refonte appli Mobile Dispo SAMU</h3>
        <p>
            Ce projet a pour but de refaire complètement une application qui était à la base en WINDEV Mobile pour la réecrire en React Native afin qu'elle soit plus performante.
        </p>
        <br>
        <br>
        <h3>But de la refonte</h3>
        <p>
            J'ai recrée une Application Mobile utilisée par le SAMU principalement pour consulter leurs disponibilités, et recevoir de nouvelles missions. 
            Le problème de l'ancienne application est qu'elle fonctionnait avec un serveur socket qui envoyait les données (comme les nouvelles missions),
            mais la connexion à ce serveur se coupait fréquemment, de plus le "bug" n'a pas été trouvé et résolu, l'application était assez historique donc elle n'était pas très maintenable.
            J'ai alors recrée l'application afin de corriger ce problème et d'optimiser un maximum le code pour qu'il soit plus maintenable et performant.
        </p>
        <br>
        <div class="flex flex-col lg:flex-row items-center space-x-4 space-y-4">
            <img class="imgPart imgUser" src="..\..\..\public\images\dispoSamu2.jpg" />
            <img class="imgPart" src="..\..\..\public\images\dispoSamu3.jpg" />
            
        </div>
        <br>

    </div>
</template>
