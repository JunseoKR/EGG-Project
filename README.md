# EEG-AP
## 🏫 Taejang High School / 태장고등학교

<br/>

# 📄 융합탐구 프로젝트 [ 3학년 ]

* * *

<br/>

<h1><b><div align="center"><a href="https://junseokr.notion.site/65a68e10ad714cb1aa8a5ab8551abe7f" target='_blank'>
    📄 Project Report 〔 Notion 〕
</a></div></b></h1>
<h3><div align="center">
    ✅ Notion으로 읽는 것을 추천드립니다.
</div></h3>

<br/>

* * *

<br/>

## ✔️ 1. 연구 주제

```
🧠 고등학생의 우울감 및 스트레스 진단과 개선 방법의 뇌파 측면에서의 접근에 대한 연구
```

<br/>

## ✔️ 2. 연구동기 및 목적

OECD 회원국 중 자살률 최고 수준을 지닌 우리나라 전체 자살자 수는 2020년 기준 13,195명이었다고 한다. 2019년 자료로 비교해보면 우리나라 자살률은 24.6명으로 OECD 평균인 11명의 2.2배이다. 

여기서 청소년인 우리의 눈에 들어온 자살률 데이터는 청소년의 자살률이 증가하는 추세라는 점이였다. 2020년도 청소년 자살자 수는 957명으로 2019년에 비해 81명 증가했다. 

보건복지부에 따르면 청소년 자살 증가의 주요동기는 정신적 문제라고 한다. 또한 청소년 자살률 증가는 우리나라 뿐만 아니라 전 세계적인 문제라는 점을 알게 되었다. 청소년 자살의 원인을 알아보고자 통계자료를 조사하니, 한림대 자살과 학생정신건상 연구소에서 조사한 자료에서 청소년 자살자들의 대부분의 문제는 26.8%인 학교성적문제가 가장 높았다는 점을 확인할 수 있었다. 

뿐만 아니라 또다른 인터뷰를 참고하여, 정신과 전문의 송후림 박사는 최근 자살이 증가하는 것은 개인의 문제가 아니라 사회의 문제이며 특히 청소년은 치열한 입시경쟁속에서 한순간의 작의 실수도 허용되지 않는 주변 환경을 견디기 힘들다고 분석했다는 점을 알 수 있었다$^1$. 

![ND_1.jpg](/Images/ND_1.jpg)

![ND_2.jpg](/Images/ND_2.jpg)

이러한 OECD 수치자료와 인터뷰내용을 접한 우리는 청소년 자살의 근본적인 이유를 스트레스라고 생각했고 이를 해결할 수 있는 방안을 모색하고자, 학생들의 스트레스 경향을 뇌파 측정과 뇌파 파형 분석을 통해 밝혀내는 것이 이 연구의 목적이다.

<br/>

---

## ✔️ 3. 이론적 배경

### **〔 뇌 〕$^2$**

1. **뇌파란?**
    
    ```
    🧠 뇌의 활동에 의하여 일어나는 전류
    ```
    
    뇌파는 두뇌의 뉴런들 내에서 이온 흐름에 따른 전류 변화를 의미하며, 이러한 전류의 흐름 및 이를 측정하는 것을 모두 뇌파라고 정의함.
    

1. **뇌의 구조**

![B1.png](/Images/B1.png)

![B2.png](/Images/B2.png)

