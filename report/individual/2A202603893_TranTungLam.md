# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Trần Tùng Lâm
- MSSV: 2A202603893
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: 
- Link repo nhóm: https://github.com/ndhai255/K5-L3B-DAY02-LuckyTeam-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi đặt Xanh SM lúc 7h sáng đi học, tôi muốn biết bao lâu có tài xế nhận, để kịp đổi sang xe buýt nếu chờ lâu | Sinh viên đi học sáng | ~4 lần/tuần, chờ 3–12 phút; tuần trước 1 lần phải hủy đặt lại (lịch sử chuyến trong app) |
| 2 | Lặp lại | Khi đi VinBus tới trường, tôi muốn biết mấy phút nữa xe tới trạm theo tình hình thực tế, để không đứng chờ lâu hoặc lỡ chuyến | Người đi VinBus | ~5 lượt/tuần, chờ 10–20 phút/lượt; xe hay trễ so với lịch khi tắc đường; từng lỡ chuyến, chờ thêm ~15 phút |
| 3 | Lặp lại | Khi báo sửa điện nước cho ban quản lý Vinhomes, cư dân muốn biết giờ kỹ thuật đến, để có người ở nhà đúng lúc | Cư dân Vinhomes | Lần gần nhất gọi 2 lần mới được hẹn, chờ ~2 ngày, 1 buổi chờ mà không ai đến |
| 4 | Tốn thời gian | Khi khám ngoại trú ở Vinmec, tôi muốn biết trước thời gian chờ từng bước, để không mất trắng cả buổi | Bệnh nhân ngoại trú | Lần gần nhất mất ~3 giờ, riêng chờ kết quả xét nghiệm ~60 phút (giờ trên phiếu khám) |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi nhận kết quả xét nghiệm trên app MyVinmec, tôi muốn biết chỉ số nào bất thường và có cần tái khám không, để khỏi lo khi chờ gặp bác sĩ | Bệnh nhân vừa xét nghiệm | ~20 chỉ số, chỉ hiểu ~5; ước ~30 phút tự tra (chưa đo, cần xác nhận); chờ 2 ngày mới gặp bác sĩ |
| 6 | Cần đọc, tổng hợp nhiều thông tin | Khi làm hồ sơ bảo hiểm sau khám Vinmec, tôi muốn biết đủ giấy tờ cần nộp, để không bị trả hồ sơ | Người có bảo hiểm sức khỏe | Bị trả hồ sơ 1 lần, chậm ~1 tuần; yêu cầu nằm rải rác ở email, web bảo hiểm và quầy thu ngân |
| 7 | Cần đọc, tổng hợp nhiều thông tin | Khi đi VinFast về quê ~150 km, người lái muốn biết nên sạc ở trạm nào, để không chờ trụ lâu hay lo hết pin | Chủ xe VinFast đi xa | Dịp lễ gần nhất chờ trụ sạc ~45 phút; phải tự đối chiếu bản đồ, % pin và app trạm sạc |
| 8 | Pain từ người khác | Khi bố mẹ ở quê lên Vinmec tái khám, gia đình muốn đặt đúng chuyên khoa và giờ, để bố mẹ không đi lại 2 lần | Bố mẹ tôi, tôi (đặt hộ) | Gọi tổng đài ~15 phút/lần; 1 lần đặt nhầm khoa, chờ chuyển thêm ~1 giờ |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Đọc kết quả xét nghiệm MyVinmec (#5) | Biết rõ ai gặp và các bước họ làm; chỉ ra được đúng bước tốn thời gian nhất (tự tra từng chỉ số, ~30 phút) | Người khác có tự tra như tôi không, hay chỉ chờ bác sĩ? App đã có mục "tra cứu thông tin thuốc và y tế" và đặt lịch tư vấn trực tuyến: cần kiểm ở CP4 xem mục tra cứu có áp vào kết quả của chính mình không |
| 2 | Chọn trạm sạc VinFast khi đi xa (#7) | Mỗi lần dừng sạc mất ~45 phút chờ trụ; dịp lễ nào về quê cũng gặp lại | App VinFast có thể đã hiện số trụ trống, cần kiểm ở CP4 |
| 3 | Chờ VinBus ở trạm (#2) | Gặp ~5 lần/tuần nên cộng lại mất ~75 phút/tuần đứng chờ; dễ lấy số liệu, chỉ cần ghi giờ ra trạm và giờ lên xe | App Xanh SM đã theo dõi được vị trí xe buýt, nhưng đường đi chỉ hiện một màu xanh, không có màu vàng/đỏ báo tắc như Google Maps. Giờ tới dự kiến trên app có tính tới tắc đường không? |

### Problem Card #1 — Đọc kết quả xét nghiệm MyVinmec

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận kết quả xét nghiệm trên app MyVinmec, tôi muốn biết chỉ số nào bất thường và có cần tái khám không, để khỏi lo khi chờ gặp bác sĩ |
| Actor | Người khám ngoại trú ở Vinmec có xét nghiệm máu, xem kết quả trên app trước khi gặp lại bác sĩ |
| Thời điểm / bối cảnh | Kết quả lên app trong ngày, nhưng lịch gặp bác sĩ đọc kết quả là 2 ngày sau |
| Quy trình hiện tại (3–7 bước) | 1. Mở app xem kết quả<br>2. Lọc các chỉ số bị đánh dấu cao/thấp<br>3. Tra từng chỉ số trên Google<br>4. Hỏi người nhà, tự đoán mức độ<br>5. Chờ gặp bác sĩ<br>6. Bác sĩ giải thích |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3, tra từng chỉ số: ước ~30 phút (chưa đo, cần xác nhận ở CP4). Các nguồn nói khác nhau, tra xong vẫn không biết có cần khám sớm không |
| Impact (nếu không giải thì sao) | Lo lắng 2 ngày; có thể bỏ qua chỉ số cần khám sớm, hoặc đi khám thừa vì hoảng |
| Success metric (baseline → target) | Thời gian từ lúc có kết quả tới lúc biết "chỉ số nào bất thường, có cần khám sớm không": ~30 phút (ước lượng) → dưới 5 phút. Baseline cần đo lại: bấm giờ lần đọc kết quả tiếp theo, hoặc hỏi 3–5 người từng xét nghiệm.  |
| Phương án không dùng AI | Bác sĩ ghi 1–2 dòng nhận xét kèm kết quả; mỗi chỉ số có giải thích ngắn soạn sẵn; chỉ số vượt ngưỡng nguy hiểm thì bệnh viện gọi báo; gợi ý ngay trên trang kết quả nút đặt lịch tư vấn trực tuyến (app đã có tính năng này) để gặp bác sĩ sớm hơn 2 ngày |
| Giả thuyết về AI (nếu có) | Tóm tắt các chỉ số ngoài ngưỡng bằng lời dễ hiểu. Không chẩn đoán, không khuyên dùng thuốc |
| Cảm nhận nhanh | Rule (cờ ngưỡng + giải thích soạn sẵn); có thể cần Workflow nếu phải diễn giải nhiều chỉ số cùng lúc |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ~47 phút tự xử lý + 2 ngày chờ (số phút là ước lượng, chưa đo)

[Mở app xem kết quả: 2'] → [Lọc chỉ số có cờ cao/thấp: 5']
→ [Tra từng chỉ số trên Google: 30'] ← BOTTLENECK
→ [Hỏi người nhà, tự đoán: 10'] → [Chờ gặp bác sĩ: 2 ngày] → [Bác sĩ giải thích: 10']
```

### Problem Card #2 — Chọn trạm sạc VinFast khi đi xa

| Trường | Nội dung |
|---|---|
| Job Story | Khi đi VinFast về quê xa, người lái muốn biết nên sạc ở trạm nào, để không chờ trụ lâu hay lo hết pin |
| Actor | Chủ ô tô điện VinFast đi đường dài dịp lễ |
| Thời điểm / bối cảnh | Tối hôm trước và trên đường về quê, dịp lễ khi trạm sạc đông |
| Quy trình hiện tại (3–7 bước) | 1. Xem quãng đường trên Google Maps<br>2. Xem % pin và số km còn đi được trên xe<br>3. Tìm trạm sạc dọc đường trên app, đối chiếu với quãng đường<br>4. Lái tới trạm<br>5. Chờ trụ trống<br>6. Sạc |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3, chọn trạm: ~20 phút đối chiếu, nhưng không biết trạm có đông không, dẫn tới chờ trụ ~45 phút ở bước 5 |
| Impact (nếu không giải thì sao) | Chuyến đi dài thêm ~45 phút mỗi lần dừng sạc; lo hết pin nên dừng sạc sớm hơn cần thiết |
| Success metric (baseline → target) | Thời gian chờ trụ mỗi lần dừng: 45 phút → dưới 15 phút. Đo bằng ghi giờ tới trạm và giờ cắm sạc ở chuyến sau |
| Phương án không dùng AI | Sạc đầy ở nhà trước khi đi; tránh giờ cao điểm; hỏi nhóm chủ xe VinFast trạm nào hay đông |
| Giả thuyết về AI (nếu có) | Dự đoán trạm nào sẽ đông vào giờ mình tới, dựa trên lịch sử dùng trụ (cần dữ liệu của VinFast) |
| Cảm nhận nhanh | Nếu app đã hiện trụ trống thời gian thực thì chỉ cần Rule |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ~27 phút lên kế hoạch + 45 phút chờ trụ

[Xem quãng đường: 5'] → [Xem % pin trên xe: 2']
→ [Tìm và chọn trạm trên app: 20'] ← BOTTLENECK (chọn sai trạm đông)
→ [Lái tới trạm] → [Chờ trụ trống: 45'] → [Sạc: ~40']
```

### Problem Card #3 — Chờ VinBus ở trạm

| Trường | Nội dung |
|---|---|
| Job Story | Khi đi VinBus tới trường, tôi muốn biết mấy phút nữa xe tới trạm theo tình hình thực tế (kể cả khi xe đang tắc đường hay gặp sự cố), để không đứng chờ lâu hoặc lỡ chuyến |
| Actor | Sinh viên đi VinBus một tuyến cố định từ nhà tới trường, ~5 lượt/tuần |
| Thời điểm / bối cảnh | Buổi sáng giờ cao điểm, trạm ngoài trời. Xe hay trễ so với lịch vì tắc đường hoặc sự cố trước khi tới trạm |
| Quy trình hiện tại (3–7 bước) | 1. Mở app Xanh SM xem vị trí xe buýt trên bản đồ<br>2. Ước giờ xe tới theo vị trí xe + kinh nghiệm (đường đi trên app chỉ một màu xanh, không thấy đoạn nào tắc)<br>3. Đi bộ ra trạm<br>4. Đứng chờ ở trạm, thấy xe ở đâu nhưng không biết đoạn đường tiếp theo có tắc không<br>5. Lên xe (lỡ chuyến thì chờ chuyến sau) |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4, đứng chờ ở trạm: 10–20 phút. App Xanh SM có vị trí xe nhưng đường đi chỉ tô một màu xanh, không hiện vàng/đỏ như Google Maps, nên không biết đoạn sắp tới có tắc không và ước giờ ở bước 2 hay sai |
| Impact (nếu không giải thì sao) | ~75 phút/tuần đứng chờ (5 lượt × ~15 phút); khi xe trễ lâu không biết để chuyển sang Xanh SM sớm, dễ trễ giờ học |
| Success metric (baseline → target) | Thời gian đứng chờ mỗi lượt: ~15 phút → dưới 5 phút; giờ xe tới dự kiến lệch giờ thực tế không quá 3 phút. Đo bằng ghi giờ ra trạm, giờ dự kiến và giờ lên xe trong 1 tuần |
| Phương án không dùng AI | Trên bản đồ theo dõi xe, tô màu đoạn đường theo tình trạng giao thông (xanh/vàng/đỏ như Google Maps); tính giờ tới từ khoảng cách + tốc độ hiện tại trên từng đoạn; tài xế/điều phối bấm báo "xe gặp sự cố" để hành khách biết sớm |
| Giả thuyết về AI (nếu có) | Chỉ cần khi muốn dự đoán giờ tới lúc tắc đường chính xác hơn công thức khoảng cách/tốc độ (học từ dữ liệu giờ tới các ngày trước) |
| Cảm nhận nhanh | Rule (GPS đã có sẵn, chỉ cần thêm lớp màu giao thông + công thức khoảng cách/tốc độ); chưa cần AI nếu sai số đã dưới 3 phút |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ~23 phút/lượt, ~5 lượt/tuần

[Mở app Xanh SM xem vị trí xe: 1'] → [Tự ước giờ tới (đường chỉ một màu xanh): 2']
→ [Đi bộ ra trạm: 5']
→ [Đứng chờ, không biết đoạn tiếp theo có tắc không: 10–20'] ← BOTTLENECK
→ [Lên xe] (lỡ chuyến: chờ thêm ~15')
```

### Card muốn pitch nhất

- Card số: 3 (Chờ VinBus ở trạm)
- Vì sao: Tôi gặp ~5 lần/tuần nên tự đo được (ghi giờ ra trạm, giờ dự kiến, giờ lên xe). Đã thấy rõ chỗ thiếu: app Xanh SM theo dõi được vị trí xe buýt, nhưng đường đi chỉ hiện một màu xanh, không có vàng/đỏ báo tắc như Google Maps, nên không biết đoạn tiếp theo có tắc không. Nhóm có thể so sánh rõ No AI / Rule / AI: thêm màu giao thông + công thức khoảng cách/tốc độ, hay cần dự đoán giờ tới bằng dữ liệu các ngày trước.
- Câu hỏi muốn nhóm phản biện: Chỉ cần tô màu giao thông xanh/vàng/đỏ trên tuyến xe (Rule) đã đủ để hành khách quyết định chờ tiếp hay chuyển sang Xanh SM chưa, hay họ cần app tự tính sẵn số phút xe tới (lúc đó mới cần AI dự đoán)?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| | | |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
