---
ms.openlocfilehash: 733bfb4740f3f274ba9ebb396749d313907d5fa6
ms.sourcegitcommit: 1bb00d2f4343e73ae8d58668f02297a3cf10a4c1
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/15/2019
ms.locfileid: "63870369"
---
.NET Framework 4.7 より、この方法では <xref:System.Security.Authentication.SslProtocols.None> を使用して認証を行うため、オペレーティング システムが使用する最適なプロトコルを選択し、セキュリティで保護されていないプロトコルをブロックできるようになります。 .NET Framework 4.6 (および最新のセキュリティ パッチがインストールされている .NET Framework 4.5) で許可されている TLS /SSL プロトコルのバージョンは 1.2、1.1 および 1.0 です (ただし、Windows のレジストリを編集して強力な暗号化を無効にしていない場合に限ります)。
