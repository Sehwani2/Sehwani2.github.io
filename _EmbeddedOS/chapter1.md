---
layout: single  # 'single'은 Minimal Mistakes의 기본 레이아웃입니다.
title: "Chapter 1: 임베디드 운영체제"
date: 2024-11-16
categories:
  - EmbeddedOS
tags:
  - RTOS
  - Operating System
  - Embedded
author_profile: true
read_time: true
share: true
comments: true
related: true
toc: true

---



## 임베디드 OS 개발 프로젝트" 책 소개 [책 링크](https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=221593471)   

- 이 글은 **"임베디드 OS 개발 프로젝트"** 책을 공부하며 남기는 기록입니다.

## 1장 : 임베디드 운영체제 

- 임베디드 운영체제는 운영체제의 하위 범주로, 운영체제의 모든 기능을 구현하지는 않습니다.
- 필요한 기능만 구현해 **임베디드 시스템에 최적화**된 효율적인 운영체제를 만드는 것이 목표입니다. 

## 운영체제의 주요 기능

***프로세스 관리***

- 태스크, 프로세스, 스레드 관리
- 스케쥴링
- 동기화
- IPC (Inter Process Communication)

***저장장치 관리***

- 메모리
- 가상 메모리 관리
- 파일 시스템 관리

***네트워킹 관리***

- TCP/IP 프로토콜 지원
- 기타 다른 네트워크 프로토콜 지원

***사용자 관리***

- 일반 사용자 또는 root 사용자 등 계정 관리
- 접근 권한 관리

***디바이스 드라이버***

- 순차 접근 장치 
- 임의 접근 장치
- 네트워크 장치

## RTOS(RealTime Operating System)

- 실시간으로 즉각적인 응답과 동작이 필요한 시스템을 위해 설계된 운영체제입니다.
- 책에서 구현하는 "나빌로스(NabilOS)"는 **RTOS**에 속합니다.



## 에뮬레이터 개발 환경

- 책에서는 **QEMU**라는 에뮬레이터를 활용하여 "나빌로스"라는 RTOS를 개발합니다.
