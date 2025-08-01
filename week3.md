# Week 3 ✌

> J089_남승현, J125_박채린, J265_차지태, J227_임민수, K010_김찬휘
> 

---

# Quest 1: ❄ “AI가 직접 봐주는 오늘의 년도별 운세”

## 목표

- 매일 과제 시작 전 출생년도(예: 97년생 ~ 05년생)를 기준으로 생성한 AI 운세를 슬랙에 메시지로 공유한다.
- 운세는 각 년도별로 2~3문장 이내의 짧고 유쾌한 개발자 밈 스타일로 구성한다.
- 공유된 운세에 대해 팀원들의 이모지 반응 수가 10개 이상 달성되면 해당 날짜는 성공으로 간주한다.
- 이 과정을 최소 3일 이상 연속적으로 진행하여 팀 내 분위기를 자연스럽게 활성화한다.

## 구체적인 진행 방법

1. 팀원들의 탄생년도 리스트를 AI에게 입력하여 각 년도별 유쾌한 오늘의 운세를 생성한다
2. 운세는 너무 길지 않게 2~3문장, 재치 있는 개발자 밈 스타일로 구성
3. 과제 시작 전(최대 14시 이전까지) 슬랙 채널에 공유한다
4. 공유 시 함께 볼 수 있도록 포맷을 꾸며 공유하면 더 좋음 (예: 📅 [2000년생 오늘의 운세])
5. 유머 포함 or 긍정적인 응원 메시지를 살짝 더해도 좋음

## 프롬프트 예시

```
다음은 부스트캠프 팀원들의 탄생년도 리스트야: 97, 98, 99, 00, 01, 02, 03, 04, 05
각 년도별로 오늘의 운세를 짧고 유쾌하게 만들어줘.
개발자 밈 느낌이 살짝 섞이되 너무 어렵지 않고 재밌으면 좋겠어.
톤은 긍정적이고 대화 시작에 좋을 정도의 라이트한 농담이 섞이면 좋아.
각 운세는 2~3문장으로, 총 9개 운세를 만들어줘.

```

## 예시 결과 (참고용)

📅 2000년생 오늘의 운세
오늘은 버그가 당신을 피해 갑니다. 하지만 회의는 피해가지 않아요... 조심하세요, 회의가 Merge 될 수 있어요.

📅 1999년생 오늘의 운세
당신의 하루는 커밋처럼 깔끔할 예정! 단, 리베이스는 하지 마세요. 감정까지 섞여버릴 수 있으니까요.

📅 2003년생 오늘의 운세
오늘의 운명은 switch-case! 어떤 일이 펼쳐질지 모르지만, default는 웃음입니다.

## 추가 팁

- 하루 미션 주제나 학습 키워드(예: Git, 알고리즘, 프론트엔드 등)에 맞춰 운세 주제를 가볍게 연결해보세요
- 톤은 재미있고 긍정적으로, 간단한 이모티콘이나 밈 표현을 섞으면 반응이 더 좋아요
- 매일 동일한 형식보다는 살짝씩 변형해서 공유하면 지루함 없이 계속 즐길 수 있어요!

## 달성 기준

- AI에게 탄생년도별 운세를 요청하여 생성
- 최소 3일 이상 팀 슬랙 또는 회의에서 공유
- 각 운세 공유 시, 이모지 리액션이 10개 이상 달성하면 퀘스트 성공! 🎉

---

# Quest 2: 🧠 “AI로 슬랙에 꿀팁 공유하기” (develop)

> 슬랙에서 말 한 마디 꺼내기 어려웠던 당신,
> 
> 
> 이번엔 AI의 도움을 받아 알쓸신잡 꿀팁을 공유해볼 차례예요!
> 

## 배경

슬랙에 메시지를 보내는 것이 어색하거나 익숙하지 않은 분들도 있습니다.

이번 퀘스트는 AI의 도움을 받아, 가볍고 유익한 정보(알쓸신잡 스타일의 꿀팁 등)를 찾아 슬랙에 공유해보는 경험을 제공합니다.

## 목적

- 슬랙 메시지 작성과 공유에 익숙해지기
- 커뮤니티에 유익한 정보 나누는 경험 만들기
- AI와 협업해 콘텐츠를 생산해보는 경험 쌓기

## AI 꿀팁 생성을 위한 프롬프트 예시

```
재미있고 유익한 ‘알쓸신잡’ 스타일의 정보나 꿀팁을 하나 알려줘.
짧고 가볍게, 슬랙 커뮤니티에서 공유하기 좋은 형식이면 좋겠어.
개발자 혹은 부스트캠프 참가자가 흥미로워할 만한 내용이면 더 좋아!
총 3개 정도 알려줘.

```

## 예시로 완성된 꿀팁

1. **HTTP vs HTTPS**

> “HTTP는 우체통에 편지 넣기, HTTPS는 자물쇠 채우고 넣기 💌🔒
> 
> 
> 암호화가 이렇게 중요한 거랍니다!”
> 
1. **터미널 단축키 꿀팁**

> Ctrl + A: 커서 맨 앞으로
> 
> 
> `Ctrl + E`: 커서 맨 뒤로
> 
> `Ctrl + U`: 앞 내용 싹 지우기
> 
> 터미널 장인이 되기 위한 첫 걸음 👣
> 
1. **Git의 숨은 기능**

> git cherry -v
> 
> 
> “내 브랜치에서만 있는 커밋이 뭐였더라?” → 이걸로 확인하세요! 🍒
> 

## 보너스 활용 팁

