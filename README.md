# OpenWRT-CI for AX1800Pro
云编译OpenWRT固件

官方版：
https://github.com/immortalwrt/immortalwrt.git

高通版：
https://github.com/VIKINGYFY/immortalwrt.git

# 固件简要说明：

固件每天早上4点自动编译。

固件信息里的时间为编译开始的时间，方便核对上游源码提交时间。

QUALCOMMAX系列AX1800Pro、X86系列。

AX1800Pro 需要刷大分区的GPT，默认gpt分区表无法输入超过60M的固件。

# 目录简要说明：

workflows——自定义CI配置

Scripts——自定义脚本

Config——自定义配置
