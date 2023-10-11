---
title: Wyszukiwanie dokumentów w języku C# .NET 

description: Wyszukuj dokumenty, w tym pliki PDF, Microsoft Office Excel, Word, PowerPoint i inne, za pośrednictwem aplikacji .NET. Wyszukuj dokumenty online za pośrednictwem aplikacji.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Przeszukuj dokumenty przy użyciu interfejsów API platformy .NET" h2="Z łatwością wyszukuj i pobieraj dane z szerokiej gamy dokumentów, obejmujących pliki Microsoft Office Word, Excel, PowerPoint i PDF, w bardzo wydajny sposób dzięki Aspose.Total dla .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

Włączenie wyszukiwania tekstu i indeksowania treści dla różnych formatów plików dokumentów umożliwia użytkownikom optymalizację produktywności, usprawnienie wyszukiwania danych i usprawnienie zarządzania informacjami w organizacjach i aplikacjach. Zwiększ funkcjonalność oprogramowania lub systemów opartych na platformie .NET, umożliwiając wyszukiwanie tekstowe w dokumentach i ustanawiając indeksy w celu wydajnego wyszukiwania informacji z różnorodnej gamy formatów plików dokumentów.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Kluczowe powody, dla których warto przeszukiwać dokumenty" %}}

1. Organizacja dokumentów
1. Wyszukiwanie informacji
1. Walidacja treści 
1. Podsumowanie treści 
1. Analiza tekstu
1. Ekstrakcja danych 
1. Indeksowanie dokumentów 


{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Wyszukaj dokumenty PDF" %}}

Używamy [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), podrzędnego API [Aspose.Total for .NET](https://products.aspose.com/total/net/) zaprojektowanego do określonych funkcji manipulacji dokumentami, a także zadań związanych z wyszukiwaniem i wyszukiwaniem treści dokumentów. Poniższy fragment kodu napisano w języku C# w celu interakcji z dokumentem PDF. Najpierw konfiguruje wzorzec wyrażenia regularnego w celu wyszukiwania w dokumencie sekwencji znaków innych niż białe znaki. Następnie uzyskuje dostęp do pierwszej strony pliku PDF i wykorzystuje TextFragmentAbsorber do wyszukiwania tekstu na tej stronie przy użyciu określonego wyrażenia regularnego. Następnie kod gromadzi odkryte fragmenty tekstu w kolekcji. Na koniec iteruje po tej kolekcji i wysyła każdy zidentyfikowany fragment tekstu do konsoli. Zasadniczo ten fragment kodu służy jako mechanizm wyodrębniania i wyświetlania określonych wzorców tekstu z dokumentu PDF. Co więcej, .NET Search API obsługuje także Microsoft [Wyszukiwanie dokumentów Worda](https://products.aspose.com/total/net/search/word/) i inne formaty.

{{% blocks/products/pf/feature-page-code h3="Kod C# do wyszukiwania dokumentów PDF" %}}

{{< gist "aspose-com-gists" "3c806eb023f399cd402ab922a247f2d0" "pdf-document-search.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}