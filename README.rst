我的 open source todo list，希望不要變成 bucket list
=====================================================

pct.vim
-------

* 已經製作
  
  https://github.com/pct/pct.vim

* 用途

  pct 的 vim 環境

* todo 

  - 各套件相依性處理好
  - 去蕪存菁，有太多相似的套件必須移除


vimpyre
-------

* 已經製作

  https://github.com/pct/vimpyre

* 用途

  Vim scripts manager

* todo

  - 將 command args 改得跟 homebrew 一樣


4money
------

* 已經製作
  
  https://github.com/pct/4money

* 用途

  免費的報價單及客戶管理工具，希望公司剛起步，找不到好用的報價單系統時，可以嘗試

* todo

  - 更簡便安裝，或獨立成 app？
  - 成為線上報價系統？



4Press
------

* 尚未製作

* 用途

  | 其實就是 blog system, 但可以讓我用 rst 來寫作，目前比較接近而做得不錯
  | 的是 http://octopress.org ，但他是用 ruby + markdown, 我比較喜歡 
  | python + rst。

* 技術

  #. git
  #. rst
  #. python
  #. use github pages?

* todo

  尚未開始，要趕快寫


4portcheck?
-----------

* 已經製作，尚未公開

* 用途

  FreeBSD ports update scanner

* 想法

  | 我的目標是每天至少 send 一個 FreeBSD 的 pr, 先從 ports 開始。原本有
  | portscout + RSS 可以用，但是 portscout 的 RSS 已經斷炊好一陣子，我因此
  | 沒有 達到每天 send-pr 的目標；聽起來像藉口，但是我已經完成了部分東西，
  | 至少已經可以正確掃到 90% 以上的 ports 更新(去除還沒做的SF, GITGUB, 
  | GOOGLE_CODE 等對應)

* 技術

  #. python
  #. sqlite or BDB or just use python dump

* todo

  - 把 FreeBSD ports 自訂的 SF, GITHUB, GOOGLE_CODE 加上對應
  - 更正確檢查 ports source tarball 版本
  - 加上 rss 更新


4Slim
-----

* 用途

  PHP web framework using php 5.2 or 5.3 and provide scaffolding commands

* 技術

  #. Structure: slim framework http://www.slimframework.com/ for structure
  #. ORM: idiorm https://github.com/j4mie/idiorm for 
  #. Template: Haanga http://haanga.org/ or Twig http://twig.sensiolabs.org/


* todo

  - 趕快整理想法來作
  - scaffolding

4Webpy
------

* 用途

  Python web framework just like pylons but not pyramid, there sould not be any zope or plone **code** in it.

* 想法

  NOT yet :'(

  But, rails or not rails? that's the question.


* todo

  - just do it, but I need cases to use it, or just switch to rails?
