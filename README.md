Track 1 — Day 19: Multiple Prototypes — Human–AI Design

1. Thông tin nhóm

Case: Case A — AI Tutor: Diagnostic Refresher

Target user: Learner / Học viên

Thành viên 1: Lê Ngọc Khánh — 2A202601487

Thành viên 2: Trần Tuấn Anh — 2A202601086

Lưu ý: File đã được chuyển sang Day 19 theo yêu cầu.
Phần Chặng 6–7 bên dưới đang sử dụng dữ liệu demo/simulated để hoàn thiện cấu trúc bài; không nên trình bày như evidence test thật nếu chưa có tester thực tế tương ứng.

Chặng 1 — Tổng hợp Evidence

1.1 Evidence từ Day 17

Practice Note 1 — P95 Latency

Situation: Đang học Day 13 — Monitoring, Logging & Observability.

Vấn đề: Không hiểu vì sao P95 quan trọng và vì sao average latency chưa đủ.

Hành vi thực tế: Đọc lại slide → Google → ChatGPT → quay lại bài.

Knowledge gap thực tế: Ban đầu tưởng không hiểu monitoring, sau mới nhận ra chưa hiểu percentile.

Consequence: Mất khoảng 15–20 phút và bị gián đoạn mạch học.

Exact quote:

“Lúc đầu mình tưởng mình không hiểu monitoring, nhưng thật ra mình chưa hiểu percentile.”

Practice Note 2

Bổ sung evidence thật từ interview của thành viên còn lại.

Practice Note 3

Nếu coach yêu cầu đủ 3 Practice Notes, nhóm bổ sung evidence thật hoặc sử dụng Evidence Pack nếu được cho phép.

1.2 Evidence Huddle

Practice Note

User đã thực sự làm / nói gì?

Điều nhóm đang diễn giải

1

Đọc lại slide, Google, ChatGPT; sau đó mới nhận ra thiếu kiến thức percentile

Một số learner khó tự xác định knowledge gap

2

Bổ sung từ evidence thật

Bổ sung sau

3

Bổ sung từ evidence thật nếu có

Bổ sung sau

1.3 Hypothesis Problem

Khi đang học một nội dung mới và gặp một phần chưa hiểu đủ để tiếp tục, học viên gặp khó khăn trong việc xác định nhanh kiến thức nền đang cản trở việc hiểu vì điểm thiếu không phải lúc nào cũng rõ từ nội dung hiện tại, dẫn đến phải chuyển qua nhiều nguồn/cách xử lý, mất thời gian và gián đoạn mạch học.

Evidence ban đầu hỗ trợ giả thuyết

Có tình huống thực tế.

Có workaround thực tế.

Có consequence rõ ràng.

Có trường hợp learner không biết ngay mình đang thiếu knowledge nào.

Điều vẫn chưa được chứng minh

Phần lớn learner đều khó tự diagnosis.

AI diagnosis tốt hơn learner tự chọn.

Diagnostic questioning luôn cần thiết.

Solution làm tăng learning outcome.

Một option cụ thể đã được validated.

Chặng 2 — Chọn ba Solution Options

2.1 Comparison Contract

Thành phần

Quyết định chung cho A/B/C

Target user

Learner / Học viên

Situation

Không hiểu vì sao P95 quan trọng khi đã có average latency

Task

Tìm phần cần làm rõ và quay lại bài

Current lesson

Day 13 — Monitoring, Logging & Observability

Content fixture

P50, P95, P99, average latency, percentile, tail latency

Trigger

“Tôi vẫn chưa hiểu”

Desired outcome

Hiểu đủ để tiếp tục bài

Visual components

Cùng lesson screen, card, button và typography

2.2 Option A — User-led Concept Selection

Mechanism

Learner tự chọn phần kiến thức mình muốn làm rõ.

User làm gì?

Bấm “Tôi vẫn chưa hiểu”.

Xem danh sách concept.

Chọn concept đang vướng.

