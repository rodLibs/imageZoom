<img src="zoom.gif" height="550" width="430">


# Sample Project
You can download the latest sample APK from this repo here: https://github.com/rodLibs/imageZoom/blob/master/sample/sample.apk
</br>
</br>


# Requirements
imageZoom requires at minimum Android 4.0 (API level 14).
</br>
</br>


# Gradle Dependency

## Repository
The Gradle dependency is available via maven. maven is the default Maven repository used by Android Studio.
</br>

## Add repository
<pre><code>
repositories {
    maven { url 'https://jitpack.io' }
}
</code></pre>



## Add dependency

#### Gradle:
<pre><code>
dependencies {
    implementation 'com.github.rodLibs:imageZoom:master-SNAPSHOT'
}
</code></pre>
</br>


# Simple usage
#### .java
<pre><code>
 ZoomImageView imgZoom = (ZoomImageView) findViewById(R.id.imageZoom);
</code></pre>

<pre><code>
 imgZoom.setImageBitmap(myBitmap);
</code></pre>
###### Or
<pre><code>
 imgZoom.setImageResource(R.drawable.myImage);
</code></pre>
</br>


#### .kt
<pre><code>
val imgZoom = findViewById< ZoomImageView >(R.id.imageZoom)
</code></pre>

<pre><code>
 imgZoom.setImageBitmap(myBitmap);
</code></pre>
###### Or
<pre><code>
imgZoom.setImageResource(R.drawable.myImage);
</code></pre>
</br>


#### .xml
```xml
 <com.github.rodlibs.libimagezoom.ZoomImageView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:id="@+id/imageZoom" />
```
</br>
</br>



# License
<pre><code>
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
</code></pre>
