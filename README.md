Instruction:
This tool can convert gbk file to utf8 format and vice versa. Default mode is gbk to utf8. You may find the example as followed.
Accepted parameters:
-r recursively traverse sourcefolder to generate in targetfolder
-m choose mode, gt8 or 8tg, gbk to utf8 or utf8 to gbk.
-h show this help info
-V version
使用说明:
本工具可以gbk和utf8文本互相转换，默认使用gbk转utf8模式。
可单文件/文件夹递归转换。
样例：
`rgbkutf8.exe sourcegbk.sql targetutf8.sql`  gbk转utf8模式[默认]-单个文件

`rgbkutf8.exe -r sourcegbkfolder targetutf8folder`  gbk转utf8模式[默认]-文件夹

`rgbkutf8.exe -m 8tg sourceutf8.sql targetgbk.sql`  utf8转gbk模式-单个文件

`rgbkutf8.exe -r -m 8tg sourceutf8folder targetgbkfolder`  utf8转gbk模式-文件夹
接受参数：
-r 递归转换
-m 转换模式，gt8表示gbk转utf8，8tg表示utf8转gbk
-h 显示帮助信息
-V 显示版本信息
