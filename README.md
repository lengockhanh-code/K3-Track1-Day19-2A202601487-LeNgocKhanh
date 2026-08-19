Track 1 — Day 18: Multiple Prototypes — Human–AI Design

1. Thông tin nhóm

Case: Case A — AI Tutor: Diagnostic Refresher

Target user: Learner / Học viên

Thành viên 1: Lê Ngọc Khánh — 2A202601487

Thành viên 2: Trần Tuấn Anh — 2A202601086

Lưu ý: Phần Chặng 6–7 bên dưới là SIMULATED / DEMO DATA để luyện trình bày và hoàn thiện cấu trúc bài. Không dùng như evidence test thật nếu chưa có tester thực tế tương ứng.

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

Trade-off

Ưu: User control cao, nhanh, ít AI inference.

Nhược: Nếu learner chưa biết mình đang thiếu gì thì có thể chọn sai concept.

2.3 Option B — AI Suggests, User Confirms

Mechanism

AI gợi ý 2–3 candidate knowledge gaps, sau đó learner xác nhận hoặc reject.

User làm gì?

Bấm “Tôi vẫn chưa hiểu”.

Xem suggestion và evidence.

Chọn một gap hoặc chọn “Không phải”.

Nhận refresher.

Quay lại lesson.

AI làm gì?

Phân tích lesson context.

Gợi ý candidate gaps.

Hiển thị lý do.

Không tự quyết định thay learner.

Trade-off

Ưu: Giảm cognitive load, giúp learner có điểm bắt đầu nhanh hơn, user vẫn giữ quyền xác nhận.

Nhược: AI có thể suggest sai, suggestion có thể gây anchoring.

2.4 Option C — Diagnostic Mini-Quiz

Mechanism

AI hỏi 2–3 câu ngắn rồi đưa ra diagnosis tạm thời.

User làm gì?

Bấm “Tôi vẫn chưa hiểu”.

Trả lời diagnostic questions.

Review diagnosis.

Chấp nhận hoặc thay đổi.

Nhận refresher.

Quay lại lesson.

AI làm gì?

Tạo diagnostic questions.

Dùng câu trả lời làm evidence.

Đề xuất likely knowledge gap.

Tạo refresher.

Trade-off

Ưu: Có thêm evidence trước khi diagnosis, phù hợp khi learner chưa biết mình đang thiếu gì.

Nhược: Nhiều friction hơn, tốn thời gian hơn.

2.5 Distance Check

A khác B: A không inference knowledge state; B có AI suggestion.

B khác C: B dùng signal sẵn có; C thu thêm evidence bằng diagnostic questions.

A khác C: A user-led; C AI-led diagnostic.

Chặng 3 — Human–AI Design Pass

3.1 Human–AI Decision Table

Human–AI Decision

Option A

Option B

Option C

User làm gì?

Tự chọn gap

Review suggestion

Trả lời diagnostic

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

Quan hệ prerequisite

Lý do AI gợi ý

Answers dẫn tới diagnosis

Uncertainty

Gần như không cần inference

“Có thể / có khả năng”

“Diagnosis tạm thời”

Recovery

Chọn lại / Back

Reject / tự chọn

Đổi diagnosis / bỏ quiz

3.2 Evidence, Uncertainty, Recovery

Evidence: căn cứ AI dùng để đưa ra suggestion/diagnosis.

Uncertainty: AI thể hiện khi chưa chắc chắn, ví dụ “Có thể bạn đang vướng ở percentile”.

Recovery: người dùng có thể reject, chọn lại, bỏ diagnosis hoặc quay lại bài.

Chặng 4 — Build ba Micro-prototype

4.1 File Prototype

Prototype_ABC.html

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

AI hỏi 3 diagnostic questions.

AI đưa diagnosis tạm thời.

Hiển thị evidence, uncertainty và recovery.

Critical interaction: AI hỏi → AI diagnosis → User review.

Chặng 5 — Chuẩn bị Test

5.1 Relevant Context Question

“Gần đây bạn có từng học một khái niệm kỹ thuật mà bạn hiểu một phần nhưng vẫn bị mắc ở một khái niệm nền hoặc cách giải thích nào đó không?”

5.2 Outcome Task

“Bạn đang học phần P50, P95 và P99 latency nhưng chưa hiểu vì sao P95 cần thiết khi đã có average latency. Hãy sử dụng từng phương án để tìm ra phần bạn cần làm rõ và quay lại bài học khi bạn cảm thấy đã đủ hiểu để tiếp tục.”

5.3 Test Order

