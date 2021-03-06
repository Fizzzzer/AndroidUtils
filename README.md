# AndroidUtils
整理项目常用的各种工具类

[用法说明](https://github.com/lvfaqiang/AndroidUtils/blob/master/Usage.md)

[历史版本](https://github.com/lvfaqiang/AndroidUtils/tags)

[功能清单](https://github.com/lvfaqiang/AndroidUtils/blob/master/FUNLIST.md)

[更新日志](https://github.com/lvfaqiang/AndroidUtils/blob/master/CHANGELOG.md)

## 资源文件
[dimens.xml](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/res/values/dimens.xml) - 尺寸单位（1-375dp , 1-50sp , 1-375px）

[colors.xml](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/res/values/colors.xml) - 整理了几个项目所用的颜色值（c_xxxxxx : 表示 完整颜色值 , color_ab : 表示 ababab 类型颜色值）

## 工具类列表：
### A
[AndroidUtil](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/AndroidUtil.java) - Android设备工具类(获取设备号，安装 Apk, 是否安装了某应用..)

[AppManager.java](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/AppManager.java) - 项目中的 Activity 管理类

[AppUtil.java](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/AppManager.java) - 应用相关工具类（获取版本号，对比版本，名称，图标等）
### B
[BottomPopwin.java](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/BottomPopwin.java) - 底部弹出框工具类
### C
[CheckUtil.java](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/CheckUtil.java) - 相关检查（Ps: checkNotNull 如果是 null 则抛出异常）
### D
[DateUtil](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/DateUtil.java) - 日期工具类

[DialogUtil.java](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/DialogUtil.java) - 创建 Dialog 工具类

[DPUtil.java](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/DPUtil.java) - 根据屏幕分辨率像素和 dp 互转，获取顶部状态栏高度
### E
[EmptyUtil.java](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/EmptyUtil.java) - 对象空判断工具类

[EncodeUtil](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/EncodeUtil.java) - 字符串 MD5, SHA1 等加密
### F
[FragmentUtil](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/FragmentUtil.java) - Fragment 控制类，目前主要用于切换界面中的多个 Fragment 显示
### I
[IntentUtil](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/IntentUtil.java) - Intent 跳转控制类
### K
[KeyBoardUtil](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/KeyBoardUtil.java) - 键盘控制类
### L
[LvLog.java](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/LvLog.java) - 打印 Log 工具类
### N
[NumberUtil](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/NumberUtil.java) - 数字保留小数相关
### P
[PopupWindowUtil.java](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/PopupWindowUtil.java) - 快速创建 PopupWindow
### S
[ScreenUtil.java](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/ScreenUtil.java) - 获取屏幕尺寸工具类

[SpUtil.java](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/SpUtil.java) - SharedPreference工具类

[StringUtil](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/StringUtil.java) - 意在整理一些常用 String 相关处理方法。后续逐步增加
### T
[ToastUtil.java](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/ToastUtil.java) - Toast 工具类
### V
[V.java](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/V.java) - 简化 findViewById ,显示明文密码，点击事件等 方法

[ViewHolder.java](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/ViewHolder.java) - 简化 ListView，GridView 的ViewHolder [Blog地址](http://blog.csdn.net/lv_fq/article/details/51913515)



## 功能整理
[DownloadDialog](https://github.com/lvfaqiang/AndroidUtils/blob/master/library/src/main/java/com/lvfq/library/utils/DownloadDialog.java) - 版本更新提示
### 以上纯属个人项目工具类整理。
