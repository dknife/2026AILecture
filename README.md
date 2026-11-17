# 파이썬 첫걸음 프로토타입

## 실행하기

프로젝트 폴더에서 로컬 웹 서버를 실행합니다.

```powershell
py -m http.server 8000
```

브라우저에서 `http://localhost:8000`을 여세요. `py` 명령을 사용할 수 없다면 `python -m http.server 8000`을 실행합니다. 서버를 종료하려면 터미널에서 `Ctrl+C`를 누릅니다.

## 파이썬 코드 실습

변수·반복·함수 각 단원과 퀴즈 화면의 편집기에서 코드를 고친 뒤 **실행**을 누릅니다. Pyodide 314.0.7을 jsDelivr CDN에서 불러와 브라우저 안에서 실행합니다. 따라서 Python 설치나 백엔드는 필요하지 않으며, 최초 로딩에는 인터넷 연결이 필요합니다. CDN을 사용할 수 없는 환경에서는 실행되지 않습니다. 로딩한 Python 환경은 단원 편집기들이 함께 사용합니다.

Pyodide 공식 안내: https://pyodide.org/en/stable/usage/quickstart.html

## GitHub Pages

이 저장소의 `main` 브랜치에 변경을 올리면 GitHub Actions가 사이트를 배포합니다. 저장소의 **Settings → Pages → Build and deployment → Source**에서 **GitHub Actions**를 선택하세요.

사이트 주소: https://dknife.github.io/2026AILecture/
