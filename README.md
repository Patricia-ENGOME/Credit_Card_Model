# Prédiction d'Acceptation de Prêt Bancaire avec le Machine Learning et Déploiement avec Flask

## Contexte et Problématique
Octroi de prêts bancaires est une activité clé, mais risquée. Les banques doivent évaluer la solvabilité des demandeurs pour minimiser les défauts de paiement. <br>
Ce projet vise à prédire automatiquement si un client obtiendra un prêt en fonction de son profil.

## Objectifs
✅ Analyser les facteurs influençant l’acceptation d’un prêt. <br>
✅ Entraîner et comparer plusieurs modèles de classification.<br>
✅ Identifier les variables les plus déterminantes.<br>

## Présentation des données
Dans ce projet, nous utilisons une base de données contenant des informations sur des clients ayant fait une demande de prêt bancaire. https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset?resource=download

Gender: Sexe du demandeur (Male/Female) <br>
Married: Indique si le demandeur est marié (Yes/No)	<br>
Dependents: Nombre de personnes à charge (0, 1, 2, 3+)	<br>
Education : Niveau d’éducation (Graduate/Not Graduate)	<br>
Self_Employed : Indique si le demandeur est indépendant (Yes/No) <br>
ApplicantIncome : Revenu principal du demandeur	<br>
CoapplicantIncome : Revenu du conjoint(e) du demandeur (si applicable)	<br>
Loan_Amount : Montant du prêt demandé <br>
Loan_Amount_Term : Durée du prêt en mois <br>
Credit_History : Historique de crédit (1 = bon, 0 = mauvais) <br>
Property_Area : Localisation du bien (Urban, Rural, Semiurban) <br>
Loan_Status	Variable cible : prêt accordé (Y) ou refusé (N)
