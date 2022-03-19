# OpenWrt orange pi r1 plus

lean https://github.com/coolsnowwolf/lede

lienol https://github.com/Lienol/openwrt

kenzok8 https://github.com/kenzok8/openwrt-packages

OpenAppFilter应用过滤插件 https://github.com/NueXini/NueXini_Packages
cd lede
sed -i '$a src-git NueXini_Packages https://github.com/NueXini/NueXini_Packages.git' feeds.conf.default
./scripts/feeds update -a && ./scripts/feeds install -a

p3terx https://p3terx.com/archives/build-openwrt-with-github-actions.html
       https://github.com/P3TERX/Actions-OpenWrt

Applications 插件说明 https://www.right.com.cn/forum/thread-344825-1-1.html
