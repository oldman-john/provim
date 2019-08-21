Search and Replace
==================
This has been quite a packed chapter, and I’ve covered a lot of important topics that will be a cornerstone of your newly acquired editing capabilities. Let’s take a “whistle-stop” tour of the functionality you learned in this chapter.
• We used :find to help us locate files, specifically within directories that Vim has access to via its runtime path. (We also looked at modifying this path to include additional directories of our choosing, using :set path+=~/SomeOtherDirectory.)
• We started to investigate the different ways to search for content, beginning with searching within the current buffer. Here, we revisited the / and ? search commands along with using the n/N commands for navigating matches. We also looked at the \c flag and hlsearch/ignorecase settings, to see how they affect the sensitivity and highlighting of matches.
164
ChAptEr 11 ■ SEArCh AND rEpLACE
• You learned about shorthand commands that allow us to automatically search for the word
under our cursor, using the # and * commands.
• In Vim 7.4+, we discovered that we are able to make a slight increase in speed in our ability to
search and edit, by utilizing the gn and gN commands.
• We then started to investigate options for searching for content within multiple buffers. This led us to vimgrep/lvimgrep, where we looked at the subtle differences and why you would use one over the other. We also saw how to modify Vim, so that we can use a different external grep’ing application.
• You learned about Vim’s lesser known ability to backtrack through multiple search histories, using :colder and :cnewer (as well as the location list variations :lolder/:lnewer).
• From there, we started to investigate options for not only searching for content (either within a single file or multiple files) but to apply a replacement pattern onto matches as well. This revolved fundamentally around the substitution command and the different techniques and tips for utilizing it alongside regular expressions and the expression register.
• You learned that trying to apply replacements across multiple files can be a performance concern in Vim, and so we looked at an alternative solution within the terminal, using the sed command.
• We took a look at another (and equally powerful) way to search content and apply changes to those matches, this time using the :global command, which allowed us to execute NORMAL mode and COMMAND-LINE mode commands to matches.
=====================
这已经是一个非常紧凑的章节，我已经介绍了许多重要的主题，这些主题将成为您新获得的编辑功能的基石。让我们对您在本章中学到的功能进行“终止”之旅。
•我们使用：find帮助我们定位文件，特别是在Vim通过其运行时路径访问的目录中。 （我们还考虑修改此路径以包含我们选择的其他目录，使用：set path + =〜/ SomeOtherDirectory。）
•我们开始研究搜索内容的不同方法，从在当前缓冲区内搜索开始。在这里，我们重访了/和？搜索命令以及使用n / N命令导航匹配。我们还查看了\ c标志和hlsearch / ignorecase设置，以了解它们如何影响匹配的灵敏度和突出显示。
164
ChAptEr 11■海洋和赛道
•您了解了允许我们自动搜索单词的速记命令
在我们的光标下，使用＃和*命令。
•在Vim 7.4+中，我们发现我们能够略微提高速度
通过使用gn和gN命令搜索和编辑。
•然后，我们开始研究在多个缓冲区中搜索内容的选项。这导致我们进入vimgrep / lvimgrep，在那里我们看到了微妙的差异，以及为什么要使用其中一个。我们还看到了如何修改Vim，以便我们可以使用不同的外部grep'ing应用程序。
•您了解了Vim用于回溯多个搜索历史的鲜为人知的能力，使用：colder和：cnewer（以及位置列表变体：lolder /：lnewer）。
•从那里开始，我们开始研究不仅搜索内容（在单个文件中或多个文件中）的选项，还要在匹配上应用替换模式。这基本围绕替换命令以及与正则表达式和表达式寄存器一起使用它的不同技术和技巧。
•您了解到尝试在多个文件中应用替换可能是Vim中的性能问题，因此我们使用sed命令查看了终端内的替代解决方案。
•我们查看了另一种（同样强大的）搜索内容并对这些匹配应用更改的方法，这次使用：global命令，它允许我们执行NORMAL模式和COMMAND-LINE模式命令进行匹配。
