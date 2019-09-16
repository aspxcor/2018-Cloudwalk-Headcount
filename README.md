# 基于PyramidBox的人头识别
## 背景 | Background
* 随着城市商业区的不断扩张和繁荣，越来越多的人在商业区购物，餐饮，寻找休闲和娱乐。繁华的商业区背后隐藏着巨大的危险。在紧急情况下，所有类型的风险将在人群区扩大。近年来，世界范围内发生的许多拥挤和践踏事故引发了对城市商业区管理的警示。
* With the continuous expansion and prosperity of urban commercial districts, more and more people are shopping, catering, finding leisure and entertainment in the business district. Behind the bustling business district is a huge hidden danger. In the event of an emergency, all types of risks will be amplified in crowd district. In recent years, many crowded and trampling accidents occurred worldwide have fired the alarm for the management of urban business districts.

## 任务 | Task
* 当我们想要计算一个非常拥挤的场景中有多少人时，我们自然地根据身体的可见部分计算人数，可见部分主要是头部区域。这促使我们检测人头计数，而不是整个以人为本来解决人群计数问题。比赛邀请参与者通过指示每个人的头部矩形的特定位置（x，y，w，h）来设计算法，主要用于检测复杂场景中的人头。其中，x表示x轴上的坐标，y表示y轴上的坐标，w是面矩形的宽度，h是面矩形的长度。
* When we want to calculate how many people in a very crowded scene, we naturally calculate the number of people based on the visible part of the body, and the visible part is mainly the head area. This drove us to detect head counting rather than the entire human-based to solve crowd counting problem. The contest invites participants to design algorithms, mainly for the detection of human heads in complex scenes, by indicating the specific position (x, y, w, h) of each person's head rectangle. In which, x represents the coordinate on the x axis, and y is the coordinate on the y axis, w is the width of the face rectangle, and h is the length of the face rectangle.
