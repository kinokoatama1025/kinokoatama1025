# kinokoatama1025
# 1426028 折井
# robosysの課題です
# 携帯の着信発光みたいにしてみました
$make

$sudo insmod myled.ko

$sudo chmod 666 /dev/myled0

$sudo chmod +x kicdic.bash

$sudo ./kicdic.bash

#上のように入力し開始してください
