## （2024-03-03和2024-03-10）这两次没有编译通过是因为新的passwall2中的插件编译时golang的版本要求1.22,但系统中是1.21,所以没有编译成功（2024-03-11）
- 具体的解决方案在github中有说，能不能成功就不知道了：https://github.com/coolsnowwolf/lede/issues/11921
- 我没有试，等主库更新。。。
### 配制信息
- 默认的管理地址是：192.168.1.181（原因是使用场景为旁路由，所以把原有的192.168.1.1改成了192.168.1.181）
- 子网掩码：255.255.255.0
- 默认网关：192.168.1.1
- DNS：223.5.5.5 192.168.1.1
- linux kernel版本是6.1.x（会根据https://github.com/coolsnowwolf/lede.git版本的升级自动升级）
- 用户名：root
- 密码：password
##### 首先感谢大佬的开源项目，是在他们基础上构建出来的：
- https://github.com/coolsnowwolf/lede.git
- https://github.com/linkease/istore
- https://github.com/xiaorouji/openwrt-passwall-packages.git
- https://github.com/xiaorouji/openwrt-passwall2.git
- https://github.com/fw876/helloworld.git

说明：如有侵权请及时联系删除
