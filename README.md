crosswalk 23.53.589.4 
xwalkview 解决打开没有 ssl 证书的 https 网址可能会报 request was denied for security 、ERR_SECURITY_RESPONSE等异常
支持 armeabi-v7a 和 x86

 ```
  allprojects {
  	repositories {
		...
		//github or gitee
		maven { url "https://raw.githubusercontent.com/louisgeek/xwalk_core_library/master" }
		//maven { url "https://gitee.com/louisgeek/xwalk_core_library/raw/master" }
        
  	}
  }
  ```
  
  ```
  dependencies {
         implementation 'com.github.louisgeek:xwalk_core_library:23.53.589.4'
  }
  ```