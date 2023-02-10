# SITA-MURIEL-KEITA-MASTER-2-ECAP
# PRÉDICTION DU DIABÈTES CHEZ UNE PERSONNE 

Notre projet se base dsur la prédiction du diabète chez une personne. La base de données que nous avions utilisée provient du site Kaggle.
Notre base de données contient 16 variables et possède 70.692 observations . Presque toutes les variables sont catégorielles , une seule variable est quantitative. Notre variable Target ou à prédire est une variable binaire. 


Description des données 

 Suivant la description des données , nous avons :
 
 Diabetes : la variable à prédire , qui est une variable binaire . Elle prend la valeur 0 si la personne interrogée n'a pas le diabète et 1 si la personne interrogée est diabétique. 
 
 Age : les classes d'ages des individus allant de 1 à 13. 1 = 18-24 / 2 = 25-29 / 3 = 30-34 / 4 = 35-39 / 5 = 40-44 / 6 = 45-49 / 7 = 50-54 / 8 = 55-59 / 9 = 60-64 / 10 = 65-69 / 11 = 70-74 / 12 = 75-79 / 13 >= 80.
 
 Sex : le genre de la personne. Elle prend la valeur 0 si la personne interrogée est une femme , 1 si cette dernière est un homme. 
 
 HighChol : fort taux de cholestérol . variable binaire. 0 si la personne n'a pas un fort taux de cholestérol, 1 si cette dernière on a . 
 
 CholCheck : 0 = pas de controle de cholestérol dans 5 ans et  1 = controle de cholestérol dans 5 ans.

 BMI : indice de masse corporelle (IMC). 
 
 Smoker : Avez-vous fumé au moins 100 cigarettes dans toute votre vie ?  0 = non ou 1 = oui.
 
 HeartDiseaseorAttack : maladie coronarienne (CHD) ou infarctus du myocarde (MI) 0 = non ou  1 = oui
 
 PhysActivity : activité physique au cours des 30 derniers jours - hors travail  0 = non ou  1 = oui.
 
 Fruits : consommation d'un fruit ou plus dans une journée  0 = non ou  1 = oui.
 
 Veggies : consommation d'un légume ou plus dans une journée 0 = non ou  1 = oui .
 
 HvyAlcoholConsump : (hommes adultes >=14 verres par semaine et femmes adultes >=7 verres par semaine) 0 = non ou 1 = oui.
 
 GenHlth : État de santé sur une échelle de 1 à 5 ,  1 = excellent 2 = très bien 3 = bien 4 = équité 5 = pauvre .
 
 MentHlth : jours de mauvaise santé mentale échelle 1-30 jours.
 
 
 PhysHlth : maladie ou blessure physique jours au cours des 30 derniers jours sur une échelle de 1-30 jours.
 
 DiffWalk : Avez-vous de sérieuses difficultés à marcher ou à monter des escaliers ? 0 = non ou 1 = oui .

Nous sommes passées à la première étape c'est à dire au nettoyage de la base de données . 


# I _ Nettoyage de la base de données 

Cependant lors de l'importation de la base de données , presque toutes les variables y compris la variable à prédire n'ont pas été bien importées. Donc on a du recoder les variables qualitatives en varibles object et les variables quantitatives en float64 ou int64. Seule la variable BMI est réstée en float64. Toutes les autres variables ont été recodées en object.
Après nous sommes passées à la vérificaton de valeurs manquantes dans notre dataset.Notre base ne détient pas de valeurs manquantes. Nous avons regarder ensuite la statistique descriptive de chaque variable.

# II_STATISTIQUES DESCRIPTIVES DES DONNÉES 

  #  1_ Description de la variable à prédire 
  
  ![image](https://user-images.githubusercontent.com/118168338/218110225-c5481594-62ee-4d81-bf83-c0ba9770ab19.png)
