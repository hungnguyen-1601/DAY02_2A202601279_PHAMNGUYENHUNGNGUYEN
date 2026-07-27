# INDIVIDUAL REFLECTION — DAY 02 LAB

**Họ và tên:** Phạm Nguyễn Hùng Nguyên  
**Mã học viên:** 2A202601279  
**Nhóm:** A4  
**Ngày thực hiện:** 27-2-2026  
**Đề tài nhóm:** Tạo lộ trình học cá nhân hóa từ JD AI/Robotics  
**Vai trò của tôi trong nhóm:** Đề xuất problem, xây dựng workflow và Problem Statement  
**Quyết định cuối của nhóm:** Not Yet

---

# 1. Tôi đã tham gia vào phần nào

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng |
| --- | --- | --- |
| Scan cá nhân | Scan 10 problems theo 4 lăng kính (lặp lại, tốn thời gian, AI có thể tốt hơn, pain từ người khác), mỗi problem đều ghi actor và dấu hiệu thật | Vượt mức tối thiểu 5 problems; nhóm có thêm nhiều candidate thuộc cụm "học tập và chuẩn bị nghề nghiệp" |
| Pitch Problem Card | Pitch Card 1 — tạo lộ trình học từ JD AI/Robotics: mất 1–2 giờ đọc JD, tra thuật ngữ, tìm roadmap nhưng vẫn không biết học gì trước | Card được nhóm chọn làm candidate problem để đào sâu |
| Challenge bài của bạn khác | Khi nghe các card khác, tôi tập trung hỏi ba câu: actor có đủ hẹp không, bottleneck có phải một bước cụ thể không, và Rule/checklist thông thường đã giải được bao nhiêu phần trăm chưa | Giúp nhóm loại các candidate có phạm vi quá rộng hoặc chưa mô tả được workflow hiện tại |
| Tự challenge card của mình | Chủ động đưa ra 8 câu hỏi phản biện chính card của mình (baseline 90 phút, actor, roadmap cố định, phần nào thật sự cần AI, cách đo "lộ trình phù hợp", rủi ro nếu AI sai thứ tự học, phạm vi pilot) | Nhóm không chọn card vì nghe hay mà vì biết trước điểm yếu của nó; các câu hỏi này về sau trở thành mục "Điều cần làm trước khi Go" |
| Gom trùng / cluster | Nhận ra 3 trong 10 problem của tôi (chọn tài liệu, đánh giá repository/khóa học, roadmap chung không biết người học đã biết gì) thực chất cùng một pattern: chọn và sắp xếp kiến thức, không phải thiếu tài liệu | Giúp nhóm gộp nhiều candidate rời rạc về một bài toán duy nhất |
| Chọn candidate problem | Lập luận chọn theo tiêu chí actor rõ, workflow mô tả được, bottleneck cụ thể, impact đo được, phạm vi vừa cho một lab | Nhóm thống nhất chọn "Tạo lộ trình học cá nhân hóa từ JD AI/Robotics" |
| Validation / research | Cung cấp baseline 90 phút từ trải nghiệm của chính mình và ghi rõ đây mới chỉ là n = 1; góp phần soạn 7 câu hỏi phỏng vấn cho kế hoạch validation | Nhóm ghi thẳng vào báo cáo rằng chưa có kết quả phỏng vấn ngoài nhóm, thay vì làm như đã kiểm chứng xong |
| Workflow nhóm | Vẽ current workflow 9 bước (~90 phút) và future workflow mục tiêu dưới 20 phút, kèm bảng actor/input/output/thời gian cho từng bước | Bản workflow trước/sau của nhóm dựa trên bản này |
| Problem Statement | Viết Problem Statement v0 và v1 (6 field + AI intervention point + mức chọn + rủi ro và người kiểm tra) | Là artifact chính của phần 20 điểm nhóm |
| Rule / Workflow / Agent | Lập luận vì sao Rule không đủ cho toàn bộ bài toán, vì sao chưa cần Agent, và đặt AI intervention point sau bước người học xác nhận danh sách kỹ năng | Nhóm chốt mức Workflow, không chọn Agent |
| Decision | Ủng hộ Not Yet thay vì Go vì baseline 90 phút chưa được kiểm chứng ngoài nhóm | Nhóm chốt Not Yet kèm 6 việc cần làm trước và điều kiện chuyển sang Go |

---

