
非本人创作，只是修改了一些东西，原作者不知道是哪位了

# fslect  依赖jquery
select下拉框，支持搜索，多选

#用法
$("id").attr("multiple","multiple").fSelect();
#动态多次加载
$("id").attr("multiple","multiple").fSelect("reload");或者$("id").empty().attr("multiple","multiple").fSelect("reload",{showSearch:false,placeholder:"三级公司"});
#搜索框和下方多选按钮控制
$("id").attr("multiple","multiple").fSelect({showSearch: true,showButton:true});
#主要参数
placeholder:  '---请选择--- ',//占位符，默认显示什么
numDisplayed: 100,//设置页面上可以显示几个选项（超出这个数量将会显示选择了n项）
overflowText: '选择了{n}项',//超出这个数量将会显示"选择了n项"
searchText: '搜索',//搜索框中占位符显示什么字
showSearch: true,//是否显示搜索框
showButton:true //是否显示多选按钮

##使用时会默认选择第一个，尽可能第一个为空
#获取选择的值与原select一致，$("id").val()即可


推荐一个牛逼的多选 https://gitee.com/maplemei/xm-select
