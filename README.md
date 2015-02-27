这是分支<br><br><br>
导入项目时:<br>
    1使用TortoiseGit(小乌龟)时,项目的url使用ssh类型的,比如本项目 git@github.com:lyxz/Test.git,并加载自己的putty秘钥,提交不用输账号密码. <br>
    2IDE导入(这里以Eclipse为例,请自行装egit插件)<br>
        2.1 Url使用https开头的,比如本项目https://github.com/lyxz/Test.git<br>
        2.2 Eclipse里右键,Import选择Git文件夹下Projects from git 然后Next<br>
        2.3 下一界面选择 clone URI 然后Next<br>
        2.4 下一界面粘贴2.1提到的https开头的Url,然后咋在Username和password里分别输入github的账号 密码,并勾选Store(保存)然后Next<br>
        2.5 下一界面是选分支.一般主分支是master. 然后Next<br>
        2.6 下一界面是保存路径,自己选一位置保存即可. 后面一路Next即可完成导入.
