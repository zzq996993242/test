# -*- coding: UTF-8 -*-
from urllib import request

if __name__ == "__main__":
    response = request.urlopen("https://www.baidu.com")
    html = response.read()
    html = html.decode("utf-8")
    print(html)
