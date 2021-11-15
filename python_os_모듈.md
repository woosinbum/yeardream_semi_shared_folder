# 파이썬에서 파일과 디렉토리 경로 다루기
파이썬에서 디렉토리와 파일경로를 다루는 주요 함수(os 모듈)  
import os하여 사용해야 된다.

|용도	|함수 예제|
| ------ | ------ |
|현재 작업 폴더 얻기|	os.getcwd()  #"C:\Temp"|
|디렉토리 변경|	os.chdir("C:\Tmp")|
|특정 경로에 대해 절대 경로 얻기|	os.path.abspath(".\\Scripts")  # "C:\Python35\Scripts"|
|경로 중 디렉토리명만 얻기|	os.path.dirname("C:/Python35/Scripts/pip.exe")  # "C:/Python35/Scripts"|
|경로 중 파일명만 얻기|	if os.path.isfile("C:/Python35/Scripts/pip.exe"):    print(os.path.basename("C:/Python35/Scripts/pip.exe"))    # "pip.exe"|
|경로 중 디렉토리명과 파일명을 나누어 얻기|	dir, file = os.path.split("C:/Python35/Scripts/pip.exe")|
|파일 각 경로를 나눠 리스트로 리턴하기|os.path.sep은 OS별 경로 분리자	"C:\Python35\Scripts\pip.exe".split(os.path.sep)  # ['C:', 'Python35', 'Scripts', 'pip.exe']|
|경로를 병합하여 새 경로 생성|	os.path.join('C:\Tmp', 'a', 'b')    # "C:\Tmp\a\b"|
|디렉토리 안의 파일/서브디렉토리 리스트|	os.listdir("C:\Python35")|
|파일 혹은 디렉토리 경로가 존재하는지 체크하기|	os.path.exists("C:\Python35")|
|디렉토리 경로가 존재하는지 체크하기|	os.path.isdir("C:\Python35")|
|파일 경로가 존재하는지 체크하기|	os.path.isfile("C:\Python35\python.exe")|
|파일의 크기|	os.path.getsize("C:\Python35\python.exe")|
