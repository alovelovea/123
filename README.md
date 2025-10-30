# 🧊 Fridge Project

냉장고 속 식재료, 알러지, 레시피, 좋아요 데이터를 관리하는 Django 웹 프로젝트입니다.
이 프로젝트는 이미 데이터(`db.sqlite3`)가 포함된 완성 버전이며,
Django가 설치되어 있지 않은 환경에서도 아래 단계만 따라 하면 실행할 수 있습니다.

---

## ⚙️ 실행 방법 (for Windows)

### 🔍 한 번에 실행하기

다음 명령어들을 **newproject 폴더 안에서 그대로 복사해 붙여넣기** 하세요 👇

```bash
cd C:\Users\<사용자이름>\Desktop\newproject
python -m venv venv
venv\Scripts\activate
pip install django django-extensions
python manage.py migrate
python manage.py runserver
```

> 💡 위 명령어를 실행한 후 브라우저에서
> [http://127.0.0.1:8000/](http://127.0.0.1:8000/) 또는 [http://localhost:8000/](http://localhost:8000/) 로 접속하면 완성된 웹앱이 실행됩니다.

---

## 💡 참고

* Python 3.10 이상이 필요합니다.
* 모든 명령은 `manage.py`가 있는 폴더(`newproject`)에서 실행해야 합니다.
* 관리자 페이지 접속:

  ```bash
  python manage.py createsuperuser
  ```

  이후 [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin) 접속.
* 가상환경을 종료하려면:

  ```bash
  deactivate
  ```

---

**Made with ❤️ by Minjae**
