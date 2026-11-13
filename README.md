# SAM
SAM 是 SmartDNS 和 Mihomo 二合一的 Magisk 模块。两个服务都可以单独使用，也可以一起启用。

## 📖说明
- SmartDNS 的优先级最低，在无启用其它服务的情况下，才会作为本机的 DNS 转发服务，在有两种和三种服务启用，只会作为上游 DNS。
- Mihomo 启用时作为本机的 DNS 转发服务，未启用时才回落到 SmartDNS。

## ⚙️功能
- 服务结构: `SmartDNS > Mihomo`
- 监听:
  - 模块:
    - 启用即运行，禁用即停止
    - 卸载备份配置，恢复拦截广告
- 黑名单 WIFI 配置
- 黑白名单代理 App 配置
- 定时执行

## 📢注意
- 禁止和其它同类型模块使用
- 模块所有服务的账号和密码都是 `root`
- 禁止该文件随意修改
  - /data/adb/modules/SAM/etc/mihomo/base.yaml

## ⚠️无网络
- 检查手机网络，开关飞行模式
- 排查 Mihomo 的拦截日志，手动添加规则放行

## 🤝使用项目
- [MetaCubeX/mihomo](https://github.com/MetaCubeX/mihomo)
- [vernesong/mihomo](https://github.com/vernesong/mihomo)
- [pymumu/smartdns](https://github.com/pymumu/smartdns)

## 🙏感谢
- [GitMetaio/Surfing](https://github.com/GitMetaio/Surfing)
- Kisaratan