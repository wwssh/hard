做存储，iscsi是必然会听到的词，比如常用的命令iscsiadm，今天简单了解下。

#### 什么是iSCSI
iSCSI来源于SCSI，SCSI，wikipedia上看的话，最早1986年就开始指定SCSI标准。而iSCSI，在2003年才成为标准。

#### 解决什么问题
通过互联网来解决数据传输问题，SCSI解决的是数据传输，iSCSI主要的特点是两个，一是通过互联网，而是解决存储数据。
相比SCSI，iSCSI主要针对存储相关的数据传输，它基于SCSI-3来解决存储数据传输。

#### iSCSI的 initiator 和 target
用iscsiadm来管理initiator，包括登入登出target，错误处理，连接。
