# Implémentation bout à bout de l'algorithme skip-gram avec TensorFlow 2
Ce dépôt contient une implémentation de bout en bout de l'algorithme skip-gram qui est une méthode de Word2Vec. Le Word2Vec est une technique du NLP qui permet de déterminer une représentation numérique d'un mot. Elle consiste à déterminer un espace multidimensionnel où les mots qui ont une proximité sémantique sont plus proches. Cette représenttion offre la possibilité d'effectuer des opérations comme : roi - homme + femme = reine qui veut dire que la reine est pour la femme ce que le roi est pour l'homme.  

La représentation numérique des mots étant une étape indispensable dans les taches du traitement automatique des langues, bien comprendre le leur fonctionnement est nécessaire si l'on aspire à être un expert NLP. Ce travail est un bon point de départ car il permet de bien comprendre le fonctionnement théorique et la mise en oeuvre d'un des algorithmes les plus performants du word embedding à savoir le skip-gram. La compréhension de l'algorithme skip-gram facilite celle du Continuous Bag of Words (CBOW) et des techniques plus avancées comme Glove et ELMO.  

Pour entrainer l'algorithme skip-gram, nous utilisons des données provenant du [site](http://mlg.ucd.ie/datasets/bbc.html). Ces données se composent de 2 225 documents de la BBC correspondant à des articles dans cinq domaines d'actualité (affaires, divertissement, politique, sport, technologie) de 2004 à 2005.  

Ce travail se base profondément sur le livre [**Natural Language Processing with TensorFlow, Second Edition**](https://www.amazon.fr/Natural-Language-Processing-TensorFlow-sought-after/dp/1838641351/ref=tmm_pap_swatch_0?_encoding=UTF8&qid=1697820792&sr=8-4) de [Thushan Ganegedara](https://www.linkedin.com/in/thushanganegedara/) et la [documentation officielle de TensorFlow](https://www.tensorflow.org/api_docs/python/tf). 