# Détection-de-Fraude-IEEE-CIS

<p align="center">
    <img src="https://github.com/TAOUFIK05/Detection-de-Fraude-IEEE-CIS/assets/48359677/e22f4c0b-34b4-4373-ac26-6e6fb017b8cb.jpg" width='900' height="400" />
</p>

Ce dépôt contient le code en réponse à la compétition "IEEE-CIS Fraud Detection". Cette compétition, organisée par la IEEE Computational Intelligence Society (IEEE-CIS), vise à détecter la fraude dans les transactions client.

Imaginez-vous à la caisse d'un supermarché avec une longue file d'attente derrière vous, lorsque le caissier annonce à voix haute que votre carte a été refusée. À ce moment-là, vous ne pensez probablement pas à la science des données qui a déterminé votre sort.

Gêné, et certain que vous avez les fonds nécessaires pour organiser une fête de nachos épique pour 50 de vos amis les plus proches, vous essayez à nouveau votre carte. Même résultat. Alors que vous vous écartez et laissez le caissier s'occuper du client suivant, vous recevez un message texte de votre banque. "Appuyez sur 1 si vous avez vraiment essayé de dépenser 500 $ en fromage cheddar."

Bien que peut-être gênant (et souvent embarrassant) sur le moment, ce système de prévention de la fraude permet en réalité d'économiser des millions de dollars aux consommateurs chaque année. Les chercheurs de la IEEE Computational Intelligence Society (IEEE-CIS) souhaitent améliorer ce chiffre, tout en améliorant l'expérience client. Avec une détection de fraude plus précise, vous pouvez continuer à profiter de vos chips sans tracas.

La IEEE-CIS travaille dans divers domaines de l'intelligence artificielle et de l'apprentissage automatique, notamment les réseaux neuronaux profonds, les systèmes flous, la computation évolutive et l'intelligence de swarm. Aujourd'hui, ils s'associent à la principale entreprise de services de paiement au monde, Vesta Corporation, à la recherche des meilleures solutions pour l'industrie de la prévention de la fraude, et vous êtes invité à relever le défi.

Dans cette compétition, vous évaluerez des modèles d'apprentissage automatique sur un ensemble de données volumineux et difficile. Les données proviennent des transactions de commerce électronique du monde réel de Vesta et contiennent une large gamme de fonctionnalités, de type de dispositif à des caractéristiques de produit. Vous avez également la possibilité de créer de nouvelles fonctionnalités pour améliorer vos résultats.

En cas de succès, vous améliorerez l'efficacité des alertes de transaction frauduleuse pour des millions de personnes dans le monde, aidant des centaines de milliers d'entreprises à réduire leurs pertes dues à la fraude et à augmenter leurs revenus. Et bien sûr, vous épargnerez aux fêtards comme vous les tracas des faux positifs.
Description du jeu de données

Dans cette compétition, vous prédisez la probabilité qu'une transaction en ligne soit frauduleuse, comme indiqué par la cible binaire isFraud.

Les données sont divisées en deux fichiers : identity et transaction, qui sont joints par TransactionID. Toutes les transactions n'ont pas d'informations d'identité correspondantes.

Fonctionnalités catégorielles - Transaction :

    ProductCD
    card1 - card6
    addr1, addr2
    P_emaildomain
    R_emaildomain
    M1 - M9

Fonctionnalités catégorielles - Identité :

    DeviceType
    DeviceInfo
    id_12 - id_38

La fonctionnalité TransactionDT est un délai par rapport à une date de référence donnée (pas un horodatage réel).

Vous pouvez en savoir plus sur les données dans ce post de l'hôte de la compétition.
Fichiers

    train_{transaction, identity}.csv - l'ensemble d'entraînement
    test_{transaction, identity}.csv - l'ensemble de test (vous devez prédire la valeur isFraud pour ces observations)

