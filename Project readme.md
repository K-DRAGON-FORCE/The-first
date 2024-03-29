# The first 

# Project 

모션인식을 통해 사람의 현재자세를 확인하고 정해진 모션과 일치하지않으면 경고메세지 출력

## High Level Design

```mermaid
flowchart TD
  A[객체 탐지] --> B[탐지된 객체의 행동 추정]
  B[탐지된 객체의 행동 추정] --> C[조건에 따른 액션]
  C[조건에 따른 액션]
```
1.객체탐지
- 웹캠을 사용한 객체 탐지

2.탐지된 객체의 행동 추정
- 객체를 탐지하고 그 객체의 행동을 추적

3.조건에 따른 액션
- 객체가 취한 행동이 정해진 행동과 다르면 경고문구 표시


## Clone code

* (각 팀에서 프로젝트를 위해 생성한 repository에 대한 code clone 방법에 대해서 기술)

```shell
https://github.com/K-DRAGON-FORCE/The-first.git
```

## Prerequite

* (프로잭트를 실행하기 위해 필요한 dependencies 및 configuration들이 있다면, 설치 및 설정 방법에 대해 기술)

```shell
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Steps to build

* (프로젝트를 실행을 위해 빌드 절차 기술)

```shell
cd ~/xxxx
source .venv/bin/activate

make
make install
```

## Steps to run

* (프로젝트 실행방법에 대해서 기술, 특별한 사용방법이 있다면 같이 기술)

```shell
cd ~/xxxx
source .venv/bin/activate

cd /path/to/repo/xxx/
python demo.py -i xxx -m yyy -d zzz
```

## Output

* (프로젝트 실행 화면 캡쳐)



## Appendix

* (참고 자료 및 알아두어야할 사항들 기술)



| 영문이름 (GitHub id)           | Team No | HW#1 | HW#2 | HW#3 | Reviwer | 
|-------------------------------|---------|------|------|------|---------|
| 01 HongGilDong(HongID) | n/a | - | - | - | king_wss |
| 02 YooJaeWook(jwbastion) | n/a | - | - | - | king_wss |
| 03 HongGilDong(HongID) | n/a | - | - | - | king_wss |
| 01 KimMinHwan(nm981212) | n/a | - | - | - | king_wss |
| 02 YooJaeWook(jwbastion) | n/a | - | - | - | king_wss |
| 03 HyunChangOh(OHC-SOMA) | n/a | - | - | - | king_wss |
| 04 Kwonyujin(tina908) | n/a | - | - | - | king_wss |
| 05 shinnahyewon(shinho804@naver.com) | n/a | - | - | - | king_wss |
| 06 HongGilDong(HongID) | n/a | - | - | - | king_wss |
| 07 LeeYuJin(Eugene821) | n/a | - | - | - | king_wss |
| 08 subinlee(subin111)  | n/a | - | - | - | king_wss |
| 09 HongGilDong(HongID) | n/a | - | - | - | king_wss |
| 10 HongGilDong(HongID) | n/a | - | - | - | king_wss |
| 11 YGK        (HongID) | n/a | - | - | - | king_wss |
| 12 Wonbin-Choi(HongID) | n/a | - | - | - | Wonbin-Choi|
| 13 LeeMinGyu(min9710) | n/a | - | - | - | king_wss |
| 14 mingyu1123(HongID) | n/a | - | - | - | king_wss |
| 15      zkf624(zkf624) | n/a | - | - | - | king_wss |
| 16 YuKWangJae(AiGom1) | n/a | - | - | - | king_wss |
| 17 JeongWooTaek(almondgood) | n/a | - | - | - | king_wss |
| 18 ByungChan Lee(BChanGod) | n/a | - | - | - | king_wss |
| 19 KuJuHeon(KuJuHeon) | n/a | - | - | - | king_wss |
| 20 LeeInHyeok(LIH00) | n/a | - | - | - | king_wss |

### Projects

* Team x:
* Team y:
* Team z:
* Team w:
* Team v:
* Team a:
* Team b:

