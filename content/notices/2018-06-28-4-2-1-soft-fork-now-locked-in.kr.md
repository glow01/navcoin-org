---
layout: 공지
title: 4.2.1 이제 소프트 포크 락.
author: Craig MacGregor
date: '2018-06-28T22:10:52+12:00'
feature_image: /images/uploads/2018-06-28.jpg
notice_categories:
  -  필수 업데이트
---
버전 4.2.1의 소프트 포크는 이제 82%의 승인과 함께 잠금을 완료했으며, 곧 Nav코인의 컨센서스 메커니즘에 대한 두 가지 변경 사항이 적용됩니다. 모든 사용자는 네트워크에 연결된 상태를 유지하기 위해 블록 2237760으로 4.2.1로 업데이트해야 합니다.
<!--more-->

## 커뮤니티 펀드 적립

고정 보상은 연간 4%로 감소하고 0.25 NAV는 커뮤니티 기금에 모든 블록을 버닝 할 것입니다. 이 기금은 Nav코이 네트워크가 적절하다고 판단하여 매년 약 250,000 NAV가 소요됩니다. 이 누적은 블록 2237760에서 시작됩니다.

커뮤니티 기금은 일반 지갑 주소가 아니며, 개인 열쇠도 없으며, 아무도 직접 자금을 통제할 수 없습니다. 기금은 테스트가 완료된 후 후속 소프트 포크로 구현되는 2단계 네트워크 투표로만 액세스할 수 있습니다. Nav코인 커뮤니티 펀드에 대한 자세한 내용은 NavHub를 참조합니다.

<https://navhub.org/projects/community-fund>

## NTP 싱크

부정확한 시스템 클럭으로 인한 네트워크 불안정성을 방지하기 위해 각 네트워크 노드는 글로벌 NTP 서버를 사용하여 클럭을 동기화해야 합니다. 시스템 시계가 NTP 서버와 동기화할 수 없는 경우 Nav코인 대몬이 네트워크에 연결되지 않습니다. 잘못된 타임스탬프가 있는 마이닝 블록의 임계값도 2분 창으로 축소되었습니다. 네트워크가 이 임계값보다 큰 분산을 가진 블록을 거부합니다.

### TL;DR 

이제 블록 2237760 이전에 4.2.1로 업데이트해야 합니다.
