---
title: Python を使用してファイルを作成する 

description: Microsoft Office をインストールせずにテキストおよび Microsoft Word ドキュメントを作成する 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用してドキュメントを作成する" h2="Microsoft Office<sup>&reg;</sup> をインストールせずに、Python アプリケーション内でテキストおよび Microsoft Word DOCX、DOC ファイルを作成します。" >}}

{{% blocks/products/pf/feature-page-summary %}}
データの保存は、アプリケーションの性質に応じて、ソフトウェア アプリケーションの基本です。 保存場所は、データベース、XML、JSON、テキスト ファイル、Excel レポート、または Microsoft Word ドキュメントです。 ファイル I/O はあらゆる言語の一部であり、Python を含むほとんどの言語はテキスト ファイルへのデータの書き込みをサポートしています。 Python 言語について考えてみましょう。 Python を使用して既存のテキスト ファイルを書き込みます。このタスクのための open、write、および close メソッドを提供します。 まず、関連するファイル パスを指定してファイルを開き、機能を引数として追加または書き込みます。 次に、必要なテキストをファイルに書き込み、最後に close() メソッドを使用してファイルを閉じます。 

Python を使用して Microsoft Word ドキュメントを作成するには、パッケージの一部として [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API を含む [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API パッケージを使用します。 この API は、請求書、レポート、および技術記事の完全なドキュメント自動化ソリューションを提供します。 ワード文書の作成手順は以下の通りです。

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Python を使用してテキスト ファイルを作成する方法" %}}

テキスト ファイルの作成と書き込みは簡単です。 Python は 3 つのパラメーターを持つ open() メソッドを提供し、ファイル パスと共にパラメーターの 1 つを使用する必要があります。 3 つのパラメーターは、"x"、"a"、および "w" です。 「x」を指定すると、新しいファイルが作成されますが、ファイルが既に存在する場合はエラーがスローされます。 "a" を指定すると、存在しない場合は新しいテキスト ファイルが作成され、存在する場合は最後にコンテンツが追加されます。 最後に "w" を指定すると、新しいテキスト ドキュメントが作成され、既に存在する場合は新しいコンテンツで上書きされます。

{{% blocks/products/pf/feature-page-code h3="Python - テキスト ファイルの作成" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-text-file-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft Word ドキュメントの作成" %}}

Total Python Word API には、Microsoft Word ファイルの作成、ドキュメント内への画像やテキストの挿入、ファイル内へのテーブルやリストの追加、既存のドキュメントの簡単な変更など、複数の機能があります。 Microsoft Word 文書プロセスを作成するには、[Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスと [DocumentBuilder](https://reference.aspose.com/words/python-net/aspose.words/documentbuilder/) クラスのオブジェクトを作成します。 ドキュメント内に必要なテキスト、段落、リスト、および表を追加し、最後に保存します。

{{% blocks/products/pf/feature-page-code h3="Python - Microsoft Word ドキュメントの作成" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-word-files-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="作成">}}