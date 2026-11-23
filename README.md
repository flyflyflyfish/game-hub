# 果果游戏大厅 🍈

一家人小游戏合集的门户页（纯静态，零后端、零内存占用）。部署在 `flyflyflyflyfish.cn/hub/`。

- **果果麻将** → `/mj/`（family-mahjong）
- **果果五子棋** → `/gmk/`（gomoku）
- 更多游戏敬请期待

登录状态展示复用果果五子棋的登录 token（`gg_wzq_token`，与果果麻将同一账号体系），通过 `/gmk/api/me` 接口获取用户名。

## 部署

把 `index.html` 放到服务器 `/var/www/flyflyflyfish.cn/hub/` 即可（nginx 主站 root 已覆盖，无需新增配置）。