| 활용 시점 | 방법 |
| --- | --- |
| 조용한 채널 분위기 띄우기 | “이런 거 혹시 알고 계셨나요?” |
| 매일 아침 슬랙에 한 줄 공유 | "오늘의 AI 꿀팁입니다! ☀️" |
| 대화 이어지도록 유도 | "이거 관련해서 더 좋은 꿀팁 아시는 분?" |

## 달성 기준

- ChatGPT 등 AI를 활용해 슬랙에 공유할 ‘꿀팁’ 또는 ‘흥미로운 정보’를 생성한다.
- 슬랙의 `random` 채널에 해당 정보를 **최소 1회 이상 공유**한다.
- 메시지에는 **AI의 도움을 받았다는 표시**를 남긴다.

---

# Quest 3: 🥑 생활 코드 리뷰

## 배경

개발자의 문제 해결력을 실 생활에도 적용할 수 있을까요?

> A: 여보 마트가서 우유 사고 만약에 아보카도 있으면 6개 사와.
B: (우유를 양 손에 가득 들고) 아보카도 있었어.
> 

## 퀘스트 소개

우리가 실 생활에서 겪는 문제를 에러 메시지로 표현해봅시다! 미션을 하거나 실제 생활을 하며 실수한 것들을 아래처럼 표현해 보세요!

```
Error: MissingRequiredItemException: Expected 'milk', received 'avocado * 6'
    at GroceryMission.execute (/home/life/missions/shopping.js:42:13)
    at processTicksAndRejections (node:internal/process/task_queues:95:5)
Note: Conditional logic misinterpreted. Did you mean "if avocado exists then also buy 6"?

```

아니면 실수하고 싶지 않은 문제에 대해 테스트 코드를 작성해 보아도 좋습니다!

→ 아침에 알람을 snooze하고 다시 잠들지 않기 위한 Jest 코드

```jsx
// wakeUpRoutine.test.js

const { triggerAlarm, userReactToAlarm } = require('./wakeUpRoutine');

jest.useFakeTimers();

describe('Morning Wake-up Routine', () => {
  test('User should not fall back asleep after snoozing the alarm', () => {
    // Step 1: Alarm rings
    const alarm = triggerAlarm();

    // Step 2: User snoozes
    const result = userReactToAlarm(alarm, { action: 'snooze' });

    // Simulate time passing (5 minutes of snooze)
    jest.advanceTimersByTime(5 * 60 * 1000); // 5 minutes

    // Step 3: Check user's consciousness state
    expect(result.fellBackAsleep).toBe(false);
    expect(result.actions.includes('gotUp')).toBe(true);
  });

  test('User completely ignores snooze and wakes up immediately', () => {
    const alarm = triggerAlarm();

    const result = userReactToAlarm(alarm, { action: 'wakeUpImmediately' });

    expect(result.fellBackAsleep).toBe(false);
    expect(result.actions).toContain('turnedOffAlarm');
    expect(result.actions).toContain('gotUp');
  });

  test('Fails when user falls back asleep', () => {
    const alarm = triggerAlarm();

    const result = userReactToAlarm(alarm, { action: 'snoozeThenSleep' });

    expect(result.fellBackAsleep).toBe(true);
    expect(result.actions).not.toContain('gotUp');

    // This is a failing case
    expect(() => {
      if (result.fellBackAsleep) {
        throw new Error('Regression: User fell back asleep after snoozing');
      }
    }).toThrow('Regression: User fell back asleep after snoozing');
  });
});

```

이외에도 자유로운 방식으로 실 생활의 문제를 LLM과 함께 코드와 에러 메시지로 표현해 보세요!

## 달성 기준

- 하루를 마치며 기억에 남는 실수나 문제를 생각해 보세요. 미션이나 개발과 직접적인 관련이 없는 것일 수록 좋습니다!
- 위 예시를 보고 어떻게 프롬프트를 입력하면 더 재미있는 출력을 생성할 수 있을지 고민해보세요.
- 가장 마음에 드는 결과를 Slack에 공유해보세요!

---

# Quest 4 : 🤾‍♂️ Slack에 질문 던지기 (develop)

## 배경

슬랙에서 적극적으로 소통하지 못해 아쉬웠던 경험이 있습니다.

많은 인원이 있는 공간에 글을 남기는 게 부담스러워 동료들과 깊이 있는 대화를 자주 하지 못했죠.

## 퀘스트 소개

전날 미션에서 학습한 CS 지식을 활용하여, AI를 통해 면접 문제 스타일의 퀴즈를 생성하고 슬랙에 공유해봅시다!

이 미션은 부담 없이 소통을 시작하고, 동료들과 지식을 나누며 함께 성장하는 계기를 만듭니다.

예시:

```
# 🍽️ 밥 먹으며 풀어보는 CS 면접 문제

(전날 미션에서 학습한 내용을 활용한 문제입니다.)

1) Java에서 멀티쓰레딩을 사용할 때 synchronized 키워드의 역할은 무엇인가요?
_힌트: 공유 자원 접근 시 발생하는 문제를 방지하는 기능입니다._

2) REST API의 상태 비저장(stateless)이 의미하는 바는 무엇인가요?
_힌트: 서버가 클라이언트의 상태 정보를 저장하지 않는다는 뜻입니다._

3) JavaScript의 event loop가 무엇이며, 비동기 작업 처리에 어떻게 기여하는지 설명해보세요.
_힌트: 콜백 함수 실행 순서와 작업 큐 관리에 관련된 개념입니다._

( 자유롭게 의견도 남겨주세요 😄)

```

## 달성 기준

- 전날 미션에서 배운 내용을 바탕으로 AI에게 면접 문제 스타일의 퀴즈 생성을 요청한다.
- 생성된 퀴즈를 슬랙에 공유한다.
- 최소 3일 이상 퀴즈를 공유하고, 팀원과 소통하며 의견을 나눈다.
