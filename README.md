# zksync-info

钱包地址数据监控

## 使用方式

> 在同级目录下创建 **wallet.py** 文件, 格式如:

```
ZKSADDRESSLIST = [
    address1,
    address2,
    address3,
    ....
]
```

> 在终端执行(默认在终端打印结果)：
```
python zksync.py
```

> zksync.py接收三个参数:
```
'-idx', type=int, default=0, 可以查询指定的钱包地址
'-save', type=str2bool, default=False, 保存到Excel和-usd_pd一起使用
'-use_pd', type=str2bool, default=False, 保存到Excel和-save一起使用
```

> 使用示例（将结果保存到Excel中）：
```bash
python zksync.py -use_pd y -save y
```
