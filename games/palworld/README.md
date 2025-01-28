# 幻兽帕鲁

## 使用方法

1. 下载规则和小黑屋文件，分别放在 `/etc/fail2ban/fitter.d/` 和 `/etc/fail2ban/jali.d/` 两个文件夹里面。
2. 修改 palworld.local 中的 logpath，日志文件路径必须是绝对路径。
3. 执行 `fail2ban-client reload` 重载规则。

## 提示

幻兽帕鲁的服务端日志文件路径如下：

```
<palworld-server/path>/Saved/Logs/PalServer.log
```
