## 프로젝트명 [ 달력 일기 ]
![메모,이미지추가](/images/img2.png)

## 프로젝트 설명
현재 날짜를 확인하고, 이전달/다음달로 이동 가능한 기존 달력에 메모와 이미지 추가기능을 더한 웹 어플리케이션으로,
작성된 메모와 이미지는 localStorage에 저장되어 페이지를 새로고침하거나, 달력 이동시에도 데이터가 유지됩니다.

## 개발자
최지영

## 개발기간
2024.12.17 ~ 2024.12.26



## 주요 기능
### 1. 달력 생성
현재 날짜 기준으로 달력이 생성되고, <> 왼쪽 오른쪽 화살표로 이전달/다음달로 이동가능 합니다.

### 2. 날짜별 모달
원하는 날짜 클릭시 메모와 이미지 추가가 가능한 모달창이 뜹니다.

### 3. 메모 작성
날짜별로 메모를 작성 할 수 있고, 작성한 내용은 localStorage에 저장됩니다.

### 4. 이미지 업로드 및 삭제
날짜별로 이미지를 업로드 할 수 있고, 삭제기능을 더해 이미지 삭제도 가능 합니다. 추가된 이미지는 localStorage에 저장됩니다.

### 5. 날짜에 이모티콘 추가기능
날짜별로 메모 또는 이미지가 추가되어있을경우, 날짜에 이모티콘이 표시되어 해당 날짜에 무언가 입력되었음을 알려줍니다.
모달 안에 메모와 이미지 모두 제거되었을경우, 날짜에 표시된 이모티콘도 제거됩니다.

### 6. 저장 데이터 유지
메모와 이미지, 날짜별 이모티콘은 localStorage에 저장되어 페이지를 새로고침하거나 달력 이동시에도 데이터가 유지됩니다.

### 7. 기술 스택
HTML / CSS / JavaScript / localStorage
* JavaScript : 달력 생성 및 기능구현
* localStorage : 메모, 이미지, 이모티콘 데이터 저장



## 개선 할점 + 추가하고 싶은 기능
- 화면 이동 및 클릭시 부드러운 효과 넣기
- 화면 사이드에 체크리스트 또는 현재 날씨api불러와서 추가하기
