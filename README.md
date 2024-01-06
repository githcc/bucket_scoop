## 说明
1. 用于汇总软件相对应的bucket，对main进行补充
2. 本项目合并入scoop官方项目

## 我的软件列表
1. [aliyundrive](https://github.com/akirco/aki-apps)
2. [aria2](https://github.com/akirco/aki-apps)
3. [Calibre](https://github.com/ScoopInstaller/Extras)
4. [Motrix](https://github.com/ScoopInstaller/Extras)
5. [Obsidian](https://github.com/ScoopInstaller/Extras)
6. [wechat](https://github.com/ScoopInstaller/Extras)
7. [finalshell](https://github.com/ViCrack/scoop-bucket)
8. [jianying](https://github.com/magicedy/scoop-bucket-m)
9. [wps](https://github.com/WinApps-share/WinApps-bucket)
10. [idea-ultimate win11无法安装](https://github.com/ScoopInstaller/Extras)
11. [xmind](https://github.com/wholegale39/onetab)
12. [wegame](https://github.com/akirco/aki-apps)

## 安装scoop
    ```
    # 设置 PowerShell 执行策略
    Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
    # 下载安装脚本
    irm get.Scoop.sh -outfile 'install.ps1'
    # 执行安装, --ScoopDir 参数指定 Scoop 安装路径 主要是考虑到假如默认路径含中文
    .\install.ps1 -ScoopDir 'C:\Scoop'
    ```

## 安装软件
    ```
      scoop install 7zip git
      scoop bucket add githcc https://github.com/githcc/bucket_scoop
      scoop install aria2
      scoop install idea-ultimate
      scoop install vlc
      scoop install finalshell  
      scoop install vcredist2022
      scoop install notepadplusplus
      scoop install wps
      scoop install xmind
      scoop install jianying
      scoop install Motrix
      scoop bucket rm githcc
    ```
### 下列版本更新较为频繁
scoop bucket add Extras https://github.com/ScoopInstaller/Extras
scoop install nodejs
scoop install wechat
scoop bucket rm Extras

Obsidian RaiDrive 这两个可能需要找非scoop的了

## bucket来源网站
1.  [Scoop Directory](https://rasa.github.io/scoop-directory/search)
2.  [scoop官网](https://Scoop.sh/)

## 项目拉取
[Ash258](https://github.com/Ash258/GenericBucket)

## 参考
1. github
   1. [Scoop](https://github.com/githcc/knowledge_self/blob/main/%E8%BD%AF%E4%BB%B6/%E4%BD%BF%E7%94%A8/Scoop.md)
   2. [win系统安装](https://github.com/githcc/knowledge_self/blob/main/%E7%B3%BB%E7%BB%9F/%E5%AE%89%E8%A3%85/win.md)