# Ansible Test

このリポジトリは、Ansibleの動作確認用リポジトリです。
また、Issue単位で、Ansibleの動作確認とコミットを行なっているので、
気になるIssueからコミットを辿れるように作っています。

# Set up

ローカル環境のセットアップ方法について説明します。
環境は、Mac OS X 10.12.6を想定しています。

リポジトリをクローンします。

```
git clone git@github.com:mtb-beta/test_ansible.git
```

PythonのpipでAnsibleをインストールします。

```
cd test_ansible
python3 -m venv ansible_test
. ansible_test/bin/activate
pip install -r requirements.txt
```

Vagrantを起動し、接続確認を行います。
```
vagrant up
vagrant ssh
```





