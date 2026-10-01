# DDM501 Individual Assignment 1 - ML System Design

Tài liệu thiết kế hệ thống Machine Learning cho bài toán hỗ trợ ưu tiên xét duyệt ca ung thư vú dựa trên bộ đặc trưng WDBC.

Hệ thống được thiết kế theo hướng **human-in-the-loop**: mô hình chỉ tạo điểm rủi ro và mức ưu tiên; bác sĩ vẫn là người đưa ra quyết định cuối cùng.

## Nội dung bài làm

- Problem definition và phân tích stakeholder
- Functional, non-functional và data requirements
- Hệ thống mục tiêu và bộ business/system/model metrics
- Kiến trúc online inference và offline training
- Data flow, monitoring, fallback và model governance
- Phân tích các trade-off quan trọng
- Kế hoạch triển khai theo shadow, pilot và canary

## Cấu trúc repository

```text
.
|-- README.md
|-- docs/
|   `-- system-design.md
`-- report/
    `-- DDM501_Assignment1_STUDENTID_NAME.pdf
```

## Tài liệu nộp bài

PDF hoàn chỉnh nằm tại [`report/DDM501_Assignment1_STUDENTID_NAME.pdf`](report/DDM501_Assignment1_STUDENTID_NAME.pdf).

Trước khi nộp, thay `[ENTER NAME]` và `[ENTER STUDENT ID]` trong PDF, sau đó đổi tên file theo định dạng:

```text
DDM501_Assignment1_[StudentID]_[Name].pdf
```

## Lưu ý phạm vi

Các chỉ tiêu trong báo cáo là mục tiêu thiết kế cho một pilot giả định. Kết quả WDBC không phải bằng chứng đủ để sử dụng trong chẩn đoán lâm sàng hoặc thay thế chuyên gia y tế.

