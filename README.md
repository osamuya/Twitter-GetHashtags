# Twitter-GetHashtags

````composer.json
{
    "name": "osamuya/Twitter-GetHashtags",
    "version": "0.1",
    "description": "Get posts tweeted with specified hashtag.",
    "keywords": ["Twitter", "API", "Hashtag"],
    "type": "library",
    "license": "MIT",
    "require": {
        "monolog/monolog": "^1.23.0"
    },
    "autoload": {
        "psr-4": {
            "osamuya\\Twitter-GetHashtags\\": "src/"
        }
    }
}
````
------------------------------------------------------------

1. Githubでリポジトリをつくる。
1. composer.jsonを作成 (nameは小文字じゃないとダメらしい。)
1. composer install
1. vebdorをignore
1. sample.phpとかでautoload

1. Packagistに登録。Githubのhttpの方のリポジトリのアドレスをSubmitします。
[https://packagist.org/packages/submit](https://packagist.org/packages/submit)
1. 登録が成功したら、composerで読んでみる。




- [PHP開発でComposerを使わないなんてありえない！Packagist公開編](https://qiita.com/niisan-tokyo/items/a6a3ee984f0ccb6c734d)
- [Twitter APIでつぶやきを取得する](https://qiita.com/yokoh9/items/760e432ebd39040d5a0f)