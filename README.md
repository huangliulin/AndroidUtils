# AndroidUtils
Android-Utils 安卓常用工具集合

###添加依赖
    repositories {  
        maven { url "https://jitpack.io" }  
    }  
    dependencies {  
        compile 'com.github.huangliulin:AndroidUtils:1.0.2'  
    }
  

Utils工具类：
* Log日志功能，设置Debug模式后打印日志
* 屏幕信息相关功能，可获取屏幕宽高、状态栏高度和导航栏高度
* 提供dp和px转换的功能
* 显示隐藏输入法
* 检查网络是否可用
* 获取App版本号和版本名
* 加密相关（暂只提供MD5加密）
* 字符串操作相关，判断和正则匹配
