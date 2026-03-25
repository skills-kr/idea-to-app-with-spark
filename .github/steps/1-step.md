## Step 1: Spark 시작하기

<img width="300px" align="right" alt="GitHub Spark logo" src="https://github.com/user-attachments/assets/46b8b848-28c3-4726-80d7-fb5be4ebb5f8">

당신은 바로 _그런 사람_입니다. 열정과 너무 많은 아이디어를 가진 사람이요.
문제를 해결하거나 프로세스를 개선할 수 있는 훌륭한 아이디어가 있지만, 그것을 구현할 기술적 역량이 없었던 거죠.

오늘, **GitHub Spark**를 사용하면 여러분의 아이디어가 실제 문제를 해결하는 웹 애플리케이션이 될 수 있다는 것을 알게 될 것입니다. 필요한 것은 약간의 업무/취미 관련 지식과 만들고 싶은 것을 적는 약간의 인내심(가장 어려운 부분)뿐입니다.

### 📖 이론: Spark란 무엇인가요?

GitHub Spark는 비개발자를 위해 설계되었습니다, 진짜로요! 😎

웹 애플리케이션을 만들고 사용하는 데 필요한 모든 것을 제공하며, 복잡한 개발 용어는 전혀 없습니다.
지금부터 _"Spark"_를 **새로운** 친구/동료의 별명이라고 생각하세요.

마케팅 문구처럼 들리겠지만, _진심입니다! ✨_

새로운 동료가 팀에 합류하면, 여러분의 분야의 기본적인 사항은 잘 이해할 것입니다. 하지만 내부 용어, 구체적인 과제, 팀의 목표는 잘 모를 수 있습니다. Spark도 마찬가지입니다, 단지 더 빠를 뿐! 🚀 그러니 대화하고, 미리보기가 업데이트되는 것을 확인하고, 깨뜨려 보고, 피드백을 공유하고, 반복하세요.

또한... 익숙한 인간 스타일로, Spark는 질문을 피하고 여러분이 잘 설명하지 않으면 창의적으로 자유롭게 판단하는 경향이 있습니다. (모두 좋아하죠! 😅)

요약하면, Spark는:

- **소프트웨어 용어 없음** - 다른 사람과 대화하듯 협업하세요. 특별한 소프트웨어 용어가 필요 없습니다(원하지 않는 한).
- **실시간 미리보기** - 변경 사항을 몇 분 안에 자동으로 확인하여 빠르게 발전시킬 수 있습니다.
- **관리할 시스템 없음** - 모든 것이 포함되어 있습니다. 인프라 걱정은 하지 마세요.
- **빠름** - 프로토타입까지 며칠이 아닌 몇 분.

