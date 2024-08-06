# Tachês :
-	Développer un tableau de bord de ventes CRM
-	Utilisateurs : Sales Managers
-	Outils : Microsoft Excel, Power BI

# Data
Les données comprennent les variables suivantes :
-	Owner : Représentant des ventes à qui le lead est attribué / propriétaire du lead
-	Lead acquisition date : la date que le lead a été saisi pour la première fois dans le système CRM
-	Product : le produit auquel l’organisation s’est intéressée
-	Status : le statut du lead. Les statuts suivants peuvent être attribués à chaque lead
1. New : vient d’ajouter
2.	Qualified : le marketing a qualifié le lead comme valide
3.	Sales accepted : le service des ventes a accepté le lead qualifié comme valide
4.	Opportunity : le service des ventes travaille avec le lead
5.	Customer : le lead (le client potentiel) est converti en client
6.	Churned customer : le client a arrêté d’utiliser le produit
7.	Disqualified : le marketing ou le service des ventes a disqualifié le lead comme invalide (cela peut se produire n’importe quel stade)
-	Status sequence : la colonne indiquant la séquence d’une étape dans le processus de conversion de lead
-	Stage : stade du lead qui est dans la phase d’opportunité. Le stade peut être attribué comme suit : 
1.	Opened : le service des ventes s’efforce d’établir la communication initiale
2.	Initial contact : la communication initiale est établie
3.	Nurturing : la communication permanente avec l’entreprise au sujet de l’offre
4.	Proposal sent : une proposition est envoyée à l’entreprise
5.	Won : l’entreprise a accepté l’offre
6.	Lost : l’entreprise ne deviendra pas client

# Méthode :
-	Charger des données d’Excel vers Power BI
-	Construire un modèle en étoile dans Power BI
-	Créer de nouveaux indicateurs pour évaluer les performances commerciales et la santé du pipeline de vente

# Résult : 
![image](https://github.com/user-attachments/assets/73c01fcf-6950-4e4e-8104-e7c813e41456) <br/>
![image](https://github.com/user-attachments/assets/fdc90415-4d88-4aeb-8f4a-4aaff6027d04) <br/>
![image](https://github.com/user-attachments/assets/cdc8f98c-4006-47b6-92c0-c958e93359ea) <br/>

> [!IMPORTANT]
**Performance des ventes :**
La valeur totale diminue significative après l’exclusion des clients “churn” , ce qui suggère que près de la moitié des affaires étaient associées à des clients qui ont fini par cesser d’utiliser le produit. <br/>
- Pays : L’Italie, les Pays-Bas, le Portugal et l’Espagne ont un taux de conversion élevé (des opportunités aux clients). La Belgique, l'Allemagne et la Suisse ont atteint un taux de conversion plus faible mais une valeur moyenne des transactions élevée. L’Autriche et la France ont un taux de conversion faible et une valeur moyenne des transactions faible.
- Produit : Le SAAS et les Services sont les principales sources de revenus.
- La taille des entreprises : Plus de 50% de la valeur des transactions provient des moyennes entreprises. D’autres entreprises contribuent chacune d’environ 10%.
- L’industrie :  Les secteurs des transports, de la banque et du gouvernement ont le plus d’impact sur la valeur totale des transactions.
- La tendance des ventes : La valeur moyenne des transactions et le nombre des transactions fluctuent d’un mois à l’autre.

**Pipeline de vente :**
En général, le pipeline de vente montre un bon taux de conversion entre les différentes étapes, sauf les étapes suivantes : 
- L’opportunité au client : Seules 348 leads transfèrent du stade de l’opportunité au stade de client (CVR = 28.6%), ce qui suggère des possibilités d’amélioration (des marges de progression).
Recommandation : Déployer des outils automatisés pour assurer un suivi en temps utiles avec toutes les nouvelles opportunités.
- Envoi de la proposition aux “won” (entreprises ayant acceptées l’offre)  : Bien que plus de la moitié de la proposition envoyée se convertissent en gains, il y a toujours des pistes d’amélioration.
Recommandation : Analyser des propositions “lost” (entreprises ayant rejeté les propositions) pour identifier les objections courantes et affiner les stratégies de proposition en conséquence

_L'agent de vente :_
- Laura Thomson est le meilleur agent de vente avec la plus haute valeur de transaction et un taux moyen de “churn”.
- David Wilson a un cycle de vente court mais un faible taux de “won” et une faible valeur de la transaction. Il faut améliorer ses techniques de conversion et augmenter la taille des affaires en ciblant les leads les plus élevés.
- Emily Johnson a obtenu un taux de réussite élevé mais un taux de “churn” supérieur, ce qui suggère des problèmes potentiels avec la satisfaction du client. Il est recommandé de faire la mise au point d’après-vent pour réduire le taux de “churn”.
- Jessica Martinez a une valeur de la transaction élevée et un bon taux de réussite mais un cycle de vente long. Il faut rationaliser le processus de vente pour réduire le cycle de vente.





