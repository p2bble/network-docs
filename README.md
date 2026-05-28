# CLOBOT 마커스빌딩 네트워크 토폴로지

마커스빌딩 사옥 이전(2025.12~2026.03) 후 전수 조사한 네트워크 인프라를 인터랙티브 HTML 다이어그램으로 문서화.

## 🔗 바로 보기

**[→ 네트워크 토폴로지 다이어그램 열기](https://p2bble.github.io/network-docs/)**

## 구성

| 항목 | 내용 |
|---|---|
| 층 구성 | 1F~7F (7개 층) |
| UTM | FortiGate FG-120G ×2 (Active/Standby HA) |
| 코어 스위치 | FS-424E FIBER (7F MDF) |
| 엑세스 스위치 | Fortinet ×15대 (FS-148F·FS-108F-PoE·FS-124F) |
| L3 스위치 | Cisco Catalyst 9200L ×4 (INT·DMZ) |
| AP | FAP231K ×16대 (1F~7F) |
| 서버 | 5F 서버실 3구역 (메인 Rack·하프 Rack·우측 선반) 14+대 |

## 특징

- 층별 사이드바 네비게이션 (7F → 1F → SVG 토폴로지)
- 5F 서버실 접기/펼치기 (collapsible)
- 상단 장비 수량 요약 바
- 1F TPS 단일 통합 관리 구조 (2F 케이블 포설 포함)
