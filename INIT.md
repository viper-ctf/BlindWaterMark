> 由于 python3 的高版本不再支持 random.shuffle 的第二个参数，因此只能选择 python2 版本

### 使用 python2 virtualenv

- https://stackoverflow.com/questions/65685217/how-to-create-a-python-2-7-virtual-environment-using-python-3-7

安装后需要手动从
/Library/Frameworks/Python.framework/Versions/2.7/bin/virtualenv
来初始化

### mamatplotlib 报错 backend 不可用

- https://stackoverflow.com/questions/41370779/using-matplotlib-with-tkagg-or-qt5agg-backend-on-4k-screen

可以使用 TkAgg作为后端

```
# ~/.matplotlib/matplotlibrc
backend: TkAgg
```
