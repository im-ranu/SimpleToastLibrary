# SimpleToastLibrary
Implementation Simple Toast in your Application


# Step to integrate

Add it in your root build.gradle at the end of repositories:

<p>allprojects {<br>
<emsp>		repositories {<br>
			...
			maven { url 'https://jitpack.io' }
		}
	}
 </p> 
  
 # Add the dependency
  
  dependencies {
	        implementation 'com.github.im-ranu:SimpleToastLibrary:Tag'
	}


# How to use it.

SimpleToast.s(Context context, String Message);