1. **뇌파 발생 원리**
    1. **뉴런의 신경전달**
        
        ![E1.png](/Images/E1.png)
        
        ```
        ⚡ 휴지전위 → 분극 → 탈분극 → 활동전위 → 재분극 → 과분극
        ```
                
        | 분극 | 자극을 받지 않은 뉴런에서 세포막 안쪽은 상대적으로 음(-)전하, 세포막 바깥쪽은 양(+)전하를 띠고 있는 상태이다. |
        | --- | --- |
        | 탈분극 | 휴지 상태의 뉴런에 자극을 주면 Na+통로가 열려 Na+이 세포 안쪽으로 들어와 막전위가 상승하는 현상이다. |
        | 재분극 | 탈분극이 일어났던 부위에서 대부분의 Na+ 통로가 닫혀 Na+이 세포 안쪽으로 들어오지 못하고, K+통로가 열려 K+이 세포 밖으로 확산하면서 막전위가 하강하는 현상이다. |
        
        뇌파를 측정할 때 단일 신경세포의 활동 전위만으로는 적절한 뇌파를 측정할 수 없다.
        
        - 대뇌피질의 뉴런에서 발생한 활동전위가 두피까지 전달되기 위해서는 뇌막, 뇌수액, 두개골 등을 지나와야 하는데 이때 대부분의 전위가 소실되어 사실상 두피에서는 노이즈 수준의 전위밖에 형성되지 않기 때문이다.
        
    2. **다수의 뉴런 활성화 ( 동시다발적 )**
    단일 신경세포의 활동 전위가 아닌 각 뉴런들의 활동전위의 합이 충분히 커져야 뇌파 측정이 가능하다. 
        
        ```
        ⚠️ 뉴런의 전류가 서로 다른 방향으로 흐를 경우 총 전류는 상쇄되어 두피부분에서 충분한 전위차 발생하지 않는다. 하지만 대뇌 피질에 있는 피라미드 세포라고 불리는 뉴런들이 동일한 방향으로 전류가 흐르도록 설계되어 있어 두피 부분에서 전극을 이용하여 뇌파를 측정할 수 있다.
        ```
        
        ![B1.png](/Images/B1.png)
        
        실제로 두피에서 측정되는 뇌파는 각 뉴런에서 발생하는 활동전위의 합이 아니라 각 피라미드 세포의 연결지점인 시냅스에서 발생하는 시냅스 후기 전위의 합이다.
        
        - 각 뉴런에서 발생하는 **활동 전위**의 합
            - 전위 약 10배정도 큼, 지속시간 짧음 ➡️ 실제 전달 떨어짐
        - 각 피라미드 세포의 연결지점인 **시냅스**에서 발생하는 시냅스 후기 전위의 합
            - 전위 작음, 지속시간 10배정도 긺 ➡️ 의미있는 신호 얻을 수 있음

1. **뇌파 측정 원리**
    - 뇌파는 신경 전류의 흐름이 두피에 만드는 전위차를 측정하는 것이므로 뇌파의 측정을 위해서는 최소 2개 이상의 전극이 필요함.
    - 하나의 전극을 기준 전극(reference electrode) 으로 지정하고 기준 전극과 다른 전극들 사이의 전위차를 측정하는 단극(unipolar) 측정 방식에서는 평균 기준 전극 방식을 이용하면 절대 전위를 근사할 수 있지만, 머리가 완전 구형이며 매우 고밀도로 전극이 되어 있어야 한다는 가정이 필요하기 때문에 실제로는 절대 전위와 어느 정도 차이가 있다.
    
    ![E2.png](/Images/E2.png)
    
    1. **〈 Scalp EEG (두피 뇌파 측정법) 〉**
        
        ```
        🧠 두개골의 외부, 다시 말해 두피에 전극을 부착하여 전위차를 측정하는 방식
        ```
        
        전기 전도도가 상대적으로 낮은 두개골을 지날 때 뇌에서 발생하는 전기적 신호가 상당수 소멸하기 떄문에 강한 시그널을 받기 위해서는 Intracranial EEG 방식을 사용해야 하지만 두개골을 절개해야 하기 때문에 Scalp EEG 방식이 일반적으로 활용된다.
        
    2. **〈 Intracranial EEG (대개강 내 뇌파 측정법) 〉**
        
        ```
        🧠 두개골을 열어 내부의 대뇌 피질 부분에 전극을 부착하여 전위차를 측정하는 방식
        ```
        

