<template>
    <div class="widget-box">
        <h3>AP4 Le Bon Vivant</h3>
        <p>
            Cette application a été réalisée dans le but de gérer un bar-restaurant.
            Elle a été réalisée entièrement avec une base de données commune utilisée par un site web du restaurant et une application mobile.
            
        </p>
        <br>
        <br>
        <h3>Les fonctionnalités disponible sur l'application sont:</h3>
        <p>
            Le But de cet applicatif était de pouvoir gérer les produits(CRUD) du bar-restaurant, leur stock. 
            L'utilisateur (dirigeant) peut gérer son personnel(cuisinier, dirigeant, serveur) avec l'ajout/modification/suppression de ceux-ci.
            Il peut aussi gérer l'impression des factures de chaque commande sur place.
            Il peut désactiver ou réactiver un client pour un motif précis.
            Enfin l'utilisateur connecté peut consulter les chiffres du restaurant (nombres de commandes sur-place/à emporter par an/mois, chiffre d'affaire annuel).
        </p>
        <br>
        <hr>
        <br>
        <h3 class="text-center">Connexion en tant que dirigeant</h3>
        <br>
        <div class="flex flex-col lg:flex-row items-center">
            <img class="imgAP4" src="..\..\..\public\images\connexionAP4.png" />
            <p>Mot de passe défini par le développeur, il pourra être modifié dans la gestion du personnel.</p>
        </div>
        <br>
        <hr>
        <br>
        <div class="flex flex-col lg:flex-row items-center">
            <img class="imgAP4" src="..\..\..\public\images\menuAP4.png" />
            <p>
                Voici le menu de l'application, l'utilisateur peut naviguer dans les différentes rubriques: 
                Approvisionnement(gestion des produits et des stocks), gestion des factures(impression des commandes), 
                gestion du personnel, gestion des comptes client, consultation des chiffres du bar-restaurant.
            </p>
        </div>
        <br>
        <hr>
        <br>
        <h3 class="text-center">Approvisionnement</h3>
        <br>
        <div class="flex flex-col lg:flex-row items-center">
            <img class="imgAP4" src="..\..\..\public\images\appro.png" />
            <p>
                La page d'Approvisionnement (onglet réapprovisionnement) permet d'une part d'alimenter le stock du bar-restaurant grâce à la liste déroulante à droite du tableau. 
                Ce tableau permet de consulter le nombre de produits qu'il y a déjà en stock.
            </p>
        </div>
        <br>
        <div class="flex flex-col lg:flex-row items-center">
            <img class="imgAP4" src="..\..\..\public\images\appro1.png" />
            <p>
                D'autre part sur l'onglet de gestion des produits on peut ajouter/modifier/supprimer et consulter les produits présents en base de données.
            </p>
        </div>
        <br>
        <div class="flex flex-col lg:flex-row items-center">
            <img class="imgAP4" src="..\..\..\public\images\approModif.png"/>
            <p>
                Cette pop-up permet à l'utilisateur de créer(bouton ajouter) ou modifier un produit(bouton modifier sélection d'un produit dans le tableau au dessus).
            </p>
        </div>
        <br>
        <hr>
        <br>
        <h3 class="text-center">Gestion des factures</h3>
        <br>
        <div class="flex flex-col lg:flex-row items-center">
            <img class="imgAP4" src="..\..\..\public\images\facture.png"/>
            <p>
                La page de gestion des factures permet au dirigeant de consulter une facture précise avec la liste déroulante 
                et il peut voir le prix TTC de cette commande, il peut l'imprimer.
            </p>
        </div>
        <br>
        <div class="flex flex-col lg:flex-row items-center">
            <img class="imgAP4" src="..\..\..\public\images\pdf.png"/>
            <p>
               Voici le pdf généré après l'appui sur le bouton imprimer. 
            </p>
        </div>
        <br>
        <hr>
        <br>
        <h3 class="text-center">Gestion du Personnel</h3>
        <br>
        <div class="flex flex-col lg:flex-row items-center">
            <img class="imgAP4" src="..\..\..\public\images\personnel.png"/>
            <p>
                Voici la page qui permet la gestion du personnel (soit dirigeant, cuisinier ou serveur). 
                L'utilisateur peut modifier ajouter ou supprimer un membre du personnel du bar-restaurant.
            </p>
        </div>
        <br>
        <div class="flex flex-col lg:flex-row items-center">
            <img class="imgAP4" src="..\..\..\public\images\modifPerso.png"/>
            <p>
                Cette pop-up permet l'ajout et la modification d'un membre du personnel.
            </p>
        </div>

    </div>
</template>