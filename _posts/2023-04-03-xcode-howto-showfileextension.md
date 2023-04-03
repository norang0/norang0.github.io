---
title:  "Xcode 내비게이터에서 파일 확장자 표시하기"
excerpt: ".swift .storyboard 등등"

categories:
  - howTo
tags:
  - Swift, Xcode
last_modified_at: 2023-04-03T22:00:00
---
  
Xcode 내비게이터에서 파일을 확인할 때, 아래와 같이 파일 아이콘과 이름만 표시되는 경우가 있다.  
(아무것도 모르는 상태에서 동영상 강의 따라가다 미아된 적이..)  
![FileExtensionsHideAll](https://user-images.githubusercontent.com/129058815/229528668-fc3f00e0-888c-417a-a084-60f2e2faa9e6.png)  

해당 설정은 아래에서 변경할 수 있다. (Xcode 14.2 기준)  
[Xcode] - [Settings] - [General] - [File Extensions]  

1. Xcode - Settings  
![XcodeSettings](https://user-images.githubusercontent.com/129058815/229529212-8eeabb89-2bd6-4772-8557-6127dea9abc4.png)  

2. General - File Extensions  
![XcodeFileExtensionsSetting](https://user-images.githubusercontent.com/129058815/229529632-9054d5d7-38bc-460c-a6a6-e23fb04b361a.png)  

3. Select [Show All]
![SelectShowAll](https://user-images.githubusercontent.com/129058815/229531233-06d2ab6d-ccc3-4472-b907-a50a601ca335.png)  

> File Extensions 의 옵션으로는 4가지 중에 선택할 수 있다.  
> ![XcodeFileExtensionsOptions](https://user-images.githubusercontent.com/129058815/229530791-acf52756-5194-4d04-b021-90176e18d44f.png)  
> option : Hide All, Show All, *Show Listed, *Hide Listed  
> *표시할 확장자, 숨길 확장자를 개별 지정하는 것도 가능하다.  

*Show All* 을 선택하면, 아래와 같이 확장자가 표시된 파일들을 확인할 수 있다.
![FileExtensionsShowAll](https://user-images.githubusercontent.com/129058815/229531385-8617bd4c-1f3a-4127-8778-f94ab4e4b9c7.png)    

- Xcode 버전정보  
![XcodeVersion14.2](https://user-images.githubusercontent.com/129058815/229525627-73545fb1-0234-4aee-ae74-3bdbce92bc95.png)  

<!--사진 정렬이 너무 안예뻐서 나중에 다시 찍어서 정리해야지-->