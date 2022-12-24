# GooseGooseDuck_helper
a non-cheating GooseGooseDuck  helper for time record and role&amp;team mark

鹅鸭杀小型软件（非作弊）
相关组件：pyqt5, Qt Designer, pyautogui

这是一个在游戏之上的透明窗口

主要功能：
1.每局计时


![Image](https://user-images.githubusercontent.com/86272490/209444254-ea210d94-2f07-45bc-baa7-bcfb99509cf3.png)


在开始行动之后，计时器会自动缩小到上方并开始计时，方便计算狼人出刀次数cd以及加拿大鹅推测。

2.人物角色标记&组队标记

![Image](https://user-images.githubusercontent.com/86272490/209444273-2be76a92-0333-4a66-9260-1fd825faa331.png)


3.按钮作用：
小窗口：调整窗口大小，并调整位置
大窗口：调整窗口大小，并自动调整位置
重置：将面板所有已做标记清空，并重置计时器
黑色方块：用于拖动，无其他作用。

原理：子线程检测开局画面和会议画面。链接计时函数以及窗口调整函数。


改进空间：
1. 目前只有中文版本
2. 目前只支持4k全屏分辨率
3. 每一局结束回到大厅之后，需要手动点击重置

好不容易进来了，留下星星再走吧:D
会努力更新的
——————————————————

Goose Goose Duck little hepler (no cheating)

Related components: pyqt5, Qt Designer, pyautogui

This is a transparent window on top of the game


Main functions:

1. Time record





! [Image](https://user-images.githubusercontent.com/86272490/209444254-ea210d94-2f07-45bc-baa7-bcfb99509cf3.png)





Each action turn, the timer will automatically reset and start counting.


2. role mark & team mark


! [Image](https://user-images.githubusercontent.com/86272490/209444273-2be76a92-0333-4a66-9260-1fd825faa331.png)





3. Function of button:

Small window: Resize the window and adjust the position

Large window: Resize the window and automatically adjust the position

Reset: Clear the panel of all marked and reset the timer

Black box: Used for dragging, no other purpose.



How it work: two thread detects Action step screen and meeting screen. Link timing function and window adjustment function.





Improvement:

1. Currently only available in Chinese

2. Currently, only 4k full screen resolution is supported

3. After returning to the lobby at the end of each game, you need to manually click Reset button.


If you like it, leave the stars :D



Will update if someone is looking for it.
