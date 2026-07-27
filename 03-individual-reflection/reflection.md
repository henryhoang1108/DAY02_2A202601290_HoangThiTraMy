## Đóng góp trong nhóm

| Hoạt động | Tôi đã làm gì? | Kết quả |
|---|---|---|
| Scan cá nhân | Đưa ra 10 problems thuộc nhiều bối cảnh như học tập, đời sống, y tế, môi trường và cộng đồng | Nhóm có thêm nhiều candidate đa dạng để đưa vào vòng gom cluster và shortlist |
| Pitch Problem Card |Trình bày 2 problem: Tóm tắt nội dung buổi họp và Lên thực đơn theo mục tiêu |Các problem được nhóm xem xét trong bước convergence và scoring |
| Challenge bài của bạn khác | Đặt câu hỏi: Liệu đó có phải là pain-point thực sự không? Có cần thiết phải thêm tính năng đó không?| Phản biện để tránh chọn đề tài không đúng |
| Gom trùng / cluster | Cùng nhóm phân loại candidate thành các nhóm như  học tập, FAQ, planning cá nhânm technical automation | Danh sách candidate rõ ràng hơn và dễ so sánh hơn |
| Chọn candidate problem | Tham gia đánh giá các candidate theo actor, workflow, evidence, impact, khả năng làm trong lab và khả năng so sánh Rule / Workflow / Agent | Nhóm chọn được idea cải thiện tình trạng thông tin học tập bị phân mảnh|
| Validation / research | Tìm hiểu giải pháp hiện tại của Google Classroom |  |
| Workflow nhóm | Hỗ trợ rà soát current workflow và future workflow của bài toán | Workflow cuối thể hiện được bottleneck, human boundary và fallback |
| Problem Statement | | Problem Statement v0/v1 cụ thể hơn và không coi AI là giải pháp mặc định |
| Rule / Workflow / Agent | Workflow giữ được boundary rõ: AI chỉ tổng hợp trong nguồn được phép, học viên kiểm tra link gốc, giảng viên/trợ giảng vẫn là owner của tài liệu và deadline. | Nhóm thống nhất chọn Workflow |
| Decision | | Decision có scope, metric và rollback rõ ràng |


---
## Bảng dùng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm các problem trong học tập, đời sống và cộng đồng | Giúp mở rộng góc nhìn và tránh chỉ tập trung vào một nhóm problem | Một số gợi ý quá rộng, khó có actor hoặc workflow cụ thể | Chỉ giữ các problem có thể mô tả actor, bottleneck và dấu hiệu thật |
| Problem Card | Phản biện Problem Card dưới vai trò là 1 PM | Giúp bảo đảm không thiếu Actor, Workflow, Bottleneck, Impact, Metric và Non-AI alternative, xác định đúng scope | Một số metric được đề xuất quá cụ thể dù chưa có baseline thật | Đổi các con số thành mục tiêu giả định và bổ sung kế hoạch validation |
| Workflow | Nhờ AI chuyển mô tả dài thành workflow ASCII dễ đọc | Giúp nhìn rõ các bước, bottleneck, human boundary và fallback | AI đôi lúc gộp các bước hoặc đặt AI vào quá nhiều vị trí | Tách lại các bước |
| Shortlist và score | Nhờ AI tạo bảng chấm điểm theo rubric | Giúp nhóm so sánh candidate theo cùng một bộ tiêu chí | Điểm số ban đầu còn mang tính chủ quan | Xem điểm chỉ là công cụ thảo luận, không thay quyết định của nhóm |
| Research | Nhờ AI gợi ý các tool và pattern tương tự | Giúp tìm ra hybrid search, talent rediscovery và AI-assisted search | Có nguy cơ đưa claim hoặc số liệu không có nguồn xác minh | Chỉ giữ các hướng có nguồn chính thức và không dùng số liệu chưa kiểm chứng |
| Rule / Workflow / Agent | Nhờ AI so sánh ba mức giải pháp | Giúp chỉ ra Rule/index giải quyết phần nền là nguồn chính thức và metadata. AI hữu ích ở bước tìm kiếm bằng ngôn ngữ tự nhiên, tóm tắt nhiều nguồn và gợi ý link liên quan. | AI ban đầu có thể đẩy scope sang Agent tự động liên hệ ứng viên | Hạ về Workflow |
| Final decision | Nhờ AI gợi ý pilot và rollback | Giúp tạo scope nhỏ, metric và điều kiện dừng | Một số mục tiêu ban đầu chưa chắc thực tế | Ghi rõ đây là mục tiêu thử nghiệm và cần baseline trước khi Go đầy đủ |

## Bài học của tôi

