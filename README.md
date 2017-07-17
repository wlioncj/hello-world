# hello-world
Just another repository

Edit hello-world
C++单向链表中的一句是什么意思
/** * Definition for singly-linked list. 
* struct ListNode { 
*     int val; 
*     ListNode *next; 
*     ListNode(int x) : val(x), next(NULL) {}
* };
*/
这其中ListNode(int x) : val(x), next(NULL) {}，这句是什么意思啊？
其实这个是结构体的构造函数，与类的构造函数相同，冒号后面的是初始化列表，也就是给成员val初始化为传入的参数x，next初始化为NULL
