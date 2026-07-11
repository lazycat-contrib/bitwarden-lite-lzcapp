# bitwarden-lite-lzcapp

项目已升级为 LPK v2。每天 23:00 UTC 检查 `ghcr.io/bitwarden/lite` 稳定版本，自动复制 `linux/amd64` 镜像、构建版本化 LPK Release，并提交懒猫官方商店和喵喵私有商店。

GitHub Secrets：官方商店使用 `LAZYCAT_TOKEN`（或兼容凭据）；喵喵商店使用 `APPSTORE_URL`、`APPSTORE_TOKEN`，可选 `APP_ID` 和 `PRIVATE_STORE_GROUP_CODES`。
