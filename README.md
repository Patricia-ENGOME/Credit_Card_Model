Prédiction d'Acceptation de Prêt Bancaire avec le Machine Learning et Déploiement avec Flask


Contexte et Problématique

Octroi de prêts bancaires est une activité clé, mais risquée. Les banques doivent évaluer la solvabilité des demandeurs pour minimiser les défauts de paiement.
Ce projet vise à prédire automatiquement si un client obtiendra un prêt en fonction de son profil.

Objectifs

✅ Analyser les facteurs influençant l’acceptation d’un prêt.
✅ Entraîner et comparer plusieurs modèles de classification.
✅ Identifier les variables les plus déterminantes.

Présentation des données

Dans ce projet, nous utilisons une base de données contenant des informations sur des clients ayant fait une demande de prêt bancaire. https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset?resource=download

Gender: Sexe du demandeur (Male/Female)
Married: Indique si le demandeur est marié (Yes/No)
Dependents: Nombre de personnes à charge (0, 1, 2, 3+)
Education : Niveau d’éducation (Graduate/Not Graduate)
Self_Employed : Indique si le demandeur est indépendant (Yes/No)
ApplicantIncome : Revenu principal du demandeur
CoapplicantIncome : Revenu du conjoint(e) du demandeur (si applicable)
Loan_Amount : Montant du prêt demandé
Loan_Amount_Term : Durée du prêt en mois
Credit_History : Historique de crédit (1 = bon, 0 = mauvais)
Property_Area : Localisation du bien (Urban, Rural, Semiurban)
Loan_Status Variable cible : prêt accordé (Y) ou refusé (N)