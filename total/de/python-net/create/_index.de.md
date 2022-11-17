---
title: Datei mit Python erstellen 

description: Erstellen Sie Text- und Microsoft Word-Dokumente, ohne Microsoft Office zu installieren 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Erstellen Sie Dokumente mit Python" h2="Erstellen Sie Text- und Microsoft Word DOCX-, DOC-Dateien in Python-Anwendungen, ohne Microsoft Office<sup>&reg;</sup> zu installieren." >}}

{{% blocks/products/pf/feature-page-summary %}}
Das Speichern von Daten ist die Grundlage jeder Softwareanwendung, abhängig von der Art der Anwendung. Speicherort können die Datenbank, XML, JSON, Textdateien, Excel-Berichte oder Microsoft Word-Dokumente sein. Datei-E/A ist Teil jeder Sprache und die meisten Sprachen, einschließlich Python, unterstützen das Schreiben von Daten in Textdateien. Betrachten wir die Python-Sprache. Schreiben vorhandener Textdateien mit Python. Es bietet eine Methode zum Öffnen, Schreiben und Schließen für diese Aufgaben. Öffnen Sie zunächst die Datei mit dem entsprechenden Dateipfad und fügen Sie die Funktion als Argumente hinzu oder schreiben Sie sie. Schreiben Sie dann den erforderlichen Text in die Datei und schließen Sie die Datei schließlich mit der Methode close (). 

Zum Erstellen von Microsoft Word-Dokumenten mit Python verwenden wir das [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/)-APIs-Paket, das die [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)-API als Teil seines Pakets enthält. Diese API bietet eine vollständige Dokumentenautomatisierungslösung für Rechnungen, Berichte und technische Artikel. Verfahren zur Erstellung von Word-Dokumenten, das unten aufgeführt ist.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="So erstellen Sie eine Textdatei mit Python" %}}

Das Erstellen und Schreiben von Textdateien ist einfach. Python stellt die Methode open() mit drei Parametern bereit und muss einen der Parameter zusammen mit dem Dateipfad verwenden. Drei Parameter sind "x", "a" und "w". Durch die Angabe von "x" wird eine neue Datei erstellt, aber es wird ein Fehler ausgegeben, falls die Datei bereits vorhanden ist. Durch die Angabe von "a" wird eine neue Textdatei erstellt, falls nicht vorhanden, und falls vorhanden, wird der Inhalt am Ende angehängt. Wenn Sie schließlich "w" angeben, wird ein neues Textdokument erstellt und mit dem neuen Inhalt überschrieben, falls es bereits vorhanden ist.

{{% blocks/products/pf/feature-page-code h3="Python - Textdatei erstellen" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-text-file-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Erstellen Sie Microsoft Word-Dokumente" %}}

Die Total Python Word API verfügt über mehrere Funktionen, darunter das Erstellen von Microsoft Word-Dateien, das Einfügen von Bildern und Text in Dokumente, das Hinzufügen von Tabellen und Listen in den Dateien sowie das einfache Ändern vorhandener Dokumente. Um einen Microsoft Word-Dokumentprozess zu erstellen, erstellen Sie das Objekt der [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)- und [DocumentBuilder](https://reference.aspose.com/words/python-net/aspose.words/documentbuilder/)-Klassen. Fügen Sie den gewünschten Text, Absatz, Listen und Tabellen innerhalb des Dokuments hinzu und speichern Sie es schließlich.

{{% blocks/products/pf/feature-page-code h3="Python - Erstellen Sie Microsoft Word-Dokumente" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-word-files-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}