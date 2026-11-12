---
name: weekly-marketing-report
description: Quy trình bắt buộc khi tạo báo cáo marketing tuần — kiểm tra dữ liệu theo thứ tự cứng, dùng định nghĩa metric trong metrics.md, áp ngoại lệ trong data-quirks.md, và luôn đính kèm Query Provenance Trace. Thiếu bảng truy vết thì dừng xuất báo cáo.
---

# Weekly Marketing Report

## Quy trình (theo khung bài chia sẻ gốc)
1. Xác định khoảng ngày + múi giờ của kỳ báo cáo. [ĐIỀN: múi giờ chuẩn của team, ví dụ Asia/Ho_Chi_Minh]
2. Lấy dữ liệu từ từng nguồn (GA4 / Meta Ads / TikTok Shop / Shopee / CRM). [ĐIỀN: nguồn team thực dùng]
3. Áp định nghĩa metric trong `metrics.md` — không tự suy diễn công thức.
4. Áp các ngoại lệ trong `data-quirks.md` (đơn COD hoàn hủy, lệch attribution window, độ trễ dữ liệu).
5. Trình bày báo cáo và đính kèm bảng **Query Provenance Trace** theo mẫu trong `templates/query-provenance-trace.md` ngay dưới mỗi bảng số liệu.
6. CHỐT CHẶN: nếu thiếu Query Provenance Trace thì DỪNG, không xuất báo cáo.
