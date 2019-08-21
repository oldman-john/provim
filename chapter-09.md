Bulk Command Processing##
=========================
This was a short chapter, but as I mentioned in the preface to this book, the decision to have short and focused chapters was made purposely to aid new users to Vim and to help them more easily find the type of features they wanted to learn about.
With that in mind, let’s first recap some of the things you learned in this chapter and then move onward!
• I explained that Vim has multiple concepts of “lists” (such as the buffer list, window list, tab list, and arguments list).
• These lists can be manipulated by using specific commands (such as :bufdo, :windo, :tabdo, and :argdo).
• You learned how Vim internally processes these commands by starting at the first item in the respective list, executing the command, and then moving to the next item in the list, until all list items have been processed and we find ourselves inside the last list item.
Chapter 9 ■ Bulk Command proCessing
125
Chapter 9 ■ Bulk Command proCessing
126
• We looked at both a simple and complex example using the :bufdo command, the latter demonstrating the use of the exe command to let us construct complex expressions from external filters (such as VimL).
• We saw how the :windo command only affects visible buffers, and our example included a command (substitution) that we’ll see in much more detail in a later chapter.
• You learned about how :tabdo, although similar in principle, requires a different perspective when trying to solve problems using it, because the interface for tabs are fundamentally different from buffers and windows.
• Finally, we saw how the arguments list and the :argdo command work, as well as how the latter is subtlety different from the :bufdo command, because of the types of files it affects. We also saw how to dynamically update the arguments list from within Vim, and that it’s a destructive action (i.e., it doesn’t append files but completely re-creates the list).
======================
这是一个简短的章节，但正如我在本书前言中提到的那样，有意识地做出简短而有针对性的章节的决定是为了帮助新用户访问Vim并帮助他们更容易地找到他们想要了解的功能类型。
考虑到这一点，让我们首先回顾一下您在本章中学到的一些内容然后继续前进！
•我解释说Vim有多个“列表”概念（例如缓冲区列表，窗口列表，选项卡列表和参数列表）。
•可以使用特定命令（例如：bufdo，：windo，：tabdo和：argdo）操纵这些列表。
•您了解了Vim如何在内部处理这些命令，方法是从相应列表中的第一项开始，执行命令，然后移动到列表中的下一项，直到所有列表项都已处理完毕，我们发现自己在最后一个列表中项目。
第9章■批量命令处理
125
第9章■批量命令处理
126
•我们使用：bufdo命令查看了一个简单而复杂的示例，后者演示了如何使用exe命令让我们从外部过滤器（如VimL）构造复杂表达式。
•我们看到：windo命令仅影响可见缓冲区，我们的示例包含一个命令（替换），我们将在后面的章节中详细介绍。
•您了解了如何：tabdo虽然在原理上类似，但在尝试使用它时解决问题时需要不同的视角，因为选项卡的界面与缓冲区和窗口根本不同。
•最后，我们看到了参数列表和：argdo命令如何工作，以及后者如何与：bufdo命令的细微差别，因为它影响的文件类型。我们还看到了如何从Vim中动态更新参数列表，并且这是一个破坏性的操作（即，它不附加文件但完全重新创建列表）。
