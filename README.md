# UTF-8toGB2312
分享一个UTF-8转GB2312函数(UTF-8toGB2312)

思路是UTF-8->Unicode->GB2312

cp936.h是Unicode->GB2312的字符表

void Utf8ToGb2312(const char* utf8, int len,u16* gbArray);

参数：

- utf8是uft-8的字符串
- len是uft-8的字符串长度
- gbArray是返回u16的字符编码数组

具体使用可参考代码的主函数main
