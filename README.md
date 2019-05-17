# algorithm_js_note

## 1. 链表小技巧
### 1）fast和slow
      a. fast = fast.next.next;    slow = slow.next;
         找到链表中间node，判断有无环(141)，判断环的起点(142)
      b. for (int i = 0; i < n; ++i) fast = fast->next;
         fast和slow相隔n个node，删除倒数n个node(19)
      
      在前面的查找循环示例中，假设我们每次移动较快的指针 2 步，每次移动较慢的指针 1 步。如果没有循环，快指针需要 N/2 次才能到达链表的末尾，其中 N 是链表的长度；如果存在循环，则快指针需要 M 次才能赶上慢指针，其中 M 是列表中循环的长度。
     
