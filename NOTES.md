# NOTES: 學習者偏好與工作筆記 (GCP 遷移版)

## 學習者偏好

- **語言**: 繁體中文(避免未提供中文對照的英文術語)。
- **學習動機**: 個人興趣與自我提升，非職涯轉換。
- **既有基礎**: AWS Certified Cloud Practitioner (CLF-C02) 繁體中文版。
- **輔助工具**: Google NotebookLM(用於影片摘要、問答、複習)。
- **教學風格**: 類比先行 $\rightarrow$ 結構化列表/對比表格 $\rightarrow$ 反向驗證。
- **實作環境**: 使用 Google Cloud Platform (GCP) 替代 AWS，以利用 \$300 抵用金降低成本風險。

## 教學策略筆記

- 學習者已完成 CLF-C02，對雲端模型有基礎，但在實作上改用 GCP。
- **術語對應表 (AWS $\rightarrow$ GCP)**:
    - EC2 $\rightarrow$ Compute Engine
    - VPC $\rightarrow$ VPC (名稱相同)
    - S3 $\rightarrow$ Cloud Storage
    - IAM $\rightarrow$ IAM (名稱相同)
- Module 5(子網路劃分) 是公認難點，需特別著重。
- Module 7(OSI 模型) 抽象度高，需用生活化類比(如:寄信過程)輔助。
- 每個 Module 結束前，必須執行反向驗證(用自己的話解釋)。

## 進度追蹤

- [x] Module 1: IT 基礎概念與硬體組件
- [x] Module 2: 伺服器、虛擬化與雲端實作準備 (理論部分)
- [ ] Module 3: 資料中心與雲端運算 (實作準備中)
- [ ] Module 4: 網路基礎知識
- [ ] Module 5: IP 位址與子網路劃分
- [ ] Module 6: IP 路由與 GCP VPC
- [ ] Module 7: 網路參考模型與通訊協定
- [ ] Module 8: 網路安全與防火牆
- [ ] Module 9: 監控、DNS、資料庫與架構圖繪製
- [ ] Module 10: 現代 IT 工具、自動化與職涯發展
