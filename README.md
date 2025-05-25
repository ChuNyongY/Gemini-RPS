# An AI-powered Rock-Paper-Scissors game using the Gemini Vision API (Challenge the Master!)
Gemini Vision API를 활용한 AI 기반 가위바위보 게임 (달인과 대결!)

---

## Functional Description (기능 설명)

**Play a rock-paper-scissors game with an AI "master" using your webcam**  
-> 웹캠으로 손 모양(가위/바위/보)을 인식해서 AI '달인'과 가위바위보를 할 수 있습니다.

**Hand gesture recognition with Gemini Vision API**  
-> Google Gemini Vision API를 이용해 당신의 손 제스처를 인식합니다.

**Statistics and visual pattern analysis**  
-> 승부 결과와 선택 패턴을 저장하고 시각적인 차트로 보여줍니다.
---

## How to Use (사용법)

1. **Install requirements**  
   ```bash
   pip install -r requirements.txt
   ```
   필요한 라이브러리를 설치하세요.

2. **Get your Gemini API key**  
   - [Google AI Studio](https://aistudio.google.com/app/apikey)에서 Gemini API 키를 발급받으세요.
   - `.env` 파일에 다음과 같이 입력하세요:  
     ```
     GEMINI_API_KEY=여기에_본인_키_입력
     ```
   - 절대 실제 키 값을 깃허브에 올리지 마세요!

3. **Run the app**  
   ```bash
   python main.py
   ```
   - 실행하면 웹브라우저에서 Gradio 인터페이스가 열립니다.
   - 웹캠으로 손 모양을 보여주고, "가위바위보 시작!" 버튼을 누르세요.

4. **Enjoy the game and check your stats!**  
   - AI 달인과 대결하고, 승부 및 패턴 통계를 확인하세요.

---

## File Structure (파일 구조)

```
Gemini-RPS.py        # 가위바위보 전체 코드
requirements.txt     # 필요한 패키지 목록
.env                 # 환경변수 파일
.gitignore           # 민감정보 제외 설정
README.md            # 설명서
```

⚠Warning & Tips (주의 및 팁)
Never commit your real API key!
실제 API 키는 절대 커밋하지 마세요!

.gitignore should include .env
.env 파일은 반드시 .gitignore에 포함되어야 합니다.

If you accidentally expose your API key, revoke and regenerate it immediately.
실수로 노출했다면 즉시 폐기하고 새 키를 발급받으세요.

---

> Made with 🐍 Python, Gemini, Colab ,Gradio
> 제작자: ChuNyongY GitHub
