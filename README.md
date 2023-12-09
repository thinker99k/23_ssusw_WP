# 23_ssusw_wp_kiosk

23학년도 숭실대 소프트웨어학부 윈도우프로그래밍 (재수강/공통 반)

3조 : 키오스크 (MFC + MySQL 8.0)

**kitsune03k : 백엔드 담당**

##
ODBC가 MFC에서 데이터베이스를 연결하는데 가장 간단하다.

MySQL ODBC Connector(https://dev.mysql.com/downloads/connector/odbc/) 로 DSN kiosk_db에 연결되어야 한다.

시작 -> ODBC 데이터원본(64비트) -> 시스템 DSN 추가

##
랩탑에서 작업한다면 MySQL Service가 시스템의 리소스를 상당히 많이 잡아먹기에, 필요할때만 켤 필요가 있다.

https://github.com/kitsune03k/Passive_MySQL80

상기 링크의 batch로 파일들을 생성하면, 매번 귀찮게 services.msc를 들어갈 필요가 없이 바탕화면에서 바로가기 실행 한번으로 켜고 끌 수 있다.

##
**MFC에서 데이터베이스를 다루는데 CDatabase, CRecordset Class 이해 필수**

플랫폼 종속적인것을 싫어하지만, 애초에 MFC부터가 MS 종속적인데 알아두는것이 신상에 좋다.

https://learn.microsoft.com/ko-kr/cpp/mfc/reference/cdatabase-class?view=msvc-170

https://learn.microsoft.com/ko-kr/cpp/mfc/reference/crecordset-class?view=msvc-170

##
Contact : kitsune03@outlook.com