# 2. Cách tôi dùng AI trong lab

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình |
| --- | --- | --- | --- | --- |
| Scan | Tự scan trước khoảng 6 problem, sau đó nhờ AI gợi ý thêm góc nhìn theo 4 lăng kính | Nhắc tôi nhớ ra vài pain của người khác mà tôi hay bỏ qua, ví dụ người hỗ trợ phải hỏi lại thông tin lỗi nhiều lần | Gợi ý nhiều ý rất rộng kiểu "trợ lý học tập toàn năng", "nền tảng cá nhân hóa việc học" — không có actor và workflow thật | Bỏ các ý tôi không có trải nghiệm trực tiếp; chỉ giữ những problem tôi tự chỉ ra được ai đau, đau ở bước nào và dấu hiệu là gì |
| Problem Card | Nhờ AI đóng vai skeptical PM phản biện Card 1, yêu cầu chỉ nêu điểm yếu | Chỉ đúng hai chỗ yếu: actor còn rộng và metric mới chỉ đo thời gian | Đề xuất luôn giải pháp "xây agent tư vấn lộ trình" trong khi tôi mới đang làm rõ problem | Giữ lại phần phản biện, bỏ phần giải pháp; thu hẹp actor thành người đã biết lập trình cơ bản nhưng chưa có nền ML/robotics; thêm metric chất lượng (tỷ lệ nội dung phải sửa sau review ≤ 20%, mỗi mục có lý do rõ ràng) |
| Workflow | Nhờ AI viết lại mô tả của tôi thành sơ đồ các bước | Nhanh hơn khi trình bày lại flow cho dễ đọc | AI gộp bước "trích xuất kỹ năng" và "phân loại, đề xuất thứ tự" thành một bước AI duy nhất, và bỏ hẳn bước người học xác nhận | Tách lại hai bước vì bản chất khác nhau: trích xuất là việc Rule làm được, phân loại và sắp thứ tự mới cần AI. Thêm bước "Người học xác nhận danh sách kỹ năng" vào giữa để nếu Rule trích sai thì lỗi không chạy tiếp xuống các bước sau |
| Research | Dùng AI và search để tìm giải pháp đã có cho bài toán chuyển JD thành lộ trình học | Gợi ý hướng tìm roadmap công khai và repository tổng hợp tài liệu robotics | Đưa ra vài con số kiểu "tiết kiệm x% thời gian học" nhưng không kèm nguồn kiểm được | Chỉ giữ những nguồn tôi mở được link và đọc trực tiếp (roadmap.sh AI Engineer, awesome-humanoid-robot-learning), thêm hai phương án phi công nghệ là mentor và checklist phân tích JD; không đưa bất kỳ số liệu nào không verify được vào báo cáo |
| Problem Statement | Nhờ AI chỉ ra field nào còn mơ hồ trong v0, không cho viết lại thay | Chỉ ra "học lan man" là mô tả cảm tính, chưa phải impact đo được | Khi được hỏi tiếp, AI tự viết lại nguyên bảng Problem Statement theo văn phong của nó, làm mất phần boundary cụ thể mà nhóm đã thống nhất | Không dùng bản AI viết lại; tự bổ sung boundary theo 5 điều AI không được làm (không quyết định mục tiêu nghề nghiệp, không khẳng định đủ khả năng ứng tuyển, không tự đăng ký khóa học, không tự áp dụng lộ trình khi chưa xác nhận, không thay mentor phê duyệt) |
| Rule / Workflow / Agent | Hỏi AI phản biện cả ba mức để kiểm tra xem nhóm có bỏ sót lập luận nào không | Giúp tôi diễn đạt rõ hơn vì sao Rule không đủ: Rule khớp từ khóa được nhưng không biết người học đã biết gì | Thiên về Agent, mô tả một agent tự tìm tài liệu, tự lập kế hoạch, tự theo dõi tiến độ, nhưng không nói ai chịu trách nhiệm khi lộ trình sai | Nhóm giữ mức Workflow. Lý do tôi đưa ra: các bước gần như cố định, không có bước nào cần AI tự quyết định gọi công cụ gì tiếp theo, và rủi ro chỉ kiểm soát được khi còn người học hoặc mentor review ở cuối |
| Decision | Hỏi AI những rủi ro còn lại trước khi nhóm chốt | Liệt kê được rủi ro AI bỏ sót kỹ năng bắt buộc | Kết luận nghiêng về Go ngay dù nhóm chưa có bất kỳ dữ liệu nào ngoài 4 người trong nhóm | Nhóm chọn Not Yet. Bằng chứng hiện tại chỉ gồm trải nghiệm của 1 người và thảo luận của 4 người; chưa đủ để coi baseline 90 phút là số thật |

