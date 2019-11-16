# sunakan

sunakan(砂缶)

---

#### 今日やることと宣言したこと（その1）

- [GatsbyJS Guidebookをすすめる(終わらせたい)](https://booth.pm/ja/items/1312387)
  - ブログ的なことを始めたいから
  - [Gatsbyは今、最高にイケてるエンジニア向けブログ。爆速、無料、フルカスタマイズでもう普通のブログには戻れない](https://www.jabba.cloud/20190113194504/)を読んで、技術(GraphQL/React)も少しは学べるし、Asciidocでも記述可能そうだから

---

#### 今日やることと宣言したこと（その2）  

- [15Stepで習得Dockerから入るKubernetesを読む](https://www.amazon.co.jp/15Step%E3%81%A7%E7%BF%92%E5%BE%97-Docker%E3%81%8B%E3%82%89%E5%85%A5%E3%82%8BKubernetes-%E3%82%B3%E3%83%B3%E3%83%86%E3%83%8A%E9%96%8B%E7%99%BA%E3%81%8B%E3%82%89K8s%E6%9C%AC%E7%95%AA%E9%81%8B%E7%94%A8%E3%81%BE%E3%81%A7-StepUp-%E9%81%B8%E6%9B%B8/dp/4865941614)
  - Qiitaでバズった記事で[IT業界で働く者の基礎知識となるクラウドネイティブ とは？](https://qiita.com/MahoTakara/items/7c6c89cbddfd4a8f7b44)の記事が良かった&コメントが興味深かった
  - 本出してる -> レビューも良さそう
  - connpassで著者によるオンライン解説があったから

---

#### 進捗(結果から)

- [x] GatsbyJS（p.66-73）、途中だけどdone
- [ ] k8s(p.1-143)、全体でp.500くらい

---

#### GatsbyJS GuideBookでの学び

- リポジトリ
  - [sunakan/notes-about-gatsby](https://github.com/sunakan/notes-about-gatsby)
- Netlifyにデプロイ
  - [Netlify](https://5dcf6ff7f0cd9d3daab963b3--blissful-raman-a0e29e.netlify.com/)
- FrontEnd(React/GraphQL)の触り
- Netlifyの存在
  - privateリポジトリでもできる(github.ioはpublic onlyだった気がする)
- GraphQLってバッククォートが普通。。？

---

#### 15Stepで習得 Dockerから入るk8s(全3章構成)

- [x] 第1章Dockerとk8sの基礎知識(p.15-89)
- [ ] 第2章コンテナを実践的に理解するレッスン(5ステップ分：p.93-p.156=64pages,約13page/ステップ)
- [ ] 第3章k8sを実践的に理解するレッスン(10ステップ分：p.159-p.447=289pages,約30page/ステップ)
- [ ] 付録：学習環境の構築(p.451-p.525=75pages)

---

#### 第1章Dockerとk8sの基礎知識その1(p.15-89)

- 読み方[brendandburns(k8sの創設者の1人?)のtweet](https://twitter.com/brendandburns/status/585479466648018944?ref_src=twsrc%5Etfw)
- 読み方1：koo-ber-net-ees
- 読み方2：k-eights

---

#### 第1章Dockerとk8sの基礎知識その２(p.15-89)

- コンテナの性能劣化：[Cedec2014 世界のゲーム業界で選ばれるIBMの高性能クラウドSoftLayerの37p目](https://www.slideshare.net/MahoTakara/cedec2014-ibmsoftlayer)

- この本で使うOSSの一覧がある
  - Ansible/Elasticsearch/Fluentd/GlusterFS/Grafana/Heapster/Heketi/InfluxDB/Kibana/NFS/Vagrantとか

---

#### 第2章コンテナ開発を習得する5ステップ(読んだのは最後のステップのみ)

- (k8sが求める)コンテナAPI
  - Docker SwarmやDocker Composeの機能は使いません、と明記

