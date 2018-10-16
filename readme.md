# avelino/awesome-go [![translate-svg]][translate-list]

[translate-svg]: http://llever.com/translate.svg
[translate-list]: https://github.com/chinanf-boy/chinese-translate-list

「 一个精明的GO框架、库和软件列表.受到[awesome-python](https://github.com/vinta/awesome-python)启发. 」

[中文](./readme.md) | [english](https://github.com/avelino/awesome-go)

---

## 校对 🀄️

<!-- doc-templite START generated -->
<!-- repo = 'avelino/awesome-go' -->
<!-- commit = '9f663dfa6f560d988b18cc00df205cfb51e704a6' -->
<!-- time = '2018-10-16' -->

| 翻译的原文 | 与日期        | 最新更新 | 更多                       |
| ---------- | ------------- | -------- | -------------------------- |
| [commit]   | ⏰ 2018-10-16 | ![last]  | [中文翻译][translate-list] |

[last]: https://img.shields.io/github/last-commit/avelino/awesome-go.svg
[commit]: https://github.com/avelino/awesome-go/tree/9f663dfa6f560d988b18cc00df205cfb51e704a6

<!-- doc-templite END generated -->

- [ ] **以下所有都没有校对**

### 贡献

欢迎 👏 勘误/校对/更新贡献 😊 [具体贡献请看](https://github.com/chinanf-boy/chinese-translate-list#贡献)

## 生活

[help me live , live need money 💰](https://github.com/chinanf-boy/live-need-money)

---


# Awesome Go

[![Build Status](https://travis-ci.org/avelino/awesome-go.svg?branch=master)](https://travis-ci.org/avelino/awesome-go) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Slack Widget](https://camo.githubusercontent.com/984828c0b020357921853f59eaaa65aaee755542/68747470733a2f2f73332e65752d63656e7472616c2d312e616d617a6f6e6177732e636f6d2f6e6774756e612f6a6f696e2d75732d6f6e2d736c61636b2e706e67)](http://gophers.slack.com/messages/awesome)

一个精明的GO框架、库和软件列表.受到启发[awesome-python](https://github.com/vinta/awesome-python).

### 贡献

请快先看看

- [ ] [contribution 指南](./CONTRIBUTING.zh.md).感谢各位[contributors](https://github.com/avelino/awesome-go/graphs/contributors) Rock!

#### *如果您在这里看到一个包或者项目不再被维护或者不适合,请提交一个拉取请求来改进这个文件.谢谢您!*

### 内容

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


  - [音频与音乐](#%E9%9F%B3%E9%A2%91%E4%B8%8E%E9%9F%B3%E4%B9%90)
  - [认证与OAuth](#%E8%AE%A4%E8%AF%81%E4%B8%8Eoauth)
  - [命令行](#%E5%91%BD%E4%BB%A4%E8%A1%8C)
    - [标准CLI](#%E6%A0%87%E5%87%86cli)
    - [高级Console UIs](#%E9%AB%98%E7%BA%A7console-uis)
  - [配置](#%E9%85%8D%E7%BD%AE)
  - [持续集成](#%E6%8C%81%E7%BB%AD%E9%9B%86%E6%88%90)
  - [CSS预处理器](#css%E9%A2%84%E5%A4%84%E7%90%86%E5%99%A8)
  - [数据结构](#%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84)
  - [数据库](#%E6%95%B0%E6%8D%AE%E5%BA%93)
  - [数据库驱动程序](#%E6%95%B0%E6%8D%AE%E5%BA%93%E9%A9%B1%E5%8A%A8%E7%A8%8B%E5%BA%8F)
  - [日期和时间](#%E6%97%A5%E6%9C%9F%E5%92%8C%E6%97%B6%E9%97%B4)
  - [分布式系统](#%E5%88%86%E5%B8%83%E5%BC%8F%E7%B3%BB%E7%BB%9F)
  - [电子邮件](#%E7%94%B5%E5%AD%90%E9%82%AE%E4%BB%B6)
  - [可嵌入脚本语言](#%E5%8F%AF%E5%B5%8C%E5%85%A5%E8%84%9A%E6%9C%AC%E8%AF%AD%E8%A8%80)
  - [文件](#%E6%96%87%E4%BB%B6)
  - [金融](#%E9%87%91%E8%9E%8D)
  - [表单Form](#%E8%A1%A8%E5%8D%95form)
  - [游戏开发](#%E6%B8%B8%E6%88%8F%E5%BC%80%E5%8F%91)
  - [生成与泛型](#%E7%94%9F%E6%88%90%E4%B8%8E%E6%B3%9B%E5%9E%8B)
  - [地理](#%E5%9C%B0%E7%90%86)
  - [Go编译器](#go%E7%BC%96%E8%AF%91%E5%99%A8)
  - [go线程](#go%E7%BA%BF%E7%A8%8B)
  - [GUI](#gui)
  - [Hardware](#hardware)
  - [图像](#%E5%9B%BE%E5%83%8F)
  - [物联网](#%E7%89%A9%E8%81%94%E7%BD%91)
  - [日志](#%E6%97%A5%E5%BF%97)
  - [机器学习](#%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0)
  - [消息传递](#%E6%B6%88%E6%81%AF%E4%BC%A0%E9%80%92)
  - [其他](#%E5%85%B6%E4%BB%96)
  - [自然语言处理](#%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E5%A4%84%E7%90%86)
  - [网络](#%E7%BD%91%E7%BB%9C)
  - [OpenGL](#opengl)
  - [ORM](#orm)
  - [包管理](#%E5%8C%85%E7%AE%A1%E7%90%86)
  - [查询语言](#%E6%9F%A5%E8%AF%A2%E8%AF%AD%E8%A8%80)
  - [资源嵌入](#%E8%B5%84%E6%BA%90%E5%B5%8C%E5%85%A5)
  - [科学与数据分析](#%E7%A7%91%E5%AD%A6%E4%B8%8E%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90)
  - [安全性](#%E5%AE%89%E5%85%A8%E6%80%A7)
  - [序列化](#%E5%BA%8F%E5%88%97%E5%8C%96)
  - [服务器应用程序](#%E6%9C%8D%E5%8A%A1%E5%99%A8%E5%BA%94%E7%94%A8%E7%A8%8B%E5%BA%8F)
  - [模板引擎](#%E6%A8%A1%E6%9D%BF%E5%BC%95%E6%93%8E)
  - [测试](#%E6%B5%8B%E8%AF%95)
  - [文本处理](#%E6%96%87%E6%9C%AC%E5%A4%84%E7%90%86)
  - [第三方API](#%E7%AC%AC%E4%B8%89%E6%96%B9api)
  - [工具库](#%E5%B7%A5%E5%85%B7%E5%BA%93)
  - [验证](#%E9%AA%8C%E8%AF%81)
  - [版本控制](#%E7%89%88%E6%9C%AC%E6%8E%A7%E5%88%B6)
  - [视频](#%E8%A7%86%E9%A2%91)
  - [Web框架](#web%E6%A1%86%E6%9E%B6)
    - [中间件](#%E4%B8%AD%E9%97%B4%E4%BB%B6)
      - [实际中间件](#%E5%AE%9E%E9%99%85%E4%B8%AD%E9%97%B4%E4%BB%B6)
      - [创建HTTP中间件的库](#%E5%88%9B%E5%BB%BAhttp%E4%B8%AD%E9%97%B4%E4%BB%B6%E7%9A%84%E5%BA%93)
    - [路由器](#%E8%B7%AF%E7%94%B1%E5%99%A8)
  - [Windows](#windows)
  - [XML](#xml)
- [工具](#%E5%B7%A5%E5%85%B7)
  - [代码分析](#%E4%BB%A3%E7%A0%81%E5%88%86%E6%9E%90)
  - [编辑器插件](#%E7%BC%96%E8%BE%91%E5%99%A8%E6%8F%92%E4%BB%B6)
  - [GO生成工具](#go%E7%94%9F%E6%88%90%E5%B7%A5%E5%85%B7)
  - [Go工具](#go%E5%B7%A5%E5%85%B7)
  - [软件包](#%E8%BD%AF%E4%BB%B6%E5%8C%85)
    - [DevOps工具](#devops%E5%B7%A5%E5%85%B7)
    - [其他软件](#%E5%85%B6%E4%BB%96%E8%BD%AF%E4%BB%B6)
- [资源](#%E8%B5%84%E6%BA%90)
  - [基准点](#%E5%9F%BA%E5%87%86%E7%82%B9)
  - [会议](#%E4%BC%9A%E8%AE%AE)
  - [电子书](#%E7%94%B5%E5%AD%90%E4%B9%A6)
  - [Gophers地鼠](#gophers%E5%9C%B0%E9%BC%A0)
  - [见面会](#%E8%A7%81%E9%9D%A2%E4%BC%9A)
  - [推特](#%E6%8E%A8%E7%89%B9)
  - [网站](#%E7%BD%91%E7%AB%99)
    - [教程](#%E6%95%99%E7%A8%8B)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## 音频与音乐

*用于操作音频的库.*

-   [EasyMIDI](https://github.com/algoGuy/EasyMIDI)EasyMIDI是使用标准MIDI文件(SMF)的简单可靠的库.
-   [flac](https://github.com/eaburns/flac)-本地GO FLAC解码器.
-   [flac](https://github.com/mewkiz/flac)-本地GO FLAC解码器.
-   [gaad](https://github.com/Comcast/gaad)-本地GO-AAC比特流解析器.
-   [go-sox](https://github.com/krig/go-sox)-LIBOSX绑定为GO.
-   [go_mediainfo](https://github.com/zhulik/go_mediainfo)为GO绑定.
-   [gosamplerate](https://github.com/dh1tw/gosamplerate)-GO的绑定.
-   [id3v2](https://github.com/bogem/id3v2)-快速、稳定的ID3解析和写入库.
-   [malgo](https://github.com/gen2brain/malgo)-迷你音频库.
-   [minimp3](https://github.com/tosone/minimp3)-轻量级MP3解码器库.
-   [mix](https://github.com/go-mix/mix)-基于序列的本地音乐混音器的音乐应用程序.
-   [mp3](https://github.com/tcolgate/mp3)-本地转到MP3解码器.
-   [music-theory](https://github.com/go-music-theory/music-theory)-音乐理论模型.
-   [PortAudio](https://github.com/gordonklaus/portaudio)-为PARTAUDIO音频I/O库绑定.
-   [portmidi](https://github.com/rakyll/portmidi)-为PUTMIDI绑定.
-   [taglib](https://github.com/wtolson/go-taglib)-为TAGLIB进行绑定.
-   [vorbis](https://github.com/mccoyst/vorbis)-"本地"GO VRBIS解码器(使用CGO,但没有依赖项).
-   [waveform](https://github.com/mdlayher/waveform)-能够从音频流生成波形图像的GO封装.

## 认证与OAuth

*用于实现认证方案的库.*

-   [authboss](https://github.com/volatiletech/authboss)-模块化的Web认证系统.它试图移除尽可能多的样板和"硬东西",以便每次在Go中启动新的Web项目时,都可以插入、配置并开始构建应用程序,而无需每次都构建身份验证系统.
-   [branca](https://github.com/hako/branca)- Golang实施布兰卡令牌.
-   [casbin](https://github.com/hsluoyz/casbin)-支持ACL、RBAC、ABAC等访问控制模型的授权库.
-   [cookiestxt](https://github.com/mengzhuo/cookiestxt)-提供COOKI.TXT文件格式的解析器.
-   [Go-AWS-Auth](https://github.com/smartystreets/go-aws-auth)AWS(Amazon WebServices)请求签名库.
-   [go-jose](https://github.com/square/go-jose)-完全完成若泽工作组的JSON Web令牌、JSON Web签名和JSON Web加密规范.
-   [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server)-独立的,符合规范的,在Golang编写的OAuth2服务器.
-   [gologin](https://github.com/dghubble/gologin)可链接的处理程序,用于与OAuth1和OAuth2身份验证提供者进行登录.
-   [gorbac](https://github.com/mikespook/gorbac)-在Golang中提供一种轻量级的基于角色的访问控制(RBAC)实现.
-   [goth](https://github.com/markbates/goth)-使用OAuthand OAuth2提供了一种简单、干净和惯用的方法.处理多个供应商.
-   [httpauth](https://github.com/goji/httpauth)- HTTP认证中间件.
-   [jwt](https://github.com/robbert229/jwt)- JSON Web令牌(JWT)的清洁和易于使用的实现.
-   [jwt](https://github.com/pascaldekloe/jwt)-轻量级JSON Web令牌(JWT)库.
-   [jwt-auth](https://github.com/adam-hanna/jwt-auth)JWT中间件,用于Golang HTTP服务器,具有多种配置选项.
-   [jwt-go](https://github.com/dgrijalva/jwt-go)Golang JSON Web令牌(JWT)的实现.
-   [loginsrv](https://github.com/tarent/loginsrv)JWT登录微服务,带有可后端的插件,如OAuth2(Github)、HTSpWD、OSIAM.
-   [oauth2](https://github.com/golang/oauth2)- GoAuth2的继承者.通用的OAuth2包附带JWT、谷歌API、计算引擎和App Engine支持.
-   [osin](https://github.com/RangelReale/osin)- GangangOAuth2服务器库.
-   [paseto](https://github.com/o1egl/paseto)Golang平台不可知安全令牌(Paseto)的实现
-   [permissions2](https://github.com/xyproto/permissions2)-用于跟踪用户、登录状态和权限的库.使用安全Cookie和BCRIPT.
-   [rbac](https://github.com/zpatrick/rbac)-面向GO应用的极简性RBAC包.
-   [securecookie](https://github.com/chmike/securecookie)-高效的安全Cookie编码/解码.
-   [session](https://github.com/icza/session)-为Web服务器进行会话管理(包括支持谷歌AppEngine—GAE).
-   [sessiongate-go](https://github.com/f0rmiga/sessiongate-go)-使用SSESIGATE RADIS模块进行会话管理.
-   [sessions](https://github.com/adam-hanna/sessions)-为GO-HTTP服务器提供简单、高性能、高度可定制的会话服务.
-   [signedvalue](https://github.com/sashka/signedvalue)-符号和时间戳字符串兼容[Tornado's](https://github.com/tornadoweb/tornado) `create_signed_value`,`decode_signed_value`因此`set_secure_cookie`和`get_secure_cookie`.
-   [yubigo](https://github.com/GeertJohan/yubigo)-提供一个简单API的YuByKy客户端包,将YuBICO YuBIKEY集成到GO应用程序中.

## 命令行

### 标准CLI

*用于建立标准或基本命令行应用程序的库.*

-   [argparse](https://github.com/akamensky/argparse)命令行参数分析器,由Python的AgPARSE模块启发.
-   [argv](https://github.com/cosiner/argv)-使用BASH语法将GO库拆分为参数数组.
-   [cli](https://github.com/mkideal/cli)-基于GalangStutt标签的功能丰富且易于使用的命令行包.
-   [cli](https://github.com/teris-io/cli)-简单而完整的API,用于构建GO中的命令行接口.
-   [cli-init](https://github.com/tcnksm/gcli)-开始构建Golang命令行应用程序的简单方法.
-   [climax](http://github.com/tucnak/climax)-替代的CLI与"人脸",在精神的GO命令.
-   [cobra](https://github.com/spf13/cobra)-现代GO CLI交互的指挥官.
-   [commandeer](https://github.com/jaffee/commandeer)-DEV友好的CLI应用程序:基于结构域和标记设置标志、默认值和用法.
-   [complete](https://github.com/posener/complete)-在GO+GO命令BASH完成中编写BASH完成.
-   [docopt.go](https://github.com/docopt/docopt.go)命令行参数分析器,它会让你微笑.
-   [drive](https://github.com/odeke-em/drive)谷歌驱动客户端的命令行.
-   [env](https://github.com/codingconcepts/env)基于标签的结构环境配置.
-   [flag](https://github.com/cosiner/flag)- GO支持子命令的简单但强大的命令行选项解析库.
-   [flaggy](https://github.com/integrii/flaggy)-具有优秀子命令支持的健壮的和惯用的标志包.
-   [flagvar](https://github.com/sgreben/flagvar)- GO标准的标志参数类型的集合`flag`包裹.
-   [go-arg](https://github.com/alexflint/go-arg)在GO中基于结构的参数解析.
-   [go-commander](https://github.com/yitsushi/go-commander)GO库简化CLI工作流程
-   [go-flags](https://github.com/jessevdk/go-flags)转到命令行选项解析器.
-   [gocmd](https://github.com/devfacet/gocmd)-用于构建命令行应用程序的GO库.
-   [kingpin](https://github.com/alecthomas/kingpin)-支持子命令的命令行和标志分析器.
-   [liner](https://github.com/peterh/liner)-用于命令行接口的读行类库.
-   [mitchellh/cli](https://github.com/mitchellh/cli)-用于实现命令行接口的GO库.
-   [mow.cli](https://github.com/jawher/mow.cli)-用复杂标志和参数解析和验证来构建CLI应用程序的GO库.
-   [pflag](https://github.com/spf13/pflag)-在GO的标志包中进行替换,实现POSIX/GNU样式-标志.
-   [readline](https://github.com/chzyer/readline)-纯GORANG实现,它提供了MIT许可下GNU读行中的大多数特征.
-   [sflags](https://github.com/octago/sflags)基于结构的标志发生器,用于标志、URFAV/CLI、PFLAG、COBRA、主销和其他库.
-   [strumt](https://github.com/antham/strumt)-创建即时链接库.
-   [ukautz/clif](https://github.com/ukautz/clif)-小型命令行接口框架.
-   [urfave/cli](https://github.com/urfave/cli)-简单,快速,有趣的软件包构建命令行应用程序在GO(以前的CODEANGSTAS/CLI).
-   [wlog](https://github.com/dixonwille/wlog)-支持跨平台颜色和并发的简单日志接口.
-   [wmenu](https://github.com/dixonwille/wmenu)-易于使用的CLI应用程序菜单结构,提示用户做出选择.

### 高级Console UIs

*用于构建Console 应用程序和Console 用户界面的库.*

-   [aurora](https://github.com/logrusorgru/aurora)支持FMT.Prtff/SaveTf的ANSI终端颜色.
-   [cfmt](https://github.com/mingrammer/cfmt)-上下文FMT由引导颜色类启发.
-   [chalk](https://github.com/ttacon/chalk)-用于美化终端/控制台输出的直观包.
-   [color](https://github.com/fatih/color)-彩色终端输出的通用封装.
-   [colourize](https://github.com/TreyBastian/colourize)-为终端中的ANSI颜色文本去库.
-   [ctc](https://github.com/wzshiming/ctc)-非侵入性跨平台终端颜色库不需要修改打印方法.
-   [go-ataman](https://github.com/workanator/go-ataman)-在终端中绘制ANSI彩色文本模板的GO库.
-   [go-colorable](https://github.com/mattn/go-colorable)Windows的可着色写入器.
-   [go-colortext](https://github.com/daviddengcn/go-colortext)转到终端的颜色输出库.
-   [go-isatty](https://github.com/mattn/go-isatty)-为戈朗服务.
-   [go-prompt](https://github.com/c-bata/go-prompt)图书馆为构建强大的互动提示,受到启发[python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit).
-   [gocui](https://github.com/jroimartin/gocui)-极简主义GO库,旨在创建控制台用户界面.
-   [gommon/color](https://github.com/labstack/gommon/tree/master/color)样式的终端文本.
-   [gookit/color](https://github.com/gookit/color)-终端显色工具库,支持16种颜色,256种颜色,RGB颜色渲染输出,兼容Windows.
-   [mpb](https://github.com/vbauerster/mpb)-用于终端应用的多进度条.
-   [progressbar](https://github.com/schollz/progressbar)-在每个操作系统中工作的基本线程安全进度条.
-   [simpletable](https://github.com/alexeyco/simpletable)-终端中带有GO的简单表.
-   [tabular](https://github.com/InVisionApp/tabular)从命令行实用工具打印ASCII表,而不需要将大量数据传递给API.
-   [termbox-go](https://github.com/nsf/termbox-go)Termbox是一个用于创建跨平台的基于文本的接口的库.
-   [termtables](https://github.com/apcera/termtables)去红宝石图书馆的港口[terminal-tables](https://github.com/tj/terminal-table)用于简单的ASCII表生成以及提供标记和HTML输出.
-   [termui](https://github.com/gizak/termui)基于终端的终端仪表板**畸胎**受到启发[blessed-contrib](https://github.com/yaronn/blessed-contrib).
-   [tui-go](https://github.com/marcusolsson/tui-go)去UI库来构建丰富的终端应用程序.
-   [uilive](https://github.com/gosuri/uilive)-用于实时更新终端输出的库.
-   [uiprogress](https://github.com/gosuri/uiprogress)-在终端应用程序中呈现进度条的灵活库.
-   [uitable](https://github.com/gosuri/uitable)-使用表格数据提高终端应用程序的可读性.

## 配置

*用于配置解析的库.*

-   [config](https://github.com/olebedev/config)JSON或YAML配置包,包含环境变量和标志解析.
-   [configure](https://github.com/paked/configure)-通过多个源提供配置,包括JSON、标志和环境变量.
-   [confita](https://github.com/heetch/confita)将级联从多个后端加载到结构中.
-   [conflate](https://github.com/miracl/conflate)-库/工具,用于合并来自任意URL的多个JSON/YAML/TOML文件,根据JSON模式进行验证,以及应用模式中定义的默认值.
-   [env](https://github.com/caarlos0/env)-解析环境变量以构造(默认值)结构.
-   [envcfg](https://github.com/tomazk/envcfg)-联合编组环境变量以构造结构.
-   [envconf](https://github.com/ian-kent/envconf)-从环境配置.
-   [envconfig](https://github.com/vrischmann/envconfig)-从环境变量中读取配置.
-   [envh](https://github.com/antham/envh)-帮助管理环境变量.
-   [gcfg](https://github.com/go-gcfg/gcfg)-将INI风格的配置文件读入GO结构;支持用户定义的类型和子段.
-   [go-up](https://github.com/ufoscout/go-up)-具有递归占位符解析和无魔法的简单配置库.
-   [goConfig](https://github.com/crgimenes/goConfig)-将结构解析为输入,并用来自命令行、环境变量和配置文件的参数填充该结构的字段.
-   [godotenv](https://github.com/joho/godotenv)Ruby DoTeV库的端口(加载环境变量)`.env`)
-   [gofigure](https://github.com/ian-kent/gofigure)转到应用程序配置很容易.
-   [gone/jconf](https://github.com/One-com/gone/tree/master/jconf)-模块化JSON配置.保持配置结构以及它们配置的代码,并将解析委托给子模块,而不牺牲完整的配置序列化.
-   [gookit/config](https://github.com/gookit/config)-应用配置管理(加载,获取,设置).支持JSON、YAML、TAML、INI、HCL.多文件加载,数据覆盖合并.
-   [hjson](https://github.com/hjson/hjson-go)人类JSON,是人类的配置文件格式.轻松的语法,更少的错误,更多的评论.
-   [ingo](https://github.com/schachmat/ingo)标志保存在INI类配置文件中.
-   [ini](https://github.com/go-ini/ini)-去读和写INI文件.
-   [joshbetz/config](https://github.com/joshbetz/config)-用于解析环境变量、JSON文件并在FIZUP上自动加载的GO小配置库.
-   [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig)从环境变量管理配置数据的GO库.
-   [mini](https://github.com/sasbury/mini)Golang包解析ini样式的配置文件.
-   [sprbox](https://github.com/oblq/sprbox)-构建环境感知工具箱工厂和不可知配置分析器(YAML、TAML、JSON和环境VARS).
-   [store](https://github.com/tucnak/store)-为GO提供轻量级配置管理器.
-   [viper](https://github.com/spf13/viper)-用尖牙进行配置.
-   [xdg](https://github.com/OpenPeeDeeP/xdg)跨平台软件包[XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html).

## 持续集成

*持续集成的帮助工具.*

-   [drone](https://github.com/drone/drone)-无人机是一个建立在DOKER上的连续集成平台,写在GO中.
-   [duci](https://github.com/duck8823/duci)一个简单的CI服务器不需要特定于域的语言.
-   [gomason](https://github.com/nikogura/gomason)-从干净的工作区测试、构建、签署和发布您的二进制二进制文件.
-   [goveralls](https://github.com/mattn/goveralls)为Curral.IO连续代码覆盖跟踪系统进行GO集成.
-   [overalls](https://github.com/go-playground/overalls)-多包GO项目覆盖配置文件的工具,如政府.
-   [roveralls](https://github.com/LawrenceWoodman/roveralls)-递归覆盖测试工具.

## CSS预处理器

*用于预处理CSS文件的库.*

-   [c6](https://github.com/c9s/c6)-高性能的SASS兼容编译器,用GO编写.
-   [gcss](https://github.com/yosssi/gcss)-纯GO CSS预处理器.
-   [go-libsass](https://github.com/wellington/go-libsass)-去包装100%个兼容SASS的LIPSASS项目.

## 数据结构

*GO中的通用数据结构和算法.*

-   [algorithms](https://github.com/shady831213/algorithms)算法和数据结构.
-   [binpacker](https://github.com/zhuangsirui/binpacker)二进制打包器和解压器帮助用户构建自定义二进制流.
-   [bit](https://github.com/yourbasic/bit)- Golang设置数据结构,具有额外的比特删除功能.
-   [bitset](https://github.com/willf/bitset)-去实现比特集.
-   [bloom](https://github.com/zhenjl/bloom)在GO中实现Bloom过滤器.
-   [bloom](https://github.com/yourbasic/bloom)- Golang Bloom滤波器实现.
-   [boomfilters](https://github.com/tylertreat/BoomFilters)-用于处理连续无界流的概率数据结构.
-   [concurrent-writer](https://github.com/free/concurrent-writer)-高度并发跌落替换`bufio.Writer`.
-   [conjungo](https://github.com/InVisionApp/conjungo)-一个小的、强大的和灵活的合并库.
-   [count-min-log](https://github.com/seiflotfy/count-min-log)-Go实现Count-Min-Log示意图:使用近似计数器进行近似计数(类似于Count-Min示意图,但是使用较少的内存).
-   [cuckoofilter](https://github.com/seiflotfy/cuckoofilter)布谷鸟过滤器:在GO中实现计数布隆过滤器的一种好方法.
-   [deque](https://github.com/gammazero/deque)快速环缓冲器DIQE(双端队列).
-   [encoding](https://github.com/zhenjl/encoding)-用于GO的整数压缩库.
-   [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree)-实现自适应基数树.
-   [go-datastructures](https://github.com/Workiva/go-datastructures)-收集有用、性能和线程安全的数据结构.
-   [go-ef](https://github.com/amallia/go-ef)- Elias Fano编码的GO实现.
-   [go-geoindex](https://github.com/hailocab/go-geoindex)内存中的GEO索引.
-   [go-mcache](https://github.com/OrlovEvgeny/go-mcache)快速内存键:值存储/缓存库.指针缓存.
-   [go-rquad](https://github.com/aurelien-rainone/go-rquad)-区域四叉树,具有有效的点定位和邻居发现.
-   [gods](https://github.com/emirpasic/gods)-去数据结构.容器,集合,列表,Stacks,地图,双底盘,树木,HashSet等.
-   [golang-set](https://github.com/deckarep/golang-set)线程安全和非线程安全的高性能设置为GO.
-   [goset](https://github.com/zoumo/goset)-用于GO的有用集合集合实现.
-   [goskiplist](https://github.com/ryszard/goskiplist)在GO中跳过列表实现.
-   [gota](https://github.com/kniren/gota)-实现数据流、系列和数据争用方法.
-   [hilbert](https://github.com/google/hilbert)-Go用于将值映射到空间填充曲线,如希尔伯特和Peao曲线.
-   [hyperloglog](https://github.com/axiomhq/hyperloglog)-用稀疏、LogLoggβ偏置校正和尾迹空间缩减实现超对数格.
-   [levenshtein](https://github.com/agext/levenshtein)- LevsHeTin距离和相似度量与可定制的编辑成本和温克勒类似奖金的共同前缀.
-   [levenshtein](https://github.com/agnivade/levenshtein)-实现计算LaveStin距离的GO.
-   [mafsa](https://github.com/smartystreets/mafsa)MA-FSA实现,具有最小完美散列.
-   [merkletree](https://github.com/cbergoon/merkletree)-实现Melkle树,提供对数据结构内容的有效和安全的验证.
-   [mspm](https://github.com/BlackRabbitt/mspm)-多串模式匹配算法的信息检索.
-   [pipeline](https://github.com/hyfather/pipeline)-一种带风扇和扇出的管道的实现.
-   [roaring](https://github.com/RoaringBitmap/roaring)-实现压缩比特集的GO包.
-   [set](https://github.com/StudioSol/set)-使用Link KeasMMAP实现GO中的简单数据结构.
-   [skiplist](https://github.com/MauriceGit/skiplist)-非常快的SKIPLIST实现.
-   [skiplist](https://github.com/gansidui/skiplist)在GO中实现SKIPPLIST.
-   [trie](https://github.com/derekparker/trie)-在GO中实现TIE.
-   [ttlcache](https://github.com/diegobernardes/ttlcache)内存中的LRU字符串接口{}映射为Galang.
-   [willf/bloom](https://github.com/willf/bloom)GO过滤器实现Bloom过滤器.

## 数据库

*GO实现的数据库.*

-   [badger](https://github.com/dgraph-io/badger)-快速键值存储在GO中.
-   [BigCache](https://github.com/allegro/bigcache)-用于千兆字节数据的高效键/值缓存.
-   [bolt](https://github.com/boltdb/bolt)-GO的低级密钥/值数据库.
-   [buntdb](https://github.com/tidwall/buntdb)-快速、可嵌入、内存中的键/值数据库,用于自定义索引和空间支持.
-   [cache2go](https://github.com/muesli/cache2go)内存键:支持基于超时的自动失效的值缓存.
-   [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache)BigCHIGH与集群支持和个别项目到期.
-   [cockroach](https://github.com/cockroachdb/cockroach)-可伸缩的、地理复制的、事务性的数据存储.
-   [couchcache](https://github.com/codingsince1985/couchcache)-由CoucBaseServer支持的REST高速缓存微服务.
-   [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL)- CovenantSQL是BooStand上的SQL数据库.
-   [dgraph](https://github.com/dgraph-io/dgraph)-可扩展、分布式、Low Latency、高吞吐量图形数据库.
-   [diskv](https://github.com/peterbourgon/diskv)-自带的磁盘备份键值存储.
-   [eliasdb](https://github.com/krotik/eliasdb)-无依赖、事务性图形数据库,具有REST API、短语搜索和SQL类查询语言.
-   [forestdb](https://github.com/couchbase/goforestdb)-为FordestDB绑定.
-   [GCache](https://github.com/bluele/gcache)-缓存库,支持可缓存的高速缓存、LFU、LRU和ARC.
-   [go-cache](https://github.com/pmylund/go-cache)内存中的键:值存储/缓存(类似于Mycache)的GO库,适用于单机应用程序.
-   [goleveldb](https://github.com/syndtr/goleveldb)-实现[LevelDB](https://github.com/google/leveldb)GO中的关键字/值数据库.
-   [gorocksdb](https://github.com/kapitan-k/gorocksdb)- Gorocksdb是一个包装[RocksDB](https://rocksdb.org)写在GO.
-   [groupcache](https://github.com/golang/groupcache)GypCache是一个缓存和缓存填充库,旨在在很多情况下替代Mycache.
-   [influxdb](https://github.com/influxdb/influxdb)-度量、事件和实时分析的可扩展数据存储.
-   [ledisdb](https://github.com/siddontang/ledisdb)Ledisdb是一个基于LealDB的高性能NoSQL的RIDS.
-   [levigo](https://github.com/jmhodges/levigo)-LeVIO是LealDB的打包器.
-   [moss](https://github.com/couchbase/moss)- Moss是一个简单的LSM密钥值存储引擎,用100% GO编写.
-   [piladb](https://github.com/fern4lvarez/piladb)-基于堆栈数据结构的轻量级REST数据库引擎.
-   [prometheus](https://github.com/prometheus/prometheus)-监控系统和时间序列数据库.
-   [rqlite](https://github.com/rqlite/rqlite)-基于SQLite构建的轻量级、分布式、关系数据库.
-   [Scribble](https://github.com/nanobox-io/golang-scribble)-小型平面文件JSON存储.
-   [slowpoke](https://github.com/recoilme/slowpoke)-具有持久性的键值存储.
-   [tempdb](https://github.com/rafaeljesus/tempdb)-用于临时项的键值存储.
-   [tidb](https://github.com/pingcap/tidb)- TiDB是分布式SQL数据库.灵感来自谷歌F1的设计.
-   [tiedot](https://github.com/HouzuoGuo/tiedot)-由Golang提供的NoSQL数据库.
-   [Vasto](https://github.com/chrislusf/vasto)-分布式高性能密钥值存储.在磁盘上.最终一致.哈.能够在没有服务中断的情况下生长或收缩.

*数据库模式迁移.*

-   [darwin](https://github.com/GuiaBolso/darwin)GO数据库模式演化库.
-   [go-fixtures](https://github.com/RichardKnop/go-fixtures)为Golang优秀的内置数据库/SQL库提供Django风格的夹具.
-   [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations)一个GO包,用于帮助用GO PG/PG编写迁移.
-   [gondolier](https://github.com/emvicom/gondolier)Gondolier是一个使用结构体自动迁移数据库模式的库.
-   [goose](https://github.com/steinbacher/goose)-数据库迁移工具.您可以通过创建增量SQL或GO脚本来管理数据库的演化.
-   [gormigrate](https://github.com/go-gormigrate/gormigrate)GORM ORM的数据库模式迁移助手.
-   [migrate](https://github.com/golang-migrate/migrate)-数据库迁移.CLI和Golang图书馆.
-   [pravasan](https://github.com/pravasan/pravasan)-简单的迁移工具-目前MySQL,但计划很快支持PistGRs,SQLite,MunGDB等.
-   [soda](https://github.com/gobuffalo/pop/tree/master/soda)-数据库迁移、创建、ORM等.对于MySQL、PostgreSQL和SQLite.
-   [sql-migrate](https://github.com/rubenv/sql-migrate)-数据库迁移工具.允许使用GO BiDATA将迁移嵌入到应用程序中.

*数据库工具.*

-   [chproxy](https://github.com/Vertamedia/chproxy)-用于点击数据库的HTTP代理.
-   [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk)-收集小实例并向CLSKEYHOST服务器发送大请求.
-   [go-mysql](https://github.com/siddontang/go-mysql)GO工具集来处理MySQL协议和复制.
-   [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch)-自动将MySQL数据同步到弹性搜索中.
-   [kingshard](https://github.com/flike/kingshard)金山是Golang提供的MySQL的高性能代理.
-   [myreplication](https://github.com/2tvenom/myreplication)MySQL二进制日志复制侦听器.支持语句和行的复制.
-   [orchestrator](https://github.com/github/orchestrator)MySQL复制拓扑管理器和可视化工具.
-   [pgweb](https://github.com/sosedoff/pgweb)-基于Web的PostgreSQL数据库浏览器.
-   [prep](https://github.com/hexdigest/prep)-使用准备好的SQL语句而不更改代码.
-   [pREST](https://github.com/nuveo/prest)-从任何PostgreSQL数据库提供REST API.
-   [rwdb](https://github.com/andizzle/rwdb)RWDB提供多个数据库服务器安装的读取副本能力.
-   [vitess](https://github.com/youtube/vitess)VITESS提供了便于大规模Web服务的MySQL数据库缩放的服务器和工具.

*SQL查询构建器,用于构建和使用SQL的库.*

-   [dat](https://github.com/mgutz/dat)-去PASGRESS数据访问工具包.
-   [Dotsql](https://github.com/gchaincl/dotsql)GO库,帮助您在一个地方保存SQL文件并轻松使用它们.
-   [gendry](https://github.com/didi/gendry)-无创SQL生成器和强大的数据绑定器.
-   [godbal](https://github.com/xujiajun/godbal)-数据库抽象层(DBAL)为GO.支持SQL Builder并轻松获取结果.
-   [goqu](https://github.com/doug-martin/goqu)-惯用的SQL生成器和查询库.
-   [igor](https://github.com/galeone/igor)PostgreSQL抽象层,它支持高级功能并使用类似GRUM的语法.
-   [ormlite](https://github.com/pupizoid/ormlite)-轻量级包,包含一些类似于ORM的特性和SQLite数据库的帮助器.
-   [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx)-强大的数据检索方法以及DB不可知查询构建能力.
-   [scaneo](https://github.com/variadico/scaneo)生成GO代码,将数据库行转换为任意结构.
-   [sqrl](https://github.com/elgris/sqrl)SQL查询生成器,具有改进性能的松鼠叉.
-   [Squirrel](https://github.com/Masterminds/squirrel)帮助您构建SQL查询的GO库.
-   [xo](https://github.com/knq/xo)-基于现有的模式定义或支持PostgreSQL、MySQL、SQLite、Oracle和Microsoft SQL Server的自定义查询为数据库生成惯用Go代码.

## 数据库驱动程序

*用于连接和操作数据库的库.*

-   关系数据库

    -   [avatica](https://github.com/apache/calcite-avatica-go)Apache AvaTICA/FieldSQL驱动程序用于数据库/SQL.
    -   [bgc](https://github.com/viant/bgc)BigQuo的数据存储连接为GO.
    -   [firebirdsql](https://github.com/nakagami/firebirdsql)火鸟RDBMS SQL驱动程序为GO.
    -   [go-adodb](https://github.com/mattn/go-adodb)微软的ActiveX对象数据库驱动程序GO,使用Dava/SQL.
    -   [go-mssqldb](https://github.com/denisenkom/go-mssqldb)微软MSSQL驱动程序为GO.
    -   [go-oci8](https://github.com/mattn/go-oci8)使用数据库/SQL的GO Oracle驱动程序.
    -   [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql)-MySQL驱动程序.
    -   [go-sqlite3](https://github.com/mattn/go-sqlite3)SQULe3驱动程序,使用数据库/SQL.
    -   [gofreetds](https://github.com/minus5/gofreetds)微软MSSQL驱动程序.Go包装[FreeTDS](http://www.freetds.org).
    -   [goracle](https://github.com/go-goracle/goracle)-Oracle驱动程序,使用ODPI-C驱动程序
    -   [pgx](https://github.com/jackc/pgx)- PostgreSQL驱动程序支持超出数据库/SQL所公开的特性.
    -   [pq](https://github.com/lib/pq)-用于数据库/SQL的纯GO PergRes驱动程序.

-   NoSQL数据库

    -   [aerospike-client-go](https://github.com/aerospike/aerospike-client-go)在GO语言中的SalpPIKE客户端.
    -   [arangolite](https://github.com/solher/arangolite)- ArangoDB的轻量级Gangon驱动程序.
    -   [asc](https://github.com/viant/asc)-用于SotoPik的数据存储连接.
    -   [cachego](https://github.com/fabiorphp/cachego)-多个驱动程序的Golang缓存组件.
    -   [cayley](https://github.com/google/cayley)-支持多个后端的图形数据库.
    -   [dsc](https://github.com/viant/dsc)- SQL、NoSQL、结构化文件的数据存储连接.
    -   [dynago](https://github.com/underarmour/dynago)DyNaGo是DunDoDB的最小惊喜客户端的原理.
    -   [go-couchbase](https://github.com/couchbase/go-couchbase)- CoucBaseClient中的GO.
    -   [go-couchdb](https://github.com/fjl/go-couchdb)-另一个用于GO的CouCHDB HTTP API包装器.
    -   [gocb](https://github.com/couchbase/gocb)官方沙发底座SDK.
    -   [gocql](http://gocql.github.io)为Apache Casdand的GO语言驱动程序.
    -   [godscache](https://github.com/defcronyke/godscache)-谷歌云平台GoestDaStor包的包装器,使用MycCurp添加缓存.
    -   [gomemcache](https://github.com/bradfitz/gomemcache/)-用于GO编程语言的MeCAMP客户端库.
    -   [gorethink](https://github.com/dancannon/gorethink)-ReTunkDB的GO语言驱动程序.
    -   [goriak](https://github.com/zegl/goriak)-RIAK KV的GO语言驱动程序.
    -   [mgo](https://github.com/globalsign/mgo)-Go语言的MongoDB驱动程序,它按照标准的Go习惯用法,在非常简单的API下实现丰富且经过良好测试的特性选择
    -   [mongo-go-driver](https://github.com/mongodb/mongo-go-driver)GO语言的官方MangoDB驱动程序.
    -   [neo4j](https://github.com/cihangir/neo4j)Golang的NeN4J REST API绑定.
    -   [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO)在GangangNe4J休息客户端.
    -   [neoism](https://github.com/jmcvetta/neoism)Golang的NeN4J客户端.
    -   [redigo](https://github.com/gomodule/redigo)- Redigo是ReDIS数据库的GO客户端.
    -   [redis](https://github.com/go-redis/redis)- Golang的Read客户端.
    -   [redis](https://github.com/hoisie/redis)-简单,强大的Read客户端为GO.
    -   [redis](https://github.com/bsm/redeo)-ReDIS协议兼容的TCP服务器/服务.
    -   [xredis](https://github.com/shomali11/xredis)-类型化,可定制,干净,易于使用的ReIS客户端.

-   搜索和分析数据库.
    -   [bleve](https://github.com/blevesearch/bleve)-用于GO的现代文本索引库.
    -   [elastic](https://github.com/olivere/elastic)-弹性搜索客户端.
    -   [elasticsql](https://github.com/cch123/elasticsql)在GO中将SQL转换为弹性搜索DSL.
    -   [elastigo](https://github.com/mattbaird/elastigo)-弹性搜索客户端库.
    -   [goes](https://github.com/OwnLocal/goes)-库与弹性搜索交互.
    -   [riot](https://github.com/go-ego/riot)-开源、分布式、简单高效的搜索引擎
    -   [skizze](https://github.com/seiflotfy/skizze)-概率数据结构服务和存储.

## 日期和时间

*用于处理日期和时间的库.*

-   [carbon](https://github.com/uniplaces/carbon)-简单的时间扩展与许多UTIL方法,从PHP碳库移植.
-   [date](https://github.com/rickb777/date)-增加使用日期、日期范围、时间跨度、周期和时间的时间.
-   [dateparse](https://github.com/araddon/dateparse)-解析日期不预先知道格式.
-   [durafmt](https://github.com/hako/durafmt)为GO提供持续时间格式化库.
-   [feiertage](https://github.com/wlbr/feiertage)-在德国计算公共假日的函数集,包括德国州(Bundl Sund)的专门化.像复活节,圣灵降临节,感恩节…
-   [go-persian-calendar](https://github.com/yaa110/go-persian-calendar)-波斯(太阳HijRi)日历在GO(GORANG)中的实现.
-   [go-sunrise](https://github.com/nathan-osman/go-sunrise)计算给定位置的日出和日落时间.
-   [goweek](https://github.com/grsmv/goweek)图书馆在GORANG中与周实体一起工作.
-   [Kair](https://github.com/GuilhermeCaruso/Kair)-日期和时间-戈朗格式化库.
-   [now](https://github.com/jinzhu/now)现在是戈朗的时间工具包.
-   [NullTime](https://github.com/kirillDanshin/nulltime)可空的`time.Time`.
-   [strftime](https://github.com/awoodbeck/strftime)-C99兼容的STRFTIMER格式化程序.
-   [timespan](https://github.com/SaidinWoT/timespan)-与时间间隔相互作用,定义为开始时间和持续时间.
-   [timeutil](https://github.com/leekchan/timeutil)-有用的扩展(TimeDelad,StfTimes,…)到Galang'的时间包.
-   [tuesday](https://github.com/osteele/tuesday)Ruby兼容的StfTime函数.

## 分布式系统

*有助于构建分布式系统的包.*

-   [celeriac](https://github.com/svcavallar/celeriac.v1)-图书馆增加支持互动和监测芹菜工人,任务和事件在GO.
-   [consistent](https://github.com/buraksezer/consistent)-有界负载的一致散列.
-   [digota](https://github.com/digota/digota)GRPC电子商务微服务.
-   [drmaa](https://github.com/dgruber/drmaa)-基于DRMAA标准的集群调度程序的作业提交库.
-   [emitter-io](https://github.com/emitter-io/emitter)-使用MQTT、WebSoCKET和Lead构建的高性能、分布式、安全和低延时的发布订阅平台.
-   [flowgraph](https://github.com/vectaport/flowgraph)MPI风格准备发送协调层.
-   [gleam](https://github.com/chrislusf/gleam)-用纯Go和Luajit编写的快速和可扩展的分布式map/reduce系统,结合Go的高并发性和Luajit的高性能,独立运行或分布式运行.
-   [glow](https://github.com/chrislusf/glow)-易于使用的可扩展的分布式大数据处理,MAP还原,DAG执行,全部在纯GO中.
-   [go-health](https://github.com/InVisionApp/go-health)-用于启用服务中异步依赖性健康检查的库.
-   [go-jump](https://github.com/dgryski/go-jump)-谷歌的"跳转"一致哈希函数端口.
-   [go-kit](https://github.com/go-kit/kit)-支持服务发现、负载平衡、可插拔传输、请求跟踪等的微服务工具包.
-   [gorpc](https://github.com/valyala/gorpc)-简单、快速、可扩展的高负载RPC库.
-   [grpc-go](https://github.com/grpc/grpc-go)GRPC的GO语言实现.基于HTTP/2的RPC.
-   [heimdall](https://github.com/gojektech/heimdall)-具有重试和HyScript功能的增强型HTTP客户端.
-   [hprose](https://github.com/hprose/hprose-golang)-非常新奇的RPC库,支持25种语言.
-   [jaeger](https://github.com/jaegertracing/jaeger)-分布式跟踪系统.
-   [jsonrpc](https://github.com/osamingo/jsonrpc)JSONRPC包有助于实现JSON-RPC 2.
-   [jsonrpc](https://github.com/ybbus/jsonrpc)JSON-RPC 2 HTTP客户端实现.
-   [KrakenD](https://github.com/devopsfaith/krakend)超性能API中间件框架.
-   [micro](https://github.com/micro/micro)可插拔微服务工具箱和分布式系统平台.
-   [NATS](https://github.com/nats-io/gnatsd)-轻量级、高性能的微服务、IoT和云本地系统的消息传递系统.
-   [raft](https://github.com/hashicorp/raft)- Golang实施RAFT共识议定书,由Hasigordp.
-   [raft](https://github.com/coreos/etcd/tree/master/raft)-通过CAREOS实施RAFT共识协议.
-   [redis-lock](https://github.com/bsm/redis-lock)-使用RIDIS简化分布式锁的实现.
-   [ringpop-go](https://github.com/uber/ringpop-go)GO应用程序的可扩展、容错应用层共享.
-   [rpcx](https://github.com/smallnest/rpcx)-分布式可插拔RPC服务框架,如阿里巴巴DubBo.
-   [sleuth](https://github.com/ursiform/sleuth)无主机P2P自动发现库和HTTP服务之间的RPC(使用)[ZeroMQ](https://github.com/zeromq/libzmq))
-   [tendermint](https://github.com/tendermint/tendermint)-高性能中间件,用于使用Tendermint协商一致和块链协议将用任何编程语言编写的状态机转换为Byzantine Fault.t复制状态机.
-   [torrent](https://github.com/anacrolix/torrent)BitTorrent客户端软件包.
    -   [dht](https://godoc.org/github.com/anacrolix/dht)BitTorrent KdimLi DHT实现.
    -   [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix)视频流激流客户端.

## 电子邮件

*实现电子邮件创建和发送的库和工具.*

-   [chasquid](https://blitiri.com.ar/p/chasquid)SMTP服务器写在GO中.
-   [douceur](https://github.com/aymerick/douceur)- CSS内联为您的HTML电子邮件.
-   [email](https://github.com/jordan-wright/email)-一个健壮灵活的GO电子邮件库.
-   [go-dkim](https://github.com/toorop/go-dkim)- DKIM图书馆,签署和验证电子邮件.
-   [go-imap](https://github.com/emersion/go-imap)-用于客户端和服务器的IMAP库.
-   [go-message](https://github.com/emersion/go-message)-用于因特网消息格式和邮件消息的流式库.
-   [Gomail](https://github.com/go-gomail/gomail/)- Gomail是一个非常简单和强大的发送电子邮件的软件包.
-   [Hectane](https://github.com/hectane/hectane)-轻量级SMTP客户端提供HTTP API.
-   [hermes](https://github.com/matcornic/hermes)- Golang包产生干净,响应性的HTML电子邮件.
-   [MailHog](https://github.com/mailhog/MailHog)用Web和API接口进行电子邮件和SMTP测试.
-   [SendGrid](https://github.com/sendgrid/sendgrid-go)sEdGrand的GO库用于发送电子邮件.
-   [smtp](https://github.com/mailhog/smtp)SMTP服务器协议状态机.

## 可嵌入脚本语言

*在GO代码中嵌入其他语言.*

-   [agora](https://github.com/PuerkitoBio/agora)-动态的,可嵌入的编程语言在GO中.
-   [anko](https://github.com/mattn/anko)-写在GO中的脚本解释器.
-   [binder](https://github.com/alexeyco/binder)-去Lua绑定库,基于[gopher-lua](https://github.com/yuin/gopher-lua).
-   [expr](https://github.com/antonmedv/expr)-一个可以评估表达式的引擎.
-   [gisp](https://github.com/jcla1/gisp)-简单的LISP中的GO.
-   [go-duktape](https://github.com/olebedev/go-duktape)DoK磁带JavaScript引擎绑定的GO.
-   [go-lua](https://github.com/Shopify/go-lua)- LUA 5.2 VM端口到纯GO.
-   [go-php](https://github.com/deuill/go-php)PHO绑定为GO.
-   [go-python](https://github.com/sbinet/go-python)-对Cython C-API进行天真的GO绑定.
-   [golua](https://github.com/aarzilli/golua)-为LUA C API进行绑定.
-   [gopher-lua](https://github.com/yuin/gopher-lua)- LUA 5.1 VM和编译器写在GO中.
-   [ngaro](https://github.com/db47h/ngaro)-可嵌入的nGARO-VM实现,使脚本能够在复古中运行.
-   [otto](https://github.com/robertkrimen/otto)JAVA脚本解释器,写在GO中.
-   [purl](https://github.com/ian-kent/purl)Perl 5.18.2嵌入到GO中.

## 文件

*用于处理文件和文件系统的库.*

-   [afero](https://github.com/spf13/afero)GO文件系统抽象系统.
-   [go-csv-tag](https://github.com/artonge/go-csv-tag)使用标签加载CSV文件.
-   [go-gtfs](https://github.com/artonge/go-gtfs)在GO中加载GTFS文件.
-   [notify](https://github.com/rjeczalik/notify)-文件系统事件通知库,具有简单的API,类似于操作系统/信号.
-   [pdfcpu](https://github.com/hhrutter/pdfcpu)- PDF处理器.
-   [skywalker](https://github.com/dixonwille/skywalker)-包允许一个同时轻松地通过文件系统.
-   [tarfs](https://github.com/posener/tarfs)-实现[`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem)焦油档案.

## 金融

*会计和财务套餐.*

-   [accounting](https://github.com/leekchan/accounting)-戈朗货币和货币格式化.
-   [decimal](https://github.com/shopspring/decimal)-任意精度的定点小数.
-   [go-finance](https://github.com/FlashBoys/go-finance)-综合金融市场数据.
-   [go-finance](https://github.com/alpeb/go-finance)-用于货币时间价值(年金)、现金流量、利率转换、债券和折旧计算的财务功能库.
-   [go-money](https://github.com/rhymond/go-money)- Fowler货币模式的实施.
-   [ofxgo](https://github.com/aclindsa/ofxgo)-查询OX服务器和/或解析响应(使用示例命令行客户端).
-   [techan](https://github.com/sdcoffey/techan)-技术分析库,具有先进的市场分析和交易策略.
-   [transaction](https://github.com/claygod/transaction)-以多线程模式运行的帐户的嵌入式事务数据库.
-   [vat](https://github.com/dannyvankooten/vat)增值税数量验证和欧盟增值税税率.

## 表单Form

*用于表单的库.*

-   [bind](https://github.com/robfig/bind)-将窗体数据绑定到任何GO值.
-   [binding](https://github.com/mholt/binding)-将窗体和JSON数据从NET/HTTP请求绑定到Stutt.
-   [conform](https://github.com/leebenson/conform)-保持用户输入检查.基于结构标签的装饰、消毒和擦洗数据.
-   [form](https://github.com/go-playground/form)-将URL值解码为GO值,并将GO值编码成URL值.双阵列和全地图支持.
-   [formam](https://github.com/monoculum/formam)-将窗体的值解码为结构.
-   [forms](https://github.com/albrow/forms)-框架不可知库,用于解析和验证表单/JSON数据,支持多部分表单和文件.
-   [gorilla/csrf](https://github.com/gorilla/csrf)-对GO Web应用程序和服务的CSRF保护.
-   [nosurf](https://github.com/justinas/nosurf)-GO的CSRF保护中间件.

## 游戏开发

*Awesome的游戏开发库.*

-   [Azul3D](https://github.com/azul3d/engine)- 3D游戏引擎写在GO上.
-   [Ebiten](https://github.com/hajimehoshi/ebiten)-死简单的2D游戏库中的GO.
-   [engo](https://github.com/EngoEngine/engo)- Engo是一个开源的2D游戏引擎,用GO编写.它遵循实体组件系统范例.
-   [g3n](https://github.com/g3n/engine)去3D游戏引擎.
-   [GarageEngine](https://github.com/vova616/GarageEngine)-2D游戏引擎编写,在OpenGL上运行.
-   [glop](https://github.com/runningwild/glop)- Glop(游戏库的权力)是一个相当简单的跨平台游戏库.
-   [go-astar](https://github.com/beefsack/go-astar)-A的实现\*路径搜索算法.
-   [go-collada](https://github.com/GlenKelley/go-collada)-使用Collada文件格式进行打包.
-   [go-sdl2](https://github.com/veandco/go-sdl2)-为[Simple DirectMedia Layer](https://www.libsdl.org/).
-   [go3d](https://github.com/ungerik/go3d)面向性能的2D/3D数学软件包.
-   [gonet](https://github.com/xtaci/gonet)- GORANG实现的游戏服务器骨架.
-   [goworld](https://github.com/xiaonanln/goworld)-可扩展的游戏服务器引擎,具有空间实体框架和热交换
-   [Leaf](https://github.com/name5566/leaf)-轻量级游戏服务器框架.
-   [nano](https://github.com/lonnng/nano)-轻量级、高性能、高性能的Galang-Basic游戏服务器框架
-   [Oak](https://github.com/oakmound/oak)-纯GO游戏引擎.
-   [Pitaya](https://github.com/topfreegames/pitaya)-通过C SDK为iOS、Android、Unity等提供集群支持和客户机库的可伸缩游戏服务器框架.
-   [Pixel](https://github.com/faiface/pixel)手工制作的2D游戏库.
-   [raylib-go](https://github.com/gen2brain/raylib-go)-去绑定[raylib](http://www.raylib.com/)一个简单而易于使用的图书馆来学习视频游戏编程.
-   [termloop](https://github.com/JoelOtter/termloop)基于终端的游戏引擎GO,构建在TimBox之上.

## 生成与泛型

*通过代码生成来增强具有泛型功能的语言的工具.*

-   [efaceconv](https://github.com/t0pep0/efaceconv)-代码生成工具,用于从接口{}到不分配的不可变类型的高性能转换.
-   [gen](https://github.com/clipperhouse/gen)-"泛型"类功能的代码生成工具.
-   [go-enum](https://github.com/abice/go-enum)代码注释中枚举的代码生成.
-   [go-linq](https://github.com/ahmetalpbalkan/go-linq).NET的LINQ类查询方法.
-   [goderive](https://github.com/awalterschulze/goderive)-从输入类型派生函数.
-   [interfaces](https://github.com/rjeczalik/interfaces)-用于生成接口定义的命令行工具.
-   [jennifer](https://github.com/dave/jennifer)-生成无模板的任意GO代码.
-   [pkgreflect](https://github.com/ungerik/pkgreflect)转到包范围反射的预处理器.

## 地理

*地理工具和服务器*

-   [geocache](https://github.com/melihmucuk/geocache)内存缓存,适用于基于地理位置的应用程序.
-   [geoserver](https://github.com/hishamkaram/geoserver)GeoServer是通过GeoServer REST API操纵GeoServer实例的GO包.
-   [osm](https://github.com/paulmach/osm)-用于阅读、书写和使用OpenStuteTMAP数据和API的库.
-   [pbf](https://github.com/maguro/pbf)- OpenStrutPMAP PBF戈兰编码器/解码器.
-   [S2 geometry](https://github.com/golang/geo)在GO中的S2几何库.
-   [Tile38](https://github.com/tidwall/tile38)地理索引数据库,具有空间索引和实时地理信息.

## Go编译器

*编译Go到其他语言(或相反)的工具.*

-   [c4go](https://github.com/Konstantin8105/c4go)-跨代码C代码去代码.
-   [f4go](https://github.com/Konstantin8105/f4go)- TracpFILE FORTRAN 77代码去代码.
-   [gopherjs](https://github.com/gopherjs/gopherjs)从JavaScript到编译器.
-   [llgo](https://github.com/go-llvm/llgo)基于LLVM的GO编译器.
-   [tardisgo](https://github.com/tardisgo/tardisgo)- Golang到Haxe到CPP/CSPAR/Java/JavaScript TrpPulter.

## go线程

*与Goroutines（go类型线程）一起工作和管理工具.*

-   [async](https://github.com/studiosol/async)-一种安全的方法来异步执行函数,在惊慌的情况下恢复它们.
-   [cyclicbarrier](https://github.com/marusama/cyclicbarrier)-戈朗的循环障碍.
-   [go-floc](https://github.com/workanator/go-floc)-精心安排好课程.
-   [go-flow](https://github.com/kamildrazkiewicz/go-flow)-控制GORDOTIN执行顺序.
-   [go-trylock](https://github.com/subchen/go-trylock)-对Golang的读写锁的TyLink支持.
-   [GoSlaves](https://github.com/themester/GoSlaves)-简单和异步GOODUTE池库.
-   [goworker](https://github.com/benmanns/goworker)GOWORKER是一个基于GO的后台工作者.
-   [grpool](https://github.com/ivpusic/grpool)- Lightweight Goroutine池.
-   [parallel-fn](https://github.com/rafaeljesus/parallel-fn)-并行运行函数.
-   [pool](https://github.com/go-playground/pool)-有限的消费者GOODUTIN或无限GOUDOTIN池更容易处理和取消GOOTUN.
-   [semaphore](https://github.com/kamilsk/semaphore)-基于通道和上下文的锁/解锁操作超时的信号量模式实现.
-   [semaphore](https://github.com/marusama/semaphore)-基于CAS(基于通道的信号量实现)的快速可重信号量实现.
-   [stl](https://github.com/ssgreg/stl)-基于软件事务内存(STM)并发控制机制的软件事务锁.
-   [threadpool](https://github.com/shettyh/threadpool)- Golang线程池实现.
-   [tunny](https://github.com/Jeffail/tunny)- Goroutine游泳池.
-   [worker-pool](https://github.com/vardius/worker-pool)GOWORKER是一个简单的异步工作池.
-   [workerpool](https://github.com/gammazero/workerpool)- Goroutine池,它限制了任务执行的并发性,而不是排队的任务数.

## GUI

*用于构建GUI应用程序的库.*

*工具程序*

-   [app](https://github.com/murlokswarm/app)-用GO、HTML和CSS创建应用程序包.支持:MACOS,正在进行中的窗口.
-   [fyne](https://github.com/fyne-io/fyne)跨平台本地GUI设计为GO,使用EFL呈现.支持:Linux,Mac OS,Windows.
-   [go-astilectron](https://github.com/asticode/go-astilectron)-用GO和HTML/JS/CSS(电子驱动)构建跨平台的GUI应用程序.
-   [go-gtk](http://mattn.github.io/go-gtk/)Go for GTK绑定.
-   [go-sciter](https://github.com/sciter-sdk/go-sciter)去绑定for sciter:HTML / CSS embeddable /脚本引擎for Modern桌面UI开发.跨平台.
-   [gotk3](https://github.com/gotk3/gotk3)Go for gtk3绑定.
-   [gowd](https://github.com/dtylman/gowd)-快速和简单的桌面界面开发以及走,HTML,CSS和nw.js.跨平台.
-   [qt](https://github.com/therecipe/qt)QT结合for走(support for Windows或MacOS / Linux /机器人/ IOS / sailfish OS /覆盆子π).
-   [ui](https://github.com/andlabs/ui)平台的GUI库为本地去.跨平台.
-   [walk](https://github.com/lxn/walk)Windows应用试剂盒去图书馆.
-   [webview](https://github.com/zserge/webview)跨平台Web视图窗口以及简单的双向JavaScript绑定(Windows / Linux和MacOS /).

*相互作用*

-   [gosx-notifier](https://github.com/deckarep/gosx-notifier)- OSX桌面通知library for走.
-   [robotgo](https://github.com/go-vgo/robotgo)跨平台的GUI去本地的自动化.控制鼠标,键盘和其他.
-   [systray](https://github.com/getlantern/systray)交叉平台去图书馆建立年图标和菜单to in the通知区域.
-   [trayhost](https://github.com/shurcooL/trayhost)跨平台去图书馆to地方年主机操作系统的图标在taskbar.

## Hardware

*库,工具和教程for相互作用以及Hardware.*

见[go-hardware](https://github.com/rakyll/go-hardware)综合列表.

## 图像

*用于操纵图像的库.*

-   [bild](https://github.com/anthonynsimon/bild)在纯GO中采集图像处理算法.
-   [bimg](https://github.com/h2non/bimg)-使用LIVIPS的快速和高效的图像处理小封装.
-   [cameron](https://github.com/aofei/cameron)-一个GAVA生成器.
-   [geopattern](https://github.com/pravj/geopattern)-从字符串创建美丽的生成图像模式.
-   [gg](https://github.com/fogleman/gg)在纯GO中进行2D渲染.
-   [gift](https://github.com/disintegration/gift)-封装图像处理滤波器.
-   [go-cairo](https://github.com/ungerik/go-cairo)-为开罗图形库进行绑定.
-   [go-gd](https://github.com/bolknote/go-gd)-为GD库进行绑定.
-   [go-nude](https://github.com/koyachi/go-nude)-用GO检测裸体.
-   [go-opencv](https://github.com/lazywei/go-opencv)-为OpenCV进行绑定.
-   [go-webcolors](https://github.com/jyotiska/go-webcolors)从Python去的WebCu饰子库端口.
-   [gocv](https://github.com/hybridgroup/gocv)-使用OpenCV 3.3 +计算机视觉软件包.
-   [goimagehash](https://github.com/corona10/goimagehash)-去感知图像哈希包.
-   [govatar](https://github.com/o1egl/govatar)库和CMD工具生成有趣的化身.
-   [imagick](https://github.com/gographics/imagick)-去绑定IMAGEMGIK的MigkWand C API.
-   [imaginary](https://github.com/h2non/imaginary)-快速和简单的HTTP微服务,用于图像调整.
-   [imaging](https://github.com/disintegration/imaging)-简易GO图像处理软件包.
-   [img](https://github.com/hawx/img)-选择图像处理工具.
-   [ln](https://github.com/fogleman/ln)三维线条艺术渲染.
-   [mergi](https://github.com/noelyahan/mergi)-用于图像处理的工具和GO库(合并、裁剪、调整大小、水印、动画).
-   [mort](https://github.com/aldor007/mort)-存储和图像处理服务器写在GO.
-   [mpo](https://github.com/donatj/mpo)MPO 3D照片的解码和转换工具.
-   [picfit](https://github.com/thoas/picfit)-用GO编写的图像调整大小服务器.
-   [pt](https://github.com/fogleman/pt)-路径跟踪引擎写在GO.
-   [resize](https://github.com/nfnt/resize)用普通插值法进行图像缩放.
-   [rez](https://github.com/bamiaux/rez)-在纯GO和SIMD中调整图像大小.
-   [smartcrop](https://github.com/muesli/smartcrop)-找到适合任意图像和作物大小的作物.
-   [steganography](https://github.com/auyer/steganography)用于LSB密写的纯GO库.
-   [svgo](https://github.com/ajstarks/svgo)为SVG生成语言库.
-   [tga](https://github.com/ftrvxmtrx/tga)-封装TGA是TARGA图像格式解码器/编码器.

## 物联网

*用于物联网编程设备的库.*

-   [connectordb](https://github.com/connectordb/connectordb)-开源平台,用于量化的自我和物联网.
-   [devices](https://github.com/goiot/devices)IOT设备库,X/EXP/IO实验.
-   [eywa](https://github.com/xcodersun/eywa)项目EYWA本质上是一个连接管理器,它跟踪连接的设备.
-   [flogo](https://github.com/tibcosoftware/flogo)Project FLUGO是IOT边缘应用和集成的开源框架.
-   [gatt](https://github.com/paypal/gatt)Gatt是一个用于构建蓝牙低能耗外围设备的GO封装.
-   [gobot](https://github.com/hybridgroup/gobot/)- Gobot是机器人学、物理计算和物联网的框架.
-   [iot](https://github.com/vaelen/iot/)IOT是一个实现谷歌IOT核心设备的简单框架.
-   [mainflux](https://github.com/Mainflux/mainflux)工业物联网消息和设备管理服务器.
-   [periph](https://periph.io/)-外围设备I/O与低层电路板设备接口.
-   [sensorbee](https://github.com/sensorbee/sensorbee)-物联网的轻量级流处理引擎.

## 日志

*用于生成和处理日志文件的库.*

-   [distillog](https://github.com/amoghe/distillog)蒸馏后的水平测井(将其视为STDLIb+log水平).
-   [glg](https://github.com/kpango/glg)GLG是一种简单快速的GO测井记录库.
-   [glog](https://github.com/golang/glog)-执行GO的执行日志.
-   [go-cronowriter](https://github.com/utahta/go-cronowriter)-简单的作者,根据当前日期和时间自动旋转日志文件,如CLONLOG.
-   [go-log](https://github.com/subchen/go-log)-简单、可配置的GO日志记录,包括级别、格式化程序和写入器.
-   [go-log](https://github.com/siddontang/go-log)-日志LIB支持级别和多处理器.
-   [go-log](https://github.com/ian-kent/go-log)在GO中实现Log4J.
-   [go-logger](https://github.com/apsdehal/go-logger)- GO程序的简单记录器,带有级别处理程序.
-   [gologger](https://github.com/sadlil/gologger)-简单易用的日志库为GO,日志在彩色控制台,简单控制台,文件或弹性搜索.
-   [gomol](https://github.com/aphistic/gomol)多输出、结构化日志,用于扩展日志记录输出.
-   [gone/log](https://github.com/One-com/gone/tree/master/log)-快速、可扩展、全功能、STD LIB源兼容的日志库.
-   [journald](https://github.com/ssgreg/journald)-执行Stasd日志的本地API用于日志记录.
-   [log](https://github.com/apex/log)GO结构化日志包.
-   [log](https://github.com/go-playground/log)-简单、可配置和可扩展的结构化GO日志记录.
-   [log](https://github.com/teris-io/log)GO结构日志接口将日志立面从其实现中分离出来.
-   [log-voyage](https://github.com/firstrow/logvoyage)-在Galang写的全功能日志SaaS.
-   [log15](https://github.com/inconshreveable/log15)-简单,强大的日志记录.
-   [logdump](https://github.com/ewwwwwqm/logdump)-用于多级测井的封装.
-   [logex](https://github.com/chzyer/logex)- Golang日志LIB,支持跟踪和级别,由标准日志LIB打包.
-   [logger](https://github.com/azer/logger)-最小化的GO日志库.
-   [logo](https://github.com/mbndr/logo)- Golang登录到不同的可配置的作家.
-   [logrus](https://github.com/Sirupsen/logrus)GO结构日志记录器.
-   [logrusly](https://github.com/sebest/logrusly) - [logrus](https://github.com/sirupsen/logrus)插件将错误发送到[Loggly](https://www.loggly.com/).
-   [logutils](https://github.com/hashicorp/logutils)-用于稍微更好地登录GO(Golang)的实用工具,扩展标准记录器.
-   [logxi](https://github.com/mgutz/logxi)12因素APP记录器,速度快,让你快乐.
-   [lumberjack](https://github.com/natefinch/lumberjack)-简单滚动记录器,实现IO.WrreCuleSER.
-   [mlog](https://github.com/jbrodriguez/mlog)GO的简单日志模块,具有5个级别,可选的旋转日志文件特征和STDUD/STDER输出.
-   [onelog](https://github.com/francoispqt/onelog)ONEOLG是一个简单但非常有效的JSON记录器.它是所有场景中最快的JSON记录器.而且,它是具有最低分配的记录器之一.
-   [ozzo-log](https://github.com/go-ozzo/ozzo-log)-支持日志严重性、分类和过滤的高性能日志记录.可以将过滤后的日志消息发送到各种目标(例如控制台、网络、邮件).
-   [seelog](https://github.com/cihub/seelog)-具有灵活调度、过滤和格式化的日志记录功能.
-   [spew](https://github.com/davecgh/go-spew)-为GO数据结构实现一个深漂亮的打印机,以帮助调试.
-   [stdlog](https://github.com/alexcesaro/log)- Stdlog是一个面向对象的库,提供分层日志.这对于Con Job非常有用.
-   [tail](https://github.com/hpcloud/tail)-GO程序包努力模仿BSD尾部程序的特性.
-   [xlog](https://github.com/xfxdev/xlog)-插件架构和灵活的日志系统的GO,与水平CTRL,多日志目标和自定义日志格式.
-   [xlog](https://github.com/rs/xlog)结构记录器`net/context`具有灵活调度的感知HTTP处理程序.
-   [zap](https://github.com/uber-go/zap)-快速、结构化、水平化日志记录.
-   [zerolog](https://github.com/rs/zerolog)-零分配JSON记录器.

## 机器学习

*用于机器学习的库.*

-   [bayesian](https://github.com/jbrukh/bayesian)-朴素贝叶斯分类的Golang.
-   [CloudForest](https://github.com/ryanbressler/CloudForest)在纯GO中机器学习的决策树快速、灵活、多线程集成.
-   [eaopt](https://github.com/MaxHalford/eaopt)-进化优化库.
-   [fonet](https://github.com/Fontinalis/fonet)-用GO编写的深度神经网络库.
-   [go-cluster](https://github.com/e-XpertSolutions/go-cluster)-实现K模式和K原型聚类算法.
-   [go-deep](https://github.com/patrikeh/go-deep)-一个功能丰富的神经网络库在GO中.
-   [go-fann](https://github.com/white-pony/go-fann)-快速人工神经网络(FANN)库的绑定.
-   [go-galib](https://github.com/thoj/go-galib)遗传算法库在GO/GORANG中编写.
-   [go-pr](https://github.com/daviddengcn/go-pr)模式识别软件包.
-   [gobrain](https://github.com/goml/gobrain)-写在GO中的神经网络.
-   [godist](https://github.com/e-dard/godist)-各种概率分布,以及相关的方法.
-   [goga](https://github.com/tomcraven/goga)遗传算法的GO库.
-   [GoLearn](https://github.com/sjwhitworth/golearn)- GO通用机器学习库.
-   [golinear](https://github.com/danieldk/golinear)-GO的线性绑定.
-   [GoMind](https://github.com/surenderthakran/gomind)一个简单的神经网络库.
-   [goml](https://github.com/cdipaolo/goml)-在线机器学习中的GO.
-   [goRecommend](https://github.com/timkaye11/goRecommend)-用GO编写的推荐算法库.
-   [gorgonia](https://github.com/chewxy/gorgonia)-基于图的计算库,如Theano for Go,它为构建各种机器学习和神经网络算法提供原语.
-   [goscore](https://github.com/asafschers/goscore)-为PMML打分API.
-   [gosseract](https://github.com/otiai10/gosseract)-使用TeSerSc++库对OCR(光学字符识别)进行打包.
-   [libsvm](https://github.com/datastream/libsvm)LIbSVM - Gangon版本基于LIbSVM 3.14的工作.
-   [mlgo](https://github.com/NullHypothesis/mlgo)这个项目的目的是提供最小的机器学习算法在GO.
-   [neat](https://github.com/jinyeom/neat)即插即用的并行GO框架,用于增强拓扑结构(Lead)的神经进化.
-   [neural-go](https://github.com/schuyler/neural-go)在GO中实现的多层感知器网络,通过反向传播进行训练.
-   [probab](https://github.com/ThePaw/probab)-概率分布函数.贝叶斯推理.写在纯GO.
-   [regommend](https://github.com/muesli/regommend)推荐与协同过滤引擎.
-   [shield](https://github.com/eaigner/shield)-贝叶斯文本分类器具有灵活的令牌和存储后备的GO.
-   [tfgo](https://github.com/galeone/tfgo)-易于使用的张紧流绑定:简化了官方TysFraseGo绑定的使用.定义在Python中训练的GO、加载和执行模型中的计算图.
-   [Varis](https://github.com/Xamber/Varis)Gangon神经网络.

## 消息传递

*实现消息传递系统的库.*

-   [APNs2](https://github.com/sideshow/apns2)- HTTP / 2苹果推送通知提供程序,用于向IOS、TVOS、Safari和OSX应用发送推送通知.
-   [Benthos](https://github.com/Jeffail/benthos)-在一系列协议之间的消息流桥.
-   [Centrifugo](https://github.com/centrifugal/centrifugo)-实时消息(WebSoCoSts或SoCKJS)服务器.
-   [dbus](https://github.com/godbus/dbus)- D-总线的本地绑定绑定.
-   [drone-line](https://github.com/appleboy/drone-line)发送[Line](https://at.line.me/en)使用二进制、码头工人或无人机CI通知.
-   [emitter](https://github.com/olebedev/emitter)-使用GO方式发出事件,使用通配符、谓词、取消可能性和许多其他好的胜利.
-   [event](https://github.com/agoalofalife/event)-模式观测器的实现.
-   [EventBus](https://github.com/asaskevich/EventBus)-具有异步兼容性的轻量级事件总线.
-   [gaurun-client](https://github.com/osamingo/gaurun-client)- Gaurun客户写在GO.
-   [Glue](https://github.com/desertbit/glue)-健壮的GO和JavaScript套接字库(替代Socket.IO).
-   [go-notify](https://github.com/TheCreeper/go-notify)- Frut桌面通知规范的本地实现.
-   [go-nsq](https://github.com/nsqio/go-nsq)-官方的NSQ软件包.
-   [go-socket.io](https://github.com/googollee/go-socket.io)为GalangSoCo.IO库提供实时应用框架.
-   [go-vitotrol](https://github.com/maxatome/go-vitotrol)-客户端库到Viessmann Vitotrol Web服务.
-   [Gollum](https://github.com/trivago/gollum)-一个N:M多路复用器,收集来自不同来源的消息,并将它们广播到一组目的地.
-   [golongpoll](https://github.com/jcuga/golongpoll)- HTTP LoopRever服务器库,使Web PUB子简单.
-   [goose](https://github.com/ian-kent/goose)-服务器在GO中发送事件.
-   [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster)GopHu集群是一个GooPress服务器集群.
-   [gorush](https://github.com/appleboy/gorush)-使用推送通知服务器[APNs2](https://github.com/sideshow/apns2)谷歌[GCM](https://github.com/google/go-gcm).
-   [guble](https://github.com/smancke/guble)-使用推送通知(Google Firebase云消息、Apple Push Notification服务、SMS)以及websockets的消息服务器,这是一个REST API,具有分布式操作和消息持久性.
-   [hub](https://github.com/leandro-lugaresi/hub)- GO应用程序的消息/事件集线器,使用发布/订阅模式,支持像RabByMQ交换机这样的别名.
-   [machinery](https://github.com/RichardKnop/machinery)-基于分布式消息传递的异步任务队列/作业队列.
-   [mangos](https://github.com/go-mangos/mangos)-通过传输互操作性实现Nanomsg("可扩展协议")的纯GO.
-   [melody](https://github.com/olahol/melody)-用于处理WebStutsS会话的极简主义框架,包括广播和自动ping /乒乓处理.
-   [Mercure](https://github.com/dunglas/mercure)-服务器和库调度服务器使用MeCurror协议发送的更新(建立在服务器发送事件的顶部).
-   [messagebus](https://github.com/vardius/message-bus)MaseAdvBUS是一个简单的异步消息总线,非常适合在事件采购、CQRS、DDD中使用事件总线.
-   [NATS Go Client](https://github.com/nats-io/nats)-轻量级和高性能发布订阅和分布式排队消息系统-这是GO库.
-   [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus)-一个围绕NSQ主题和通道的小包装.
-   [oplog](https://github.com/dailymotion/oplog)- REST API的通用OPROG/复制系统.
-   [pubsub](https://github.com/tuxychandru/pubsub)-简单的PUBSUB软件包.
-   [rabbus](https://github.com/rafaeljesus/rabbus)-在AMQP交换和队列上的一个小包装.
-   [rabtap](https://github.com/jandelgado/rabtap)RabbMQ瑞士军刀CLI应用程序.
-   [RapidMQ](https://github.com/sybrexsys/RapidMQ)- RapidMQ是管理本地消息队列的轻量级可靠的库.
-   [sarama](https://github.com/Shopify/sarama)-为Apache卡夫卡去图书馆.
-   [Uniqush-Push](https://github.com/uniqush/uniqush-push)-ReIDIS支持服务器端通知向移动设备的统一推送服务.
-   [zmq4](https://github.com/pebbe/zmq4)转到DeloMQ版本4.也可用于[version 3](https://github.com/pebbe/zmq3)和[version 2](https://github.com/pebbe/zmq2).

## 其他

*这些图书馆被放置在这里,因为其他类别似乎都不适合.*

-   [alice](https://github.com/magic003/alice)- Golang的添加剂依赖注入容器.
-   [anagent](https://github.com/mudler/anagent)-具有依赖注入的最小化、可插入的Golang evloop /定时器处理程序.
-   [antch](https://github.com/antchfx/antch)-一种快速、强大和可扩展的Web爬行和刮削框架.
-   [archiver](https://github.com/mholt/archiver)库和命令,用于制作和提取.zip和t.gz档案.
-   [autoflags](https://github.com/artyom/autoflags)-从软件结构域中自动定义命令行标志.
-   [avgRating](https://github.com/kirillDanshin/avgRating)根据Wilson积分方程计算平均得分和评分.
-   [banner](https://github.com/dimiro1/banner)在你的GO应用程序中添加漂亮的横幅.
-   [base64Captcha](https://github.com/mojocn/base64Captcha)BASIC 64 CAPTCH支持数字,数字,字母,算术,音频和数字字母CATCTHA.
-   [battery](https://github.com/distatus/battery)跨平台、标准化的电池信息库.
-   [bitio](https://github.com/icza/bitio)-高度优化的位级读写器为GO.
-   [browscap_go](https://github.com/digitalcrab/browscap_go)戈朗图书馆[Browser Capabilities Project](http://browscap.org/).
-   [captcha](https://github.com/steambap/captcha)-封装CAPTCHA提供了一个易于使用的、不固执己见的API用于CAPTCHA生成.
-   [conv](https://github.com/cstockton/go-conv)包CONV提供跨GO类型的快速和直观转换.
-   [datacounter](https://github.com/miolini/datacounter)-为读者/写入器/HTTP.RealScript编写计数器.
-   [errors](https://github.com/pkg/errors)-提供简单的错误处理原语的包.
-   [ffmt](https://github.com/go-ffmt/ffmt)-美化人类的数据显示.
-   [ghorg](https://github.com/gabrie30/ghorg)将GITHUB ORG中的所有副本复制到单个目录中.
-   [go-chat-bot](https://github.com/go-chat-bot/bot)- IRC,松弛和电报BOT写在GO.
-   [go-commons-pool](https://github.com/jolestar/go-commons-pool)Golang的通用对象池.
-   [go-multierror](https://github.com/hashicorp/go-multierror)-GO(GALON)包,用于将错误列表表示为单个错误.
-   [go-openapi](https://github.com/go-openapi)-收集包以解析和利用开放API模式.
-   [go-resiliency](https://github.com/eapache/go-resiliency)戈兰的弹性模式.
-   [go-sarah](https://github.com/oklahomer/go-sarah)-框架构建BOT所需的聊天服务,包括线,松,GITER等.
-   [go-unarr](https://github.com/gen2brain/go-unarr)-用于RAR、TAR、ZIP和7Z存档的解压缩库.
-   [go.uuid](https://github.com/satori/go.uuid)-实现通用唯一标识符(UUID).支持UUID的创建和解析.
-   [gofakeit](https://github.com/brianvoe/gofakeit)随机数据生成器,写在GO中.
-   [goid](https://github.com/jakehl/goid)-生成并解析符合RCF4122的V4 UUID.
-   [gommit](https://github.com/antham/gommit)-分析Git提交消息以确保它们遵循定义的模式
-   [gopsutil](https://github.com/shirou/gopsutil)-跨平台库,用于检索进程和系统利用率(CPU、内存、磁盘等).
-   [gosh](https://github.com/osamingo/gosh)-提供GO统计处理程序、结构、度量方法.
-   [gosms](https://github.com/haxpax/gosms)-你自己的本地短信网关,可以用来发送短信.
-   [gountries](https://github.com/pariz/gountries)-封装国家和细分数据的包.
-   [hanu](https://github.com/sbstjn/hanu)编写松散机器人的框架.
-   [health](https://github.com/dimiro1/health)-易于使用,可扩展的健康检查库.
-   [healthcheck](https://github.com/etherlabsio/healthcheck)-用于REST服务的自定和并发的健康检查HTTP处理程序.
-   [hostutils](https://github.com/Wing924/hostutils)-一个用于包装和解开FQDNS列表的戈兰图书馆.
-   [indigo](https://github.com/osamingo/indigo)-使用SybFLink并由Base58编码的分布式唯一ID生成器.
-   [jobs](https://github.com/albrow/jobs)-持久灵活的后台作业库.
-   [lk](https://github.com/hyperboloide/lk)-戈兰的简单许可证库.
-   [margelet](https://github.com/zhulik/margelet)-建造电报机器人的框架.
-   [morse](https://github.com/alwindoss/morse)-库转换为莫尔斯电码.
-   [pdfgen](https://github.com/hyperboloide/pdfgen)HTTP服务从JSON请求生成PDF.
-   [persian](https://github.com/mavihq/persian)-一些用于波斯语的实用工具.
-   [sandid](https://github.com/aofei/sandid)地球上每一粒沙子都有它自己的ID.
-   [secdl](https://github.com/xor-gate/secdl)-下载到安全下载URL的MODECSEP下载算法.
-   [shellwords](https://github.com/Wing924/shellwords)-一个Gangon库,根据UNIX Burne shell的解析规则来操作字符串.
-   [shortid](https://github.com/teris-io/shortid)-分布式超短、独特、非顺序、URL友好的ID生成.
-   [slacker](https://github.com/shomali11/slacker)-易于使用的框架来创建松弛机器人.
-   [stats](https://github.com/go-playground/stats)-监视器去MeSTATS+系统统计,如内存,交换和CPU,并通过UDP发送任何你想要的日志记录等.
-   [strutil](https://github.com/ozgio/strutil)-字符串实用程序
-   [turtle](https://github.com/hackebrot/turtle)-表情表情.
-   [url-shortener](https://github.com/pantrif/url-shortener)-具有MySQL支持的现代、强大和健壮的URL缩短器微服务.
-   [uuid](https://github.com/agext/uuid)-用快速或加密质量的随机节点标识符生成、编码和解码UUIDV1.
-   [uuid](https://github.com/gofrs/uuid)-实现通用唯一标识符(UUID).支持UUID的创建和解析.积极维护的StoRi UUID叉.
-   [VarHandler](https://github.com/azr/generators/tree/master/varhandler)-生成样板HTTP输入和输出处理.
-   [werr](https://github.com/txgruppi/werr)-错误包装器为GO中的错误类型创建包装,它捕获文件的名称、行和堆栈.
-   [wuid](https://github.com/edwingeng/wuid)一个非常快的唯一数字发生器,比UUID快10-135倍.
-   [xkg](https://github.com/go-xkg/xkg)-X键盘抓取器.
-   [xstrings](https://github.com/huandu/xstrings)-从其他语言移植的有用字符串函数的集合.

## 自然语言处理

*图书馆与人类语言一起工作.*

-   [getlang](https://github.com/rylans/getlang)-快速自然语言检测软件包.
-   [go-eco](https://github.com/ThePaw/go-eco)-相似性、差异性和距离矩阵;多样性、公平性和不平等度量;物种丰富度估计器;单斜模型.
-   [go-i18n](https://github.com/nicksnyder/go-i18n/)-包和附带的工具来处理本地化文本.
-   [go-mystem](https://github.com/dveselov/mystem)- CGo绑定到YANDEX.MySTEM -俄罗斯形态分析仪.
-   [go-nlp](https://github.com/nuance/go-nlp)-使用离散概率分布和其他工具做NLP工作有用的工具.
-   [go-pinyin](https://github.com/mozillazg/go-pinyin)汉字汉化到汉语拼音转换器.
-   [go-stem](https://github.com/agonopol/go-stem)-执行波特堵塞算法.
-   [go-unidecode](https://github.com/mozillazg/go-unidecode)Unicode文本的ASCII音译.
-   [go2vec](https://github.com/danieldk/go2vec)-用于Word2VEC嵌入的读取器和实用功能.
-   [gojieba](https://github.com/yanyiwu/gojieba)这是一个GO实现[jieba](https://github.com/fxsjy/jieba)其中一个中文分词算法.
-   [golibstemmer](https://github.com/rjohnsondev/golibstemmer)-为雪球LIbSTEMMER库,包括波特2进行绑定.
-   [gounidecode](https://github.com/fiam/gounidecode)-Unicode音译器(也称为UNIDCODE)为GO.
-   [gse](https://github.com/go-ego/gse)-有效的文本分割;支持英语、汉语、日语等.
-   [icu](https://github.com/goodsign/icu)-CGO绑定用于ICU4C C库的检测和转换功能.保证与版本50.1兼容.
-   [kagome](https://github.com/ikawaha/kagome)JP形态分析器用纯GO编写.
-   [libtextcat](https://github.com/goodsign/libtextcat)-CbGo绑定用于LIbTeXTCAT C库.保证与版本2.2兼容.
-   [MMSEGO](https://github.com/awsong/MMSEGO)这是一个GO实现[MMSEG](http://technology.chtsai.org/mmseg/)其中一个中文分词算法.
-   [nlp](https://github.com/Shixzie/nlp)从字符串中提取值,并用NLP填充结构.
-   [nlp](https://github.com/james-bowman/nlp)-支持LSA(潜在语义分析)的自然语言处理库.
-   [paicehusk](https://github.com/rookii/paicehusk)- Golang PARES/HASK堵塞算法的实现.
-   [petrovich](https://github.com/striker2000/petrovich)-彼得罗维奇是一个使俄语名字被赋予语法案例的图书馆.
-   [porter](https://github.com/a2800276/porter)这是Martin Porter的C实现波特括号算法的一个相当简单的端口.
-   [porter2](https://github.com/zhenjl/porter2)-真的快搬运工2茎.
-   [prose](https://github.com/jdkato/prose)用于支持标记化、词性标注、命名实体提取等的文本处理库.
-   [RAKE.go](https://github.com/Obaied/RAKE.go)-去港的快速自动关键词提取算法(RAKE).
-   [segment](https://github.com/blevesearch/segment)-用于执行Unicode文本分割的GO库,如[Unicode Standard Annex #29](http://www.unicode.org/reports/tr29/)
-   [sentences](https://github.com/neurosnap/sentences)句子符号化器:将文本转换成句子列表.
-   [shamoji](https://github.com/osamingo/shamoji)- Sooji是用GO编写的文字过滤软件包.
-   [snowball](https://github.com/goodsign/snowball)雪球STMMER端口(CGO包装)的GO.提供词干提取功能[Snowball native](http://snowball.tartarus.org/).
-   [stemmer](https://github.com/dchest/stemmer)用于GO程序设计语言的STEMER软件包.包括英语和德语词干.
-   [textcat](https://github.com/pebbe/textcat)-以N-gram为基础的文本分类,支持UTF-8和原始文本.
-   [whatlanggo](https://github.com/abadojack/whatlanggo)-用于GO的自然语言检测软件包.支持84种语言和24种脚本(书写系统如拉丁语、西里尔语等).
-   [when](https://github.com/olebedev/when)-具有可插入规则的自然EN和RU语言日期/时间解析器.

## 网络

*用于与网络的各个层一起工作的库.*

-   [arp](https://github.com/mdlayher/arp)包ARP实现了ARP协议,如RFC 826中所描述的.
-   [buffstreams](https://github.com/stabbycutyou/buffstreams)通过TCP实现流协议缓冲区数据变得容易.
-   [canopus](https://github.com/zubairhamed/canopus)- COAP客户端/服务器实现(RFC 7252).
-   [cidranger](https://github.com/yl2chen/cidranger)-快速的IP到CIDR查找的GO.
-   [dhcp6](https://github.com/mdlayher/dhcp6)-包DHCP6实现了一个DHCPv6服务器,如RFC 3315中所描述的.
-   [dns](https://github.com/miekg/dns)-去图书馆与DNS一起工作.
-   [ether](https://github.com/songgao/ether)跨平台GO包,用于发送和接收以太网帧.
-   [ethernet](https://github.com/mdlayher/ethernet)-封装以太网实现IEEE 802.3以太网II帧和IEEE 802.1Q VLAN标签的封送和解除封送.
-   [fasthttp](https://github.com/valyala/fasthttp)包FasthTTP是GO的一种快速HTTP实现,比NET/HTTP快10倍.
-   [fortio](https://github.com/fortio/fortio)加载测试库和命令行工具,高级回声服务器和Web UI.允许指定每秒加载的设置查询和记录等待时间直方图和其他有用的统计信息并绘制它们.TCP、HTTP、GRPC.
-   [ftp](https://github.com/jlaffaye/ftp)-包FTP实现FTP客户端,如[RFC 959](http://tools.ietf.org/html/rfc959).
-   [gNxI](https://github.com/google/gnxi)-使用GNMI和GNOI协议的网络管理工具集合.
-   [go-getter](https://github.com/hashicorp/go-getter)-Go库,用于使用URL下载来自不同来源的文件或目录.
-   [go-stun](https://github.com/ccding/go-stun)-执行STUN客户端(RFC 3489和RFC 5389).
-   [gobgp](https://github.com/osrg/gobgp)BGP在GO编程语言中实现.
-   [golibwireshark](https://github.com/sunwxg/golibwireshark)包GLIBIWRESARK使用LabWiReSurk库解码PCAP文件并分析剖析数据.
-   [gopacket](https://github.com/google/gopacket)-用LIPBCAP绑定进行数据包处理.
-   [gopcap](https://github.com/akrennmair/gopcap)-用于LIPPCAP的包装器.
-   [goshark](https://github.com/sunwxg/goshark)包GOSHARK使用TSARK解码IP包并创建数据结构来分析数据包.
-   [gosnmp](https://github.com/soniah/gosnmp)-用于执行SNMP操作的本地GO库.
-   [gotcp](https://github.com/gansidui/gotcp)GO程序包用于快速编写TCP应用程序.
-   [grab](https://github.com/cavaliercoder/grab)-去管理文件下载包.
-   [graval](https://github.com/koofr/graval)-实验FTP服务器框架.
-   [HTTPLab](https://github.com/gchaincl/httplab)HTTPLABS允许您检查HTTP请求并伪造响应.
-   [jazigo](https://github.com/udhos/jazigo)- JAGIGO是为多个网络设备检索配置而编写的工具.
-   [kcp-go](https://github.com/xtaci/kcp-go)- KCP -快速可靠的ARQ协议.
-   [kcptun](https://github.com/xtaci/kcptun)-基于KCP协议的极其简单和快速的UDP隧道.
-   [lhttp](https://github.com/fanux/lhttp)-强大的WebSoT框架,更容易构建IM服务器.
-   [linkio](https://github.com/ian-kent/linkio)-读写器接口的网络链路速度模拟.
-   [llb](https://github.com/kirillDanshin/llb)这是一个非常简单但很快的代理服务器后端.可用于快速重定向到预定义的域,具有零内存分配和快速响应.
-   [mdns](https://github.com/hashicorp/mdns)- Golang中简单的MNS(多播DNS)客户机/服务器库.
-   [mqttPaho](https://eclipse.org/paho/clients/golang/)- PAHO GO客户端提供了一个MQTT客户端库,用于通过TCP、TLS或WebSoCube连接到MQTT经纪人.
-   [NFF-Go](https://github.com/intel-go/nff-go)-云和裸金属的性能网络功能的快速开发框架(前YANFF).
-   [packet](https://github.com/aerogo/packet)通过TCP和UDP发送数据包.它可以缓冲消息和热交换连接,如果需要的话.
-   [peerdiscovery](https://github.com/schollz/peerdiscovery)使用UDP组播的跨平台本地对等发现纯GO库
-   [portproxy](https://github.com/aybabtme/portproxy)-简单的TCP代理,它为不支持它的API添加了CORS支持.
-   [publicip](https://github.com/polera/publicip)-包PrimeIP返回您面向公众的IPv4地址(Internet EXCEL).
-   [quic-go](https://github.com/lucas-clemente/quic-go)-在纯GO中实现QIC协议.
-   [raw](https://github.com/mdlayher/raw)-包RAW允许在网络接口的设备驱动程序级别上读取和写入数据.
-   [sftp](https://github.com/pkg/sftp)-包SFTP实现了SSH文件传输协议,如<https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt>.
-   [ssh](https://github.com/gliderlabs/ssh)-用于构建SSH服务器的高级API(包装密码/ SSH).
-   [sslb](https://github.com/eduardonunesp/sslb)这是一个超级简单的负载均衡器,只是一个小项目来实现某种性能.
-   [stun](https://github.com/go-rtc/stun)-执行RFC 5389 STUN协议.
-   [tcp_server](https://github.com/firstrow/tcp_server)GO库用于更快地构建TCP服务器.
-   [utp](https://github.com/anacrolix/utp)-去UTP微传输协议的实现.
-   [water](https://github.com/songgao/water)-简单的Tun/TAP库.
-   [winrm](https://github.com/masterzen/winrm)去WINRM客户端远程执行Windows机器上的命令.
-   [xtcp](https://github.com/xfxdev/xtcp)- TCP服务器框架同时具有全双工通信、优雅关机、自定义协议.

## OpenGL

*在GO中使用OpenGL的库.*

-   [gl](https://github.com/go-gl/gl)-通过OpenGL(通过辉光生成)进行绑定.
-   [glfw](https://github.com/go-gl/glfw)-为GLFW 3绑定.
-   [goxjs/gl](https://github.com/goxjs/gl)-跨平台OpenGL绑定(OS X、Linux、Windows、浏览器、IOS、Android).
-   [goxjs/glfw](https://github.com/goxjs/glfw)-跨平台的GLFW库,用于创建OpenGL上下文和接收事件.
-   [mathgl](https://github.com/go-gl/mathgl)-纯GO数学包专门为3D数学,从GLM的启示.

## ORM

*实现对象关系映射或数据映射技术的库.*

-   [beego orm](https://github.com/astaxie/beego/tree/master/orm)-强大的ORM框架的GO.支持:PQ/MySQL/SqLITE3.
-   [go-pg](https://github.com/go-pg/pg)- PostgreSQL ORM,重点关注PostgreSQL特定的特性和性能.
-   [go-queryset](https://github.com/jirfag/go-queryset)100%型安全ORM代码生成和MySQL、PostgreSQL、SQLITE3、基于GORM的SQL Server支持.
-   [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder)-灵活和强大的SQL字符串生成器库加上零配置ORM.
-   [go-store](https://github.com/gosuri/go-store)-简单且快速的Read支持的GO键值存储库.
-   [gomodel](https://github.com/cosiner/gomodel)-轻量级、快速、类似ORM的库有助于与数据库交互.
-   [GORM](https://github.com/jinzhu/gorm)- Golang的神奇ORM库,旨在成为开发者友好的.
-   [gorp](https://github.com/go-gorp/gorp)-去关系持久性,ORM图书馆去GO.
-   [grimoire](https://github.com/Fs02/grimoire)GRIMOIR是GRANG的数据库访问层和验证.(支持:MySQL、PostgreSQL和SqLeTe3).
-   [lore](https://github.com/abrahambotros/lore)- GO的简单轻量级伪ORM/伪结构映射环境.
-   [Marlow](https://github.com/dadleyy/marlow)从项目结构生成ORM,用于编译时安全保证.
-   [pop/soda](https://github.com/gobuffalo/pop)-数据库迁移、创建、ORM等.对于MySQL、PostgreSQL和SQLite.
-   [QBS](https://github.com/coocood/qbs)-用结构表示查询.一个ORM.
-   [reform](https://github.com/go-reform/reform)-更好的ORM,基于非空接口和代码生成.
-   [SQLBoiler](https://github.com/volatiletech/sqlboiler)ORM发生器.生成适合于数据库模式的特征和快速的ORM.
-   [upper.io/db](https://github.com/upper/db)-通过使用成熟的数据库驱动程序的适配器来与不同的数据源交互的单一接口.
-   [Xorm](https://github.com/go-xorm/xorm)-简单有力的ORM.
-   [Zoom](https://github.com/albrow/zoom)-在ReDIS上创建快速数据存储和查询引擎.

## 包管理

*包管理的正式工具*

-   [dep](https://github.com/golang/dep)转到依赖工具.
-   [vgo](https://go.googlesource.com/vgo/)-版本的GO.

*用于包装和依赖管理的非官方图书馆.*

-   [gigo](https://github.com/LyricalSecurity/gigo)类似于GORANG的PIP类依赖工具,支持私有存储库和散列.
-   [glide](https://github.com/Masterminds/glide)管理你的Galang-Prand和包包容易.灵感来自Maven、Bundler和PIP等工具.
-   [godep](https://github.com/tools/godep)GO的依赖工具通过固定它们的依赖性来帮助构建可复制的包.
-   [gom](https://github.com/mattn/gom)-去经理-捆去.
-   [goop](https://github.com/nitrous-io/goop)-简单的依赖管理器为GO(GORANG),灵感来自捆绑.
-   [gop](https://github.com/lunny/gop)-构建和管理GOPATH中的GO应用程序
-   [gopm](https://github.com/gpmgo/gopm)-打包管理器.
-   [govendor](https://github.com/kardianos/govendor)-打包管理器.转到与标准供应商文件一起工作的供应商工具.
-   [gpm](https://github.com/pote/gpm)- BAR依赖性管理器.
-   [gvt](https://github.com/FiloSottile/gvt) - `gvt`是一个简单的售货工具,为GO本地Destern(又名GO15VANDORACE实验),基于GB供应商.
-   [johnny-deps](https://github.com/VividCortex/johnny-deps)-使用Git的最小依赖版本.
-   [nut](https://github.com/jingweno/nut)-供应商去依赖.
-   [VenGO](https://github.com/DamnWidget/VenGO)-创建和管理可导出的隔离虚拟环境.

## 查询语言

-   [gojsonq](https://github.com/thedevsaddam/gojsonq)-一个简单的GO包,用于查询JSON数据.
-   [graphql](https://github.com/tmc/graphql)-图形化语法分析器+实用工具.
-   [graphql](https://github.com/sevki/graphql)GOGQL在GO中的实现.
-   [graphql](https://github.com/neelance/graphql-go)- GraphQL服务器的重点是易于使用.
-   [graphql-go](https://github.com/graphql-go/graphql)-实现GOGQL的GO.
-   [jsonql](https://github.com/elgs/jsonql)Golang中的JSON查询表达式库.
-   [jsonslice](https://github.com/bhmj/jsonslice)-用高级过滤器查询Jsonpath.
-   [rql](https://github.com/a8m/rql)REST API的资源查询语言.

## 资源嵌入

-   [esc](https://github.com/mjibson/esc)-将文件嵌入到GO程序中,并向它们提供HTTP文件系统接口.
-   [fileb0x](https://github.com/UnnoTed/fileb0x)-简单的工具来嵌入文件在去关注"定制"和易于使用.
-   [go-embed](https://github.com/pyros2097/go-embed)生成GO代码,将资源文件嵌入到库或可执行文件中.
-   [go-resources](https://github.com/omeid/go-resources)-用GO嵌入非幻想资源.
-   [go.rice](https://github.com/GeertJohan/go.rice)Go.Lice是一个GO程序包,可以很容易地使用HTML、JS、CSS、图像和模板等资源.
-   [packr](https://github.com/gobuffalo/packr)-将静态文件嵌入到GO二进制文件中的简单易行方法.
-   [statics](https://github.com/go-playground/statics)-将静态资源嵌入到GO文件中,用于单个二进制编译+与HTTPFielStase+SysLink的工作.
-   [statik](https://github.com/rakyll/statik)-将静态文件嵌入到GO可执行文件中.
-   [templify](https://github.com/wlbr/templify)-将外部模板文件嵌入到GO代码中以创建单文件二进制文件.
-   [vfsgen](https://github.com/shurcooL/vfsgen)-生成一个静态实现给定虚拟文件系统的VFSDATA.GO文件.

## 科学与数据分析

*用于科学计算和数据分析的图书馆.*

-   [blas](https://github.com/ziutek/blas)BLAS(基本线性代数子程序)的实现.
-   [chart](https://github.com/vdobler/chart)-简单的图表绘制库的GO.支持多种图形类型.
-   [evaler](https://github.com/soniah/evaler)-简单浮点算术表达式求值器.
-   [ewma](https://github.com/VividCortex/ewma)指数加权移动平均数.
-   [geom](https://github.com/skelterjohn/geom)GRang-2D几何.
-   [go-dsp](https://github.com/mjibson/go-dsp)-数字信号处理的GO.
-   [go-fn](https://github.com/ematvey/go-fn)用GO语言编写的数学函数,这些数学函数不被数学PKG所覆盖.
-   [go-gt](https://github.com/ThePaw/go-gt)用"go"语言编写的图论算法.
-   [go.matrix](https://github.com/skelterjohn/go.matrix)-线性代数的GO(已经停滞).
-   [gocomplex](https://github.com/varver/gocomplex)用于GO程序设计语言的复数库.
-   [goent](https://github.com/kzahedi/goent)熵测度的实现
-   [gofrac](https://github.com/anschelsc/gofrac)-(GoStabrabl)分数库,支持基本算法.
-   [gohistogram](https://github.com/VividCortex/gohistogram)-数据流的近似直方图.
-   [gonum/mat64](https://github.com/gonum/matrix)-矩阵计算的通用程序包.包MAT64为FLUAT64矩阵提供基本的线性代数运算.
-   [gonum/plot](https://github.com/gonum/plot)- GunU/Prand提供了一个用于构建和绘制GO图的API.
-   [goraph](https://github.com/gyuho/goraph)-纯GO图形理论库(数据结构,算法可视化).
-   [gosl](https://github.com/cpmech/gosl)-去线性代数、FFT、几何、NURBS、数值方法、概率、优化、微分方程等的科学图书馆,等等.
-   [gostat](https://github.com/ematvey/gostat)- GO语言的统计库.
-   [GoStats](https://github.com/OGFris/GoStats)GoStats是一个开源的GoLang数学统计库,主要用于机器学习领域,它涵盖了大多数统计测量功能.
-   [graph](https://github.com/yourbasic/graph)-基本图形算法库.
-   [ode](https://github.com/ChristopherRabotin/ode)-常微分方程(ODE)求解器,支持扩展状态和基于信道的迭代停止条件.
-   [orb](https://github.com/paulmach/orb)-二维几何类型与剪辑,GEOJSON和MAPBOX矢量瓦片支持.
-   [pagerank](https://github.com/alixaxel/pagerank)在GO中实现的加权PageRank算法.
-   [PiHex](https://github.com/claygod/PiHex)-实现"Bailey Borwein Plouffe"算法的十六进制数PI.
-   [sparse](https://github.com/james-bowman/sparse)-用于支持科学和机器学习应用的线性代数的Go稀疏矩阵格式,与gonum矩阵库兼容.
-   [stats](https://github.com/montanaflynn/stats)- Golang标准库中缺少通用功能的统计软件包.
-   [streamtools](https://github.com/nytlabs/streamtools)-用于处理数据流的通用图形工具.
-   [TextRank](https://github.com/DavidBelicza/TextRank)-Golang中的TextRank实现,具有可扩展的特性(摘要、加权、短语提取)和多线程(goroutine)支持.
-   [triangolatte](https://github.com/tchayen/triangolatte)二维三角剖分库.允许将线条和多边形(基于点)转换为GPU语言.

## 安全性

*用于帮助您的应用程序更安全的库.*

-   [acmetool](https://github.com/hlandau/acme)ACME(让我们加密)客户端工具自动更新.
-   [acra](https://github.com/cossacklabs/acra)-网络加密代理,以保护基于数据库的应用程序免受数据泄漏:强选择性加密,SQL注入预防,入侵检测系统.
-   [argon2pw](https://github.com/raja/argon2pw)- ARGON2密码哈希生成与恒定时间密码比较.
-   [autocert](https://godoc.org/golang.org/x/crypto/acme/autocert)自动提供让我们加密证书并启动TLS服务器.
-   [BadActor](https://github.com/jaredfolkins/badactor)在内存中,应用驱动的JavaER以Valu2BAN的精神构建.
-   [Cameradar](https://github.com/Ullaakut/cameradar)-工具和库远程监视来自监控摄像机的RTSP流.
-   [go-yara](https://github.com/hillu/go-yara)-去绑定[YARA](https://github.com/plusvic/yara)"模式匹配瑞士刀的恶意软件研究人员(和其他人)".
-   [goArgonPass](https://github.com/dwin/goArgonPass)- ARGON2密码哈希和验证,设计为兼容现有的Python和PHP实现.
-   [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword)-一个可能偏执的包,用于安全地散列和加密密码.
-   [lego](https://github.com/xenolf/lego)-纯AcMe客户端库和CLI工具(用于让我们加密).
-   [memguard](https://github.com/awnumar/memguard)-一个纯GO库,用于处理内存中的敏感值.
-   [nacl](https://github.com/kevinburke/nacl)-去实现API的NaCL集合.
-   [passlib](https://github.com/hlandau/passlib)-未来防伪密码哈希库.
-   [secure](https://github.com/unrolled/secure)- HTO中间件的GO,这有助于一些快速安全获胜.
-   [simple-scrypt](https://github.com/elithrar/simple-scrypt)-具有简单、明显的API和内置的自动成本校准的ScRyPT包.
-   [ssh-vault](https://github.com/ssh-vault/ssh-vault)使用SSH密钥加密/解密.

## 序列化

*用于二进制序列化的库和工具.*

-   [asn1](https://github.com/PromonLogicalis/asn1)- Galang.ASN.1 BER和DER编码库.
-   [bambam](https://github.com/glycerine/bambam)发电机为CANN原型模式从GO.
-   [colfer](https://github.com/pascaldekloe/colfer)- Colfer二进制格式的代码生成.
-   [csvutil](https://github.com/jszwec/csvutil)-高性能、惯用的CSV记录对本地GO结构的编码和解码.
-   [fwencoder](https://github.com/o1egl/fwencoder)-固定宽度文件解析器(编码和解码库)为GO.
-   [go-capnproto](https://github.com/glycerine/go-capnproto)- CAPN原始库和解析器的GO.
-   [go-codec](https://github.com/ugorji/go)-msgpack、cbor和json的高性能、特性丰富、惯用编码、解码和rpc库,支持基于运行时的OR代码生成.
-   [gogoprotobuf](https://github.com/gogo/protobuf)-协议缓冲器,用于小工具.
-   [goprotobuf](https://github.com/golang/protobuf)-以库和协议编译器插件的形式支持谷歌的协议缓冲区.
-   [jsoniter](https://github.com/json-iterator/go)-高性能100%兼容的替换"编码/JSON".
-   [mapstructure](https://github.com/mitchellh/mapstructure)GO库,用于将通用映射值解码为本地GO结构.
-   [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder)- GoLang图书馆,用于处理PHP会话格式和PHP序列化/非序列化功能.
-   [structomap](https://github.com/tuvistavie/structomap)-库可以轻松地、动态地从静态结构生成地图.
-   [structs](https://github.com/fatih/structs)-支持将结构转换为映射、结构键/值到切片等的库.

## 服务器应用程序

-   [algernon](https://github.com/xyproto/algernon)- HTTP/2 Web服务器,内置Lua、MARDUN、GCSS和安伯支持.
-   [Caddy](https://github.com/mholt/caddy)Caddy是另一种HTTP/2 Web服务器,它易于配置和使用.
-   [consul](https://www.consul.io/)领事是一种服务发现、监控和配置的工具.
-   [devd](https://github.com/cortesi/devd)-为开发人员提供本地Web服务器.
-   [discovery](https://github.com/Bilibili/discovery)-弹性中间层负载平衡和故障转移的注册表.
-   [etcd](https://github.com/coreos/etcd)-用于共享配置和服务发现的高度可用的密钥值存储.
-   [Fider](https://github.com/getfider/fider)- Fider是一个开放的平台来收集和组织客户反馈.
-   [Flagr](https://github.com/checkr/flagr)- Flagr是一个开放源码的特征标记和A/B测试服务.
-   [jackal](https://github.com/ortuman/jackal)-用GO编写的XMPP服务器.
-   [minio](https://github.com/minio/minio)MIIO是一个分布式对象存储服务器.
-   [nsq](http://nsq.io/)-实时分布式消息传递平台.
-   [RoadRunner](https://github.com/spiral/roadrunner)-高性能PHP应用服务器、负载均衡器和进程管理器.
-   [yakvs](https://git.sci4me.com/sci4me/yakvs)-小型、网络化、内存键值存储.

## 模板引擎

*图书馆和工具模板和词汇.*

-   [ace](https://github.com/yosssi/ace)ACE是GO的HTML模板引擎,由SLIM和杰德启发.王牌是精金的.
-   [amber](https://github.com/eknkc/amber)安伯是一个优雅的模板引擎,用于GO程序设计语言,灵感来自汉姆和杰德.
-   [damsel](https://github.com/dskinner/damsel)-标记语言,其特征在于HTML通过CSS选择器勾画,可通过PKG HTML/模板等扩展.
-   [ego](https://github.com/benbjohnson/ego)-轻量级模板语言,允许您在GO中编写模板.模板被翻译成GO和编译.
-   [extemplate](https://github.com/dannyvankooten/extemplate)-围绕HTML/模板的小型包装器,允许基于文件的模板继承.
-   [fasttemplate](https://github.com/valyala/fasttemplate)-简单快速的模板引擎.替代模板占位符达到10X快[text/template](http://golang.org/pkg/text/template/).
-   [gofpdf](https://github.com/jung-kurt/gofpdf)PDF文档生成器,支持文本、绘图和图像的高级支持.
-   [hero](https://github.com/shiyanhui/hero)-英雄是一个方便、快速、强大的GO模板引擎.
-   [jet](https://github.com/CloudyKit/jet)-喷射模板引擎.
-   [kasia.go](https://github.com/ziutek/kasia.go)-模板系统,用于HTML和其他文本文档-GO实现.
-   [liquid](https://github.com/osteele/liquid)-实现Suffice液体模板.
-   [mustache](https://github.com/hoisie/mustache)-去实现胡桃模板语言.
-   [pongo2](https://github.com/flosch/pongo2)- Django模板引擎的GO.
-   [quicktemplate](https://github.com/valyala/quicktemplate)-快速,强大,但易于使用的模板引擎.将模板转换为GO代码,然后编译它.
-   [raymond](https://github.com/aymerick/raymond)-在GO中实现完整的把手.
-   [Razor](https://github.com/sipin/gorazor)Golang剃须刀视图引擎.
-   [Soy](https://github.com/robfig/soy)-关闭模板(又名大豆模板)为GO,跟随[official spec](https://developers.google.com/closure/templates/).
-   [velvet](https://github.com/gobuffalo/velvet)-在GO中实现完整的把手.

## 测试

*用于测试代码库和生成测试数据的库.*

-   测试框架

    -   [assert](https://github.com/go-playground/assert)-基本断言库使用附带的本地GO测试,以及用于自定义断言的构建块.
    -   [badio](https://github.com/cavaliercoder/badio)- GO的扩展`testing/iotest`包裹.
    -   [baloo](https://github.com/h2non/baloo)-表达和通用的端到端HTTP API测试很容易.
    -   [biff](https://github.com/fulldump/biff)-分岔测试框架,BDD兼容.
    -   [bro](https://github.com/marioidival/bro)-在目录中监视文件并为它们运行测试.
    -   [charlatan](https://github.com/percolate/charlatan)-为测试生成假接口实现的工具.
    -   [cupaloy](https://github.com/bradleyjkemp/cupaloy)-测试框架的简单快照测试插件.
    -   [dbcleaner](https://github.com/khaiql/dbcleaner)-为测试目的清理数据库,受到启发`database_cleaner`红宝石.
    -   [dsunit](https://github.com/viant/dsunit)- SQL、NoSQL、结构化文件的数据存储测试.
    -   [endly](https://github.com/viant/endly)-声明式端到端功能测试.
    -   [frisby](https://github.com/verdverm/frisby)REST API测试框架.
    -   [ginkgo](http://onsi.github.io/ginkgo/)-BDD测试框架的GO.
    -   [go-carpet](https://github.com/msoap/go-carpet)-查看终端测试覆盖率的工具.
    -   [go-cmp](https://github.com/google/go-cmp)在测试中比较GO值的包
    -   [go-mutesting](https://github.com/zimmski/go-mutesting)GO源代码的突变测试.
    -   [go-testdeep](https://github.com/maxatome/go-testdeep)-非常灵活的Gangang-TrimePrimes,扩展了GO测试包.
    -   [go-vcr](https://github.com/dnaeon/go-vcr)记录和重放HTTP交互以进行快速、确定和准确的测试.
    -   [goblin](https://github.com/franela/goblin)-摩卡样测试框架FO.
    -   [gocheck](http://labix.org/gocheck)-更先进的测试框架替代GoTest.
    -   [GoConvey](https://github.com/smartystreets/goconvey/)BDD样式框架,具有Web UI和实况重载.
    -   [gocrest](https://github.com/corbym/gocrest)可组合的哈姆雷斯特式匹配器.
    -   [godog](https://github.com/DATA-DOG/godog)-黄瓜或BeHAT类似BDD框架的GO.
    -   [gofight](https://github.com/appleboy/gofight)- Galang-Router框架的API处理程序测试.
    -   [gogiven](https://github.com/corbym/gogiven)-YATSPEC,类似于GO的BDD测试框架.
    -   [gomega](http://onsi.github.io/gomega/)-RSPEC类似Matter /断言库.
    -   [GoSpec](https://github.com/orfjackal/gospec)-BDD风格测试框架,用于GO编程语言.
    -   [gospecify](https://github.com/stesla/gospecify)这为测试GO代码提供了一种BDD语法.对于使用过诸如RSPEC之类的库的人来说应该是熟悉的.
    -   [gosuite](https://github.com/pavlo/gosuite)-带轻量级测试套件与安装/拆卸设施`testing`通过利用GO1.7的子测试.
    -   [gotest.tools](https://github.com/gotestyourself/gotest.tools)-一个包的集合,以增加GO测试包和支持常见模式.
    -   [Hamcrest](https://github.com/rdrdr/hamcrest)-声明性匹配器对象的FLUENT框架,当应用于输入值时,会产生自描述结果.
    -   [httpexpect](https://github.com/gavv/httpexpect)-简洁、声明性强、易于使用的端到端HTTP和REST API测试.
    -   [restit](https://github.com/yookoala/restit)-GO微框架来帮助编写REST API集成测试.
    -   [testfixtures](https://github.com/go-testfixtures/testfixtures)-一个帮助Rails类似的测试设备来测试数据库应用程序的助手.
    -   [Testify](https://github.com/stretchr/testify)-标准的GO测试包的神圣延伸.
    -   [testsql](https://github.com/zhulongcheng/testsql)-在测试前生成SQL文件的测试数据,并在完成后清除.
    -   [Tt](https://github.com/vcaesar/tt)-简单多彩的测试工具.
    -   [wstest](https://github.com/posener/wstest)WebSutoClient用于单元测试WebStutoHTTP处理程序.

-   嘲弄

    -   [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter)-用于生成独立的模拟对象的工具.
    -   [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock)-模拟数据库交互的模拟SQL驱动程序.
    -   [go-txdb](https://github.com/DATA-DOG/go-txdb)-基于单事务的数据库驱动程序主要用于测试目的.
    -   [gock](https://github.com/h2non/gock)-通用的HTTP嘲弄很容易.
    -   [gomock](https://github.com/golang/mock)模拟编程语言的框架.
    -   [govcr](https://github.com/seborama/govcr)Golang的HTTP模拟:记录和重放脱机测试的HTTP交互.
    -   [minimock](https://github.com/gojuno/minimock)- GO接口的模拟生成器.
    -   [mockhttp](https://github.com/tv42/mockhttp)为GO HTTP.Rebug编写器的模拟对象.

-   模糊和增量调试/缩小/缩小.

    -   [go-fuzz](https://github.com/dvyukov/go-fuzz)-随机试验系统.
    -   [gofuzz](https://github.com/google/gofuzz)-用于填充具有随机值的GO对象的库.
    -   [Tavor](https://github.com/zimmski/tavor)-通用模糊和增量调试框架.

-   硒和浏览器控制工具.
    -   [cdp](https://github.com/mafredri/cdp)-为Chrome调试协议键入安全绑定,可以与浏览器或实现它的其他调试目标一起使用.
    -   [chromedp](https://github.com/knq/chromedp)一种驱动/测试Chrome、Safari、EdGE、Android WebVIEW和支持Chrome调试协议的其他浏览器的方法.
    -   [ggr](https://github.com/aerokube/ggr)-一个轻量级服务器,它将硒WebReST请求路由并代理到多个硒集线器.
    -   [selenoid](https://github.com/aerokube/selenoid)-在容器内启动浏览器的替代硒集线器服务器.

## 文本处理

*用于解析和操作文本的库.*

-   特定格式
    -   [align](https://github.com/Guitarbum722/align)-对齐文本的通用应用程序.
    -   [allot](https://github.com/sbstjn/allot)CLI工具和机器人的占位符和通配符文本分析.
    -   [bbConvert](https://github.com/CalebQ42/bbConvert)-将BBCODEL转换为HTML,允许您添加对自定义BBCODEL标签的支持.
    -   [blackfriday](https://github.com/russross/blackfriday)- GO中的标记处理程序.
    -   [bluemonday](https://github.com/microcosm-cc/bluemonday)- HTML消毒剂.
    -   [colly](https://github.com/asciimoo/colly)-快速而优雅的刮毛机
    -   [commonregex](https://github.com/mingrammer/commonregex)- GO的常用正则表达式的集合
    -   [dataflowkit](https://github.com/slotix/dataflowkit)- Web刮削框架,将网站转换为结构化数据.
    -   [doi](https://github.com/hscells/doi)GO中的文档对象标识符(DOI)解析器.
    -   [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go)EdgRealFig文件解析器和操作器用于GO.
    -   [enca](https://github.com/endeveit/enca)-最小的CGO绑定[libenca](http://cihar.com/software/enca/).
    -   [encdec](https://github.com/mickep76/encdec)-包提供了一个通用的编码器和解码器的接口.
    -   [genex](https://github.com/alixaxel/genex)-计数并展开正则表达式到所有匹配字符串中.
    -   [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown)- GITHUB调味标记渲染器(使用BLFRIFIDY),带有栅栏代码块突出显示、可点击的标题锚点链接.
    -   [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth)-固定宽度文本格式化(带有反射的编码器/解码器).
    -   [go-humanize](https://github.com/dustin/go-humanize)-格式化时间、数字和内存大小到人类可读格式.
    -   [go-nmea](https://github.com/adrianmo/go-nmea)-NMEA解析器库,用于GO语言.
    -   [go-runewidth](https://github.com/mattn/go-runewidth)-函数以获得字符或字符串的固定宽度.
    -   [go-slugify](https://github.com/mozillazg/go-slugify)-用多种语言支持漂亮的蛞蝓.
    -   [go-vcard](https://github.com/emersion/go-vcard)解析和格式化VCARD.
    -   [gofeed](https://github.com/mmcdole/gofeed)在RE中解析RSS和Atom提要.
    -   [gographviz](https://github.com/awalterschulze/gographviz)-解析图形化的点语言.
    -   [gommon/bytes](https://github.com/labstack/gommon/tree/master/bytes)-将字节设置为字符串.
    -   [gonameparts](https://github.com/polera/gonameparts)把人名分为个人名字部分.
    -   [goq](https://github.com/andrewstuart/goq)-使用JQuery语法(使用GoQuery)使用Stutt标签声明性解除封送HTML.
    -   [GoQuery](https://github.com/PuerkitoBio/goquery)GoQuery为GO语言带来语法和一组类似于jQuery的特性.
    -   [goregen](https://github.com/zach-klippenstein/goregen)-用于从正则表达式生成随机字符串的库.
    -   [gotext](https://github.com/leonelquinteros/gotext)GONGETTICE实用工具.
    -   [guesslanguage](https://github.com/endeveit/guesslanguage)-函数来确定Unicode文本的自然语言.
    -   [htmlquery](https://github.com/antchfx/htmlquery)-一个HTML的XPath查询包,允许您通过XPath表达式提取数据或从HTML文档中进行评估
    -   [inject](https://github.com/facebookgo/inject)-包注入提供反射式注射器.
    -   [mxj](https://github.com/clbanning/mxj)-将XML编码或解码为JSON或MAP[一串]接口{};用点符号路径和通配符提取值.替换X2J和J2X包.
    -   [sdp](https://github.com/gortc/sdp)会话描述协议[RFC 4566](https://tools.ietf.org/html/rfc4566)]
    -   [sh](https://github.com/mvdan/sh)- shell解析器和格式化程序.
    -   [slug](https://github.com/gosimple/slug)- URL友好Sulu化与多种语言支持.
    -   [Slugify](https://github.com/avelino/slugify)去处理字符串的SLUGIZY应用程序.
    -   [syndfeed](https://github.com/zhengchun/syndfeed)-原子1和RSS 2的联合馈源.
    -   [toml](https://github.com/BurntSushi/toml)- TML配置格式(带反射的编码器/解码器).
-   效用
    -   [gotabulate](https://github.com/bndr/gotabulate)-很容易用GO打印表格数据.
    -   [kace](https://github.com/codemodus/kace)-常见情况下的转换,覆盖常见的初始化.
    -   [parseargs-go](https://github.com/nproc/parseargs-go)-字符串引语解析器,它理解引号和反斜杠.
    -   [parth](https://github.com/codemodus/parth)- URL路径分割解析.
    -   [radix](https://github.com/yourbasic/radix)-快速字符串排序算法.
    -   [xj2go](https://github.com/stackerzzq/xj2go)-将XML或JSON转换为SO结构.
    -   [xurls](https://github.com/mvdan/xurls)从文本中提取URL.

## 第三方API

*用于访问第三方API的库.*

-   [amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api)-转到客户端库[Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html).
-   [anaconda](https://github.com/ChimeraCoder/anaconda)转到Twitter 1.1 API的客户端库.
-   [aws-sdk-go](https://github.com/aws/aws-sdk-go)- GO编程语言的官方AWS SDK.
-   [brewerydb](https://github.com/naegelejd/brewerydb)GO库用于访问BRWYYDB API.
-   [cachet](https://github.com/andygrunwald/cachet)-转到客户端库[Cachet (open source status page system)](https://cachethq.io/).
-   [circleci](https://github.com/jszwedko/go-circleci)-去与CliCeli的API交互的客户端库.
-   [clarifai](https://github.com/samuelcouch/clarifai)转到客户端库,用于与CalrIFAIAPI接口.
-   [codeship-go](https://github.com/codeship/codeship-go)转到客户端库,用于与CODESIP的API V2交互.
-   [discordgo](https://github.com/bwmarrin/discordgo)-为不和谐聊天API进行绑定.
-   [ethrpc](https://github.com/onrik/ethrpc)-为EJUM JSON RPC API进行绑定.
-   [facebook](https://github.com/huandu/facebook)支持脸谱网图形API的GO库.
-   [fcm](https://github.com/maddevsio/fcm)为FixBASE云消息去库.
-   [gads](https://github.com/emiddleton/gads)-谷歌AdWords非官方API.
-   [gami](https://github.com/bit4bit/gami)转到星号管理器接口库.
-   [gcm](https://github.com/Aorioli/gcm)为谷歌云消息传递去库.
-   [geo-golang](https://github.com/codingsince1985/geo-golang)-转到库访问[Google Maps](https://developers.google.com/maps/documentation/geocoding/intro),[MapQuest](http://open.mapquestapi.com/geocoding/),[Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search),[OpenCage](http://geocoder.opencagedata.com/api.html),[Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx),[Mapbox](https://www.mapbox.com/developers/api/geocoding/)和[OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim)地理编码/反向地理编码API.
-   [github](https://github.com/google/go-github)GO库,用于访问GITHUB REST API V3.
-   [githubql](https://github.com/shurcooL/githubql)GO库,用于访问GITHUB图形化API API V4.
-   [go-chronos](https://github.com/axelspringer/go-chronos)-Go库,用于与[Chronos](https://mesos.github.io/chronos/)作业调度程序
-   [go-hacknews](https://github.com/PaulRosset/go-hacknews)-为HACEReNeXAPI API的小GO客户端.
-   [go-imgur](https://github.com/koffeinsource/go-imgur)-转到客户端库[imgur](https://imgur.com)
-   [go-jira](https://github.com/andygrunwald/go-jira)-转到客户端库[Atlassian JIRA](https://www.atlassian.com/software/jira)
-   [go-marathon](https://github.com/gambol99/go-marathon)-去图书馆与中层马拉松Paas互动.
-   [go-myanimelist](https://github.com/nstratos/go-myanimelist)去客户端库访问[MyAnimeList API](http://myanimelist.net/modules.php?go=api).
-   [go-sophos](https://github.com/esurdam/go-sophos)-为客户机的客户机库[Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en)具有零依赖性.
-   [go-sptrans](https://github.com/sergioaugrod/go-sptrans)为SPANTH OLHO活体API应用客户端库.
-   [go-telegraph](https://github.com/toby3d/go-telegraph)-电信发布平台API客户端.
-   [go-tgbot](https://github.com/olebedev/go-tgbot)-纯Gangon电报BOTAPI API,由SWAGER文件、基于会话的路由器和中间件生成.
-   [go-trending](https://github.com/andygrunwald/go-trending)转到访问库[trending repositories](https://github.com/trending)和[developers](https://github.com/trending/developers)在吉图布.
-   [go-twitch](https://github.com/knspriggs/go-twitch)-去与TwityV3 API交互的客户端.
-   [go-twitter](https://github.com/dghubble/go-twitter)转到Twitter V1.1 API的客户端库.
-   [go-unsplash](https://github.com/hbagdi/go-unsplash)-为客户机的客户机库[Unsplash.com](https://unsplash.com)应用程序编程接口.
-   [go-xkcd](https://github.com/nishanths/go-xkcd)-为XKCD API去客户端.
-   [goamz](https://github.com/mitchellh/goamz)流行叉子[goamz](https://launchpad.net/goamz)它为某些包添加了一些缺少的API调用.
-   [golyrics](https://github.com/mamal72/golyrics)- Golyrics是一个GO库,从维基网站获取音乐歌词数据.
-   [GoMusicBrainz](https://github.com/michiwend/gomusicbrainz)-转到MysCyrz WS2客户端库.
-   [google](https://github.com/google/google-api-go-client)自动生成的谷歌API.
-   [google-analytics](https://github.com/chonthu/go-google-analytics)-简单包装,便于谷歌分析报告.
-   [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang)谷歌云API进入客户端库.
-   [google-email-audit-api](https://github.com/ngs/go-google-email-audit-api)-转到客户端库[Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/).
-   [gostorm](https://github.com/jsgilmore/gostorm)-GoStorm是一个Go库,它实现了编写与Storm外壳通信的Storm喷口和Go中的Bolts所需的通信协议.
-   [govkbot](https://github.com/nikepan/govkbot)-简单走[VK](https://vk.com)BOT库.
-   [hipchat](https://github.com/andybons/hipchat)这个项目为HiTraceAPI实现了Galang-Client库.
-   [hipchat (xmpp)](https://github.com/daneharrigan/hipchat)-一个Galang-Puxor通过XMPP与HIPCATH通信.
-   [igdb](https://github.com/Henry-Sarabia/igdb)-去客户机[Internet Game Database API](https://api.igdb.com/).
-   [Medium](https://github.com/Medium/medium-sdk-go)- Golang SDK为媒体的OAuth2 API.
-   [megos](https://github.com/andygrunwald/megos)-用于访问AN的客户端库[Apache Mesos](http://mesos.apache.org/)集群.
-   [micha](https://github.com/onrik/micha)为电报BOT API去库.
-   [minio-go](https://github.com/minio/minio-go)Myo GO库用于Amazon S3兼容云存储.
-   [mixpanel](https://github.com/dukex/mixpanel)- Mixpanel是一个用于跟踪事件的库,并从您的GO应用程序向MixPosits发送MixStor配置文件更新.
-   [patreon-go](https://github.com/mxpv/patreon-go)-为PATReAPI API运行库.
-   [paypal](https://github.com/logpacker/PayPal-Go-SDK)- PayPal支付API的包装器.
-   [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk)- PrYLYFE REST API GO SDK.
-   [pushover](https://github.com/gregdel/pushover)为Pushover API打包.
-   [rrdaclient](https://github.com/Omie/rrdaclient)GO库访问STATDNSCOM API,这又是RRDA API.通过HTTP查询DNS.
-   [shopify](https://github.com/rapito/go-shopify)转到库,以向CualType API请求CRUD.
-   [slack](https://github.com/nlopes/slack)在GO中松弛API.
-   [smite](https://github.com/sergiotapia/smitego)-打包以访问SMIT游戏API.
-   [spotify](https://github.com/rapito/go-spotify)GO库访问Spotify Web API.
-   [steam](https://github.com/sostronk/go-steam)-去图书馆与蒸汽游戏服务器互动.
-   [stripe](https://github.com/stripe/stripe-go)-为条带API去客户端.
-   [tbot](https://github.com/yanzay/tbot)-具有类似于NET/HTTP的API的电话BOT服务器.
-   [telebot](https://github.com/tucnak/telebot)-写在GO中的电报BOT框架.
-   [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api)-简洁干净的电话BOT客户端.
-   [textbelt](https://github.com/dietsche/textbelt)-为TebBeltT.TXT消息传递API打开客户端.
-   [TheMovieDb](https://github.com/jbrodriguez/go-tmdb)-简单的Gangang-Pube[themoviedb.org](https://themoviedb.org).
-   [translate](https://github.com/poorny/translate)-在线翻译包.
-   [Trello](https://github.com/adlio/trello)为TrRoLAPI API打包.
-   [tumblr](https://github.com/mattcunningham/gumblr)为TunBLR V2 API进行打包.
-   [uptimerobot](https://github.com/bitfield/uptimerobot)-运行时包装器和命令行客户端,用于正常运行的机器人V2 API.
-   [webhooks](https://github.com/go-playground/webhooks)Webhook接收器,用于GITHUB和比特桶.
-   [wit-go](https://github.com/wit-ai/wit-go)-为WIT.AI HTTP API去客户端.
-   [ynab](https://github.com/brunomvsouza/ynab.go)为YNABAPI的GO包装器
-   [zooz](https://github.com/gojuno/go-zooz)转到Zooz API的客户端.

## 工具库

*通用工具和工具,使您的生活更轻松.*

-   [abutil](https://github.com/bahlo/abutil)-收集经常使用的Golang帮手.
-   [apm](https://github.com/topfreegames/apm)用HTTP API处理Golang应用程序的过程管理器.
-   [backscanner](https://github.com/icza/backscanner)-类似于bufio.Scanner的扫描器,但它以相反的顺序读取和返回行,从给定位置开始,然后向后移动.
-   [boilr](https://github.com/tmrts/boilr)-快速创建CLI工具,用于从样板模板创建项目.
-   [chyle](https://github.com/antham/chyle)-使用具有多种配置可能性的Git存储库的CeleLogg生成器.
-   [circuit](https://github.com/cep21/circuit)-一种高效和完整的Hythx类似的断路器模式的GO实现.
-   [circuitbreaker](https://github.com/rubyist/circuitbreaker)-断路器.
-   [clockwerk](http://github.com/onatm/clockwerk)-使用简单、流畅的语法打包程序以安排周期性作业.
-   [clockwork](https://github.com/whiteShtef/clockwork)-简单和直观的作业调度库中的GO.
-   [command](https://github.com/txgruppi/command)-线程安全串行和并行调度器的命令模式.
-   [copy-pasta](https://github.com/jutkko/copy-pasta)-通用多工作站剪贴板,使用S3类后端进行存储.
-   [ctop](https://github.com/bcicen/ctop) - [Top-like](http://ctop.sh)容器度量的接口(例如HTTH).
-   [Death](https://github.com/vrecan/death)-用信号管理GO应用程序关闭.
-   [Deepcopier](https://github.com/ulule/deepcopier)为GO的简单结构复制.
-   [delve](https://github.com/derekparker/delve)-转到调试器.
-   [dlog](https://github.com/kirillDanshin/dlog)编译时间控制记录器,使您的发布更小,而不必删除调试调用.
-   [ergo](https://github.com/cristianoliveira/ergo)-管理多个本地服务在不同端口上运行很容易.
-   [evaluator](https://github.com/nullne/evaluator)-基于S表达式动态地评估表达式.它简单易行.
-   [excelize](https://github.com/360EntSecGroup-Skylar/excelize)- Golang图书馆用于阅读和编写微软Excel(XLSX)文件.
-   [fastlz](https://github.com/digitalcrab/fastlz)包裹[FastLz](http://fastlz.org/)(免费,开源,便携式实时压缩库)为GoLang.
-   [filetype](https://github.com/h2non/filetype)-小包推断文件类型检查魔术数字签名.
-   [filler](https://github.com/yaronsumel/filler)-使用"填充"标签填充结构的小实用程序.
-   [fpGo](https://github.com/TeaEntityLab/fpGo)- Monad,Golang的功能编程特性
-   [fzf](https://github.com/junegunn/fzf)-命令行模糊查找器写在GO.
-   [gaper](https://github.com/maxcnunes/gaper)-当崩溃或一些被监视的文件更改时,构建并重新启动GO项目.
-   [generate](https://github.com/go-playground/generate)-运行在指定的路径或环境变量上递归生成,并可以通过正则表达式进行筛选.
-   [gentleman](https://github.com/h2non/gentleman)-全功能插件驱动的HTTP客户端库.
-   [git-time-metric](https://github.com/git-time-metric/gtm)Git简单、无缝、轻量级的时间跟踪.
-   [GJSON](https://github.com/tidwall/gjson)用一行代码获取JSON值.
-   [go-astitodo](https://github.com/asticode/go-astitodo)在GO代码中解析ToDOS.
-   [go-bind-plugin](https://github.com/wendigo/go-bind-plugin)-GO:生成包装GORIN插件(仅1.8)的符号的工具.
-   [go-cron](https://github.com/rk/go-cron)-用于go的简单Cron库,可以以不同的间隔执行闭包或函数,从每秒一次到每年在特定的日期和时间执行一次.主要用于Web应用程序和长时间运行的守护进程.
-   [go-dry](https://github.com/ungerik/go-dry)-干洗(不要重复)包装.
-   [go-excel](https://github.com/szyhf/go-excel)-一个简单而轻量级的阅读器,可以读取类似的DB类Excel作为表.
-   [go-funk](https://github.com/thoas/go-funk)-现代GO实用库,它提供帮助器(映射、查找、包含、筛选、块、反转、……).
-   [go-health](https://github.com/Talento90/go-health)健康包简化了向您的服务添加健康检查的方式.
-   [go-httpheader](https://github.com/mozillazg/go-httpheader)-将库编码为头字段的GO库.
-   [go-rate](https://github.com/beefsack/go-rate)GO定时限速器.
-   [go-respond](https://github.com/nicklaw5/go-respond)-用于处理常见HTTP JSON响应的软件包.
-   [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator)XML编写的站点地图生成器.
-   [go-torch](https://github.com/uber/go-torch)GO程序的随机火焰图分析器.
-   [go-trigger](https://github.com/sadlil/go-trigger)GO Lang-Global事件触发程序,用ID注册事件,并从项目的任何地方触发事件.
-   [go-underscore](https://github.com/tobyhede/go-underscore)-有用的功能收集集合实用工具的有用集合.
-   [goback](https://github.com/carlescere/goback)去简单的指数退避包.
-   [godaemon](https://github.com/VividCortex/godaemon)-编写守护进程的实用工具.
-   [godropbox](https://github.com/dropbox/godropbox)-用于从Dropbox编写GO服务/应用程序的通用库.
-   [gohper](https://github.com/cosiner/gohper)-各种工具/模块有助于开发.
-   [gojq](https://github.com/elgs/gojq)Golang中的JSON查询.
-   [gojson](https://github.com/ChimeraCoder/gojson)-从示例JSON自动生成GO(GORANG)结构定义.
-   [golarm](https://github.com/msempere/golarm)-火灾警报与系统事件.
-   [golog](https://github.com/mlimaloureiro/golog)-轻松和轻量级CLI工具,时间跟踪您的任务.
-   [gopencils](https://github.com/bndr/gopencils)-小而简单的软件包,可以轻松地使用REST API.
-   [goplaceholder](https://github.com/michiwend/goplaceholder)-一个小的GangangLIB生成占位符图像.
-   [goreleaser](https://github.com/goreleaser/goreleaser)尽可能快速和容易地传送二进制文件.
-   [goreporter](https://github.com/wgliang/goreporter)- Golang工具,可以进行静态分析、单元测试、代码审查和生成代码质量报告.
-   [goreq](https://github.com/franela/goreq)-用于GO语言的最小和简单请求库.
-   [goreq](https://github.com/smallnest/goreq)-基于GORQUEST的简化的HTTP客户端.
-   [gorequest](https://github.com/parnurzeal/gorequest)-简化的HTTP客户端,具有丰富的GO特性.
-   [goseaweedfs](https://github.com/linxGnu/goseaweedfs)-具有几乎所有功能的SeaWeeDFS客户端库.
-   [gotenv](https://github.com/subosito/gotenv)负载环境变量`.env`或任何`io.Reader`进去.
-   [goxlsxwriter](https://github.com/fterrag/goxlsxwriter)-用于编写XLSX(微软Excel)文件的LIXXLSXWrror的Golang绑定.
-   [gpath](https://github.com/tenntenn/gpath)库以在反射中使用GO表达式简化访问结构域.
-   [grequests](https://github.com/levigross/grequests)雅致简约`net/http`遵循Python请求库的包装器.
-   [gron](https://github.com/roylee0704/gron)-使用简单的GO API定义基于时间的任务,Gron的调度器将相应地运行它们.
-   [gubrak](https://gubrak.github.io/)- Golang实用图书馆与句法糖.这就像是土楼,但是格朗的.
-   [htcat](https://github.com/htcat/htcat)-并行和流水线HTTP获取实用工具.
-   [httpcontrol](https://github.com/facebookgo/httpcontrol)-包HTTP-控件允许HTTP传输级别控制围绕超时和重试.
-   [hub](https://github.com/github/hub)用附加功能包装Git命令,与终端交互GITHUB.
-   [hystrix-go](https://github.com/afex/hystrix-go)-实现程序员定义的回退,也就是断路器的HySrx模式.
-   [immortal](https://github.com/immortal/immortal) - \*NIX跨平台(OS不可知)监控器.
-   [intrinsic](https://github.com/mengzhuo/intrinsic)-使用X86 SIMD而不编写任何汇编代码.
-   [JobRunner](https://github.com/bamzi/jobrunner)-智能和特色的CRON作业调度程序内置作业队列和实时监控.
-   [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors)-基于JSONAPI API引用进行绑定.
-   [jsonf](https://github.com/miolini/jsonf)控制台工具,用于突出显示格式和结构查询获取JSON.
-   [jsongo](https://github.com/ricardolonga/jsongo)-FLUENT API,使创建JSON对象更容易.
-   [jsonhal](https://github.com/RichardKnop/jsonhal)-简单GO包将自定义结构封成HAL兼容的JSON响应.
-   [kazaam](https://github.com/Qntfy/kazaam)-API用于任意转换JSON文档.
-   [lrserver](https://github.com/jaschaephraim/lrserver)- LiveReload服务器.
-   [mc](https://github.com/minio/mc)MIIO客户端提供了与Amazon S3兼容的云存储和文件系统工作的最小工具.
-   [mergo](https://github.com/imdario/mergo)-赫尔珀在Golang合并结构和地图.适用于配置默认值,避免混乱的if语句.
-   [minify](https://github.com/tdewolff/minify)-用于HTML、CSS、JS、XML、JSON和SVG文件格式的快速微型化器.
-   [minquery](https://github.com/icza/minquery)-支持有效分页的MongoDB /MGO.V2查询(游标继续在我们离开的文档中列出).
-   [mmake](https://github.com/tj/mmake)现代制造.
-   [moldova](https://github.com/StabbyCutyou/moldova)-用于基于输入模板生成随机数据的实用程序.
-   [mp](https://github.com/sanbornm/mp)-简单CLI电子邮件解析器.它当前采用STDIN并输出JSON.
-   [mssqlx](https://github.com/linxGnu/mssqlx)数据库客户端库,代理任何主从,主控主机结构.轻量级和自动平衡的想法.
-   [multitick](https://github.com/VividCortex/multitick)- Multiplexor队对准球员.
-   [myhttp](https://github.com/inancgumus/myhttp)-简单的API,使HTTP GET请求具有超时支持.
-   [netbug](https://github.com/e-dard/netbug)-轻松远程分析您的服务.
-   [okrun](https://github.com/xta/okrun)-运行错误的压路机.
-   [onecache](https://github.com/adelowo/onecache)-缓存库,支持多个后端存储(ReDIS、MeMcCurrand、文件系统等).
-   [panicparse](https://github.com/maruel/panicparse)-分组相似的GOODUTIN和着色堆栈转储.
-   [peco](https://github.com/peco/peco)-简单的交互式过滤工具.
-   [pester](https://github.com/sethgrid/pester)-以重试、退避和并发的方式访问HTTP客户端调用.
-   [pm](https://github.com/VividCortex/pm)-用HTTP API处理进程(即GOODUTIN)管理器.
-   [profile](https://github.com/pkg/profile)为GO提供简单的剖析支持软件包.
-   [rclient](https://github.com/zpatrick/rclient)可读的、灵活的、简单易用的客户端API.
-   [realize](https://github.com/tockins/realize)-使用文件观察器和实况重新加载构建系统.使用自定义路径运行、生成和监视文件更改.
-   [repeat](https://github.com/ssgreg/repeat)-执行不同的退避策略,用于重试操作和心跳.
-   [request](https://github.com/mozillazg/request)-对人类进行HTTP请求.
-   [rerate](https://github.com/abo/rerate)基于RADIS的速率计数器和速率限制器.
-   [rerun](https://github.com/ivpusic/rerun)-当源更改时重新编译和重新运行应用程序.
-   [resty](https://github.com/go-resty/resty)-简单的HTTP和REST客户端,用于Ruby REST客户端的启发.
-   [retry](https://github.com/kamilsk/retry)-基于上下文的功能机制,重复执行直到成功.
-   [retry](https://github.com/percolate/retry)-一个简单但高度可配置的GO重试包.
-   [retry](https://github.com/thedevsaddam/retry)-简单易行的重试机制包.
-   [retry](https://github.com/shafreeck/retry)-一个非常简单的库,以确保您的工作完成.
-   [retry-go](https://github.com/rafaeljesus/retry-go)重试让Gangang简单简单.
-   [robustly](https://github.com/VividCortex/robustly)-运行函数弹性,捕捉和重新启动恐慌.
-   [rq](https://github.com/ddo/rq)- Galang-Stdlib HTTP客户端更好的接口.
-   [scheduler](https://github.com/carlescere/scheduler)- Cronjobs调度很容易.
-   [sling](https://github.com/dghubble/sling)-为API客户端运行HTTP请求生成器.
-   [spinner](https://github.com/briandowns/spinner)去包装,以方便地提供一个终端纺纱机与选项.
-   [sqlx](https://github.com/jmoiron/sqlx)-在优秀的内置数据库/SQL包的顶部提供一组扩展.
-   [Storm](https://github.com/asdine/storm)-简单而强大的BoLTB工具包.
-   [structs](https://github.com/PumpkinSeed/structs)-实现简单的函数来操作结构.
-   [Task](https://github.com/go-task/task)-简单的"制作"替代品.
-   [toolbox](https://github.com/viant/toolbox)-切片、映射、多聚体、结构、函数、数据转换实用程序.服务路由器,宏评估器,令牌.
-   [ugo](https://github.com/alxrm/ugo)-UGO是切片工具箱,语法简洁.
-   [UNIS](https://github.com/esemplastic/unis)-用于GO中的字符串实用程序的通用架构.
-   [usql](https://github.com/knq/usql)-USQL是SQL数据库的通用命令行接口.
-   [util](https://github.com/shomali11/util)-收集有用的实用函数.(字符串,并发,操作,…).
-   [wuzz](https://github.com/asciimoo/wuzz)交互式HTI检查CLI工具.
-   [xferspdy](https://github.com/monmohan/xferspdy)XFELSPY提供Galangin的二进制差异和补丁库.
-   [xlsx](https://github.com/tealeg/xlsx)-库以简化读取GO Excel程序中微软Excel的最新版本所使用的XML格式.
-   [xlsx](https://github.com/plandem/xlsx)-快速和安全的方式读取/更新现有的微软Excel文件中的GO程序.

## 验证

*用于验证的库.*

-   [govalidator](https://github.com/asaskevich/govalidator)-用于字符串、数值、切片和结构的验证程序和消除器.
-   [govalidator](https://github.com/thedevsaddam/govalidator)-用简单的规则验证Gangon请求数据.受到Laravel请求验证的启发.
-   [ozzo-validation](https://github.com/go-ozzo/ozzo-validation)-支持使用在普通代码构造中指定的可配置和可扩展的验证规则来验证各种数据类型(结构、字符串、映射、片等),而不是使用结构标记.
-   [validate](https://github.com/markbates/validate)这个包提供了一个编写GO应用程序验证的框架.
-   [validator](https://github.com/go-playground/validator)进行结构和现场验证,包括交叉场、交叉结构、地图、切片和阵列潜水.

## 版本控制

*用于版本控制的库.*

-   [gh](https://github.com/rjeczalik/gh)-用于Github WebHookes的脚本服务器和NET/HTTP中间件.
-   [git2go](https://github.com/libgit2/git2go)-为LBGIT2进行绑定.
-   [go-vcs](https://github.com/sourcegraph/go-vcs)-在VO中操作和检查VCS库.
-   [hgo](https://github.com/beyang/hgo)- Hgo是一个GO包的集合,提供对本地水银存储库的读取访问.

## 视频

*用于操作视频的库.*

-   [gmf](https://github.com/3d0c/gmf)FFMPEG AV的绑定\*图书馆.
-   [go-astisub](https://github.com/asticode/go-astisub)-操纵GO中的字幕(.SRT,.STL,.TTML,.WebVTT,.SSA/.ASS,图文电视,SMI等).
-   [go-astits](https://github.com/asticode/go-astits)在GO中解析和解复用MPEG传输流(.TS).
-   [goav](https://github.com/giorgisio/goav)- FFMPEG的复数GO绑定.
-   [gst](https://github.com/ziutek/gst)-为GStreamer进行绑定.
-   [libgosubs](https://github.com/wargarblgarbl/libgosubs)字幕格式支持GO.支持,SRT,TTML,和As.
-   [libvlc-go](https://github.com/adrg/libvlc-go)-为LBVLC 2、X/ 3、X/ 4 .x(由VLC媒体播放器使用)绑定.
-   [v4l](https://github.com/korandiz/v4l)用于Linux的视频采集库,写在GO中.

## Web框架

*全栈Web框架.*

-   [aah](https://aahframework.org)可扩展、高效、快速开发的GO Web框架.
-   [Aero](https://github.com/aerogo/aero)高性能的GO Web框架,达到灯塔的最高分数.
-   [Air](https://github.com/aofei/air)-一个理想的精简的GO Web框架.
-   [Banjo](https://github.com/nsheremet/banjo)-非常简单快速的GO Web框架.
-   [Beego](https://github.com/astaxie/beego)BEYGO是一个开源的、高性能的GO编程框架.
-   [Buffalo](http://gobuffalo.io)-带来轨道的生产力去!
-   [Echo](https://github.com/labstack/echo)-高性能、极简主义的GO Web框架.
-   [Fireball](https://github.com/zpatrick/fireball)-更多的"自然"感觉Web框架.
-   [Florest](https://github.com/jabong/florest-core)-基于高性能工作流的REST API框架.
-   [Gem](https://github.com/go-gem/gem)-简单快速的Web框架,友好的REST API.
-   [Gin](https://github.com/gin-gonic/gin)- GIN是一个用GO编写的Web框架!它具有类似马蒂尼的API,性能更佳,速度快40倍.如果你需要性能和良好的生产力.
-   [Gizmo](https://github.com/NYTimes/gizmo)纽约时报使用的微服务工具包.
-   [go-json-rest](https://github.com/ant0ine/go-json-rest)-快速和简便的方法来设置一个REST的JSONAPI.
-   [go-relax](https://github.com/codehack/go-relax)-构建可修复API的可插入组件框架.
-   [go-rest](https://github.com/ungerik/go-rest)-小而邪恶的休息框架.
-   [goa](https://github.com/raphael/goa)-基于Ruby实践的微服务开发框架.
-   [Golax](https://github.com/fulldump/golax)一个非西纳特拉快速HTTP框架,支持谷歌自定义方法、深度拦截器、递归等等.
-   [Golf](https://github.com/dinever/golf)-高尔夫是一种快速、简单、轻量级的GO微网框架.它具有强大的特性,除了GO标准库之外没有依赖关系.
-   [Gondola](https://github.com/rainycape/gondola)-用于更快地编写网站的Web框架.
-   [gongular](https://github.com/mustafaakin/gongular)-带有输入映射/验证和(DI)依赖注入的快速GO Web框架.
-   [Macaron](https://github.com/go-macaron/macaron)- MARARON是一个高生产性和模块化设计的Web框架.
-   [mango](https://github.com/paulbellamy/mango)芒果是一个模块化的Web应用框架,由Grand和PEP333驱动.
-   [Microservice](https://github.com/claygod/microservice)-创建微服务的框架,写在Golang.
-   [neo](https://github.com/ivpusic/neo)-尼奥是极小且快速的WEB框架,具有极其简单的API.
-   [Resoursea](https://github.com/resoursea/api)REST框架,用于快速编写基于资源的服务.
-   [REST Layer](http://rest-layer.io)-在数据库之上构建RES/GAPQL API的框架,主要通过代码进行配置.
-   [Revel](https://github.com/revel/revel)- GO语言的高生产率Web框架.
-   [rex](https://github.com/goanywhere/rex)-雷克斯是一个基于大猩猩/MUX的模块化开发的图书馆,完全兼容`net/http`.
-   [sawsij](https://github.com/jaybill/sawsij)-轻量级的开源Web框架,用于构建高性能、数据驱动的Web应用程序.
-   [tango](https://github.com/lunny/tango)GO的微可插入Web框架.
-   [tigertonic](https://github.com/rcrowley/go-tigertonic)GO框架,用于构建由DoopWistor启发的JSON Web服务.
-   [traffic](https://github.com/pilu/traffic)-西纳特拉启发ReGEX/MuleMulx和Web框架的GO.
-   [utron](https://github.com/gernest/utron)-轻量级MVC框架的GO(GORANG).
-   [violetear](https://github.com/nbari/violetear)去HTTP路由器.
-   [WebGo](https://github.com/bnkamalesh/webgo)-构建Web应用程序的微框架;处理程序链接、中间件和上下文注入.使用符合标准库的HTTP处理程序(即http.Hall).
-   [YARF](https://github.com/yarf-framework/yarf)-快速微框架,旨在以快速和简单的方式构建REST API和Web服务.
-   [Zerver](https://github.com/cosiner/zerver)- ZEVER是一个表达性、模块化、功能完备的REST框架.

### 中间件

#### 实际中间件

-   [client-timing](https://github.com/posener/client-timing)-服务器定时报头的HTTP客户端.
-   [CORS](https://github.com/rs/cors)-很容易为您的API添加CORS功能.
-   [formjson](https://github.com/rs/formjson)-透明地处理JSON输入作为标准窗体POST.
-   [go-server-timing](https://github.com/mitchellh/go-server-timing)-添加/解析服务器定时报头.
-   [Limiter](https://github.com/ulule/limiter)GO的简单简单速率限制中间件.
-   [ln-paywall](https://github.com/philippgille/ln-paywall)利用闪电网络(Bitcoin)在每个请求基础上对API进行货币化的GO中间件
-   [Tollbooth](https://github.com/didip/tollbooth)速率限制HTTP请求处理程序.
-   [XFF](https://github.com/sebest/xff)-手柄`X-Forwarded-For`标题和朋友.

#### 创建HTTP中间件的库

-   [alice](https://github.com/justinas/alice)无痛中间件链接GO.
-   [catena](https://github.com/codemodus/catena)- http.Halder-Wrper-CelpEngress(与"链"相同的API).
-   [chain](https://github.com/codemodus/chain)-汉德勒包装与范围数据链接(基于网络/上下文的"中间件").
-   [go-wrap](https://github.com/go-on/wrap)NET/HTTP的中小型封装.
-   [gores](https://github.com/alioygur/gores)-去处理HTML、JSON、XML等响应的软件包.对于REST API是有用的.
-   [interpose](https://github.com/carbocation/interpose)-极简网/HTTP中间件.
-   [muxchain](https://github.com/stephens2424/muxchain)轻量级的NET/HTTP中间件.
-   [negroni](https://github.com/urfave/negroni)Golang的惯用HTTP中间件.
-   [render](https://github.com/unrolled/render)-GO程序包,用于容易地呈现JSON、XML和HTML模板响应.
-   [renderer](https://github.com/thedevsaddam/renderer)-简单、轻量级和更快的响应(JSON、JSONP、XML、YAML、HTML、文件)GO渲染包.
-   [rye](https://github.com/InVisionApp/rye)-微GO中间件库(带有罐头中间件),支持JWT、CORS、STATSD和GO 1.7上下文.
-   [stats](https://github.com/thoas/stats)去存储关于Web应用程序的各种信息的中间件.
-   [Volatile](https://github.com/volatile/core)-极简中间件堆栈促进灵活性,良好的实践和干净的代码.

### 路由器

-   [alien](https://github.com/gernest/alien)-轻量级快速HTTP路由器从外层空间.
-   [Bone](https://github.com/go-zoo/bone)-闪电快速HTTP多路复用器.
-   [Bxog](https://github.com/claygod/Bxog)-简单快捷的HTTP路由器.它有不同难度、长度和嵌套的路线.他知道如何从接收到的参数创建URL.
-   [chi](https://github.com/go-chi/chi)-基于网络/上下文的小型、快速和有表现力的HTTP路由器.
-   [fasthttprouter](https://github.com/buaazp/fasthttprouter)-高性能路由器分叉`httprouter`. 第一路由器适合`fasthttp`.
-   [FastRouter](https://github.com/razonyang/fastrouter)一个快速、灵活的HTTP路由器写在GO中.
-   [gocraft/web](https://github.com/gocraft/web)MUX和中间件包在GO中.
-   [Goji](https://github.com/goji/goji)- GoGi是一种支持支持的简约灵活的HTTP请求多路复用器.`net/context`.
-   [GoRouter](https://github.com/vardius/gorouter)-GoRouter是一个服务器/API微框架,HTTP请求路由器,多路复用器,多路复用器,为请求路由器提供中间件支持`net/context`.
-   [gowww/router](https://github.com/gowww/router)-闪电快速HTTP路由器完全兼容NET/HTTP.Helpter接口.
-   [httprouter](https://github.com/julienschmidt/httprouter)-高性能路由器.使用这个和标准的HTTP处理程序来形成一个非常高性能的Web框架.
-   [httptreemux](https://github.com/dimfeld/httptreemux)-高速,灵活的基于树的HTTP路由器的GO.来自HTTPROTEL的启示.
-   [lars](https://github.com/go-playground/lars)是一个轻量级的、快速的、可扩展的零分配HTTP路由器,用于创建可定制的框架.
-   [medeina](https://github.com/imdario/medeina)- Medeina是一个HTTP路由树,基于RoopRead,受RDA和古巴的启发.
-   [mux](https://github.com/gorilla/mux)-强大的URL路由器和调度器为戈朗.
-   [ozzo-routing](https://github.com/go-ozzo/ozzo-routing)-一种支持正则表达式路由匹配的非常快的GO(GALON)HTTP路由器.完全支持构建RESTORY API.
-   [pat](https://github.com/bmizerany/pat)-西纳特拉风格的MUXER为GO的网络/HTTP库,由作者西纳特拉.
-   [pure](https://github.com/go-playground/pure)是一个轻量级的HTTP路由器,它支持STD"NET/HTTP"实现.
-   [Siesta](https://github.com/VividCortex/siesta)-编写中间件和处理程序的可组合框架.
-   [vestigo](https://github.com/husobee/vestigo)-性能,独立,HTTP兼容的URL路由器的GO Web应用程序.
-   [xmux](https://github.com/rs/xmux)-基于高性能的多路复用器`httprouter`具有`net/context`支持.
-   [xujiajun/gorouter](https://github.com/xujiajun/gorouter)-一个简单快捷的HTTP路由器.
-   [zeus](https://github.com/daryl/zeus)-非常简单快捷的HTTP路由器.

## Windows

-   [d3d9](https://github.com/gonutz/d3d9)-为DUNT3D9进行绑定.
-   [go-ole](https://github.com/go-ole/go-ole)为Gangang.Win32 OLE实现.

## XML

*用于操纵XML的库和工具.*

-   [XML-Comp](https://github.com/xml-comp/xml-comp)-简单的命令行XML比较器,它生成文件夹、文件和标签的差异.
-   [xmlwriter](https://github.com/shabbyrobe/xmlwriter)-基于LIXXML2的XMLMeX模块的过程XML生成API.
-   [xpath](https://github.com/antchfx/xpath)XPath包为GO.
-   [xquery](https://github.com/antchfx/xquery)XQuery允许您使用XPath表达式从HTML/XML文档中提取数据.

# 工具

*Go软件和插件.*

## 代码分析

-   [apicompat](https://github.com/bradleyfalzon/apicompat)-检查对向后项目不兼容更改的GO项目的最近更改.
-   [dupl](https://github.com/mibk/dupl)-用于代码克隆检测的工具.
-   [errcheck](https://github.com/kisielk/errcheck)Errcheck是一个程序,用于检查GO程序中的未检查错误.
-   [gcvis](https://github.com/davecheney/gcvis)-可视化GO程序实时跟踪GC数据.
-   [Go Metalinter](https://github.com/alecthomas/gometalinter)- Metalinter是自动应用所有静态分析工具并以标准化形式报告其输出的工具.
-   [go-checkstyle](https://github.com/qiniu/checkstyle)CHECKTYPE是一种样式检查工具,如Java检查样式.这个工具是由Java CalpType,GoLITE启发的.该样式引用GO代码审查注释中的某些点.
-   [go-cleanarch](https://github.com/roblaszczak/go-cleanarch)-go-cleanarch是为了验证Clean Architecture规则而创建的,比如依赖规则和Go项目中的包之间的交互.
-   [go-critic](https://github.com/go-critic/go-critic)-源代码链接器,它带来当前没有在其他LTENS中实现的检查.
-   [go-outdated](https://github.com/firstrow/go-outdated)控制台应用程序显示过时的包.
-   [goast-viewer](https://github.com/yuroyoro/goast-viewer)-基于Web的Galang-AST可视化程序.
-   [GoCover.io](http://gocover.io/)- GoCover.io提供任何Galang-Cube作为服务的代码覆盖率.
-   [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports)工具自动修复(添加,删除)你的GO导入.
-   [GolangCI](https://golangci.com/)- GolangCI是Gigthub拉请求的自动Galang-Code审阅服务.服务是开放源代码,它对于开源项目是免费的.
-   [GoLint](https://github.com/golang/lint)Golint是一个GO源代码.
-   [Golint online](http://go-lint.appspot.com/)在GITHUB、BITKUP和谷歌项目托管上使用GORITE包进行网上下载.
-   [goreturns](https://sourcegraph.com/github.com/sqs/goreturns)-添加零值返回语句以匹配FUNC返回类型.
-   [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple)GoSimple是一个专门用于简化代码的GO源代码的链接器.
-   [gostatus](https://github.com/shurcooL/gostatus)命令行工具,显示包含GO包的存储库的状态.
-   [interfacer](https://github.com/mvdan/interfacer)-暗示接口类型的链接器.
-   [lint](https://github.com/surullabs/lint)-运行LTENS作为GO测试的一部分.
-   [php-parser](https://github.com/z7zmey/php-parser)一个PHP的解析器,用GO编写的.
-   [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck)静态检查是`go vet`在类固醇上,应用一吨静态分析检查,您可能会从像ReHARPER这样的工具使用C.
-   [tarp](https://github.com/verygoodsoftwarenotvirus/tarp)TARP在GO源代码中没有直接单元测试的功能和方法.
-   [unconvert](https://github.com/mdempsky/unconvert)-从GO源中删除不必要的类型转换.
-   [unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused)未使用的检查为未使用的常量、变量、函数和类型提供代码.
-   [validate](https://github.com/mccoyst/validate)-用标记自动验证结构域.

## 编辑器插件

-   [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go)去JETBEED IDE插件.
-   [go-language-server](https://github.com/theia-ide/go-language-server)一个包装器,将VSCODE GO扩展变成支持语言服务器协议的语言服务器.
-   [go-mode](https://github.com/dominikh/go-mode.el)GNU/EMACS模式.
-   [go-plus](https://github.com/joefitzgerald/go-plus)-Go(GORANG)包,用于添加自动完成、格式化、语法检查、Linting和审核.
-   [Goclipse](https://github.com/GoClipse/goclipse)Eclipse插件.
-   [gocode](https://github.com/nsf/gocode)-自动完成守护进程,用于GO程序设计语言.
-   [GoSublime](https://github.com/DisposaBoy/GoSublime)-用于文本编辑器SualimeTeXT 3的Golang插件集合,提供代码完成和其他IDE类特性.
-   [gounit-vim](https://github.com/hexdigest/gounit-vim)VIM插件,用于根据函数或方法的签名生成GO测试.
-   [theia-go-extension](https://github.com/theia-ide/theia-go-extension)-为TIEA IDE提供语言支持.
-   [velour](https://github.com/velour/velour)为ACME编辑器的IRC客户端.
-   [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go)VIM插件,以突出显示保存时的语法错误.
-   [vim-go](https://github.com/fatih/vim-go)为VIM开发插件.
-   [vscode-go](https://github.com/Microsoft/vscode-go)-扩展VisualStudio代码(VS代码),为GO语言提供支持.
-   [Watch](https://github.com/eaburns/Watch)在文件更改中运行AcMe Win命令.

## GO生成工具

-   [generic](https://github.com/usk81/generic)-灵活的数据类型为GO.
-   [genny](https://github.com/cheekybits/genny)-优雅的仿制品.
-   [gocontracts](https://github.com/Parquery/gocontracts)-通过合同将设计与代码同步.
-   [gonerics](http://github.com/bouk/gonerics)GO中的成语.
-   [gotests](https://github.com/cweill/gotests)-从源代码生成GO测试.
-   [gounit](https://github.com/hexdigest/gounit)-使用自己的模板生成GO测试.
-   [re2dfa](https://github.com/opennota/re2dfa)-将正则表达式转换为有限状态机并输出GO源代码.

## Go工具

-   [colorgo](https://github.com/songgao/colorgo)-包装器`go`着色命令`go build`输出.
-   [depth](https://github.com/KyleBanks/depth)通过分析导入来可视化任何包的依赖树.
-   [gb](https://getgb.io/)-一种易于使用的基于项目的构建工具,用于GO程序设计语言.
-   [generator-go-lang](https://github.com/axelspringer/generator-go-lang)-A[Yeoman](http://yeoman.io)生成器启动新的GO项目.
-   [go-callvis](https://github.com/TrueFurby/go-callvis)用点格式可视化你的GO程序的调用图.
-   [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete)为GO和WGO完成BASH.
-   [go-swagger](https://github.com/go-swagger/go-swagger)-炫耀2实现的GO.Savigle是一个简单但功能强大的REST API.
-   [OctoLinker](https://github.com/OctoLinker/browser-extension)-使用GOTHUB的OctoLink浏览器扩展,有效地浏览GO文件.
-   [richgo](https://github.com/kyoh86/richgo)-丰富`go test`具有文本装饰的输出.
-   [rts](https://github.com/galeone/rts)RTS:对结构的响应.从服务器响应生成GO结构.

## 软件包

*软件写在GO中.*

### DevOps工具

-   [aptly](https://github.com/smira/aptly)适当地是Debian存储库管理工具.
-   [aurora](https://github.com/xuri/aurora)跨平台的基于Web的BeaStAcDeD队列服务器控制台.
-   [awsenv](https://github.com/soniah/awsenv)-为Apple加载Amazon(AWS)环境变量的小二进制文件.
-   [Banshee](https://github.com/eleme/banshee)周期性度量的异常检测系统.
-   [Blast](https://github.com/dave/blast)- API加载测试和批处理作业的简单工具.
-   [bombardier](https://github.com/codesenberg/bombardier)-快速跨平台HTTP基准测试工具.
-   [bosun](https://github.com/bosun-monitor/bosun)-时间序列警报框架.
-   [DepCharge](https://github.com/centerorbit/depcharge)-帮助跨大型项目中的许多依赖项协调命令的执行.
-   [dogo](https://github.com/liudng/dogo)-监视源文件中的更改,并自动编译和运行(重新启动).
-   [drone-jenkins](https://github.com/appleboy/drone-jenkins)-使用二进制、码头工人或无人机CI触发下游詹金斯作业.
-   [drone-scp](https://github.com/appleboy/drone-scp)-通过SSH使用二进制、DOCKER或无人机CI复制文件和工件.
-   [Dropship](https://github.com/chrismckenzie/dropship)-通过CDN部署代码的工具.
-   [easyssh-proxy](https://github.com/appleboy/easyssh-proxy)- Golang包,通过SSH和SCP下载方便远程执行`ProxyCommand`.
-   [fac](https://github.com/mkchoi212/fac)命令行用户界面修复Git合并冲突
-   [gaia](https://github.com/gaia-pipeline/gaia)-用任何编程语言构建强大的流水线.
-   [Gitea](https://github.com/go-gitea/gitea)-叉叉,完全由社区驱动.
-   [Go Metrics](https://github.com/rcrowley/go-metrics)去考达海尔度量库的端口:<https://github.com/codahale/metrics>.
-   [go-furnace](https://github.com/go-furnace/go-furnace)主机解决方案写在GO.在AWS、GCP或DigialOpWord上轻松部署应用程序.
-   [go-selfupdate](https://github.com/sanbornm/go-selfupdate)-启用您的GO应用程序进行自更新.
-   [gobrew](https://github.com/cryptojuice/gobrew)- GuBrw让您轻松切换多个版本的GO.
-   [godbg](https://github.com/sirnewton01/godbg)-基于Web的GDB前端应用程序.
-   [Gogs](https://gogs.io/)- GO编程语言中的自托管Git服务.
-   [gonative](https://github.com/inconshreveable/gonative)-创建Go构建的工具,可以跨编译到所有平台,同时仍然使用支持Cgo的stdlib包版本.
-   [govvv](https://github.com/ahmetalpbalkan/govvv)-"构建"包装,以方便地将版本信息添加到GO二进制文件中.
-   [gox](https://github.com/mitchellh/gox)-死简单,没有虚饰交叉编译工具.
-   [goxc](https://github.com/laher/goxc)-为GO构建工具,重点是交叉编译和打包.
-   [grapes](https://github.com/yaronsumel/grapes)-轻量级工具,用于在SSH上轻松分配命令.
-   [GVM](https://github.com/moovweb/gvm)GVM提供了一个管理GO版本的接口.
-   [Hey](https://github.com/rakyll/hey)-Hi是一个向Web应用程序发送一些负载的小程序.
-   [kala](https://github.com/ajvb/kala)-简单化、现代化和性能化的作业调度程序.
-   [kcli](https://github.com/cswank/kcli)-命令行工具,用于检查卡夫卡主题/分区/消息.
-   [kubernetes](https://github.com/kubernetes/kubernetes)-来自谷歌的容器集群管理器.
-   [lstags](https://github.com/ivanilves/lstags)-工具和API来同步跨不同注册表的码头工人图像.
-   [lwc](https://github.com/timdp/lwc)- UNIX WC命令的实时更新版本.
-   [manssh](https://github.com/xwjdsh/manssh)-MANSSH是一个命令行工具,用于管理您的SSH别名配置.
-   [Moby](https://github.com/moby/moby)-基于集装箱系统的集装箱生态系统合作项目.
-   [Mora](https://github.com/emicklei/mora)REST服务器用于访问MUGODB文档和元数据.
-   [ostent](https://github.com/ostrost/ostent)-收集和显示系统度量,并可选地中继到石墨和/或涌入数据库.
-   [Packer](https://github.com/mitchellh/packer)PACKER是用于从单一源配置创建多个平台的相同机器映像的工具.
-   [Pewpew](https://github.com/bengadbois/pewpew)-灵活的HTTP命令行应力测试仪.
-   [Rodent](https://github.com/alouche/rodent)-啮齿动物帮助您管理GO版本、项目和跟踪依赖项.
-   [s3gof3r](https://github.com/rlmcpherson/s3gof3r)-小型实用程序/库,用于高速传输大型对象到Amazon S3.
-   [Scaleway-cli](https://github.com/scaleway/scaleway-cli)-从命令行管理BeReMever服务器(与Docker一样容易).
-   [sg](https://github.com/ChristopherRabotin/sg)-对一组HTTP端点(如ab)进行基准测试,有可能根据先前的响应在每次调用之间使用响应代码和数据来应对特定的服务器压力.
-   [skm](https://github.com/TimothyYe/skm)SKM是一个简单而强大的SSH密钥管理器,它可以帮助您轻松地管理多个SSH密钥.
-   [StatusOK](https://github.com/sanathp/statusok)-监视您的网站和RESTAPI.在服务器停机或响应时间超过预期时,通过Slack、电子邮件获得通知.
-   [traefik](https://github.com/containous/traefik)-反向代理和负载平衡器,支持多个后端.
-   [Vegeta](https://github.com/tsenart/vegeta)- HTTP负载测试工具和库.超过9000!
-   [webhook](https://github.com/adnanh/webhook)-允许用户创建在服务器上执行命令的HTTP端点(钩子)的工具.
-   [Wide](https://wide.b3log.org/login)基于Gide的团队的基于Web的IDE.
-   [winrm-cli](https://github.com/masterzen/winrm-cli)CLI工具远程执行Windows机器上的命令.

### 其他软件

-   [borg](https://github.com/crufter/borg)-基于BASH片段的基于终端的搜索引擎.
-   [boxed](https://github.com/tejo/boxed)基于Dropbox的博客引擎.
-   [Cherry](https://github.com/rafael-santiago/cherry)-微型网络聊天服务器进入.
-   [Circuit](https://github.com/gocircuit/circuit)- Cir.是可编程平台即服务(PaaS)和/或基础设施即服务(IaaS),用于管理、发现、同步和编排包括云应用程序的服务和主机.
-   [Comcast](https://github.com/tylertreat/Comcast)-模拟坏的网络连接.
-   [confd](https://github.com/kelseyhightower/confd)-使用ETCD或领事的模板和数据管理本地应用程序配置文件.
-   [DDNS](https://github.com/skibish/ddns)个人DDNS客户端,以数字海洋网络DNS作为后端.
-   [Docker](http://www.docker.com/)-开放平台,用于开发和系统管理员的分布式应用程序.
-   [Documize](https://github.com/documize/community)现代Wiki软件,集成了SaaS工具的数据.
-   [Duplicacy](https://github.com/gilbertchen/duplicacy)一种基于无锁去重思想的跨平台网络和云备份工具.
-   [Go Package Store](https://github.com/shurcooL/Go-Package-Store)-应用程序显示GOPATH中的GO包的更新.
-   [GoBoy](https://github.com/Humpheh/goboy)任天堂游戏男童彩色仿真器编写的GO.
-   [gocc](https://github.com/goccmack/gocc)- Gocc是GO编写的GO编译器工具包.
-   [GoDNS](https://github.com/timothyye/godns)一个动态DNS客户端工具,支持DNSPOD和H.NET,写在GO中.
-   [GoDocTooltip](https://github.com/diankong/GoDocTooltip)-Chrome扩展为GO DOC站点,它将函数描述显示为函数列表中的工具提示.
-   [GoLand](https://jetbrains.com/go)-全功能跨平台Goide IDE.
-   [Gor](https://github.com/buger/gor)- HTTP流量复制工具,用于实时回放从生产到阶段/DEV环境的流量.
-   [hugo](http://gohugo.io/)-快速而现代的静态网站引擎.
-   [ide](https://github.com/thestrukture/ide)浏览器可访问IDE.与GO一起设计.
-   [ipe](https://github.com/dimiro1/ipe)-开源Pover服务器实现,与GO中的PuxS客户端库兼容.
-   [JayDiff](https://github.com/yazgazan/jaydiff)- JSON差异实用工具写在GO.
-   [joincap](https://github.com/assafmo/joincap)命令行实用程序,用于将多个pCAP文件合并在一起.
-   [Juju](https://jujucharms.com/)-云不可知服务部署和编排-支持EC2,Azure,OpenStack,MAAS等.
-   [Leaps](https://github.com/jeffail/leaps)-使用操作变换的配对编程服务.
-   [lgo](https://github.com/yunabe/lgo)与Jupyter互动的GO编程.它支持代码完成、代码检查和100% GO兼容性.
-   [limetext](http://limetext.org/)Lime Text是一个功能强大、优雅的文本编辑器,主要由Go开发,旨在成为"崇高文本"的自由、开源软件的继承者.
-   [LiteIDE](https://github.com/visualfc/liteide)- LiteIDE是一个简单的、开源的跨平台Goide IDE.
-   [mockingjay](https://github.com/quii/mockingjay-server)-从一个配置文件中伪造HTTP服务器和用户驱动的合同.您还可以使服务器随机错误行为,以帮助进行更逼真的性能测试.
-   [myLG](https://github.com/mehrdadrad/mylg)-命令行网络诊断工具写在GO.
-   [naclpipe](https://github.com/unix4fun/naclpipe)-简单的基于NaCl EC25519的加密管工具写在GO中.
-   [nes](https://github.com/fogleman/nes)-任天堂娱乐系统(NES)仿真器编写的GO.
-   [orange-cat](https://github.com/noraesae/orange-cat)用GO写下来的.
-   [Orbit](https://github.com/gulien/orbit)-一个简单的工具,用于运行命令和从模板生成文件.
-   [peg](https://github.com/pointlander/peg)PEG,解析表达式语法,是PIDRAT解析器生成器的一个实现.
-   [Pipe](https://github.com/b3log/pipe)-一个小而漂亮的博客平台.
-   [Postman](https://github.com/zachlatta/postman)命令行实用程序批量发送电子邮件.
-   [restic](https://github.com/restic/restic)-去重备份程序.
-   [rkt](https://github.com/coreos/rkt)与init系统集成的App Cube运行时与Docker等其他容器格式兼容,并支持像KVM这样的替代执行引擎.
-   [Seaweed File System](https://github.com/chrislusf/seaweedfs)-具有O(1)磁盘查找的快速、简单和可扩展的分布式文件系统.
-   [shell2http](https://github.com/msoap/shell2http)-通过HTTP服务器执行shell命令(用于原型或远程控制).
-   [snap](https://github.com/intelsdi-x/snap)-强大的遥测框架.
-   [Snitch](https://github.com/lucasgomide/snitch)-当有人通过TSUU部署任何应用程序时,通知团队和许多工具的简单方法.
-   [Stack Up](https://github.com/pressly/sup)堆叠起来,一个超级简单的部署工具——Unix——把它想象成一个服务器网络的"make".
-   [syncthing](https://syncthing.net/)-开放、分散的文件同步工具和协议.
-   [Tenyks](https://github.com/kyleterry/tenyks)面向服务的IRC BOT,使用ReISIS和JSON进行消息传递.
-   [term-quiz](https://github.com/crazcalm/term-quiz)-为你的终端测验.
-   [toto](https://github.com/blogcin/ToTo)-用GO语言编写的简单代理服务器,可以与浏览器一起使用.
-   [toxiproxy](https://github.com/shopify/toxiproxy)代理模拟自动化测试的网络和系统条件.
-   [tsuru](https://tsuru.io/)-可扩展和开源平台作为服务软件.
-   [vFlow](https://github.com/VerizonDigital/vflow)-高性能、可扩展和可靠的IPFIX、SFlow和NetFlow收集器.
-   [websysd](https://github.com/ian-kent/websysd)-基于Web的过程管理器(如马拉松或新贵).
-   [wellington](https://github.com/wellington/wellington)SASS项目管理工具,用SpRITE函数(如指南针)扩展语言.

# 资源

*在哪里发现新的GO图书馆.*

## 基准点

-   [autobench](https://github.com/davecheney/autobench)框架来比较不同GO版本之间的性能.
-   [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app)-强大的HTTP基准工具,与B,WRK,围攻工具混合.收集基准和比较结果的统计和各种参数.
-   [go-benchmarks](https://github.com/tylertreat/go-benchmarks)-很少有其他的GO微基准.将一些语言特征与替代方法进行比较.
-   [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark)-去HTTP请求路由器基准和比较.
-   [go-type-assertion-benchmark](https://github.com/hgfischer/go-type-assertion-benchmark)-对在GO中进行类型断言的两种方式进行天真的性能测试.
-   [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark)-去Web框架基准.
-   [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks)GO序列化方法的基准.
-   [gocostmodel](https://github.com/PuerkitoBio/gocostmodel)- GO语言常用的基本操作的基准.
-   [golang-micro-benchmarks](https://github.com/amscanne/golang-micro-benchmarks)微微的GO微基准.其目的是将一些语言特征与其他语言进行比较.
-   [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark)-收集流行的GO数据库/ SQL实用工具的基准.
-   [gospeed](https://github.com/feyeleanor/GoSpeed)去微基准来计算语言结构的速度.
-   [kvbench](https://github.com/jimrobinson/kvbench)-关键字/值数据库基准.
-   [skynet](https://github.com/atemerev/skynet)SkyNET1M线程微基准.
-   [speedtest-resize](https://github.com/fawick/speedtest-resize)比较GO语言的各种图像大小调整算法.

## 会议

-   [Capital Go](http://www.capitalgolang.com)-华盛顿、D.C.、美国
-   [dotGo](http://www.dotgo.eu)-巴黎,法国
-   [GoCon](http://gocon.connpass.com/)-东京,日本
-   [GoDays](https://www.godays.io/)-柏林,德国
-   [GoLab](http://golab.io/)-佛罗伦萨,意大利
-   [GolangUK](http://golanguk.com/)-伦敦,英国
-   [GopherChina](http://gopherchina.org)-上海,中国
-   [GopherCon](http://www.gophercon.com/)-丹佛,美国
-   [GopherCon Brazil](https://gopherconbr.org)-弗洛里安·波利斯
-   [GopherCon Europe](https://gophercon.is/)-雷克雅未克,冰岛
-   [GopherCon India](https://www.gophercon.in/)-浦那,印度
-   [GopherCon Russia](https://www.gophercon-russia.ru)-莫斯科,俄罗斯
-   [GopherCon Singapore](https://gophercon.sg)新加坡枫叶商务城
-   [GothamGo](http://gothamgo.com/)-纽约,美国
-   [GoWayFest](https://goway.io/)-明斯克,白俄罗斯

## 电子书

-   [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
-   [An Introduction to Programming in Go](http://www.golang-book.com/)
-   [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
-   [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details)
-   [Go 101](https://go101.org)一本关于GO语法/语义和各种细节的书
-   [Go Bootcamp](http://golangbootcamp.com)
-   [GoBooks](https://github.com/dariubs/GoBooks)一份精选的GO书籍.
-   [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
-   [Network Programming With Go](https://jan.newmarch.name/go/)
-   [The Go Programming Language](http://www.gopl.io/)
-   [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/)
-   [Writing A Compiler In Go](https://compilerbook.com)
-   [Writing An Interpreter In Go](https://interpreterbook.com)

## Gophers地鼠

-   [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector)Goector矢量数据[A.SVG,]
-   [gopher-logos](https://github.com/GolangUA/gopher-logos)可爱的地鼠标志
-   [gopher-stickers](https://github.com/tenntenn/gopher-stickers)
-   [gopher-vector](https://github.com/golang-samples/gopher-vector)
-   [gophericons](https://github.com/shalakhin/gophericons)
-   [gopherize.me](https://github.com/matryer/gopherize.me)把自己打扮得漂漂亮亮
-   [gophers](https://github.com/ashleymcnamara/gophers)- Ashley McNamara的吉普赛作品
-   [gophers](https://github.com/egonelbre/gophers)-自由地鼠
-   [gophers](https://github.com/rogeralsing/gophers)随机GopHER图形
-   [gophers](https://github.com/sillecelik/go-gopher)Gooper-Aigururmii玩具图案

## 见面会

-   [Go Language NYC](https://www.meetup.com/golanguagenewyork/)
-   [Go London User Group](https://www.meetup.com/Go-London-User-Group/)
-   [Go Toronto](https://www.meetup.com/go-toronto/)
-   [Go User Group Atlanta](https://www.meetup.com/Go-Users-Group-Atlanta/)
-   [GoBridge, San Francisco, CA](https://www.meetup.com/gobridge/)
-   [GoJakarta](https://www.meetup.com/GoJakarta/)
-   [Golang Amsterdam](https://www.meetup.com/golang-amsterdam/)
-   [Golang Argentina](https://www.meetup.com/Golang-Argentina/)
-   [Golang Bangalore](https://www.meetup.com/Golang-Bangalore/)
-   [Golang Belo Horizonte - Brazil](https://www.meetup.com/go-belo-horizonte/)
-   [Golang Boston](https://www.meetup.com/bostongo/)
-   [Golang Bulgaria](https://www.meetup.com/Golang-Bulgaria/)
-   [Golang Cardiff, UK](https://www.meetup.com/Cardiff-Go-Meetup/)
-   [Golang Copenhagen](https://www.meetup.com/Go-Cph/)
-   [Golang DC, Arlington, VA](https://www.meetup.com/Golang-DC/)
-   [Golang Dorset, UK](https://www.meetup.com/golang-dorset/)
-   [Golang Hamburg - Germany](https://www.meetup.com/Go-User-Group-Hamburg/)
-   [Golang Israel](https://www.meetup.com/Go-Israel/)
-   [Golang Joinville - Brazil](https://www.meetup.com/Joinville-Go-Meetup/)
-   [Golang Lima - Peru](https://www.meetup.com/Golang-Peru/)
-   [Golang Lyon](https://www.meetup.com/Golang-Lyon/)
-   [Golang Melbourne](https://www.meetup.com/golang-mel/)
-   [Golang Mountain View](https://www.meetup.com/Golang-Mountain-View/)
-   [Golang New York](https://www.meetup.com/nycgolang/)
-   [Golang Paris](https://www.meetup.com/Golang-Paris/)
-   [Golang Pune](https://www.meetup.com/Golang-Pune/)
-   [Golang Singapore](https://www.meetup.com/golangsg/)
-   [Golang Stockholm](https://www.meetup.com/Go-Stockholm/)
-   [Golang Sydney, AU](https://www.meetup.com/golang-syd/)
-   [Golang São Paulo - Brazil](https://www.meetup.com/golangbr/)
-   [Golang Vancouver, BC](https://www.meetup.com/golangvan/)
-   [Golang Москва](https://www.meetup.com/Golang-Moscow/)
-   [Golang Питер](https://www.meetup.com/Golang-Peter/)
-   [Istanbul Golang](https://www.meetup.com/Istanbul-Golang/)
-   [Seattle Go Programmers](https://www.meetup.com/golang/)
-   [Ukrainian Golang User Groups](https://www.meetup.com/uagolang/)
-   [Utah Go User Group](https://www.meetup.com/utahgophers/)
-   [Women Who Go - San Francisco, CA](https://www.meetup.com/Women-Who-Go/)

*添加你的城市/国家的组(发送)**公共关系**)*

## 推特

-   [@golang](https://twitter.com/golang)
-   [@golang_news](https://twitter.com/golang_news)
-   [@golangch](https://twitter.com/golangch)
-   [@golangflow](https://twitter.com/golangflow)
-   [@golangweekly](https://twitter.com/golangweekly)

## 网站

-   [Awesome Go @LibHunt](https://go.libhunt.com)你的工具箱.
-   [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job)精选的远程工作列表.他们中的很多人都在寻找GO黑客.
-   [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness)-列出其他令人惊叹的令人惊叹的列表.
-   [CodinGame](https://www.codingame.com/)-通过使用小游戏作为实际例子来解决交互任务.
-   [Go Blog](http://blog.golang.org)官方博客.
-   [Go Challenge](http://golang-challenge.org/)学习解决问题,从GO专家那里得到反馈.
-   [Go Forum](https://forum.golangbridge.org)论坛讨论一下.
-   [Go In 5 Minutes](https://www.goin5minutes.com/)5分钟的录音机专注于完成一件事.
-   [Go Projects](https://github.com/golang/go/wiki/Projects)-Go社区维基项目列表.
-   [Go Report Card](https://goreportcard.com)一张你的旅行包的成绩单.
-   [gocryforhelp](https://github.com/ninedraft/gocryforhelp)-收集需要帮助的GO项目.开始开源的好地方.
-   [godoc.org](https://godoc.org/)-开源软件包的文档.
-   [Golang Flow](https://golangflow.io)-更新,新闻,软件包等等.
-   [Golang News](https://golangnews.com)-关于GO编程的链接和新闻.
-   [golang-graphics](https://github.com/mholt/golang-graphics)收集GO图像、图形和艺术.
-   [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts)转到邮件列表.
-   [Google Plus Community](https://plus.google.com/communities/114112804251407510571)谷歌+ GRANG社区.
-   [Gopher Community Chat](https://invite.slack.golangbridge.org)-加入我们的新懒虫社区[Understand how it came](https://blog.gopheracademy.com/gophers-slack-community/))
-   [gowalker.org](https://gowalker.org)-去项目API文档.
-   [justforfunc](https://www.youtube.com/c/justforfunc)YouTube频道致力于编程语言技巧和技巧,由Francesc Campoy主持[@francesc](https://twitter.com/francesc).
-   [r/Golang](https://www.reddit.com/r/golang)-关于Go的消息.
-   [Trending Go repositories on GitHub today](https://github.com/trending?l=go)-找到新的GO图书馆的好地方.

### 教程

-   [50 Shades of Go](http://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/)陷阱,陷阱,以及新哥兰德夫的常见错误.
-   [A Tour of Go](http://tour.golang.org/)互动之旅.
-   [Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang)Golang电子书介绍如何用Galang-web构建一个Web应用程序.
-   [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin)-熟悉GIN并了解它能帮助你减少样板代码并建立一个请求处理管道.
-   [Games With Go](http://gameswithgo.org/)一个视频系列教学编程及游戏开发.
-   [Go By Example](https://gobyexample.com/)动手介绍使用注释的示例程序.
-   [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet)-GO的参考卡.
-   [Go database/sql tutorial](http://go-database-sql.org/)介绍数据库/SQL.
-   [Golangbot](https://golangbot.com/learn-golang-series/)在GO中开始编程的教程.
-   [Hackr.io](https://hackr.io/tutorials/learn-golang)学习GOLAN程序设计社区提交的最佳在线Gangon教程.
-   [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go)-开始使用GoDOWER——一个行为驱动的开发框架,用于构建和测试GO应用程序.
-   [Learn Go with TDD](https://github.com/quii/learn-go-with-tests)学习测试驱动开发.
-   [package main](https://www.youtube.com/packagemain)- YouTube有关GO编程的频道.
-   [Working with Go](https://github.com/mkaz/working-with-go)-去体验有经验的程序员.
-   [Your basic Go](http://yourbasic.org/golang)-大量的教程和如何收集教程