## 2.1. Những phần tôi không dùng AI

Theo quy ước dùng AI của lab, tôi không dùng AI cho ba phần thể hiện suy nghĩ cá nhân:

- **Pitch:** tôi tự trình bày card của mình bằng trải nghiệm thật khi đọc JD AI/Robotics.
- **Challenge:** các câu hỏi tôi hỏi bạn trong nhóm là do tôi tự đặt khi nghe, không lấy từ AI.
- **Reflection:** phần này là đánh giá của tôi về buổi lab; AI chỉ được dùng để nhắc tôi còn thiếu ý nào cần tự soi.

---

# 3. Trả lời các câu hỏi phản tư

## 3.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?

Điều tôi học được nhiều nhất là một problem chỉ đứng vững khi người pitch mô tả được workflow hiện tại. Có những vấn đề nghe rất đau nhưng khi hỏi "hiện tại bạn đang làm bước nào, mất bao lâu, ai làm bước tiếp theo" thì không trả lời được, và những vấn đề đó rất khó đo và khó chọn mức AI phù hợp. Ngược lại, những card mô tả được từng bước thì cả nhóm bàn được ngay bước nào Rule làm đủ, bước nào cần AI.

Điều thứ hai là nhiều problem khác nhau về bề mặt nhưng chung một pattern. Ba trong số 10 problem của tôi tưởng là khác nhau, cuối cùng đều quy về việc chọn và sắp xếp kiến thức từ nhiều nguồn, chứ không phải thiếu nguồn.

## 3.2. Nhóm có lúc nào bị solution-first không?

Có. Lúc mới chọn xong candidate, nhóm bàn ngay tới việc "hệ thống sẽ trông như thế nào", "có nên để AI tự cập nhật lộ trình theo tiến độ học không". Đó là bàn giải pháp trong khi chưa có metric và chưa biết bottleneck nằm ở đâu.

Chúng tôi quay lại được nhờ vẽ current workflow đủ chi tiết trước. Khi bảng workflow có cột thời gian, nhóm nhìn ra khoảng 30 phút nằm ở bước tìm và so sánh nguồn, còn bước viết kế hoạch chỉ mất 5 phút. Từ đó nhóm mới đặt AI intervention point vào đúng chỗ so sánh và sắp xếp, thay vì để AI ôm cả quy trình.

Bản thân tôi cũng bị solution-first ở phần AI hypothesis của Card 1: tôi viết ra 8 bước AI sẽ làm trước khi có success metric rõ. Sau khi bị hỏi "đo thế nào là lộ trình phù hợp", tôi mới bổ sung tiêu chí tỷ lệ nội dung phải sửa sau review.

## 3.3. Tôi có thay đổi ý kiến sau khi bị challenge không?

Có, ở hai điểm.

Điểm thứ nhất là mức độ tự tin về baseline. Ban đầu tôi viết 90 phút như một con số chắc chắn. Khi bị hỏi con số này đến từ đâu, tôi phải thừa nhận nó chỉ đến từ vài lần tôi tự làm, không có log và không có người thứ hai xác nhận. Vì vậy nhóm ghi rõ trong báo cáo rằng baseline 90 phút hiện chỉ là giả định ban đầu.

Điểm thứ hai là phạm vi của AI. Ban đầu tôi nghĩ AI nên đọc JD rồi trả thẳng ra lộ trình. Sau khi bàn về trường hợp AI trích sai kỹ năng, tôi đổi ý: bước trích xuất giao cho Rule, người học xác nhận danh sách kỹ năng trước, rồi AI mới phân loại và đề xuất thứ tự. Như vậy nếu có sai thì người học phát hiện ở bước rẻ nhất chứ không phải sau khi đã có nguyên một lộ trình sai.

## 3.4. Tôi đóng góp gì thật sự vào artifact cuối?

- Candidate problem mà nhóm chọn đào sâu.
- Current workflow 9 bước kèm bảng actor/input/output/thời gian.
- Future workflow với ranh giới rõ giữa Rule, AI và người, kèm 6 bước fallback.
- Problem Statement v0 và v1.
- Lập luận chọn mức Workflow và lý do chưa chọn Agent.
- Việc ghi thẳng vào báo cáo rằng bằng chứng hiện tại còn yếu, dẫn tới quyết định Not Yet.

