# 두줄자막 — 개인정보 처리방침 / Privacy Policy

최종 수정 / Last updated: 2026-11-23

## 한국어

두줄자막은 Netflix 자막을 두 언어로 보여 주고 AI로 번역·설명해 주는 무료 Chrome 확장 프로그램입니다. 개발자는 별도의 서버를 운영하지 않으며, 사용자의 정보를 수집·저장·판매하지 않습니다.

**확장 프로그램이 다루는 정보**
- **자막 텍스트:** 지금 보는 Netflix 작품의 공식 자막을 읽어 화면에 표시합니다. AI 번역, 단어 뜻, '자세히' 설명을 쓰면 작품 제목과 자막 문장이 **사용자가 직접 연결한 AI 제공자**에게 전송됩니다. 번역 품질을 위해 앞뒤 문맥이나 회차 전체 대본이 함께 전송될 수 있으며, 사용자가 불러온 자막 파일도 같은 방식으로 처리됩니다. 여러 제공자를 연결했다면 속도나 장애에 따라 연결된 제공자 중 하나가 자동으로 쓰일 수 있습니다.
- **음성(선택 기능):** 사용자가 음성 인식 자막을 직접 시작한 경우에만 재생 중인 탭의 소리를 사용자가 고른 음성 인식 제공자에게 보냅니다. 정확도를 위해 그 장면의 공식 자막 문장을 함께 보낼 수 있습니다.
- **API 키와 설정:** 사용자가 입력한 API 키, 모델 선택, 화면 설정은 이 브라우저 안(chrome.storage.local)에만 저장되고 동기화되거나 개발자에게 전송되지 않습니다.
- **저장한 단어·문장과 메모, 학습용 캐시:** 이 브라우저 안(chrome.storage.local, IndexedDB)에만 저장됩니다. 캐시에는 작품별 번역·단어 설명, 회차 준비 상태, 불러온 자막 파일, 최근 찾아본 단어, 오류 진단 기록, 음성 인식용 오디오 조각(최대 60일·500MiB, 자동 정리)이 포함됩니다. 진단 기록은 사용자가 설정 화면에서 직접 복사하지 않는 한 어디에도 전송되지 않습니다.
- **ChatGPT 구독 연결(선택):** 사용자의 PC에서 실행되는 로컬 도우미가 OpenAI의 공식 "Sign in with ChatGPT"로 로그인합니다. 로그인 정보는 그 PC의 현재 Windows 사용자만 해독할 수 있게 암호화되어 저장됩니다.

**정보가 전달되는 곳**
사용자가 설정한 경우에만, 다음 제공자에게 번역·설명·음성 인식 요청이 직접 전송됩니다. 각 제공자의 개인정보 처리방침이 적용되며, 제공자가 응답 속도를 위해 요청 내용을 잠시 캐시할 수 있습니다(예: Gemini 문맥 캐시 약 5분).
- Google Gemini API (generativelanguage.googleapis.com)
- Anthropic Claude API (api.anthropic.com)
- OpenAI API (api.openai.com) 또는 사용자 PC의 로컬 도우미를 거친 ChatGPT 구독

**수집하지 않는 것:** 개발자는 시청 기록, 방문한 사이트, 개인 식별 정보, 분석·광고용 데이터를 받지 않습니다. 위 캐시는 이 브라우저 안에만 있습니다. Netflix 외의 사이트에서는 동작하지 않습니다(내 자막 파일 불러오기 포함).

**삭제:** 확장 프로그램을 제거하면 브라우저 안의 설정·키·저장 목록이 함께 삭제됩니다. 로컬 도우미의 로그인 정보는 도우미 설정 화면의 로그아웃으로 지울 수 있습니다.

## English

두줄자막 (Dujul Jamak) is a free Chrome extension that shows Netflix subtitles in two languages and translates or explains them with AI. The developer runs no server and does not collect, store or sell user data.

- **Subtitle text** of the Netflix title being watched is read to display it. When AI translation, word glosses or explanations are used, the title and subtitle lines are sent to **the AI provider the user connected** (Google Gemini API, Anthropic Claude API, OpenAI API, or the user's own ChatGPT plan through a local helper on the user's PC). Nearby context or the whole episode script may be included for translation quality, and subtitle files the user loads are handled the same way. If several are connected, any connected provider may be used depending on speed or failures. Providers may briefly cache requests (e.g. Gemini context cache, about 5 minutes).
- **Tab audio** is sent to the user's chosen speech-recognition provider only after the user starts speech-recognized subtitles, possibly with that scene's official subtitle lines for accuracy.
- **API keys, settings, saved words and notes, and study caches** stay in this browser (chrome.storage.local and IndexedDB); they are not synced or sent to the developer. Caches hold per-title translations and explanations, episode preparation state, loaded subtitle files, recent lookups, an error log (sent nowhere unless the user copies it), and audio pieces for speech recognition (up to 60 days / 500 MiB, pruned automatically).
- **ChatGPT plan (optional):** the local helper signs in with OpenAI's official Sign in with ChatGPT; its credentials are stored encrypted for the current Windows user only.
- **Not collected:** the developer receives no viewing or browsing history, personal identifiers, analytics or advertising data. The extension runs only on Netflix, including loading subtitle files.
- **Deletion:** removing the extension deletes its browser data; the helper's sign-in can be removed with Sign out in the helper settings.
