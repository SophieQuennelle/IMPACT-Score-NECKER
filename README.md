AL_SVM : algorithme de sélection des exemples à annoter pour constituer un jeu de données
qui pourra entraîner la classification par deep learning.


Text_Classifier : premier embedding par CamemBERT puis embedding des exemples par
le TextClassifier de Flair c'est à dire : gated recurrent unit uni ou bidirectionnelle pour l'embedding
de la sequence + one dense layer pour la classification.

Score : assembler les données et tracer la courbe ROC. 
