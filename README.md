# Java_taxiClass
프로그래밍 기초 주차-Taxi 클래스 모델링

1. **아래의 정보를 가지는 ‘Taxi’ 클래스 모델링**
    - 포함해야 할 정보
        1. 택시 번호 
        2. 주유량
        3. 현재속도
        4. 목적지 
        5. 기본거리
        6. 목적지까지 거리
        7. 기본 요금
        8. 거리당 요금
        9. 상태 (운행 중, 일반)
    - **기능**
        1. 운행시작
        2. 승객 탑승
        3. 속도 변경
        4. 거리당 요금 추가
        5. 요금 결제
    - **요구 사항**
        - 운행 시작
            - 운행 시작전 주유상태를 체크 하고 주유량이 10 이상이어야 운행 가능
        - 승객탑승
            - 승객 탑승은 택시 상태가 ‘일반'일 때만 가능합니다.
            - 그 외 택시는 ‘탑승 불가’ 처리를 해주세요.
            - ‘일반’ 상태의 택시가 승객을 태우면 ‘운행 중’ 상태로 변경해 주세요
        - 속도 변경
            - 변경할 속도를 입력 받아 현재 속도에 추가 하거나 뺄 수 있어야 합니다.
        - 거리당 요금 추가
            - 기본 거리보다 먼 곳은 추가 요금이 붙습니다.
            - 기본 거리와 추가 요금은 자유롭게 산정해 주세요
        - 요금 결제
            - 최종 요금을 출력하는 것으로 합니다.
