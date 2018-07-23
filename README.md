# Dataset-Survey
NLP분야에서 쓸만한 데이터셋 조사/
NLPの分野で使えそうなデータセットのサーベイ

##
* [IMDb](https://www.imdb.com/interfaces/)
  * 영화 리뷰 한 개가 여러 문장으로 되어있는 데이터셋.
  * 映画レビュー一つ当たり幾つかの文章が含まれている。
* [MR](http://www.cs.cornell.edu/people/pabo/movie-review-data/)
  * 영화 리뷰 한 개가 한 문장으로 되어있는 데이터셋. 포지티브/네거티브 라벨링 되어있음.
  * 映画レビュー一つ当たり一つの文章が含まれている。ポジティブ/ネガティブのラベリングがされている。
* [SST](https://nlp.stanford.edu/sentiment/)
  * Stanford Sentiment Treebank 데이터셋. MR의 확장판이며 train/dev/test로 분류되어있음.
  * Stanford Sentiment Treebankデータセット。MRの拡張版、train/dev/testで分けられている。
* [OpinRank Review Dataset](http://archive.ics.uci.edu/ml/datasets/opinrank+review+dataset)
  * Tripadvisor와 Edmunds의 자동차/호텔 리뷰 모아놓은 데이터셋.
  * TripadbisorとEdmundsの車・ホテルのレビューコレクション。
* [Citysearch corpus](http://www.cs.cmu.edu/~mehrbod/RR/)
  * 식당 리뷰로 만든 코퍼스. 코퍼스 중에서 aspect 라벨링이 된 3,400 개 문장을 제공.6 개 aspect 라벨을 이용.
  * レストランのレビューコーパス。コーパスの中のaspectのラベリングがされた3,400個の文を提供。6つのaspectラベルを利用。
* [SemEval-n](https://en.wikipedia.org/wiki/SemEval)
  * 현재진행형 semantic evaluation 프로젝트(감정분석, 텍스트 분류 등)의 데이터셋. 가장 아래에 링크 있음.
  * 現在進行形のsemantic evaluationプロゼクト（センチメント分析・テキスト分類など）のデータセット。一番下にリンクあり。
* [Yelp Challenge dataset](https://www.yelp.com/dataset)
  * 리뷰(520만), 비지니스(17.4만), 사진(20만) 등의 데이터셋. JSON, SQL 제공.
  * レビュー（520万）、ビジネス（17.4万）、画像（20万）などのデータセット。JSON、SQL提供。
* [SemCor](https://www.sketchengine.eu/semcor-annotated-corpus/)
  * 의미 별로 아노테이션 된 영문 코퍼스. WordNet 1.6 senses로 의미를 분석했으며 WordNet 3.0으로 자동 매핑.
  * 意味的にアノテーションされた英文コーパス。WordNEt1.6sensesで意味分析をし、WordNet3.0で自動的にマッピング。
* [SNLI](https://nlp.stanford.edu/projects/snli/)
  * 570k개의 사람이 적은 영어문장을 토대로 함의, 모순, 가정 전제라는 라벨로 분류한 코퍼스.
  * 570k個の人の書いた英文をもとに、含意・矛盾・仮定の前提というラベルを付けてクラス分けしたコーパス。
* [MultiNLI](https://www.nyu.edu/projects/bowman/multinli/)
  * SNLI의 확장판으로 433k개 문장을 텍스트 함의 정보 아노테이션과 함께 모아둔 코퍼스. SNLI와 다른 점은 spoken과 written 둘 다 포함.
  * SNLIの拡張版で、433k個の文をテキスト含意情報のアノテーション付きで集めといたコーパス。SNLIとの違いは、spokenとwrittenどっちも使用してるという点。
