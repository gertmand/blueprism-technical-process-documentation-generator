# Blueprism Techincal Documentation Generator

Application is developed in C# (.Net Core Console Application). Application will generate a technical document like BluePrism does with the object.

## Installation

 - Download the ZIP file and extract it to the folder
 - Open up the folder, where "generate.exe" file is located
 - Open command line (cmd)
 - Type:
```sh
generate filePath -c false -d 1
```

```sh
generate "C:\Users\ComputerName\Desktop\myprocess.bpprocess" -c false -d 2.1
```

-c (condition - optionl) is for post- or preconditions. True - All conditions will be documented, even if they are "None". False - Hide all empty/None conditions. Default: **false**

-d (documentNo - optionl) is for starting number of process subpages. For example, if -d **1**, then the first number will be **1**.1, **1**.2, **1**.3. Default: 1

To copy the file path, simply hold shift and right click on the file + Copy As Path

Can only convert **.bpprocess** files