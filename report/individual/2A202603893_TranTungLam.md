# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Trần Tùng Lâm
- MSSV: 2A202603893
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: LuckyTeam
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

- Không dùng AI ở bước này. Cả 8 problem đều lấy từ việc tôi hoặc người nhà gặp thật.

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
| Baseline ~75'/tuần là ước lượng, chưa đo | Đồng ý | Ghi rõ cách đo: ghi giờ ra trạm, giờ dự kiến, giờ lên xe trong 1 tuần |
| Nhảy ngay sang "dùng AI dự đoán giờ xe tới" | Không đồng ý | Giữ Rule (tô màu giao thông + công thức khoảng cách/tốc độ) làm phương án trước; AI chỉ khi sai số còn > 3' |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch 3 card: #4 Kết quả xét nghiệm MyVinmec, #5 Trạm sạc VinFast, #6 Chờ VinBus (card chính, ~75'/tuần đứng chờ) | #6 vào shortlist, xếp thứ 2 (25 điểm) |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: "45 phút là bấm giờ hay nhớ lại?" (#1); "Trùng pattern với #7, gộp được không?" (#12); hỏi thêm về #3 và #8 đã có phương án No AI chưa | Baseline 45' thành giả định #1, thêm poll ở lab sau; #7 và #12 được gộp |
| Nhận phản biện | Câu hỏi tôi nhận được: "Nhóm lấy được dữ liệu GPS và giao thông của tuyến không?" (Anh Quân, #6); "Ai kiểm được lời giải thích y tế?" (Đức Hải, #4) | Tôi đã sửa gì: bỏ #4 (y tế, không kiểm được); nhận #6 thiếu dữ liệu, sẽ ghi giờ chờ 1 tuần để có baseline thật |
| Gom cluster / cây OST | Xếp 3 card của tôi vào cluster C (thiếu thông tin đúng lúc để quyết định) | Cluster C nằm ngoài outcome, nhưng #6 vẫn vào shortlist để so sánh |
| Chọn candidate problem | Chấm điểm shortlist, chấp nhận #6 điểm thấp ở "Vừa sức lab" | Đồng ý chọn #1 vì kiểm chứng được ngay trong buổi |
| Kiểm chứng / research | Cùng nhóm đọc kết quả review đề, log sửa đề và 200 tên repo fork | Problem thu hẹp lại: gom điều kiện chấm + kiểm tên ngay sau khi làm |
| Quy trình nhóm | Cùng nhóm vẽ quy trình trước/sau | 45' → ~18' (ước tính), 6/6 → 4/6 bước thủ công |
| Problem Statement | Cùng nhóm viết v0, nhờ AI phản biện, sửa thành v1 | v1 thêm metric độ phủ 25/25 điều kiện và 0 lỗi tên |
| Mức can thiệp AI | So sánh 4 mức No AI / Rule / Workflow / Agent | Chọn Rule + đổi thứ tự đọc; Workflow để dự phòng |
| Quyết định | Cùng nhóm chấm 4 rủi ro | No-Go cho AI; thử quy trình mới ở Day 03 |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Không dùng. Problem lấy từ việc tôi gặp hằng ngày | — | — | — |
| CP2 Problem Card | Nhờ AI phản biện card #6 Chờ VinBus, chỉ chỉ ra chỗ yếu, không viết lại | Hỏi đúng chỗ khó: baseline 75'/tuần là đo hay ước, Job Story có lẫn giải pháp không | Nhảy ngay sang "dùng AI dự đoán giờ xe tới", chưa xét cách đơn giản hơn | Giữ Rule (tô màu giao thông + công thức khoảng cách/tốc độ) làm phương án trước, AI chỉ khi sai số còn > 3' |
| CP4 Research | Tìm công cụ đã có cho việc gom yêu cầu đề (NotebookLM, GitHub Classroom…) | Ra nhanh danh sách để kiểm | Một số thông tin cũ hoặc không có nguồn (GitHub Classroom đã ngừng từ 28/08/2026) | Mở trang gốc kiểm từng công cụ, chỉ giữ thông tin có link |
| CP5 Quy trình | Không dùng. Các bước và số phút lấy từ đề và log của nhóm | — | — | — |
| CP5–6 Problem Statement | Đưa v0 cho AI với prompt "chỉ ra lỗ hổng, không viết lại" | Chỉ ra metric chỉ đo thời gian, baseline 45' của 1 người, Impact và quy trình lệch nhau | Đề nghị thêm nhiều metric, có cái không đo được trong lab | Chỉ thêm 2 metric đo được: độ phủ 25/25 điều kiện và 0 lỗi tên |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Theo tôi thấy nhiều card ban đầu có giải pháp nằm sẵn trong Job Story, ví dụ "tự động gom nhóm" ở #7. Card #3 và #8 thì đã có cách không cần AI nên việc đầu tiên xác định dự án có cần dùng đến AI hay không khá là quan trọng.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Có. Nghe card đọc đề lab, ý đầu tiên của nhóm là làm chatbot hỏi đáp đề. Card VinBus của tôi cũng ghi "tô màu giao thông", vốn là cách giải chứ không phải vấn đề. Lúc vẽ cây OST nhóm mới thấy và gạch các ý này đi.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Có. Tôi muốn nhóm chọn card VinBus vì tôi gặp hằng tuần. Nhưng Anh Quân hỏi lấy đâu ra dữ liệu GPS và giao thông thì tôi không trả lời được, nên tôi đồng ý chọn card đọc đề lab vì kiểm chứng được ngay trong buổi.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Có. Đặt tên repo là việc dễ nhất mà 35/200 repo của lớp vẫn sai rõ, dù quy tắc nằm ngay bước 1 README và sai bị trừ 5 điểm. Tôi hiểu ra vấn đề không phải đề thiếu thông tin, mà là không có bước kiểm lại sau khi làm.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Khó nhất là metric. Con số 45 phút chỉ là một người tự ghi. Lúc đầu nhóm chỉ đo thời gian, sau mới thấy làm nhanh mà sót điều kiện thì vô ích, nên thêm độ phủ điều kiện và số lỗi tên.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Tôi sẽ ghi giờ chờ VinBus một tuần trước buổi lab để có số liệu thật. Tôi cũng sẽ đòi nhóm hỏi vài bạn nhóm khác mất bao lâu đọc đề, vì cả bài vẫn dựa trên con số 45 phút của một người.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.
Học viên K5 mất khoảng 45 phút đọc 6 file đề mới biết đủ điều kiện chấm, mà vẫn làm sai. Chỗ nghẽn là bước đối chiếu giữa các file, vì 25 điều kiện nằm rải ở 3 file. Metric là giảm từ 45 xuống dưới 20 phút, bắt đủ 25/25 điều kiện và không sai tên repo, tên file. Boundary là công cụ chỉ trích nguyên văn đề, không tóm tắt, không tự đổi tên. Nhóm chọn Rule (vài lệnh gom điều kiện và kiểm tên) vì đã đủ, nên quyết định No-Go cho AI.

---

## 7. Tài liệu tham khảo

- Báo cáo nhóm LuckyTeam: [report/team/group_report.md](../team/group_report.md)
- Đề Day 02: [CHECKPOINTS.md](../../CHECKPOINTS.md), [RUBRIC.md](../../RUBRIC.md), [docs/01-worksheet.md](../../docs/01-worksheet.md)
- Teresa Torres, Opportunity Solution Trees: https://www.producttalk.org/opportunity-solution-trees/
- Google, NotebookLM / Gemini Notebook: https://support.google.com/notebooklm/answer/16179559
- GitHub Docs, Use autograding: https://docs.github.com/en/education/manage-coursework-with-github-classroom/teach-with-github-classroom/use-autograding
- Anthropic, Building effective agents: https://www.anthropic.com/research/building-effective-agents
