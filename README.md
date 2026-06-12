# 🌸 Scenetype: 나를 표현하는 향을 찾아보세요

중앙대학교 [2026/1] 프로그래밍 언어의 이해 2조 프로젝트

<br>

<div align="center">
  <img src="https://github.com/user-attachments/assets/9d361845-7d33-4c95-8bf4-de4a8eba9631" width="300px">
<br>
  <i>"나를 표현하는 향을 찾아보세요. 🌸"</i>
</div>

## 📌 프로젝트 소개
Scenetype(씬타입)은 복잡한 향수 선택을 성격 유형(MBTI) 기반으로 쉽고 재미있게 풀어낸 웹 서비스입니다. 
딱딱한 심리 검사가 아닌 일상적인 12가지 감성 질문을 통해 사용자의 향 계열(플로럴, 우디, 시트러스, 오리엔탈, 머스크)을 분석하고, 그에 완벽하게 어울리는 퍼스널 향수를 추천해 드립니다.

* **배포 링크:** [[https://id.github.io/scenetype](https://codusnee.github.io/scenetype/)]

<br>

## ✨ 주요 기능
1. MBTI 기반 맞춤 향수 테스트 (`quiz.html`)
   * 12가지 시나리오 질문을 통해 사용자의 향 유형 도출.
   * 로딩 애니메이션 및 4가지 축(E/I, N/S, T/F, J/P) 기반의 직관적인 결과 제공.
2. 향 계열 및 추천 향수 결과 (`recommend.html`)
   * 분석된 향 계열(플로럴, 우디 등)에 따른 대표 향수 10종 추천.
   * MBTI 성격 특성과 어울리는 계절/상황 정보 제공.
3. 나의 향수 보관함 (`collection.html`)
   * LocalStorage를 활용하여 로그인 없이도 기기 내에 데이터 유지.
   * 보유 중인 향수 추가, 수정, 삭제 및 별점/메모 기능 지원.
4. 향수 백과사전 & 시뮬레이터 (`info.html`)
   * 노트 구조, 농도, 향 계열에 대한 상세 가이드 제공.
   * 인체 실루엣을 활용한 맥박 포인트 발향 시뮬레이터.

<br>

## 🛠 기술 스택
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
** Frontend: HTML5, CSS3, JavaScript (Vanilla JS)
** Storage: 브라우저 LocalStorage API
** Deployment: GitHub Pages

<br>

## 👥 Team (2조)
* 20224106 예술공학부 김채연 : [프로젝트 기획, MBTI 추천 로직 및 UI/UX 디자인 구현]
<br>
* 20246060 공공인재학부 노유빈 : [MBTI 16가지 유형별 향수 매칭 시나리오 기획 및 향수 매핑 recommend.html 제작, AI 향수 에셋(이미지) 제작, 향수 DB 수집]
