To get a Git project into your build:

Step 1. Add the JitPack repository to your build file

gradle | maven | sbt | leiningen
Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
		
			maven { url 'https://jitpack.io' }
		}
	}
Step 2. Add the dependency

	dependencies {
	         implementation 'com.github.hgnis:mToast:1.0'
	}
	
[![](https://jitpack.io/v/hgnis/mToast.svg)](https://jitpack.io/#hgnis/mToast)


How to use :
 mToast.checker(this);
 mToast.error(this); 
 mToast.success(this); 
 mToast.Show(this,Message);
 mToast.errorMessage(this,Message); 
 mToast.successMessage(this,Message); 
 mToast.custom(this,Message,BackgroundColor,textColor);
