# BarLib-Android
A simple Android library project for bring the bar graph

# How to implement this library to Android project

To get a Git project into your build:

Step 1. Add the JitPack repository to your build file

# gradle
Add it in your root build.gradle at the end of repositories:

<code>allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }			
		}
	}</code>
	

  
  Step 2. Add the dependency
  
  <code>dependencies {
	        compile 'com.github.Sridhar-Studio:BarLib-Android:0.1.0'
	}</code>
  
  Note: For other builds like maven,.. click this icon [![](https://jitpack.io/v/Sridhar-Studio/BarLib-Android.svg)](https://jitpack.io/#Sridhar-Studio/BarLib-Android)
  
  Afer Sync this Library project into your reference project, Open the .xml file you want. 
  For example, i take <i> activity_main.xml</i>. In that simple write the code as given below:
  
  <com.sridhar.bar1.BarAnimate
        android:layout_width="match_parent"
        android:layout_height="400dp" />
        
 # Run the program see the bar graph.
  you can give n counts to get the bar graph dynamically by clciking the submit button.
  
  # Thanks :)

