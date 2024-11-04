[中文](https://p3terx.com/archives/build-openwrt-with-github-actions.html)

# Immortalwrt Images

仅对MR3000D-CIq（512M）/JCG q30 编译固件
固件分为：
- [hanwckf / immortalwrt-mt798x](https://github.com/hanwckf/immortalwrt-mt798x), openwrt 21.02， 稳定好用，预装PW2。
- [padavanonly / immortalwrt-mt798x-23.05](https://github.com/padavanonly/immortalwrt-mt798x-23.05) openwrt 23.05，mtk无线驱动，mtk网络加速，支持 firewall4 nft，预装HP，但内核依旧为5.4，所以部分软件安装会报错，但能预编译进固件的就能用。谨慎选择！！！
[Download File](https://github.com/1molCu/openwrt_action/releases)

## Credits

- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)
- [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
- [Mattraks/delete-workflow-runs](https://github.com/Mattraks/delete-workflow-runs)
- [dev-drprasad/delete-older-releases](https://github.com/dev-drprasad/delete-older-releases)
- [peter-evans/repository-dispatch](https://github.com/peter-evans/repository-dispatch)
- [hanwckf / immortalwrt-mt798x](https://github.com/hanwckf/immortalwrt-mt798x)
- [padavanonly / immortalwrt-mt798x-23.05](https://github.com/padavanonly/immortalwrt-mt798x-23.05)
## License

[MIT](https://github.com/P3TERX/Actions-OpenWrt/blob/main/LICENSE) © [**P3TERX**](https://p3terx.com)
