# algorithm_js_note

## 1. 链表小技巧
### 1）fast和slow
      a. fast = fast.next.next;    slow = slow.next;
         找到链表中间node，判断有无环(141)，判断环的起点(142)
      b. for (int i = 0; i < n; ++i) fast = fast->next;
         fast和slow相隔n个node，删除倒数n个node(19)