Đọc refresher.

Quay lại lesson.

AI làm gì?

Không tự diagnosis learner.

Chỉ giải thích concept do learner chọn.

Evidence chính

Self-diagnosis của learner.

Concept learner chủ động chọn.

Trade-off

Ưu điểm

User control cao.

Nhanh.

Ít AI inference.

Nhược điểm

Nếu learner chưa biết mình đang thiếu gì thì có thể chọn sai concept.

2.3 Option B — AI Suggests, User Confirms

Mechanism

AI sử dụng context đã có để gợi ý 2–3 candidate knowledge gaps, sau đó learner xác nhận hoặc reject.

Context AI có thể dùng

Bài hiện tại.

Section hiện tại.

Concept liên quan.

Câu trả lời gần đây nếu VLearn có lưu.

Lịch sử học tập nếu VLearn cung cấp.

User làm gì?

Bấm “Tôi vẫn chưa hiểu”.

Xem suggestion và phần “Vì sao AI gợi ý?”.

Chọn một gap hoặc chọn “Không phải”.

Nhận refresher.

Quay lại lesson.

AI làm gì?

Phân tích context đã có.

Gợi ý candidate gaps.

Hiển thị evidence.

Không tự quyết định thay learner.

Trade-off

Ưu điểm

Giảm cognitive load.

Giúp learner có điểm bắt đầu nhanh hơn.

User vẫn giữ quyền xác nhận.

Nhược điểm

AI có thể suggest sai.

Suggestion có thể gây anchoring nếu learner tin AI quá nhanh.

2.4 Option C — Adaptive Diagnostic

Mechanism

AI sử dụng context ban đầu để hình thành hypothesis về knowledge gap, sau đó hỏi một số câu diagnostic ngắn để xác minh trước khi đưa diagnosis tạm thời.

AI có thể dựa trên

Trước diagnostic

Bài hiện tại.

Câu trả lời gần đây.

Lịch sử học tập.

Hoạt động học gần đây nếu VLearn có lưu, ví dụ: xem lại nội dung, đổi đáp án, đánh dấu “Chưa hiểu”, hỏi AI về cùng một concept.

Trong diagnostic

Correctness: đáp án đúng/sai.

Reasoning: vì sao learner chọn đáp án đó.

Confidence: learner chắc chắn hay đang đoán.

Self-report: learner tự đánh dấu phần mình chưa chắc.

Consistency: các câu trả lời có nhất quán không.

User làm gì?

Bấm “Tôi vẫn chưa hiểu”.

Trả lời 1–3 diagnostic questions.

Giải thích ngắn: “Vì sao bạn chọn đáp án này?”

Chọn mức độ tự tin.

Tự đánh dấu phần mình chưa chắc.

Review diagnosis.

Chấp nhận, reject hoặc chọn lại.

Nhận refresher và quay lại lesson.

AI làm gì?

Chọn câu hỏi dựa trên knowledge gap đang nghi ngờ.

Không coi một đáp án đúng là bằng chứng đủ.

Kết hợp correctness + reasoning + confidence + self-report.

Đưa diagnosis tạm thời cùng evidence và uncertainty.

Cho phép learner reject hoặc sửa diagnosis.

Xử lý trường hợp “đoán đúng nhưng không hiểu”

Nếu learner:

chọn đúng đáp án;

nhưng nói “Em đoán”;

hoặc không giải thích được vì sao đáp án đúng;

thì AI không kết luận learner đã hiểu.

Ví dụ:

Correctness: đúng
Reasoning: chưa thể hiện hiểu biết
Confidence: thấp
→ Diagnosis: hiểu chưa ổn định
→ Reliability: thấp–trung bình

Trade-off

Ưu điểm

Có nhiều evidence hơn trước khi diagnosis.

Phù hợp khi learner thật sự không biết mình thiếu gì.

Giảm nguy cơ coi “trả lời đúng” là “hiểu thật”.

Nhược điểm

Tốn thời gian hơn B.

