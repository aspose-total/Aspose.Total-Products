---
title: Python で XPS を EML に変換する
description: Microsoft Word や Outlook を使用せずに、Python アプリケーション内で XPS を EML に保存します。

family: total
platformtag: Python
feature: conversion
informat: XPS
outformat: EML
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して XPS を EML に変換する" h2="Microsoft Word<sup>&reg;</sup> または Outlook をインストールせずに、Python アプリケーションで XPS から EML への変換。" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に XPS から EML への変換機能を追加しようとしている Python 開発者は誰ですか? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 これは、電子メール、画像、Microsoft Word 形式など、さまざまな形式を扱うさまざまな API の完全なパッケージです。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) パッケージの一部である [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) および [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API により、Python を使用してこの変換が容易になります。 これは 2 段階のプロセスです。最初に XPS ファイルをロードし、[Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を介して HTML にレンダリングします。 次に、[Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) を使用して変換された HTML を読み込み、EML 形式に保存します。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で XPS を EML に変換する方法" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスを使用してソース XPS ファイルを開きます。
- 出力 HTML ファイル パスと関連する HTML 保存オプションをパラメーターとして指定して、`save` メソッドを呼び出します。 したがって、XPS ファイルは指定されたパスで HTML に変換されます。
- MailMessage.load を使用して、保存した HTML ファイルをロードします。
- 関連するファイル パスを指定して save メソッドを呼び出します。最後にXPSが変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- XPS から EML への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI から直接参照 ([Aspose.Words](https://pypi.org/project/aspose-words/) および [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- または、次の pip コマンド ```pip install aspose.words``` および ```pip install Aspose.Email-for-Python-via-NET``` を使用します。 
- さらに、Microsoft Windows または Linux ベースの OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) および [Email](https://docs.aspose.com/email/python-net/system-requirements/) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、ステップバイステップの手順に従ってください [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PythonでXPSをEMLに保存" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

XPS から EML への変換は、Python API を使用して固定レイアウト文書を、メッセージの保存、交換、アーカイブに広く利用されている標準的なメールメッセージファイルに変換します。これは、文書内容を下流の通信、レビュー、またはコンプライアンス用途のために、ポータブルなメール形式で保持する必要がある場合に特に有用です。

自動化の観点から、XPS から EML へのワークフローは、文書駆動型メッセージングの一貫性を向上させ、手動での準備作業を削減し、文書システム、メール処理ツール、アーカイブ環境間のスケーラブルな統合をサポートします。

{{% blocks/products/pf/agp/feature-section-col title="主なユースケース" %}}

* **ポータブルメールメッセージ作成**  
  XPS ドキュメントを EML ファイルに変換し、互換システム間で標準化された保存と転送を実現します。

* **メール形式でのドキュメントアーカイブ**  
  規制された保存と将来の検索のために、ドキュメント内容をメールメッセージとして保持するのに役立ちます。

* **相互運用可能なメッセージ交換**  
  標準メールファイル形式をサポートするプラットフォーム間で、変換されたメッセージの移動を容易にします。

* **レビューおよび承認フロー**  
  ドキュメント内容を検証や承認のためにメッセージファイルとして共有する必要があるワークフローをサポートします。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

* **バッチドキュメントからメッセージへの変換**  
  自動ジョブは大量の XPS ファイルを EML に変換し、下流での一貫した処理を実現します。

* **システム生成レコードのパッケージ化**  
  アプリケーションは生成された XPS 出力を EML ファイルに変換し、レコード管理ワークフローの一部として使用できます。

* **メールアーカイブの取り込み**  
  変換された EML ファイルは、プログラムでアーカイブやインデックスシステムにルーティングされ、保存に利用できます。

* **ワークフローベースのメッセージエクスポート**  
  ドキュメントが処理の特定段階に達したとき、動的パイプラインが EML 出力を生成できます。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}