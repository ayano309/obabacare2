# obaba-care
# 健康管理アプリ（obaba-care）です。


## なぜ制作したか
介護生活の際、毎日のバイタル情報や訪問看護の方のアドバイスを紙に書いてました。
また、症状もいつ頃かなのかをしっかりと把握することができずちゃんとした内容を医者に話すことが
できませんでした。


## サービス概要
* バイタル情報
* 気になったこと
* アドバイスなどのメモ機能
* メモ検索機能
* 気になったこと重要フラグ
* 水分記録
*　　排便記録
*　　薬記録

# 主な機能

* User ログイン機能
* ゲストログイン機能
* バイタル情報登録
* 今日の気になったことコメント
* 気になったこと重要フラグ
* 気になったことカテゴリ機能
* アドバイスメモ登録
* 水分記録機能
* 排便記録機能
* 薬記録機能
* 薬タグ機能
* 非同期
* 検索機能
* ページネーション

# ER図

# 使用技術
## バックエンド
 * Ruby 2.7.5p203 (2021-11-24 revision f69aeb8314) [arm64-darwin20]
 * Rails 6.1.5
 * Rubocop
## フロントエンド
* HTML
* CSS(SCSS)
* JavaScript(jQuery)
* bootstrap4

# 主な Gem
* gem 'devise'
* gem 'better_errors'
* gem 'binding_of_caller'
* gem 'pry-rails'
* gem 'annotate'
* gem 'rubocop-rails'
* gem 'rubocop'
* gem 'factory_bot_rails'
* gem 'faker'
* gem 'rspec-rails'
* gem 'simple_calendar', '~> 2.0'
* gem 'image_processing', '~> 1.2'

## その他
* ActiveStrage
* ActionText
