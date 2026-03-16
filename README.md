# Immigration Finance Tracker

미국 이민 목표 금융자산 달성률 추적 페이지

## Setup

1. GitHub에서 새 레포 생성 (Public)
2. 이 프로젝트를 push:
   ```bash
   cd ~/immigration-finance-tracker
   git add -A
   git commit -m "Initial commit"
   git remote add origin https://github.com/YOUR_USERNAME/immigration-finance-tracker.git
   git push -u origin main
   ```
3. GitHub 레포 → Settings → Pages → Source를 **GitHub Actions**로 설정

## 자산 업데이트 방법

1. GitHub 레포 → Actions → **Update Assets**
2. **Run workflow** 클릭
3. 각 카테고리별 금액(USD) 입력 후 실행
4. 자동으로 data.json 업데이트 + 페이지 재배포

## 직접 수정

`data.json`의 각 자산 `amount`를 직접 수정하고 push해도 됩니다.
