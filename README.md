# ArafatLog

Add it in your root build.gradle at the end of repositories:

```
allprojects {
		repositories {
			maven { url 'https://jitpack.io' }
		}
	}
```

Step 2. Add the dependency

```
	dependencies {
	        implementation 'com.github.amiarafat:ArafatLog:0.0.1'
	}
```	

After adding this library now you can show/hide your log files with this library

#To set a log
```
 ArafatLog.d("d::","Debug");
 ArafatLog.e("e::","Error");
 ArafatLog.i("i::","Info");
 ArafatLog.v("v::","Verbose");
 ArafatLog.w("w::","Warn");
```
#To set a log show/hide

```
 ArafatLog.setLogFalse();
 ArafatLog.setLogTrue();
 ```
