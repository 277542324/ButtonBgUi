# ButtonBgUi用法以及说明

### XML属性说明

|方法名             |用法|
|-------------     |:-------------:|
| strokeColor      | 默认边框的颜色          |
| selectStrokeColor| 选中边框的颜色          |
| pressedColor     | 选中的背景色            |
| defaultColor     | 默认的背景色            |
| isRipple         | 是否设置水波纹效果       |
| parameter        | 颜色变亮或变浅参数默认0.2|
| strokeWidth      | 边框的宽度             |
| raoundRadius     | 圆角                   |
| topLeftRadius    | 左上角圆角             |
| topRightRadius   | 右上角圆角             |
| bottomLeftRadius | 左下角圆角             |
| bottomRightRadius| 右下角圆角             |
### java调用
#### `setDefaultColor需填入两个颜色id,如背景色与边框色相同，都填入一种颜色即可。setDefaultColor此方法只能动态设置strokeColor、defaultColor，如果在Java中调用则在XML文件不要填入“strokeColor”、“defaultColor”，否则会颜色冲突。`
