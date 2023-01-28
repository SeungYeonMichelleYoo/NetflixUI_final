# SeSAC 과제 - NetflixUI_final  

## 개발 기간 / 개발 환경  
2022.07.05

<img width="95" src="https://img.shields.io/badge/Xcode-13.4.1-blue"> <img width="77" src="https://img.shields.io/badge/iOS-15.0+-silver">  
  
  
## 시연 영상  
  
![netflix_gif](https://user-images.githubusercontent.com/87454813/215252608-ac56cc2b-8307-4791-a151-25adc56b0b2c.gif)

![jackflix](https://user-images.githubusercontent.com/87454813/215252892-dd3afafd-e69b-4f72-9f92-c8b1ccf58cdb.gif)

## 핵심 화면 및 기능
### UI factors UI 요소
Making photos in circle & border size and color changing (Button에 테두리 및 둥글게 추가)

UISwitch - changing background color with setting cornerRadius (스위치 배경 색상 변경 - 회색)
SwitchBtn.backgroundColor = .lightGray
SwitchBtn.layer.cornerRadius = 16

Autolayout - You can see similar iPhone UI even if it is changed as iPhone SE, 8 plus, 13 Pro Max , etc. (오토레이아웃 적용)

### Action factors 액션 관련

Keyboard up and down with Tap Gesture Regonizer & button clicked (텍스트필드 외 배경 탭 경우 & 회원가입 버튼 키보드 내려감)

The 4 photos background images are changed when clicking 'Play' button. (재생 버튼 클릭시 배경 랜덤 변경)

Dont't show the password textfield (패스워드창 암호화 적용)
passwordtxtField.isSecureTextEntry = true  
