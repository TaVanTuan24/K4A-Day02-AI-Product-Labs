# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Tạ Văn Tuấn
- Mã học viên: 2A202602806
- Nhóm: Thân Tý Dậu
- Candidate problem nhóm chọn: Chuẩn bị checklist lab từ đúng nguồn và đúng phiên bản

---

## 1. Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi scan 10 vấn đề từ trải nghiệm học AI, làm lab và luyện coding; sau đó chọn Top 3 gồm hiểu yêu cầu GitHub lab, debug thuật toán và tổng hợp kiến thức kỹ thuật. | Nhóm có thêm ba candidate cụ thể, trong đó bài toán yêu cầu GitHub lab trùng với pain của nhiều thành viên khác. |
| Pitch Problem Card | Tôi pitch bài “Hiểu đúng yêu cầu GitHub lab và không bỏ sót deliverable”, nêu workflow đọc README → worksheet → example → map yêu cầu → kiểm tra lại, với baseline sơ bộ 30–45 phút/lab. | Candidate có actor, bottleneck và metric đủ rõ để đưa vào shortlist của nhóm. |
| Challenge bài của bạn khác | Tôi hỏi liệu các bài planning/report có đủ dữ liệu Jira và template chuẩn để pilot hay không; với bài của mình, tôi đặt câu hỏi liệu checklist/rule đã giải được phần lớn pain mà chưa cần AI hay chưa. | Nhóm không chọn theo độ “ngầu” của solution và giữ Rule-only làm phương án đối chứng. |
| Gom trùng / cluster | Tôi cùng nhóm tổng hợp 21 candidate từ 7 thành viên và gom thành bốn cụm: yêu cầu/bài nộp lab; đọc/tổng hợp kiến thức; planning/reporting; debug/issue/handoff. | Các ý trùng được nhìn thành pattern chung, giúp shortlist không bị chi phối bởi cách diễn đạt của từng người. |
| Chọn candidate problem | Tôi tham gia chấm ba candidate theo bảy tiêu chí và ủng hộ bài checklist lab vì đạt 34/35, có evidence trực tiếp từ 4/7 thành viên và dữ liệu pilot sẵn có. | Nhóm chọn được một candidate duy nhất, có scope nhỏ và liên quan trực tiếp tới bối cảnh học hiện tại. |
| Validation / research | Tôi cung cấp các bảng Top 3 làm mini-poll nội bộ, tách rõ 4/7 tín hiệu trực tiếp và 2/7 tín hiệu gần kề; đồng thời kiểm lại các pattern GitHub Copilot Spaces, Discord Search và Gemini Notebook qua nguồn chính thức. | Nhóm không bịa interview, thu hẹp problem thành tạo checklist có dẫn nguồn và ghi rõ validation còn hạn chế. |
| Workflow nhóm | Tôi góp phần mô tả current workflow 7 bước, xác định bước map nhiều nguồn thành checklist là bottleneck; ở future workflow tôi giữ hai human boundary là chọn nguồn và xác minh từng mục. | Workflow thể hiện rõ việc nào do Rule, AI và con người làm, cùng fallback `UNRESOLVED` khi nguồn thiếu hoặc mâu thuẫn. |
| Problem Statement | Tôi giúp sửa v0 bằng cách định nghĩa output cụ thể là `phase → task → required field → output file → deadline → source`, đồng thời thêm cách đo trên ba lab. | Problem Statement v1 có actor, workflow, bottleneck, impact, metric, boundary và AI intervention point nhất quán. |
| Rule / Workflow / Agent | Tôi lập luận rằng bài toán có độ phức tạp cao nhưng độ mơ hồ thấp; Rule xử lý metadata/format/validator, AI chỉ extract ngôn ngữ tự nhiên, còn sinh viên review. | Nhóm chọn Workflow thay vì Agent và giữ khả năng hạ xuống Rule-only nếu AI không tạo thêm giá trị. |
| Decision | Tôi ủng hộ `Go` với pilot bán thủ công trên ba lab cũ nhưng `Not Yet` cho tích hợp tự động với Discord/GitHub hoặc Agent. | Quyết định có điều kiện dừng rõ: 0 deliverable thiếu, 100% item có nguồn, ≤15 phút và phải tốt hơn Rule-only. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là candidate “Hiểu đúng yêu cầu GitHub lab và không bỏ sót
deliverable” cùng câu challenge “checklist/rule đã đủ chưa?”. Hai ý này trở thành trục
chính của Problem Statement, phương án đối chứng và quyết định không chọn Agent.
```

---

## 2. Bảng dùng AI

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Sau khi tự liệt kê các pain, tôi dùng AI để nhóm chúng theo bốn lăng kính và gợi ý thêm cách đo. | AI giúp chuyển các quan sát rời rạc thành bảng có actor và dấu hiệu thật. | Một số gợi ý quá rộng hoặc nghe giống ý tưởng sản phẩm hơn là problem thật. | Tôi bỏ các ý không xuất phát từ trải nghiệm của mình và chỉ giữ 10 pain đã từng gặp. |
| Problem Card | Tôi nhờ AI phản biện actor, workflow, bottleneck, metric và non-AI alternative của Top 3. | AI chỉ ra rằng “hiểu đúng yêu cầu” cần đổi thành output kiểm được như checklist và file tree. | AI ban đầu viết dài và có xu hướng nhảy sớm sang “Agent đọc GitHub”. | Tôi thu hẹp scope, giữ source gốc là source of truth và chọn quick gut là Workflow. |
| Workflow | Tôi dùng AI để chuyển mô tả thành current/future workflow có thời gian, actor, boundary và fallback. | AI giúp nhìn rõ bottleneck nằm ở bước map nhiều nguồn chứ không phải chỉ ở bước đọc. | Các con số thời gian do AI sắp xếp chỉ là ước lượng, chưa phải log đã bấm giờ. | Tôi ghi rõ baseline sơ bộ và đưa việc đo lại ba lab vào pilot. |
| Research | Tôi dùng AI/search để tìm các giải pháp và pattern tương tự. | AI giúp tìm nhanh GitHub Copilot Spaces, Discord Search và Gemini Notebook để so sánh các bước đã được giải quyết. | AI có thể đưa claim tiết kiệm thời gian hoặc tính năng không có nguồn kiểm chứng. | Tôi chỉ giữ thông tin có trang chính thức, không dùng số liệu hiệu quả chưa được xác minh. |
| Problem Statement | Tôi dùng AI để kiểm tra v0 có thiếu field nào và hỗ trợ sắp xếp thành v1. | AI giúp làm rõ metric, boundary, AI intervention point và người chịu trách nhiệm kiểm tra. | AI từng gộp cả tóm tắt kiến thức, nhắc deadline, giải bài và kiểm bài vào cùng một solution. | Tôi giới hạn output vào yêu cầu/deadline/deliverable có dẫn nguồn; loại bỏ giải bài và tóm tắt sâu kiến thức. |
| Rule / Workflow / Agent | Tôi yêu cầu AI so sánh ba mức trên cùng một workflow. | AI giúp phân tách phần deterministic cho Rule và phần hiểu ngôn ngữ cho AI. | AI có xu hướng xem nhiều nguồn là lý do để chọn Agent dù quy trình không cần tự lập kế hoạch. | Tôi dựa vào luồng tuyến tính và human boundary để chọn Workflow, đồng thời giữ Rule-only làm baseline. |
| Decision | Tôi dùng AI để gợi ý pilot, metric và điều kiện rollback. | AI giúp biến quyết định thành phép thử có thể đo thay vì kết luận cảm tính. | AI ban đầu quá tự tin với evidence nội bộ và có thể gọi đó là validation đầy đủ. | Tôi đổi thành `Go với pilot nhỏ`, ghi `Not Yet` cho tự động hóa và yêu cầu phỏng vấn thêm người ngoài nhóm. |

---

## 3. Reflection câu hỏi mở

**Reflection:**

```text
Khi nghe 21 candidate problems của các thành viên, tôi nhận ra nhiều ý khác tên nhưng cùng bắt nguồn từ việc phải tìm và nối thông tin rời rạc.
Candidate về checklist lab thuyết phục tôi nhất vì nó xuất hiện trực tiếp ở bốn thành viên và gần với trải nghiệm học hiện tại của cả nhóm.
Ban đầu tôi nghĩ một AI Agent tự đọc GitHub và Discord sẽ là hướng hấp dẫn, nhưng sau khi vẽ workflow tôi thấy các bước chính đã cố định và không cần Agent tự lập kế hoạch.
Câu challenge quan trọng nhất đối với tôi là liệu một README chuẩn cùng checklist có giải được phần lớn vấn đề mà không cần AI hay không.
Vì vậy tôi thay đổi quan điểm và chọn Workflow kết hợp Rule, một bước AI extract và sinh viên review thay cho Agent.
Phần khó nhất khi viết Problem Statement là không biến “chuẩn bị lab tốt hơn” thành một mục tiêu mơ hồ, nên tôi cùng nhóm định nghĩa output, baseline, target và cách đo cụ thể.
Đóng góp rõ nhất của tôi là đưa candidate yêu cầu GitHub lab vào shortlist và giữ Rule-only làm phương án đối chứng trong pilot.
AI giúp tôi cấu trúc bảng, phản biện field và tìm pattern tương tự nhanh hơn, nhưng nó cũng từng mở rộng scope và đề xuất số liệu chưa được kiểm chứng.
Nếu làm lại, tôi sẽ phỏng vấn hai hoặc ba học viên ngoài nhóm và bấm giờ cùng một lab trước khi chốt baseline 30–45 phút.
Bài học lớn nhất của tôi là chất lượng của một AI product bắt đầu từ workflow, metric và boundary rõ chứ không bắt đầu từ việc chọn model hay Agent.
```

---

## 4. Tự kiểm cuối bài

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI


