
## breeze-date

这是一个基于原生JavaScript开发的日期插件

## 版本

1.0.0

## 安装

使用npm下载源文件


```
npm install breeze-date --save
```

直接使用script引用

```js
<script src="../dist/breeze-date-1.0.0.min.js"></script>
```

## 使用

```js
<script type="text/javascript">
      var config1 = {
        target: "picker-date1",
        type: "date",
        format: 'YYYY-MM-DD',
        currentValue: '1993-11-28',
        valueRange: ['1900-06-10', '2018-03-21'],
        ensureCallback: function(value) {
          console.log(value);
        }
      };
      new BreezeDate(config1);
    </script>
```

## 参数
```
```

|        参数       |   类型   | 默认值  |             说明             |
|-------------------|----------|----------|-------------------------------------|
| target              | String    | “picker”       | 目标元素id          |
| currentValue             | Number or String   | 0      | 当前日期或年龄 |
| valueRange       | Number or String   | [0, 100]   | 日期或年龄范围          |
| ensureCallback       | Function   | 空函数   | 点击确定之后执行回调函数          |

## 演示

[demo](https://breeze55.github.io/breeze-date/example/index.html)

```
如果你感觉好用，欢迎给我打赏
```
![avatar](https://raw.githubusercontent.com/breeze55/static/master/breeze.png)

## License
[MIT](https://github.com/breeze55/breeze-date/blob/master/LICENSE)
