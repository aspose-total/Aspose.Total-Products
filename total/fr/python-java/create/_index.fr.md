---
title: Créer et mettre à jour des fichiers Microsoft Excel à l'aide de Python 
url: /fr/python-java/create/
description: Créer des rapports de feuille de calcul Microsoft Excel sans installer Microsoft Office 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Créer des rapports Excel à l'aide de Python" h2="Créez et mettez à jour des feuilles de calcul Microsoft Excel XLS, XLSX dans les applications Python sans installer Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) est une API Python pour créer, lire et écrire des documents dans les formats Microsoft Excel, y compris XLS et XLSX. Cette API fait partie du package [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/). De plus, les développeurs peuvent facilement écrire du code pour insérer des données, des images, des graphiques, des tableaux croisés dynamiques dans des feuilles de calcul et de nombreuses autres fonctionnalités. L'API Python prend également en charge des fonctionnalités telles que la définition de divers [Formules](https://docs.aspose.com/cells/python-java/supported-formula-functions/), la conversion de texte en colonnes, le marqueur intelligent et les options de formule dynamique. Vous trouverez ci-dessous quelques exemples de codes pour créer et modifier des feuilles de calcul.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Comment créer des fichiers Excel avec Python" %}}

L'API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) fournit la classe Workbook qui gère la création de fichiers. Le processus est simple. Créez l'objet de classe Workbook et accédez à la feuille de calcul appropriée en fournissant son index. Utilisez la méthode putValue pour ajouter le contenu dans la cellule accédée et enfin appelez la méthode save() pour enregistrer le document avec un nom spécifique.

{{% blocks/products/pf/feature-page-code h3="Code 1 - Créer un fichier Excel simple" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="Code 2 - Insérer des images dans des documents Microsoft Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Comment mettre à jour des fichiers Microsoft Excel à l'aide de Python" %}}

Le processus de création et de mise à jour du fichier Excel est presque le même, à l'exception de la seule différence. La différence est que, pendant le processus de création, l'objet Classeur vide est créé tandis que pendant le processus de mise à jour, un fichier Excel existant est nécessaire. Passez donc le fichier existant en paramètre à la classe Workbook. Reste la procédure est la même

{{% blocks/products/pf/feature-page-code h3="Code 3 - Mettre à jour les documents Microsoft Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}