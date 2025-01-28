# Minecraft Java版
## 使用方法

1. 下载规则和小黑屋文件，分别放在 `/etc/fail2ban/fitter.d/` 和 `/etc/fail2ban/jali.d/` 两个文件夹里面。
2. 修改 minecraft-java.local 中的 logpath, 日志文件路径必须是绝对路径。
3. 执行 `fail2ban-client reload` 重载规则。

## 提示

Minecraft Java版服务端的日志文件路径如下：

```
<minecraft-server-path>/logs/latest.log
```
