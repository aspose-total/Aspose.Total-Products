---
title: Python で ODT を EML に変換する
description: Microsoft Word や Outlook を使用せずに、Python アプリケーション内で ODT を EML に保存します。

family: total
platformtag: Python
feature: conversion
informat: ODT
outformat: EML
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して ODT を EML に変換する" h2="Microsoft Word<sup>&reg;</sup> または Outlook をインストールせずに、Python アプリケーションで ODT から EML への変換。" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に ODT から EML への変換機能を追加しようとしている Python 開発者は誰ですか? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 これは、電子メール、画像、Microsoft Word 形式など、さまざまな形式を扱うさまざまな API の完全なパッケージです。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) パッケージの一部である [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) および [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API により、Python を使用してこの変換が容易になります。 これは 2 段階のプロセスです。最初に ODT ファイルをロードし、[Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を介して HTML にレンダリングします。 次に、[Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) を使用して変換された HTML を読み込み、EML 形式に保存します。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で ODT を EML に変換する方法" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスを使用してソース ODT ファイルを開きます。
- 出力 HTML ファイル パスと関連する HTML 保存オプションをパラメーターとして指定して、`save` メソッドを呼び出します。 したがって、ODT ファイルは指定されたパスで HTML に変換されます。
- MailMessage.load を使用して、保存した HTML ファイルをロードします。
- 関連するファイル パスを指定して save メソッドを呼び出します。最後にODTが変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- ODT から EML への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI から直接参照 ([Aspose.Words](https://pypi.org/project/aspose-words/) および [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- または、次の pip コマンド ```pip install aspose.words``` および ```pip install Aspose.Email-for-Python-via-NET``` を使用します。 
- さらに、Microsoft Windows または Linux ベースの OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) および [Email](https://docs.aspose.com/email/python-net/system-requirements/) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、ステップバイステップの手順に従ってください [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PythonでODTをEMLに保存" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

ODT から EML への変換は、OpenDocument Text ファイルを標準的なメールメッセージ形式に変換し、保存、転送、またはアーカイブ目的でメッセージ構造を保持します。これは、文書の内容を通信や記録管理のためのメールアーティファクトとしてパッケージ化する必要がある場合に役立ちます。

自動化環境では、ODT から EML への変換は、文書からメッセージへのワークフロー、メールアーカイブプロセス、そして大量コンテンツの変換をサポートします。Python API を使用すると、これらのタスクをプログラム的に、かつ大規模な文書セット全体で一貫して実行できます。

{{% blocks/products/pf/agp/feature-section-col title="主な使用例" %}}

* **メールメッセージ作成**  
  文書の内容をポータブルなメールメッセージ形式に変換します。

* **アーカイブパッケージング**  
  標準化された構造で、通信準備ができたコンテンツの保存を支援します。

* **ワークフローハンドオフ**  
  メッセージベースの交換を使用するシステム向けに文書を準備します。

* **コンテンツ配布の準備**  
  下流の配信やレビューをメールオブジェクトとして可能にします。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

* **自動メッセージパッケージング**  
  Python ワークフローは、文書を保存または転送用の EML ファイルに変換できます。

* **アーカイブパイプライン**  
  ODT コンテンツは、長期的な通信記録のために自動的に変換できます。

* **大量メールアーティファクト作成**  
  大規模な文書コレクションは、バッチジョブで EML 形式に処理できます。

* **システム間交換**  
  自動化プロセスは、メッセージ指向の統合で EML 出力を使用できます。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}