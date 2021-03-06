## 2.0.0-alpha.11

### Features

  * 新增 [circularProgress](#/circularProgress) 组件
  * dropDownMenu, iconMenu, selectField, autoComplete 组件新增 `scroller` 属性
  * autoComplete 组件新增 `maxHeight` 属性
  * 更改所有表单组件 change 事件触发条件 (必须是因为用户行为导致value改变才触发)

### Bugs

  * 修复 pagination 修改 defaultPageSize 或者 pageSize 的时候不生效的问题
  * 修复 pagination 页码小于5个的时候显示不正常
  * 修复 dialog 中，两个action button，一个为 a，一个为 button 的话，样式显示问题
  * 修复 datePicker 组件格式化显示不完善的问题

## 2.0.0-alpha.10

### Features

  * 新增 [pagination](#/pagination) 组件

### Bugs

  * 修复 Text Field multiLine，如果带浮动标签，则容器高度不对
  * 在 slider 父级元素上加上定位属性会导致拖动定位异常
  * 修复 autoComplete 组件提示内容不显示的问题

## 2.0.0-alpha.9

### Features

  * 重构 slider 组件,内部不再使用 input[type=range]
  * bottomSheet, dialog, popover, popup 组件新增 open 参数（用于控制打开于关闭）, 新增 `show` (打开动画结束后)，`hide` (关闭动画结束后) 事件
  * drawer 新增 `show` (打开动画结束后)，`hide` (关闭动画结束后) 事件

### Bugs

  * 修复 menuItem 文本过长显示重叠
  * 修复 Text Field multiLine模式下 rows & rowsMax 设置无效的问题
  * 修复 drawer 的 open=true, docked=false 没有遮盖层
  * 修复 tabs 组件 z-index 值过低的问题
  * 修复 popover 在 dialog 组件中使用定位出错的问题
  * 修复 dialog 嵌套使用时没有遮盖上一个 dialog 的问题

## 2.0.0-alpha.8

### Features

  * bottomNavItem 增加 `default` slot
  * iconMenu 增加 `icon` slot
  * flexboxItem 增加 `grow` 和 `shrink` 属性, `basis` 替换 `span`

### Bugs

  * 修改 tbody 在 selectedRow 的时候全选时重复 emit 事件给父组件
  * 修复slider min参数设置后显示于实际值不一致的问题
  * 优化部分组件的动画效果
  * 修复textField float效果在 `type=number` 时的bug

## 2.0.0-alpha.7

### Features

  * table 组件增加 `enableSelectAll` 属性
  * tr 组件增加 `selected` 属性，控制tr选择

### Bugs

  * 修复 selectField无法选择 value 为 0 的项
  * 修复 radio,checkbox,switch 鼠标移出后波纹不消失的问题
  * 修复 mu-text-field设置type为number后，maxLength显示错误

## 2.0.0-alpha.5

### Features

  * bottomNavItem 新增 `href` 属性
  * tab 新增 `href`, `disabled` 属性
  * menuItem 增加 `click` 事件

### Bugs

  * 修复 textField 提示文字可以选择的问题
  * 修复 appbar 标题溢出不显示的问题
  * 修复 badge 组件 `color` 属性无效

## 2.0.0-alpha.4

### Bugs

  * 修复多行文本光标与提示文字不对齐
  * 修复drawer组件销毁后overlay仍存在的问题
  * 修复drawer docked切换后zIndex没有重置的问题
  * 修复table选择后再取消以后全选框仍选中的问题
  * 修改tooltip错位的问题

## 2.0.0-alpha.3

### Bugs

  * 修复 refreshControl 和波纹点击冲突的问题
  * 修复对 CommonJs 规范的支持不友好的问题
  * 修复 menu 组件嵌套点击时会报错

## 2.0.0-alpha.2

### Features

  * 更改组件变量命名和主题文件中的使用
  * 增加 carbon, dark, teal 主题

### Bugs

  * 修复 slider 组件在 ios 设备上显示出错的bug

## 2.0.0-alpha.1

### Features

  * Add 38 Material Design Components
  * Add 7 others components
