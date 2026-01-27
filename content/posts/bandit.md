+++
date = '2026-01-26T16:54:48+08:00'
draft = true
title = 'Bandit'
+++
ssh bandit8@bandit.labs.overthewire.org -p 2220 

find . -size 1033c

find . -size 33c -user bandit7 -readable 2>/dev/null   #屏蔽错误信息 1>/dev/null屏蔽正确信息

cat data.txt | grep millionth

cat data.txt | sort | uniq -u #sort排序 uniq过滤重复 -u指定唯一

strings data.txt | grep = #strings提取并显示长度超过4的人类可读字符串

cat data.txt | base64 -d #base64 -d解码为人类可读数据

cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'

7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4



