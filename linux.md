<pre><code></code></pre>

# ��Ϻ��� ls
 - ls -a �������ϱ��� ���� 
 - ls -l �ڼ��� ����
	<pre><code>
		//-rw-r--r-- 1 kkk2 197121     787  9��  9 08:57  adfasdf 		//����Ʈ���� -(������)���� �����ϴ� �׸��� "����"�̴�.
		//drwxr-xr-x 1 kkk2 197121       0  9�� 29 19:34  Desktop/ 	//����Ʈ���� /(������)���� �����ϴ� �׸��� "���丮"�̴�.
	</code></pre> 
- ls *txt
	<pre><code>
		ls my.*
   	</code></pre>
- ls -al ���������� �ڼ��� ����
	<pre><code>
		-ls -al //a�� l�� ������ ��¾�
	</code></pre>
# ���� �۾�����
- pwd 
# ���丮�� �̵��ϴ� cd 
- pwd ��ɾ ���� ����ϵ�������!

# ���/���� ��� 
	- ��� ��� : .. �� .  
			//cd ..		// .. ���� ���丮�� ���� ���͸��� �̵���
			//cd ../../..//	// �Ѳ����� �̵�������
			//cd ../etc/sysconfig // �ش� ���͸��� �̵� ������

			//cd . 		// ���� ���͸��� �̵��� 
	- ���� ��� cd /aaaa/bbb/ 	
# �� ���� ����  touch 
	<pre><code>
		- touch test.txt
	</code></pre>
# ���� ����  rm 
	<pre><code>
		rm test.txt
	</code></pre>
	<pre><code>
		rm -f test.txt 	// -f ��������
	</code></pre>
# ���� ���� cp 
	- ���� ���� cp + ���� + ī�Ǻ� 
	<pre><code>
		cp test.txt copyTest.txt
	</code></pre>
	- ���� ���� cp -r �������� + ī������
	<pre><code>
		cp -r java copyJava
	</code></pre>