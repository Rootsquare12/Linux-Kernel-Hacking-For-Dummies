# Chapter 3. 커널 보호 기법 1 - SMEP과 그 우회

현대 리눅스 커널은 해커가 쉽게 공격을 하지 못하도록 여러 종류의 보호 기법을 적용합니다. 이번 장에서는 그 중 첫 번째 보호 기법인, SMEP(Supervisor Mode Execution Prevention)을 설명합니다. 이 방패를 우회하기 위한 기법인 KROP(Kernel-ROP)을 배웁니다.

- 3-1. 커널의 무한한 권한이 낳은 재앙: 커널 셸코드와 ret2usr
- 3-2. 보호 기법 : SMEP 란 무엇인가요?
- 3-3. SMEP 우회하기 : KROP(Kernel-ROP)