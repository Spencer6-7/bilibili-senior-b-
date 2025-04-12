# bilibili-senior
调用AI自动答题

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

![Snipaste_2025-04-12_21-22-11](https://github.com/user-attachments/assets/2e12fb6b-2e94-44da-ab8b-15fcfa67c032)

![Snipaste_2025-04-12_21-22-26](https://github.com/user-attachments/assets/f93b42a0-0acb-4e53-9256-015445ba8a19)

![Snipaste_2025-04-12_21-24-57](https://github.com/user-attachments/assets/1155de6d-6233-4b7c-8c3f-45d8078cee98)

