# 获取 BULM 多账户 100% 在线 免费 NODE.js 机器人

这个 Node.js 机器人脚本可以管理 Blum 机器人的多账户，支持无限账户处理，每日领取、每日游戏、每日任务。脚本还包括定期发送领取 BLUM 代币的功能。如果你的电脑可以 24/7 运行，你不需要 VPS，否则建议购买一个小型 VPS!!

**在此注册 Blum** - [https://t.me/blum/app?startapp=ref_4P0iHV9xlf](https://t.me/blum/app?startapp=ref_4P0iHV9xlf)

# 不要错过 Blum，它是由币安实验室投资的！第七季！ ![image](https://github.com/user-attachments/assets/8ad531fd-d417-40e0-9c74-66b91da03a02)

# 获取 Query_id 的步骤 ->

1. 打开 Telegram 桌面版，进入设置，然后选择高级 > 实验性设置。
2. ![image](https://github.com/user-attachments/assets/f2251f9a-be84-4db7-b568-7bc164bc3f78)
3. 打开 `启用网络检查`。
4. ![image](https://github.com/user-attachments/assets/9bc59cbc-0fd4-4cf8-ac70-1f6547edc366)
5. 完成！登录 Blum 机器人并检查获取 Query ID（右键点击检查）。
6. ![image](https://github.com/user-attachments/assets/c27bccac-b8bd-43fd-a3dd-7727be662abe)

# 操作步骤：

1. 克隆仓库 - `git clone https://github.com/Solana0x/blumscript`
2. 然后进入项目目录 `cd blumscript`
3. 安装依赖包 `npm install`
4. 在 Telegram 桌面版右键点击你的机器人，然后检查，获取 `query_id=`
5. 在控制台输入 `allow pasting`，然后输入 `sessionStorage.getItem('query_id');`
6. 你将看到类似 `'query_id=AAENbsx1uxHCS49780&hash=7a153fc0cfd3e78056x3bfdd346d783036'` 的输出，复制这个 query_id。
7. 在 data.txt 文件中每行添加一个新的 `query_id=`。
8. 对所有 Telegram 账户重复此操作。
9. 完成后，运行机器人代码 - `node blum.js`
10. 如果你想使用代理来避免 Sybil 攻击！请运行 `node blum-proxy.js` 并在 `proxy.txt` 文件中添加你的代理！
11. 机器人有两种方式：1. 如果你选择是（y），它将完成所有任务，如 Coinmarketcap、币安等 app 中的所有任务；
   2. 如果你选择否（n），它将跳过任务，只进行游戏和每日签到等操作。
11. 所以，首次运行建议选择是（y），之后每日使用时选择否（n）！

```javascript
async randomDelay() {
    const delay = Math.floor(Math.random() * (5000 - 3000 + 1)) + 3000;
    return new Promise(resolve => setTimeout(resolve, delay));
}

```

如果你想自定义随机延迟，可以将 3000 改为 0！3000 表示任务之间的 3 秒延迟。

# 机器人的功能：

1. 自动养殖机器人
2. 自动每日签到
3. 自动每 7 小时签到
4. 自动玩游戏
5. 自动加入部落
6. 自动完成任务

![image](https://github.com/user-attachments/assets/7bd8f8f2-5b73-4967-b582-61035eecfe48)

# 如需任何帮助，请联系：0xphatom on Discord https://discord.com/users/979641024215416842


