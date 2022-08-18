# VMware
このレポジトリではVMware関連のナレッジをまとめています。

## 目次
### Tanzu Kubernetes Grid Multicloud(TKGm)
- [HPE ProLiantにインストール](tkgm/installation)  
Tanzu Kubernetes Grid(TKG)のインストール方法

- [使ってみる01](tkgm/instruction01)  
NginxのデプロイやPVの宣言、NSXがない環境でのMetal LBやIngress Controller導入などについて

- [HPE Nimble Storageと連携してみる](tkgm/nimble)  
HPE Storageと連携方法について

- [トラブルシュート系 ](tkgm/trouble_shoot)  
検証の際に出会った問題等

### vSphere with Tanzu(TKGS)
- [基本セットアップ](tkgs/installation)  
  初期セットアップ手順
- [Supervisor Cluster作成してみる](tkgs/s_cluster)  
  管理用Kubernetes Clusterの作成手順
- [k8s Cluster作成してみる](tkgs/k8s_cluster)  
  ユーザー用Kubernetes Clusterの作成手順
- [Nvidia AI Enterprise環境をセットアップしてみる](tkgs/nvidia-ai-enterprise/installation)  
  Nvidia AI Enterprise環境にするための初期セットアップ手順
- [GPUをアサインしてみる](tkgs/nvidia-ai-enterprise/k8s)  
  Nvidia AI Enterprise環境でk8sクラスタにGPUのアサイン手順

