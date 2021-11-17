## pyspark의 python과 에디터에서 사용할 python을 분리하고 싶을 경우

1. 시스템 환경 변수의 Path에는 에디터에서 사용할 python이 있는 폴더 경로를 지정한다.

2. 시스템 환경 변수 PYSPARK_PYTHON에는 anaconda3의 python이 있는 폴더 경로를 지정한다.

3. 시스템 환경 변수에 anaconda3 python의 Scripts 폴더와 bin 폴더를 추가한다.

4. 이 경우 pip는 anacona3 python의 것이 호출된다. 따라서, python -m pip install [Package명]처럼 사용한다.

- pip에 대해 자세한 것은 아래 링크 참조  
https://thrillfighter.tistory.com/368
