

***【写在前面】***
　　<font color="blue">这是现在网上流传的一套关于M皇后问题的构造法公式，但是这套公式是怎么得来的，却鲜有人知。
而文本会详细阐述这套公式的推导过程：</font>

对于 $m \geq 4$ 的 **m皇后** 问题：
　　若 $m \bmod 6 \neq 2$ 且 $m \bmod 6 \neq 3$ ，则可通过（A1）或（A2）导出解序列。
　　若 $m \bmod 6 = 2$ 或 $m \bmod 6 = 3$ ，则可通过（B1）或（B2）或（B3）或（B4）导出解序列。
　　其中当 $m$ 是偶数时, $n=\dfrac{m}{2}$ ；当 $m$ 是奇数时 $n=\dfrac{m-1}{2}$ ，

$
\small{
\begin{cases}
\text{A1-m是偶数: }\[2,4,6,8,...,m\],\[1,3,5,7,...,m-1\] \\\
\text{A2-m是奇数: }\[2,4,6,8,...,m-1\],\[1,3,5,7,...,m-2\],\[m\] \\\
\text{B1-m偶n偶: } \\\
 \quad \[n,n+2,...,m\],\[2,4,6,...,n-2\],\[n+3,n+5,...,m-1\],\[1,3,5,...,n+1\] \\\
\text{B2-m偶n奇: } \\\
 \quad \[n,n+2,...,m-1\],\[1,3,5,...,n-2\],\[n+3,n+5,...,m\],\[2,4,6,...,n+1\] \\\
\text{B3-m奇n偶: } \\\
 \quad \[n,n+2,...,m-1\],\[2,4,6,...,n-2\],\[n+3,n+5,...,m-2\],\[1,3,5,...,n+1\],\[m\] \\\
\text{B4-m奇n奇: } \\\
 \quad \[n,n+2,...,m-2\],\[1,3,5,...,n-2\],\[n+3,n+5,...,m-1\],\[2,4,6,...,n+1\],\[m\]
\end{cases}
}
$

------------