Tester

Thứ tự

Tester 1

A → B → C

Tester 2

B → C → A

Tester 3

C → A → B

Chặng 6 — Test A/B/C

SIMULATED / DEMO DATA

Tester 1 — P01

Relevant context: Có trải nghiệm học nội dung kỹ thuật và từng phải tìm thêm nguồn khi không hiểu một phần bài.

Order: A → B → C

TC01 — Option A

First action: Đọc toàn bộ danh sách concept trước khi chọn.

Hesitation / misunderstanding: Do dự giữa “Percentile” và “P95 được diễn giải thế nào?” vì hai lựa chọn khá gần nhau.

Evidence read / ignored: Không có AI suggestion nên tester phải tự dựa vào hiểu biết của mình.

Control / recovery: Hiểu rằng có thể chọn lại concept nếu lựa chọn đầu tiên chưa đúng.

Quote:

“Nếu mình chưa biết chính xác mình thiếu cái gì thì chọn ở đây cũng hơi khó.”

TC02 — Option B

First action: Đọc suggestion đầu tiên và phần “Vì sao AI gợi ý?”.

Hesitation / misunderstanding: Hỏi sự khác nhau giữa Option B và Option C.

Evidence read / ignored: Có đọc evidence trước khi xác nhận.

Control / recovery: Nhận ra có thể reject suggestion và tự chọn concept khác.

Quote:

“Option B là AI đoán từ context trước đúng không? Còn Option C là hỏi mình rồi mới chẩn đoán?”

TC03 — Option C

First action: Làm đủ 3 diagnostic questions.

Hesitation / misunderstanding: Đặt câu hỏi về độ tin cậy nếu người dùng trả lời bừa nhưng tình cờ đúng.

Evidence read / ignored: Có đọc phần evidence giải thích diagnosis.

Control / recovery: Hiểu rằng có thể reject diagnosis hoặc tự chọn concept khác.

Quote:

“Nếu mình trả lời bừa mà lại đúng thì AI có tưởng là mình hiểu không? Lúc đó chẩn đoán có còn chuẩn không?”

Compare

Option chọn: C

Vì sao: Tester thích việc AI hỏi thêm câu diagnostic thay vì chỉ suy đoán từ context. Tester cho rằng nếu câu hỏi được thiết kế tốt và có nhiều signal hơn một câu đúng/sai đơn lẻ thì diagnosis có khả năng sát knowledge gap hơn.

Trade-off chính: Option C tốn thời gian hơn nhưng tester chấp nhận thêm vài bước để đổi lấy cảm giác diagnosis có căn cứ hơn.

Tester 2 — P02

Relevant context: Thường học lập trình qua slide và video; khi bị mắc thường biết tương đối chủ đề mình chưa hiểu nhưng không chắc nên bắt đầu ôn từ đâu.

Order: B → C → A

TC04 — Option B

First action: Đọc cả 3 suggestion rồi quay lại đọc lý do của suggestion “Percentile”.

Hesitation / misunderstanding: Ban đầu chưa rõ AI đang dựa vào dữ liệu nào để gợi ý.

Evidence read / ignored: Đọc phần “Vì sao AI gợi ý?” trước khi xác nhận.

Control / recovery: Thử nút reject và đánh giá cao khả năng tự chọn phần khác.

Quote:

“Có lý do thì mình mới biết AI đang gợi ý dựa trên cái gì.”

TC05 — Option C

First action: Làm 2 câu đầu nhanh, dừng lâu hơn ở câu thứ ba.

Hesitation / misunderstanding: Cảm thấy diagnostic flow hơi dài so với mức độ khó của câu hỏi ban đầu.

Evidence read / ignored: Có đọc diagnosis nhưng lướt nhanh phần evidence.

Control / recovery: Biết có thể đổi diagnosis nhưng không muốn phải quay lại làm lại quiz.

Quote:

“Nếu mình đã biết gần gần là vướng ở đâu thì hỏi ba câu hơi mất công.”

TC06 — Option A

First action: Chọn ngay “Average khác P95 thế nào?”.

Hesitation / misunderstanding: Không gặp breakdown lớn.

Evidence read / ignored: Không có AI suggestion.

Control / recovery: Control rõ, nhưng tester nói nếu không biết gap thì A sẽ khó.

Quote:

“Cái này nhanh, nhưng phải tự biết mình muốn hỏi cái gì.”

Compare

Option chọn: B

Vì sao: Tester muốn AI thu hẹp phạm vi trước nhưng vẫn muốn tự xác nhận. B giúp giảm số bước hơn C và giảm cognitive load hơn A.

