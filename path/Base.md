## func Base(path string) string

�����б�

- path ��ʾ��Ҫȡ·�����ַ��� 


����ֵ��

- ����string

����˵����

���������Ҫ�������������һ��Ԫ�ص�·��,
		1.���·��Ϊ�շ���.
	  2.���·����б�����,����/

����ʵ����

package main

import (
	"fmt"
	"path"
)

func main() {
	fmt.Println(path.Base("/a/b"))
	fmt.Println(path.Base(""))
	fmt.Println(path.Base("////"))
}
