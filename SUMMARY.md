# Table of contents

* [FreeBSD 架构手册](README.md)
* [FreeBSD 架构手册](freebsd-jia-gou-shou-ce.md)
* [概述](gai-shu.md)
* [第一部分 内核](di-yi-bu-fen-nei-he.md)

## 第1章 引导和内核初始化

* [1.1. 内容提要](di-1-zhang-yin-dao-he-nei-he-chu-shi-hua/1.1.-nei-rong-ti-yao.md)
* [1.2. 概述](di-1-zhang-yin-dao-he-nei-he-chu-shi-hua/1.2.-gai-shu.md)
* [1.3. BIOS](di-1-zhang-yin-dao-he-nei-he-chu-shi-hua/1.3.-bios.md)
* [1.4. 主引导记录（boot0）](di-1-zhang-yin-dao-he-nei-he-chu-shi-hua/1.4.-zhu-yin-dao-ji-lu-boot0.md)
* [1.5. boot1 阶段](di-1-zhang-yin-dao-he-nei-he-chu-shi-hua/1.5.-boot1-jie-duan.md)
* [1.6. BTX 服务器](di-1-zhang-yin-dao-he-nei-he-chu-shi-hua/1.6.-btx-fu-wu-qi.md)
* [1.7. boot2 阶段](di-1-zhang-yin-dao-he-nei-he-chu-shi-hua/1.7.-boot2-jie-duan.md)
* [1.8. loader 阶段](di-1-zhang-yin-dao-he-nei-he-chu-shi-hua/1.8.-loader-jie-duan.md)
* [1.9. 内核初始化](di-1-zhang-yin-dao-he-nei-he-chu-shi-hua/1.9.-nei-he-chu-shi-hua.md)

## 第2章 内核中的锁

* [2.1. 互斥锁](di-2-zhang-nei-he-zhong-de-suo/2.1.-hu-chi-suo.md)
* [2.2. 共享的互斥锁](di-2-zhang-nei-he-zhong-de-suo/2.2.-gong-xiang-de-hu-chi-suo.md)
* [2.3. 原子保护变量](di-2-zhang-nei-he-zhong-de-suo/2.3.-yuan-zi-bao-hu-bian-liang.md)

## 第3章 内核对象

* [3.1. 术语](di-3-zhang-nei-he-dui-xiang/3.1.-shu-yu.md)
* [3.2. Kobj 操作](di-3-zhang-nei-he-dui-xiang/3.2.-kobj-cao-zuo.md)
* [3.3. 使用 Kobj](di-3-zhang-nei-he-dui-xiang/3.3.-shi-yong-kobj.md)

## 第4章 Jail 系统

* [4.1. 架构](di-4-zhang-jail-xi-tong/4.1.-jia-gou.md)
* [4.2. 限制条件](di-4-zhang-jail-xi-tong/4.2.-xian-zhi-tiao-jian.md)

## 第5章 SYSINIT 框架

* [5.1. 术语](di-5-zhang-sysinit-kuang-jia/5.1.-shu-yu.md)
* [5.2. SYSINIT 操作](di-5-zhang-sysinit-kuang-jia/5.2.-sysinit-cao-zuo.md)
* [5.3. 使用 SYSINIT](di-5-zhang-sysinit-kuang-jia/5.3.-shi-yong-sysinit.md)

## 第6章 TrustedBSD MAC 框架

* [6.1. MAC 文件版权](di-6-zhang-trustedbsd-mac-kuang-jia/6.1.-mac-wen-jian-ban-quan.md)
* [6.2. 内容提要](di-6-zhang-trustedbsd-mac-kuang-jia/6.2.-nei-rong-ti-yao.md)
* [6.3. 简介](di-6-zhang-trustedbsd-mac-kuang-jia/6.3.-jian-jie.md)
* [6.4. 策略背景](di-6-zhang-trustedbsd-mac-kuang-jia/6.4.-ce-lve-bei-jing.md)
* [6.5. MAC 框架的内核结构](di-6-zhang-trustedbsd-mac-kuang-jia/6.5.-mac-kuang-jia-de-nei-he-jie-gou.md)
* [6.6. MAC 策略架构](di-6-zhang-trustedbsd-mac-kuang-jia/6.6.-mac-ce-lve-jia-gou.md)
* [6.7. MAC 策略入口函数参考](di-6-zhang-trustedbsd-mac-kuang-jia/6.7.-mac-ce-lve-ru-kou-han-shu-can-kao.md)
* [6.8. 应用层体系架构](di-6-zhang-trustedbsd-mac-kuang-jia/6.8.-ying-yong-ceng-ti-xi-jia-gou.md)
* [6.9. 总结](di-6-zhang-trustedbsd-mac-kuang-jia/6.9.-zong-jie.md)

## 第7章 虚拟内存系统

