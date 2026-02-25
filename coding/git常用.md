https://mp.weixin.qq.com/s/fOaXwvlEioTZr1pybWeOKQ

# 四个区域：

1. 工作区，就是你电脑上实际的文件夹，你和AI在这里写代码。
2. 暂存区，相当于一个待提交的缓冲区，你用git add把文件放进去。
3. 本地仓库，git commit之后，代码就正式存档到你本地的Git仓库里了。
4. 远程仓库，用git push把本地存档同步到GitHub或者GitLab上，相当于云存档。

git为什么需要一个暂存区，直接工作区到本地仓库不就行了吗？
![[Pasted image 20260225171043.png]]
感觉必要写不是很大，后面慢慢再感受吧，可能是我写的少。
# 常用代码：
1. 初始化：git init，当前文件夹变成一个本地仓库。
2. 本地文件→缓存区：git add .
3. 缓存区→本地仓库：git commit -m "完成了用户登录功能"
4. 