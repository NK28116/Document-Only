# Cinra面接


## 一般的な質問

1.  なぜ転職活動を始めたのですか？
  2. 自分は技術者として向上していきたいが今の部署では書類を書いたり手順書を遵守した動作を確認しているだけなのでそれが難しそう。
  3. findyで転職活動をしている中ではデザインの方が全面に出されていたので今まで自とのかかわりが少なかったフィールドなので今までと違う刺激をもらえると感じた
2. 転職活動ってどれくらい積極的ですか？
     1. 転職活動については結構積極的に動いている 
6.  転職活動にてどういう軸で動いてますか？意識して見てるポイント教えて下さい：
	1. 技術者として関われるか，技術力を上げられるか。それに伴い，収入も上げていけばいい
 1.  3年〜5年のスパンでの将来像イメージってありますか？今後のキャリアはなんですか？：
	 1. 将来のキャリア，なりたいエンジニア像はテックリードと名乗れるようになること
 2. 現職でどんなお仕事してますか？どんなミッションですか？（仕事内容は何か。何の達成を目指しているか）
	 1. 現職ではシステムの維持保守をやっている
 3. 現職での課題と解決方法はなんですか？（どんな課題があるか。どうやって解決しようとしているか）
	 1. 現職の課題は，組織が大きく自由度が低い。また書類を書くことや変化前後の画面のスクショをとったりと本筋でない業務の方が多いこと。これを解決するにはそれぞれモジュールの粒度を高めた方がいいのかも？
 4. 得意なことや好きなことってどんなことですか？
	 1. 特異なことは論理的な思考だと思っている。好きなことは将来100の楽をするために今の10の苦労をすることと酒飲みながら無責任に思考実験もどきをすること
	 2. 逆に苦手なことは，対人関係だと割ときにしぃなの初対面だとあまり親しくできないと感じる
 5. スキル・経験値のアップはどんなことをしてますか？
	 1. スキルアップのために，気になった言語の個人開発や公式ドキュメントを流し読みしたりしている(今気になっているのはRust,個人開発は骨子はできたと思う。あとはレコードとデザインを整えるだけだと思う)
 6.     上司から改善フィードバックとしてどういうものを貰うことが多いですか？
	 1. 上司から，説明するときの単語が抽象的というか概念的なことが多いと言われたことがありそうならないように気を付けてはいる
 7. ストレスがあったときにどう感じ（ex. 怒る、落ち込む、など） 、それをどうやって解消していますか？
	 1. ストレスがあったときは，割と落ち込むので自分の機嫌を自分でとることを心掛けている
 8.  出社の頻度、リモートワークに対する考え方
	 1. 出社の頻度は基本，会社の方針に従うができるなら，在宅の方が性にはあっているし独り言を気にしないでいいのはストレスがない
	 2. 古リモートは本社が大阪や仙台など関東以外ならいいと思う。自分はふらっと出かけられてなんかできるのが好きなので他はそう言いうことがやりにくいイメージがある
	 3. リモートワークで一番気を付けているのは文面がきつくならないようにすること


## 技術系
そこまで深く突っ込まれないだろうと予想(まだ一年目なので)
- 使ってきた言語、サーバーの構成はどうで、なぜその構成で、もっと良い方法あるか、現在の課題は何か、教えてください
	- 意図：得意領域、苦手領域の確認意図：技術的な向上や理想形を考えられるか
	- 今まで使ってきたのはfrontではNext.jsやTypeScriptなどbackではlaravelやmysqlなど
	- TypeScriptはstatocな型付け言語なので,間違いに気づきやすい
	- nextはファイルルートなので可視性が高く，また部分的な高速リロードが利点だと思います
    Q. 出てきた技術単語についてwhat?why?をいろいろ聞かせて頂くので、教えてください
        詳細：設計や実装方針や技術選定への候補、メリデメ(なぜ良いか、何が解決されるか)、導入理由
        詳細：単語の意味、その単語で出てきた単語の意味を更に聞く、それを繰り返す
        意図：どんなプロセスで判断をする人か（どれだけ任せられるか）
- 設計、開発をするときに大切にしている思想は何か、なぜそれを大切にしているか、具体的に過去の事例でその思想でどういう成果が出たか、逆に失敗した例はあるか教えてください
	- 意図：学びを体系化できるか、どんな一貫した行動を取れるか
	- 意図：思想だけじゃなくてどこまで実践出来ているか、実現可能性があるか
		- なるべく細かすぎないようにパーツを分割している。アトミックデザインは確かに優れた考えだと思うが他に多くの場所に流用できることが前提の考えで対象の規模によってはコードが増えて保守性や性格が正しくとらえっれない
		- 個人開発レベルでやるべきじゃない

- プロダクト/プロジェクトマネジメントで大事にしている思想は何か、なぜそれを大切にしているか、具体的に過去の事例でその思想でどういう成果が出たか、逆に失敗した例はあるか教えてください
	- 意図：学びを体系化できるか、どんな一貫した行動を取れるか
	- 意図：思想だけじゃなくてどこまで実践出来ているか、実現可能性があるか
	- (ex.PMの場合)権限はどこまであったか、目標は何か、今の戦略と課題は何で、まずどうすべきと考えているか教えて下さい。
        意図：どの範囲まで任せられるのか、どこまで考えられるのかを判断
- 各技術（ex. ruby,php,react.js/vue.js/アーキテクト/インフラ)は、組織内で最も詳しい人たちから深堀り
	- 意図：どこまでその技術で課題解決が行えるか（深い所まで一問一答が繰り返す)
- 会社からどんな環境を用意できれば、成果を出せる自信があるか、逆に何がないと苦労しそうか教えて下さい
	- 意図：何で成果を出せて、どこが苦手かのスキル面での自己理解を見る
		- まだそこまでこだわれるほどの実力はないが，文章に残す文化が主流になっていると嬉しい
- 一般的にはこう言われているが、実はもっとこうじゃないかって考える開発や組織思想は何かあるか教えて下さい
	- スタンダードを学びつつ、自分の思想を持てているか、日々考えられているか
		- 自由度が高すぎる言語は人間には早すぎたんじゃないか
