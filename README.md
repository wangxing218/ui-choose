# ui-choose 选择插件
基于jquery的选择插件，可用于选项不太多的select、radio、checkbox等，提升用户体验！

##[demo](http://wangxing218.github.io/ui-choose/test/demo.html)


## 基于jquery,使用非常方便！
```javascript
// 将所有.ui-choose实例化
$('.ui-choose').ui_choose();

// uc_01 ul 单选
var uc_01 = $('#uc_01').data('ui-choose'); // 取回已实例化的对象
uc_01.click = function(index, item) {
    console.log('click', index, item.text())
}
uc_01.change = function(index, item) {
    console.log('change', index, item.text())
}

// uc_02 select 单选
var uc_02 = $('#uc_02').data('ui-choose');
uc_02.click = function(value, item) {
    console.log('click', value);
};
uc_02.change = function(value, item) {
    console.log('change', value);
};

// uc_03 ul 多选
var uc_03 = $('#uc_03').data('ui-choose');
uc_03.click = function(index, item) {
    console.log('click', index);
};
uc_03.change = function(index, item) {
    console.log('change', index);
};

// uc_04 select 多选
var uc_04 = $('#uc_04').ui_choose();
uc_04.click = function(value, item) {
    console.log('click', value);
};
uc_04.change = function(value, item) {
    console.log('change', value);
};

```


#兼容性
IE8+, Chrome, Firefox, Edge, 360, Sougou 等主流浏览器;

##作者
###网站： [www.boyxing.com](http://www.boyxing.com/)
### QQ ： [1263996779](http://wpa.qq.com/msgrd?v=3&uin=1263996779&site=qq&menu=yes)

