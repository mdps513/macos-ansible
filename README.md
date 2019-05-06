# 概要
MacOS用playbook

## ディレクトリ移動
`$ cd ~/macos-ansible`
## 構文チェック
`$ ansible-playbook --syntax-check ./playbooks/setup.yml -i inventory/dedault`
## playbook実行
`$ ansible-playbook ./playbooks/setup.yml -i inventory/dedault`
