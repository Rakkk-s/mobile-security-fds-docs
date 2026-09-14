# 금융 데이터

네 시나리오의 룰에 **실제로 조건으로 들어가는** 금융사 데이터만 추린 최소 세트 21개다. 거래 1건이 한 줄이며, 단말에서 오는 [단말 데이터](detection-device.md)와 결합해 판정한다. 각 데이터를 룰에서 어떻게 쓰는지는 [룰 정의서](rule-catalog.md)에서 다룬다.

| 데이터 | 담고 있는 정보 |
| --- | --- |
| <a id="fin-txn-id"></a>거래 식별자 | 거래 한 건을 구분하는 식별자 |
| <a id="fin-cust-id"></a>고객 식별자 | 고객을 구분하는 식별자 |
| <a id="fin-device-id"></a>단말 식별자 | 거래를 발생시킨 단말의 식별자 |
| <a id="fin-txn-time"></a>거래 요청 시각 | 거래가 요청된 시각 |
| <a id="fin-recv-time"></a>서버 수신 시각 | 거래 요청이 서버에 도달한 시각 |
| <a id="fin-txn-type"></a>거래 유형 | 이체 · 카드 승인 · ATM 출금 |
| <a id="fin-amount"></a>거래 금액 | 이번 거래의 금액 |
| <a id="fin-req-ip"></a>거래 요청 IP | 거래를 요청한 접속 IP |
| <a id="fin-new-payee"></a>신규 수취인 여부 | 평소 수취인 목록에 없는 계좌인지 |
| <a id="fin-avg-amount"></a>최근 30일 평균 이체금액 | 최근 30일간의 평균 이체 금액 |
| <a id="fin-cp-cnp"></a>카드 제시 구분 | 카드 제시 결제인지, 비제시(온라인) 결제인지 |
| <a id="fin-cancel"></a>취소 요청 이력 존재 | 해당 카드에 취소 요청 이력이 있는지 |
| <a id="fin-origin-txn"></a>원 거래 실재 | 문자가 알린 결제 건이 승인 이력에 있는지 |
| <a id="fin-sms-time"></a>인증 문자 발송 시각 | 금융사가 인증 문자를 발송한 시각 |
| <a id="fin-limit-time"></a>이체한도 변경 시각 | 이체한도가 변경된 시각 |
| <a id="fin-limit-ratio"></a>이체한도 상향 배수 | 이체한도가 몇 배로 상향됐는지 |
| <a id="fin-input-source"></a>이체 입력 발생 방식 | 타이핑 · 붙여넣기 · 주입(물리 터치 없는 입력) |
| <a id="fin-card-region"></a>카드 발급지 | 카드가 발급된 지역 |
| <a id="fin-atm-loc"></a>ATM 위치 | 인출이 일어난 ATM의 위치 |
| <a id="fin-rf-txn"></a>NFC 거래 여부 | 비접촉(NFC) 거래인지 |
| <a id="fin-outbound-call"></a>확인 전화 결과 | 금융사가 건 확인 전화의 결과 — 응답 · 무응답 · 통화중 |