Nếu hỏi quá nhiều sẽ tạo friction.

Chất lượng diagnosis vẫn phụ thuộc chất lượng câu hỏi và signal đầu vào.

2.5 Distance Check

So sánh

Khác biệt chính

A vs B

A để learner tự xác định gap; B để AI gợi ý từ context rồi learner xác nhận

B vs C

B dùng evidence đã có để suggest; C thu thêm evidence mới bằng diagnostic questions

A vs C

A gần như không inference; C chủ động diagnosis nhưng vẫn cần user review

Chặng 3 — Human–AI Design Pass

3.1 Human–AI Decision Table

Human–AI Decision

Option A

Option B

Option C

User làm gì?

Tự chọn gap

Review suggestion

Trả lời diagnostic + reasoning + confidence

AI làm gì?

Giải thích

Suggest + giải thích

Diagnose + giải thích

AI Act / Ask / Don’t Act

Don’t Act về diagnosis

Ask / Recommend

Ask rồi Act

Capability / Limit

Không xác định gap thay user

Suggestion có thể sai

Diagnosis chỉ là tạm thời

Evidence

Concept user chọn

Context + lý do AI gợi ý

Correctness + reasoning + confidence + self-report

Uncertainty

Gần như không cần inference

“Có thể / có khả năng”

Reliability + diagnosis tạm thời

Recovery

Chọn lại / Back

Reject / tự chọn

Reject / làm lại / tự chọn / bỏ diagnosis

3.2 Evidence, Uncertainty, Recovery

Evidence

Căn cứ AI dùng để đưa ra suggestion hoặc diagnosis.

Uncertainty

AI không nên nói:

“Bạn chắc chắn không hiểu percentile.”

Nên nói:

“Có thể bạn đang vướng ở percentile.”

hoặc:

“Diagnosis tạm thời: Percentile — cần bạn xác nhận.”

Recovery

Người dùng luôn có thể:

Không đúng — chọn phần khác

Tôi muốn tự chọn

Làm lại diagnostic

Bỏ diagnosis

Quay lại bài

Chặng 4 — Build ba Micro-prototype

4.1 File Prototype

Prototype_ABC.html

Khi nộp, nên đổi tên file prototype tối ưu cuối cùng thành Prototype_ABC.html.

4.2 Common Context

Lesson: Day 13 — Monitoring, Logging & Observability

Section: Latency Percentiles

Question: Tại sao hệ thống cần theo dõi P95 thay vì chỉ dùng average latency?

Trigger: Tôi vẫn chưa hiểu

4.3 Prototype A

Learner tự chọn concept.

AI chỉ giải thích concept được chọn.

Critical interaction: Learner tự xác định knowledge gap.

4.4 Prototype B

AI đưa ra 3 suggestions.

Mỗi suggestion có phần “Vì sao AI gợi ý?”.

User xác nhận hoặc reject.

Critical interaction: AI suggest → User confirm.

4.5 Prototype C

AI hỏi diagnostic questions.

Mỗi câu có phần “Vì sao bạn chọn đáp án này?”.

Learner chọn mức độ tự tin.

Learner tự đánh dấu phần chưa chắc.

AI đưa diagnosis tạm thời.

AI hiển thị:

correctness;

reasoning;

confidence;

self-report;

reliability;

uncertainty;

recovery.

Critical interaction:

AI hỏi → thu evidence → diagnosis tạm thời → user review.

Chặng 5 — Chuẩn bị Test

5.1 Relevant Context Question

“Gần đây bạn có từng học một khái niệm kỹ thuật mà bạn hiểu một phần nhưng vẫn bị mắc ở một khái niệm nền hoặc cách giải thích nào đó không?”

5.2 Outcome Task

“Bạn đang học phần P50, P95 và P99 latency nhưng chưa hiểu vì sao P95 cần thiết khi đã có average latency. Hãy sử dụng từng phương án để tìm ra phần bạn cần làm rõ và quay lại bài học khi bạn cảm thấy đã đủ hiểu để tiếp tục.”

