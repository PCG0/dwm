# 如何使用？

克隆并安装：

```bash
git clone https://github.com/PCG0/dwm

cd dwm

make && make clean install
```

然后在 `~/.xinitrc` 的末尾中添加：

```bash
exec dwm
```

如果你在 `~/.xinitrc` 的末尾中看到：

```bash
twm &
xclock -geometry 50x50-1+1 &
xterm -geometry 80x50+494+51 &
xterm -geometry 80x20+494-0 &
exec xterm -geometry 80x66+0+0 -name login
```

那么删掉他们。
