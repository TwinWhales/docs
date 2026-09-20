양식
# Windows Prefetch Artifact Specification

## 1. Artifact Overview

| Item | Value |
|---|---|
| Artifact | Windows Prefetch |
| Path | C:\Windows\Prefetch |
| Extension | .pf |
| Primary Purpose | Application execution optimization |
| Forensic Value | Program execution evidence |

## 2. Tested Environments

| OS | Version | Build | Architecture |
|---|---|---|---|
| Windows 10 | 22H2 | 19045.x | x64 |
| Windows 11 | 23H2 | 22631.x | x64 |
| Windows 11 | 24H2 | 26100.x | x64 |

## 3. Test Methodology

1. VM Snapshot 복원
2. test.exe 최초 실행
3. Prefetch 생성 확인
4. 이미지 획득
5. 원본 해시 계산
6. PECmd 및 Hex 분석
7. 버전별 결과 비교

## 4. Artifact Location

...

## 5. File Structure

...

## 6. Timestamp Semantics

...

## 7. Experiment Results

...

## 8. Version Differences

...

## 9. Parser Validation

...

## 10. Forensic Interpretation

...

## 11. Limitations

...


반드시 포함되어야 하는 내용
OS Edition
OS Version
OS Build
Architecture
Filesystem
Timezone

VM Software
VM Snapshot State

Artifact Path
Artifact SHA256

Action Performed
Action Time
Collection Time

Acquisition Tool
Parsing Tool
Parsing Tool Version



추후 추가할 것들
SRUM
ShellBags
Recycle Bin
RecentDocs
RunMRU
TypedPaths
USB artifacts
Browser artifacts
Windows Search DB
ActivitiesCache