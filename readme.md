# ![](https://fonts.gstatic.com/s/i/materialiconsoutlined/flare/v4/24px.svg) Publish Books on Amazon
>__The missing guide on publishing books on Amazon from Linux__

# Arch Linux
- `yay -S pandoc`
- `yay -S kindlegen`
- write the MD book
- `pandoc readme.md -o readme.epub --metadata title="Publishing books on Amazon from Linux"`
- `kindlegen readme.epub`
