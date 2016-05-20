# mathematical_neuroscience
Mathematical Neuroscience Course Materials

    git clone "https://github.com/date333cs/mathematical_neuroscience"


### Associative Memory

- Purpose: reproduce Fig.1 and Fig.2 of Amari & Maginu (1988).

- an example of memory allocation:  [mn_test.c](mn_test.c)
- templates: [mn_asm000.c](mn_asm000.c), [mn_asm001.c](mn_asm002.c), [mn_asm002.c](mn_asm002.c)
- for gnuplot [gp001](gp001)
- data structure (n neurons, m memory patterns, i,j=0,...,n-1, a=0,...,m-1)
 - int x[i] :  current state
 - int ux[i] : next state 
 - double w[i][j] : connection weights
 - int p[a][i] : memory items

### �����ȿ�����ǥ롧 Kohonen �μ����ȿ����ޥåס�Self-organizaing MAP��

- Ǻ�ޤ�������ξ���Ĥ��롩

 - �Ȥꤢ����ư�����Τ��������Υ�ǥ��Ĥ��뤫���� ����2���������о�1�����ʤ⤷����2�����ˡ�
  - �ǡ�����¤��x[a],m[i][a], a=0,1, i=0,1,...,n-1 ��n ���ǻҿ���

 - ���Ȥ����Ѥ��䤹����Τ�Ĥ��뤫�����ξ�硤������֤������롥

 - �鿴�ԤˤȤäơ����򤷤䤹���Τϡ�

- templates: [mn_som000.c](mn_som000.c), [mn_som001.c](mn_som001.c),
 - for MNIST [templates](http://www.cs.miyazaki-u.ac.jp/~date/lectures/2015neural/mnist/index.html)


### Boltzmann Machine
+



