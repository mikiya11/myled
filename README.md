このプログラムは、LEDを点滅させ、Raspberry Pi 4 Model B上のubuntuにおいて動作できる。また、点滅回数は自由に設定可能。

# 使い方
	make
	sudo insmod myled.ko
	sudo chmod 666 /dev/myled0
	echo -n [number] > /dev/myled0
を入力。numberには点滅させたい回数を入れる。
# デモ動画
[youtube]https://youtu.be/K4OsGqTQ_y0
# LICENCE
GNU General Public License v3.0
