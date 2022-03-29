# sam-stepfunctions1

[Step Functions ステートを作成マシンLambda の使用 - AWS Step Functions](https://docs.aws.amazon.com/ja_jp/step-functions/latest/dg/tutorial-creating-lambda-state-machine.html)
に出てくるリソースをSAMで作成する。

SAMの AWS::Serverless::StateMachine ではなく
CFnの AWS::StepFunctions::StateMachine を使っているので
結構きつい。

デプロイ後のテストの方法は
上記URLを参照
