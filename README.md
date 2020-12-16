# COVID_SPOTTED

L'objectif de ce projet a été de se familiariser à la création d'un modèle d'apprentissage supervisé profond (deep learning) pour la détection automatique 
de patients atteints de la COVID-19 en maximisant la précision de détection. Pour cela, une base de données publique a été utilisée 
(https://www.kaggle.com/tawsifurrahman/covid19-radiography-database) contenant un mélange de 219 clichés radiographiques de patients positifs au COVID-19, 
de 1341 clichés radiographiques de patients positifs à une infection virale respiratoire déclenchée par un autre virus (toujours à tropisme pulmonaire) qui est à l'origine
de la COVID-19 et finalement 1345 clichés radiographiques de patients sains. Il est à noté que ce projet a été entièrement réalisé sous le langage de programmation Python et 
grâce à l'utilisation de librairies utiles à l'avancée de ce projet.

Base de données construite par l'équipe de recherche cidessous:

M.E.H. Chowdhury, T. Rahman, A. Khandakar, R. Mazhar, M.A. Kadir, Z.B. Mahbub, K.R. Islam, M.S. Khan, A. Iqbal, N. Al-Emadi, M.B.I. Reaz, M. T. Islam, 
“Can AI help in screening Viral and COVID-19 pneumonia?” IEEE Access, Vol. 8, 2020, pp. 132665 - 132676.

Ce projet est composé de trois grandes parties:

+ Exploration des données contenus de la base de données utilisée
+ Visualisation des données
+ Modélisation - Classification

La grande partie "Modélisation - Classification" est constituée de plusieurs sous parties :

+ Architectures CNN & Lenet
+ Transfert learning VGG16 & resnet50
+ Features extraction avec VGG16 + Logistic Regression/SVC/Random Forest
