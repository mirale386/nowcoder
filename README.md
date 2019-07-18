# nowcoder
## 剑指offer
### 19-7-13
- 面试题3：二维数组中的查找  
注1：注意控制循环开始条件  
注2：注意数组下标-1，否则数组越界

- 面试题4：替换空格 
注1：‘’单引号是字符，“”双引号是字符串  
注2：cin不可以吃空格  
注3：cin.get吃一行，不能剔除前面输入的回车

- 面试题5：从未到头打印链表 


### 19-7-15
- 面试题6：重建二叉树（根据前序中序序列）  
注1：举例解决  
注2：树的前序序列开头是根结点，中序序列可以找到左右子树，后序序列结尾是根节点

- 面试题7：用两个栈实现队列  
注：因为push和pop操作每次都是将一个栈倒入一个栈操作，故不用事先清空栈。

- 面试题8：旋转数组的最小数字  
注（bug修复）：增加了对l,mid,r三者相等的判断,一旦相等,最小值就不知道落在哪个区间,得使用遍历法

### 19-7-17
- 面试题9：斐波那契数列
注：递归浪费时间空间，观察斐波那契数列的规律可以用循环解决，而不需要用栈转换递归。  
  - 应用：  
  1.青蛙跳台阶  
    注：n>2时，青蛙第一次跳一个台阶，剩余n-1个台阶就是f(n-1);第一次跳两个台阶，剩余n-2个台阶就是f(n-2)，所以总的f(n)=f(n-1)+f(n-2)  
  2.变态跳台阶  
    注：每次可以跳最多n个台阶，就是数学问题中的排列次数问题！   
  3.小方块填充大方块  
  - 注：此类问题举例可发现其规律，数学归纳法!  
  
- 面试题10：2进制中1的个数  
注1：直接进行右移位判断，负数会导致死循环，因为负数首位始终为1！  
注2：可以改进左移1进行判断！！  
注3：利用数的规律n个1循环n次，n&(n-1)！  

- 面试题11：数值的整数次方  
注1：尽量避免使用很多if判断模块，尽量合并成if-else
注2：怎样非递归实现？移位次方数。(及计算2、4、6、8次方，很巧妙！！！）