* [7.1. 物理内存的管理——vm\_page\_t](di-7-zhang-xu-ni-nei-cun-xi-tong/7.1.-wu-li-nei-cun-de-guan-li-vmpaget.md)
* [7.2. 统一缓冲区缓存——vm\_object\_t](di-7-zhang-xu-ni-nei-cun-xi-tong/7.2.-tong-yi-huan-chong-qu-huan-cun-vmobjectt.md)
* [7.3. 文件系统 I/O——buf 结构体](di-7-zhang-xu-ni-nei-cun-xi-tong/7.3.-wen-jian-xi-tong-iobuf-jie-gou-ti.md)
* [7.4. 映射页表——vm\_map\_t、vm\_entry\_t](di-7-zhang-xu-ni-nei-cun-xi-tong/7.4.-ying-she-ye-biao-vmmaptvmentryt.md)
* [7.5. KVM 内存映射](di-7-zhang-xu-ni-nei-cun-xi-tong/7.5.-kvm-nei-cun-ying-she.md)
* [7.6. 调试 FreeBSD 的虚拟内存系统](di-7-zhang-xu-ni-nei-cun-xi-tong/7.6.-tiao-shi-freebsd-de-xu-ni-nei-cun-xi-tong.md)

## 第8章 SMPng 设计文档

* [8.1. 简介](di-8-zhang-smpng-she-ji-wen-dang/8.1.-jian-jie.md)
* [8.2. 基本工具与上锁的基础知识](di-8-zhang-smpng-she-ji-wen-dang/8.2.-ji-ben-gong-ju-yu-shang-suo-de-ji-chu-zhi-shi.md)
* [8.3. 一般架构和设计](di-8-zhang-smpng-she-ji-wen-dang/8.3.-yi-ban-jia-gou-he-she-ji.md)
* [8.4. 具体的锁定策略](di-8-zhang-smpng-she-ji-wen-dang/8.4.-ju-ti-de-suo-ding-ce-lve.md)
* [8.5. 实现说明](di-8-zhang-smpng-she-ji-wen-dang/8.5.-shi-xian-shuo-ming.md)
* [8.6. 其他话题](di-8-zhang-smpng-she-ji-wen-dang/8.6.-qi-ta-hua-ti.md)

***

* [第二部分 设备驱动程序](di-er-bu-fen-she-bei-qu-dong-cheng-xu.md)

## 第9章 编写 FreeBSD 设备驱动

* [9.1. 简介](di-9-zhang-bian-xie-freebsd-she-bei-qu-dong/9.1.-jian-jie.md)
* [9.2. 动态内核链接器工具——KLD](di-9-zhang-bian-xie-freebsd-she-bei-qu-dong/9.2.-dong-tai-nei-he-lian-jie-qi-gong-ju-kld.md)
* [9.4. 字符设备](di-9-zhang-bian-xie-freebsd-she-bei-qu-dong/9.4.-zi-fu-she-bei.md)
* [9.4. 块状设备（已不复存在）](di-9-zhang-bian-xie-freebsd-she-bei-qu-dong/9.4.-kuai-zhuang-she-bei-yi-bu-fu-cun-zai.md)
* [9.5. 网络驱动程序](di-9-zhang-bian-xie-freebsd-she-bei-qu-dong/9.5.-wang-luo-qu-dong-cheng-xu.md)

## 第10章 ISA 设备驱动程序

* [10.1. 内容提要](di-10-zhang-isa-she-bei-qu-dong-cheng-xu/10.1.-nei-rong-ti-yao.md)
* [10.2. 基本信息](di-10-zhang-isa-she-bei-qu-dong-cheng-xu/10.2.-ji-ben-xin-xi.md)
* [10.3. device\_t 指针](di-10-zhang-isa-she-bei-qu-dong-cheng-xu/10.3.-devicet-zhi-zhen.md)
* [10.4. 配置文件和自动配置期间的识别和探测顺序](di-10-zhang-isa-she-bei-qu-dong-cheng-xu/10.4.-pei-zhi-wen-jian-he-zi-dong-pei-zhi-qi-jian-de-shi-bie-he-tan-ce-shun-xu.md)
* [10.5. 资源](di-10-zhang-isa-she-bei-qu-dong-cheng-xu/10.5.-zi-yuan.md)
* [10.6. 总线内存映射](di-10-zhang-isa-she-bei-qu-dong-cheng-xu/10.6.-zong-xian-nei-cun-ying-she.md)
* [10.7. DMA](di-10-zhang-isa-she-bei-qu-dong-cheng-xu/10.7.-dma.md)
* [10.8. xxx\_isa\_probe](di-10-zhang-isa-she-bei-qu-dong-cheng-xu/10.8.-xxx\_isa\_probe.md)
* [10.9. xxx\_isa\_attach](di-10-zhang-isa-she-bei-qu-dong-cheng-xu/10.9.-xxx\_isa\_attach.md)
* [10.10. xxx\_isa\_detach](di-10-zhang-isa-she-bei-qu-dong-cheng-xu/10.10.-xxx\_isa\_detach.md)
* [10.11. xxx\_isa\_shutdown](di-10-zhang-isa-she-bei-qu-dong-cheng-xu/10.11.-xxx\_isa\_shutdown.md)
* [10.12. xxx\_intr](di-10-zhang-isa-she-bei-qu-dong-cheng-xu/10.12.-xxx\_intr.md)

