# GenerateJSON
Generates JSON Files Needed For Minecraft 1.8 Mods

# For Windows Users
Make sure your Java version is at least 1.8.0_40. To check open up the command prompt and type
```
java -version
```
If your Java version is not up to date, try updating at <a href="http://www.oracle.com/technetwork/java/javase/downloads/index.html">Oracle's website</a>.

Copy GenerateJSON.class to any location you wish the output files to be located at.

Hold SHIFT And RMB, select "Open Command Window Here"
<hr>
In order to create block files type
```
java GenerateJSON block
```
Enter the ModID and block name (same name used to create the block object).

Your json files will be created and sorted inside an assets directory.
<hr>
In order to create item files type
```
java GenerateJSON item
```
Enter the ModID and item name (same name used to create the item object).

Your json files will be created and sorted inside an assets directory.
