Text, Text, Text - The past, present and future of writing (and publishing). 


# Awesome .TXT / Text

A collection of awesome .TXT / Text  tools, formats, services, tips & tricks and more.

#### _Contributions welcome. Anything missing? Send in a pull request. Thanks._


## Formats

[**Journal.TXT**](https://journaltxt.github.io) - single-text file journals - the human multi-document format for writers

```
--- 
day:   Wed 19
---
Let's reinvent push-button publishing on the internets! 
Use a single-file for your journal / diary / blog. That's it.
---
day:   Thu 20
---
Crazy idea? Let's put up a website and a example blog auto-generated from journal.txt.
---
day:   Fri 21
---
Did you know? The single-file format works great for advent calendars 
or beer-of-the-day calendars.
```

[**jrnl**](https://jrnl.sh) - collect your thoughts and notes without leaving the command line

```
[2025 Sep 04 09:00] Called in sick.
Used the time to clean, and spent 4h on writing my book.

[2025 Sep 06 15:41] Had a wonderful day at the @beach with @Tom and @Anna.

[2025 Sep 07 03:28] I just met Steve Buscemi in a bar!
What a nice guy.
```

[**Todo.TXT**](http://todotxt.org) by Gina Trapani et al -- future-proof task tracking in a file you control; if you want to get it done, first write it down.

```
(A) Call Mom @Phone +Family
(A) Schedule annual checkup +Health
(B) Outline chapter 5 +Novel @Computer
(C) Add cover sheets @Office +TPSReports
Plan backyard herb garden @Home
Pick up milk @GroceryStore
Research self-publishing services +Novel @Computer
x Download Todo.txt mobile app @Phone
```

[**Calendar.txt**](https://terokarvinen.com/2021/calendar-txt/) - Versionable, supports all operating systems and easily syncs with Android mobile phone.

```
2021-02-15 w07  Architecture week
2021-02-15 w07 Mon  9-12 project groups. 17 jogging. 
2021-02-16 w07 Tue  9-11 John 12-16 architecture meeting
2021-02-17 w07 Wed  8-14 +lp. 14:15-16 +mp
2021-02-18 w07 Thu  write out architecture
2021-02-19 w07 Fri  12-13 board
2021-02-20 w07 Sat  
2021-02-21 w07 Sun  10 ski with N
2021-04  Grand rollout
2022  The year of foobar
```

[**Feed.TXT**](https://feedtxt.github.io) - free web feeds format in (plain) text w/ structured meta data

```
|>>>
 title:          My Example Feed
 home_page_url:  https://example.org/
 feed_url:       https://example.org/feed.txt
 </>
 id:  2
 url: https://example.org/second-item
 ---
 This is a second item.
 </>
 id:  1
 url: https://example.org/initial-post
 ---
 Hello, world!
<<<| 
```

[**Manuscripts**](http://manuscripts.github.io) - free book format - write books in (plain) text 

```
---
title:  Strange Case of Dr. Jekyll and Mr. Hyde
year:   1886
author:
  name: Robert Louis Stevenson
---

=Story of the Door=

Mr. Utterson the lawyer was a man of a rugged countenance, that was
never lighted by a smile; cold, scanty and embarrassed in
discourse; backward in sentiment; lean, long, dusty, dreary, and
yet somehow lovable. At friendly meetings, and when the wine was to
his taste, something eminently human beaconed from his eye;
something indeed which never found its way into his talk, but which
spoke not only in these silent symbols of the after-dinner face, but
more often and loudly in the acts of his life...
```

[**Bib.TXT**](http://bibtxt.github.io) - free bibliographies in text (unicode) format - BibTeX for the 21st century - books, articles, & more

```
[Fau86]
  author:    J.W. Goethe
  title:     Faust. Der Tragödie Erster Teil
  publisher: Reclam
  year:      1986
  address:   Stuttgart
```

[**Ledger**](http://plaintextaccounting.org/quickref) / [**hledger**](https://hledger.org) - double-entry bookkeeping / accounting in (plain) text; follow your money

```
2016/1/1 set opening balance
   assets:checking       $500.00
   equity:opening balances

2016/1/5 farmer's market
   expenses:groceries     $50.00
   assets:checking
```

[**BeanCount**](https://beancount.github.io) - A double-entry bookkeeping computer language that lets you define financial transaction records in a text file, read them in memory, generate a variety of reports from them, and provides a web interface. 

```
2014-02-03 open Assets:US:BofA:Checking

2014-02-03 * "Initial deposit"
  Assets:US:BofA:Checking         100 USD
  Assets:Cash                    -100 USD

; I paid and left the taxi, forgot to take change, it was cold.
2015-01-01 * "Taxi home from concert in Brooklyn"
  Assets:Cash      -20 USD  ; inline comment
  Expenses:Taxi
```

[**mkjog**](https://gitea.gf4.pw/ki9/mkjog) - Manage your running in a text file. 

```
# DATE    	DIST	TIME 	PACE	COMMENT
2019-05-27	4.43	37:07	08:22 ; Chased by dog
2019-05-30	5.03	39:19	07:49
2019-06-02	5.05	42:03	08:20
2019-06-16	3.46	29:26	08:30	# Ran the big hill
```


## Light Markup

_Structured documents in text with formatting conventions_


**Markdown** -- see [Awesome Markdown](https://github.com/mundimark/awesome-markdown)

- [**Kramdown**](https://kramdown.gettalong.org) -- see [Awesome Kramdown](https://github.com/viennahtml/awesome-kramdown)

**Wikipedia Markup / Wiki Text**

**DokuWiki Markup**

[**Wiki Creole**](http://www.wikicreole.org)  

[**Text with Instruction (.texti)**](https://texti.github.io) - structured documents in text with formatting conventions; the best of markdown, wikipedia markup, latex & Friends - all together now

[**AsciiDoc**](http://www.methods.co.nz/asciidoc) by Stuart Rackham et al

[**Rimu Markup**](http://rimumarkup.org) by Stuart Rackham et al

**reStructured Text (.rst)**

**[Org /Org mode (Ecmacs)](http://orgmode.org)** -- your life in (plain) text; keeping notes, maintaining TODO lists, planning projects, and writing documents in fast and effective (plain) text

**[txt2tags](http://txt2tags.org)**



#### More

- [Compare Wiki Syntax @ WikiMatrix](http://www.wikimatrix.org/syntax.php)
- [Markup & Markdown Madness!](https://markupmadness.github.io)
- [Lightweight markup language @ Wikipedia](https://en.wikipedia.org/wiki/Lightweight_markup_language)



## Datafile Formats

_Values, records, hierarchies (trees), types & more_


**CSV (Comma-Separated Values)** -- see [Awesome CSV](https://github.com/csvalues/awesome-csv)

[**YAML (YAML Ain't Markup Language)**](http://yaml.org) -- see [Awesome YAML](https://github.com/datatxt/awseome-yaml)

[**JSON (JavaScript Object Notation)**](http://json.org) -- see [Awesome JSON (What's Next?)](https://github.com/jsonii/awesome-json-next)

[**TOML (Tom's Obvious, Minimal Language)**](https://github.com/toml-lang/toml) by Tom Preston-Werner et al

[**Markdown Configuration (.mdconf)**](https://github.com/tj/mdconf) by TJ Holowaychuk et al



## More

[**Plain Text Project**](https://plaintextproject.online) by Scott Nesbitt et al

[**Plain Text Accounting**](http://plaintextaccounting.org) by Simon Michael et al

- [**Ledger Syntax Quick Reference**](http://plaintextaccounting.org/quickref)


[**Mundi Mark**](https://mundimark.github.io) - all about markup & markdown



## Meta

**License**

![](https://publicdomainworks.github.io/buttons/zero88x31.png)

The awesome list is dedicated to the public domain. Use it as you please with no restrictions whatsoever.

**Questions? Comments?**

Post them to the [wwwmake forum](http://groups.google.com/group/wwwmake). Thanks!
