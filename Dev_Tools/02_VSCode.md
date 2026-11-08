# VSCode

- [VSCode](#vscode)
- [환경변수 설정](#환경변수-설정)
- [확장 프로그램과 설정](#확장-프로그램과-설정)

<br>

---

### VSCode

> VSCode는 오픈소스 코드 편집기다. 효율적으로 코딩할 수 있고 편의 기능을 많이 제공해 대부분의 언어 개발에 널리 쓰인다. GitHub와 연동된 파일을 열어 그 편집기에서 바로 커밋할 수도 있다.

---

### 환경변수 설정

> 터미널에서 해당 폴더 위치에서 `code .`를 입력하면 바로 VSCode가 열리도록 `Path`에 VSCode의 `bin` 폴더를 등록한다.

<br>

| **순서** | **설명** |
| --- | --- |
| 1 | 검색창에 `실행`을 입력해 실행창을 열고 `sysdm.cpl`로 시스템 속성 열기 |
| 2 | 고급, 환경 변수, 시스템 변수의 `Path` 선택 후 편집 |
| 3 | 맨 아래 빈 칸에 VSCode의 bin 경로(예: `C:\Users\사용자명\AppData\Local\Programs\Microsoft VS Code\bin`) 입력 후 확인 |
| 4 | 폴더에서 cmd를 열고 `code .` 입력. 그 폴더가 VSCode로 열린다 |

---

### 확장 프로그램과 설정

> 왼쪽 관리 메뉴의 확장에서 마켓 플레이스의 확장 프로그램을 설치하고, 설정을 사용자에 맞게 바꿀 수 있다.

<br>

| **용도** | **설명** |
| --- | --- |
| 한글 패치 | `Korean Language Pack for Visual Studio Code`를 설치한 뒤 검색창에 `> Configure Display Language`를 입력하고 `한국어 (ko)` 선택 |
| 태그 이름 동시 변경 | `Auto Rename Tag`를 설치하면 HTML, XML에서 시작 태그를 바꿀 때 짝인 닫는 태그도 함께 바뀐다. `<div></div>`의 시작 태그를 `<section>`으로 바꾸면 `</div>`도 `</section>`으로 바뀐다 |

<br>

---

<br>

**VSCode 요약**

<aside>

> VSCode: 오픈소스 코드 편집기, GitHub 연동 가능 <br>
Path에 bin 폴더를 등록하면 code .으로 폴더 열기 <br>
확장: Korean Language Pack, Auto Rename Tag

</aside>

<br>

### Link
[VSCode 공식 문서](https://code.visualstudio.com/docs)
