# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Tạ Văn Tuấn
- Mã học viên: 2A202602806
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên mới tốt nghiệp
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):

---

## Scan rộng

Đã scan 10 problems, vượt mức tối thiểu 5. Mỗi dòng có actor và dấu hiệu thực tế để tiếp tục kiểm chứng.

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Tốn thời gian + Lặp lại | Khi nhận một GitHub repo bài tập, mất nhiều thời gian đọc README, worksheet, example và xác định chính xác phải tạo những file nào | Sinh viên làm lab | Đã nhiều lần phải quay lại kiểm tra yêu cầu hoặc phát hiện thiếu file/phần cần nộp |
| 2 | Tốn thời gian | Khi code LeetCode/C++, khó xác định nguyên nhân chính xác khi code compile được nhưng Wrong Answer hoặc logic sai | Sinh viên luyện coding/interview | Thường phải trace lại từng bước, gửi code/screenshot và sửa nhiều lần |
| 3 | AI có thể tốt hơn | Khi học một thuật toán mới, khó chuyển từ “hiểu lời giải” sang “tự nhận ra pattern để giải” | Người luyện coding | Hiểu lời giải sau khi xem nhưng có thể không nhận ra pattern khi gặp bài tương tự |
| 4 | Tốn thời gian | Học các khái niệm AI như Transformer, Attention, SFT, RLHF, DPO từ nhiều tài liệu rời rạc | Sinh viên AI | Phải đọc website, slide, diagram và giải thích lại thuật ngữ nhiều lần |
| 5 | Pain từ người khác | Khi làm bài theo nhóm, mọi người có thể hiểu khác nhau về deliverable, scope hoặc file cần nộp | Thành viên nhóm | Dễ phải hỏi lại “phần này làm gì?”, “file này nằm đâu?”, “cần nộp cái gì?” |
| 6 | AI có thể tốt hơn | Tìm project cybersecurity vừa mới, hữu dụng và không trùng các project đã có mất nhiều công research | Sinh viên làm project | Phải xem nhiều project/repository rồi mới so sánh novelty và feasibility |
| 7 | Tốn thời gian | Khi phân tích APK, phải dùng nhiều công cụ để decompile, search endpoint và xác định app tải gì từ server | Người phân tích ứng dụng | Thông tin nằm rải rác trong code, manifest, strings và network logic |
| 8 | Tốn thời gian | Khi viết literature review, phải đọc nhiều paper và nối các nghiên cứu theo theme thay vì chỉ tóm tắt từng paper | Sinh viên nghiên cứu | Khó quản lý source, theme, research gap và citation cùng lúc |
| 9 | Lặp lại | Khi gặp lỗi API/model như rate limit, TPM hoặc request failure, phải đọc log rồi tìm nguyên nhân và cách retry | Developer dùng API/LLM | Các lỗi có cấu trúc giống nhau nhưng vẫn phải kiểm tra log thủ công |
| 10 | Lặp lại + Tốn thời gian | Tìm lại kiến thức, quyết định hoặc lời giải đã xuất hiện trong GitHub, chat, tài liệu học trước đó | Sinh viên | Biết thông tin đã từng đọc nhưng không nhớ nằm ở đâu, phải search lại nhiều nguồn |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

### AI đã dùng ở Phase 1
- Prompt đã hỏi: Kiểm tra lịch sử trò chuyện và tìm hiểu xem việc nào tôi tốn nhiều thời gian để hỏi nhất
- Ý dùng được: Tốn nhiều thời gian để đọc lại và phân tích readme các repo github để thực hiện đúng quy trình
- Ý bỏ vì không phải pain thật:

### Self-check Phase 1
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Top 3 Problem Cards

Giữ bài có actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở một bước và impact đo được.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Hiểu đúng yêu cầu của GitHub lab và không bỏ sót deliverable | Pain xảy ra trực tiếp khi học; workflow rõ; dễ đo số lần phải sửa và thời gian đọc yêu cầu | Bao nhiêu phần có thể giải bằng checklist/rule mà không cần AI |
| 2 | Debug code khi luyện thuật toán nhưng vẫn phải hiểu nguyên nhân lỗi | Xảy ra thường xuyên, impact lớn đến tốc độ học và khả năng interview | AI hỗ trợ đến mức nào mà không làm giảm khả năng tự suy nghĩ |
| 3 | Tổng hợp kiến thức kỹ thuật từ nhiều tài liệu rời rạc | Xuất hiện ở nhiều môn/chủ đề, workflow rõ và có thể đo thời gian | Đo “hiểu tốt hơn” khách quan như thế nào |

---

## Problem Card #1 — Hiểu đúng yêu cầu GitHub Lab

**Problem 1 câu:**  
Khi nhận một GitHub repository chứa README, worksheet và example, sinh viên mất nhiều thời gian chuyển các hướng dẫn rời rạc thành một checklist cụ thể về những việc và file cần hoàn thành, dẫn đến nguy cơ bỏ sót deliverable và phải sửa lại.

