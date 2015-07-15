# Android-Decompiler
# decompile the resuource
java -jar apktool.jar d test.apk
# decompile the src to jar
sh dex2jar/d2j-dex2jar.sh test.apk
# view the jar 
java -jar jd-gui.jar test-dex2jar.jar

