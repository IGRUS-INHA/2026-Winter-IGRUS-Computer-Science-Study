# 운영체제 강의 자료

참고 교재: *Operating Systems: Three Easy Pieces* (Remzi H. Arpaci-Dusseau, Andrea C. Arpaci-Dusseau)

## 가상화 - CPU

| 챕터 | 주제 | 주요 내용 |
|------|------|-----------|
| [Ch.2](IGRUS-operating-system-ch02-v20260126.pdf) | OS 소개 | 프로그램 실행 과정, 시스템 콜, 가상화, 자원 관리 |
| [Ch.4](IGRUS-operating-system-ch04-v20260126.pdf) | 프로세스 | 프로세스 정의와 구조, 메모리 구성, 프로세스 API |
| [Ch.5](IGRUS-operating-system-ch05-v20260126.pdf) | 프로세스 API | fork(), exec(), wait(), 부모-자식 프로세스 |
| [Ch.6](IGRUS-operating-system-ch06-v20260126.pdf) | 제한적 직접 실행 | 유저 모드/커널 모드, 인터럽트, 성능과 제어의 트레이드오프 |
| [Ch.7](IGRUS-operating-system-ch07-v20260128.pdf) | 스케줄링 소개 | 스케줄링 메트릭, FIFO, 워크로드 가정 |
| [Ch.8](IGRUS-operating-system-ch08-v20260128.pdf) | MLFQ | 다단계 피드백 큐, 우선순위 기반 스케줄링, 동적 우선순위 조정 |
| [Ch.9](IGRUS-operating-system-ch09-v20260128.pdf) | 비례 배분 | 로터리 스케줄링, 스트라이드 스케줄링, Linux CFS |

## 가상화 - 메모리

| 챕터 | 주제 | 주요 내용 |
|------|------|-----------|
| [Ch.13](IGRUS-operating-system-ch13-v20260130.pdf) | 주소 공간 | 가상 주소 공간, 코드/데이터/힙/스택, 메모리 가상화 |
| [Ch.14](IGRUS-operating-system-ch14-v20260130.pdf) | 메모리 API | malloc/free, calloc/realloc, brk/sbrk, mmap |
| [Ch.15](IGRUS-operating-system-ch15-v20260130.pdf) | 주소 변환 | 하드웨어 기반 주소 변환, 가상-물리 매핑, TLB |
| [Ch.16](IGRUS-operating-system-ch16-v20260202.pdf) | 세그멘테이션 | 세그먼트 개념, Base and Bounds, 외부 단편화 |
| [Ch.17](IGRUS-operating-system-ch17-v20260203.pdf) | 여유 공간 관리 | 힙 관리, 분할과 병합, 할당 전략 (Best/Worst/First/Next Fit) |
| [Ch.18](IGRUS-operating-system-ch18-v20260202.pdf) | 페이징 소개 | 페이징 개념, 페이지 테이블, VPN/PFN |
| [Ch.19](IGRUS-operating-system-ch19-v20260204.pdf) | TLB | TLB 히트/미스, 시간적·공간적 지역성, TLB 교체 정책, ASID |
| [Ch.20](IGRUS-operating-system-ch20-v20260204.pdf) | 고급 페이지 테이블 | 선형 페이지 테이블, 다단계 페이지 테이블, 크기 최적화 |
| [Ch.21](IGRUS-operating-system-ch21-v20260207.pdf) | 스와핑 메커니즘 | 스왑 공간, 페이지 폴트, 메모리 계층 구조 |
| [Ch.22](IGRUS-operating-system-ch22-v20260207.pdf) | 스와핑 정책 | 최적 교체, FIFO, Belady's Anomaly, 페이지 교체 알고리즘 |

## 동시성

| 챕터 | 주제 | 주요 내용 |
|------|------|-----------|
| [Ch.26](IGRUS-operating-system-ch26-v20260211.pdf) | 동시성 소개 | 스레드, 멀티스레드 프로그래밍, 컨텍스트 스위칭, 공유 주소 공간 |
| [Ch.27](IGRUS-operating-system-ch27-v20260211.pdf) | 스레드 API | pthread_create, 스레드 속성, 스레드 실행 관리 |
| [Ch.28](IGRUS-operating-system-ch28-v20260211.pdf) | 락 | 임계 영역, 상호 배제, pthread mutex, 락 구현 (하드웨어/OS 지원) |
