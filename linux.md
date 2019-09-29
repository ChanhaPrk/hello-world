<pre><code></code></pre>

# 목록보기 ls
 - ls -a 숨긴파일까지 보기 
 - ls -l 자세히 보기
	<pre><code>
		//-rw-r--r-- 1 kkk2 197121     787  9월  9 08:57  adfasdf 		//리스트에서 -(하이픈)으로 시작하는 항목은 "파일"이다.
		//drwxr-xr-x 1 kkk2 197121       0  9월 29 19:34  Desktop/ 	//리스트에서 /(슬러쉬)으로 시작하는 항목은 "디렉토리"이다.
	</code></pre> 
- ls *txt
	<pre><code>
		ls my.*
   	</code></pre>
- ls -al 숨긴파일을 자세히 보기
	<pre><code>
		-ls -al //a와 l를 조합한 명력어
	</code></pre>
# 현재 작업보기
- pwd 
# 디렉토리를 이동하다 cd 
- pwd 명령어를 같이 사용하도록하자!

# 상대/절대 경로 
	- 상대 경로 : .. 과 .  
			//cd ..		// .. 현재 디렉토리의 상위 디렉터리로 이동함
			//cd ../../..//	// 한꺼번에 이동가능함
			//cd ../etc/sysconfig // 해당 디렉터리로 이동 가능함

			//cd . 		// 현재 디렉터리로 이동함 
	- 절대 경로 cd /aaaa/bbb/ 	
# 빈 파일 생성  touch 
	<pre><code>
		- touch test.txt
	</code></pre>
# 파일 삭제  rm 
	<pre><code>
		rm test.txt
	</code></pre>
	<pre><code>
		rm -f test.txt 	// -f 강제상제
	</code></pre>
# 파일 복사 cp 
	- 파일 복사 cp + 원본 + 카피본 
	<pre><code>
		cp test.txt copyTest.txt
	</code></pre>
	- 폴더 복사 cp -r 원본폴더 + 카피폴더
	<pre><code>
		cp -r java copyJava
	</code></pre>