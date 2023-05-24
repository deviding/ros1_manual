# ROS1学習用テキスト
本ページはROS1の学習用のテキストとして作成しています。

ROSの公式wikiが非常にわかりにくいのと、ROS1の情報を網羅的にまとめた日本語の資料がなかったので自分で作ってみた次第です。

ROS1に初めて触れる方への入門や参考になれば幸いです。

筆者自身ROS1を独学で学習しているため、間違いや誤りがある可能性があります。その場合は場合は指摘して下さるとありがたいです。

## 目次

### 1：準備
- [1-1：ROSの概要](./01_preparation/1-01.md)
- [1-2：ROS1の環境構築](./01_preparation/1-02.md)

### 2：基本
- [2-1：ROSの仕組み](./02_base/2-01.md)
- [2-2：ワークスペース](./02_base/2-02.md)
- [2-3：パッケージ](./02_base/2-03.md)
- [2-4：PublisherとSubscriber(C++)](./02_base/2-04.md)
- [2-5：PublisherとSubscriber(python)](./02_base/2-05.md)
- [2-6：メッセージ](./02_base/2-06.md)
- [2-7：サービス](./02_base/2-07.md)
- [2-8：roslaunch(基本)](./02_base/2-08.md)
- [2-9：roslaunch(応用)](./02_base/2-09.md)
- [2-10：rviz](./02_base/2-10.md)
- [2-11：rosコマンド](./02_base/2-11.md)

### 3：tfとフレームと時間
- [3-1：tfとフレームの概要](./03_tf/3-01.md)
- [3-2：tfのbroadcasterとlistener(C++)](./03_tf/3-02.md)
- [3-3：フレームの追加(C++)](./03_tf/3-03.md)
- [3-4：tfの時間(C++)](./03_tf/3-04.md)
- [3-5：tfのbroadcasterとlistener(python)](./03_tf/3-05.md)
- [3-6：フレームの追加(python)](./03_tf/3-06.md)
- [3-7：tfの時間(python)](./03_tf/3-07.md)

### 4：Turtlebot3を使ったシミュレーション
- [4-1：Turtlebot3の概要](./04_turtlebot/4-01.md)
- [4-2：Turtlebot3の環境構築](./04_turtlebot/4-02.md)
- [4-3：GazeboとTurtlebot3の簡単なシミュレーション](./04_turtlebot/4-03md)
- [4-4：地図の作成](./04_turtlebot/4-04.md)
- [4-X：AMCL](./04_turtlebot/4-0X.md)
- [4-X：Navigation](./04_turtlebot/4-0X.md)

### 5：Simple Action Server(actionlib)

### 6：PCL(Point Cloud Library)

### 7：Nodelet

### 参考資料

|リンク|内容|
|---|---|
|[ROS1公式wiki](https://wiki.ros.org/ja/)|ROS1の公式wikiの日本語版。チュートリアルなど情報が豊富だが、あまり親切でなかったり、翻訳されてないページがあったり、サンプルがそのままでは動かなかったりするので注意が必要。|
|[ROBOTIS Turtlebot3ページ](https://e-shop.robotis.co.jp/list.php?c_id=93)|ROBOTISさんのTurtlebot3のページ|
|[Turtlebot3 Githubページ](https://github.com/ROBOTIS-GIT/turtlebot3)|Turtlebot3のROSパッケージなどが置かれているGitHubページ|
|[Turtlebot3 wiki](https://wiki.ros.org/turtlebot3)|Turtlebot3のWiki。ROSの公式wikiと同じようにわかりにくかったりする。|
|[Turtlebot3 e-manual](https://emanual.robotis.com/docs/en/platform/turtlebot3/overview/)|Turtlebot3のe-manual。wikiよりもこっちの方がexampleなどがあるのでわかりやすいかも。|


## 更新履歴

|日付|内容|
|---|---|
|2022/10/26|初版として公開|