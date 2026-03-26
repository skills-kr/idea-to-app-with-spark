## Step 5: (선택 사항) 고급 개발자 기능

<img height="150px" align="right" src="https://octodex.github.com/images/securitocat.png">

여러분이 만든 것에 놀라고 있겠지만(그것도 빠르게), 뒤에서 무슨 일이 일어나고 있을까요?

코더 지향적인 기능들을 살펴봅시다. 어쩌면 이것이 앞으로 올 더 멋진 것의 _Spark(불꽃)_일 수도 있습니다. 🧑‍🚀🚀

또는... 어쩌면 여러분은 직접 코딩하는 개발자이고 수동으로 무언가를 변경하고 싶을 수도 있습니다. 👨‍💻

> [!NOTE]
> 이 단계는 **100% 선택 사항**입니다. 원하시면 바로 끝으로 건너뛸 수 있습니다.
> 이 단계는 소프트웨어 개발자를 위해 의도적으로 더 기술적입니다.

### 📖 이론: 쉬운 개발 환경

모든 Spark 애플리케이션 뒤에는 [GitHub Codespace](https://github.com/features/codespaces)라는 클라우드 기반 개발 환경에서 실행되는 완전한 코드베이스가 있으며, 당연히 Git 버전 관리로 관리됩니다.

모든 Codespaces와 마찬가지로, 일반 프로젝트처럼 열어서 수동으로 코딩을 시작할 수 있습니다. 이것은 여러 고급 기능을 제공합니다:

- **코드 편집**: 애플리케이션을 구동하는 실제 코드와 에셋을 보고 수정합니다.
- **Copilot**: GitHub Copilot Chat을 사용하여 코드 지원과 설명을 받습니다.
- **저장소 생성**: Spark 프로젝트를 버전 관리와 협업을 위한 영구적인 GitHub 저장소로 저장합니다.

> [!NOTE]
> Codespaces에 대해 더 알고 싶으신가요?
> [Skills 실습](https://github.com/skills-kr/code-with-codespaces)을 시도하거나 [문서](https://docs.github.com/en/codespaces/quickstart)를 살펴보세요.

### ⌨️ 활동: Codespace 탐색하기

1. 실시간 미리보기 위 오른쪽 상단에서 도구 모음을 찾으세요. **점 세 개(...)** 버튼을 클릭하고 **Open codespace** 옵션을 선택합니다.

   <img width="350" alt="Codespace 열기 버튼" src="https://github.com/user-attachments/assets/fd1cdb41-24ce-4312-bc32-990b76dd6283">

1. 새 브라우저 탭에서 codespace가 로드될 때까지 기다립니다.

1. 왼쪽 파일 탐색기에서 `./PRD.md` 파일을 열어 Spark가 애플리케이션을 체계적으로 유지하기 위해 저장하는 메모를 봅니다.

   <img width="350" alt="PRD 파일 예시" src="https://github.com/user-attachments/assets/3b000513-acd7-4188-85e7-4ee1ac543443">

1. **Copilot Chat Panel**을 확장합니다. **Agent** 모드인지 확인한 후 Copilot에게 애플리케이션 제목을 변경하도록 요청합니다.

   > ![Static Badge](https://img.shields.io/badge/-Prompt-text?style=social&logo=github%20copilot)
   >
   > ```prompt
   > #codebase
   > Please make the application's title more inviting.
   > Make sure it is updated in all places.
   > ```

1. Spark 페이지로 돌아갑니다. 실시간 미리보기가 업데이트되었고 왼쪽 채팅 패널에 `Manual edit` 항목이 추가된 것을 확인합니다.

   <img width="350" alt="왼쪽 채팅 패널에 추가된 수동 편집" src="https://github.com/user-attachments/assets/b06eccb0-644e-4562-918f-3f2253004ddb">

### ⌨️ 활동: 저장소에 저장하기

1. 실시간 미리보기 위 오른쪽 상단에서 도구 모음을 찾으세요. **점 세 개(...)** 버튼을 클릭하고 **Create repository** 옵션을 선택합니다.

   <img width="350" alt="저장소 생성 버튼" src="https://github.com/user-attachments/assets/ad91575a-0906-48e4-8f76-9d06ae95035e">

1. **Create** 버튼을 클릭하여 GitHub 계정에 개인 저장소를 시작합니다.

   <img width="350" alt="저장소 생성 대화 상자" src="https://github.com/user-attachments/assets/2efcfd7a-5807-4a2e-b208-3a29c2ac6795">

1. 저장소가 생성될 때까지 잠시 기다린 후 **Go to repository** 버튼을 누릅니다.

   <img width="350" alt="저장소 열기 창" src="https://github.com/user-attachments/assets/f89569cb-f706-439e-83d4-0b2ed057aa27">

1. (선택 사항) 평소 스타일로 다른 사람들과 협업을 시작하세요. 🎉

<details>
<summary>문제가 있나요? 🤷</summary><br/>

- **Open Codespace**와 **Create repository** 옵션이 사용할 수 없다면, 잠시 기다린 후 다시 시도하세요. Spark는 중요한 작업 중에 이 기능들을 일시적으로 비활성화합니다.

</details>

## 놀이 시간 끝! ✨

<img width="150px" align="right" alt="Octonaut" src="https://octodex.github.com/images/octonaut.jpg">

여러분의 여정은 이제 막 시작되었습니다! 🚀

어떠셨나요? 재미있었나요, 아니면 새로운 아이디어에 _불꽃(spark)_이 일었나요?! ✨
답변 후에 모두 완료됩니다! 축하합니다! 🎉

- [ ] 놀랍도록 재미있었다! 🤓
- [ ] 비확정적인 답변을 선호합니다!
- [ ] 별로 안 좋았다. 👎 (솔직하게 말해줘서 감사합니다)
- [ ] 나빴다. [이슈를 만들어](../issues/new) 피드백을 공유할 수밖에 없었다. 📝