Trade-off chính: B cân bằng tốt giữa tốc độ và quyền kiểm soát, nhưng cần hiển thị evidence rõ để tránh user tin suggestion một cách máy móc.

Tester 3 — P03

Relevant context: Từng gặp trường hợp học công thức nhưng không biết mình đang thiếu công thức, trực giác hay kiến thức nền.

Order: C → A → B

TC07 — Option C

First action: Làm diagnostic questions ngay.

Hesitation / misunderstanding: Ban đầu hiểu “diagnosis tạm thời” như một kết luận khá chắc chắn.

Evidence read / ignored: Sau khi đọc evidence thì hiểu rõ hơn vì sao AI đưa ra diagnosis.

Control / recovery: Đánh giá cao nút “Không đúng — chọn phần khác”.

Quote:

“Nếu nó nói rõ đây chỉ là chẩn đoán tạm thời thì mình thấy yên tâm hơn.”

TC08 — Option A

First action: Đọc toàn bộ danh sách concept.

Hesitation / misunderstanding: Phân vân giữa “Percentile” và “P95 được diễn giải thế nào?”.

Evidence read / ignored: Không có evidence hỗ trợ lựa chọn.

Control / recovery: Có thể chọn lại nhưng tester vẫn cảm thấy phải tự diagnosis quá nhiều.

Quote:

“Đúng lúc mình không biết mình thiếu gì thì A lại bắt mình tự biết.”

TC09 — Option B

First action: Đọc suggestion đầu tiên và xác nhận khá nhanh.

Hesitation / misunderstanding: Lo rằng suggestion đầu tiên có thể khiến mình bị dẫn dắt.

Evidence read / ignored: Có đọc lý do nhưng vẫn cho rằng AI đang định hướng user khá mạnh.

Control / recovery: Biết reject nhưng cảm thấy user có thể không dùng nút đó nếu quá tin AI.

Quote:

“Nếu AI gợi ý ngay từ đầu thì có thể mình sẽ bị kéo theo nó.”

Compare

Option chọn: C

Vì sao: Tester thích việc AI thu thêm evidence trước khi đưa ra diagnosis, đặc biệt trong trường hợp bản thân chưa biết đang thiếu kiến thức nào.

Trade-off chính: C chậm hơn nhưng giảm cảm giác AI đoán mò từ context. Tester yêu cầu diagnosis phải thể hiện uncertainty rõ và cho phép reject dễ dàng.

Chặng 7 — Group Feedback Synthesis

SIMULATED / DEMO DATA

7.1 Tổng hợp Feedback

Nội dung

Tester 1

Tester 2

Tester 3

Pattern / Khác biệt

First action

A: đọc concept; B: đọc evidence; C: làm quiz

B: đọc suggestion; C: làm quiz; A: chọn gap

C: làm quiz; A: đọc concept; B: đọc suggestion

Hành vi thay đổi theo mechanism của từng option

Breakdown chính

Lo C sai nếu user đoán đúng

C hơi dài; A cần tự biết gap

A khó khi chưa biết gap; B có nguy cơ anchoring

A khó cho learner chưa rõ gap; B nhanh nhưng có anchoring; C cần kiểm soát reliability

Evidence read / ignored

Đọc evidence ở B/C

Đọc kỹ evidence ở B, lướt ở C

Evidence giúp hiểu diagnosis C

Evidence quan trọng nhất khi AI chủ động inference

Recovery

Biết reject

Muốn reject nhanh, không làm lại quiz

Đánh giá cao reject diagnosis

Recovery phải dễ thấy và ít bước

Option được chọn

C

B

C

2/3 nghiêng về C, 1/3 chọn B

Trade-off

C kỹ hơn nhưng chậm

B cân bằng tốc độ/control

C đáng tin hơn nếu evidence tốt

Không có option thắng tuyệt đối; preference phụ thuộc mức user biết gap

7.2 Observed

Tester 1 và Tester 3 chọn Option C vì muốn AI thu thêm evidence trước khi diagnosis.

Tester 2 chọn Option B vì đã tương đối biết vùng kiến thức đang vướng và không muốn làm thêm diagnostic quiz.

Option A được đánh giá là nhanh nhưng phụ thuộc mạnh vào việc learner có tự xác định được knowledge gap hay không.

Option B giảm friction nhưng có nguy cơ anchoring nếu user quá tin suggestion đầu tiên.

