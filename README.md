# sam-stepfunctions1a

[Step Functions ステートを作成マシンLambda の使用 - AWS Step Functions](https://docs.aws.amazon.com/ja_jp/step-functions/latest/dg/tutorial-creating-lambda-state-machine.html)
に出てくるリソースをSAMで作成するサンプル。

CFnの AWS::StepFunctions::StateMachine ではなく
SAMの AWS::Serverless::StateMachine を使っている。

それですっきり短くなったか、というとそうでもない感じ。
(ポリシーをインラインにしたので、見た目4つ分減っている)

実際には使用していないS3が1個ある。

デプロイ後のテストの方法は
上記URLを参照。
