# RenGo 隐私政策页

App Store Connect 要求填写「隐私政策网址」，本仓库只为托管那一个页面。

内容源文件在 RenGo 主仓库的 `docs/privacy-policy.md`；`index.html` 由其生成。
修改后请同步两边。

## 发布步骤

1. 在 GitHub 上新建一个**公开**仓库，名为 `rengo-privacy`（不要勾选任何初始化文件）
2. 在本目录执行：

   git remote add origin git@github.com:JO-WTF/rengo-privacy.git
   git push -u origin main

3. 到仓库 Settings → Pages，Source 选 `Deploy from a branch`，
   分支选 `main`、目录选 `/ (root)`，保存
4. 等待约 1 分钟，页面上线于：

   https://jo-wtf.github.io/rengo-privacy/

5. 把该网址填入 App Store Connect 的「隐私政策网址」
