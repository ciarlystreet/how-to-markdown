如果你想对文档做更多的格式化，而这些格式超出了 MarkDown 的能力范围，你可以使用 HTML 标记，MarkDown 对 HTML 能够很好地兼容。

    <p align="center">可以很好地将文本居中。</p>

这样你就可以得到一个居中的段落。

这个功能非常有用，但是需要小心。HTML 内部的 MarkDown 语法会无效！如果你按下面的方式编写文档：

    <span>Markdown **不能** 正常工作！</span>

它不能正常工作。

## 挑战

创建一个新文件，在文件第一行添加一个一级标题，标题的文字是 `HTML`。

接下来，使用 HTML 将下面的文字居中：

    HTML in Markdown

完成后，请检查你的文件。

---