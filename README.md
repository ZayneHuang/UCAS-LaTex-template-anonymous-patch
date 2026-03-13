# 国科大LaTex模板一键匿名盲审补丁

1. 在现有LaTex模板包的基础上，将`Thesis.tex`、`Style/ucasthesis.cfg`替换对应的文件。如果`Thesis.tex`已经有修改，把63-75行复制进去也可
2. `FrontInfo.tex`请使用`Tex/FrontInfo.tex`的版本
3. `BackMatter.tex`请使用`Tex/BackMatter.tex`的版本
4. 在`Thesis.tex`中的65和67行，通过`\anonymoustrue`和`\anonymousfalse`控制是否导出盲审版匿名论文
5. 导入补丁后，首页、原创性声明和学位论文授权使用声明位置自动匿名为XXX；攻读学位期间发表的学术论文与科研成果也自动匿名，注意修改匿名后的成果内容
6. 其它需要匿名的地方使用`\anon{}{}`命令写，第一个大括号写正常内容，第二个大括号写匿名后的内容
7. 请一定仔细手动检查是否正确匿名，是否有遗漏！

欢迎讨论补充，也可邮件zeyuan2020@iscas.ac.cn