# 概要

Djangoの環境を構築するためのリポジトリです。

## コマンド

### DB

python manage.py makemigrations

- DBとmodels.pyを比較して、差分があればマイグレーションファイルを作成する

python manage.py migrate

- マイグレーションファイルを、DBに反映する


### 開発サーバーの実行

python manage.py runserver
python manage.py runserver 0.0.0.0:8000

### 管理者ユーザーの作成

python manage.py createsuperuser



