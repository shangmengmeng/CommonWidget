 **

### 欢迎使用CommonWidget(仅支持androidx)

添加依赖：

```
//根目录
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
//依赖
dependencies {
	       implementation 'com.github.shangmengmeng:CommonWidget:1.0'
	}
```


** 
### ReadMoreTextView 的基本使用方法：


```
 <com.star.commonwidgetlib.ReadMoreTextView
        android:id="@+id/text1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:trimCollapsedText="更多"
        app:trimExpandedText="收起"
        app:colorClickableText="#00b7ee"
        app:trimLines ="7"
        app:trimMode="trimModeLine"
        />
```


