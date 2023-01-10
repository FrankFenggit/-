# usb、串口、设备管理资料收集

## [CEnumerateSerial 枚举串行端口的 C++ 类](http://www.naughter.com/enumser.html)

```
简单的 C++ 类接口。

该代码完全兼容 Unicode，并在工作区文件中包含 Unicode 构建选项。

在内部，代码提供了 10 种不同的方式（是的，你没看错：十种）来枚举串行端口：使用 CreateFile、QueryDosDevice、GetDefaultCommConfig，两种使用 Setup API、EnumPorts、WMI、Com Database 的方式，枚举注册表项 HKEY_LOCAL_MACHINE 下的值\HARDWARE\DEVICEMAP\SERIALCOMM & GetCommPorts。

All of the configuration of the code is controlled by the following preprocessor values: NO_CENUMERATESERIAL_USING_CREATEFILE, NO_CENUMERATESERIAL_USING_QUERYDOSDEVICE, NO_CENUMERATESERIAL_USING_GETDEFAULTCOMMCONFIG, NO_CENUMERATESERIAL_USING_SETUPAPI1, NO_CENUMERATESERIAL_USING_SETUPAPI2, NO_CENUMERATESERIAL_USING_ENUMPORTS, NO_CENUMERATESERIAL_USING_WMI, NO_CENUMERATESERIAL_USING_COMDB & NO_CENUMERATESERIAL_USING_REGISTRY.

```
