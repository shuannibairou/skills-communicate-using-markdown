# 基础命令
- 进入系统视图：system-view 或简写为 sys。
- 退出当前视图：quit。
- 返回用户视图：return。
- 查看当前配置：display current-configuration。
- 保存配置：save。
- 重启设备：reboot。
# 接口配置
- 进入接口视图：interface [接口类型][接口编号]
- ipv6 enable
- ipv6 address
- 查询某个接口的ipv6属性：dis ipv6 int g0/0/0 
- 配置接口 IP 地址：ip address [IP地址] [子网掩码]。
- 启用/关闭接口：undo shutdown（启用）/ shutdown（关闭）。
- 查看接口状态：display ip interface brief
VLAN 配置
- 创建 VLAN：vlan [VLAN编号]。
- 设置接口链路类型：port link-type [access|trunk|hybrid]。
- 将接口加入 VLAN：port default vlan [VLAN编号]
# 路由配置
- 配置静态路由：ip route-static [目的网络] [子网掩码] [下一跳地址]。
- 进入 RIP 协议视图：rip。
- 设置 RIP 版本：version [版本号]
- undo summary
- 宣告直连网段：network [网段]。
# 其他常用命令
- 更改主机名：hostname [新主机名]。
- 查看路由表：display ip routing-table。
- ping 测试：ping -a [源IP地址] [目的IP地址]。
- 自动补齐命令：输入命令开头后按 Tab 键。
- 命令提示：在命令中输入 ?，查看当前模式下的可用命令。
- 关闭生成树协议:undo stp enable(全局)如果要关闭特点接口，需要进入接口视图