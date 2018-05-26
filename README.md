# 51-MCU-for-character-LED-dot-matrix-
51 MCU for character LED dot matrix display question，51单片机驱动32*32点阵字符
本项目是使用51单片机实现32*32的点阵汉字显示 ，设计才用两片74LS154（4-16译码器）控制行，4片74hs595控制列，采用动态扫描的方式，每给一个行信号，4片74hs595填充32位数据，然后输出到LED，然后给下一个行信号。
在时间允许的范围内添加一些额外的功能，比如APP实时显示，
