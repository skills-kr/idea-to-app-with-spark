## Step 3: 앱 스타일링하기

<img height="150px" align="right" src="https://octodex.github.com/images/gangnamtocat.png">

앱이 잘 작동하고 있으니, 이제 개인 브랜드나 디자인 요구사항에 맞게 스타일링할 차례입니다.

코딩을 몰라도 되는 것처럼, Spark는 기본 스타일링도 도와주므로 색상 조합과 폰트의 전문가가 될 필요가 없습니다. 🖍️

Spark가 앱의 느낌을 수정하기 위해 제공하는 미리 만들어진 제안들을 살펴봅시다.

### 📖 이론: 비주얼 및 데이터 커스터마이징

Spark는 애플리케이션을 커스터마이징하는 여러 방법을 제공합니다:

- **테마 커스터마이징**: 테마 창을 사용하여 색상, 폰트, 간격, 전체적인 외관을 쉽게 조정
- **에셋 관리**: 이미지, 로고 또는 기타 파일을 애플리케이션에 업로드하고 통합
- **데이터 저장**: Spark가 앱의 데이터를 위한 키-값 저장소를 자동으로 제공하며, 저장된 정보를 보고 관리할 수 있는 내장 인터페이스 포함

### ⌨️ 활동: 디자인 개인화하기

1. 왼쪽 채팅 패널 상단에서 **Theme** 탭을 클릭합니다. 외관을 변경하는 컨트롤이 열립니다.

   <img width="350" alt="테마 탭이 강조된 사이드 패널" src="https://github.com/user-attachments/assets/402d2fc9-47fe-413b-85e4-e4d3837d9a35">

1. 색상 테마를 `Minimalist`나 `Cosmic Latte` 같은 것으로 변경하세요. 참고: Spark가 다른 옵션을 추천할 수도 있습니다.

   <img width="350" alt="테마 패널의 색상 선택기" src="https://github.com/user-attachments/assets/2baa2671-7d65-4b49-9706-93194fedb988">

1. **Typography**를 실험하여 앱의 느낌에 맞는 폰트를 찾으세요.

   <img width="350" alt="테마 패널의 타이포그래피 선택기" src="https://github.com/user-attachments/assets/b3b6251d-c4de-47bc-8649-aa8b93945b26">

1. 관심이 있다면, **Color** 영역을 사용하여 테마를 오버라이드하고 수동으로 색상을 설정하세요.

   <img width="350" alt="테마 패널의 색상 선택 영역" src="https://github.com/user-attachments/assets/3fe6a485-122f-46d9-97ab-65736446efda">

### ⌨️ 활동: 기존 파일 추가하기

회사 로고, 학교 마스코트 이미지, PDF 문서 등 기존 에셋이 있는 것은 매우 흔한 일입니다. 이것들을 포함하는 방법을 배워봅시다.

1. 왼쪽 채팅 패널 상단에서 **Assets** 탭을 클릭하여 파일 목록을 표시합니다(아마 비어있을 것입니다).

1. 아래 로고 중 하나를 우클릭하여 다운로드하세요.

   | 종이 접시 회사                                                                                             | 커피숍                                                                                                    | 라크로스 팀                                                                           |
   | --------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
   | ![Mergington Paper Prod](https://github.com/user-attachments/assets/976591b7-7af3-460d-a3db-174c1ef084b6) | ![The Late Commit Cafe](https://github.com/user-attachments/assets/c5149b86-df10-41b2-a772-4fd463b5df19) | ![](https://github.com/user-attachments/assets/779f9c47-83f5-4e1a-8e8f-e98f7663db27) |

1. 왼쪽 사이드 패널에서 **Upload files** 버튼을 클릭하고 로고 이미지를 선택합니다.

1. Spark에게 업로드한 이미지를 사용하도록 요청합니다.

   > ![Static Badge](https://img.shields.io/badge/✨-Spark%20Prompt-text?style=flat-square&labelColor=ce2c85&color=ffe5f1)
   >
   > ```prompt
   > I just uploaded a logo. Please add it to the site.
   > I'll let you decide the best place to put it.
   > ```

### ⌨️ 활동: (선택 사항) 저장된 데이터 보기

때로는 저장된 정보를 확인하고 수동으로 수정하는 것이 좋습니다. 이 영역은 Spark의 기술적인 측면으로 가볍게 들어가는 것이므로 선택 사항입니다.

1. 왼쪽 채팅 패널 상단에서 **Data** 탭을 클릭하여 데이터 객체 목록을 표시합니다. 일부는 단일 값이고 일부는 테이블입니다.

   <img width="350" alt="" src="https://github.com/user-attachments/assets/daf55c10-755c-4394-a2b9-04d7b7a82584">

1. 몇 가지 항목을 클릭하여 값을 변경하는 편집기를 엽니다. 몇 가지 예시:

   | JSON 문서                                                                             | 테이블                                                                                |
   | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
   | ![](https://github.com/user-attachments/assets/856ffcd3-2b59-4de5-99e9-cfd47b0ec00c) | ![](https://github.com/user-attachments/assets/0d3753ee-9d55-4900-b4bb-f064efeb81d6) |

1. 테이블 중 하나에서 값을 변경한 다음 **Done** 버튼을 클릭하여 저장합니다.

1. 애플리케이션이 업데이트되었는지 확인합니다.

<details>
<summary>문제가 있나요? 🤷</summary><br/>

- 테마 옵션이 업데이트되지 않는 것 같으면, 페이지를 새로고침해 보세요. 때때로 실시간 미리보기와 동기화가 안 될 수 있습니다.
- 이미지가 Assets 목록에 더 이상 표시되지 않아도 걱정하지 마세요. 삭제된 것이 아닙니다. Spark가 애플리케이션의 다른 곳으로 옮겼을 수 있습니다. 채팅에서 여전히 언급할 수 있습니다.

</details>

## 멋져 보이나요? 🧐

<img width="150px" align="right" alt="Daftpunktocat-Guy" src="https://octodex.github.com/images/daftpunktocat-guy.gif">

당신이 멋져 보이는 건 알고 있습니다! 하지만... 사실 말하고 싶은 건:

앱은 어때 보이나요? 😎

- [ ] 제 앱은 당연히 화려합니다. 💋
- [ ] 판단하지 않아요, 드라마와 SF를 좋아할 뿐. 🤠
- [ ] "절충적 커피 캐시"라고 부릅니다. 🤷 ☕️
- [ ] (여기에 맞춤 유머를) 💡
