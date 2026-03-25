## Step 2: 앱 수정하기

<img height="150px" align="right" src="https://octodex.github.com/images/mcefeeline.jpg">

새 앱을 가지고 놀아본 후, 뭔가 빠뜨린 것을 금방 깨달았을 것입니다. 또는... 앱을 더 좋게 만들 재미있는 새 아이디어가 떠올랐을 수도 있습니다!

좋은 소식이 있습니다. Spark에게 일상적인 언어(그리고 Spark에게 가르친 업무/취미 전문 용어)로 계속 대화하면서 앱을 개선할 수 있습니다.

> [!NOTE]
> 나머지 단계에서는 시연 목적으로 종이 접시 디자이너 앱을 사용합니다.

### 📖 이론: 지속적인 개선

Spark의 가장 강력한 기능 중 하나는 지속적으로 변경 사항을 제출하여 프로젝트를 더욱 향상시킬 수 있다는 것입니다.

기존 소프트웨어와 달리, 수많은 "기능 요청"과 "버그 리포트"를 제출하고 다음 릴리스까지 6개월을 기다리며 현재 버전으로 살 필요가 없습니다! (그리고 문제가 해결되길 바라는 것도 😒)

첫날 몇 번의 대화만으로도 정말 유용한, 어쩌면 멋진 것을 가질 수 있습니다! 6개월 후를 상상해 보세요! 🧑‍🚀

Spark에 아이디어를 전달하는 2(그리고 반)가지 주요 방법이 있습니다:

1. **왼쪽 채팅 패널**: 초기 애플리케이션 설명과 마찬가지로, 원하는 변경 사항을 설명합니다.

2. **요소 선택기**: 실시간 미리보기에서 기능을 선택하고 플로팅 채팅 상자를 사용하여 특정 영역에 요청을 집중합니다.

&nbsp;&nbsp; 2.5. **이미지 공유**: 위의 채팅 중 하나에서 목업 이미지나 손 스케치를 첨부하여 설명을 명확히 합니다.

다음은 (나중에) 탐색할 수 있는 몇 가지 예제 상황입니다. 🧐

- 기존 기능 개선하기.
- 새로운 버그 있는 기능을 추가한 다음 수정하기.
- 실수로 무언가를 깨뜨린 다음 "되돌리기"로 수정하기.
- 더 이상 필요 없는 기능 제거하기.

> [!TIP]
> 애플리케이션이 문제를 해결하는 단 하나의 방법에만 제한될 필요는 없습니다.
> 여러 기술을 동시에 추가하여 시도해 보고, 나중에 사용하지 않는 것만 제거하세요! 🧪

### ⌨️ 활동: 새 기능 추가하기

1. 실시간 미리보기 화면에 있는지 확인하세요.

