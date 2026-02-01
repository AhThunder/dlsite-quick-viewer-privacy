# DLsite Quick Viewer

DLsite Quick Viewer 확장 프로그램에 대한 사용 설명서입니다.
***

### ⚠️ 주의사항 ⚠️
확장 프로그램 사용 전, 반드시 DLsite에 접속하여 "한국어"로 사이트 설정을 변경하여야 합니다.

또한 본 확장 프로그램은 "Chrome" 브라우저를 기반으로 제작되었습니다. 

기타 브라우저에서는 안정적인 동작을 보장하지 않습니다.
***

### 🖍️ 본인이 보유하고 있는 제품에 대한 하이라이트 기능을 제공합니다.

본인이 보유하고 있는 상품 목록을 등록하기 위해선 확장 프로그램 창의 [파일 선택] 버튼을 누르고, 상품의 코드가 들어간 txt 형식의 파일을 등록해야 합니다.

아래는 이를 위한 txt 파일을 만드는 간략한 방법 소개입니다.

<p align="center">
  <img width="50%" src="https://github.com/user-attachments/assets/73f82602-c8e1-489e-a69b-343f62dc5a73">
</p>

1. 제품들이 저장된 폴더의 주소창을 클릭하고, CMD를 입력합니다.   
   (혹은 명령 프롬프트를 열고 해당하는 주소로 이동합니다.)

<p align="center">
  <img width="50%" src="https://github.com/user-attachments/assets/20e87fb6-4f49-417a-8534-93fa8eb85889">
</p>

2. 열린 명령 프롬프트 창에 "dir /b > 원하는파일명.txt"를 입력하고, 엔터를 누릅니다.

<p align="center">
  <img width="30%" src="https://github.com/user-attachments/assets/b13550bf-40c3-4ee4-8939-11668b7dffcb">
</p>

3. 다음과 같이 폴더 내 파일명이 정리된 txt 파일이 생성된 것을 확인할 수 있습니다.


4. 생성된 파일을 [파일 선택] 버튼을 누른 후, 등록합니다.


확장 프로그램은 txt 파일을 확인하고 6자리 숫자 혹은 0으로 시작하는 8자리 숫자는 RJ 상품의 코드로, VJ 또는 vj가 접두사로 붙는 경우 VJ 상품의 코드로 분류·저장합니다.

5. 2.63버전 이후, [폴더 선택] 버튼을 통해 txt 파일 생성 없이 폴더내 파일명을 자동으로 로드하여 목록에 저장할 수 있는 기능이 추가되었습니다.

확장 프로그램의 [하이라이트] 기능을 통해 DLsite 및 기타 웹페이지에서 본인이 보유하고 있는 혹은 보유하고 있지 않은 상품을 쉽게 파악할 수 있습니다.

~~또한 하이라이트 처리된 상품 코드는 좌 클릭/휠 클릭을 통해 DLsite의 상품 페이지로 이동할 수 있습니다.~~

2.70.2 업데이트 이후 DLsite 상품 페이지 바로 이동 기능을 제공하지 않습니다. 이는 크롬 웹스토어의 선정성 관련 심의를 준수하기 위한 조치이며, 대신 구글 검색 엔진을 위한 상품 검색으로 이동되도록 변경하였습니다.

아래는 그 예시 이미지 입니다.

<table align="center">
  <tr>
    <td align="center">
      <img width="80%" src="https://github.com/user-attachments/assets/e2a735d7-3f6d-4293-b735-985d958ff9ce">
    </td>
    <td align="center">
      <img width="100%" src="https://github.com/user-attachments/assets/1d452a1a-fc9c-412e-8269-c14c4f5e4ece">
    </td>
  </tr>
</table>


목록과 중복되는 상품은 붉은 색으로, 목록에 존재하지 않는 상품은 노란 색으로 하이라이트 처리되는 것을 확인할 수 있습니다.

이러한 하이라이트 색상은 사용자가 원하는 색상으로 직접 변경할 수 있습니다.


또한 하이라이트 기능은 확장 프로그램 팝업창의 [하이라이트 시작] 버튼을 클릭하는 것 뿐만 아니라 단축키를 사용할 수 있습니다.

하이라이트 단축키는 [하이라이트 단축키 사용] 체크 박스를 통해 활성화 시킬 수 있으며, 직접 단축키를 지정할 수 있습니다.

***
### 🔍 제품 코드·URL을 통한 미리보기 기능을 지원합니다.

하이라이트가 적용된 상품 코드와 URL은 마우스 호버 시 미리보기 팝업을 지원합니다.