1. **절대파워 ( Absolute Power )$^3$**
    
    ```
    🧠 푸리에 변환과 스펙트럼 분석에 의해 나타나는 주기에 따른 진폭의 양
    ```
    
    - 〈 스펙트럼 분석 〉
        
        푸리에 변환 후 나타나는 각 성분에서의 $Sine$파, $Cosine$파를 주기에 따른 진폭의 양으로 표시하는 것
        
    - 〈 절대파워 〉
        
        **뇌의 각 부위에서의 Delta / Theta / Alpha / Beta / Gamma파의 Power의 양**
        
        - 이는 전기적인 신호의 실제적인 양을 반영함.
        - 절대파워의 변화는 병적인 상황이나, 정상적인 상태의 변화에서도 생기며, 뇌의 활동이 어느 정도가 되는가를 의미함.
    
2. **주파수별 뇌파**
    1. **델타파 (Delta wave) - 0.2 Hz ~ 4 Hz**
        
        진폭이 가장 크고 속도가 가장 느린 뇌파로서, 어린 아기로부터 정상적으로 나타나며 대뇌 피질하 병변과 함께 국소적으로 나고(후두부), 서파수면을 하는 성인에게서 정상적으로 나타남 ( 전두부에서 두드러짐 )
        
    2. **세타파 (Theta wave) - 4 Hz ~ 8 Hz**
        
        어린아이에게는 정상적으로 관찰되고, 성인에서는 졸음, 각성, 명상 상태일 때 관찰된다.
        
    3. **알파파 (Alpha wave) - 8 Hz ~ 13 Hz**
    성인기에는 각 개인이 고유한 알파 리듬 주파수를 가지고 있으며 노년이 되기 전까지는 거의 변하지 않는다.
    4. **베타파 (Beta wave) - 13 Hz ~ 30 Hz**
    다양하고 변화가 있는 주파수를 가진 저진폭 베타는 종종 활동적이고 바쁘거나 불안한 생각과 적극적인 집중과 관련이 있다. 민감한 상태에 있거나 불안한 환자에게서 주로 나타난다.
    5. **감마파 (Gamma wave) - 30 Hz ~ 50 Hz**
    외적 의식으로 불안, 흥분의 강한 스트레스 상태에서 전두엽과 두정엽에서 비교적 많이 발생하는 뇌파이다.

<br/>

---

### **〔 푸리에 변환 〕$^4$**

![FT.png](/Images/FT.png)

```
➗ 시간에 대한 함수를 주파수 성분으로 분해하는 변환
```

하나의 신호를 서로 다른 주파수를 갖는 신호의 합으로 볼 수 있게 쪼개주는 것.

- **〈 주파수 성분으로 분해 〉**
    - 주파수 축 위에 각 성분이 얼만큼 들어있는지 수치적으로 표현하는 것
    - 여러 주파수 성분을 가지는 신호를 주파수 성분별로 함량을 표시함

![FFT_1.png](/Images/FFT_1.png)

![FFT_2.png](/Images/FFT_2.png)

![FFT_3.png](/Images/FFT_3.png)

〈 지수에 들어있는 $f$ 〉 : 회전속도

```
➗ 주파수 f값이 커질수록 회전 함수의 회전 속도가 빨라짐.
```

회전 함수의 값을 $x$축 또는 $y$축에서 본다면 우리가 알고 있는 코사인, 사인파와 같은 역할을 한다.

![FFT_4.png](/Images/FFT_4.png)

```
➗ 수식을 추상적으로 표현 ➡️ 내적 과정을 통해서 얼마나 닮았는지를 계산함
```

> **하나하나의 원소를 모두 곱하고 더해주는 과정을 내적이라고 한다.**
> 

푸리에 변환은 주어진 신호$x(t)$와 함수$e^{-j2πft}$를 곱해주고 모든 시간 t에 대해 더해주는 것인데 이는 하나하나의 원소를 모두 곱하고 더해주는 내적으로도 볼 수 있다. 

따라서 앞의 수식을 추상적으로 표현하면 내적 과정을 통해서 신호 $x(t)$와 $e^{-j2πft}$가 얼마나 닮았는지를 계산하는 것이라고 표현할 수 있다.

