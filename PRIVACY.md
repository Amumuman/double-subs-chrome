# Double Subs — 개인정보 처리방침 / Privacy Policy

최종 수정 / Last updated: 2026-11-23

## 한국어

Double Subs는 Netflix 자막을 두 언어로 보여 주고 AI로 번역·설명해 주는 무료 Chrome 확장 프로그램입니다. 개발자는 별도의 서버를 운영하지 않으며, 사용자의 정보를 수집·저장·판매하지 않습니다.

**확장 프로그램이 다루는 정보**
- **자막 텍스트:** 지금 보는 Netflix 작품의 공식 자막을 읽어 화면에 표시합니다. AI 번역이나 '자세히' 설명을 쓰면 해당 자막 문장과 앞뒤 문장이 **사용자가 직접 고른 AI 제공자**에게 전송됩니다.
- **음성(선택 기능):** 사용자가 음성 인식 자막을 직접 시작한 경우에만 재생 중인 탭의 소리를 사용자가 고른 음성 인식 제공자에게 보냅니다.
- **API 키와 설정:** 사용자가 입력한 API 키, 모델 선택, 화면 설정은 이 브라우저 안(chrome.storage.local)에만 저장되고 동기화되거나 개발자에게 전송되지 않습니다.
- **저장한 단어·문장과 메모:** 이 브라우저 안에만 저장됩니다.
- **ChatGPT 구독 연결(선택):** 사용자의 PC에서 실행되는 로컬 도우미가 OpenAI의 공식 "Sign in with ChatGPT"로 로그인합니다. 로그인 정보는 그 PC의 현재 Windows 사용자만 해독할 수 있게 암호화되어 저장됩니다.

**정보가 전달되는 곳**
사용자가 설정한 경우에만, 다음 제공자에게 번역·설명·음성 인식 요청이 직접 전송됩니다. 각 제공자의 개인정보 처리방침이 적용됩니다.
- Google Gemini API (generativelanguage.googleapis.com)
- Anthropic Claude API (api.anthropic.com)
- OpenAI API (api.openai.com) 또는 사용자 PC의 로컬 도우미를 거친 ChatGPT 구독

**수집하지 않는 것:** 시청 기록, 방문한 사이트, 개인 식별 정보, 분석·광고용 데이터. Netflix 외의 사이트에서는 동작하지 않습니다.

**삭제:** 확장 프로그램을 제거하면 브라우저 안의 설정·키·저장 목록이 함께 삭제됩니다. 로컬 도우미의 로그인 정보는 도우미 설정 화면의 로그아웃으로 지울 수 있습니다.

## English

Double Subs is a free Chrome extension that shows Netflix subtitles in two languages and translates or explains them with AI. The developer runs no server and does not collect, store or sell user data.

- **Subtitle text** of the Netflix title being watched is read to display it. When AI translation or a word explanation is used, those lines and nearby lines are sent to **the AI provider the user chose** (Google Gemini API, Anthropic Claude API, OpenAI API, or the user's own ChatGPT plan through a local helper on the user's PC).
- **Tab audio** is sent to the user's chosen speech-recognition provider only after the user starts speech-recognized subtitles.
- **API keys, settings, saved words and notes** stay in this browser (chrome.storage.local); they are not synced or sent to the developer.
- **ChatGPT plan (optional):** the local helper signs in with OpenAI's official Sign in with ChatGPT; its credentials are stored encrypted for the current Windows user only.
- **Not collected:** browsing or viewing history, personal identifiers, analytics or advertising data. The extension runs only on Netflix.
- **Deletion:** removing the extension deletes its browser data; the helper's sign-in can be removed with Sign out in the helper settings.
