# 11
 #爬虫 免费观看会员视频
#-*- coding:UTF-8 -*-
url = 'https://okjx.cc/?url='
import sys

import webbrowser

sys.path.append("libs")

##修改链接
urls = "https://www.iqiyi.com/v_19rrol0698.html#vfrm=19-9-0-1"
print(url+urls)

webbrowser.open(url+urls)

print(webbrowser.get())
