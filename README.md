[TOC]

# 123hhh
111
222
333aaaa
444aaaa
jjjj
ccc


> hduehdueude

> rfrffrfefefjefie


|不同点|appium_lib方法|selenium-webdriver方法|
|--|--|--|
|driver|Appium::Driver|Selenium::WebDriver|
|id定位|elem = page.id('resource-id')|elem = page.find_element(id: 'resource-id')|
|id|ids('resource-id')|find_elements(id: '')|
|class_name|tag(class_name)默认匹配第一个|find_element(:class, class_name)|
|class_name|tags(class_name)| find_elements(:class, class_name)|
|class_name|first_ele(class_name)和tag(class_name)一样||
|class_name|last_ele(class_name)|ele_index(class_name, 'last()'）|
|输入内容|element.type(text)|element.send_keys(text)|
|获取window大小|window_size|driver.manage.window.size|
