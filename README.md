# 現場で使える Ruby on Rails 5速習実践ガイド　Chapter3のタスク管理アプリ

## 現場で使える Ruby on Rails 5速習実践ガイド   大場 寧子 https://www.amazon.co.jp/dp/B07JHQ9B5T/ref=cm_sw_r_tw_dp_U_x_98OkDbQZHRKNS @amazonJPさんから

***
## 3-1-3 アプリケーションの雛形作成
> $ rails new taskleaf -d postgresql
> $ cd taskleaf
> $ bin/rails db:create

## 3-2-2 タスクモデルの雛形作成
> $ bin/rails g model Task name:string description:text  
> $ bin/rails db:migrate

## 3-3 コントローラとビューの雛形作成
> $ bin/rails g controller tasks index show new edit