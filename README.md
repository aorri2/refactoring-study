# 리팩터링 스터디!

# 소개

`sturdy-study` 의 처음이자 마지막이 될 수도 있는  리팩터링 스터디입니다.

>  목표 : 리팩터링을 할 때 본인만의 기준을 만드는 것

'최고의 리팩터링' 이란 정의하기 힘들고, 사람마다 다르게 생각할 수도 있을 것입니다. 따라서 현 스터디의 목적은 '잘한다'가 아닌, 리팩터링에 대한 서로의 생각을 공유하며 **본인만의 기준을 갖는 것이 목적**입니다.

<br>

# 진행 방식

## 개요

- 책 : [리팩터링 2판](https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=236186172)(원활한 진행을 위해 구입하는 것을 추천드립니다)
- 공부방법 : [삼색볼펜 공부법](http://egloos.zum.com/agile/v/3684946)(스터디 전 반드시 읽어주세요)
- 스터디 리더 : 매 스터디 마다 리드하는 사람을 로테이션 돌릴 것입니다.

기본적으로 삼색볼펜 공부법으로 스터디를 진행할 것입니다. 왜냐하면 바쁜 분들께서 모이셨을 것이라.. 스터디에 시간을 최대한 안뺏기면서 높은 몰입도로 진행하려면 제격이라고 생각했습니다. (다른 의견도 환영입니다.)

스터디 시간에 다 같이 책을 읽고, 읽은 후 의견을 공유. 그 후 본인이 리팩터링한 코드를 서로 보며 질문 타임하여 끝내는 스터디라고 생각해주시면 됩니다.

<br>

## 스터디 상세 진행 방식

1. 타이머 20분을 설정한 다음, **정해진 분량 정독** (시간이 부족하다면 그 때 리더의 재량에 따라 5~10분 시간 추가 가능)
   1. 기본적으로 삼색볼펜 공부법을 적용할 것이기에, 읽으시면서 중요한 문장에는 밑줄을 긋게 될 것입니다.
2. 타이머 20분을 설정한 다음, 각자가 중요하다고 생각했던 곳을 돌아가면서 발표. (시간이 부족하다면 5~10분 시간 추가 가능)
3. 타이머 5분을 설정한 다음, 각자가 리팩터링한 코드 서로 보며 질문.
4. 다음 주 스터디 시간에 읽을 분량 및 리더를 정한 후 스터디 종료
5. **(김재준)** 다음 스터디 시작 최소 4일전까지 리팩터링해야할 코드를 Github에 업로드

<br>

## 중요하다 생각되는 곳 발표

간단하게 말씀드리자면, 이번 스터디에서는 아래와 같은 기준으로 밑줄을 긋고 발표해주시면 될 것 같습니다. (기준은 본인 마음이에요. 아래는 예시라고 생각해주세요.)

- 빨간줄 : **페이지당 1번**의 빨간줄을 그을 수 있습니다. (안그어도 됩니다.) 가장 중요하다고 생각되는 부분에 밑줄을 그어주세요
- 파란줄 : **페이지당 최대 3번**까지의 파란줄을 그을 수 있습니다. (안그어도 됩니다.) 꽤 중요하다고 생각되는 부분에 밑줄을 그어주세요
- 초록줄 : 페이지당 무제한으로 초록색 줄을 그을 수 있습니다. (안그어도 됩니다.) 흥미로웠던 부분, 한번 알아보고 싶던 부분, 처음 들어본 부분, 잘 모르겠는 부분 등등 다양한 이유로 그어주세요.

그은 밑줄을 전부 말할 필요는 없고, 스터디 시간이 한정적이라 **중요하다고 생각되거나 한번 의견을 나눠보고 싶은 부분**만 공유해주세요. 

기준은 마음대로지만, 적어도 **밑줄을 그은 본인만의 이유** 정도는 당연하게도 있어야 합니다...!

<br>

## 리팩터링

*코드 업로드 방식은 아래 `Study Rule` 부분을 참고해주세요.*

책을 읽을 범위를 정하고 그 다음 주 스터디 시간에 해당 범위를 읽게 될텐데, 코드같은 경우는 미리 각자 작성해서 오셔야 합니다. 여기서 언어의 문제가 발생할 수 있는데, 기본적으로 어떤 언어를 쓰시던 상관없고, Java, Javascript(책에 이미 존재), Ruby 정도의 리팩터링 대상 코드를 스터디 대장인 제가 미리 만들어놓을 것이기에 해당 코드를 리팩터링 해오시면 됩니다.

여기서 미리 하는 이유는, 책을 읽기 전과 읽은 후의 나를 비교하는 목적이 큽니다. 책을 읽은 후에는 강제는 아니지만 원하는 사람들은 코드를 업로드 하셔도 됩니다.

<hr>
<br>

# Study Rule

## 코드 업로드

Git-flow를 사용하지는 않을 것입니다. 그러나 리팩터링 작업을 진행하실 때에는 최대한 'commit 별로 어떤 리팩토링을 했는지'를 보여주려고 해주시면 나중에 돌아볼 때 더 도움이 되지 않을까 싶네요.

리팩터링을 진행할 때에는 아래와 같이 진행해주세요.

1. `main` 브랜치 pull

2. 이번 리팩터링을 위한 본인의 브랜치를 만들어주세요.
   ```shell
   git checkout -b 230509_kimjaejun_refactoring
   ```

   → `230509_kimjaejun_refactoring` 이라는 이름의 브랜치를 만든 후 바로 checkout

3. 다음 스터디 날짜로 미리 directory를 만들어 놓을 것입니다. 거기에 다음과 같이 파일을 생성 해주세요. (directory를 생성하셔도 됩니다)

   1. 파일 이름 : `${다음 스터디 날짜}_${본인영어이름}_refactoring.${확장자}`
      1. 다음 스터디 날짜 ex) `20230509`
      2. 본인 영어 이름 ex) `kimjaejun`
      3. 만약 리팩터링 스터디 진행 후 한번 더 코드를 올리고 싶다면? → 파일 이름 앞에 `after_`를 붙여주세요. 
         Ex) `after_20230509_kimjaejun_refactoring.java`

4. 리팩터링을 진행해주세요. (아까 2번 과정에서 checkout한 본인의 브랜치에서 진행해주세요.)

5. 다 하시면, `main` 브랜치로 Pull Request를 주시면 됩니다.

   1. PR로 다른 사람들의 코드를 보며 질문을 진행할 예정입니다.
   2. 스터디 시간이 아니더라도, 편하게 질문해주세요.

6. 그 날 스터디가 끝나면, 다 같이 `main` 브랜치에 merge하면 됩니다.

## 불참 시 불이익?

- [ ] 돈 걷은 후 참석자들에게만 환급?
- [ ] N번 불참 시 퇴출?
- [ ] 불참하면 벌금! → 벌금은 어디로...?