5.3 Observation Focus

Trong mỗi lượt test, ghi lại:

First action

Hesitation / misunderstanding

Evidence read / ignored

Control / recovery

Option chosen + trade-off

5.4 Test Order

Tester

Thứ tự

Tester 1

A → B → C

Tester 2

B → C → A

Tester 3

C → A → B

Tổng: 3 tester × 3 options = 9 lượt trải nghiệm prototype.

Chặng 6 — Test A/B/C

Dữ liệu bên dưới là demo/simulated theo file hiện tại.

Tester 1 — P01

Relevant context: Có trải nghiệm học nội dung kỹ thuật và từng phải tìm thêm nguồn khi không hiểu một phần bài.

Order: A → B → C

TC01 — Option A

First action: Đọc toàn bộ danh sách concept trước khi chọn.

Hesitation / misunderstanding: Do dự giữa “Percentile” và “P95 được diễn giải thế nào?”.

Evidence read / ignored: Không có AI suggestion nên tester phải tự dựa vào hiểu biết của mình.

Control / recovery: Hiểu rằng có thể chọn lại concept.

Quote:

“Nếu mình chưa biết chính xác mình thiếu cái gì thì chọn ở đây cũng hơi khó.”

TC02 — Option B

First action: Đọc suggestion đầu tiên và phần “Vì sao AI gợi ý?”.

Hesitation / misunderstanding: Hỏi sự khác nhau giữa B và C.

Evidence read / ignored: Có đọc evidence trước khi xác nhận.

Control / recovery: Nhận ra có thể reject suggestion.

Quote:

“Option B là AI đoán từ context trước đúng không? Còn Option C là hỏi mình rồi mới chẩn đoán?”

TC03 — Option C

First action: Làm diagnostic questions.

Hesitation / misunderstanding: Đặt câu hỏi về trường hợp người dùng trả lời bừa nhưng tình cờ đúng.

Evidence read / ignored: Có đọc evidence giải thích diagnosis.

Control / recovery: Hiểu rằng có thể reject diagnosis hoặc tự chọn lại.

Quote:

“Nếu mình trả lời bừa mà lại đúng thì AI có tưởng là mình hiểu không? Lúc đó chẩn đoán có còn chuẩn không?”

Compare

Option chọn: C

Vì sao: Muốn AI thu thêm evidence trước khi diagnosis.

Trade-off chính: C chậm hơn nhưng tạo cảm giác diagnosis có căn cứ hơn.

Tester 2 — P02

Relevant context: Thường học lập trình qua slide và video; khi bị mắc thường biết tương đối vùng kiến thức nhưng không chắc nên bắt đầu ôn từ đâu.

Order: B → C → A

TC04 — Option B

First action: Đọc cả 3 suggestion rồi xem lý do của suggestion “Percentile”.

Hesitation / misunderstanding: Ban đầu chưa rõ AI dựa vào dữ liệu nào để gợi ý.

Evidence read / ignored: Đọc “Vì sao AI gợi ý?”.

Control / recovery: Thử reject và đánh giá cao khả năng tự chọn.

Quote:

“Có lý do thì mình mới biết AI đang gợi ý dựa trên cái gì.”

TC05 — Option C

First action: Làm diagnostic.

Hesitation / misunderstanding: Cảm thấy flow hơi dài nếu đã biết gần đúng vùng đang vướng.

Evidence read / ignored: Có đọc diagnosis nhưng lướt nhanh evidence.

Control / recovery: Biết có thể đổi diagnosis.

Quote:

“Nếu mình đã biết gần gần là vướng ở đâu thì hỏi nhiều bước hơi mất công.”

TC06 — Option A

First action: Chọn ngay “Average khác P95 thế nào?”.

Hesitation / misunderstanding: Không gặp breakdown lớn.

Control / recovery: Control rõ.

Quote:

