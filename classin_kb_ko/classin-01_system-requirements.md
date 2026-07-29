---
kb_name: ClassIn 헬프센터 지식베이스
language: ko-KR
category: ClassIn(클라이언트)
subcategory: "1. 사양 요건 및 기기 정보 확인"
batch: 10 of N
translated_from: zh-CN (source: ClassIn/1._配置要求与查询)
glossary_ref: classin_glossary_zh-ja-ko-en.json
---

# 1. 사양 요건 및 기기 정보 확인

<!-- DOC_BOUNDARY -->
```yaml
title: "기기 정보 조회: 사양, 벤치마크 점수, 인터넷 속도, 칩 모델"
source_title_zh: "设备信息查询：配置，跑分，网速，芯片型号"
```

## 기기 정보 조회: 사양, 벤치마크 점수, 인터넷 속도, 칩 모델

## 1. 컴퓨터 사양 확인하기

### 이런 경우에
컴퓨터 사양 확인이란 특정 소프트웨어의 요구 사항을 충족하는지 확인하기 위해 컴퓨터의 하드웨어와 시스템 사양을 점검하는 것을 말합니다. 컴퓨터를 사용하는 사용자는 "컴퓨터 사양 요건"에 나와 있는 하드웨어 파라미터를 참고하여, 자신의 컴퓨터 하드웨어 사양과 비교해 ClassIn을 실행할 수 있는지 확인할 수 있습니다.

### 조작 방법

**(1) Windows 컴퓨터**
1. 바탕화면의 "내 PC"를 마우스 오른쪽 버튼으로 클릭합니다.
2. "속성"을 선택합니다.
3. "장치 사양"에서 메모리 용량과 CPU 모델을 확인합니다.

