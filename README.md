# ZWH SPACE INDUSTRIAL / ZSI 静态网站 V2

这是一个可直接部署到 GitHub Pages 的静态网站。

## 文件说明

- `index.html`：主页
- `login.html`：员工登录页
- `ships.html`：舰船售卖中心
- `assets/ships/`：从《舰船档案.docx》导出的舰船图片

## 本次更新

- 主页导航中的“舰船售卖”已指向 `ships.html`
- 主页二级导航中的“舰船售卖中心”已指向 `ships.html`
- 主页英雄区按钮“进入舰船售卖中心”已指向 `ships.html`
- 已从《舰船档案.docx》录入 19 艘舰船信息
- 已导入 38 张舰船图片
- 售卖页支持搜索、厂商筛选、舰种筛选、详情弹窗

## GitHub Pages 部署方法

1. 新建 GitHub 仓库，例如 `zsi-site`
2. 上传本文件夹中的所有文件和 `assets` 文件夹
3. 进入仓库 `Settings`
4. 打开 `Pages`
5. Source 选择 `Deploy from a branch`
6. Branch 选择 `main`，目录选择 `/root`
7. 保存后等待 GitHub Pages 自动生成网址

## 注意

当前登录页和购买申请为静态演示，不连接数据库。真实登录或订单系统需要后端服务。