Phần tôi đóng góp ít hơn là validation thực địa. Đây cũng chính là phần khiến bài của nhóm chưa thể Go.

## 3.5. Điều khó nhất khi viết Problem Statement là gì?

Khó nhất là success metric. Đo thời gian thì dễ: 90 phút xuống dưới 20 phút. Nhưng một lộ trình tạo trong 20 phút mà sai thứ tự học thì còn tệ hơn mất 90 phút. Nghĩa là chỉ có metric thời gian thì có thể tối ưu đúng số nhưng sai mục tiêu.

Nhóm xử lý bằng cách thêm hai metric chất lượng: tỷ lệ nội dung phải sửa sau khi mentor review không quá 20%, và mỗi mục trong lộ trình phải có lý do giải thích được. Metric thứ hai quan trọng vì nó ép AI không được đưa ra đề xuất mà không nói được vì sao, và giúp người học phát hiện đề xuất vô lý.

Khó thứ hai là boundary. Ban đầu tôi viết boundary theo kiểu chung chung là "AI chỉ hỗ trợ". Câu đó không dùng được vì không kiểm tra được. Nhóm phải viết lại thành danh sách những việc AI không được làm, để sau này nhìn vào là biết ngay đã vi phạm hay chưa.

## 3.6. Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

Tôi sẽ challenge mạnh hơn ở phương án không dùng AI.

Trong báo cáo, nhóm kết luận Rule "không đủ cho toàn bộ bài toán", nhưng chúng tôi chưa thử đo xem một roadmap cố định cộng checklist phân tích JD giải được bao nhiêu phần trăm nhu cầu. Nếu con số đó là 70–80% thì kết luận hợp lý phải là làm checklist tốt trước, chứ chưa cần workflow có AI. Chúng tôi đã đưa việc so sánh này vào danh sách phải làm trước khi Go, nhưng lẽ ra nên ép nhau trả lời ngay trong lab, ít nhất bằng cách lấy một JD thật rồi thử tay bằng roadmap.sh xem thiếu ở đâu.

Điểm thứ hai tôi sẽ challenge mạnh hơn là chính card của mình. Vì card được chọn nên tôi vô tình trở thành người bảo vệ nó, trong khi vai trò tốt hơn là người tìm cách bác bỏ nó.

---

# 4. Tôi tự giải thích mạch bài của nhóm

**Problem.** Người mới học AI/robotics không thiếu tài liệu. Cái họ thiếu là cách chuyển một JD và nhiều nguồn rời rạc thành thứ tự học phù hợp với nền tảng, mục tiêu và thời gian của chính họ.

**Workflow.** Hiện tại quy trình gồm 9 bước: tìm JD, đọc và gạch kỹ năng, tra thuật ngữ, tìm roadmap và tài liệu, so sánh nguồn, tự sắp xếp thứ tự, viết kế hoạch, hỏi mentor, sửa lại. Tổng khoảng 90 phút cho bản draft đầu tiên.

**Bottleneck.** Nằm ở cụm so sánh nguồn và tự sắp xếp thứ tự học, khoảng 30 phút. Đây là bước duy nhất đòi hỏi hiểu ngữ cảnh cá nhân: người học đã biết gì, cần đến mức nào, kiến thức nào phụ thuộc kiến thức nào. Các bước còn lại chủ yếu là tìm và chép.

**Metric.** Giảm thời gian tạo draft từ khoảng 90 phút xuống dưới 20 phút; tỷ lệ nội dung phải sửa sau mentor review không quá 20%; mỗi mục trong lộ trình đều có lý do giải thích được.

**Boundary.** AI không quyết định mục tiêu nghề nghiệp, không khẳng định người học đã đủ khả năng ứng tuyển, không tự đăng ký khóa học, không tự áp dụng lộ trình khi người học chưa xác nhận, và không thay mentor phê duyệt. Nếu AI không chắc, hệ thống hiển thị lại JD gốc và danh sách kỹ năng để người học sửa tay, đồng thời cho phép quay về roadmap cố định.

**Độ phù hợp với AI.** Bài toán có độ mơ hồ cao (nhiều lộ trình khác nhau vẫn có thể chấp nhận được) nhưng độ phức tạp trung bình vì các bước gần như cố định và không có bước nào cần AI tự quyết định gọi công cụ gì tiếp theo. Vì vậy nhóm chọn **Workflow**: Rule trích xuất kỹ năng, người học xác nhận, AI phân loại và đề xuất thứ tự kèm giải thích, người học hoặc mentor review và chốt. Rule một mình không đủ vì không biết người học đã biết gì. Agent chưa cần vì không có nhánh động, mà lại làm mất điểm kiểm soát duy nhất là bước review.

