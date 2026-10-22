# 我的个人主页

- 姓名或昵称：emmmm
- GitHub 用户名：emmmm7696
- 主页仓库：https://github.com/emmmm7696/acad-homepage.github.io

## 我修改了什么

-
-
-

### 方式 B：使用本地 Git

先在网页上 Fork PR-test，再执行下面的命令。示例中的 `YOUR_USERNAME` 都需要替换为自己的实际用户名。

```bash
git clone https://github.com/YOUR_USERNAME/PR-test.git
cd PR-test
git switch -c add-homepage-YOUR_USERNAME
mkdir -p members
# 创建 members/YOUR_USERNAME.md，按上面的模板填写并保存
git add members/YOUR_USERNAME.md
git commit -m "docs: add my homepage submission"
git push -u origin add-homepage-YOUR_USERNAME
