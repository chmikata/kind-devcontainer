# kind-devcontainer

簡単にローカルでkubernetesを動かしてみたいとう方向けのdevcontainerです。
Docker in Dockerの構成でコンテナ内でkindを使ってkubernetesのクラスタを構築できるようにしています。

コンテナ内には以下のツールが同胞されていますので、
kubernetesのクラスタを立てて、一通りの動きを確認することが可能だと思います。

- kubectl
- helm
- kind

Docker in Dockerの構成なのでイメージは共有されません。
コンテナ内でイメージの消し忘れなどが起きないように注意してください。
