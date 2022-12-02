# Image Compressor Library
Compressor is a lightweight and powerful android image compression library. Compressor will allow you to compress large photos into smaller sized photos with very less or negligible loss in quality of the image.
# Gradle
Step 1. Add it in your root build.gradle at the end of repositories:

allprojects {
		
    repositories {
			
              ...
			maven { url 'https://jitpack.io' }
		}
	}
  
Step 2. Add it in your module build.gradle:

dependencies {

      implementation 'com.github.xswapsx:ImageCompressorLibrary:ImageCompressor'

}

# Let's compress the image size!
            
    val compressedImagePath = ImageCompressor.compressImage("Your file's absolute path")
    
   # desclaimer: 
        This library will overwrite the original file with the compressed file.