**Quyết định.** **Not Yet.** Actor và workflow đã rõ, nhưng baseline 90 phút mới chỉ đến từ trải nghiệm của một người trong nhóm, chưa có phỏng vấn hay khảo sát bên ngoài, chưa có mentor đánh giá chất lượng draft, và chưa biết roadmap cố định giải được bao nhiêu phần trăm vấn đề. Nhóm chuyển sang Go khi phần lớn người được hỏi xác nhận problem, workflow mới giảm ít nhất 50% thời gian, không bỏ sót kỹ năng bắt buộc, mentor không phải sửa quá 20–30% nội dung và AI giải thích được lý do của từng đề xuất.

---

# 5. Bài học của tôi sau buổi lab

1. **Problem tốt không phải problem nghe "AI" nhất, mà là problem vẽ được workflow.** Khi chưa vẽ được từng bước với thời gian cụ thể, mọi lựa chọn Rule/Workflow/Agent đều là đoán.
2. **Vẽ workflow là công cụ phát hiện bottleneck, không phải để trình bày cho đẹp.** Chỉ khi có cột thời gian, nhóm mới thấy phần đau nằm ở so sánh và sắp xếp chứ không nằm ở viết kế hoạch.
3. **Đặt AI ở đâu quan trọng hơn dùng AI mạnh tới đâu.** Chèn thêm một bước người học xác nhận danh sách kỹ năng, tuy tốn 2 phút, lại chặn được lỗi lan xuống toàn bộ lộ trình.
4. **Metric thời gian một mình có thể dẫn nhóm đi sai hướng.** Phải có thêm metric chất lượng thì mới biết cải thiện là thật.
5. **Boundary phải viết dưới dạng kiểm tra được.** "AI chỉ hỗ trợ" không kiểm tra được; "AI không được tự áp dụng lộ trình khi người học chưa xác nhận" thì kiểm tra được.
6. **Not Yet là một quyết định đàng hoàng.** Nói rõ còn thiếu bằng chứng gì và cần đo gì trước khi Go có giá trị hơn một chữ Go dựa trên n = 1.
7. **AI phản biện tốt nhưng hay nhảy sang giải pháp và nghiêng về mức phức tạp nhất.** Trong lab này, gần như lần nào AI cũng đẩy về phía Agent và về phía Go; phần việc của tôi là kéo lại về đúng bằng chứng đang có.

---

# 6. Nếu làm lại, tôi sẽ đổi gì

1. **Dành 15 phút đầu để lấy bằng chứng thay vì viết đẹp thêm.** Chỉ cần nhắn hỏi 3 người mới học AI/robotics một câu "lần gần nhất bạn chuyển JD thành kế hoạch học mất bao lâu" là baseline 90 phút đã có cơ sở hơn hẳn, và nhóm có thể đã đủ điều kiện để cân nhắc Go với scope nhỏ.
2. **Thử phương án không dùng AI ngay trong lab.** Lấy một JD thật, dùng roadmap.sh và checklist làm tay trong 20 phút, rồi ghi lại chỗ nào thiếu. Kết quả đó sẽ quyết định phần AI có đáng làm hay không, thay vì để nhóm suy đoán.
3. **Chọn phản biện chính card của mình.** Vì card của tôi được chọn, tôi nên chủ động nhận vai người tìm cách bác bỏ nó để tránh nhóm chỉ đi theo góc nhìn của một người.
4. **Đo bước review của mentor.** Trong bảng workflow hiện tại, bước review vẫn ghi "chưa đo", trong khi metric chính của nhóm lại phụ thuộc vào tỷ lệ nội dung mentor phải sửa. Đây là lỗ hổng lớn nhất còn lại của bài.
5. **Dùng AI muộn hơn một nhịp.** Những lần AI làm tôi mất thời gian nhất đều là khi tôi hỏi trước lúc tự nghĩ xong; những lần AI hữu ích nhất đều là khi tôi đưa cho nó một bản nháp cụ thể và chỉ yêu cầu chỉ ra điểm yếu.

---

*Individual Reflection — Day 02 Lab, Phạm Nguyễn Hùng Nguyên, 2A202601279, Nhóm A4*
