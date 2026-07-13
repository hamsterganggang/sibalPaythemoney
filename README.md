# DEU 카르텔 자금 현황

납부/미납 현황을 보여주는 GitHub Pages(Jekyll) 사이트.

## 현황 업데이트 방법

`_data/payments.yml` 파일만 수정하면 됩니다.

- `"O"` → 납부 완료 (초록 ✓)
- `""` (빈칸) → 미납 (빨강)
- 그 외 텍스트 (예: `"5만원"`) → 빨간 칸에 해당 텍스트 표시

새 달을 추가하려면 `months` 목록에 달을 추가하고, 각 사람의 `status`에도 값을 하나씩 추가하세요.

수정 후 커밋/푸시하면 GitHub Pages가 자동으로 사이트를 다시 빌드합니다. (반영까지 1~2분)

```
git add _data/payments.yml
git commit -m "7월 납부 현황 업데이트"
git push
```
