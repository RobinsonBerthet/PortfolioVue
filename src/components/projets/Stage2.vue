<template>
    <div class="widget-box">
        <h3>Application de migration de base de données Stage 2ème année de BTS</h3>
        <p>
            Cette application à été conçue pour migrer les bases de données de type HFSQL qui sont utilisé avec WINDEV en MySQL.
        </p>
        <br>
        <br>
        <h3>Comment ai-je réalisé ce projet ?</h3>
        <p>Pour réaliser cet applicatif j'ai du me connecter d'abord sur un serveur HFSQL C/S et sur un serveur MySQL, 
            pour ensuite effectuer la migration du serveur HFSQL vers le serveur MySQL.</p>
        <br>
        <div class="flex flex-col lg:flex-row items-center">
            <img class="imgStag1" src="..\..\..\public\images\migration.png" />

            <p>Voici la page du début de l'application. Cette page permet de se connecter à deux serveur (HFSQL C/S et MySQL)</p>
        </div>
        <br>
        <div class="flex flex-col lg:flex-row items-center">
            <img class="imgStag1" src="..\..\..\public\images\migration1.png" />
            <p>
                Dès que l'on est connecté à un serveur HFSQL on peut choisir la base de données à migrer. 
                Cependant les bases HFSQL sont parfois construites différemment des bases MySQL car il peut y avoir des sous dossiers dans une base.</p>
        </div>
        <br>
        <div class="flex flex-col lg:flex-row items-center">
            <img class="imgStag1" src="..\..\..\public\images\migration2.png" />
            <p>
                Après avoir seléctionnée la Base de données à migrer on peut généré un script de cette base si elle comporte pas de dossier sinon on ne peut générer le script que d'un seul sous-dossier. 
                Dans ce cas il n'y a qu'un seul sous dossier alors on peut générer la base entière. 
            </p>
        </div>
        <br>
        <div class="flex flex-col lg:flex-row items-center">
            <img class="imgStag1" src="..\..\..\public\images\migration3.png" />
            <p>
                Une fois le script généré on peut le déposer directement dans la zone qui récupère le script pour qu'il soit exécuté directement sur le serveur MySQL.
            </p>
        </div>
        <br>
        <div class="flex flex-col lg:flex-row items-center">
            <img class="imgStag1" src="..\..\..\public\images\migration4.png" />
            <p>
                Après avoir sélectionné les deux bases sur chaque serveur la migration des données peut s'effectuer.
            </p>
        </div>
    </div>
</template>