아래는 지원하는 미리보기 팝업과 레이아웃 설정의 예시 입니다.

<table align="center">
  <tr>
    <td align="center">
      <img width="100%" src="https://github.com/user-attachments/assets/f3eaefec-95ff-4123-8ca7-d6295488f043">
    </td>
    <td align="center">
      <img width="100%" src="https://github.com/user-attachments/assets/c988c920-3ef3-4009-80d1-e889f9c46a51">
    </td>
  </tr>
</table>

미리보기에는 선호/불호 장르 지정 기능을 제공합니다.

확장 프로그램 창에서 해당하는 장르를 작성하면 미리보기 창에서 각각에 해당하는 장르가 초록색/빨간색으로 출력됩니다.

⚠️ 선호/불호 장르 저장은 반드시 설정창 우측 상단의 돌아가기 버튼 클릭을 통해 저장됩니다.

또한 제목에 대한 번역 기능을 제공합니다.

2.70 업데이트 이후 Gemini 번역 기능은 제거되었습니다. 기본 구글 번역 엔진을 사용합니다.

~~번역 기능을 적용하기 위해선 Google AI Studio의 API 키가 필요합니다.~~

설정창의 API키 발급 버튼을 누르면 키 발급 페이지로 바로 이동하며, Google 계정에 로그인 되어 있을시 API 키 발급에 별다른 조건 없이 대략 10초 미만의 시간이 소요됩니다.

<table align="center">
  <tr>
    <td align="center">
      <img width="80%" src="https://github.com/user-attachments/assets/05a1d362-42a3-4064-b846-6351cd62b840">
    </td>
    <td align="center">
      <img width="78%" src="https://github.com/user-attachments/assets/69c36c22-aa12-432e-97e4-f6757222c2c4">
    </td>
  </tr>
</table>


본 확장 프로그램에는 번역을 위해 총 3가지의 모델이 등록되어 있습니다.

각 모델에 대한 간략한 비교는 아래와 같습니다.

<div align="center">
  
  (성능순)    
  Gemini 2.0 Flash lite > Gemma 3 27b ≥ Gemini 1.5 Flash 8b
  
  (사용량/일 기준)   
  Gemma 3 27b (14,400회) >> Gemini 2.0 Flash lite = Gemini 1.5 Flash 8b (1,500회)
  
  (검열순/클수록 심함)   
  Gemma 3 27b > Gemini 2.0 Flash lite ≥ Gemini 1.5 Flash 8b
</div>

***
### 💾 파일명 자동 변경

[다운로드 파일명 자동 변경] 기능을 이용하면 다운로드 받는 파일명을 자동으로 [{상품번호} {[제작사]} {제목} {버전}.{확장자}] 형식으로 변경합니다.

만약 [제목 번역] 기능이 같이 켜져 있다면 파일명의 {제목} 부분은 자동으로 {번역된 제목}이 삽입됩니다.

아래는 각 기능이 적용된 예시 이미지입니다.

<p align="center">
  <img width="50%" src="https://github.com/user-attachments/assets/e9ab7d69-5590-4f1e-936d-e6b3d16367a7">
</p>

본 기능은 브라우저 내장 다운로더를 사용하는 경우에만 적용됩니다.
***

### 📜 저장된 목록 보기

사용자는 쉽게 현재까지 저장된 제품들의 목록을 확인할 수 있습니다.

더불어 [저장된 목록 보기]에는 단순한 확인을 넘어서 몇 가지 추가 기능을 제공합니다. 

<p align="center">
  <img width="70%" src="https://github.com/user-attachments/assets/69c3c50b-8500-4995-9562-e55548332180">
</p>

- [포함 장르] 기능을 통해 원하는 장르들로 목록을 필터링 할 수 있습니다. 해당 기능은 모두 만족하는 경우의 목록을 출력합니다.
- [제외 장르] 기능을 통해 원하지 않는 장르들을 필터링 합니다.
- [제작사] 검색 기능을 통해 특정 제작사의 목록만 필터링 합니다. 제작사의 풀네임이 아닌 일부만 입력되도 적용됩니다.
- 목록의 제품 클릭시 우측 화면을 통해 미리보기가 가능합니다.
- 좌측의 목록에 상품 코드 뿐만 아니라 제목/제작사/장르와 같이 표시되는 정보를 추가할 수 있습니다.

우측의 상품 미리보기 영역은 [제목 번역] 기능의 영향을 받습니다.

***
기타 문의 사항은 아래의 연락처로 연락 바랍니다.

📧 yoonsh4625@gmail.com
