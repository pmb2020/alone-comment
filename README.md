# zxcomment
真心评论系统，简单、免费、无广告。

开发记录
思路：
点击发表评论，将访客信息存入cookie（昵称、邮箱、网址），

点击回复，判断cookie是否存在，不存在提示用户生成自己的id通行证，生成后可评论


待完成：
生成名片的动画，后台接口


评论数据库设计
id 
p_id(默认为0留言系统，其他为文章评论)
username（用户昵称）
com_id（默认0一级评论，其他则为二级评论）
title(评论自由)
time
ip（char16）
address(varchar20)
zan
