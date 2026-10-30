# text-mining

텍스트마이닝 수업용 데이터

```python
import pandas as pd

df = pd.read_csv(
    "https://raw.githubusercontent.com/MiYoungJang/text-mining/main/data/dart_business.csv",
    dtype={"corp_code": str, "stock_code": str, "induty_code": str},
)
```

## 출처

금융감독원 전자공시시스템 DART (https://dart.fss.or.kr), OpenDART API (https://opendart.fss.or.kr).