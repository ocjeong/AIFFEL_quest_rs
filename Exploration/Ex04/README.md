# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 정우철
- 리뷰어 : 성연우


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - 프로젝트 완성된 결과물까지 잘 적어주셨습니다
      
      ![완료](https://github.com/user-attachments/assets/40ccea08-c64b-41ad-af32-64e4444c2145)
    
    
- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 이미지를 불러오고 RGB를 BGR로 변환하는 부분, 배경과 인물을 분리해 배경만 블러처리 하는 과정을 하나의 함수로 만들어 여러장의 이미지를 하나씩 변환하지 않아도 되도록 코드를 작성해주신 부분이 가장 중요하다고 생각했습니다
        - 블러의 강도를 찾기 위해 여러 값들을 넣어보며 최적의 값을 찾은 코드도 이미지에 맞는 적절한 강도를 찾을 수 있었던 좋은 시도였던 것 같습니다
      
      ![핵심](https://github.com/user-attachments/assets/60c253a5-63de-4aa7-9d78-318d7a06571d)

        
- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 이미지에서 세종대왕 동상의 얼굴과 뒤에 경찰들도 모두 사람으로 인식하는 부분이 모델이 얼마나 민감하고 알 수 있는 부분이었습니다
        - 커널 사이즈를 조정해서 타켓을 좀 더 자세하게 잡은 부분 또한 효과적인 방법이었습니다
        - 타겟을 가리고 있을 때 과연 어디까지 블러처리를 할 것인가에 대한 궁금증으로 실습하신 말 사진도 새로운 시도였다고 생각합니다 
        ![새로운 시도](https://github.com/user-attachments/assets/81904110-6b54-4e51-9205-ff4491c172c5)
        ![새로운2](https://github.com/user-attachments/assets/25d3c898-a462-4bf1-9441-3598becfc569)


        
- [O]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 전체적으로 각각의 코드마다 주석을 달아 이해하기 쉬웠고 불필요한 코드를 없애 코드가 간결했습니다
      ![간결](https://github.com/user-attachments/assets/6f71c2d5-06b4-4e33-aac0-df0caa077758)

      


# 회고(참고 링크 및 코드 개선)
```
인식하는 객체가 가려졌을 때 모델은 어떻게 보여질까와 같이 제가 생각해보지 못한 방법 부분을 실습해 주셔서 좋았습니다
개선할 부분에 대해서도 저와 비슷한 생각을 한 부분이 많아서 해결방법에 대해 이야기할 수 있는 좋은 기회였습니다
추후에 회고 부분만 추가적으로 보충해 주시면 좋을 것 같아요. 오늘 고생하셨습니다!
```
