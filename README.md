![image](https://user-images.githubusercontent.com/78777059/166392118-5a0735ac-4739-4377-b4cb-84e8b4f8414e.png)

# 📌 Index
* [📖 Intro](#-intro)
* [💻 Installation](#-installation)
* [🔎 OverView](#-overview)
* [📔 MC Studio](#-mc-studio)
* [📖 MC Wizard](#-mc-wizard)
* [📑 MC Agent](#-mc-agent)
* [⚙️ MC Framework](#-mc-framwork)
* [💡 License](#-License)
* [📫 Contact](#-Contact)

# 📖 intro  
장비 서버 프로그램을 개발하는 데는 하나의 방법만이 있는 것이 아니며, 또한 개발을 위한 완벽한 플랫폼이 있는 것이 아닙니다. 그러나, 플랫폼을 만드는 사람들은 도달할 수 없는 이러한 이상을 위해 계속 노력하고 있습니다. 그러나 현실적으로 생각을 해보면, 기존의 장비 서버 프로그램을 만드는 기술이 완전하게 새로운 기술로 대체되기 보다는 수정되는 편이 한결 나을 것입니다. 하지만, 우리는 “변화는 소프트웨어를 이용한 작업의 본질”이라는 것을 잊어서는 안될 것입니다.

에임시스템은 그동안의 수많은 경험과 새로운 Architecture 의 연구, Pattern 의 연구등을 통해 nanoMC 를 공급하게 되었습니다. 공통된 분모들을 묶은 형태의 프레임워크와 뛰어난 개발 편의성을 제공하게 되는데, 가장 큰 철학은 얼마나 쉽게 개발자가 이해할 수 있는가라는 것에 있습니다. 따라서, 이 책의 목표는 사용자 여러분들이 기존의 기술을 새로운 기술로 이동하는데 도움을 주는 것에 있습니다. 


# 💻 Installation  
nanoMC Intallation package는 MCFramework과 EAP를 개발하고 운영하기 위한 도구들을 포함하고 있으며 사용자가 보다 쉽게 nanoMC를 설치할 수 있도록 도와줄 것입니다.  

##### Install Package  
-	MC Studio  
Workflow를 정의하고 nanoMC의 사용환경을 설정하는 도구입니다.  
-	MC Wizard   
Application과 Custom Component의 틀을 만들어주는 도구입니다.  
-	MC Agent  
EC에서 동작하는 프로그램으로 Application을 실행시키고 파일을 배포하는 역할을 합니다. MC Agent는 EC에 설치가 됩니다.  
-	MC Framework  
EIS 개발 및 실행시 꼭 필요한 Framework으로 nanoMC의 기능들이 구현된 Component입니다.  
-	Tool  
nanoMC를 사용하여 개발 및 운영할 때 사용되는 Utility입니다.  
-	Document  
nanoMC 사용 설명서입니다.  

##### Install  
nanoMC 3.1 Install CD에서 nanoMC 3.1_Setup.exe 파일을 실행시킵니다.  
그림 2.2.1과 같이 설치작업을 준비하는 윈도우를 볼 수 있습니다.  
![image](https://user-images.githubusercontent.com/78777059/166392689-15ca5f7b-afb5-4fe0-a19f-1a676a5fc617.png)  
					      <그림 2.2.1>  

2.2.2	Welcome  
설치를 계속하기 위해 Next 버튼을 클릭합니다.  
![image](https://user-images.githubusercontent.com/78777059/166392780-66fa9b8c-e314-464c-94b6-03863cc69dde.png)
					     <그림 2.2.2>  
2.2.3	Maintenance  
nanoMC가 설치되어 있다면 Maintenance 윈도우가 실행될 것입니다.  
처음 설치하는 것이라면 이 단계는 실행되지 않습니다.  
![image](https://user-images.githubusercontent.com/78777059/166392843-d58221da-7223-48a5-a8ee-4feac52d9cdd.png)  
					    <그림 2.2.3>  
-	Modify : 새로운 Component를 추가하거나 기존의 Component를 제거합니다. 이 항목을 선택한다면 Component를 선택하는 단계로 넘어갑니다.  
-	Repair : 전에 설치한 설정정보에 따라 다시 설치합니다.  
-	Remove : 설치되었던 모든 파일을 삭제합니다.  

2.2.4	License Agreement  

Software 사용권 동의서를 읽으십시요.  
![image](https://user-images.githubusercontent.com/78777059/166392902-9778aba3-1c9b-418e-aff7-21829eb2afa1.png)   
					    <그림 2.2.4>  

위 내용에 동의한다면 붉은 사각형 안의 ‘ I accept the items of the license agreement ’ 항목을 클릭합니다. 이 항목에 체크하지 않는다면   버튼은 활성화 되지 않습니다.  
동의하지 않는다면   버튼을 클릭하여 InstallShield Wizard를 종료합니다.  
2.2.5	Customer Information  

사용자 이름, 회사 이름과 Serial Number를 입력한 후   버튼을 클릭하여 다음 단계로 넘어갑니다.  
Serial Number는 배포되는 nanoMC의 CD 케이스 뒷면에 있습니다.  
 ![image](https://user-images.githubusercontent.com/78777059/166392979-0d50df91-242e-49e4-81de-4dff0d34a3b5.png)  
					     <그림 2.2.5>  
2.2.6	Destination Folder  
그림 2.2.6은 nanoMC및 SEComEnabler가 설치될 경로를 보여줍니다. 경로를 바꾸고자 한다면 ‘ Browse ’ 버튼을 클릭하여 설치될 경로를 지정합니다.  
![image](https://user-images.githubusercontent.com/78777059/166392992-f103a7d1-ad9d-4959-86bb-80aa711137f7.png)   
					     <그림 2.2.6>  
다은 단계에서 선택할 컴포넌트들은 Destination Folder의 하위 Directory로 설치가 됩니다. nanoMC 3.1을 선택한다면 C:\Program Files\AIM Systems, Inc.\nanoMC 3.1 의 경로로 설치가 됩니다.  
2.2.7	Setup Type 선택  

설치하고자 하는 유형를 선택합니다.  
![image](https://user-images.githubusercontent.com/78777059/166393017-da639ecb-36e7-4263-b869-901ec66491b4.png)  
					      <그림 2.2.7>  
2.2.7.1	Developer  
nanoMC 3.1을 사용하여 EAP를 개발하고 운영할 수 있는 컴포넌트를 설치합니다.  
2.2.7.2	Custom  
설치하고자 하는 컴포넌트를 직접 선택할 수 있습니다.  
2.2.7.3	Equipment Server  
장비 서버에 설치하고자 한다면 이 항목을 선택합니다.  

2.2.8	Feature 선택  

그림 2.2.8은 이전 단계의 Setup Type중에서 Developer를 선택했을 때의 Feature 선택 화면입니다.   
체크되어 있는 Feature들은 모두 설치가 됩니다. 이 중에서 설치하지 않으려는 Feature들은 체크표시를 없애줍니다.  
![image](https://user-images.githubusercontent.com/78777059/166393035-11583f39-5c2b-427e-be34-21f69bf8ddca.png)   
					      <그림 2.2.8>  

Next 버튼을 클릭하면 설치를 시작할 수 있습니다.  

2.2.9	Install 시작  

설치 작업에 필요한 정보를 모두 입력하였습니다.
Install 버튼을 클릭하면 이전 단계에서 설정한대로 설치작업을 시작합니다.
![image](https://user-images.githubusercontent.com/78777059/166393093-c758b238-5b72-45b6-bbb1-7d67bf6faa92.png)   
					  <그림 2.2.9>  
2.2.10	Setup Status  
이전 단계에서   버튼을 클릭하였다면 설치 작업을 시작할 것입니다. 그림 2.2.10은 Setup 진행 상태를 보여줍니다.  
![image](https://user-images.githubusercontent.com/78777059/166393107-c7c79e72-8e39-40d2-99b1-abcc948dfc60.png)  
					   <그림 2.2.10>  
2.2.11	Complete  
설치작업이 완료되었음을 나타냅니다.   
![image](https://user-images.githubusercontent.com/78777059/166393118-21f8956c-5fff-4d47-b0ad-30abcef72423.png)  
					    <그림 2.2.11>  
2.2.12	Uninstall  
Setup.exe 파일을 실행시키면 그림 2.2.12과 같은 윈도우가 실행됩니다.   
![image](https://user-images.githubusercontent.com/78777059/166393128-abf364d8-7d0b-4f9b-8c46-b0b1195e8b9e.png)  
					    <그림 2.2.12>  
세 가지 항목중에서 Remove 항목을 클릭하여 Check한 후 Uninstall 버튼을 클릭하여 제거작업을 시작합니다.  
그림 2.2.13는 제거 작업의 진행 상황을 보여줍니다.  
![image](https://user-images.githubusercontent.com/78777059/166393144-beaf7aaa-2dcf-466a-9cb9-7203d2d0ff52.png)   
					  <그림 2.2.13>  

제거작업이 성공적으로 끝나면 Finish 버튼을 클릭하여 종료합니다.  
![image](https://user-images.githubusercontent.com/78777059/166393161-ce7cca23-697d-4ab6-936f-3ab31c2f48c4.png)

# 🔎 OverView  
반도체 및 LCD 공정 및 제품이 고도화 되어감에 따라 공정의 안정적 운영이 더욱 중요해 지고 있습니다.  
따라서, 제조 장비에 대한 효율적 이용측면에서 장비 엔지니어링에 대한 솔루션을 생각하지 않을 수 없게 되었습니다.  
이러한 배경에 따라, 에임 시스템은 반도체 및 LCD 공장 자동화 시스템 구축의 많은 경험을 바탕으로 SEComEnabler 와 nanoMC 를 개발하게 되었습니다.  

SEComEnabler 는 SECS Protocol 을 완벽히 제공하는 솔루션으로, nanoMC 는 SEComEnabler 를 내부적으로 사용하면서, 보다 향상된 장비 자동화 시스템 구축 솔루션입니다.  
Framework 을 바탕으로, 제공되는 수많은 Technical API 와 SEMI API 를 통해 개발자는 보다 빠르고, 안정된 시스템 구축을 할 수 있습니다.   

### nanoMC의 장점  
###### - 개발 기간의 단축  
Framework 기반의 API 를 사용함으로써, 개발 기간을 현저히 줄인다.  
###### - 유지 보수의 편리성  
Internal 코드 형태에서 WorkFlow Context 형태로 전환   
###### - Downtime 이 최소화되는 시스템  
Recompile 과 Restart 가 필요없는 시스템 구축  
###### - WorkFlow 시스템  
원하는 형태의 Business Process 를 정의하고, 이를 각각의 조건에 따라 (복수)실행  

# 📔 MC Studio  
Studio 는 nanoMC Framework 을 사용하는 장비 서버 프로그램을 개발하고, 이를 운영하기 위해 사용하는 User Interface Tool 입니다.  
Database 와 연동으로 모델링 데이터의 무결성을 확보하고, 사용자 권한을 지정함으로써, 데이터 오류를 미연에 방지합니다.  
  
사용자들은 비즈니스 요구사항, 재사용 가능한 자산(Container), 관리자 수준의 커뮤니케이션 등을 위한 모델을 생성해 낼 수 있습니다.  
쉬운 UI 와 강력한 패턴 엔진은 사용자들로 하여금 비즈니스 요구 사항을 만족시킬 수 있을 뿐만 아니라, 개발 팀도 쉽게 이해할 수 있는 풍부한 의미를 가진 애플리케이션 아키텍쳐를 구성할 수 있도록 해 줍니다.  
  
사용자가 강력한 패턴 기능을 활용하여 정의한 Process 단위들을 자동 변환하게 해 줌으로써, 설계 및 구현을 통제할 수 있도록 해 줍니다.  
이러한 자동화 기능은 언제나 같은 결과를 도출해낼 수 있으므로, 사용자가 보다 효과적으로 작업을 수행할 수 있게 해줍니다.  
  
nanoMC 환경하에서 Studio 를 사용할 것을 강력히 추천합니다.  

###### MC Studio의 기능
![image](https://user-images.githubusercontent.com/78777059/166394112-333b414e-3910-4216-855c-bc86f7cfac4c.png)  

###### UI 화면
![image](https://user-images.githubusercontent.com/78777059/166394151-dfc19798-d67c-4a17-a7ab-92993dcd640b.png)


# 📖 MC Wizard  
nanoMC Framework 을 사용해서 장비 서버 프로그램을 개발할 때, 개발자에게 Guide 역할을 해줍니다.  
Wizard의 주요기능 두가지는 다음과 같습니다.  
1. EAP 프로그램 Template 을 제공  
2. 사용자 컴포넌트를 개발하기 위한 Interface 를 생성  

###### UI 화면
![image](https://user-images.githubusercontent.com/78777059/166394374-d47d5c55-e2a6-4b01-b015-534f2f68766e.png)  


# 📑 MC Agent  
Agent는 EC에서 실행되는 프로그램으로 다음의 두 가지 역할을 하고 있습니다.  

###### - 배포 및 파일 관리
배포 이벤트( Server Moder의 추가 및 업데이트 )가 발생을 하게되면 Agent는 Database로부터 Studio를 통해 설정해준, Application을 실행하기 위해 필요한 파일들을 다운로드 하여 특정 Directory에서 관리합니다.  
###### - Studio를 통한 Application의 원격 실행
EC와 네트워크로 연결된 Computer에서 Studio를 통해 특정 EC에 있는 특정 Application의 실행을 명령할 수 있는데, 이 명령을 특정 EC에 있는 Agent가 받아 Application을 구동시키는 역할을 합니다.  


# ⚙️ MC Framework  
자동화 프로그램에 대한 기술적 틀을 만드는 것은 필수입니다. 개발 뿐만 아니라, 유지 보수 측면까지 고려해야만 합니다.  
“nanoMC Framework 이라 함은 반도체 및 LCD 장비 자동화 프로그램에 대한 기술적 틀을 제공함” 을 의미하며, 이것은 마치 컴퓨터를 사용하기 위해 제일 먼저 Operating System 을 설치하는 것과 같다고 볼 수 있습니다.  
  
수많은 API 를 제공함으로써, 개발자는 개발 기간이 단축되고, 표준화된 코드를 사용할 수 있습니다.  
  
자동화 요구 사항이 훨씬 많아지고, 복잡해짐으로써, 자동화 프로그램은 다음과 같은 세가지 역할을 수행할 수 있어야 합니다.  
이것은 nanoMC Framework 을 사용하는 중요한 이유가 됩니다.  

“nanoMC Framework 은 장비 자동화 프로그램을 구성할 때 필요한 공통요소를 엮어 만든 것입니다” 라고 앞에서 설명한 바와 같이,  
지금까지 우리가 항상 해왔던 반복적인 작업과 의미없는 작업들을 프레임웍 Level 에서 지원해 줌으로써, 개발자는 실제 비즈니스 로직을 더욱더 충실하게 작업할 수 있게 됩니다.  


# 💡 License
![image](https://user-images.githubusercontent.com/102704655/161007121-8da3684a-c5bc-4bc6-8247-6ea363a340eb.png)  
**Copyright (c) 1995-2004 AIM Systems Co. All rights reserved.**
###### The information in this document is subject to change without notice and should not be construed as a commitment by AIM Systems, Inc. While all reasonable care has been taken to ensure accuracy, AIM Systems, Inc. assumes no responsibility for any errors that may appear in this document.
###### The software described in this document is furnished under a license and may be used or copied only in accordance with the terms of such license.
###### No part of this document may be reproduced in any form of by any means without permission in writing from AIM Systems, Inc.
###### nanoMC is a trademark of AIM Systems, Inc.

# 📫 Contact
http://www.aim.co.kr/
