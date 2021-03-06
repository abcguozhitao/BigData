Linux du命令 也是磁盘相关的非常有用的命令，用于显示目录或文件的大小。
## du命令格式
````
du [OPTION]... [FILE]...
或
du [OPTION]... --files0-from=F
````
## du命令常用的参数
````
-a或-all 显示目录中个别文件的大小。 

-b或-bytes 显示目录或文件大小时，以byte为单位。 

-c或--total 除了显示个别目录或文件的大小外，同时也显示所有目录或文件的总和。 

-D或--dereference-args 显示指定符号连接的源文件大小。 

-h或--human-readable 以K，M，G为单位，提高信息的可读性。 

-H或--si 与-h参数相同，但是K，M，G是以1000为换算单位。 

-k或--kilobytes 以1024 bytes为单位。 

-l或--count-links 重复计算硬件连接的文件。 

-L<符号连接>或--dereference<符号连接> 显示选项中所指定符号连接的源文件大小。 

-m或--megabytes 以1MB为单位。 

-s或--summarize 仅显示总计。 

-S或--separate-dirs 显示个别目录的大小时，并不含其子目录的大小。 

-x或--one-file-xystem 以一开始处理时的文件系统为准，若遇上其它不同的文件系统目录则略过。 

-X<文件>或--exclude-from=<文件> 在<文件>指定目录或文件。 

--exclude=<目录或文件> 略过指定的目录或文件。 

--max-depth=<目录层数> 超过指定层数的目录后，予以忽略。 

--help 显示帮助。 

--version 显示版本信息。
````
## du命令 应用实例
* 1、查看目录或文件所占的空间
````

````
* 2、查看某文件的大小
````

````
* 3、查看某目录大小
````

````
* 4、只显示总和的大小
````

````
* 5、以易读方式展示
````

````
* 6、文件和目录都显示
````

````
* 7、只显示一层子目录所占空间
````

````
