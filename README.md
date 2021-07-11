# Covid19

Cet ensemble de données contient des données anonymes provenant de patients dans un hôpital et dont les échantillons ont été prélevés pour effectuer le test covid19 SRAS-CoV-2.

L'objectif est de prédire les cas confirmés de COVID-19 parmi les cas suspects en se basant sur les résultats des tests de laboratoire.
Vous trouvez dans le notebook __covid19.ipynb__ le cycle de vie complet de la préparation des données, de la création et de l'évaluation du modèle.

Dans le fichier __app.py__ vous trouvez le code écrit pour le déploiment du modèle.

Vous trouvez la page web construite pour le déploiement du modèle à l'adresse suivante http://covid19-pred.herokuapp.com/

Vous pouvez ainsi remplir les champs qui correspondent aux résultats des tests de laboratoire et ensuite vous appuyer sur le boutton "Predict"

Exemple de données que vous pouvez fournir pour obtenir un cas positif au covid19:

Patient age quantile:19/Hematocrit:-0.495919/Hemoglobin:-0.6489/Platelets:-1.635414/Mean platelet volume:	0.683835/Red blood Cells:-0.973448/Lymphocytes:0.292779/ean corpuscular hemoglobin concentration (MCHC):-0.751633/Leukocytes:-0.406283/Basophils:-0.529226/Mean corpuscular hemoglobin (MCH):0.700891/Eosinophils:-0.70909/Mean corpuscular volume (MCV):1.187699/Monocytes:-0.141454/Red blood cell distribution width (RDW):-0.625073/est malade:0

Si vous faites entrer d'autres données vous allez probablement tomber sur un cas négatif.



