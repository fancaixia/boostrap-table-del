### boostrap table  删除行数据
```javascript
$(ele).bootstrapTable('remove',{

field:"id",            //对应字段必须为表格列对应字段（表格上没初始化的字段，删除失败
                       如果不想显示此列可以visible：false隐藏）

values:[parseInt(rowid)]                          // 切记将 values 对应数据转为数值

})
```

#####   Bootstrap Table 中文文档（完整翻译版）  
 
```
  http://blog.csdn.net/rickiyeat/article/details/56483577
```
