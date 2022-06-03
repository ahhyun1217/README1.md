# gitflow_20223098




> **리눅스 명령어_top**

- top 명령어는 시스템 프로세스와 메모리 사용 현황을 실시간으로 출력한다. 


___- top 옵션___
   
-b : 배치모드로 정보를 출력한다. 실시간 상화 대화형모드로 정보를 화면에 일렬로 출력한다.

-d delay : 지정한 시간(delay 초)의 간격으로 정보를 업데이트하여 출력한다.

-i idle : 토글값이 off일 때, idle 프로세스나 좀비 프로세스 정보를 출력하지 않는다.

-n num : 지정한 시간(num)만큼 업데이트 정보를 출력한다.

-p pid : 지정한 프로세스 ID(pid)의 정보만을 출력한다.

-q : 시간의 간격 없이 계속하여 업데이트 정보를 출력한다.

-s : 몇 개의 대화식 명령을 비활성화한다(시큐어 모드).

-S : 누적된 정보를 출력한다(cumulative 모드).

   
  
---------

 > ### 리눅스 명령어_ps

- 프로세스의 현재 상태를 출력한다.

___- 전체 프로세스와 관련된 옵션___

-A : 모든 프로세스를 출력한다.

-N : -A 옵션과 비슷하나 ps 프로세스를 제외하고 출력한다.

-a : 세션 리더 및 터미널에 속하지 않는 프로세스를 제외하고 출력한다.

-d : 세션 리더를 제외한 모든 프로세스를 출력한다.

-e : 커널 프로세스를 제외한 모든 프로세스를 출력한다.

T : 현재 터미널에서의 모든 프로세스를 출력한다.

a : 현재 터미널의 사용자 고유 프로세스를 출력한다.

r : 현재 실행 중인 프로세스를 출력한다.

x : 터미널이 없는 프로세스를 출력한다.

--deselect : -N 옵션과 같다.


******
> **리눅스 명령어_jobs**
- jobs는 작업이 중지된 상태, 백그라운드로 진행 중인 작업 상태, 변경되었지만 보고되지 않은 상태 등을 표시한다.

![캡쳐2](https://user-images.githubusercontent.com/106646157/171816885-fa87dfbb-b940-449d-a921-8bdf91447b56.jpg)

-l : 프로세스 그룹 ID를 state 필드 앞에 출력한다.

-n : 프로세스 그룹 중에 대표 프로세스 ID를 출력한다.

-p : 각 프로세스 ID에 대해 한 행씩 출력한다.

command : 지정한 명령어를 실행한다.


********
> **리눅스 명령어_kill**

![캡처1](https://user-images.githubusercontent.com/106646157/171816339-da1eb197-0aff-48f2-9087-4c1db757522c.jpg)


pid ··· : 종료시킬 프로세스 ID나 프로세스 이름을 지정한다.

-s : 전달할 시그널의 종류를 지정한다. 여기에는 시그널 이름이나 번호를 써준다.

-l : 시그널로 사용할 수 있는 시그널 이름들을 보여준다. 이것은 /usr/include/linux/signal.h 파일에서도 알 수 있다.

-1, : -HUP 프로세스를 재활성화한다.

-9 : 프로세스를 강제로 종료시킨다.


- kill 명령어는 프로세스에 종료 시그널을 보낸다. 시스템에 예기치 않은 문제가 생긴 프로세스를 종료시킬 수 있다. kill 명령으로 종료되지 않는 프로세스는 -9옵션을 사용해서 강제로 종료하면 된다.


|Root|USER|프로세스의 사용자|
|---|----|----|
|**2518**|PI|D|프로세스의 id|
|0.0|%CPU|마지막 1분 동안 프로세스가 사용한 CPU 점유율|
|0.1|%MEM|마지막 1분 동안 프로세스가 사용한 메모리의 점유율|
|7084|VSZ|가상메모리에 있는 프로세스의 KB 단위 크기|
|1076|RSS|프로세스의 실제 메모리의 크기로 KB 단위|
|?|TTY|연결되어 있는 터미널|
|Ss|STAT|실행되고 있는 프로세스 상태|
|Jun07|START|프로세스가 시작된 날짜|
|0:00|TIME|프로세스가 소비한 총 시간|
|/usr/sbin/sshd|COMMAND|사용자가 실행한 명령이름|

-------------
>매크로 사용법(q)

___- 매크로 기록___
- qA -> 작업 -> q
- q 로 시작해서 q로 끝난다.
- 시작 q 다음은 매크로명.








[github사이트](https://github.com/ahhyun1217/README.md/edit/main/README.md"사이트참조)

|제목|내용|설명|
|---|----|----|
|테스트1|테스트2|테슽트3|
|테스트1|테스트2|테슽트3|
|테스트1|테스트2|테슽트3|
