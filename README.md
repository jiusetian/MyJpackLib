# MyJpackLib
测试发布JitPack

第一步：Add it in your root build.gradle at the end of repositories:
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  
  第二步：Add the dependency
  dependencies {
	        implementation 'com.github.jiusetian:MyJpackLib:Tag'
	}
  