“Cái này nhanh, nhưng phải tự biết mình muốn hỏi cái gì.”

Compare

Option chọn: B

Vì sao: Muốn AI thu hẹp phạm vi trước nhưng vẫn muốn tự xác nhận.

Trade-off chính: B cân bằng tốc độ và quyền kiểm soát.

Tester 3 — P03

Relevant context: Từng gặp trường hợp học công thức nhưng không biết mình đang thiếu công thức, trực giác hay kiến thức nền.

Order: C → A → B

TC07 — Option C

First action: Làm diagnostic ngay.

Hesitation / misunderstanding: Ban đầu hiểu “diagnosis tạm thời” như một kết luận khá chắc chắn.

Evidence read / ignored: Sau khi đọc evidence thì hiểu rõ hơn.

Control / recovery: Đánh giá cao nút “Không đúng — chọn phần khác”.

Quote:

“Nếu nó nói rõ đây chỉ là chẩn đoán tạm thời thì mình thấy yên tâm hơn.”

TC08 — Option A

First action: Đọc toàn bộ danh sách concept.

Hesitation / misunderstanding: Phân vân giữa “Percentile” và “P95 được diễn giải thế nào?”.

Control / recovery: Có thể chọn lại nhưng vẫn phải tự diagnosis khá nhiều.

Quote:

“Đúng lúc mình không biết mình thiếu gì thì A lại bắt mình tự biết.”

TC09 — Option B

First action: Đọc suggestion đầu tiên và xác nhận khá nhanh.

Hesitation / misunderstanding: Lo suggestion đầu tiên khiến learner bị dẫn dắt.

Evidence read / ignored: Có đọc lý do.

Control / recovery: Biết reject.

Quote:

“Nếu AI gợi ý ngay từ đầu thì có thể mình sẽ bị kéo theo nó.”

Compare

Option chọn: C

Vì sao: Muốn AI thu thêm evidence trước khi diagnosis.

Trade-off chính: C chậm hơn nhưng giảm cảm giác AI đoán mò từ context.

Chặng 7 — Group Feedback Synthesis

7.1 Tổng hợp Feedback

Nội dung

Tester 1

Tester 2

Tester 3

Pattern / Khác biệt

Breakdown chính

Lo C sai nếu user đoán đúng

C hơi dài

B có nguy cơ anchoring

C cần kiểm soát reliability; B cần evidence rõ

Evidence

Đọc B/C

Đọc kỹ B, lướt C

Evidence giúp hiểu C

Evidence quan trọng khi AI inference

Recovery

Biết reject

Muốn reject nhanh

Đánh giá cao reject diagnosis

Recovery phải dễ thấy

Option chọn

C

B

C

2/3 nghiêng về C

Trade-off

C kỹ hơn nhưng chậm

B cân bằng tốc độ/control

C đáng tin hơn nếu evidence tốt

Không có option thắng tuyệt đối

7.2 Observed

Tester 1 và Tester 3 nghiêng về C vì muốn AI thu thêm evidence.

Tester 2 nghiêng về B vì muốn flow nhanh hơn.

A nhanh nhưng phụ thuộc learner đã biết gap.

B có anchoring risk.

C có reliability risk nếu chỉ nhìn correctness.

7.3 Interpreted

Không nên dùng một flow duy nhất cho mọi learner:

Learner đã tương đối biết vùng đang vướng → B phù hợp hơn.

Learner không biết mình thiếu gì → C phù hợp hơn.

Learner biết rõ concept cần làm rõ → A nhanh nhất.

7.4 Evidence chống lại kỳ vọng ban đầu

Kỳ vọng:

Có thêm diagnostic questions thì diagnosis sẽ đáng tin hơn.

Điểm phản biện:

Correct answer chưa chắc phản ánh actual understanding nếu learner đoán, copy hoặc không giải thích được lý do.

Vì vậy Option C được cải thiện để dùng thêm reasoning + confidence + self-report.

7.5 One Next Change

