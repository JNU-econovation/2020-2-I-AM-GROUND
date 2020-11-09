# 우리 좀 더 친해져보아요!

### 목표

- 프로젝트에서 자주 사용하는 도구 'Git'과 'GitHub'와 친해져보아요!
- 여러 사람들과 함께 이야기나누면서 좀 더 가까워져요!



### 참여 방법

갈색이 잘 어울리는 가을 11월, 약 3주동안 진행할 예정입니다.🌰

**11월 30일(월)까지 수행해야하는 미션 소개입니다.**

- 자신을 소개하는 글을 작성해서 [Pull Request](#pull-request-%EB%B3%B4%EB%82%B4%EA%B8%B0)를 올려요!
- 에코노베이션 활동을 하면서 해보고 싶은 버킷리스트를 Issue로 올려주세요!(좋은 말씀들을 공유해주시거나 가사, 시를 공유해주셔도 좋아요!)💓
- Hoxy, 에코노피플들에게 궁금한 점이 있으신가요? 서로에게 재미난 질문, 궁금한 점을 물어보아요! Issue를 적극적으로 이용해 다양한 질문들을 올려주세요.
- 다른 사람들의 자기소개와 Issue들을 읽으며 댓글과 이모지 등을 활용해 적극적으로 소통해보아요! 📣
- 다른 사람들의 PR을 `review`하신 후 `approve` 해주세요!
- 하시면서 어려움이 생기시다면 언제든지 slack을 적극적으로 활용해주세요!

**자신을 소개하는 글에는 이런 것들을 포함해 작성해주세요.**

기본적인 예시를 제공합니다.

> 한 줄로 간단하게 당신을 알려주세요!
>
> 좀 더 자세하게 자신에 대해서 소개해주세요
>
> 이번 학기에는 어떤 프로젝트/공부를 하시나요?
>
> 앞으로 어떤 것을 공부하고 싶으신가요?
>
> 마지막으로 하고 싶으신 말씀이 있다면?

(위의 양식은 예시일 뿐 수정하셔도 괜찮습니다.)

이모지를 활용하시면 더 개성넘치게 글을 작성하실 수 있답니다 :) [바로가기](https://www.emojiengine.com/ko/)

**6명 이상의 동아리원들로부터 `Approve`를 받으시고, Issue를 하나 이상 올리시면 확인을 통해 `merge`해드립니다.**

### Pull Request 보내기!

앗! git 명령이 잘 생각나지 않으신다구요? **확인하기**를 눌러보세요! 

1. 다음의 저장소를 local에 `clone`해주세요. 

   <details>
   	<summary>확인하기</summary>
		<div markdown="1">
			<pre>git clone https://github.com/JNU-econovation/2020-2-I-AM-GROUND</pre>
			<text>이후 local에 clone된 저장소로 이동해주세요!</text>
			<pre>cd 2020-2-I-AM-Ground</pre>
    </div>
	 </details>
   
2. `master`브랜치를 기준으로 자신만의 새로운 브랜치를 만들어주세요. 브랜치 이름은 **본인의 GitHub아이디**로 해주세요.

	<details>
   	<summary>확인하기</summary>
		<div markdown="1">
			<pre>git branch -b 본인의 Github 아이디</pre>
    </div>
	 </details>

3. 자기소개 문서를 작성하여 해당 브랜치로 `commit`합니다.
	<details>
   	<summary>확인하기</summary>
		<div markdown="1">
			<pre>git commit -m "commit message"</pre>
    </div>
	</details>
   - username.md파일은 삭제하시면 안됩니다. 

   - 자기소개 문서 제목은 **본인의 'GitHub아이디'**로 만들어주세요.
     - ex) mywnajsldkf.md

4. 자신이 만든 브랜치를 `origin/자신의 브랜치`로 `push`합니다.
	
		<details>
      	<summary>확인하기</summary>
		<div markdown="1">
			<pre>git push origin {자신의 브랜치 이름}</pre>
    </div>
	 </details>
	
5. GitHub에서 `자신의 브랜치`에서 `master`브랜치로 Pull Request 날립니다.

   - 제목은 '자신의 GitHub 아이디 - 자기 소개'로 해주세요.

     ex) mywnajsldkf - 자기소개

   - Pull Request 내용은 한줄로 간단하게 자신을 소개하는 내용을 담아주세요.

     ex) 안녕하세요! 에코노베이션의 화석이 되어가는 김정인입니다. 

6. PR문서에 `자기 소개` label을 달아주세요!

