# what is EAP?  
EAP(Equipment Application Program)는 CIM과 시스템 역할은 유사하지만 큰 차이점이 있다.  
CIM은 장비Level에 가까운데 EAP는 Host 영역이다.  

EAP의 역할은 상위 Host 시스템 (MES, FDC, SPC 등등)과 interface 를 하면서 장비를 Control 하고 Event수집 및 DataCollection 하는 것이다.  
EAP는 SEMI에서 본래 반도체 공장에 장비와 Host 통신 인터페이스를 위한 표준을 정하고 이를 제어하고 데이터를 수집하기 위한 interface 시스템으로 볼 수 있다.  
초기에는 반도체 공장에 장비 interface 시스템이였으나 LCD/OLED 로 확대 되었다.  
물론  
상위 Host시스템 (MES, FDC, SPC, MCS 등등 에서 직접 interface 를 할 수 있으나 interface 를 분리해서 운영하는게 일반적이다.  
이는 시스템의 목적이 달라서 서로를 구분하고, Network traffic 을 분리하고, Load balancing 하는 측면이 있다.
EAP는 각 기업의 site 공장마다 다르게 용어를 구분하기도 한다.  
TC(Tool Control), MC(Machine Control), EIS 등등 기업에 따라서 용어가 다르지만 기능은 동일하다.

##### Scope of EAP
![image](https://user-images.githubusercontent.com/78777059/166433011-46934c5c-d928-4064-b947-2386676ebe71.png)  

##### SW Architecture
![image](https://user-images.githubusercontent.com/78777059/166433048-c3c4b17c-a29d-4207-8975-411d5086265d.png)  


# SECom Enabler
SECS Protocol을 따르는 통신 Driver.  
(Semiconductor Equipment Communication Standard)  

SEComEnabler는 다음과 같이 구성되어집니다.  

-	SEComClient  
SEComEnabler를 사용하여 빠르게 Communication 환경을 구성할 수 있도록 도와주는 Helper Tool 입니다.  
-	SEComDevTool   
SECS 통신에 필요한 Messgae들을 정의해놓은 SMD 파일을 빠르게 만들어낼 수 있도록 도와주는 Tool 입니다.  
- SEComSimulator  
SMD 파일을 이용하여 SECS Communication을 Simualting 할 수 있는 Tool 입니다.  
-	SEComLibrary  
SEComDriver를 이용하여 Custom Application을 만들고자 할 때 사용하는 Library 파일입니다.  
-	Examples  
SECSLibrary를 이용하여 구현한 Template Project입니다.  
-	Document  
SEComEnabler 사용설명서 입니다.  


