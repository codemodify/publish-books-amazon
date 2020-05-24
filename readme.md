# ![](https://fonts.gstatic.com/s/i/materialiconsoutlined/flare/v4/24px.svg) Publish Books on Amazon
>__The missing guide on publishing books on Amazon from Linux__

>__This is designed to be hands on and to the point without any BS__

>__Book updated on May 24 2020__


# Arch Linux
- `yay -S pandoc`


- `yay -S kindlegen`


- Write the MD (markdown format) book


- `pandoc book.md -o book.epub --metadata title="Publishing books on Amazon from Linux"`


- `kindlegen book.epub`


- Take the generated book.mobi and upload it to https://kdp.amazon.com



# Source Code
https://github.com/codemodify/publish-books-amazon
