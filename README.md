#ngx_processman
---------------------------------------
##Nginxモジュール。 インストール後もNginxモジュール追加可能になります。.htaccessを読むこともできるようになります。nginx.confでhttpd.confのsyntaxが使用可能になります。PHPはインストールされていれさえすればインストール後、設定なしで使えるようになります。また、SuExecらしきものが使えるようになります。
###例えば、Nginxモジュールの追加コマンド。その前にコンパイルしておいてください。
---
####sudo ngxs -i ./ngx_pagespeed.so
##コンパイル方法
####./configure --add-module-../ngx_processman
###コンパイルオプション
####--exclude-ngxs = Nginx動的モジュール追加をしない
####--exclude-httpdconf = httpd.confのsyntaxを使用しない
####--exclude-htaccess = .htaccessを使わない
####--exclude-php = PHPをデフォルトでは使いません。
###このモジュールを作ったのは[Project Kazuki](http://www.jisakuroom.net/ "Project Kazuki")です。
####*このモジュールはベータ版です。バグも多くあります。是非GithubにIssueの送信お願いします。*
