# 初始需要
git init

# 添加所有
git add -A

# 提交本地库
git commit -m "***"

# 分支,注意由于本地有多个仓库，需要ssh-keygen生成多个账号
git branch -M main
git remote add origin git@mlagent.github.com:generatemotion/mini_ml_agent.git

# 提交github

git push -u origin main