# oss_02_report2

# 과제2

## 1. top
### 설명
`top`은 CPU 사용률, 메모리 사용률, 실행 중인 프로세스를 실시간으로 보여주는 명령어이다.

### 사용 예시

### 주요 출력 항목
| 항목 | 설명 |
|------|------|
| PID | 프로세스 ID |
| %CPU | CPU 사용률 |
| %MEM | 메모리 사용률 |
| TIME+ | 누적 CPU 사용시간 |
| COMMAND | 실행된 프로세스 이름 |

### 옵션 설명
| 옵션 | 설명 |
|------|------|
| -d | 화면 갱신 시간 간격 조정 |
| -u | 특정 사용자 프로세스만 표시 |
| -p | 특정 PID만 표시 |

### 실행 화면 예시
top 실행 화면

<img width="733" height="227" alt="top" src="https://github.com/user-attachments/assets/5ddcf793-c7fd-4418-bbbb-3adc363ae7be" />


---

## 2. ps
### 설명
`ps`는 현재 실행 중인 프로세스를 스냅샷 형태로 출력하는 명령어이다.

### 사용 예시

### 주요 옵션
| 옵션 | 설명 |
|------|------|
| -e | 모든 프로세스 출력 |
| -f | 상세 출력(full format) |
| -u 사용자 | 특정 사용자 프로세스 출력 |

### 프로세스 상태 코드
| 상태 | 의미 |
|------|------|
| R | 실행 중 |
| S | 대기 상태 |
| Z | 좀비 프로세스 |
| T | 일시정지 |

### 실행 화면 예시
ps 실행 화면

<img width="588" height="164" alt="ps" src="https://github.com/user-attachments/assets/2b067642-3b02-40ab-ad27-7057d82b31ed" />


---

## 3. jobs
### 설명
`jobs`는 현재 쉘에서 실행한 백그라운드 작업 목록을 출력하는 명령어이다.

### 사용 예시

### 상태 종류
| 상태 | 설명 |
|------|------|
| Running | 실행 중 |
| Stopped | 일시정지 |
| Done | 작업 완료 |

### 실행 화면 예시
jobs 실행 화면

<img width="473" height="79" alt="jobs" src="https://github.com/user-attachments/assets/66dc51b9-92d9-48b5-9aea-80e200dd673f" />


---

## 4. kill
### 설명
`kill`은 프로세스에 특정 시그널을 보내 종료시키는 명령어이다.

### 사용 예시

### 주요 시그널
| 시그널 | 설명 |
|--------|------|
| 15 (SIGTERM) | 정상 종료 요청 |
| 9 (SIGKILL) | 강제 종료 |
| 1 (SIGHUP) | 재시작 요청 |

### 실행 화면 예시
kill 실행 화면

<img width="539" height="140" alt="kill" src="https://github.com/user-attachments/assets/67480804-f2d5-43dc-8859-14b5a910d3bf" />


---
