# 강의 소개

:::{image} ./Principle_of_Economics.png
:alt: Principles of Economics
:align: center
:::

이 강의 노트는 현대 경제학의 핵심 원리를 데이터 기반으로 탐구하는 **경제학 원론(Principles of Economics)** 교과서입니다. 단순히 추상적인 이론을 암기하는 것을 넘어, 역사적 데이터와 현실의 통계를 통해 경제 현상을 실증적으로 분석하는 능력을 기르는 것을 목표로 합니다. 우리는 "왜 어떤 국가는 부유하고 어떤 국가는 가난한가?", "시장은 어떻게 작동하며 언제 실패하는가?"와 같은 근본적인 질문들에 대해 데이터가 들려주는 이야기에 귀를 기울일 것입니다.

본 강의는 전통적인 경제학 교육 방식을 넘어, **컴퓨테이셔널 사고(Computational Thinking)**를 경제학에 접목합니다. 정적인 그래프와 수식 대신, Jupyter Notebook을 활용하여 실제 경제 데이터를 다루고 시각화하며 이론을 검증합니다. 학생들은 Python과 같은 도구를 통해 경제 모형을 직접 시뮬레이션해봄으로써, 복잡한 경제 시스템의 작동 원리를 보다 직관적이고 깊이 있게 이해하게 될 것입니다.

강의의 구성은 경제학의 거시적 흐름과 미시적 기초를 체계적으로 연결하도록 설계되었습니다. 먼저 경제 성장의 역사적 배경과 자본주의 제도(Chapter 1)에서 출발해, 경제학자의 사고방식과 데이터를 다루는 방법(Chapter 2)을 익힙니다. 이어 개별 경제 주체의 선택과 시장의 작동 원리, 그리고 시장의 한계와 정부의 역할(미시경제학, Chapter 3~10)을 다루고, 마지막으로 이를 바탕으로 국가 전체의 소득, 성장, 경기 변동(거시경제학, Chapter 11~15)을 분석합니다. 이러한 흐름은 나무를 보며 숲을 이해하고, 다시 숲 속에서 나무의 역할을 재조명하는 통합적인 경제적 사고를 형성하는 데 도움을 줄 것입니다.

## 주차별 학습 내용

각 챕터별 학습 주제와 강의 노트 링크는 아래와 같습니다.

