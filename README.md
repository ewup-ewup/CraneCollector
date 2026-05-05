# Crane Collector 🎮

3D 웹 기반 인형뽑기 시뮬레이터. 橋渡し(다리걸기) 메커니즘으로 도파민 극대화!

## 🎯 게임 플레이

- **목표**: 30초 동안 최대한 많은 박스 획득
- **조작**:
  - **드래그**: 크레인 좌우/전후 이동
  - **Lower Claw**: 집게 내리기
  - **Rotate**: 집게 회전

### 메커니즘

1. **약한 그립**: 집게는 직접 들어올리기 거의 불가능
2. **봉 사이 낙하**: 회전/이동으로 박스를 봉 사이로 떨어뜨림
3. **획득 판정**: 봉 사이를 통과 후 바닥에 도달하면 획득!

## 🚀 배포

- **URL**: https://ewup-ewup.github.io/CraneCollector/
- **기술**: Three.js + Cannon-es (CDN)

## 📋 개발 로드맵

### Phase 1 (완료) ✅
- 기본 3D 씬 + 물리
- 크레인 메커니즘 (약한 그립)
- 박스 획득 + 점수
- 파티클 이펙트

### Phase 2 (완료) ✅
- 등급 시스템 (F~A)
- 등급 공개 연출 (애니메이션)
- Last One 메커니즘 (보너스 2배)
- Pity 시스템 (실패 누적 시 확률↑)

### Phase 3 (완료) ✅
- 메인 메뉴
- 게임 상태 관리
- Best Score 추적 (localStorage)
- 게임 통계

### Phase 4 (완료) ✅
- 무료 뽑기 (일일 1회)
- 광고 시청 보상 (+1 게임)
- 일일 리셋 시스템
- AD_SLOT 마커 (AdMob/AppLovin 통합 준비)

### Phase 5 (계획)
- 광물/결정 도감
- 트로피/칭호 시스템
- 인앱 코인 구매 (IAP_SLOT)
- 프로필 진열

## 🔧 로컬 개발

```bash
# 저장소 클론
git clone https://github.com/ewup-ewup/CraneCollector.git
cd CraneCollector

# 로컬 서버 실행
python3 -m http.server 8000

# 브라우저에서 접속
# http://localhost:8000
```

## 📱 모바일 테스트

1. PC에서 서버 실행: `python3 -m http.server 8000`
2. PC IP 확인: `ipconfig getifaddr en0` (Mac)
3. 모바일에서 접속: `http://PC_IP:8000`

## 📄 라이선스

MIT License

---

**마지막 업데이트**: 2026-05-06  
**개발자**: Game Developer (Claude)