Option C có khả năng tạo cảm giác diagnosis có căn cứ hơn, nhưng đặt ra vấn đề reliability nếu answer không phản ánh actual understanding.

7.3 Interpreted

Kết quả cho thấy không nên thiết kế một flow duy nhất cho mọi learner.

Có thể chia thành hai tình huống:

Learner tương đối biết mình đang vướng ở đâu:
Option B phù hợp hơn vì AI chỉ cần thu hẹp candidate gaps và để user xác nhận.

Learner không biết mình đang thiếu kiến thức nào:
Option C phù hợp hơn vì AI cần thu thêm evidence trước khi đưa ra diagnosis.

Option A phù hợp nhất khi learner đã biết rõ concept cần làm rõ, nhưng giá trị diagnosis thấp nhất.

7.4 Evidence chống lại kỳ vọng ban đầu

Kỳ vọng ban đầu:

Có thêm diagnostic questions thì diagnosis sẽ đáng tin hơn.

Feedback từ Tester 1 cho thấy assumption này chưa chắc đúng:

Nếu learner đoán, copy hoặc tình cờ chọn đúng, correct answer chưa chắc phản ánh actual understanding.

Feedback từ Tester 2 cũng cho thấy:

Nhiều evidence hơn có thể không đáng giá nếu chi phí tương tác quá cao so với nhu cầu của learner.

7.5 One Next Change

Next Change: Thiết kế flow thích ứng hai tầng: mặc định dùng Option B — AI Suggests, User Confirms, nhưng bổ sung nút “Tôi vẫn không biết mình vướng ở đâu” để chuyển sang Option C — Diagnostic Mini-Quiz khi learner cần diagnosis sâu hơn.

7.6 Evidence dẫn tới Next Change

Tester 2 chọn B vì tốc độ và user control.

Tester 1 và Tester 3 chọn C vì muốn diagnosis có thêm evidence.

A hữu ích khi learner đã biết rõ gap nhưng không xử lý tốt trường hợp problem hypothesis chính.

Vì vậy, thay vì chọn B hoặc C tuyệt đối, nhóm kết hợp B làm flow mặc định và C làm escalation flow.

7.7 Still Unproven

Nhóm vẫn chưa chứng minh rằng:

Diagnostic questions thực sự xác định đúng actual knowledge gap.

Flow B → C giúp learner tiết kiệm thời gian hơn so với tự tìm Google/ChatGPT.

Learner có sử dụng nút chuyển sang diagnostic khi thực sự cần.

AI explanation sau diagnosis giúp tăng learning outcome.

Kết quả từ số lượng tester nhỏ có thể đại diện cho toàn bộ learner population.

AI Support Log

Lê Ngọc Khánh

AI đã giúp tôi ở đâu?

Gợi ý cách chuyển Hypothesis Problem thành 3 solution mechanisms.

Kiểm tra A/B/C có khác nhau thực sự về Human–AI role.

Gợi ý evidence, uncertainty và recovery.

Gợi ý prototype flow.

AI sai / hơi hợt ở đâu?

Một số gợi ý ban đầu dễ làm cả ba option giống nhau và chỉ khác giao diện.

AI có xu hướng coi diagnosis nhiều hơn là tốt hơn.

Tôi đã tự sửa / quyết định lại điều gì?

Giữ A là user-led.

Giữ B là AI suggestion + user confirmation.

Giữ C là diagnostic.

Tách B thành flow mặc định và C thành escalation sau khi xem feedback.

Trần Tuấn Anh

AI đã giúp tôi ở đâu?

Phân biệt diagnosis problem với explanation problem.

Gợi ý trade-off của từng option.

Gợi ý cách thể hiện evidence, uncertainty và recovery.

AI sai / hơi hợt ở đâu?

Ban đầu các option còn quá gần nhau về mục tiêu cuối.

AI chưa tính đủ trường hợp learner trả lời đúng do đoán.

AI chưa nhấn mạnh đủ anchoring risk của Option B.

Tôi đã tự sửa / quyết định lại điều gì?

Làm rõ sự khác nhau giữa B và C ở nguồn evidence.

Giữ user confirmation ở B.

Giữ uncertainty và recovery ở C.

Đề xuất flow B → C thay vì chọn một option duy nhất.

Deliverables cuối Day 18

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

Day18/
├── README.md
└── Prototype_ABC.html

Learning Goal

Khi learner bị mắc nhưng chưa chắc mình thiếu gì, mức chủ động nào của AI tạo ra sự cân bằng tốt nhất giữa tốc độ hỗ trợ, độ tin cậy và quyền kiểm soát của learner?