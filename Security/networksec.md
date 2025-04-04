 # 🌐 네트워크 보안

네트워크 보안에 대한 키워드, 요약 답안, 복습 포인트 위주로 구성되어 있습니다.

---

## 📚 구성 목차

| 구분 | 설명 | 
|------|------|
| 1️⃣ 네트워크 개요 | N/A |
| 2️⃣ TCP/IP | N/A |
| 3️⃣ 라우팅 | N/A |
| 4️⃣ 네트워크 장비의 이해 | N/A |
| 5️⃣ 무선통신 보안 | N/A |
| 6️⃣ 네트워크 관리 | N/A |
| 7️⃣ 네트워크 기반 프로그램 활용 | N/A |
| 8️⃣ 네트워크 기반 공격의 이해 | N/A |
| 9️⃣ IDS/IPS | N/A |
| 🔟 방화벽 | N/A |  
| 1️⃣1️⃣ VPN | N/A |
| 1️⃣2️⃣ 최신 네트워크 보안 기술 | N/A |
---

## 1️⃣ 네트워크 개요
### 프로토콜의 정의, 주요 요소
- **키워드**: 구문(Syntax), 의미(Semantics), 타이밍(Timing)
- **설명**:
  1. **프로토콜**: 데이터 통신에서 송/수신자 측 혹은 네트워크에서 사전에 약속된 규약
  2. **구문**: 데이터가 어떠한 구조와 순서로 표현되는지를 나타냄 (데이터 형식, 부호화, 신호 레벨 등)
  3. **의미**: 각 비트가 갖는 의미를 나타내는 것 (전송제어, 오류수정 등 제어정보 규정)
  4. **타이밍**: 두 개체 간의 통신 속도를 조정 / 메시지 전송시간 및 순서 등의 특성

### OSI 7계층에 대한 설명 (데이터 종류, 프로토콜, 보안 프로토콜) ⭐
- **키워드**: Physical, Datalink, Network, Transport, Session, Presentation, Application
- **설명**:  
  1. **Physical (L1)**: 물리적 연결을 설정 및 해제, 전송방식 및 전송 매체 (Bitstream | -)
  2. **Datalink (L2)**: 오류 제어, 매체 제어 (MAC), 흐름 제어 (Frame | 이더넷 | PPTP, L2F, L2TP)
  3. **Network (L3)**: 통신 경로를 설정하고 중계함, 라우팅 (Packet | IP, ICMP, IGMP, ARP, RIP, OSRF | IPSec)
  4. **Transport (L4)**: 데이터 전송을 보장, 흐름 제어, Quality Of Service (QOS) (Segment | TCP, UDP, SCTP | SSL/TLS)
  5. **Session (L5)**: 소켓 프로그래밍, 동기화, 세션 연결/관리/ 종료 (Message | FTP, TFTP, SNMP, SMTP, HTTP, DNS | Kerberos, PGP, S/MIME, SSH, SET)
  6. **Presentation (L6)**: 네트워크 보안(암/복호화), 압축/압축해, 포맷 변환 수행 (L5와 동일)
  7. **Application (L7)**: 각종 응용 서비스 제공, 네트워크 관리 (L5와 동일)

