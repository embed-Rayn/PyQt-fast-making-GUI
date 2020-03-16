# PyQt-fast-making-GUI
본 문서는 PyQt를 학습하기 위한 저장소입니다. <br/>
기본은 [초보자를 위한 Python GUI 프로그래밍 - PyQt5](https://wikidocs.net/book/2944)와 [예제로 배우는 PyQt](https://www.opentutorials.org/module/544/5001)로 공부합니다.<br/>
디자이너 툴을 이용하여 빠른 나만의 어플리케이션을 만드는 것을 목적으로 합니다.

## Purpose
- 나만의 GUI 어플리케이션 만들기
	- 배포하고 싶었던 나만의 프로그램을 사용자가 사용하기 편한 GUI로 만듭니다.
- 메모장 만들기
	- 위 어플리케이션에서 다루지 못한 기능을 보충하여 연습하기 위해 실습합니다.
## Index

### [wikidocs](./wikidocs_code)
[초보자를 위한 Python GUI 프로그래밍 - PyQt5](https://wikidocs.net/book/2944)책에 나오는 예제 코드입니다.

| Number | Description |
|:---:|---|
| 1 | OT: UI 설계도, Qt 개요, Qt 툴 설명, Qt 프로그램 예제 |
| 2 | button: 푸쉬버튼, 라디오버튼, 체크박스 |
| 3 | display: 레이블, 텍스트브라우저 |
| 4 | input: 라인 에디터, 텍스트에딧, 플레인 텍스트 에딧, 폰트, 컬러 |
| 5 | input: 콤보박스, 스핀박스, 더블 스핀 박스 |
| 6 | input: 슬라이더, 다이얼, 데이트타임에딧, 데이트에딧, 타임에딧 |
| 7 | display: 캘린더 위젯, 픽스맵, 사이즈 |
| 8 | display: 웹엔진뷰, 프로그래스바, 타이머 |
| 9 | item widgets: 리스트 위젯, 테이블 위젯, 컨테이너 |
| 10 | 메모장 만들기, 나의 프로그램 만들기, exe 만들기(1) |
| 11 | 메모장 만들기, 나의 프로그램 만들기, exe 만들기(2) |

### [css in widget](https://github.com/sommerc/pyqt-stylesheets)
1. PyQt5위젯에 css 적용하기 위해 위의 주소에 들어가 코드를 다운로드 받습니다.
2. 압축을 푼 폴더에 접근하여 아래의 명령어를 입력해 줍니다. (Python version3을 사용할 경우 아래 파일의 print 함수에 소괄호를 추가해 줍니다.)
	- `pyqt-stylesheets-master/setup.py`
	- `pyqt-stylesheets-master/pyqtcss/__init__.py`
```bash
python setup.py build
python setup.py install
```
3. __pyqtcss.py가 있는 곳에서__ PyQt 프로그래밍을 합니다.
	- [예제](https://github.com/embed-Rayn/PyQt-fast-making-GUI/blob/master/qtcss/qtcss_example.ipynb)

## Reference
| Source | Description |
|:---:|---|
| [초보자를 위한 Python GUI 프로그래밍 - PyQt5](https://wikidocs.net/book/2944) | 주 교재로 사용하는 wikidocs 입니다. |
| [예제로 배우는 PyQt](https://www.opentutorials.org/module/544/5001) | 위젯을 참고하기위한 페이지 입니다. |
| [C++ GUI 라이브러리 소개: Qt & Nana](https://www.slideshare.net/LazyAhasil/c-gui-qt-nana) | Qt와 nana에 대한 설명입니다. |
| [PyCon 2017 예제로 살펴보는 PyQt](https://www.slideshare.net/ravenkyu/pycon-2017-pyqt) | 파이콘에서 발표 되었던 임덕규님의 자료입니다. |

<br/>
