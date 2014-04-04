assistant.vim
=============

Vim script: http://www.vim.org/scripts/script.php?script_id=2805

Display the definition of functions, variables, etc. (Tags, PHP/JS/Vim/...)

1. Use <C-h> to display the definition(load from tags and the dict) of functions, variables, etc.
2. Use <C-x><C-u> to complete words.

Supported dictionary list:

    php(en_US),
    vim(zh_CN),
    f90(zh_CN),
    ...

使用 <C-h> 快捷键显示当前位置函数或者变量名等关键字的原型，

<C-x-u>补全当前位置关键字，

支持Tags搜索，支持PHP、JS、Vim脚本等……

若喜欢用netbeans或者eclipse的补全快捷键，可以将 Conf 中的键映射启用。

若需要支持更多的文件类型，只要将符合 键=>值 形式的字典文件以 文件后缀名.dict.txt 保存到 assistant 目录下即可，1.35版之后会自动载入。

**** Install Detail ***

Just put the files into ~/.vim/plugin or <HOMEDIR>\vimfiles\plugin (for Windows).
