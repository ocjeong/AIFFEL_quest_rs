# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 정우철
- 리뷰어 : 박세희

# PRT(Peer Review Template)
- [V]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - LMS Step 5까지 수행되었고, 그에 대한 Loss 및 accuracy의 결과값이 시각화 그래프로 출력되었습니다.
    - <img width="709" alt="image" src="https://github.com/user-attachments/assets/6a5ead2b-0b29-40cd-895f-1b1b4fc048ec" />

    
- [V]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
      - BERT 모델의 레이어와 각 Shape 이 출력되어 구동방식을 이해하기 좋은 것 같습니다.
       <img width="886" alt="image" src="https://github.com/user-attachments/assets/ea499f24-97c9-40cc-8c4a-2aa67e907297" />

        
- [V]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - Bucketing, Dynamic Padding 적용 모델에 Dropout을 추가하여 실험이 수행되었습니다.
    - <img width="819" alt="image" src="https://github.com/user-attachments/assets/f0fc81d9-7526-4b39-a497-17997dba0702" />

        
- [V]  **4. 회고를 잘 작성했나요?**
    - 실험한 내용 및 결과가 잘 정리된 것 같습니다.
    - <img width="654" alt="image" src="https://github.com/user-attachments/assets/a5d20640-256d-4753-bc8d-7cc068522104" />

        
- [V]  **5. 코드가 간결하고 효율적인가요?**
    - Shard 메서드를 활용해서 모델 테스트용 데이터셋이 별도로 구축되었습니다.
    - <img width="816" alt="image" src="https://github.com/user-attachments/assets/e4a7e54b-a0c4-4c7d-9c2f-91f5a88de500" />



# 회고(참고 링크 및 코드 개선)
모델의 각 레이어와 파라미터의 사이즈를 출력해서 확인하는 부분이 모델의 작동 방식을 쉽게 이해할 수 있어서 좋았던 것 같습니다!!   
특히, 모델의 훈련 결과를 500 steps 별로 시각화해서 확인하는 작업은 처음 알게 되었네요!!   
오늘도 많이 배워갑니다! 😄 이번 노드도 고생 많으셨습니다!