Next Change: Dùng Option B làm flow mặc định, nhưng bổ sung nút “Tôi vẫn không biết mình vướng ở đâu” để chuyển sang Option C — Adaptive Diagnostic khi learner cần diagnosis sâu hơn.

7.6 Evidence dẫn tới Next Change

B nhanh và ít friction hơn.

C hữu ích khi learner thật sự không xác định được gap.

A phù hợp khi user đã biết rõ phần cần hỏi.

Kết hợp B → C cho phép hệ thống thích ứng với mức độ uncertainty của learner.

7.7 Still Unproven

Nhóm vẫn chưa chứng minh:

Diagnostic questions thực sự xác định đúng actual knowledge gap.

Flow B → C tiết kiệm thời gian hơn workaround hiện tại.

Learner sẽ sử dụng escalation sang C đúng lúc.

AI explanation sau diagnosis giúp tăng learning outcome.

Kết quả từ số lượng tester nhỏ đại diện cho toàn bộ learner population.

AI Support Log

Lê Ngọc Khánh

AI đã giúp tôi ở đâu?

Gợi ý cách chuyển Hypothesis Problem thành 3 solution mechanisms.

Kiểm tra A/B/C có khác nhau thực sự về Human–AI role.

Gợi ý evidence, uncertainty và recovery.

Gợi ý prototype flow.

AI sai / hơi hợt ở đâu?

Một số gợi ý ban đầu dễ làm cả ba option giống nhau.

AI có xu hướng coi diagnosis nhiều hơn là tốt hơn.

Tôi đã tự sửa / quyết định lại điều gì?

Giữ A là user-led.

Giữ B là AI suggestion + user confirmation.

Tối ưu C bằng reasoning + confidence + self-report.

Đề xuất B → C thay vì chọn một flow duy nhất.

Trần Tuấn Anh

AI đã giúp tôi ở đâu?

Phân biệt diagnosis problem với explanation problem.

Gợi ý trade-off của từng option.

Gợi ý cách thể hiện evidence, uncertainty và recovery.

AI sai / hơi hợt ở đâu?

Ban đầu B và C chưa khác nhau đủ rõ về nguồn evidence.

Chưa tính đủ trường hợp learner trả lời đúng do đoán.

Chưa nhấn mạnh đủ anchoring risk của B.

Tôi đã tự sửa / quyết định lại điều gì?

Làm rõ B dùng context đã có để suggest.

C thu thêm evidence mới để diagnosis.

Giữ user confirmation và recovery ở cả B/C.

Thêm reasoning check cho C.

Deliverables cuối Day 19

Hypothesis Problem

Evidence Snapshot

Comparison Contract

Option A

Option B

Option C

Distance Check

Human–AI Decision Table

Micro-prototype A/B/C

Test plan

9 lượt test dạng demo/simulated

Group Feedback Synthesis dạng demo/simulated

One Next Change

Still Unproven

AI Support Log

Cấu trúc thư mục

Day19/
├── README.md
└── Prototype_ABC.html

Tóm tắt ba Options

COMMON PROBLEM
Learner chưa hiểu P95 và cần tiếp tục bài
        │
        ├── OPTION A — USER-LED
        │   User tự chọn knowledge gap
        │   ↓
        │   AI giải thích
        │
        ├── OPTION B — CO-CREATE
        │   AI dùng context đã có
        │   ↓
        │   AI suggest knowledge gap
        │   ↓
        │   User confirm
        │
        └── OPTION C — ADAPTIVE DIAGNOSTIC
            AI dùng context để chọn câu hỏi
            ↓
            Diagnostic answers
            + Reasoning
            + Confidence
            + Self-report
            ↓
            AI diagnosis tạm thời
            ↓
            User review

Learning Goal

Khi learner bị mắc nhưng chưa chắc mình thiếu gì, mức chủ động nào của AI tạo ra sự cân bằng tốt nhất giữa tốc độ hỗ trợ, độ tin cậy và quyền kiểm soát của learner?