다시 말해 주어진 신호 $x(t)$가 그 주파수에 회전 함수의 성분이 얼마나 있는지를 물어보고있는 것이다.

![FFT_5.png](/Images/FFT_5.png)

```
🛠 주어진 신호를 비교용 신호들과 하나하나 내적해보면서 닮은 정도를 나타내는 것
```

- 주어진 신호에 해당 비교용 신호 성분이 들어있으면 닮은 정도는 높게 나올 것이고 그렇지 않으면 낮게 나올 것이다.
    - 주파수 성분이 얼만큼 들어있는지 알 수 있기 때문에 주파수 분석이 가능하다.
- **〈 시간 신호를 주파수 분석하면 좋은 점 〉**
    - 푸리에 변환 자체만으로는 주파수의 관점에서 신호를 볼 수 있는 정도의 도움을 받을 수 있음.

➡️ 응용하면 불필요한 주파수 성분을 제거해 주는 일을 할 수 있게 됨

![FFT_6.png](/Images/FFT_6.png)

```
🛠 신호에 고주파 잡음이 껴있는 상황
```

〔 1️⃣ ➡️ 2️⃣ 〕 **푸리에 변환**

- 주파수 관점에서 신호의 성분을 파악할 수 있음.

〔 2️⃣ ➡️ 3️⃣ 〕 **불필요한 주파수 성분 제거**
〔 3️⃣ ➡️ 4️⃣ 〕 **역 푸리에 변환**

- 다시 합성함으로써 고주파 잡음이 제거된 신호를 얻을 수 있음.

<br/>

---

### 〔 Savitzky-Golay Filter 〕$^5$

![SGF.png](/Images/SGF.png)

순간적으로 튀는 값(Noisy Sine)의 영향을 많이 받는 데이터를 **평활화** 하기 위해 짧은 구간내에서 다항 회귀모델을 구축해야한다. 하지만 매번 다항 회귀식으로 계산하는것이 힘들기 때문에 시간에 따른 구간마다 회귀모델을 계산하지 않고 특정한 Impulse Response를 마련함으로써 신호를 Smoothing하는 것이다. 필터링 하고자 하는 값의 앞에 있는 값과 뒤에 있는 값의 중간값을 새로운 값으로 얻게하며 노이즈, 무의미한 변동을 제거한다.

시간샘플을 중심으로 왼쪽으로 $A$개 오른쪽으로 $A$개의 신호를 획득하고 이 신호를 $n$차 회귀모델로 대체하는 것이다. 굳이 시간샘플을 중심으로 하는 신로를 분석하는 이유는 회귀모델을 Smoothing할때 필요한 Impluse response이기 때문이다. Impluse response를 이용해 원래 신호에 합성곱(Convolution)을 해주면 결국 Smoothing을 할 수 있다.

$$
y(n) = On(x(n))
$$

어떤 시스템의 입력이 $x(n)$, 출력이 $y(n)$ 이고 입력과 출력을 연결 시켜주는 시스템을 $On()$ 이라고 한다.   

$$
\sum_{k=-∞}^{∞} x[k]O_n (δ[n-k])
$$


➗ $O_n(δ[n])$을 $h[n]$이라고 정의하자.

➗ $h[n]$을 Inpulse Response라고 부른다.

<br/>

---

## ✔️ 4. 연구정보

### 📄 연구대상

- 대상군의 데이터는 기말고사가 끝난 태장고등학교 3학년 4명을 대상으로 하였음.

### 📄 측정 장치

