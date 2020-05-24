# ![](https://fonts.gstatic.com/s/i/materialiconsoutlined/flare/v4/24px.svg) Publish Books on Amazon
>__The missing guide on publishing books on Amazon from Arch Linux__

>__This is designed to be hands on and to the point without any BS__

>__Book updated on May 24 2020__



# ![](https://fonts.gstatic.com/s/i/materialicons/build/v5/24px.svg) Tools
- Run in terminal
	```bash
	yay -S pandoc
	```

- Run in terminal
	```bash
	yay -S kindlegen
	```



# ![](https://fonts.gstatic.com/s/i/materialicons/publish/v5/24px.svg) Publish

- Write the MD (markdown format) book

- Run in terminal
	```bash
	pandoc readme.md -o book.epub --metadata title="Publishing books on Amazon from Arch Linux"
	```

- Run in terminal
	```bash
	kindlegen book.epub`
	```


- Take the generated "book.mobi" and upload it to https://kdp.amazon.com



# ![](https://fonts.gstatic.com/s/i/materialicons/code/v5/24px.svg) Source Code

https://github.com/codemodify/publish-books-amazon