> [!IMPORTANT]
> Spark의 [과금](https://docs.github.com/en/billing/concepts/product-billing/github-spark) 시스템은 [프리미엄 요청 단위](https://docs.github.com/en/copilot/concepts/billing/copilot-requests#what-are-premium-requests)(PRU)를 사용하며, 월별 사용 허용량입니다. Spark에 대한 각 요청은 4 PRU를 사용합니다. 아이디어를 더 적은 수의 긴 요청으로 결합하는 것도 좋은 방법입니다. 😎

### 📖 이론: 좋은 설명 작성하기

우리의 친구 _Spark_가 수줍음이 많고, 질문을 피하지만, 창의적이고 재미있는 것을 탐구하는 것을 좋아한다고 가정하면(우리처럼), 좋은 결과를 얻는 가장 중요한 부분은: 명확한 소통입니다.

"종이 접시를 디자인하는 앱을 만들어줘."라고 시작하면 꽤 일반적이고 우리가 실제로 원하는 것을 얻지 못할 것이라는 걸 알고 있습니다.

좋은 소통 이론을 설명하기보다는, 재미있는 창작 흐름에 집중하고 예제로 바로 시작합시다.

> [!TIP]
> [GitHub.com의 Copilot](https://github.com/copilot)과 같은 다른 AI 채팅 도구를 사용하여 앱 아이디어를 브레인스토밍하고 Spark가 구현할 명확한 계획을 세워보세요.

### ⌨️ 활동: Spark 탐색하고 첫 번째 앱 만들기

1. 아래 링크를 우클릭하여 Spark를 다른 브라우저 탭에서 엽니다.

   [![](https://img.shields.io/badge/✨%20Spark%20열기-%E2%86%92-f1e5ff?style=for-the-badge&labelColor=ce2c85&color=f8e5ff)](https://github.com/spark)

1. 아래 예제 애플리케이션 설명을 읽어보세요. 가장 마음에 드는 것을 선택하세요.

   <details>
   <summary>1. 커피숍 - ☕️ 시크릿 메뉴 (짧은 버전)</summary><br/>

   때로는 빠르게 시작하고 결과에 유연하게 대처하고 싶을 때가 있습니다. 이것은 매우 개방적인 프롬프트의 예시입니다. 이 프롬프트가 마음에 드시면, 설명 텍스트 상자에 붙여넣고 **Submit** 버튼을 클릭하세요.

   <img width="500" alt="커피숍 예제 앱 스크린샷" src="https://github.com/user-attachments/assets/18a91fb9-5f5b-48f1-9736-e6f089b1f45b">

   ![Static Badge](https://img.shields.io/badge/✨-Spark%20Prompt-text?style=flat-square&labelColor=ce2c85&color=ffe5f1)

   ```prompt
   Create an application to help a barista build a secret menu with fellow staff.
   Add a side panel with filters to make it easy to find recipes.
   ```

   </details>

   ***

   <details>
   <summary>2. 라크로스 - 🥍 통계 트래커 (보통 버전)</summary><br/>

   메모가 많고 구체적인 요구사항이 있을 수도 있습니다. 이것은 더 상세한 예시입니다. 이 프롬프트가 마음에 드시면, 설명 텍스트 상자에 붙여넣고 **Submit** 버튼을 클릭하세요.

   <img width="500" alt="라크로스 예제 앱 스크린샷" src="https://github.com/user-attachments/assets/c750bbf2-bccd-4147-b6fa-66bffe964674">

   ![Static Badge](https://img.shields.io/badge/✨-Spark%20Prompt-text?style=flat-square&labelColor=bc4c00&color=ffe7d1)

   ```prompt
   # Lacrosse Statistics App

   Make an application for tracking statistics for the players of a lacrosse team. This will be used to help coaches optimize team performance.

   App Name: Lacrosse Stats Tracker
   Team Name: The Cherry Pickers

   ## Application Requirements

   There are 3 tabs for different modes, and a side panel for settings.

   - Setup - Features to manage the team.
   - Track Stats - Primary entry screen entering stats.
   - Reports - High level overview of the entire team.
   - Config Panel - Quickly access to various settings.

   ### Setup

   The Setup page is mainly used for organizing members of the team.

   - It should be easy to edit multiple names.
   - Provide an option to upload via CSV.
   - Provide an option to download via CSV.
   - Provide a "Download Sample CSV" file that provides the required format for uploading.
   - Ensure support for multiple player positions.

   - Provide a button to clear the stats but not the team.
   - Provide a button to clear everything.
   - If importing multiple times, update existing entries without deleting them or associated stats.

   ### Track Stats

   This page is the primary entry screen that allows the coach to enter scores live during the game.

   - Add a tab bar at the top to select the current quarter. Stats are stored associated to it.
   - Each player has 2 sets of buttons: offensive stats and defensive stats.
   - It should be easy to find a player and choose a statistic.
   - It should be easy to increase/decrease a statistic. Example: a `+` button and `-` button
   - Add a search field to quickly find a player.

   ### Reports

   - Basic game info like: Game Name, Opponent, Date, Location
   - List top three players for every statistic.
   - Tables to select report view: Full Game, Q1, Q2, Q3, Q4.
   - Table showing all statistics.
   - Include totals for each player and overall for the game.
   - Button to export as CSV. All reports are included.
   - Button to save as PDF. All reports are included.

   ### Config Panel

   - It should always be visible on the right side of the page, for easy access to change settings.
   - Add a dropdown toggle for display (Light, Dark, System). Default to the current phone's mode.
   - Readability - Provide 3 settings for easier viewing. (Compact, Spacious, Large Font)

   ### Other considerations

   - Make it work best on phones. This will be used live during games.
   - The page should never need refreshed to view a change.
   - A player can have multiple positions. example: SSDM / LSM
   - Use the exact names for the player details and statistics.
   - All math for the statistics needs to be 100% accurate. This cannot ever be wrong.
   - Include sample data for 20 players for easily testing the app.
   - The Readability setting adjusts the layout for accessibility.

   ## Background on lacrosse

   There are 10 players on the field per team.

   ### Positions

   - There are offensive and defensive players.
   - Attack and midfield are offense.
   - Long stick midfielder (LSM) is a cross between offensive and defensive.
   - Short stick defensive midfielders (SSDM) mostly play defense.
   - Close defense long poles mostly play defense.
   - Faceoff players are also called FOGOs.
   - Goalie

   ### Player Details

   - First Name
   - Last Name
   - Number
   - Position
   - School Year (Freshman, Sophomore, Junior, Senior)
   - Hometown (City and State)

   ### Offensive statistics

   - Goals
   - Assists
   - Shots
   - Faceoff Win
   - Faceoff Loss

   ### Defensive statistics

   - Ground balls (GBs)
   - Caused turnover (CTO)

   ### Goalie statistics

   These stats are only visible and trackable for people with the "Goalie" position.

   - Goals saved
   - Goals allowed
   ```

   </details>

   ***

   <details>
   <summary>3. 종이 접시 - 🍽️ 프로토타입 디자이너 (긴 버전)</summary><br/>

   요구사항이 매우 기술적으로 구체적인가요? 이미지도 첨부하는 예시입니다. 이 프롬프트가 마음에 드시면, 설명 텍스트 상자에 붙여넣고 **Submit** 버튼을 클릭하세요.

   <img width="500" alt="종이 접시 디자인 예제 앱 스크린샷" src="https://github.com/user-attachments/assets/c1b6359f-3104-4250-9e63-8ca3a9a86e3d">

   ![Static Badge](https://img.shields.io/badge/✨-Spark%20Prompt-text?style=flat-square&labelColor=a830e8&color=f8e5ff)

   📎 Attachment: [Example Paper Plate Drawing](https://github.com/user-attachments/assets/8fbc27db-1dc8-4ef6-a85d-7e732d7f88f1) (optional)

   ```prompt
   Make an application for dynamically previewing the design of a paper plate.
   This will be used to help communicate with customers.

   ### Plate Drawing Preview

   There is a live preview on the left showing a CAD drawing of a paper plate.

   This drawing must look identical to the attached image of a real drawing.
   Below are details to understand the attached image:

   - There are 2 views: Top View and Front Section View. The top view is always directly over the front section view. The top view has a line (A) indicating the path of the section view (Section A-A).
   - The title block is in the bottom right. It includes information about the company, plate design, designer, and date.
   - Below the drawings is a disclaimer. This text must be exactly the same.
   - The front section views (Section A-A) show the dimensions.
   - In the attached example image, the plate geometry is in red and the dimensions are in black.
   - The placement of the dimensions is somewhat flexible. Just make sure they don't overlap and all clearly have leader lines pointing to the correct location.

   ### Plate Configuration Panel

   There is a configuration panel on the right that provides all configuration options for the design of the plate in the drawing.

   - It is always visible.
   - The plate design is dynamically generated from the values in the configuration panel. This is very very important.

   The parameters are the following:

   - THICK - The thickness of the paper. Default to 0.018 inches.
   - PLATE DEPTH - The distance from the top to the bottom of the plate.
   - TOP OUT DIAMETER - The maximum diameter from measuring the outside of the plate.
   - TOP IN DIAMETER - Intersection of the theoretical side wall and the top of the plate.
   - BOTTOM OUT DIAMETER - Intersection of the side wall and the bottom of the plate.
   - SIDE WALL - The angle between the plate bottom and the plate side.
   - TOP RADIUS - The transition radius between the plate top and the plate side.
   - BOTTOM RADIUS - The transition radius between the plate bottom and the plate side.
   - FLANGE DEPTH - The distance from the top of the plate to the bottom of the the flange.
   - TURN DOWN - The angle of the flange relative to the plate top.
   - TURN DOWN RADIUS - The transition radius between the plate top and the flange.

   ### Enhancements

   The following features are independent of the design but must be included.

   1. Saved Designs - Add a "designs" tab in the configuration panel for storing the current and past designs. This will allow the user to quickly switch between designs. Add 3 example plates so the history already has samples to test with.

   1. Export to PDF - A button below the drawing preview. This will open a new page formatted for printing and trigger the print dialog.

   1. Quick Add - Add a text box below the configuration options with the title "Quick Add". This will be used for copying an email into it that has all the configuration values somewhere. Use AI to scan the email text and automatically fill in the configuration values.

   ### Other considerations

   - All dimensions are in inches by default. Add a toggle for metric (millimeters).
   - The interface needs to be beautiful. This tool will be used by sales and marketing teams.
   - Make it work best for desktop. Phone does not matter.
   - Multiple users will be using this simultaneously. Make sure they can't see each others designs.

   ### Context

   - Plates are made out of paper board, not paper (like for writing).
   - You are an expert paper plate designer.
   - You are an expert computer aided drafter.
   ```

   </details>

   ***

1. 채팅 인터페이스와 실시간 미리보기가 있는 페이지로 이동합니다.

   <details>
   <summary>🐛 오류 메시지가 나왔나요? </summary>

   때때로 Spark가 너무 야심차서 문제가 생길 수 있습니다. 이런 경우 **Fix all** 버튼을 클릭하면 대부분 해결됩니다.

   <img width="350px" alt="Fix All 버튼 스크린샷" src="https://github.com/user-attachments/assets/7a4e5543-8d37-4d98-9da4-3e46bf8526ec" />

   </details>

   <img width="350" alt="예제 텍스트와 하이라이트된 제출 버튼이 있는 Spark 시작 화면" src="https://github.com/user-attachments/assets/0e6afb14-7791-4741-b2c1-bb788ee5bba1">

1. 왼쪽 채팅 패널에서 Spark가 앱 진행 상황에 대한 실시간 피드백을 제공하는 것을 확인하세요.

   <img width="350" alt="실시간 진행 정보가 있는 Spark 채팅" src="https://github.com/user-attachments/assets/45ded9dc-6744-4a16-ae4f-af25836a5ae8">

1. Spark가 완료될 때까지 몇 분 기다리세요. 기다리는 동안 재미있는 메시지를 즐기세요!

   > 🪧**참고:** 결과는 앞서 공유한 예제 스크린샷과 다를 수 있습니다.

   <img width="350" alt="반짝이 장식이 있는 재미있는 메시지" src="https://github.com/user-attachments/assets/46ca83de-22e0-47ca-b54c-e6acf975c7b9">

> [!TIP]
> 같거나 비슷한 설명으로 여러 Spark 앱을 시작하면 다른 결과를 얻게 됩니다. 병렬 아이디어를 탐색하는 좋은 방법입니다! 하지만 조심하세요, 할당량도 빨리 소모됩니다!

<details>
<summary>문제가 있나요? 🤷</summary><br/>

- 첫 시도에서 앱이 잘 작동하지 않아도 걱정하지 마세요! 같은 프롬프트를 다시 제출하여 다른 결과를 얻을 수 있습니다.
- 시간이 좀 걸리는 것 같다면, 그것은 정상입니다. 많은 요구사항이 있는 앱은 20분 또는 30분까지 걸릴 수 있습니다.

</details>

## 앱이 준비되었나요?

<img width="100px" align="right" alt="Nyantocat Gif" src="https://octodex.github.com/images/nyantocat.gif">

앱이 준비되고 작동하는 것 같으면, 가장 마음에 드는 예제 애플리케이션의 체크박스를 선택한 후 다음 단계가 공유될 때까지 잠시 기다리세요.

- [ ] 종이 접시 - 🍽️ 프로토타입 디자이너
- [ ] 커피숍 - ☕️ 시크릿 메뉴
- [ ] 라크로스 - 🥍 통계 트래커
- [ ] 나만의 앱 - 미래의 유명 앱! 🦄 🧙