1. 아래는 Spark에 구현을 요청할 수 있는 예제 아이디어입니다. 또는 직접 만들어도 됩니다!

   <details>
   <summary>1. 커피숍 - ☕️ 시크릿 메뉴</summary><br/>

   ![Static Badge](https://img.shields.io/badge/✨-Spark%20Prompt-text?style=flat-square&labelColor=ce2c85&color=ffe5f1)

   ```prompt
   Ingredients Filter
   The available ingredients for the secret menu are constantly changing.
   Add an area in the side panel that shows all ingredients with checkboxes.
   If something is unchecked, those items in the menu are dimmed and the word "unavailable" is added.
   ```

   </details>

   ***

   <details>
   <summary>2. 라크로스 - 🥍 통계 트래커</summary><br/>

   ![Static Badge](https://img.shields.io/badge/✨-Spark%20Prompt-text?style=flat-square&labelColor=ce2c85&color=ffe5f1)

   ```prompt
   Player Notes - Add the below fields for additional tracking.

   - Add a plain text field under each player for capturing notes.
   - Add a "Sparkles" button counter to give a player kudos. Increment it the same way as the other stats.
   ```

   ![Static Badge](https://img.shields.io/badge/✨-Spark%20Prompt-text?style=flat-square&labelColor=179b9b&color=c7f5ef)

   ```prompt
   Opponent Tracking - Add support for also tracking the opponent.

   - Add an area in the "Setup" page for also managing the opponents team members.
   - Add an option to set a color for our team. Also show this in the config panel.
   - Add an option to set a color for the opponent team. Also show this in the config panel.
   - Modify the "Track Stats" page to make the player cards the matching colors.
   - Add a setting in the config panel to filter the "Track Stats" page. (Us, Opponent, Both). This way different people can track each team.
   ```

   </details>

   ***

   <details>
   <summary>3. 종이 접시 - 🍽️ 프로토타입 디자이너</summary><br/>

   ![Static Badge](https://img.shields.io/badge/✨-Spark%20Prompt-text?style=flat-square&labelColor=8250df&color=f1e5ff)

   ```prompt
   Add support for different shaped plates.
   Add a configuration option in the side panel to pick shape: Round, Triangle, Square, Pentagon, Hexagon, Octagon.
   For all options except round, add a configuration option in the side panel to set "Corner Radius". default: 0.5 inches
   ```

   ![Static Badge](https://img.shields.io/badge/✨-Spark%20Prompt-text?style=flat-square&labelColor=179b9b&color=c7f5ef)

   📎 Attachment: [Example Paper Plate Drawing](https://github.com/user-attachments/assets/8fbc27db-1dc8-4ef6-a85d-7e732d7f88f1)

   ```prompt
   I've attached an example drawing.
   Several dimensions are not shown on the drawings.
   Some dimensions are in the incorrect locations.
   Please change the top view and front section view to use the same dimensions, locations, and fonts as the example drawing.
   ```

   ![Static Badge](https://img.shields.io/badge/✨-Spark%20Prompt-text?style=flat-square&labelColor=bc4c00&color=ffe7d1)

   ```prompt
   1. Add a 3D viewer that renders the plate in a semi-realistic way.

      - It should be a solid model, not wireframe.
      - The plate should be floating in space so it can be easily rotated and viewed from different angles.

   2. Add mouse controls to pan, zoom, and rotate.

      - Rotate is controlled by clicking and dragging. Add a toggle to invert rotation.
      - Pan is controlled by holding ctrl (windows) / cmd (mac) then clicking and dragging.
      - Zoom is controlled by holding shift then clicking and dragging.
      - Add a toggle to invert

   3. Add a toggle to show a cross section view.
   ```

   </details>

   ***

1. 마음에 드는 기능을 왼쪽 채팅 패널에 복사하세요. **Submit** 버튼을 클릭합니다.

1. 왼쪽 채팅 패널에서 실시간 피드백을 확인하세요. Spark가 완료될 때까지 기다립니다.

   <img width="350" alt="실시간 진행 정보가 있는 Spark 채팅" src="https://github.com/user-attachments/assets/652bf9b3-9e22-4575-8980-e8841f3dece5">

1. (선택 사항) 실시간 미리보기에서 새 기능을 테스트해 보세요. 예상대로 작동하지 않으면 후속 피드백을 제출하는 것을 고려하세요.

> [!NOTE]
> "PDF 다운로드"와 같은 일부 파일 기반 기능은 현재 실시간 미리보기에서는 작동하지 않지만, 게시 후에는 작동합니다.

### ⌨️ 활동: 특정 변경 사항 타겟팅하기

앱의 사이드 설정 패널이 화면 공간을 많이 차지한다는 것을 깨달았습니다. Spark가 이것을 해결하도록 합시다.

1. 실시간 미리보기 위에서 오른쪽 상단의 도구 모음을 찾으세요. **Select element to edit** 버튼을 클릭합니다.

   <img width="350" alt="요소 선택 버튼" src="https://github.com/user-attachments/assets/9c9dbf82-4cc8-48e8-82dc-eda14d7e6e3f">

1. 실시간 미리보기에서 앱의 오른쪽 설정 패널 위에 마우스를 올리세요. 클릭하여 하이라이트하면 채팅 상자가 나타납니다.

   <details>
   <summary>🤷‍♂️ 사이드 패널이 없나요?</summary>

   생성된 앱에 사이드 패널이 없다면 괜찮습니다. Mona가 이것을 확인하지 않습니다. 다른 것을 수정해 볼 수 있습니다. 🧑‍🚀
   </details>

   <img width="350" alt="요소 선택 버튼" src="https://github.com/user-attachments/assets/2f5a3d9a-30d1-4c8b-aa01-b208c63b65ec">

1. 다음 텍스트를 입력하여 Spark에게 사용하지 않을 때 사이드 패널이 자동으로 숨겨지도록 요청합니다:

   > ![Static Badge](https://img.shields.io/badge/✨-Spark%20Prompt-text?style=flat-square&labelColor=8250df&color=f1e5ff)
   >
   > ```prompt
   > This takes up a lot of room.
   > Can you do something to make it automatically hide and show?
   > ```

   <img width="350" alt="플로팅 채팅 상자" src="https://github.com/user-attachments/assets/c6141af3-cd8c-4924-969c-a2992218dc4d">

1. 실시간 미리보기에서 새 기능이 원하는 대로 작동하는지 테스트합니다.

### ⌨️ 활동: 되돌리기와 다시 시도

때로는 결과가 마음에 들지 않거나, 더 나은 설명으로 다시 시도하고 싶을 때가 있습니다.

1. 왼쪽 채팅 패널에서 세로 타임라인이 있는 것을 확인하세요. 각 요청한 변경 사항마다 하나의 항목이 있습니다.

1. 이전 작업을 찾아서 마우스를 올리고 **Restore** 버튼을 클릭합니다.

   <img width="350" alt="복원 버튼" src="https://github.com/user-attachments/assets/7fadae34-2155-4fcc-89b1-fdff9d4891bd">

1. 실시간 미리보기가 업데이트될 때까지 잠시 기다립니다.

1. "패널 숨기기" 기능을 더 구체적인 설명으로 다시 업데이트해 봅시다. 왼쪽 채팅 패널에 아래 요청을 제출합니다:

> ![Static Badge](https://img.shields.io/badge/✨-Spark%20Prompt-text?style=flat-square&labelColor=a830e8&color=f8e5ff)
>
> ```prompt
> The side panel takes up a lot of room.
> Can you do something to make it automatically hide and show?
> I don't want to have to click anything.
> Just show when I move my mouse near the side.
> ```

<details>
<summary>문제가 있나요? 🤷</summary><br/>

- 업데이트에 시간이 걸릴 수 있습니다, 특히 바쁜 시간대인 경우.

</details>

## 다 놀았나요?

<img width="150px" align="right" alt="Skatetocat" src="https://octodex.github.com/images/skatetocat.png">

앱이 준비되면, 가장 마음에 드는 Spark 기능을 선택한 후 다음 단계가 공유될 때까지 잠시 기다리세요.

- [ ] 기술 용어가 없거나 적어도 적다. 🙇
- [ ] 재미있는 메시지들. 😎
- [ ] 커피를 더 가져올 수 있는 완벽한 대기 시간. ☕️
- [ ] 아직 확신이 없다. 🤷
