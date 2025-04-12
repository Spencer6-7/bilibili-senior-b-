# bilibili-senior B站硬核会员答题

提取网页元素，调用 GPT-4o-mini 或 Deepseek 自动答题

![Snipaste_2025-04-12_21-22-26](https://github.com/user-attachments/assets/f93b42a0-0acb-4e53-9256-015445ba8a19)

关键词：6级会员、硬核会员、bilibili、B站、哔哩哔哩

## 安装

[greasyfork.org地址](https://greasyfork.org/fr/scripts/532626-b%E7%AB%99%E7%A1%AC%E6%A0%B8ai%E7%AD%94%E9%A2%98)

## 使用

1.  手机B站进行硬核答题页面，直接开始答题。
2.  浏览器打开调试工具(`F12`), 将浏览器切换为移动设备，(左上角的图标，快捷键是`Ctrl+Shift+M`)；
4.  进入答题地址[https://www.bilibili.com/h5/senior-newbie/](https://www.bilibili.com/h5/senior-newbie/)
5.  Tampermonkey扩展中选择脚本，配置API和启动

## 一些注意点

- 手机B站开始答题了，网页才能使用，两个小时时间足够调试
- 选择`文史`，`知识`，`影视`这些适合AI回答的分类
- 控制台可以查看进度
- 间隔时间可以自己调一下：`const delayTime = getRandomDelay(5000, 10000);`，默认是5-10s中随机选择
- DeekSeek使用的官网API，GPT-4o-mini使用的第三方的网站

![Snipaste_2025-04-12_21-22-11](https://github.com/user-attachments/assets/2e12fb6b-2e94-44da-ab8b-15fcfa67c032)

![Snipaste_2025-04-12_21-24-57](https://github.com/user-attachments/assets/1155de6d-6233-4b7c-8c3f-45d8078cee98)


修改自：[HCLonely/bili-senior-newbie-qa: 哔哩哔哩硬核会员搜题脚本](https://github.com/HCLonely/bili-senior-newbie-qa?tab=readme-ov-file)，答题页面对问题进行了混淆，源程序将所有问题拼在一块儿，不能定位当前问题。修改的地方：利用hash列表记录问题历史，能很好定位当前问题。

