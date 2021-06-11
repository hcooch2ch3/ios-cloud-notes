# 동기화 메모장(Cloud Notes)
## 야곰 iOS 커리어 스타터 캠프 10번째 프로젝트

<p align="center">
<img src="https://user-images.githubusercontent.com/28377820/121497686-aa4a0100-ca16-11eb-881a-77a0195404d9.gif" width="60%"/>
</p>

- 요약 : 로컬에 메모를 저장하는 메모장 앱을 구현.
  
- 진행 기간 : 2021.02.15 ~ 2021.03.05 [3주]

- 팀 구성 : 밤(본인), [Joons](https://github.com/elddy0948) [2인]

- 역할 분담 : 기능을 각자 구현한 다음, 상호 검토 후 코드 병합

- 코드 리뷰어 : [cmindy](https://github.com/cmindy)

- 학습 키워드 : `CoreData`, `UISplitViewController`, `NSFetchedResultController`

## 1. 앱 상세 기능
- 메모 목록 표시 기능
- 특정 메모 선택시, 상세 내용 표시 기능
- 메모 추가/수정/삭제 기능
- 메모 공유 기능
    - 화면 우측 상단의 `...`버튼을 누르고 share 버튼을 누르면 아래 이미지와 같이 창이 나옴.
<p align="center">
<img src="https://user-images.githubusercontent.com/28377820/121670302-3d06a080-cae8-11eb-9b96-bd66c6c25d80.png" width="30%"/>
</p>

- 화면 크기에 맞게 UI를 변경하는 기능
    - 화면 너비의 Size class가 Compact 일 때는 메모 목록 또는 메모 내용 하나만 나오게 하며, Regular 일 때는 메모 목록 화면, 메모 내용 화면이 동시에 나타나도록 구성.
- 메모 내용에 포함된 전화번호, URL, 날짜를 하이퍼링크로 표시하는 기능
    - 아래 이미지와 같이, 메모 내용에 포함된 전화번호, URL, 날짜를 감지하여 하이퍼링크로 표시
<p align="center">
<img src="https://user-images.githubusercontent.com/28377820/121670155-16486a00-cae8-11eb-9834-e3b93b3b76d7.png" width="60%"/>
</p>



## 2. 구현 과정

## 3. 문제 해결(Troubleshooting)
### 3.1. 메모 내용을 보여주는 View를 매번 새로 생성하는 문제
#### 3.1.1. 문제 내용
#### 3.1.2. 해결 과정
### 3.2. 텍스트뷰의 편집기능과 키워드 자동탐지기능 병존불가 문제
#### 3.2.1. 문제 내용
#### 3.2.2. 문제 원인
#### 3.2.3. 해결 과정

## 4. 참고
