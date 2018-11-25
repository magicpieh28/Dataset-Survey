# Dataset-Survey
  * NLP분야에서 쓸만한 데이터셋 조사
  * NLPの分野で使えそうなデータセットのサーベイ

##
* [IMDb](https://www.imdb.com/interfaces/)
  * 영화 리뷰 한 개가 여러 문장으로 되어있는 데이터셋.
  * 映画レビュー一つ当たり幾つかの文章が含まれている。
* [MR](http://www.cs.cornell.edu/people/pabo/movie-review-data/)
  * 영화 리뷰 한 개가 한 문장으로 되어있는 데이터셋. 포지티브/네거티브 라벨링 되어있음.
  * 映画レビュー一つ当たり一つの文章が含まれている。ポジティブ/ネガティブのラベリングがされている。
* [Amazon Product Data](http://jmcauley.ucsd.edu/data/amazon/)
  * This dataset contains product reviews and metadata from Amazon, including 142.8 million reviews spanning May 1996 - July 2014.This dataset includes reviews (ratings, text, helpfulness votes), product metadata (descriptions, category information, price, brand, and image features), and links (also viewed/also bought graphs).
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
* [Amazon Review Data](http://jmcauley.ucsd.edu/data/amazon/links.html)
  * 아마존 리뷰를 각 카테고리별로 나누어 만든 데이터셋. 어찌됐든 사이즈가 엄청 큼. 리뷰 하나에는 여러 문장이 포함되어 있고 전체 리뷰를 다운로드 하기 위해서는 메일을 보내야 함. 별점 파일과 메타데이터 파일이 추가로 있는데 메타데이터 파일에는 카테고리 분류 명이 들어있지만 작은 따옴표로 만들어진 json파일이라 짜증남.
  * アマゾンのレビューを書くカテゴリごとに分けて作ったデータセット。とにかくサイズがでかい。レビュー分１つにはいくつかの文章が含まれていて、全体のレビューをダウンロードするためにはメールを怒る必要がある。星点のファイルとメタデータのファイルが追加的にあり、メタデータの中にはカテゴリが細かに分類されている。しかし、single quotationのjsonなのでうざい。
  
## Lexicon
* [SST](https://nlp.stanford.edu/sentiment/) treebank
  * Stanford Sentiment Treebank 데이터셋. MR의 확장판이며 train/dev/test로 분류되어있음.
  * Stanford Sentiment Treebankデータセット。MRの拡張版、train/dev/testで分けられている。
* [MPQA](https://mpqa.cs.pitt.edu/lexicons/subj_lexicon/) ??
  * Polarity ratings for sentiment words from MPQA corpus
* [HLT](https://hlt-nlp.fbk.eu/technologies/sentiwords) .txt
  * 155,000개 영어 단어의 sentiment score를 매겨놓은 데이터셋. (단어#형태소 점수)형식으로 되어있음.
  * 155,000個の英単語のsentiment scoreがつけられてるデータセット。(単語＃形態素　点数)形式になってる。
* [SentiWordNet](https://sentiwordnet.isti.cnr.it/) .txt
  * Opinion Mining을 위한 감성언어 데이터셋. (POS	ID	PosScore	NegScore	SynsetTerms	Gloss)형식으로 되어있음.
  * Opinion Miningのためのsentiment lexiconデータセット。(POS	ID	PosScore	NegScore	SynsetTerms	Gloss)形式になってる。
* [WSD(Word Stat Dictionary)](https://provalisresearch.com/products/content-analysis-software/wordstat-dictionary/sentiment-dictionaries/) ??
  * rule: The first rule is negative words not preceded by a negation within three words in the same sentence. The second rule is positive words preceded by a negation within three words in the same sentence.
  * 9164개의 부정 단어와 4847개의 긍정 단어 이상이 포함되어있는 데이터셋.
  * 9164個以上の否定単語と4847個以上の肯定単語でなっているデータセット。
* [NRC Hashtag Affirmative Context Sentiment Lexicon and NRC Hashtag Negated Context Sentiment Lexicon](http://saifmohammad.com/WebPages/lexicons.html) .txt
  * unigram lexicon과 bigram lexicon이 있는데 unigram의 경우 36,357개 긍정 단어와 7,592개 부정 단어가 포함되어 있고 bigram의 경우 159,479개의 긍정 단어와 23,875개의 부정 단어가 포함되어 있음. (#단어 sentiment_score 긍정문에서의_출현_빈도 부정문에서의_출현_빈도)형식으로 되어있음.
  * unigram lexiconとbigram lexiconがあり、unigramの場合、36,357個の肯定単語と7,592個の否定単語が含まれている。bigramの場合、159,479個の肯定単語と23,875個の否定単語が含まれている。(#単語 sentiment_score 肯定文での出現頻度　否定文での出現頻度)の形式になっている。