**Actor:**  
Sinh viên tham gia các lab/project kỹ thuật được giao bài thông qua GitHub repository.

**Thời điểm / bối cảnh:**  
Khi bắt đầu một lab mới hoặc trước khi chuẩn bị submit bài.

**Current workflow:**

```text
1. Mở GitHub repository
2. Đọc README
3. Mở worksheet/hướng dẫn chi tiết
4. Mở deliverable example
5. Tự xác định mỗi Phase cần tạo output/file nào
6. Bắt đầu thực hiện bài
7. Quay lại README/worksheet để kiểm tra khi phát hiện thiếu hoặc không chắc yêu cầu
```

**Bottleneck:**  
Bước 5: chuyển nhiều đoạn hướng dẫn thành một cấu trúc:

Phase
→ việc cần làm
→ nội dung bắt buộc
→ file cần tạo
→ tiêu chí hoàn thành

Thông tin thường nằm ở nhiều vị trí khác nhau.

**Impact:**  
Tăng thời gian setup trước khi thực sự bắt đầu làm bài.
Dễ bỏ sót field hoặc file.
Phải sửa lại bài sau khi đã làm.
Tốn context-switch giữa README, worksheet và example.
**Success metric:**  
Mục tiêu:

Thời gian từ lúc mở repo
→ có checklist hoàn chỉnh:

30–45 phút → dưới 10–15 phút

Đồng thời:

Số deliverable bị bỏ sót: 0
Số lần phải sửa do hiểu sai cấu trúc bài: giảm ≥ 50%
**Non-AI alternative:**  
Tạo một template checklist cố định:

Phase | Task | Required fields | Output file | Done?

Ngoài ra có thể yêu cầu giảng viên đặt toàn bộ deliverable trong một SUBMISSION_CHECKLIST.md.

Giải pháp này đơn giản và có thể đã xử lý phần lớn problem.
**AI hypothesis:**  
AI có thể đọc:

README
+ worksheet
+ example

sau đó tự tạo:

Submission checklist
Phase-by-phase guide
Required file tree
Missing-field checker

AI không tự quyết định nội dung bài; sinh viên vẫn chịu trách nhiệm đọc và xác nhận checklist.
**Quick gut:**
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết

### Draft current workflow

```text
CURRENT STATE — 40 phút

[1. Mở repo: 2']
→ [2. Đọc README: 5']
→ [3. Đọc worksheet: 10']
→ [4. Xem example: 5']
→ [5. Map Phase → Deliverable: 10']  <-- bottleneck
→ [6. Bắt đầu làm]
→ [7. Quay lại check requirement: ~8']
```

### Draft future workflow

```text
FUTURE STATE — 10 phút

[README + Worksheet + Example]
→ [AI/Parser extract requirement: 1–2']
→ [Generate structured checklist: 1']
→ [Student kiểm tra checklist: 5']  <-- human boundary
→ [Thực hiện từng Phase]
→ [Validator check missing fields/files: 1–2']

Fallback: nếu AI sai thì hiểu sai requirement → mở source gốc → sinh viên tự sửa checklist.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

## Problem Card #2 — Debug code khi luyện thuật toán

**Problem 1 câu:**  
Khi luyện bài thuật toán, sinh viên thường mất nhiều thời gian xác định tại sao code sai và có xu hướng tìm lời giải quá sớm thay vì xác định chính xác bug hoặc lỗ hổng trong tư duy của mình.

**Actor:**  
Sinh viên luyện LeetCode/C++ để chuẩn bị technical interview.

**Thời điểm / bối cảnh:**  
Sau khi đã có ý tưởng và viết solution đầu tiên nhưng gặp:

Wrong Answer
runtime error
compile error
edge case sai
complexity không đạt

**Current workflow:**

```text
1. Đọc problem
2. Nghĩ solution
3. Viết code
4. Submit/run
5. Nhận error hoặc Wrong Answer
6. Đọc lại code và thử sửa
7. Trace input thủ công hoặc tìm lời giải/gửi AI
8. Sửa code và submit lại
```

**Bottleneck:**  
Bước 6–7.

Không biết lỗi nằm ở:

hiểu sai problem
        ↓
sai thuật toán
        ↓
sai data structure
        ↓
off-by-one
        ↓
edge case
        ↓
syntax/implementation

nên dễ sửa theo kiểu thử-sai.

**Impact:**  
Tốn nhiều thời gian cho một bug nhỏ.
Có thể xem solution quá sớm.
Fix được code nhưng chưa chắc hiểu nguyên nhân.
Khả năng nhận dạng pattern trong interview cải thiện chậm.
**Success metric:**  
Thời gian xác định root cause: 20–40 phút → dưới 15 phút

**Non-AI alternative:**  
Debugger.
Print/log.
Trace table.
Bộ test edge cases.
Checklist debugging.
Viết brute force để đối chiếu output.
**AI hypothesis:**  
AI đóng vai debugging coach, không phải solution generator.
**Quick gut:**
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết

### Draft current workflow

```text
CURRENT STATE — 20-40 phút

