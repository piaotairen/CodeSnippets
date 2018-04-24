# CodeSnippets

本仓库提供了Xcode的常用的代码块管理，配置详情请查看：Xcode奇淫巧技（四）——代码块Code Snippets，链接：https://blog.csdn.net/a184251289/article/details/58032989。

在iOS开发过程中，经常会用到一些相似的代码。我们能不能将这些代码保存起来，重复使用呢？回答是可以的。我们来看一下Xcode代码片段——Code Snippets。

初识代码片段
1. 新增
书写如下语句
@property (nonatomic, strong) <#type#> *<#value#>;
1
<##> 作用是占位，## 之间可以输入提示文字。

将上述代码，鼠标左键拖到常用代码管理区

进行如下配置：
Title：标题。 
Summary：描述文字。 
Platform：可以使用的平台（如iOS）。 
Language：可以在哪些语言中使用（如 Objective-C）。 
Completion Shortcut：快捷方式，以字母开头（支持少数符号，如@）。 
Completion Scopes：作用范围，一般写在正确的位置拖动即可，Xcode会自行选择好。