| 챕터 | 주제 | 주요 내용 | 강의 노트 | Colab | 과제 |
|:---:|:---|:---|:---:|:---:|:---:|
| **Chapter 1** | 경제문제와 경제체제 | 역사적 데이터(Maddison Project)를 통해 '대분기'와 소득 급증 현상을 확인합니다.<br>자본주의의 핵심 제도(사유재산, 시장, 기업)가 성장에 미친 영향을 분석합니다.<br>희소성과 선택이라는 경제학의 기본 원리를 데이터로 이해합니다. | [Link](./02-notebook.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voidmain443/economic_principle_book/blob/main/02-notebook.ipynb) | - |
| **Chapter 2** | 경제학의 본질 | 관찰-가설-검증의 과학적 방법과 경제 모형(추상화, ceteris paribus)을 이해합니다.<br>유인(incentive)과 의도치 않은 결과, 상관관계와 인과관계의 차이를 배웁니다.<br>실증적 분석과 규범적 분석을 구분하고, 자연실험(Card–Krueger)을 데이터로 다룹니다. | [Link](./chapter2.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voidmain443/economic_principle_book/blob/main/chapter2.ipynb) | - |
| **Chapter 3** | 시장의 작동 원리 | '정보로서의 가격'(하이에크)과 수요·공급의 법칙을 개별 최적화 관점에서 이해합니다.<br>시장 균형을 분권적 '가격 발견 과정'으로 파악합니다.<br>실제 원자재(커피·원유) 데이터로 공급·수요 충격을 분석합니다. | [Link](./chapter3.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voidmain443/economic_principle_book/blob/main/chapter3.ipynb) | - |
| **Chapter 4** | 탄력성과 시장 | 수요·공급의 가격탄력성을 정의하고 중간점법으로 측정합니다.<br>2015년 담배세 인상 사례로 실제 수요의 가격탄력성을 추정합니다.<br>조세의 귀착과 사중손실을 탄력성으로 분석합니다. | [Link](./chapter4.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voidmain443/economic_principle_book/blob/main/chapter4.ipynb) | - |
| **Chapter 5** | 소비자 선택 | 예산제약과 무차별곡선으로 효용극대화 선택을 도출합니다.<br>OWID·World Bank 데이터로 엥겔곡선을 확인하고, 대체효과·소득효과를 분해합니다.<br>행동경제학적 관점에서 합리성 가정을 재조명합니다. | [Link](./chapter5.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voidmain443/economic_principle_book/blob/main/chapter5.ipynb) | - |
| **Chapter 6** | 생산과 비용 | 생산함수와 한계생산체감, 단기·장기 비용곡선을 도출합니다.<br>한계비용과 평균비용의 관계로 최적 생산량을 도출합니다.<br>규모의 경제가 산업 구조에 미치는 영향을 분석합니다. | [Link](./chapter6.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voidmain443/economic_principle_book/blob/main/chapter6.ipynb) | - |
| **Chapter 7** | 완전경쟁시장 | 가격수용자의 이윤극대화(P=MC), 조업중단·장기균형을 학습합니다.<br>진입·퇴출을 통한 장기 조정 과정을 이해합니다.<br>World Bank 원자재 데이터로 일물일가·가격수렴을 확인합니다. | [Link](./chapter7.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voidmain443/economic_principle_book/blob/main/chapter7.ipynb) | - |
| **Chapter 8** | 불완전경쟁시장 | 독점·독점적경쟁·과점의 가격설정과 사중손실을 분석합니다.<br>게임이론(죄수의 딜레마, 내쉬균형)으로 전략적 상호작용을 모델링합니다.<br>통신·반도체 등 실제 산업의 집중도(HHI)를 측정합니다. | [Link](./chapter8.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voidmain443/economic_principle_book/blob/main/chapter8.ipynb) | - |
| **Chapter 9** | 생산요소시장 | 파생수요와 한계생산가치로 임금·이자 결정을 이해합니다.<br>최저임금·인적자본 등 노동시장 제도를 분석합니다.<br>World Bank 데이터로 로렌츠곡선·지니계수로 소득분배를 측정합니다. | [Link](./chapter9.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voidmain443/economic_principle_book/blob/main/chapter9.ipynb) | - |
| **Chapter 10** | 시장 실패와 정부 | 외부효과·공공재·정보비대칭으로 인한 시장 실패를 연구합니다.<br>피구세·코즈정리 등 교정 수단과 정부실패의 조건을 분석합니다.<br>OWID CO2 데이터로 환경 외부효과를 정량화합니다. | [Link](./chapter10.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voidmain443/economic_principle_book/blob/main/chapter10.ipynb) | - |
| **Chapter 11** | 거시경제학의 기초 | GDP(삼면등가)·물가·실업률의 측정 방법과 추이를 살펴봅니다.<br>World Bank 데이터로 한국 GDP를 지출측면으로 분해합니다.<br>GDP가 후생·분배·환경을 어떻게 놓치는지 비판적으로 검토합니다. | [Link](./chapter11.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voidmain443/economic_principle_book/blob/main/chapter11.ipynb) | - |
| **Chapter 12** | 장기 경제성장 | 솔로우 모형으로 자본축적과 정상상태를 분석합니다.<br>Penn World Table로 한국의 성장회계와 자본 심화를 수행합니다.<br>수렴가설과 제도의 역할을 데이터로 검증합니다. | [Link](./chapter12.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voidmain443/economic_principle_book/blob/main/chapter12.ipynb) | - |
| **Chapter 13** | 화폐와 금융 | 화폐의 기능·통화량·신용창조와 중앙은행의 통화정책을 분석합니다.<br>World Bank 통화량·물가 데이터로 화폐수량설을 검증합니다.<br>이자율 결정과 자산 가격(현재가치) 원리를 이해합니다. | [Link](./chapter13.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voidmain443/economic_principle_book/blob/main/chapter13.ipynb) | - |
| **Chapter 14** | 경기변동 | 총수요-총공급 모형으로 단기 경기 변동을 분석합니다.<br>재정·통화정책의 안정화 효과와 필립스곡선·오쿤의 법칙을 다룹니다.<br>World Bank 데이터로 오쿤의 법칙과 필립스곡선을 실증합니다. | [Link](./chapter14.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voidmain443/economic_principle_book/blob/main/chapter14.ipynb) | - |
| **Chapter 15** | 개방경제 | 비교우위와 무역의 이익, 관세 등 무역정책의 효과를 분석합니다.<br>환율 결정 이론과 국제수지 데이터로 개방경제를 이해합니다.<br>World Bank 환율·경상수지로 대외 균형과 무역개방도를 확인합니다. | [Link](./chapter15.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voidmain443/economic_principle_book/blob/main/chapter15.ipynb) | - |

:::{note}
전 15개 챕터의 강의 노트가 모두 준비되어 있습니다. 각 챕터는 위 표의 **강의 노트** 링크로 열람하거나, **Colab** 배지를 눌러 별도 설치 없이 브라우저에서 직접 실행할 수 있습니다. 모든 코드는 무료 공개 데이터(Maddison, World Bank, OWID, Penn World Table 등)를 사용하므로 누구나 그대로 재현할 수 있습니다.
:::