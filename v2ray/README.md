## v2ray-core
- [~~https://github.com/v2ray/v2ray-core~~](https://github.com/v2ray/v2ray-core/)
- [https://github.com/v2fly/v2ray-core](https://github.com/v2fly/v2ray-core)

## `dlc.dat`
- [~~https://github.com/v2ray/domain-list-community/~~](https://github.com/v2ray/domain-list-community)
- [https://github.com/v2fly/domain-list-community](https://github.com/v2fly/domain-list-community)

## `geosite.dat`
- [https://github.com/Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat)

## `geoip.dat`
- [~~https://github.com/v2ray/geoip/~~](https://github.com/v2ray/geoip)
- [https://github.com/v2fly/geoip](https://github.com/v2fly/geoip)

## 安裝和更新 `V2Ray` 脚本
- [https://github.com/v2fly/fhs-install-v2ray/](https://github.com/v2fly/fhs-install-v2ray/)

```
installed: /usr/local/bin/v2ray
installed: /usr/local/bin/v2ctl
installed: /usr/local/share/v2ray/geoip.dat
installed: /usr/local/share/v2ray/geosite.dat
installed: /usr/local/etc/v2ray/config.json
installed: /var/log/v2ray/
installed: /var/log/v2ray/access.log
installed: /var/log/v2ray/error.log
installed: /etc/systemd/system/v2ray.service
installed: /etc/systemd/system/v2ray@.service
```

### 安裝和更新 `V2Ray`

```
# bash install-release.sh
```

### 安裝最新發行的 `geoip.dat` 和 `geosite.dat`

```
# bash install-dat-release.sh
```

### 移除 `V2Ray`
```
# bash install-release.sh --remove
```