## 第11章 PCI 设备

* [11.1. 探测与连接](di-11-zhang-pci-she-bei/11.1.-tan-ce-yu-lian-jie.md)
* [11.2. 总线资源](di-11-zhang-pci-she-bei/11.2.-zong-xian-zi-yuan.md)

## 第12章 通用访问方法 SCSI 控制器

* [12.1. 内容提要](di-12-zhang-tong-yong-fang-wen-fang-fa-scsi-kong-zhi-qi/12.1.-nei-rong-ti-yao.md)
* [12.2. 通用基础架构](di-12-zhang-tong-yong-fang-wen-fang-fa-scsi-kong-zhi-qi/12.2.-tong-yong-ji-chu-jia-gou.md)
* [12.3. 全局和模板](di-12-zhang-tong-yong-fang-wen-fang-fa-scsi-kong-zhi-qi/12.3.-quan-ju-he-mo-ban.md)
* [12.4. 设备配置： xxx\_attach](di-12-zhang-tong-yong-fang-wen-fang-fa-scsi-kong-zhi-qi/12.4.-she-bei-pei-zhi-xxxattach.md)
* [12.5. 处理 CAM 信息：xxx\_action](di-12-zhang-tong-yong-fang-wen-fang-fa-scsi-kong-zhi-qi/12.5.-chu-li-cam-xin-xi-xxxaction.md)
* [12.6. 轮询 xxx\_poll](di-12-zhang-tong-yong-fang-wen-fang-fa-scsi-kong-zhi-qi/12.6.-lun-xun-xxxpoll.md)
* [12.7. 异步事件](di-12-zhang-tong-yong-fang-wen-fang-fa-scsi-kong-zhi-qi/12.7.-yi-bu-shi-jian.md)
* [12.8. 中断](di-12-zhang-tong-yong-fang-wen-fang-fa-scsi-kong-zhi-qi/12.8.-zhong-duan.md)
* [12.9. 错误总结](di-12-zhang-tong-yong-fang-wen-fang-fa-scsi-kong-zhi-qi/12.9.-cuo-wu-zong-jie.md)
* [12.10. 超时处理](di-12-zhang-tong-yong-fang-wen-fang-fa-scsi-kong-zhi-qi/12.10.-chao-shi-chu-li.md)

## 第13章 USB 设备

* [13.1. 简介](di-13-zhang-usb-she-bei/13.1.-jian-jie.md)
* [13.2. 主机控制器](di-13-zhang-usb-she-bei/13.2.-zhu-ji-kong-zhi-qi.md)
* [13.3. USB 设备信息](di-13-zhang-usb-she-bei/13.3.-usb-she-bei-xin-xi.md)
* [13.4. 设备的探测和连接](di-13-zhang-usb-she-bei/13.4.-she-bei-de-tan-ce-he-lian-jie.md)
* [13.5. USB 驱动程序协议信息](di-13-zhang-usb-she-bei/13.5.-usb-qu-dong-cheng-xu-xie-yi-xin-xi.md)

## 第14章 Newbus

* [14.1. 设备驱动程序](di-14-zhang-newbus/14.1.-she-bei-qu-dong-cheng-xu.md)
* [14.2. Newbus 概览](di-14-zhang-newbus/14.2.-newbus-gai-lan.md)
* [14.3. Newbus API](di-14-zhang-newbus/14.3.-newbus-api.md)

## 第15章 声音子系统

* [15.1. 简介](di-15-zhang-sheng-yin-zi-xi-tong/15.1.-jian-jie.md)
* [15.2. 文件](di-15-zhang-sheng-yin-zi-xi-tong/15.2.-wen-jian.md)
* [15.3. 探测、连接等](di-15-zhang-sheng-yin-zi-xi-tong/15.3.-tan-ce-lian-jie-deng.md)
* [15.4. 接口](di-15-zhang-sheng-yin-zi-xi-tong/15.4.-jie-kou.md)

## 第16章 PC Card

* [16.1. 添加一个设备](di-16-zhang-pc-card/16.1.-tian-jia-yi-ge-she-bei.md)

***

* [第三部分 附录](di-san-bu-fen-fu-lu.md)
* [书目](shu-mu.md)