[Đọc problem]
→ [Nghĩ solution]
→ [Code]
→ [Submit]
→ [Wrong Answer]
→ [Đọc lại toàn bộ code]  <-- bottleneck
→ [Thử sửa]
→ [Submit lại]
→ [Nếu vẫn sai → tìm solution/AI]
```

### Draft future workflow

```text
FUTURE STATE — 15 phút

[Code fail]
→ [Chạy minimal failing test]
→ [Rule-based check: syntax / bounds / initialization]
→ [AI phân loại loại lỗi]
→ [AI đưa 1 hint hoặc counterexample]
→ [Student tự sửa]  <-- human boundary
→ [Student giải thích root cause]
→ [AI verify explanation]

Fallback: AI đưa hint sai → chạy brute-force/reference test → dùng debugger/trace thủ công.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

## Problem Card #3 — Tổng hợp kiến thức kỹ thuật từ nhiều nguồn

**Problem 1 câu:**  
Khi học một chủ đề kỹ thuật mới, sinh viên phải đọc nhiều website, GitHub repository, slide và diagram rồi tự nối chúng thành một mental model thống nhất, khiến quá trình học mất thời gian và dễ hiểu từng khái niệm rời rạc.

**Actor:**  
Sinh viên học AI/software.

**Thời điểm / bối cảnh:**  
Khi bắt đầu học một chủ đề mới, ví dụ:

Transformer
Attention
RLHF
DPO
AI Agent
**Current workflow:**

```text
1. Search khái niệm
2. Mở 3–5 nguồn
3. Đọc từng nguồn
4. Tra các thuật ngữ chưa hiểu
5. So sánh các cách giải thích
6. Viết note
7. Quay lại nguồn khi gặp khái niệm liên quan
```

**Bottleneck:**  
Bước 4–6.
Sinh viên phải tự nối:
Khái niệm A
→ liên quan B thế nào
→ B khác C ở đâu
→ khi nào dùng
→ ví dụ thực tế

**Impact:**  
Mất thời gian.
Dễ học từng thuật ngữ nhưng không hiểu quan hệ.
Notes dài nhưng khó dùng khi ôn.
Phải search lại cùng khái niệm sau này.

**Success metric:**  
Thời gian tạo study note: 45–90 phút → dưới 30–40 phút

**Non-AI alternative:**  
Sử dụng template:
Definition
Why it exists
How it works
Example
Compare with...
Limitation
và giới hạn số nguồn đọc ban đầu.

**AI hypothesis:**  
AI có thể:
đọc các source do người dùng cung cấp,
tạo concept map,
giải thích sự liên hệ,
chỉ ra điểm các nguồn không thống nhất,
tạo câu hỏi self-test.

**Quick gut:**
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết

### Draft current workflow

```text
CURRENT STATE — 45-90 phút

[Search topic]
→ [Mở nhiều nguồn]
→ [Đọc source #1]
→ [Đọc source #2]
→ [Đọc source #3]
→ [Tra thuật ngữ phụ]  <-- bottleneck
→ [Tự nối các concept]
→ [Viết note]
```

### Draft future workflow

```text
FUTURE STATE — 25-40 phút

[Chọn 2–4 source đáng tin]
→ [AI extract concepts + citation]
→ [AI tạo concept map]
→ [Student đọc source quan trọng]  <-- human boundary
→ [AI tạo comparison + examples]
→ [Student tự giải thích lại]
→ [Quiz tự kiểm]

Fallback: Các nguồn mâu thuẫn → không để AI tự kết luận → mở source gốc và kiểm tra thủ công.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

## Card muốn pitch nhất

**Card tôi muốn pitch nhất:**

```text
Problem Card #1: Hiểu đúng yêu cầu GitHub Lab và không bỏ sót deliverable.
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Problem này gần với trải nghiệm thực tế của sinh viên và dễ kiểm chứng ngay trong lớp.
Nó cũng không bắt đầu bằng:
"Xây AI Agent đọc GitHub"
mà bắt đầu bằng pain cụ thể:
Sinh viên mất thời gian chuyển tài liệu hướng dẫn
thành một checklist hành động chính xác.
Điểm quan trọng cần kiểm chứng là liệu AI thực sự cần thiết hay một checklist/rule-based tool đã đủ.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
Pain thật nằm ở việc tài liệu khó hiểu, hay chỉ vì cấu trúc tài liệu chưa tốt? Nếu README được chuẩn hóa và có submission checklist, AI còn tạo ra đủ giá trị để đáng sử dụng không?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra:
- Tôi sửa gì:

## Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
