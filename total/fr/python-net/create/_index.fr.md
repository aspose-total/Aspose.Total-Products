---
title: Créer un fichier à l'aide de Python 
url: /fr/python-net/create/
description: Créez des documents texte et Microsoft Word sans installer Microsoft Office 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Créer des documents à l'aide de Python" h2="Créez des fichiers texte et Microsoft Word DOCX, DOC dans les applications Python sans installer Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Le stockage des données est la base de toute application logicielle en fonction de la nature de l'application. L'emplacement de stockage peut être la base de données, XML, JSON, des fichiers texte, des rapports Excel ou des documents Microsoft Word. Les E/S de fichiers font partie de n'importe quel langage et la plupart des langages, y compris Python, prennent en charge l'écriture de données dans des fichiers texte. Considérons le langage Python. En écrivant des fichiers texte existants à l'aide de Python, il fournit une méthode d'ouverture, d'écriture et de fermeture pour ces tâches. Ouvrez d'abord le fichier avec le chemin de fichier approprié et ajoutez ou écrivez la fonctionnalité en tant qu'arguments. Ensuite, écrivez le texte requis dans le fichier et fermez enfin le fichier en utilisant la méthode close (). 

Pour créer des documents Microsoft Word à l'aide de Python, nous utilisons le package d'API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) qui contient l'API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) dans son package. Cette API fournit une solution complète d'automatisation des documents pour les factures, les rapports et les articles techniques. Procédure de création de document Word répertoriée ci-dessous.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Comment créer un fichier texte avec Python" %}}

Créer et écrire dans des fichiers texte est simple. Python fournit la méthode open() avec trois paramètres et doit utiliser l'un des paramètres avec le chemin du fichier. Trois paramètres sont "x", "a" et "w". En fournissant "x", un nouveau fichier sera créé mais génère une erreur au cas où le fichier existe déjà. En fournissant "a", un nouveau fichier texte sera créé s'il n'existe pas et s'il existe, le contenu sera ajouté à la fin. Et enfin, en fournissant "w", un nouveau document texte sera créé et remplacé par le nouveau contenu au cas où il existerait déjà.

{{% blocks/products/pf/feature-page-code h3="Python - Créer un fichier texte" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-text-file-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Créer des documents Microsoft Word" %}}

Total Python Word API possède plusieurs fonctionnalités, notamment la création de fichiers Microsoft Word, l'insertion d'images et de texte dans des documents, l'ajout de tableaux et de listes dans les fichiers ainsi que la modification de documents existants en toute simplicité. Pour créer un processus de document Microsoft Word, créez l'objet des classes [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) et [DocumentBuilder](https://reference.aspose.com/words/python-net/aspose.words/documentbuilder/). Ajoutez le texte, le paragraphe, les listes et les tableaux requis dans le document et enfin enregistrez-le.

{{% blocks/products/pf/feature-page-code h3="Python - Créer des documents Microsoft Word" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-word-files-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}