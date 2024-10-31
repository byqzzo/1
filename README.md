# 1. 初始化本地仓库（如果已经有远程仓库，可以跳过此步）
git init

# 2. 克隆远程仓库（如果已有远程仓库）
git clone https://github.com/your-username/repository-name.git
cd repository-name

# 3. 创建或编辑文件
echo "Hello, GitHub!" > example.txt

# 4. 将文件添加到暂存区
git add example.txt

# 5. 提交修改，创建 commit
git commit -m "Add example.txt with Hello, GitHub! message"

# 6. 推送到远程仓库的主分支
git push origin main  # 或者 git push origin master，根据仓库的默认分支而定
