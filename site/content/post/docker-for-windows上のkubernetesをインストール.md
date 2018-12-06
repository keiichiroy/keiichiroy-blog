---
title: Docker for Windows上のKubernetesをインストール
date: 2018-12-06T13:17:30.712Z
description: まずはCI/CDできるところまで(というかGitLab入れるまで)
image: /img/shipping_containers_at_clyde-1-.jpg
---
久々のKubernetes
===

新しいノートPCになってから、久しぶりにDockerをインストール。以前のマシンはなぜかHyper-Vが立ち上がらずに、Docker自体が使えなくなってしまっていたのでした(VirtualBoxとの切り替えで何かが起きたかもしれないのだけれど追い切れず)

**kube proxy** して管理用のWeb UIが見られる所までは確認。  
あとはhelm入れてGitLabを入れればOKなはず。

Helmインストール
---
こちらを参照に。  
- <https://qiita.com/nykym/items/1573ca568a80d0d01c45>
- <https://docs.helm.sh/using_helm>

コマンドはChocolateyからインストール
```
choco install helm
```

