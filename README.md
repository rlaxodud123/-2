운영체제 프로젝트 2
<readme>
이름 : 김태영
 학번 : 202220694
학과 : 사이버보안학과


[실행 방법]
  
1.	  gcc -o before_sync before_sync.c (before_sync컴파일)
2.	./before_sync (before_sync실행)
3.	gcc -o after_sync after_sync.c (after_sync컴파일)
4.	./after_sync (after_sync실행)

**Producer-Consumer, Read-Write 모델은 각각다른 폴더에 같은 이름으로 저장되어 있어 2개의 폴더에. 위의 명령어를. 실행하면 된다.

Producer-Consumer 모델같은 경우 생산자가 저장할 공간이 없거나 소비자가물건을 가져올 수 없을 때를 초점으로 코드를 만들었다. 
Reader-Writer 모델같은 경우 Writer와 Reader의 기아 문제나 Reader의 수가 많아지면 그만큼 Writer가 일을 처리 하지 못하는 문제를 초점으로 코드를 만들었다.

