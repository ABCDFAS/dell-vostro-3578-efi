## 这里是Dell vostro 3578 黑果的efi（可下载文件的仓库）

需要预览EFI内的文件 请移步至此仓库https://github.com/ABCDFAS/vostro-3578-hackintosh-efi/

网上查了很多都没有这个机型的efi 今天我来了～ 来放上～（毕竟这机型也很冷门呐）

本来呢 我不打算把这个放到GitHub上 因为不会怎么放（捂脸）

这个efi 适用于dell vostro 3578 

本机配置：

| CPU  | i5-8250u                                        |
| ---- | ----------------------------------------------- |
| 内存 | 4GB DDR4 2400                                   |
| 硬盘 | 256GB 镁光SATA SSD                              |
| 显卡 | 核显 UHD620<br />独显Radeon 520（黑果无法驱动） |
| 声卡 | ALC236 layout-id: `16`                          |

- 功能列表
  - 核显驱动成功 显示2048mb
  - 声卡有时可能会耳机不太好 重启即可 估计死了
  - 网卡以太网可以的 无线我上了94360cs2 正常
  - 亮度已修复 可大幅度调
  - usb驱动已成功
  - 蓝牙正常
  - 触控板支持Apple多点式触控
  - 电池显示正常
  - 睡眠暂时可以 时间长自动唤醒 10.14.6以下可能会卡黑屏

不工作：读卡器 独显

bios设置 csm关闭 uefi打开 secure boot关闭

clover版本 5103

GitHub不能下太多哈 回来下不完整 这里给个百度云链接 （已更新 请看下面）

掉了的话提醒我一声 我会补上

2020/03/13更新：kext简化 解决可能因为触控板而导致的卡屏死机问题 将EFI内容打包成ZIP形式 有效解决部分下载不完整问题

百度网盘链接:https://pan.baidu.com/s/1Cy_hf8INA946SzzVzGwqpQ  密码:z0vo

最后来几张图~嘻嘻!![](/Users/gaotiancheng/Desktop/截屏2020-03-14上午12.39.34.png)

![截屏2020-03-14上午12.40.14](/Users/gaotiancheng/Desktop/截屏2020-03-14上午12.40.14.png)

![截屏2020-03-14上午12.40.37](/Users/gaotiancheng/Desktop/截屏2020-03-14上午12.40.37.png)

![截屏2020-03-14上午12.40.46](/Users/gaotiancheng/Desktop/截屏2020-03-14上午12.40.46.png)

![截屏2020-03-14上午12.41.22](/Users/gaotiancheng/Desktop/截屏2020-03-14上午12.41.22.png)

![截屏2020-03-14上午12.41.37](/Users/gaotiancheng/Desktop/截屏2020-03-14上午12.41.37.png)