# yibancheck
一个打卡脚本

需要抓包获得loginToken, deviceData, UA(User-Agent)

可使用bark推送结果

抓包方法可以在[EastItem/auto-daka](https://github.com/EastItem/auto-daka)和[liangzejun123/GDUF_autocheck](https://github.com/liangzejun123/GDUF_autocheck)获得

本项目代码也抄袭自上面两个项目，只是略加修改让代码能正常使用

本项目本着解决重复工作的繁琐，使用时请按时、如实打卡，遵守学校的防疫规定。

## 241218更新：
本项目更新考勤签到网页：

https://babattata-ta.github.io/yibancheck/

用其他QR扫描器提取出考勤员QR-Code截图的字符串，粘贴到输入框（

该字符串格式为开头是https://ygj.gduf.edu.cn/index.aspx?qrcode=[一段base64]+[一段256位的aes-ecb key,32位16进制数]的格式

本脚本仅为能用的程度，需要更多测试

可能会更新：

1、实现网页端扫码直接生成

2、在找yiban的url scheme在应用内打开URL，以单设备完成签到上传