![](https://cofile.eeo.cn/res-store%2F207d74d5f0e039ef1498ace4e289f42cb4e480653d840eb3c47df6733319d61b_254401?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=82c2969925bd7134ba35e3fb67c100d9ed687e63)

**(2) Mac 컴퓨터**
1. "런치패드"를 엽니다.
2. 검색창에 "터미널"을 입력한 후 "터미널" 앱을 엽니다.
3. 터미널 창의 프롬프트(예: `LeondeMacbook-Air:~ shouhouzhichi$`) 오른쪽에 `sysctl machdep.cpu.brand_string`을 입력합니다.
4. 입력 후 엔터 키를 누릅니다.
5. 명령 실행 후 출력된 결과에서 컴퓨터의 CPU 모델 정보를 확인합니다.

![](https://cofile.eeo.cn/res-store%2Fd8e2f7bd40c5df5a8612c7bb3e852b5d2fe0243d74dcf5560cb1859dd34fcea5_361026?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=24d5c2fa2a2f9e340e6f51170e22071a2f610772)

## 2. 인터넷 속도 확인하기

ClassIn으로 온라인 수업/학습을 진행할 때 안정적인 네트워크 연결을 확보하려면, 시작 전에 네트워크 상태를 점검해 주세요. 사전에 네트워크를 점검하고 설정을 최적화하면 ClassIn을 원활하게 실행하는 데 도움이 되어 온라인 수업을 안정적으로 지원할 수 있습니다.

### 사용 설명
점검 결과에서 확인해야 할 주요 지표는 네트워크 업로드 속도, 다운로드 속도, 지연 시간, 지터, 패킷 손실률입니다. 네트워크가 다음 요건을 동시에 모두 충족하지 못하면, ClassIn 사용 중 연결 불안정이나 잦은 끊김 등의 문제가 발생해 수업에 지장을 줄 수 있습니다.

| 최소 네트워크 요건 |
| --- |
| 업로드 속도: 2Mbps 이상 |
| 다운로드 속도: 2Mbps 이상 |
| 지연 시간: 중국 국내 50ms 이내, 해외 지역 300ms 이내 |
| 패킷 손실률: 반드시 0% |

1. "브라우저"를 엽니다.
2. 브라우저 주소창에 다음을 입력합니다: https://www.speedtest.cn
3. "측정"을 클릭합니다.

![](https://cofile.eeo.cn/res-store%2F46e397fb953659ed33b6119718556f27b879769eae8acb042399cad96d359215_366221?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=1c368b8a4de4a408039fe6447a6a79dccd3d22eb)

## 3. 기기 벤치마크 점수 확인하기

### 이런 경우에
사용자는 컴퓨터의 CPU 모델을 기준으로, 지정된 CPU 벤치마크 사이트에서 CPU 성능 점수를 조회해 ClassIn이 정상적으로 작동할 수 있는지 확인할 수 있습니다.

### 사용 설명
교사용 컴퓨터의 CPU 성능 점수는 6000점 이상이어야 합니다.

학생용 컴퓨터의 CPU 성능 점수는 4000점 이상이어야 합니다.

### 조작 방법
1. 브라우저 주소창에 다음 URL을 입력합니다: https://www.cpubenchmark.net/cpu_list.php
2. 검색창에 컴퓨터의 CPU 모델을 입력합니다.
3. "Find CPU"를 클릭해 검색합니다.
4. 왼쪽 노란색 영역에서 컴퓨터의 CPU 모델과 완전히 일치하는 항목을 찾습니다.
5. 오른쪽 "CPU Mark" 항목의 수치를 확인합니다. 이 수치가 컴퓨터 CPU의 성능 점수입니다.

![](https://cofile.eeo.cn/res-store%2F57ebd37b9391dcc022dca39ec54aa02be8efe5a589e51f54dec7efb985ed1179_379263?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=a6179c425172f8f5c7289fccf95558b10e6f3f36)

## 4. Mac 칩 모델 확인하기

ClassIn은 Mac용으로 두 가지 설치 파일을 제공합니다: 인텔 칩 탑재 Mac용과 Apple 실리콘(M1, M2 등) 탑재 Mac용입니다. 따라서 설치 파일을 다운로드하기 전에, 먼저 컴퓨터의 프로세서 종류를 확인하고 그에 맞는 설치 파일을 선택해 다운로드해야 합니다.

1. 화면 왼쪽 상단의 Apple 메뉴 아이콘에 마우스를 올립니다.
2. 메뉴에서 "이 Mac에 관하여"를 클릭합니다.
3. "이 Mac에 관하여" 화면의 "프로세서" 항목에서 CPU 칩 모델을 확인합니다.

![](https://cofile.eeo.cn/res-store%2Fa123ab72dc9c959fe87db4f2f7e97e2c25cae4e4e015a92b5a98d9815a6cfc25_461854?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=9a884733f148e07102c7b71df32b6837e017f04e)

<!-- DOC_BOUNDARY -->
```yaml
title: "사양 요건"
source_title_zh: "配置要求"
```

## 사양 요건

## 1. 사양 요건이란?

사양 요건이란 ClassIn 소프트웨어를 실행할 때 기기에 요구되는 하드웨어 및 소프트웨어 측면의 구체적인 조건을 말합니다. 이러한 요건에는 일반적으로 프로세서, 메모리, 운영체제 등의 핵심 요소가 포함됩니다. 프로세서, 메모리, 운영체제는 소프트웨어가 정상적으로 작동하기 위한 기본 조건입니다. 수업 규모에 따라 필요한 하드웨어 사양도 달라지며, ClassIn에서는 무대에 오르는 인원이 많아질수록 소프트웨어를 안정적이고 원활하게 실행하기 위해 요구되는 하드웨어 사양도 높아집니다.

## 2. 컴퓨터 사양 요건

| | 최소 사양 요건(학생 / 녹화하지 않는 교사) | 최소 사양 요건(녹화 교사) | 권장 사양 요건(교사 / 학생) |
| --- | --- | --- | --- |
| 프로세서 | Intel 8세대 i3 이상, AMD Ryzen 3 2세대 이상 | Intel 8세대 i5 이상, AMD Ryzen 5 1세대 이상 | Intel 9세대 i7 이상, AMD Ryzen 7 2세대 이상 |
| 메모리 | Windows: 8GB RAM 이상, Mac: 4GB RAM 이상 | Windows: 16GB RAM 이상, Mac: 4GB RAM 이상 | Windows: 16GB RAM 이상, Mac: 8GB RAM 이상 |
| 운영체제 | Windows 7 이상, macOS 10.13 이상 | Windows 7 이상, macOS 10.13 이상 | Windows 10 이상, macOS 12 이상 |
| 화면 해상도 | 1280 x 720 이상 | 1280 x 720 이상 | 1920 x 1080 이상 |
| 네트워크 대역폭 | 2Mbps 이상 | 4Mbps 이상 | 6Mbps 이상 |

## 3. 휴대폰/태블릿 사양 요건

| | 최소 사양 요건(학생 / 녹화하지 않는 교사) | 최소 사양 요건(녹화 교사) | 권장 사양 요건(교사 / 학생) |
| --- | --- | --- | --- |
| 운영체제 | iOS 11 이상, Android 7.0 이상, HarmonyOS 1.0 이상 | iOS 11 이상, Android 10.0 이상, HarmonyOS 2.0 이상 | iOS 14 이상, Android 10.0 이상, HarmonyOS 2.0 이상 |
| 메모리 | Android: 4GB 이상, iPad/iPhone: 2GB 이상 | Android: 8GB 이상, iPad/iPhone: 2GB 이상 | Android: 8GB 이상, iPad/iPhone: 3GB 이상 |
| 프로세서 모델 | iPad/iPhone: A9 이상. Android: 스냅드래곤 7시리즈 730G 이상 / 스냅드래곤 8시리즈 835 이상 / 기린 8시리즈 810 이상 / 기린 9시리즈 970 이상 / 디멘시티 720 이상 / Helio G90T 이상. | iPad/iPhone: A11 이상. Android: 스냅드래곤 8시리즈 855 이상 / 기린 9시리즈 980 이상 / 디멘시티 1000 이상. | iPad/iPhone: A12 이상. Android: 스냅드래곤 8시리즈 865 이상 / 기린 9시리즈 9000 이상 / 디멘시티 1100 이상. |
| iPad/iPhone 기기 모델 | iPhone 6 이상, iPad 5세대 이상, iPad mini 4세대 이상, iPad Air 3세대 이상, iPad Pro 이상. | iPhone 8 이상, iPad 6세대 이상, iPad Pro 이상. | iPhone XS 이상, iPad 8세대 이상, iPad Pro 2세대 이상, iPad mini 5세대 이상, iPad Air 3세대 이상. |
| 네트워크 대역폭 | 2Mbps 이상 | 4Mbps 이상 | 6Mbps 이상 |

## 4. ClassIn X 권장 기기

교육 시나리오에 따라 권장되는 기기 성능은 다음과 같습니다:

**듀얼 티처 클래스룸**

![](https://cofile.eeo.cn/res-store%2F17766803a0c8c5cd1f6c361665599b60b57c960ecb9b915fcbb19071f3a640fd_100043?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=329f9adba452c88a144b07c0f7ec43fd3ac41910)

**일반 오프라인 수업**

![](https://cofile.eeo.cn/res-store%2Fb8f0fd78dc217d592076750452affe93afff5f6def42a2f944e1047a904446df_119426?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=8c223e25fd4fb3ac83c68d1295ae42eee76c9cb6)

최소 사양에서 권장되는 기능: 펜, 교재(PPT/PDF/음성·영상 등), QR코드 스캔으로 이미지 공유, 보조 카메라 등 기본적인 수업 도구.

최소 사양에서 권장되지 않는 기능: Nobook 및 비디오월.

권장 사양을 충족하면 모든 기능을 사용할 수 있습니다.

## 5. 듀얼 티처 교육 권장 기기

듀얼 티처 클래스룸은 온라인과 오프라인 수업을 결합한 새로운 시도로, 2015년부터 대중화되었습니다. 온라인 주강사와 오프라인 진행·담임 교사의 역할 분담을 통해, 우수한 교사가 지역을 넘어 수업을 진행할 수 있게 되었습니다.

![](https://cofile.eeo.cn/res-store%2F7cd38a3d4277c24347b109ecad3e542b9e0224e85e797599f5d990e83e919dd0_885358?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=a1c3b82b8bbb05039045350426d371e43dfc79a4)

점점 더 많은 파트너들이 듀얼 티처 클래스룸의 상호작용 도구로 ClassIn을 선택하고 있습니다. 사용자가 더 나은 수업 경험을 얻을 수 있도록, 다음과 같은 하드웨어 구매 방안을 권장합니다:

![](https://cofile.eeo.cn/res-store%2F6ef3fbf38d682224d94a4f0f45a0fec73d64e410cda3072a5a13883bf3ebeba4_138418?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=ee9c1339eb20a8b7f5866e5e316484816f6d3223)

## 6. 원격 회의 권장 기기

EEO는 가장 전문적인 온라인 강의실 제품을 만드는 데 주력하고 있습니다. 실제 활용에서 ClassIn은 매우 안정적이고 편리한 원격 회의 시스템이기도 합니다.

ClassIn 사용자가 더 나은 원격 회의 경험을 얻을 수 있도록, 저희의 실제 사용 경험을 바탕으로 다음의 하드웨어 기기를 권장합니다.

![](https://cofile.eeo.cn/res-store%2Fdbd247b10b9b7e07ce4cf454f8b05bbcb1171ec9932abbf8821dc1f6cda00f58_279364?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=ea97775d29e905af9a38f5fbd29b6bdcc69745c3)

![](https://cofile.eeo.cn/res-store%2F786974847dfd91a935b2103049e4c3db4af2bffee859539e13be64d9c1e84aa9_265608?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=41dda5ec9a238fdc43a21bdc9cd0f65f04c659aa)

*면책 조항: 본 내용은 EEO의 실제 시범 학교(一丟丟実験校)에서의 사용 경험을 정리한 것으로, 시중의 모든 제품을 다루지는 않으며 엄격한 제품 평가도 아닙니다. 참고용으로만 활용해 주세요.*
