# やったこと
- terraformの初期化
- terraformでVMインスタンスを作成
- VMでSSH接続して, Hello Worldを表示
- Webサーバーとして、Hello Worldを表示

# terraform

```bash
# 初期化
terraform init
# 構成プラン(構成を適用可能かどうか検証)(コンパイルに近い)
terraform plan
# 構成の適用
terraform apply
# 構成の削除
terraform destroy

# 出力
terraform output

```
# 参考
https://cloud.google.com/docs/terraform/get-started-with-terraform?hl=ja