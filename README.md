#ngx_processman
---------------------------------------
##Nginxモジュール。 インストール後もNginxモジュール追加可能になります。.htaccessを読むこともできるようになります。nginx.confでhttpd.confのsyntaxが使用可能になります。PHPはインストールされていれさえすればインストール後、設定なしで使えるようになります。また、SuExecらしきものが使えるようになります。
例えば、Nginxモジュールの追加コマンド。その前にコンパイルしておいてください。
-sudo ngxs -i ./ngx_pagespeed.so
###このモジュールを作ったのは[Project Kazuki](http://www.jisakuroom.net/ "Project Kazuki")です。
####*このモジュールはベータ版です。バグも多くあります。是非GithubにIssueの送信お願いします。*
