# Báo cáo cá nhân — 2A202603950_NguyenAnhQuan

## 1. Thông tin học viên

- Họ tên: Nguyễn Anh Quân
- MSSV: 2A202603950
- Tên nhóm: LuckyTeam
- Link repo nhóm: [K5-L3B-DAY02-LuckyTeam-DiscoveryProblemFraming](https://github.com/ndhai255/K5-L3B-DAY02-LuckyTeam-DiscoveryProblemFraming)

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dữ liệu minh họa (thời gian, tần suất, số người) |
|---:|---|---|---|---|
| 1 | lặp lại | Khi ứng tuyển thực tập hoặc việc làm ở nhiều công ty, tôi muốn quản lý được các vị trí đã nộp, hạn tuyển và trạng thái phản hồi, để không bỏ lỡ lịch phỏng vấn hoặc nộp trùng | sinh viên đang tìm việc | ứng tuyển 8 vị trí trong 3 tuần, mất khoảng 15 phút/lần để kiểm tra email và cập nhật trạng thái ứng tuyển |
| 2 | tốn thời gian | Khi hoàn thiện báo cáo, tôi muốn trình bày tài liệu đúng quy định của khoa, để hạn chế phải sửa lại định dạng nhiều lần trước khi nộp. | sinh viên làm bài tập lớn, đồ án | mất khoảng 2 giờ chỉnh mục lục, tiêu đề và bảng biểu; phải chỉnh lại 3 lần |
| 3 | cần đọc, tổng hợp nhiều thông tin | Khi tìm tài liệu cho khóa luận hoặc làm nghiên cứu khoa học, tôi muốn xác định được kết quả chính, phương pháp và điểm khác nhau giữa các nghiên cứu, để chọn tài liệu phù hợp và xây dựng phần tổng quan. | sinh viên năm cuối, sinh viên làm nghiên cứu khoa học | đọc 4-5 bài nghiên cứu/tuần, trung bình 60 phút/bài để đọc và ghi chú phương pháp, kết quả chính |
| 4 | cần đọc, tổng hợp nhiều thông tin | Khi kiểm tra chi tiêu cuối tháng, tôi muốn tổng hợp được các khoản đã trả bằng tiền mặt, chuyển khoản để biết tiền đang dành cho những việc gì và điều chỉnh ngân sách tháng sau | người chi tiêu | mỗi tháng mất khoảng 45–60 phút để đối chiếu lịch sử chuyển khoản và ghi chép tiền mặt; có 3–5 khoản không nhớ rõ mục đích chi |
| 5 | lặp lại, pain từ người khác | Khi hướng dẫn thực tập sinh mới, tôi muốn các bạn hiểu đúng cách cài đặt và chạy dự án, để giảm thời gian giải thích lại những lỗi thiết lập giống nhau và dành thời gian hỗ trợ chuyên môn | mentor | Trong một đợt tiếp nhận 3 thực tập sinh, mentor phải giải thích lại cùng lỗi cài đặt 2–3 lần, mỗi lần khoảng 15–20 phút. |


---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Theo dõi quá trình ứng tuyển thực tập hoặc việc làm | Actor rõ; công việc lặp lại; có thể đo thời gian cập nhật và kiểm tra độ đầy đủ của thông tin. | Việc theo dõi thủ công có thực sự gây bỏ sót hay chỉ bất tiện? Một bảng tính có đủ giải quyết không? |
| 2 | Định dạng báo cáo theo quy định của khoa | Quy trình cụ thể; có thể đối chiếu với quy định và đo thời gian sửa; có phương án không dùng AI rõ ràng. | Bước nghẽn nằm ở sửa định dạng hay chưa hiểu quy định? Đã có template chính thức chưa? |
| 3 | Đọc và tổng hợp tài liệu nghiên cứu | Liên quan đến khóa luận/nghiên cứu khoa học; cần hiểu ngữ cảnh và đối chiếu nhiều nguồn. | Tốn thời gian nhất ở đọc hiểu hay so sánh? Ghi chú theo mẫu có đủ không? Đo độ chính xác thế nào? |

### Problem Card #1 — Theo dõi quá trình ứng tuyển

| Trường | Nội dung |
|---|---|
| Job Story | Khi ứng tuyển thực tập hoặc việc làm ở nhiều công ty, tôi muốn quản lý được các vị trí đã nộp, hạn tuyển và trạng thái phản hồi, để không bỏ lỡ lịch phỏng vấn hoặc nộp trùng. |
| Actor | Sinh viên năm cuối đang ứng tuyển nhiều vị trí thực tập hoặc việc làm. |
| Thời điểm / bối cảnh | Trong đợt tìm việc, khi kiểm tra phản hồi và xác định hồ sơ cần xử lý tiếp. |
| Quy trình hiện tại (3–7 bước) | Kiểm tra email → kiểm tra nền tảng tuyển dụng → đối chiếu với hồ sơ đã gửi → cập nhật trạng thái → ghi lịch và việc tiếp theo. Tổng minh họa: 15 phút/lần. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Dự kiến: bước 3, đối chiếu phản hồi với hồ sơ đã gửi, 6 phút/lần do thông tin nằm ở nhiều nơi. |
| Impact (nếu không giải thì sao) | Mất 15 phút/lần cập nhật theo kịch bản minh họa; có nguy cơ bỏ sót phản hồi, quên lịch hoặc nộp trùng. |
| Success metric (baseline → target) | 15 → không quá 7 phút/lần; ghi nhận đầy đủ lịch phỏng vấn đã xác nhận. Đo trung bình 5 lần cập nhật trước và 5 lần sau thay đổi; đối chiếu lịch với email/nền tảng tuyển dụng trong 2 tuần thử nghiệm. |
| Phương án không dùng AI | Dùng một bảng tính gồm công ty, vị trí, ngày nộp, hạn tuyển, trạng thái, việc tiếp theo và link nguồn; đặt lịch nhắc các mốc quan trọng. |
| Giả thuyết về AI (nếu có) | Nếu việc đối chiếu vẫn nghẽn sau khi dùng bảng theo dõi, AI có thể gợi ý ghép phản hồi với hồ sơ dựa trên công ty, vị trí và ngày nộp. Người dùng kiểm tra trước khi lưu; AI không tự gửi email hoặc ứng tuyển. |
| Cảm nhận nhanh | No AI hoặc Rule có thể đủ. |

Quy trình nháp hiện tại — tổng 15 phút/lần:

```text
[1. Kiểm tra email: 3 phút]
→ [2. Kiểm tra nền tảng tuyển dụng: 2 phút]
→ [3. Đối chiếu với hồ sơ đã gửi: 6 phút] ← BOTTLENECK DỰ KIẾN
→ [4. Cập nhật trạng thái: 3 phút]
→ [5. Ghi lịch và việc tiếp theo: 1 phút]
```

### Problem Card #2 — Định dạng báo cáo theo quy định của khoa

| Trường | Nội dung |
|---|---|
| Job Story | Khi hoàn thiện báo cáo, tôi muốn trình bày tài liệu đúng quy định của khoa, để hạn chế phải sửa lại định dạng nhiều lần trước khi nộp. |
| Actor | Sinh viên làm báo cáo bài tập lớn, đồ án hoặc khóa luận có yêu cầu trình bày cụ thể. |
| Thời điểm / bối cảnh | Sau khi hoàn thiện nội dung hoặc nhận góp ý, trước khi gửi bản thảo hay nộp chính thức. |
| Quy trình hiện tại (3–7 bước) | Đọc quy định → đối chiếu bản thảo → sửa định dạng → cập nhật mục lục/danh mục → xuất PDF và kiểm tra. Tổng minh họa: 120 phút/đợt hoàn thiện. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Dự kiến: bước 3, sửa thủ công tiêu đề, đoạn văn, bảng và hình chưa thống nhất, tổng cộng 50 phút/đợt. |
| Impact (nếu không giải thì sao) | Theo kịch bản minh họa, mất 2 giờ cho định dạng qua 3 lượt sửa; có nguy cơ giảm thời gian kiểm tra nội dung hoặc còn lỗi trình bày khi nộp. |
| Success metric (baseline → target) | 120 → không quá 60 phút/đợt với tài liệu có độ dài và số bảng/hình tương đương. Đo bằng nhật ký thời gian; bản PDF cuối đạt toàn bộ mục trong checklist định dạng của khoa. |
| Phương án không dùng AI | Dùng template chính thức; thiết lập Styles, heading, caption, mục lục và danh mục tự động; kiểm tra bằng checklist trước khi xuất PDF. |
| Giả thuyết về AI (nếu có) | AI có thể hỗ trợ giải thích yêu cầu trình bày hoặc gợi ý thao tác. Mọi hướng dẫn phải đối chiếu với quy định chính thức; không để AI tự thay đổi nội dung chuyên môn. |
| Cảm nhận nhanh | No AI hoặc Rule có thể đủ vì phần lớn yêu cầu định dạng là quy tắc xác định. |

Quy trình nháp hiện tại — tổng cộng 120 phút cho cả đợt gồm 3 lượt sửa; thời gian từng bước là cộng dồn:

```text
[1. Đọc quy định trình bày: 15 phút]
→ [2. Đối chiếu bản thảo: 20 phút]
→ [3. Sửa tiêu đề, đoạn văn, bảng và hình: 50 phút] ← BOTTLENECK DỰ KIẾN
→ [4. Cập nhật mục lục và danh mục: 15 phút]
→ [5. Xuất PDF và kiểm tra lại: 20 phút]
```

### Problem Card #3 — Đọc và tổng hợp tài liệu nghiên cứu

| Trường | Nội dung |
|---|---|
| Job Story | Khi đọc tài liệu cho khóa luận hoặc nghiên cứu khoa học, tôi muốn xác định được kết quả chính, phương pháp và điểm khác nhau giữa các nghiên cứu, để chọn tài liệu phù hợp và xây dựng phần tổng quan. |
| Actor | Sinh viên năm cuối hoặc sinh viên làm nghiên cứu khoa học đang xây dựng phần tổng quan cho một đề tài cụ thể. |
| Thời điểm / bối cảnh | Khi đọc các bài đã sàng lọc và cập nhật thông tin vào bảng tổng hợp tài liệu. |
| Quy trình hiện tại (3–7 bước) | Đọc tóm tắt/mục tiêu → đọc phương pháp → đọc kết quả/hạn chế → ghi chú → đối chiếu với các bài trước → cập nhật bảng tổng quan và nguồn. Tổng minh họa: 60 phút/bài. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Dự kiến: bước 2, đọc hiểu phương pháp, 20 phút/bài. Cần hiểu đúng phương pháp trước khi ghi chú và so sánh các nghiên cứu; nguyên nhân gây chậm cần xác nhận thực tế. |
| Impact (nếu không giải thì sao) | Với 4–5 bài/tuần và 60 phút/bài trong kịch bản minh họa, tổng thời gian là 240–300 phút/tuần. Có nguy cơ phải đọc lại hoặc bỏ sót khác biệt quan trọng nếu ghi chú không đầy đủ. |
| Success metric (baseline → target) | 60 → không quá 40 phút/bài. Ghi chú đủ phương pháp, kết quả, hạn chế và vị trí nguồn; mục nào bài gốc không nêu thì ghi rõ. Đo trung bình ít nhất 3 bài trước và 3 bài sau có độ dài/độ khó tương đương; đối chiếu ghi chú với bài gốc. |
| Phương án không dùng AI | Dùng bảng tổng hợp thống nhất: mục tiêu, phương pháp, dữ liệu, kết quả, hạn chế, mức liên quan và nguồn; dùng công cụ quản lý tài liệu tham khảo; ghi vị trí nguồn ngay khi đọc. |
| Giả thuyết về AI (nếu có) | Nếu cách ghi chú thống nhất vẫn chưa đủ, AI có thể hỗ trợ giải thích phương pháp và trích xuất thông tin từ bài được cung cấp. Sinh viên kiểm tra với bản gốc; không dùng trích dẫn hoặc kết quả không có nguồn. |
| Cảm nhận nhanh | Cân nhắc Workflow nếu kiểm chứng cho thấy No AI/Rule không đủ. |

Quy trình nháp hiện tại — tổng 60 phút/bài đã chọn, chưa tính thời gian tìm kiếm ban đầu:

```text
[1. Đọc tóm tắt và mục tiêu: 5 phút]
→ [2. Đọc hiểu phương pháp: 20 phút] ← BOTTLENECK DỰ KIẾN
→ [3. Đọc kết quả và hạn chế: 15 phút]
→ [4. Ghi chú có vị trí nguồn: 10 phút]
→ [5. Đối chiếu với các bài trước: 8 phút]
→ [6. Cập nhật bảng tổng quan và nguồn: 2 phút]
```

### Card muốn pitch nhất

- Card số: 3.
- Vì sao: Có thể phân tích rõ phần đọc hiểu, ghi chú và đối chiếu; có cơ hội so sánh cách làm không dùng AI với AI hỗ trợ nhưng vẫn phải kiểm tra độ chính xác.
- Câu hỏi muốn nhóm phản biện: Nếu đã dùng một bảng ghi chú thống nhất thì còn cần AI không? Bằng chứng nào cho thấy bước nghẽn thực sự nằm ở đọc hiểu phương pháp?

### AI đã phản biện card thế nào

Tôi tổng hợp các góp ý của AI và nội dung đã điều chỉnh trong bảng dưới đây.

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Card #1: Giả thuyết AI ban đầu tập trung vào đọc và nhập email, chưa khớp bottleneck là đối chiếu phản hồi với hồ sơ đã gửi. | Đồng ý | Đã chỉnh giả thuyết AI thành gợi ý ghép phản hồi với hồ sơ; chỉ cân nhắc nếu bảng theo dõi chưa đủ và người dùng phải kiểm tra trước khi lưu. |
| Card #2: Mốc 120 phút và 3 lượt sửa có thể bị hiểu thành 120 phút cho mỗi lượt. | Đồng ý | Đã ghi rõ 120 phút là tổng cả đợt gồm 3 lượt sửa; thời gian từng bước được cộng dồn, không nhân thêm 3 lần. |
| Card #3: Job Story nói về tìm tài liệu nhưng quy trình chỉ mô tả đọc và tổng hợp những bài đã chọn. | Đồng ý | Đã đổi bối cảnh thành đọc tài liệu và ghi rõ 60 phút/bài chưa gồm thời gian tìm kiếm ban đầu. |
| Cả 3 card: Metric chỉ giảm thời gian sẽ chưa cho biết chất lượng công việc có được giữ lại không. | Đồng ý | Đã thêm tiêu chí: ghi nhận đủ lịch phỏng vấn, đạt checklist định dạng và đối chiếu ghi chú nghiên cứu với bài gốc. |
| Cả 3 card: Số liệu minh họa và bước có thời gian lớn nhất chưa đủ để xác nhận bottleneck thực tế. | Đồng ý | Đã gắn nhãn số liệu minh họa và bottleneck dự kiến. Phần cần tự làm tiếp: đo từng bước, kiểm tra nguyên nhân gây chậm và cập nhật baseline theo thực tế. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

Tôi tham gia trình bày, phản biện, thảo luận và rà soát bài nhóm. Bảng dưới ghi phần việc tham gia và kết quả chung của LuckyTeam.

| Hoạt động | Tôi đã làm gì? | Kết quả chung / nội dung được nhóm ghi nhận |
|---|---|---|
| Pitch Problem Card | trình bày 3 candidate #10, #11, #12: theo dõi ứng tuyển, định dạng báo cáo và đọc tài liệu nghiên cứu. | #10 vào cluster B, #11 vào cluster D, #12 vào cluster A; #12 được gộp với #7 vào shortlist. |
| Phản biện bài của bạn khác | hỏi Tùng Lâm (#6): “Nhóm lấy được dữ liệu GPS và tình trạng giao thông của tuyến không? Không có thì làm sao so sánh Rule với AI?”; hỏi Quang Hải (#9) về pattern trùng với #3 và quyền riêng tư khi đọc chat. Tôi hỏi Đức Hải (#1): “SUBMISSION.md đã có checklist 10 mục. Vậy đề thiếu thông tin, hay chỉ là không biết đọc file nào trước?” | Nhóm ghi nhận rủi ro thiếu dữ liệu ở candidate VinBus, gom các vấn đề tìm thông tin trong chat và xem xét lại giải pháp No AI cho việc đọc đề. |
| Nhận phản biện | tiếp nhận câu hỏi của Quang Hải về số liệu minh họa và bảng tính ở #10; câu hỏi của Đức Hải về template + Styles ở #11; câu hỏi của Tùng Lâm về việc gộp #12 với #7 và nguyên nhân đọc chậm. | Báo cáo nhóm gộp #12 với #7 và ghi Pain = 2 do chưa có số đo thật. CP2 giữ phương án không dùng AI và nhãn số liệu minh họa. |
| Gom cluster / cây OST | tham gia trao đổi về điểm chung giữa các card; đối chiếu 3 card của mình với các cluster và phân biệt nhu cầu với giải pháp trong cây OST. | Theo mục 2.2–2.3, #10 thuộc cluster B, #11 thuộc D, #12 thuộc A. Card #12 được đặt dưới opportunity về đọc và nghiên cứu nhiều nguồn; tầng opportunity không chứa tên công cụ AI. |
| Chọn candidate problem | tham gia thảo luận shortlist theo actor, bằng chứng, khả năng đo impact và phạm vi lab; cân nhắc hạn chế của card nghiên cứu của mình khi so với bài toán đọc đề. | Theo mục 2.4, nhóm chọn #1 Đọc đề lab (33 điểm). Candidate #7 + #12 đạt 24 điểm và chưa được chọn vì baseline chưa đo, chất lượng tổng hợp khó đánh giá trong buổi lab. |
| Kiểm chứng / research | tham gia rà soát giả định, hai Interview Snapshot và bảng research; đối chiếu tín hiệu xác nhận, phản bác với vấn đề đang phân tích.  | Hai cuộc phỏng vấn trong báo cáo cho thấy thời gian kiểm tra yêu cầu khác nhau giữa người học, checklist có thể giúp ích và lỗi thao tác vẫn cần bước kiểm cuối. Nhóm thu hẹp bài toán sang gom điều kiện chấm và kiểm các yêu cầu có quy tắc. |
| Quy trình nhóm | Tôi tham gia rà soát quy trình trước/sau, bước đối chiếu yêu cầu và việc đặt bước kiểm tên repo/file sau thao tác; xem xét thời gian và vai trò con người ở từng bước. | Theo mục 4, quy trình hiện tại là 45 phút/lab; phương án đề xuất khoảng 18 phút/lab, gồm 2 bước Rule và 4 bước thủ công. Có bước mở nguồn gốc để kiểm tra và phương án quay về đọc thủ công. 18 phút vẫn là ước tính. |
| Problem Statement | tham gia thảo luận và rà các trường bottleneck, success metric và boundary khi đối chiếu v0 với v1; chú ý việc giảm thời gian phải đi cùng độ đầy đủ của yêu cầu. | Theo mục 5 và 7, v1 bổ sung độ phủ điều kiện chấm, 0 lỗi tên repo/file, bước fork/đặt tên và boundary riêng cho Rule. Người học vẫn kiểm tra nguồn, công cụ không tự bỏ yêu cầu hoặc đổi tên. |
| Mức can thiệp AI | tham gia so sánh No AI, Rule, Workflow và Agent; xem xét việc chỉ đổi thứ tự đọc đã đủ chưa và khi nào cần công cụ hỗ trợ cao hơn. | Theo mục 6, nhóm chọn Rule kèm đổi thứ tự đọc. Workflow có trích dẫn là phương án dự phòng nếu Rule không đủ; Agent không phù hợp với các bước cố định của bài toán. |
| Quyết định | tham gia thảo luận kết luận, các rủi ro còn lại và điều kiện cần đánh giá lại lựa chọn; đối chiếu No-Go cho AI với kế hoạch tiếp tục thử Rule. | Theo mục 8, nhóm chốt No-Go cho AI và thử Rule ở 2 lab tiếp theo. Nếu còn sót tiêu chí hoặc thời gian vẫn trên 20 phút sau 2 lab, đánh giá lại và cân nhắc Workflow; nếu nhu cầu thấp thì thu hẹp giải pháp. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 — Scan problem | chọn phạm vi và giữ lại 5 vấn đề; nhờ AI gợi ý thêm góc nhìn và hỗ trợ diễn đạt Job Story. | Làm rõ lăng kính, actor và cách tìm dấu hiệu thực tế. | Các con số AI gợi ý chỉ là minh họa. | Chọn các vấn đề đưa vào báo cáo; còn cần xác nhận số liệu theo trải nghiệm của mình. |
| CP2 — Problem Card | chọn 3 chủ đề, đọc và xác nhận các phản biện; AI hỗ trợ bản nháp rồi rà quy trình, metric và câu chữ. | Phát hiện chỗ chưa khớp giữa bottleneck với giả thuyết AI, bổ sung cách kiểm tra chất lượng. | Phạm vi 120 phút/đợt và 60 phút/bài ban đầu chưa rõ; baseline chưa được đo. | Đồng ý các góp ý đã ghi ở CP2; giữ phương án không dùng AI và các giới hạn cần kiểm tra trong bản cuối. |
| CP4 — Research, rà tài liệu | tham gia cùng nhóm đọc và trao đổi về nguồn, giả định và bằng chứng; nhờ AI rà cách lập luận, trình bày. | Chỉ ra cần phân biệt dữ kiện, giả định và kết luận về nguyên nhân. | AI đọc báo cáo chưa đồng nghĩa đã kiểm chứng nguồn hoặc chạy lại phép đếm. | Đối chiếu góp ý với phần research của nhóm; giữ giới hạn của mẫu và tránh suy rộng kết quả. |
| CP5 — Quy trình | tham gia rà quy trình trước/sau; nhờ AI giải thích yêu cầu và đối chiếu cách trình bày các bước. | Làm rõ thời gian, bước người kiểm và phương án quay về. | AI không xác nhận được thời gian thực tế của quy trình đề xuất. | Giữ mốc 18 phút là ước tính; giữ bước kiểm nguồn và kiểm tên repo/file trong quy trình. |
| CP5–CP6 — Problem Statement | tham gia rà v0/v1; nhờ AI đọc và chỉ ra các thay đổi cần đối chiếu. | Làm rõ baseline, target, độ phủ điều kiện và boundary. | Nội dung diễn đạt mạch lạc vẫn có thể dựa trên baseline ít mẫu. | Đối chiếu với bản nhóm; giữ cách đo, giới hạn baseline một người và các chỉ số chất lượng. |
| CP6 — Mức can thiệp, quyết định | cùng nhóm thảo luận lựa chọn; nhờ AI giải thích các mức và rà tính nhất quán của kết luận. | Làm rõ lý do chọn Rule và điều kiện cân nhắc Workflow. | Kết quả thử trên một đề chưa đủ chứng minh áp dụng được cho mọi lab. | Giữ quyết định Rule kèm đổi thứ tự đọc, kế hoạch thử ở hai lab sau và ngưỡng dừng đã thống nhất. |

---

## 6. Reflection (CP7)

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Qua các card của nhóm, tôi thấy một vấn đề gần gũi chưa chắc đã phù hợp để giải quyết trong phạm vi lab. Chẳng hạn, bài toán chờ VinBus có ảnh hưởng rõ nhưng nhóm thiếu dữ liệu vị trí xe và giao thông. Bài toán đọc đề lab có phạm vi nhỏ hơn, nhưng nhóm tiếp cận được tài liệu và có thể kiểm tra ngay các yêu cầu. Bài học tôi rút ra là cần cân nhắc bằng chứng, dữ liệu và khả năng đánh giá bên cạnh mức độ phiền toái của vấn đề.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Nhóm có những ý mang tính giải pháp như “chatbot hỏi đáp đề lab” hoặc “tự động gom nhóm ý chính”. Khi lập cây OST, nhóm tách các ý đó khỏi tầng opportunity và quay lại mô tả khó khăn: thông tin nằm ở nhiều nguồn, phải đối chiếu và dễ sót điều kiện. Tôi thấy cách làm này giúp thảo luận rõ hơn, vì cùng một khó khăn có thể được xử lý bằng đổi thứ tự đọc, checklist hoặc Rule, thay vì mặc định cần AI.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Câu hỏi của Tùng Lâm về card nghiên cứu của tôi — chậm do đọc hay do thiếu kiến thức nền — cho thấy việc nêu thời gian chưa đủ để xác định nguyên nhân. Tôi điều chỉnh cách trình bày bằng cách giữ bottleneck ở mức dự kiến và ghi rõ số liệu chưa đo. Với phản biện ở CP2, tôi cũng đồng ý sửa phạm vi từ tìm tài liệu sang đọc các bài đã chọn, đồng thời bổ sung kiểm tra chất lượng ghi chú. Card cần giải thích đúng công việc đang gặp khó khăn trước khi đề xuất cách hỗ trợ.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Điểm đáng chú ý khi rà kết quả kiểm chứng là người học có cách xử lý rất khác nhau. SV-01 kể việc đối chiếu ba nguồn mất 35 phút và phải bổ sung nội dung; SV-02 dùng checklist, kiểm tra trong 12 phút rồi thêm 2 phút đổi tên file. Điều này khiến tôi thận trọng với giả định mọi người đều mất nhiều thời gian đọc yêu cầu. Hai tình huống cũng thuộc bối cảnh khác lab K5, nên nhóm vẫn cần đo lại trên đúng đối tượng trước khi kết luận hiệu quả của giải pháp.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Khi tham gia rà Problem Statement, phần tôi cần cân nhắc nhiều là success metric và phạm vi đo. Baseline 45 phút mới là số tự ghi của một người, còn 18 phút của quy trình tương lai là ước tính. Vì vậy, mục tiêu không quá 20 phút cần được kiểm tra ở các lab sau. Ngoài tốc độ, nhóm phải đo độ đầy đủ của điều kiện và lỗi tên repo/file. Tôi hiểu rằng một metric tốt cần cho biết vừa làm nhanh hơn vừa giữ được chất lượng, cùng cách đo rõ ràng.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu làm lại, tôi sẽ ghi thời gian từng bước ngay từ CP1 và CP2, đồng thời phân biệt số đo, ước lượng và mục tiêu đề xuất. Tôi cũng sẽ hỏi người dùng sớm hơn để kiểm tra nguyên nhân trước khi nhóm thu hẹp bài toán. Khi phản biện, tôi muốn hỏi kỹ hơn phương án không dùng AI đã giải được phần nào, phần nào còn vướng và bằng chứng nào cho thấy cần mức cao hơn. Cách này giúp nhóm chọn giải pháp vừa sức và giảm các kết luận dựa trên giả định.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Bài toán nhóm tôi chọn là học viên K5 mất thời gian tìm và đối chiếu điều kiện chấm ở đầu mỗi lab. Quy trình hiện tại gồm đọc các file hướng dẫn, đối chiếu yêu cầu và ghi danh sách việc cần làm, với baseline 45 phút do một người tự ghi. Bottleneck là bước đối chiếu khoảng 10 phút vì cần chốt điều kiện trước khi chia việc, trong khi một phần tài liệu có thể đọc khi làm từng checkpoint. Nhóm đặt mục tiêu không quá 20 phút, giữ đủ điều kiện chấm và không sai tên repo/file; khoảng 18 phút của quy trình đề xuất vẫn cần đo lại. Boundary yêu cầu Rule chỉ trích nguyên văn kèm nguồn, lệnh kiểm tên chỉ báo và người học phải kiểm lại phần chưa rõ. Nhóm chọn Rule kèm đổi thứ tự đọc vì các thao tác có quy tắc cố định, chưa cần AI tạo nội dung hoặc tự quyết bước tiếp theo. Quyết định là No-Go cho AI, thử Rule ở hai lab sau và đánh giá lại nếu vẫn sót điều kiện hoặc thời gian trên 20 phút.

---

## 7. Tài liệu tham khảo

1. [Repo nhóm LuckyTeam](https://github.com/ndhai255/K5-L3B-DAY02-LuckyTeam-DiscoveryProblemFraming).
2. [report/team/group_report.md](../team/group_report.md).
3. [docs/01-worksheet.md](../../docs/01-worksheet.md).
4. [CHECKPOINTS.md](../../CHECKPOINTS.md).
5. [RUBRIC.md](../../RUBRIC.md).
6. [RULES.md](../../RULES.md).
7. [SUBMISSION.md](../../SUBMISSION.md).
8. [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).
9. [docs/03-international-frameworks.md](../../docs/03-international-frameworks.md).
