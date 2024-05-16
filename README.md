v9版本踩坑：

1.文档
https://pnpm.io/npmrc#link-workspace-packages

2.本地依赖安装失败
https://github.com/pnpm/pnpm/issues/8036

使用攻略：

1.请确保有安装pnpm

2.如果要使用monorepo，请在根目录创建pnpm-workspace.yaml并在里面设置packages

3.-w为根目录，-F后接对应的package就能操作子包