- __[BackYard Brains](https://backyardbrains.com/)$^6$ | The Heart and Brain SpikerBox$^7$__ [ Custom EEG Arduino - Scalp EEG ]

### 📄 측정 부위

- **P3, P4 [ 10-20 System ]$^8$** / 단일채널

### 📄 통계 방법

- IBM사의 SPSS$^9$ 통계 분석 소프트웨어를 이용함.

### 📄 가설

```
1️⃣ 무자극 상태의 Alpha Power가 자극 상태의 Alpha Power보다 높을 것이다.
```

```
2️⃣ 자극 상태의 Delta / Theta Power가 무자극 상태의 Delta / Theta Power 보다 더 낮을것이다.
```

<br/>

---

## ✔️ 5. 연구과정

1. 무자극 / 자극(불안 / 긴장) 상태의 데이터를 측정하기 위한 환경을 조성한다.
    - **무자극 상태**
        - 의자에 앉아 측정 장치를 부착, 편안한 상태에서 EEG 데이터를 측정, 저장한다.
            - 눈을 계속 감지 않도록 함.
            - 인위적으로 눈을 움직이지 않도록 함.
            - 몸의 움직임이 없도록 함.
    - **자극 상태**
        - 의자에 앉아 측정 장치를 부착, **시간 제한이 있는 수학 문제 풀이**를 통한 불안을 유발한 상태일 때 EEG 데이터를 측정, 저장한다.
            - 눈을 계속 감지 않도록 함.
            - 몸의 움직임이 없도록 함.

1. 무자극 / 자극(불안 / 긴장) 상태의 EEG(.WAV) 데이터를 측정 후 분류한다.
    - 대상자 4명 각각 무자극 상태 / 자극(불안 / 긴장) 상태에서 30초씩 3번 측정함.

1. 개발한 파이썬 코드를 통해 EEG(.WAV) 데이터를 샘플링하고 Savitzky-Golay Filter로 Noisy Sine을 제거한 후 [FFT](https://en.wikipedia.org/wiki/Fast_Fourier_transform)$^{10}$ 처리하여 주파수별 데이터를 추출함.
    - 분석 주파수
        - Delta : 0.2 Hz ~ 4 Hz
        - Theta : 4 Hz ~ 8 Hz
        - Alpha : 8 Hz ~ 13 Hz
    - 데이터 처리 / 저장 ［자동화 ］
        - 30초 동안 0.01초 간격으로 측정된 데이터를 100개씩 그룹화하여 총 30개의 그룹을 생성한다.
        - 측정한 모든 데이터를 FFT, Savitzky-Golay Filtering 처리하여 데이터 별로 Delta / Theta / Alpha Power 데이터를 추출, 저장한다.

1. [IBM SPSS](https://www.ibm.com/analytics/spss-statistics-software?mhsrc=ibmsearch_a&mhq=spss)를 통해 데이터를 분석한다.
    1. 30개 그룹을 각각 평균분석하여 평균 주파수값을 도출한다.
    2. 평균 주파수값 30개의 평균을 구한다.
    3. 동일한 상황에서 측정하고 평균분석된 3개의 데이터 값이 모두 다르므로 가장 신뢰도 높은 데이터를 선택하기 위해 각 데이터의 시간에 따른 Power 값과 그래프를 비교분석하여 값이 과도하게 급상승 / 급하강하지 않는 데이터를 선택한다.
    4. 무자극 / 자극 상태의 Delta / Theta / Alpha Power 데이터를 차이비교한다.
        - 절대파워 수치값 비교
        - 백분위 비교

1. 정렬된 무자극 / 자극(불안 / 긴장) 상태의 데이터와 우울증 환자의 EEG 데이터를 비교분석한다.
    - 타 논문$^{11}$ 우울증 환자의 뇌파 데이터와 경향비교분석하였음.

<br/>

---

## ✔️ 6. 연구결과

```
💻 Delta / Theta / Alpha Power Data
```

|  | Subject 1 [ 무자극 ] | Subject 1 [ 자극 ] |  |
| --- | --- | --- | --- |
| Delta | 495.1959 | 995.6701 | 101.07%$p$ 증가 |
| Theta | 377.7940 | 1172.5385 | 210.37%$p$ 증가 |
| Alpha | 720.7569 | 2735.8973 | 279.59%$p$ 증가 |

|  | Subject 2 [ 무자극 ] | Subject 2 [ 자극 ] |  |
| --- | --- | --- | --- |
| Delta | 548.5284 | 351.3204 | 35.95%$p$ 감소 |
| Theta | 246.6136 | 268.5186 | 8.88%$p$ 증가 |
| Alpha | 184.2492 | 265.2032 | 43.94%$p$ 증가 |

|  | Subject 3 [ 무자극 ] | Subject 3 [ 자극 ] |  |
| --- | --- | --- | --- |
| Delta | 1523.8579 | 1401.2519 | 8.05%$p$ 감소 |
| Theta | 1063.4032 | 1151.5245 | 8.29%$p$ 증가 |
| Alpha | 1117.5066 | 2403.4597 | 115.07%$p$ 증가 |

|  | Subject 4 [ 무자극 ] | Subject 4 [ 자극 ] |  |
| --- | --- | --- | --- |
| Delta | 661.4917 | 789.9828 | 19.42%$p$ 증가 |
| Theta | 474.8888 | 740.5128 | 55.93%$p$ 증가 |
| Alpha | 1247.1455 | 2256.1408 | 80.9%$p$ 증가 |
- Subject 2 측정 당시 대상자의 머리카락 길이가 길어 전극이 두피에 제대로 부착되지 않음으로서 절대파워의 값들이 낮게 측정된 것으로 생각됨.
- 〈 Subject 4 → Subject 1 → Subject 3 → Subject 4 〉 순서대로 유의미한 데이터라고 생각됨.

<br/>

---

```
📄 데이터의 정량적 분석과 결론
```

**〈 1️⃣,** 2️⃣**번 가설 〉 - 거짓**

- 무자극 상태일 때가 자극상태일 때보다 Alpha Power가 더 높게 측정될 것이라고 생각했지만, 자극 상태일 때 뇌가 활발해져 무자극 상태일 때보다 모든 절대파워가 더 높게 나왔다.
- 무자극 상태일 때보다 자극 상태일 때의 절대파워가 전체적으로 더 높게 나오므로 정량적인 수치비교보다는 차이비교를 통한 경향적 비교방법이 적합하다고 판단함.

```
⚠️ 연구에서 측정한 데이터와 타 연구 우울증 환자 데이터의 수치나 단위가 달라 정량적인 비교가 불가능하여 데이터의 경향을 기준으로 비교하였음.
```

> 뇌파 스펙트럼을 분석한 결과 약물복용을 하지 않은 우울증 환자가 정상인에 비해 알파파워와 베타파워가 높다는 결과, 우반구에서 절대델타 세타파워가 증가하는 결과, 또는 델타파워만 정상인에 비해 높다는 결과 등 다양한 연구 결과가 있다. 
이 중 우울증 환자의 알파파워가 증가되었다고 보고한 연구들이 절반정도였으며 델타 세타파워에 관련된 결과들은 일치 하지 않았다$^{12}$.
> 

분석 과정에서 우울증에 걸린 사람들의 뇌파 스펙트럼 분석 결과들 중 가장 신뢰성이 높은 알파파워의 증가를 측정한 데이터의 분석기준으로 삼았다.

연구에서 측정한 **〈 무자극 상태 → 자극 상태 〉** **데이터들의 증가율**을 비교해봤을때, ［Subject 1］ 279.59%$p$ 상승 / ［ Subject 2 ］ 43.94%$p$ 상승 / ［ Subject 3 ］ 115.07%$p$ 상승 / ［ Subject 4 ］ 80.9%$p$ 상승으로 타 논문의 연구 결과와 비슷하게 **4명의 대상자 모두 Alpha Power의 수치가 가장 크게 상승**했다.

```
💡 분석 결과를 통해 불안과 긴장을 느끼는 학생들의 우울감과 우울증 환자의 뇌파 사이의 연관성을 확인함.
```

<br/>

---

## ✔️ 7. 연구 결론 및 기대 효과

```
💡 불안과 긴장을 느끼는 학생들의 우울감과 뇌파 간의 연관성을 데이터 측정과 분석을 통해 입증하였다. 측정한 학생들의 뇌파를 우울증 환자의 뇌파와 비교, 분석하여 극단적인 선택을 예측하고 이에 대비할 방법을 마련할 수 있었다.
```

### 〈 우울증 극복 방법 〉

1. **〔 건강한 식단 섭취 〕**
    - 먹는 음식은 몸과 마음이 느끼는 방식에 상당한 영향을 미칠 수 있음.
2. **〔 더 많은 운동하기 〕**
    - 하루의 15분의 적당한 운동이 필요함.
    - 운동은 코티솔과 같은 스트레스 호르몬을 분해하는 동시에 기분 좋은 엔돌핀을 방출함.
3. **〔 양질의 수면 〕**
    - 규칙적인 취침시간과 기상일정을 유지하며 뇌에게 규칙적인 신호를 전달할 수 있도록 함.
4. **〔 친구 및 가족과 사교 〕**
    - 가족 및 친구와 함께 방문할 시간을 정하는 둥 다른 사람에게 의지할 수 있는 특정 시간과 장소를 확보함.
5. **〔 재미있는 활동 계획 〕**
    - 여가시간을 차지하는 많은 관심사, 취미 및 좋아하는 활동을 함.
6. **〔 자신에게 친절 〕**
    - 어려운 상황에서 자신을 도울 수 있는 중요한 방법임.

<br/>

---

## ✔️ 8. 느낀 점

```
💡 〈 30505 홍준서 〉
EEG 커스텀 아두이노를 통해 EEG 데이터를 측정하고 FFT, Savitzky-Golay Filtering, CSV 저장과 같은 각 기능들을 모듈화하여 객체지향적인 Python 코드를 구성, 개발하였다. 또한 팀원들과 함께 SPSS를 통해 EEG 데이터들을 분석하고 다른 논문의 데이터와 비교하였다. 이러한 연구 과정에서 변인통제가 되지 않아 부정확한 데이터가 추출되고, 집단 데이터 분석 방법에 대한 문제점을 해결하는 과정과, 각 모듈의 기능을 설계할 때 이론을 제대로 이해하지 못해 구성하는 과정에서 어려움이 있었지만, 모든 변인들을 통제한 후 EEG를 재측정하고, 데이터 분석 방식에 대해 팀원들과 논의하고, 푸리에 변환과 Savitzky-Golay Filter에 대한 자료 탐색과 이해를 위한 탐구하는 과정을 통해 어려움들을 해결할 수 있어서 성취감을 느꼈다. 뇌와 같은 EEG와 관련된 내용을 심화적으로 탐구할 수 있어서 좋았고, 여러 EEG 데이터들을 코딩을 통해서 처리, 분석, 저장하면서 데이터를 다루는 역량도 향상된 것 같아 뿌듯함을 느꼈다. 이후에 심화된 주제를 바탕으로 팀원과 협력하여 데이터를 분석하거나 수학적 원리를 이해하는 프로젝트를 진행하고 싶다.
```

```
💡 〈 30825 정X현 〉
데이터를 측정하는데 필요한 SCALP EEG 방식과 데이터를 분석하고 결과를 도출하는데 필요한 푸리에 변환과 Savitzky-Golay Filter, 그리고 SPSS에 대해 이번 프로젝트를 진행하면서 처음 들어봤고 낯선 지식이라서 이것들의 이론과 원리를 이해하는데 어려움이 있었다. 하지만 스스로 많은 양의 여러 자료들의 찾아보면서 공부하고, 내가 공부한 것들을 팀원들에게 설명하고, 팀원들이 공부한 내용에 대한 설명을 들으면서 이론과 원리에 대해 이해할 수 있었고 이런 심화적인 내용을 탐구하는 과정을 통해 자기주도적 학습 능력과 협력 학습 능력을 기를 수 있었다. 그리고 우리가 직접 실험 과정에서 측정하고 분석한 데이터를 통해 불안과 긴장을 느끼는 학생들이 우울감과 우울증 환자의 뇌파 사이의 연관성을 입증할 수 있어서 뿌듯했고 성취감을 느꼈다.
```

```
💡 〈 31010 송X수 〉
데이터를 측정하고 분석하는 과정이 낯설고 어렵게 느껴졌지만 친구들과 함께 협업을 하며 프로젝트를 진행했고, 관련된 자료를 찾아보고 서로 이야기 하는 과정에서 새롭게 알게된 내용이 많은 것 같다. 푸리에 변환, 필터링 과정이나 SPSS의 이론이 복합하고 평소에 공부하던 내용과는 달라서 이해하는데 어려움이 있었지만 세부적인 내용과 관련 자료를 스스로 찾아보며 이해하려고 노력하는 과정에서 자기주도성을 향상시킬 수 있었다. 우울한 상태에서의 뇌파와 그렇지 않은 상태에서 뇌파의 주파수에 대한 내용이 자료마다 달라서 어떤내용이 사실인지 확인하는 과정에서 아직 이 분야에 대한 연구가 지속되어야 할 것 같고, 나중에 기회가 된다면심화된 실험을 해보고 싶다는 생각을 하게되었다. 학생들의 뇌파와 우울증 환자의 뇌파의 주파수를 비교하면서 학생들의 극단적인 선택을 예방 할 수 있는 방법까지 알아보는 의미있는 시간이었다.
```

```
💡 〈 31105 김X서 〉
실험을 하고 데이터를 분석하는데 있어서 우울증과 뇌파 관련 논문의 의견이 상충되는 지점, 측정된 데이터의 기준점을 설정하는 점에 있어 어려움을 겪기도 했지만, 팀원들과 함께 하나하나 생각하고 논의하며 최종적인 결론에 도달할 수 있어 뜻깊은 경험이였다고 생각한다. 또한 결론을 도출하기 위해 적용된 푸리에 변환, SPSS, Savitzky-Golay Filter의 개념부터 원리까지 이해하는 과정에서는 심화적 원리내용 그 자체 뿐만 아니라 낯선 지식을 자기주도적으로 학습하는 능력을 기를 수 있었다. 직접 실험하고 분석한 방법으로 우울증과 뇌파간의 연관성을 알아냈고, 이를 활용하여 청소년 극단적 선택의 예방에 한가지 해결책을 제시함으로써 도움을 줄 수 있어 뿌듯함을 느꼈다.
```

<br/>

---

---

## 🚀 Reference

1. 동아일보 : [중고생 자살원인 1위는 ‘성적’…학업 스트레스 크다](https://www.donga.com/news/It/article/all/20150525/71446025/1)
2. 연세대학교 의료공학연구센터 : [뇌파 측정과 동적신경영상 이론 및 응용](http://cone.hanyang.ac.kr/bioest/kor/pds/shortterm_lecture.pdf)
3. Jun Soo Kwon, M.D., Ph.D. : The Clinical Utility of EEG Mapping
4. 1） Wikipedia : [Fourier Transform](https://en.wikipedia.org/wiki/Fourier_transform)
2）공돌이의 수학정리노트 : [5분만에 이해해보는 푸리에 변환](https://youtu.be/YsG8fJsH9JE)
5. 1）Wikipedia : [Savitzky-Golay Filter](https://en.wikipedia.org/wiki/Savitzky%E2%80%93Golay_filter)
2）Plotly : [Smoothing in Python](https://plotly.com/python/smoothing/)
6. [BackYard Brains](https://github.com/BackyardBrains)
7. BackYard Brains : [The Heart and Brain SpikerBox](https://backyardbrains.com/products/heartAndBrainSpikerBox)
8. Wikipedia : [10-20 System (EEG)](https://en.wikipedia.org/wiki/10%E2%80%9320_system_(EEG))
9. IBM : [SPSS](https://www.ibm.com/kr-ko/analytics/spss-statistics-software)
10. Wikipedia : [Fourier Transform](https://en.wikipedia.org/wiki/Fourier_transform)
11. Jun-Seok Lee, MD, PhD **⋯ :** Power Spectral Analysis of Resting EEG in Unmedicated Major Depressive Disorder
12. Jun-Seok Lee **⋯ :** Power Spectral Analysis EEG Characteristics of Major Depressive Disorder
