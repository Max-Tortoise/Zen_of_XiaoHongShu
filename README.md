# Zen_of_XiaoHongShu

> 赞美一下小红书
* 2025-01-01: 发现存储逻辑不一致了，不知道和迁移到aliyun有没有关系
* 可以访问`https://www.xiaohongshu.com/user/profile/profile_id`，但是不能访问`https://www.xiaohongshu.com/user/profile/profile_id/`
* 不能直接访问note`https://www.xiaohongshu.com/explore/node_id`，必须加上`xsec_token`
* ~~不能直接访问profile`https://www.xiaohongshu.com/user/profile/profile_id`，必须加上`xsec_token`，但是`xsec_token`是可以传入空的~~
* 之前好奇RSSHub为什么小红书里没有日期，debug一下发现返回的json里面把日期给去掉了，这个反爬虫的思路太牛了
* 最开始版本的网页版，访问主页的json会包含note里的所有图片，后来只返回了每条note的封面图片
* 🫣🤭🫢🤫🤐
