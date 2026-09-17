# Repo des notebooks mobilisés dans le cadre du volet BNF-ASP du projet TORNE-H

## Notebooks de détection/segmentation

* "executer_modele_yolo.ipynb" est un notebook permettant d'appliquer un modéle de détection yolo à un lot d'images, d'obtenir en sortie les coordonnées des BBoxs en texte et csv, ainsi que de produire une visualisation de ces Bboxs sur l'image d'origine. Une deuxième étape permet d'extraire les crops des Bbox à partir des csvs produits précdemment. Le notebook fonctionne sur une ou plusieurs classe.
* "dinov2_pca.ipynb" est un notebook permettant de fitter une pca sur un échantillon d'image, pour dans un premier temps en extraire l'avant plan, puis dans un second temps de fitter une secode pca sur cet avant plan pour en extraire les éléments significatifs.

## Notebooks adaptés du distant-viewing toolkit

* "depth_estimation.ipynb" est un notebook créant des crops des images d'un dossier selon un seuil de profondeur.
* "color_dv.ipynb" est un notebook effectuant une série d'analyses sur la colorimétrie d'une collection d'image, est permettant à la fin de générer et contrôler des couleurs. Par défaut, il captera plus fortement les bleus et verts, plus estompés dans la collection Mültzer. Il fonctionne en tandem avec nuances_doublees.csv, qui lui sert de référence pour définir chaque couleur.

## Notebooks de traitement du texte

* "nuextract3.ipynb" est un notebook d'execution de nuextract3. 