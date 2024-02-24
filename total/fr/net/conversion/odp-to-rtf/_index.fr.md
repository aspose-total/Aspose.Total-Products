---
title: Convertir ODP en RTF via C# .NET ou avec le convertisseur en ligne gratuit
description: Convertissez des documents PowerPoint odp en fichiers rtf Word avec C#. Convertissez plusieurs fichiers dans ASP.NET ou d'autres applications .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir ODP en RTF en utilisant C# ou en ligne" h2="Créez des applications de conversion de documents Microsoft PowerPoint ODP vers Word RTF sur les plates-formes .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Comment convertir ODP en RTF en utilisant C#" %}}

Afin d'automatiser le processus de toute présentation PowerPoint odp vers la conversion par lots de fichiers rtf Word, nous utiliserons [Aspose.Slides pour .NET](https://products.aspose.com/slides/net) et [Aspose.Words pour les API .NET](https://products.aspose.com/words/net). Le premier est une API de manipulation de présentation PowerPoint qui vous permet de créer ou de modifier des diapositives Microsoft PowerPoint. Alors que ce dernier est une API de traitement de texte pour traiter ou manipuler des documents Microsoft Word. Les deux API font partie du package [Aspose.Total pour .NET](https://products.aspose.com/total/net). Vous pouvez directement [télécharger](https://releases.aspose.com/) à partir de Nuget ou utiliser les commandes suivantes à partir de la console du gestionnaire de packages.

{{% blocks/products/pf/agp/code-block title="Commande de la console du gestionnaire de packages" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour convertir ODP en RTF via C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Ajouter une référence à Aspose.Slides pour .NET et Aspose.Words pour .NET
1. Chargez la présentation PowerPoint ODP à l'aide de la classe [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. Enregistrez le document dans l'objet [MemoryStream](https://rtfs.microsoft.com/en-us/dotnet/api/system.io.memorystream?view=net-5.0)
1. Créez [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document) et initialisez-le avec MemoryStream Object
1. Enregistrez le document en utilisant [Aspose.Words.Document.Save("output.rtf", SaveFormat.Rtf)](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/3)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec les plates-formes .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin.
- Environnement de développement comme Microsoft Visual Studio.
- Aspose.Slides pour .NET et Aspose.Words pour .NET DLL référencé dans votre projet.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Cet exemple de code montre comment convertir un ODP en RTF à l'aide de C#" offSpacer="" %}}

```cs
// Load the Microsoft PowerPoint ODP file
Aspose.Slides.Presentation odp = new Aspose.Slides.Presentation("source.odp");

var stream = new MemoryStream();

odp.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// Load the content of the presentation to a Word document
var rtf = new Aspose.Words.Document(stream);
      
// Save the Word RTF document
rtf.Save("output.rtf", Aspose.Words.SaveFormat.Rtf);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Convertisseur en ligne pour ODP en RTF</h3>

<iframe title="Outil en ligne de conversion rtf en odp" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=rtf&from=odp" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Application gratuite pour convertir ODP en RTF" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant ODP file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->
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
                          <span itemprop="name"><b>Comment puis-je convertir ODP en RTF en ligne ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">L'application en ligne pour la conversion ODP est intégrée ci-dessus. Pour utiliser l'application, vous pouvez ajouter votre fichier ODP en le faisant glisser et en le déposant dans la zone désignée ou en cliquant à l'intérieur de la zone pour importer le fichier. Une fois le fichier ajouté, cliquez sur le bouton Convertir pour lancer le processus de conversion. Une fois la conversion ODP en RTF terminée, vous pouvez télécharger votre fichier nouvellement converti en un seul clic, et il sera disponible au format RTF.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Combien de temps faut-il pour convertir ODP ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">ce convertisseur en ligne est rapide, mais la vitesse de conversion ODP en RTF dépend principalement de la taille du fichier ODP à convertir. Les fichiers ODP plus petits peuvent être rendus au format RTF en quelques secondes. De plus, si vous avez intégré le code de conversion ODP en RTF dans une application .NET, la vitesse de conversion dépendra de la façon dont vous avez optimisé votre application pour le processus de conversion.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Est-il sûr de convertir ODP en RTF en utilisant le convertisseur gratuit Aspose.Total ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Bien sûr! Une fois le processus de conversion ODP en RTF terminé, le lien de téléchargement du fichier RTF converti sera instantanément disponible. Tous les fichiers téléchargés, y compris les fichiers ODP, sont supprimés du système après 24 heures et les liens de téléchargement cessent de fonctionner après cette période. Le convertisseur en ligne garantit la sécurité et la confidentialité de vos fichiers, et l'application intégrée est disponible gratuitement à des fins de test. Cela permet aux utilisateurs de vérifier le résultat avant d'intégrer le code dans leurs projets.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quel navigateur dois-je utiliser pour convertir ODP ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Vous pouvez utiliser n'importe quel navigateur Web contemporain tel que Google Chrome, Firefox, Opera ou Safari pour convertir des fichiers ODP en RTF en ligne. Toutefois, si vous créez une application de bureau, l'API Aspose.Total ODP Conversion est recommandée pour un processus de conversion fluide et transparent.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}