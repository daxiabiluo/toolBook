# Modbus slave界面操作

```
   modbus_slave协议是一个上传协议，通过id和采集协议中的id进行绑定，达到采集-上传(更新modbus地址数据)的需求。
```

### 1.配置modbus slave通讯类型

```
    在Modbus上传服务器配置一栏中使用开关按钮选择TCP或者RTU，如果选择RTU，还需要选择使用的com口，配置之后点击“保存”按钮。
```

### 2.modbus slave配置

```
    点击界面左侧的“上传协议配置”中的“modbus slave配置”，会自动刷新出采集协议中配置的所有采集项的id，可以通过双击需要修改
的表格行进行数据的修改，之后点击“保存按钮”；也可以点击“导出配置”，把modbus slave表格导出到本地电脑当中，修改之后通过“导入
配置”导入到表格当中。
```

#### 注：每次更改采集协议中的id项之后，需要点击modbus slave界面的“刷新”按钮才能在界面中刷新出

#### 新更改的id项。