- Một problem tốt không nhất thiết phải dùng AI phức tạp, mà cần có Actor, Workflow, Bottleneck và Impact rõ ràng, đo lường được.
- Chấm điểm candidate chỉ giúp nhóm có cơ sở thảo luận; điểm cao không thể thay thế cho evidence thực tế từ việc phỏng vấn hay quan sát người dùng.
- Vẽ Current Workflow trước là bước bắt buộc để nhìn thấy điểm nghẽn (bottleneck) nằm ở đâu, tránh đưa AI vào một cách tràn lan toàn bộ quy trình.
- Process fix, chuẩn hóa quy tắc (Rule) và trang index thông tin không phải giải pháp "kém hơn AI", mà là nền tảng bắt buộc phải làm trước khi áp dụng AI.
- Agent không phải đích đến mặc định. Với các workflow có quy trình rõ ràng, mức độ Workflow phù hợp hơn vì giữ được sự kiểm soát, không cần nhảy ngay sang Agent phức tạp đầy rủi ro.
- Human boundary (Ranh giới kiểm soát bởi con người) là bắt buộc: AI chỉ đóng vai trò hỗ trợ Q&A/tóm tắt trong phạm vi dữ liệu được phép, người thật (học viên, trợ giảng) vẫn là bên xác nhận cuối cùng.
- Research giải pháp có sẵn không phải để sao chép tool, mà để nhận ra các pattern thành công, điểm mù và rủi ro cần tránh.
- Các con số thành công (như giảm thời gian từ 25–40 phút xuống 10–15 phút hay giảm 30% câu hỏi lặp) chỉ mang tính kỳ vọng/giả định, bắt buộc phải có baseline đo lường thực tế trong đợt pilot để kiểm chứng.
---

## Điều khó nhất khi làm bài
Điều khó nhất là phân biệt giữa triệu chứng bề ngoài và nguyên nhân gốc rễ (root cause). Ban đầu, pain point dễ bị coi là chung chung như "học viên thiếu thông tin" hay "chỉ là có quá nhiều nền tảng".

Sau khi phân tích workflow, nhóm mới nhận ra nguyên nhân gốc rễ nằm ở bước tự đối chiếu và xác thực: học viên không biết đâu là nguồn thông tin chính thức và mới nhất giữa Vlearn, Codelabs và Discord, dẫn đến việc mất 25–40 phút xoay xở và tạo ra vô số câu hỏi lặp lại cho trợ giảng.

Nếu chỉ vội vàng dựng một AI Agent tự trả lời mọi câu hỏi mà không giải quyết bài toán chuẩn hóa dữ liệu nguồn (data metadata/index), hệ thống mới vẫn sẽ thất bại hoặc tạo ra ảo giác (hallucination).

---

## Tôi có thay đổi ý kiến sau khi bị challenge không?

Có. Sau khi đặt ra câu hỏi phản biện về việc liệu các công cụ đơn giản hơn như Form, Process Fix hay Rule có thể giải quyết bài toán hay không, tôi đã thay đổi quan điểm:

```text
Không nên để AI tự do suy diễn, tự cập nhật deadline hay tự động thay thế vai trò xác thực của trợ giảng.

Hướng phù hợp hơn là:

Process fix + Chuẩn hóa Metadata / Index nguồn chính thức (Rule)
-> AI tìm kiếm và tổng hợp thông tin bằng ngôn ngữ tự nhiên trong phạm vi cho phép (Workflow)
-> Luôn bắt buộc kèm link nguồn gốc
-> Người dùng (Học viên/Trợ giảng) tự kiểm tra và xác nhận lại nguồn.
```

---

## Nếu làm lại

```text
Tôi sẽ thực hiện phỏng vấn/khảo sát trực tiếp học viên sớm hơn và đo đạc baseline thực tế
trước khi đưa ra các con số kỳ vọng như giảm từ 25-40 phút xuống 10-15 phút hay giảm 30% câu hỏi.

Tôi cũng sẽ challenge mạnh hơn ở ba câu hỏi:

1. Pain chính là do học viên lười đọc hay do cấu trúc lưu trữ dữ liệu bị phân mảnh thật?
2. Nguồn dữ liệu Discord/Vlearn/Codelabs đã có chuẩn hóa metadata để AI đọc chính xác chưa?
3. Nếu AI trả lời sai thông tin hoặc tự suy diễn deadline/yêu cầu bài, cơ chế Fallback và Rollback sẽ kích hoạt như thế nào để không ảnh hưởng tới kết quả học tập?
```

---

## Tự kiểm cuối phần reflection

- [x] Nêu rõ tôi đã tham gia vào những hoạt động nào.
- [x] Nêu kết quả hoặc ảnh hưởng của từng đóng góp.
- [x] Phân biệt phần AI hỗ trợ và phần con người tự quyết định.
- [x] Chỉ ra điểm AI trả lời hời hợt hoặc đẩy scope quá rộng.
- [x] Nêu điều tôi đã sửa bằng nhận định của mình.
- [x] Nêu bài học về problem, workflow, metric và human boundary.
- [x] Nêu việc tôi sẽ thay đổi nếu làm lại.
- [x] Kiểm tra lại toàn bộ nội dung để bảo đảm phản ánh đúng trải nghiệm thật trước khi nộp.
