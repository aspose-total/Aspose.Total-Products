---
title: Python で PDF を EML に変換する
description: Microsoft Word や Outlook を使用せずに、Python アプリケーション内で PDF を EML に保存します。

family: total
platformtag: Python
feature: conversion
informat: PDF
outformat: EML
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して PDF を EML に変換する" h2="Microsoft Word<sup>&reg;</sup> または Outlook をインストールせずに、Python アプリケーションで PDF から EML への変換。" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に PDF から EML への変換機能を追加しようとしている Python 開発者は誰ですか? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 これは、電子メール、画像、Microsoft Word 形式など、さまざまな形式を扱うさまざまな API の完全なパッケージです。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) パッケージの一部である [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) および [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API により、Python を使用してこの変換が容易になります。 これは 2 段階のプロセスです。最初に PDF ファイルをロードし、[Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を介して HTML にレンダリングします。 次に、[Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) を使用して変換された HTML を読み込み、EML 形式に保存します。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で PDF を EML に変換する方法" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスを使用してソース PDF ファイルを開きます。
- 出力 HTML ファイル パスと関連する HTML 保存オプションをパラメーターとして指定して、`save` メソッドを呼び出します。 したがって、PDF ファイルは指定されたパスで HTML に変換されます。
- MailMessage.load を使用して、保存した HTML ファイルをロードします。
- 関連するファイル パスを指定して save メソッドを呼び出します。最後にPDFが変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- PDF から EML への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI から直接参照 ([Aspose.Words](https://pypi.org/project/aspose-words/) および [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- または、次の pip コマンド ```pip install aspose.words``` および ```pip install Aspose.Email-for-Python-via-NET``` を使用します。 
- さらに、Microsoft Windows または Linux ベースの OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) および [Email](https://docs.aspose.com/email/python-net/system-requirements/) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、ステップバイステップの手順に従ってください [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PythonでPDFをEMLに保存" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Python API を使用した PDF から EML への変換は、PDF ドキュメントを標準的なメールメッセージファイルに変換し、保存、共有、または互換性のあるメールシステムにインポートできるようにします。これは、コミュニケーション、バックアップ、相互運用性のために、メッセージ指向の形式でドキュメント内容を保存するのに有用です。

PDF から EML への変換を自動化することで、ドキュメントをメールアーカイブに取り込んだり、自動メッセージフローや大量処理システムを実現したりして、業務効率が向上します。構造化されたメールファイルの出力が必要なスケーラブルなデータ交換をサポートします。

{{% blocks/products/pf/agp/feature-section-col title="主要な使用例" %}}

* **メールファイル生成**  
  PDF ドキュメントを EML ファイルに変換し、保存、転送、または後で配信できるようにします。

* **アーカイブワークフロー**  
  記録保持のために、標準的なメール互換形式でドキュメント内容を保存します。

* **メールシステム統合**  
  PDF 由来のコンテンツをメールクライアントや処理システムにインポートできるように準備します。

* **コンテンツ再利用**  
  PDF 情報をデジタルコミュニケーションワークフロー用の構造化メッセージファイルに再フォーマットします。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

* **バッチメールファイル作成**  
  自動化スクリプトは大量の PDF を EML ファイルに変換し、下流での使用に利用できます。

* **アーカイブ取り込みパイプライン**  
  システムは変換された EML 出力をストレージやコンプライアンスリポジトリにルーティングできます。

* **自動メッセージ準備**  
  PDF コンテンツはプログラムでメールファイルとして準備され、後でレビューや送信に利用できます。

* **ドキュメントからメッセージへの変換**  
  Python ワークフローは受信 PDF を動的に変換し、再利用可能な EML 資産にします。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}