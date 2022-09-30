# VMware
このレポジトリではNVIDIA AI Enterprise関連のナレッジをまとめています。

## 目次
### NVIDIA AI Enterprise(NVAIE)
- [NVAIE対応のTanzu整理](instruction)  
  NVIDIA AI Enterpriseに対応しているTanzu製品の整理

- [TKGs構築① - vDS作成](installation01)  
NginxのデプロイやPVの宣言、NSXがない環境でのMetal LBやIngress Controller導入などについて

- [TKGs構築② - 共有データストアの作成](installation02)<br>
クラスターを構成する各ホストがアクセス可能な共有データストアを用意

- [TKGs構築③ - ロードバランサ用のHA Proxyの用意](installation03)<br>
NSX-Tによるロードバランサーの代わりとなるHA Proxy仮想アプライアンスをデプロイ

- [TKGs構築④ - コンテンツライブラリの用意＆ストレージポリシーの有効化](installation04)<br>
Tanzu K8s Grid OVF用のコンテンツライブラリの事前作成

- [TKGs構築⑤ - ワークロードの管理の有効化](installation05)<br>
ワークロードを有効化し、Supervisor Clusterを作成

- [TKGs構築⑥ - SuperVisor Clusterの作成後の作業](installation06)<br>
名前空間を作成してDeveloper側に引き渡す前までの作業

### MIG(Multi Instance GPU)
- [MIGの有効化](mig-enabled)  
  MIGの有効化手順について、GPU Instance、Compute Instance作成

### NVIDIA NGC(AI Development Catalog)
- [NGCアカウントの登録](ngc-register)  
  NPNアカウントの登録、API Keyの取得方法について
