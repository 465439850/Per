# Per
正则表达式

[\u0391-\uFFE5]匹配中文以外的字符

php:
/^[\x{4e00}-\x{9fa5}]+$/u  中文字符 utf8下的

preg_match("/^[".chr(0xa1)."-".chr(0xff)."A-Za-z0-9_]+$/"$str); //GB2312汉字字母数字下划线正则表达式  gbk的

/^[A-Z]{1}[a-zA-Z_0-9]{5}$/ 车牌号
