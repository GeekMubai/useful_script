# useful_script

个人写的一些自用的小脚本。

# 注意

以下脚本如有在使用过程中出现任何问题，均与本人无关。

## 查找项目中废弃的图片

主要是因为在开发的时候，有些图片放在XCode项目中，但是在版本迭代的时候，经常无法及时的删除无用的图片，所以，长时间的积累的话，肯定会造成项目的越来越臃肿。

脚本可以清理项目中的无用的图片，并将清理掉的内容写到缓存起来，以备查看。

测试了几个项目，效果还不错。

[查看详细说明](https://github.com/JyHu/useful_script/blob/master/Scripts/查找项目中废弃的图片/Note.md)

## 导出XCode中的Framework

将XCode中的各个平台的SDK导出到目标目录，可以导出为markdown文件和头文件。

使用

python 脚本文件名 保存地址

例：
`python frameworkHeaders.py /Users/JyHu/Desktop/t`

***

当有新需求的时候会第一时间更新上来。。。
