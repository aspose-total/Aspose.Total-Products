---
title: Twórz i aktualizuj pliki Microsoft Excel za pomocą Pythona 
url: /pl/python-java/create/
description: Twórz raporty arkuszy Microsoft Excel bez instalowania pakietu Microsoft Office 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Twórz raporty Excel za pomocą Pythona" h2="Twórz i aktualizuj dokumenty Microsoft Excel SpreadSheets XLS, XLSX w aplikacjach Pythona bez instalowania pakietu Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) to API Pythona do tworzenia, czytania i pisania dokumentów w formatach Microsoft Excel, w tym XLS i XLSX. Ten interfejs API jest częścią pakietu [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/). Co więcej, Develpors może z łatwością napisać kod do wstawiania danych, obrazów, wykresów, tabel przestawnych w arkuszach roboczych i wielu innych funkcji. Python API obsługuje również funkcje, takie jak ustawianie różnych [Formuły](https://docs.aspose.com/cells/python-java/supported-formula-functions/), konwertowanie tekstu na kolumny, inteligentny znacznik i opcje formuł dynamicznych. Poniżej znajduje się kilka przykładowych kodów do tworzenia i modyfikowania arkuszy kalkulacyjnych.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Jak tworzyć pliki Excela za pomocą Pythona" %}}

API ASSOSE.CELLS udostępnia klasę Workbook, która obsługuje tworzenie plików. Proces jest prosty. Utwórz obiekt klasy Workbook i uzyskaj dostęp do odpowiedniego arkusza roboczego, podając jego indeks. Użyj metody putValue, aby dodać zawartość do wybranej komórki, a na koniec wywołaj metodę save(), aby zapisać dokument o określonej nazwie.

{{% blocks/products/pf/feature-page-code h3="Kod 1 - Utwórz prosty plik Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="Kod 2 - Wstaw obrazy w dokumentach programu Microsoft Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Jak zaktualizować pliki Microsoft Excel za pomocą Pythona?" %}}

Proces tworzenia i aktualizacji pliku Excel jest prawie taki sam, z wyjątkiem jedynej różnicy. Różnica polega na tym, że podczas procesu tworzenia tworzony jest obiekt Pusty skoroszyt, podczas gdy podczas procesu aktualizacji potrzebny jest istniejący plik Excel. Więc przekaż istniejący plik jako parametr do klasy Workbook. Reszta procedura jest taka sama

{{% blocks/products/pf/feature-page-code h3="Kod 3 — Zaktualizuj dokumenty programu Microsoft Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}