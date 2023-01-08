# zoom-zd2-compressed

Taking inspiration from [this repo](https://github.com/ELynx/zoom-fx-compressed), I decided to strip the debug info from the .ZD2 files as well, using the [C6000 Assembly Language Tools](https://www.ti.com/tool/C6000-CGT) and [zoom-zt2](https://github.com/mungewell/zoom-zt2).

I haven't actually tested this yet (I will for G1X Four in a few days), but if the ZDLs work without debug info I don't believe there's any reason these shouldn't.

It looks like on average the effects are compressed ~80% for ZD2s as well, meaning that the stripped file is about 80% the size of the original. You should be able to put around 25% more effects into your unit using these files.

As with all of the Zoom modding stuff, use these at your own risk.
