**課題**
・heredocが動かない。EOFは認識して終わるけど、コマンドが動いてない。
↑家で動かしたら動いた。なんで？42の校舎でまた動かしてみる。1/15

・エラーケース網羅できてない。1/15

・here_docのケース増やす 1/15

・引数で""がきた時、permission deniedになる。エラーハンドリングでで前もって弾くべきなのかなと思う。

・ファイルが存在しないときのエラー、存在しないコマンドの時のエラーのメッセージが本家と異なるので変えたほうがいいかも。

・pipe heredoc> とpipexのheredoc> これも合わせた方がいいかもしれない

・エラーケースを試すとき、メモリリークしてる。子プロセスだけではなくて、親プロセスを終わらせる必要ある。 1/17