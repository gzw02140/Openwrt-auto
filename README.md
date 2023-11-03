# Openwrt-auto
完成.config配置之后，使用以下命令完成配置差异化文件
`./scripts/diffconfig.sh > diffconfig`
将diffconfig的内容复制如action文件中

也可以使用make defconfig命令生成完整版的配置文件
```
cp diffconfig .config
make defconfig
```
