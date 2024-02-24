---
title: Konwertuj HTML stron internetowych na obrazy za pomocą C#
description: Zeskrobuj strony internetowe i eksportuj HTML do obrazów. Twórz aplikacje .NET, aby zgarniać dane ze stron internetowych do formatu JPEG, PNG, GIF, BMP itp. 
family: total
platformtag: net
feature: conversion
informat: WEB
outformat: IMAGE
otherformats: WORD EXCEL POWERPOINT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwertuj strony internetowe na obrazy za pomocą C#" h2="Wyodrębnij dane witryny ze stron internetowych HTML. Konwertuj HTML na obrazy JPG, GIF, PNG, BMP w aplikacjach .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">Dlaczego warto konwertować strony internetowe na obrazy?</h2>
<p>Konwertowanie stron internetowych na obrazy może być przydatne w różnych sytuacjach. Jest to wspólne wymaganie dla wielu aplikacji. W niektórych scenariuszach konieczne jest przechwycenie całej strony internetowej jako obrazu, w tym części niewidocznych na ekranie. Może to być przydatne do generowania podglądów stron internetowych, przechwytywania paragonów i faktur lub archiwizowania stron internetowych do celów prawnych. Może być używany do tworzenia zrzutów ekranu stron internetowych w celach dokumentacyjnych lub testowych. Może być również używany do tworzenia miniatur lub podglądów stron internetowych do wykorzystania w wynikach wyszukiwania lub galeriach obrazów. Niezależnie od tego, czy tworzysz aplikację klasyczną, czy aplikację internetową, dostępnych jest wiele opcji konwertowania stron internetowych na obrazy przy użyciu języka C#.</p><br />

<p>Konwertowanie stron internetowych na obrazy przy użyciu języka C# może zapewnić kilka korzyści, w tym:</p><br />
<ul>
<li>Poprawiona dostępność: Obrazy mogą być łatwiejsze do odczytania i zrozumienia dla osób z wadami wzroku lub innymi niepełnosprawnościami.</li>
<li>Zwiększona mobilność: Obrazy można łatwo udostępniać lub osadzać w innych dokumentach lub aplikacjach.</li>
</ul>
<p>Konwertowanie stron internetowych na obrazy przy użyciu języka C# może również wiązać się z pewnymi wyzwaniami, takimi jak:</p><br />
<ul>
<li>Ograniczona obsługa formatu: Niektóre interfejsy API lub narzędzia mogą nie obsługiwać wszystkich formatów obrazów lub mogą mieć ograniczenia dotyczące rozmiaru lub rozdzielczości obrazów wyjściowych.</li>
<li>Problemy ze zgodnością: Niektóre strony internetowe mogą nie wyświetlać się poprawnie we wszystkich przeglądarkach lub mogą wymagać określonych ustawień lub wtyczek do prawidłowego wyświetlania.</li>
</ul>
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak konwertować strony internetowe na obrazy za pomocą C#?" %}}
Aby przekonwertować strony sieci Web na obrazy przy użyciu języka C#, można użyć interfejsu API Aspose.HTML dla platformy .NET, który udostępnia tę funkcję do konwertowania stron HTML na formaty obrazów, w tym JPEG, PNG i TIFF.</p>

1. Załaduj dokument HTML za pomocą jednego z konstruktorów dostępnych w [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/). Możesz załadować kod HTML z pliku, kodu HTML, strumienia lub adresu URL.
2. Utwórz nową instancję [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) i ustaw właściwość ImageFormat na JPEG. Domyślnie właściwość Format jest ustawiona na PNG.
3. Wykorzystaj [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) metodę z klasy Converter, aby zapisać dokument HTML jako plik JPEG. Będziesz musiał podać HTMLDocument, ImageSaveOptions i ścieżkę pliku wyjściowego jako parametry metody ConvertHTML().
4. Wynikowy plik JPEG zostanie zapisany w określonej ścieżce pliku.
 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące usuwania treści z sieci i konwersji obrazów" %}}
Zainstaluj z linii poleceń jako ```nuget install Aspose.Total``` lub zainstaluj bezpośrednio z konsoli Menedżera pakietów Visual Studio.

Dwa [Aspose.Total for .NET](https://products.aspose.com/total/net/) potomne API, [Aspose.HTML for .NET](https://products.aspose.com/html/net/) zostanie zintegrowany.

Ewentualnie pobierz instalator MSI offline lub biblioteki DLL w pliku ZIP z [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "convert-web-pages-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}