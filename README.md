# 🚀 04-1. 설치 및 세팅: AI 챗봇 만들기 (가상환경 생성)

---

## 📌 단계별 가이드

### 1. 기본 설치
1. **파이썬 설치**  
   [Python 공식 웹사이트](https://www.python.org/)에서 다운로드 후 설치.
2. **VS Code 설치**  
   [VS Code 공식 웹사이트](https://code.visualstudio.com/)에서 다운로드 후 설치.

---

### 2. 프로젝트 폴더 구성
1. 원하는 위치에 프로젝트 폴더 생성:
   - **폴더 구조**:  
     ```
     chat-gpt-prg/
       └── ch03/
     ```
   - `chat-gpt-prg` 폴더를 생성하고 그 하위에 `ch03` 폴더 생성.
2. **예제 코드 저장**:
   - 예제 코드를 `ch03` 폴더에 저장:  
     - 파일명 예: `example.py`
   - [예제 코드 다운로드 경로](https://github.com/chatgpt-kr/chatgpt-api-tutorial)  
     (*`진짜 챗GPT API 활용법` 교재의 깃허브 자료*)

---

### 3. 가상환경 설정
1. **명령 프롬프트 실행** (관리자 권한으로 실행 권장).
2. `ch03` 폴더로 이동:  
   ```bash
   cd D:\chat-gpt-prg\ch03
   ```
3. 가상환경 생성:
	```bash
	python -m venv ch03_env
	```
4. 가상환경 활성화:
   ```bash
   ch03_env\Scripts\activate.bat
   ```
5. 가상환경 진입 확인:
	```bash
	(ch03_env) D:\chat-gpt-prg\ch03 >
	```
---

### 4. 패키지 설치
1. OpenAI 설치:
```bash
pip install openai
```
