# Coupang narx kalkulyatori (FORETIMBER)

매입가 (부가세 별도) va istalgan sof foydadan Coupang **판매가**, **정상가**, **쿠팡 수수료** va **부가세**ni bir zumda hisoblaydigan sahifa.

## Imkoniyatlar
- Sof foyda: 판매가 대비 %, 매입가 대비 % yoki aniq summa (₩)
- Set: 1 set = N dona, 매입가 avtomatik N barobar
- Chegirma: 할인율 % yoki 할인 금액 → 정상가
- 수수료율, 판매가 yaxlitlash (10 / 100 / 1,000 / …900원)
- Set bo'yicha va foiz bo'yicha narx jadvallari
- O'zbek / 한국어

## Formula
```
순이익 = 판매가 ÷ 1.1 − 판매가 × 수수료율 − 매입가 − 택배비 ÷ 1.1
```
(FORETIMBER Coupang ERP hisobi bilan bir xil.)

## Ishlatish
`index.html` faylini brauzerda oching. Server kerak emas, hammasi bitta faylda.
