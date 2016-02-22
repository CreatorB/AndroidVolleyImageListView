# Android Volley Image ListView

Just a Little explanations How to parse json image to listview using volley. This code writen just for answer some questions on stackoverflow about how to passing some json string to detail activity.

This repo based on : [Androidhive](http://www.androidhive.info/2012/02/android-custom-listview-with-image-and-text)

## Usage

### for Maven

``` xml
<dependency>
    <groupId>com.mcxiaoke.volley</groupId>
    <artifactId>library</artifactId>
    <version>1.0.19</version>
</dependency>
```


### for Gradle

``` groovy
compile 'com.mcxiaoke.volley:library:1.0.19'
```


### Using SNAPSHOT

add this to repositories section in build.gradle

``` groovy
repositories {
        maven { url 'https://oss.sonatype.org/content/repositories/snapshots' }
    }
```

add this to dependencies section in build.gradle

```groovy
compile 'com.mcxiaoke.volley:library:1.0.19-SNAPSHOT'
```

## Changelog
* **Today**
    * Just add a little code, like on click to detail info
    * That's mean passing some json string from main to detail
