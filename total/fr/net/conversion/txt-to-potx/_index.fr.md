---
title: Convertir TXT en POTX via C# .NET ou avec le convertisseur en ligne gratuit
description: Convertissez des documents Word en fichiers PowerPoint potx avec C#. Convertissez plusieurs fichiers dans ASP.NET ou d'autres applications .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir TXT en POTX en utilisant C# ou en ligne" h2="Créez des applications de conversion Microsoft Word TXT vers PowerPoint POTX sur les plates-formes .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="POTX" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Comment convertir TXT en POTX en utilisant C#" %}}

Afin d'automatiser le processus pour tous les fichiers txt Word vers la conversion par lots de présentation PowerPoint potx, nous utiliserons [Aspose.Words pour .NET](https://products.aspose.com/words/net) et [Aspose.Slides pour les API .NET](https://products.aspose.com/slides/net). Le premier est une API de traitement de texte pour traiter ou manipuler des documents Microsoft Word. Alors que ce dernier est une API de manipulation de présentation qui vous permet de créer ou de modifier des diapositives Microsoft PowerPoint. Les deux API font partie du package [Aspose.Total pour .NET](https://products.aspose.com/total/net). Vous pouvez directement [télécharger](https://releases.aspose.com/) à partir de Nuget ou utiliser les commandes suivantes à partir de la console du gestionnaire de packages.

{{% blocks/products/pf/agp/code-block title="Commande de la console du gestionnaire de packages" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour convertir TXT en POTX via C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Ajouter la référence de Aspose.Total pour .NET
1. Chargez le fichier TXT à l'aide de la classe [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document)
1. Enregistrez le document TXT au format HTML
1. Créer un objet [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. Importez du contenu HTML dans le cadre de texte de n'importe quelle forme de diapositive dans la présentation
1. Enregistrez le document en utilisant [Aspose.Slides.Presentation.Save("output.potx", SaveFormat.Potx)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec les plates-formes .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin.
- Environnement de développement comme Microsoft Visual Studio.
- Aspose.Words pour .NET &amp; Aspose.Slides pour les DLL .NET ou Aspose.Total pour les DLL .NET référencées dans votre projet.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Cet exemple de code montre comment convertir un TXT en POTX à l'aide de C#" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word TXT file
Aspose.Words.Document txt = new Aspose.Words.Document("sourceWordFile.txt");

// Save TXT file to HTML 
txt.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages TXT documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to POTX.

using (Presentation potx = new Presentation()){

	// Access the default first slide of presentation
	ISlide slide = pres.Slides[0];

	// Adding the AutoShape to accomodate the HTML content 
	// Adjust it as of your need
	IAutoShape ashape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, pres.SlideSize.Size.Width - 20, pres.SlideSize.Size.Height - 10);

	ashape.FillFormat.FillType = FillType.NoFill;

	// Adding text frame to the shape
	ashape.AddTextFrame("");

	// Clearing all paragraphs in added text frame
	ashape.TextFrame.Paragraphs.Clear();

	// Loading the HTML file using stream reader
	TextReader tr = new StreamReader("filepath\\test.html");

	// Adding text from HTML stream reader in text frame
	ashape.TextFrame.Paragraphs.AddFromHtml(tr.ReadToEnd());

	// Save the POTX Presentation
	potx.Save("filepath\\pres.potx", Aspose.Slides.Export.SaveFormat.Potx);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Convertisseur en ligne pour TXT en POTX</h3>

<iframe title="Outil en ligne de conversion potx en txt" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=potx&from=txt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Application gratuite pour convertir TXT en POTX" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant POTX file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->
{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier TXT en POTX par programmation : cas d'utilisation" %}}
Les fichiers de texte (TXT) sont devenue une composante essentielle de la communication numérique, offrant un format de texte brut facilement partagé et accessible. Cependant, lorsque l'on s'agit de créer des présentations visuellement attractives, les fichiers POTX prennent le pas. La conversion des fichiers de texte en POTX est nécessaire pour débloquer pleinement la capacité de présentation de votre document.

Cette conversion vous permet :

*   **Business Presentations** : Convertir les fichiers de texte pour créer des présentations commerciales engageantes, munies de slides, images et contenu multimédia.
*   **Recherche Universitaire** : Utiliser POTX pour créer des documents de recherche universitaire de niveau professionnel, comme des thèses et des dissertations, dotés de tables, figures et graphiques.
*   **Matériel de Marketing** : Convertir les fichiers de texte en matériel de marketing efficace, tels que des scripts commerciaux, des descriptions de produits et du contenu publicitaire.
*   **Contenu Éducatif** : Créer du contenu éducatif interactif, comme des plans de leçon, des quiz et des évaluations, dans la format POTX.
*   **Documentations Techniques** : Utiliser POTX pour créer des documents techniques complets, comprenant les manuels d'utilisateur, les instructions et la documentation système.

En convertissant vos fichiers de texte en POTX, vous pouvez élévar la visibilité visuelle de vos documents, les rendant plus engageants et efficaces à des fins diverses.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Questions fréquemment posées</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Comment puis-je convertir TXT en POTX en ligne ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">L'application en ligne pour la conversion TXT est intégrée ci-dessus. Pour utiliser cette application, vous pouvez ajouter votre fichier TXT en le faisant glisser et en le déposant dans la zone blanche désignée ou en cliquant à l'intérieur de la zone pour importer le document. Ensuite, appuyez sur le bouton Convertir pour démarrer le processus de conversion. Une fois la conversion TXT en POTX terminée, vous pouvez télécharger votre fichier nouvellement converti en un seul clic, et il sera disponible sous la forme d'un fichier POTX.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Combien de temps faut-il pour convertir TXT ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Ce convertisseur en ligne fonctionne rapidement mais dépend principalement de la taille du fichier TXT à convertir. Pour les petits fichiers TXT, la conversion en POTX peut être effectuée en quelques secondes. Cependant, si vous avez intégré le code de conversion dans une application .NET, la vitesse de conversion dépendra de la qualité de l'optimisation de votre application pour le processus de conversion.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Est-il sûr de convertir TXT en POTX en utilisant le convertisseur gratuit Aspose.Total ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Bien sûr! Une fois la conversion TXT en POTX terminée, le lien de téléchargement du fichier POTX nouvellement converti sera instantanément disponible. Cela garantit également la sécurité du processus de conversion, car tous les fichiers téléchargés, y compris les fichiers TXT, sont entièrement sécurisés et seront supprimés du système après 24 heures. De plus, les liens de téléchargement cesseront de fonctionner après cette période, garantissant la confidentialité et la protection de vos fichiers. L'application intégrée est gratuite et conçue à des fins de test afin que les utilisateurs puissent évaluer les résultats avant d'intégrer le code dans leurs projets.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quel navigateur dois-je utiliser pour convertir TXT ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Vous pouvez utiliser n'importe quel navigateur Web moderne, tel que Google Chrome, Firefox, Opera ou Safari, pour la conversion TXT en POTX en ligne. Toutefois, si vous développez une application de bureau, l'API Aspose.Total TXT Conversion est recommandée pour un traitement fluide et efficace.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}