# python_test

```
#仮想環境を作る
$ python -m venv [仮想環境名]
$ cd [仮想環境名]
```

#仮想環境の起動
```
**win**
$ Scripts/activate.bat
**mac**
$ source bin/activate
```

#ライブラリーのインストール
```
$ pip install Django==3.0
$ pip install django-bootstrap4
```

# 開発フォルダの作成
```
cd ..
git clone git@github.com:Sounn/python_test.git
cd python_test
python manage.py migrate
python manage.py runserver
```

#システムの起動
```
$ python manage.py runserver
```
http://localhost:8000<br>
http://localhost:8000/app_folder/top_page<br>

#管理者ユーザー
```
$ python manage.py createsuperuser
```
1.ユーザ名<br>
2.メールアドレス<br>
3.パスワード（１回目）<br>
4.パスワード（確認用）<br>
http://localhost:8000/admin
