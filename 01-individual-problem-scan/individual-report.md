# INDIVIDUAL PROBLEM SCAN — DAY 02 LAB

**Họ và tên:** Phạm Nguyễn Hùng Nguyên  
**Mã học viên:** 2A202601279  
**Ngày thực hiện:** 27-2-2026  
**Nhóm:** ................................

> Các số liệu về thời gian và tần suất trong bài là ước lượng dựa trên trải nghiệm cá nhân.

---

# 1. Individual Problem Scan

## 1.1. Danh sách các vấn đề quan sát được

| #   | Lăng kính          | Problem quan sát được                                                                                                          | Ai chịu ảnh hưởng?                                          | Dấu hiệu thật                                                                                                                                |
| --- | ------------------ | ------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | Tốn thời gian      | Người mới học AI/robotics phải đọc nhiều JD, roadmap, video và repository khác nhau nhưng vẫn khó xác định nên học gì trước.   | Sinh viên năm cuối, người mới chuyển hướng sang AI/robotics | Tôi đã nhiều lần đọc JD và roadmap trong khoảng 1–2 giờ nhưng sau đó vẫn phải hỏi người khác về thứ tự học.                                  |
| 2   | Lặp lại            | Người mới cài môi trường robotics phải thực hiện nhiều lệnh rời rạc và thường xuyên hỏi lại từng bước khi gặp lỗi.             | Sinh viên mới học ROS, Gazebo hoặc Ubuntu                   | Chỉ cần sai một lệnh là quá trình cài đặt bị dừng; người học thường phải chụp màn hình và hỏi người khác.                                    |
| 3   | Tốn thời gian      | Khi đọc JD hoặc tài liệu tiếng Anh, người học phải tra từng thuật ngữ kỹ thuật rồi tự liên kết chúng thành kiến thức tổng thể. | Sinh viên có khả năng tiếng Anh chưa tốt                    | Một JD có thể chứa nhiều thuật ngữ như manipulation, motion planning, RL, MPC, VLA, ASR và TTS; việc tra cứu làm quá trình đọc bị gián đoạn. |
| 4   | Pain từ người khác | Thành viên nhóm dễ bỏ sót yêu cầu trong README hoặc worksheet dài khi chuẩn bị bài nộp.                                        | Học viên làm bài cá nhân và bài nhóm                        | Yêu cầu nằm ở nhiều phần khác nhau; học viên thường phải hỏi lại cần nộp file nào và phần nào làm theo nhóm.                                 |
| 5   | Lặp lại            | Người mới sử dụng Git/GitHub thường hỏi lại về clone, branch, commit, push, pull và conflict.                                  | Sinh viên mới làm dự án nhóm                                | Người mới dễ nhầm giữa repository local, remote, branch cá nhân và branch main.                                                              |
| 6   | Tốn thời gian      | Người học khó tìm lại một hướng dẫn hoặc quyết định cũ trong Discord, nhóm chat hoặc lịch sử trao đổi dài.                     | Học viên và thành viên dự án                                | Khi cần tìm một lệnh hoặc yêu cầu cũ, người dùng có thể mất 10–20 phút để tìm kiếm hoặc cuộn lại tin nhắn.                                   |
| 7   | AI có thể tốt hơn  | Roadmap chung không biết người học đã biết gì, còn thiếu gì, mục tiêu là gì và có bao nhiêu thời gian học.                     | Người mới học AI/robotics                                   | Hai người xem cùng một roadmap nhưng có nền tảng khác nhau; roadmap cố định không chỉ ra nội dung nào cần ưu tiên hoặc có thể bỏ qua.        |
| 8   | Pain từ người khác | Trong nhóm học tập, câu hỏi về deadline, cấu trúc file và yêu cầu nộp bài thường được hỏi lặp lại.                             | Thành viên nhóm và người phụ trách nhóm                     | Người phụ trách phải trả lời nhiều lần vì thông tin nằm rải rác trong README, worksheet và tin nhắn.                                         |
| 9   | Tốn thời gian      | Người học khó đánh giá một repository hoặc khóa học có phù hợp với mục tiêu nghề nghiệp của mình hay không.                    | Sinh viên tự học AI/robotics                                | Người học xem nhiều tài liệu nhưng không biết tài liệu nào là nền tảng, tài liệu nào quá nâng cao hoặc không liên quan.                      |
| 10  | Lặp lại            | Khi gặp lỗi cài đặt hoặc code, người học thường chỉ gửi ảnh lỗi nhưng không biết cần cung cấp thêm thông tin gì.               | Người mới học lập trình và robotics                         | Người hỗ trợ phải hỏi lại phiên bản hệ điều hành, câu lệnh đã chạy, log đầy đủ và bước trước khi xảy ra lỗi.                                 |

---

# 2. Top 3 Problems

## 2.1. Tiêu chí lựa chọn

Ba vấn đề được chọn dựa trên các tiêu chí:

- Actor cụ thể.
- Workflow hiện tại có thể mô tả được.
- Bottleneck rõ ràng.
- Impact có thể ước lượng hoặc đo.
- Phạm vi không quá rộng cho một buổi lab.
- Có thể so sánh No AI, Rule, Workflow và Agent.

## 2.2. Bảng xếp hạng

| Rank | Problem                                                                                                             | Vì sao chọn                                                                                                                                    | Điều còn chưa chắc                                                                 |
| ---- | ------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| 1    | Người mới học AI/robotics khó tạo lộ trình học từ JD và nhiều nguồn rời rạc                                         | Đây là vấn đề tôi trực tiếp gặp nhiều lần; actor, workflow và bottleneck rõ; có thể đo bằng thời gian tạo kế hoạch và số lần phải sửa kế hoạch | Chưa có dữ liệu từ nhiều người để xác nhận thời gian trung bình và mức độ phổ biến |
| 2    | Người mới cài môi trường robotics khó hoàn thành quy trình khi hướng dẫn bị phân tán và lỗi phát sinh theo từng máy | Workflow có nhiều bước rõ ràng; bottleneck nằm ở bước xử lý lỗi; có thể hỗ trợ bằng checklist, Rule và AI                                      | Lỗi môi trường rất đa dạng nên có thể khó giới hạn phạm vi                         |
| 3    | Học viên dễ bỏ sót yêu cầu trong README hoặc worksheet dài khi chuẩn bị bài nộp                                     | Vấn đề gần với trải nghiệm hiện tại; dễ kiểm chứng; có thể đo số phần bị thiếu và thời gian kiểm tra                                           | Checklist hoặc script thông thường có thể đã giải quyết được phần lớn vấn đề       |

---

# 3. Problem Card 1 — Tạo lộ trình học từ JD AI/Robotics

## 3.1. Problem một câu

Người mới học AI/robotics mất nhiều thời gian đọc JD và nhiều nguồn học rời rạc nhưng vẫn khó xác định kiến thức cần học, thứ tự ưu tiên và phạm vi phù hợp với trình độ hiện tại.

## 3.2. Actor

Sinh viên năm cuối hoặc người mới chuyển hướng sang AI/robotics, đã biết lập trình cơ bản nhưng chưa có nền tảng đầy đủ về machine learning, robotics và các thuật ngữ chuyên ngành.

## 3.3. Thời điểm / bối cảnh

Vấn đề xảy ra khi người học:

- Đọc JD AI Engineer hoặc Robotics Engineer.
- Muốn chuẩn bị để ứng tuyển trong khoảng 1–3 tháng.
- Cần chuyển yêu cầu tuyển dụng thành kế hoạch học cụ thể.
- Không biết nội dung nào cần học trước và nội dung nào có thể học sau.

## 3.4. Current workflow

1. Tìm và đọc JD tuyển dụng.
2. Gạch ra các kỹ năng và thuật ngữ chưa biết.
3. Tra từng thuật ngữ trên Google, YouTube hoặc ChatGPT.
4. Tìm roadmap, repository và khóa học liên quan.
5. So sánh nhiều nguồn nhưng không biết nguồn nào phù hợp.
6. Tự sắp xếp thứ tự học.
7. Viết kế hoạch học.
8. Hỏi mentor hoặc người có kinh nghiệm để kiểm tra.
9. Sửa lại kế hoạch nhiều lần.

## 3.5. Bottleneck

Bottleneck nằm ở bước so sánh tài liệu và tự sắp xếp thứ tự học.

Người học không biết cách chuyển một danh sách kỹ năng rộng thành lộ trình phù hợp với:

- Nền tảng hiện tại.
- Vị trí muốn ứng tuyển.
- Thời gian có thể dành cho việc học.
- Mức độ quan trọng của từng kỹ năng.
- Quan hệ phụ thuộc giữa các kiến thức.

## 3.6. Impact

- Mỗi lần phân tích một JD có thể mất khoảng 1–2 giờ.
- Người học dễ học lan man hoặc bắt đầu từ nội dung quá nâng cao.
- Kế hoạch thường xuyên thay đổi vì không có tiêu chí ưu tiên rõ ràng.
- Thời gian bị tiêu tốn cho việc tìm tài liệu thay vì học và thực hành.
- Người học dễ mất động lực vì không biết mình đang đi đúng hướng hay không.

## 3.7. Success metric

- Giảm thời gian tạo bản lộ trình đầu tiên từ khoảng 90 phút xuống dưới 20 phút.
- Lộ trình chỉ gồm những kỹ năng liên quan trực tiếp đến JD và mục tiêu đã chọn.
- Người học có thể giải thích lý do từng nội dung xuất hiện trong lộ trình.
- Sau khi được mentor hoặc người có kinh nghiệm review, số nội dung cần thay đổi không vượt quá 20%.
- Giảm số lần người học phải xây dựng lại toàn bộ kế hoạch.

## 3.8. Non-AI alternative

- Dùng roadmap cố định theo từng vị trí.
- Dùng checklist kỹ năng do mentor chuẩn bị.
- Dùng template phân loại kiến thức thành nền tảng, bắt buộc, nâng cao và chưa cần học.
- Tham khảo lộ trình của những người đã ứng tuyển thành công.
- Đặt lịch tư vấn trực tiếp với mentor.

## 3.9. AI hypothesis

Một workflow có AI có thể:

1. Nhận JD tuyển dụng.
2. Nhận thông tin nền tảng, mục tiêu và thời gian của người học.
3. Tách các kỹ năng xuất hiện trong JD.
4. Nhóm kỹ năng thành nền tảng, bắt buộc và nâng cao.
5. Xác định quan hệ phụ thuộc giữa các kỹ năng.
6. Đề xuất thứ tự học và thời lượng dự kiến.
7. Giải thích lý do của từng đề xuất.
8. Đưa lộ trình cho người học hoặc mentor kiểm tra.

AI chỉ hỗ trợ phân tích và đề xuất, không quyết định mục tiêu nghề nghiệp thay người học.

## 3.10. Quick gut

- [ ] No AI / Process fix
- [ ] Rule
- [x] Workflow
- [ ] Agent
- [ ] Chưa biết

## 3.11. Draft current workflow

```text
CURRENT STATE — khoảng 90 phút

[Tìm JD tuyển dụng: 10 phút]
        ↓
[Đọc JD và gạch kỹ năng: 15 phút]
        ↓
[Tra các thuật ngữ chưa biết: 20 phút]
        ↓
[Tìm roadmap, repository và khóa học: 20 phút]
        ↓
[So sánh nhiều nguồn: 10 phút]
        ↓
[Tự sắp xếp thứ tự học: 10 phút]
        ↓
[Viết kế hoạch học: 5 phút]
        ↓
[Hỏi mentor và sửa kế hoạch]

BOTTLENECK:
So sánh nhiều nguồn và tự sắp xếp thứ tự học.
```

## 3.12. Draft future workflow

```text
FUTURE STATE — khoảng 20 phút

[Nhập JD tuyển dụng]
        ↓
[Nhập nền tảng, mục tiêu và thời gian học]
        ↓
[Rule tách các kỹ năng rõ ràng trong JD]
        ↓
[AI phân loại kỹ năng]
        ↓
[AI đề xuất thứ tự và thời lượng]
        ↓
[AI giải thích lý do]
        ↓
[Người học hoặc mentor kiểm tra]
        ↓
[Chỉnh sửa và chốt lộ trình]

HUMAN BOUNDARY:
Người học hoặc mentor chịu trách nhiệm kiểm tra
và chốt lộ trình cuối cùng.
```

## 3.13. Fallback

Nếu AI phân tích sai JD hoặc đề xuất nội dung không phù hợp, người học quay lại danh sách kỹ năng gốc và sử dụng roadmap, checklist hoặc ý kiến của mentor để chỉnh sửa.

---

# 4. Problem Card 2 — Hỗ trợ cài đặt môi trường Robotics

## 4.1. Problem một câu

Người mới học robotics dễ bị mắc kẹt khi cài đặt Ubuntu, ROS hoặc Gazebo vì hướng dẫn gồm nhiều bước, lỗi phụ thuộc vào từng máy và người học không biết phải làm gì sau khi một câu lệnh thất bại.

## 4.2. Actor

Sinh viên mới bắt đầu học robotics, chưa quen với Linux, terminal, package manager và cách đọc log lỗi.

## 4.3. Thời điểm / bối cảnh

Vấn đề xảy ra khi người học cần:

- Cài đặt Ubuntu, ROS hoặc Gazebo.
- Chạy một repository robotics.
- Chuẩn bị môi trường mô phỏng.
- Làm bài tập hoặc dự án yêu cầu Linux.
- Cài thêm package hoặc dependency.

## 4.4. Current workflow

1. Tìm README, tài liệu hoặc video hướng dẫn.
2. Kiểm tra sơ bộ hệ điều hành đang sử dụng.
3. Copy và chạy từng câu lệnh.
4. Một câu lệnh xuất hiện lỗi.
5. Chụp màn hình hoặc copy một phần thông báo lỗi.
6. Tìm lỗi trên Google hoặc hỏi người khác.
7. Thử nhiều câu lệnh sửa lỗi khác nhau.
8. Không chắc bước nào đã hoàn thành.
9. Tiếp tục cài đặt hoặc cài lại từ đầu.

## 4.5. Bottleneck

Bottleneck nằm ở bước xử lý lỗi.

Sau khi một câu lệnh thất bại, người học thường không biết:

- Lỗi xuất phát từ phiên bản hệ điều hành hay package.
- Bước nào đã cài đặt thành công.
- Cần cung cấp log hoặc thông tin gì.
- Câu lệnh sửa lỗi có an toàn không.
- Nên tiếp tục, rollback hay cài đặt lại.

## 4.6. Impact

- Quá trình cài đặt dự kiến mất 30–60 phút có thể kéo dài nhiều giờ.
- Người học dễ chạy các câu lệnh mà không hiểu tác dụng.
- Những lệnh sửa sai có thể làm môi trường phức tạp hơn.
- Người hỗ trợ phải hỏi lại nhiều thông tin trước khi xác định lỗi.
- Người học có thể bỏ cuộc trước khi bắt đầu học phần chuyên môn.

## 4.7. Success metric

- Giảm tổng thời gian cài đặt và xử lý các lỗi phổ biến xuống dưới 90 phút.
- Khi gặp lỗi, người học xác định được bước lỗi và thu thập đủ thông tin trong dưới 5 phút.
- Giảm số lần người hỗ trợ phải hỏi lại thông tin về hệ điều hành, phiên bản, câu lệnh và log.
- Tăng tỷ lệ người học hoàn thành cài đặt ngay trong lần đầu.
- Không tự động chạy các câu lệnh có nguy cơ làm mất dữ liệu hoặc thay đổi cấu hình quan trọng.

## 4.8. Non-AI alternative

- Viết checklist cài đặt riêng cho từng hệ điều hành và phiên bản.
- Tạo script kiểm tra phiên bản và dependency.
- Chuẩn hóa form báo lỗi.
- Tạo FAQ cho các lỗi phổ biến.
- Sử dụng Docker hoặc image đã được cấu hình sẵn.
- Yêu cầu mentor hướng dẫn trực tiếp từng bước.

## 4.9. AI hypothesis

Một workflow có AI có thể:

1. Nhận thông tin hệ điều hành và mục tiêu cài đặt.
2. Dùng Rule để kiểm tra phiên bản và dependency.
3. Hiển thị từng bước cài đặt theo đúng thứ tự.
4. Lưu lại trạng thái bước nào đã hoàn thành.
5. Khi có lỗi, yêu cầu người dùng cung cấp đúng log cần thiết.
6. Dùng AI để giải thích lỗi bằng ngôn ngữ đơn giản.
7. Đề xuất phương án xử lý đã được kiểm chứng.
8. Yêu cầu người dùng xác nhận trước khi chạy lệnh.
9. Chuyển vấn đề cho mentor nếu AI không đủ chắc chắn.

AI chỉ hỗ trợ giải thích và đề xuất. Người dùng vẫn quyết định có chạy câu lệnh hay không.

## 4.10. Quick gut

- [ ] No AI / Process fix
- [ ] Rule
- [x] Workflow
- [ ] Agent
- [ ] Chưa biết

## 4.11. Draft current workflow

```text
CURRENT STATE

[Tìm README, tài liệu hoặc video]
        ↓
[Kiểm tra sơ bộ hệ điều hành]
        ↓
[Copy và chạy từng câu lệnh]
        ↓
[Câu lệnh xuất hiện lỗi]
        ↓
[Chụp ảnh hoặc copy một phần log]
        ↓
[Tìm lỗi trên Google hoặc hỏi người khác]
        ↓
[Thử nhiều cách sửa khác nhau]
        ↓
[Kiểm tra xem lỗi đã được sửa chưa]
        ↓
[Nếu chưa được: cài lại hoặc tiếp tục chờ hỗ trợ]

BOTTLENECK:
Người học không biết nguyên nhân lỗi,
không biết cần cung cấp thông tin gì
và không biết phương án xử lý có an toàn hay không.
```

## 4.12. Draft future workflow

```text
FUTURE STATE

[Nhập hệ điều hành và mục tiêu cài đặt]
        ↓
[Rule kiểm tra phiên bản và dependency]
        ↓
[Hiển thị từng bước cài đặt phù hợp]
        ↓
[Người dùng chạy câu lệnh]
        ↓
[Hệ thống kiểm tra kết quả]
        ↓
       Có lỗi?
       /     \
    Không     Có
      ↓        ↓
[Lưu trạng  [Thu thập log theo mẫu]
 thái]               ↓
      ↓       [AI giải thích nguyên nhân]
[Bước tiếp           ↓
 theo]       [AI đề xuất phương án xử lý]
                      ↓
             [Người dùng kiểm tra và xác nhận]
                      ↓
                 [Chạy lại lệnh]

HUMAN BOUNDARY:
Người dùng phải đọc và xác nhận trước khi chạy
bất kỳ câu lệnh sửa lỗi nào.
```

## 4.13. Fallback

Nếu lỗi không thuộc phạm vi đã biết hoặc AI không đủ chắc chắn, hệ thống dừng đề xuất và tạo một gói thông tin gồm:

- Hệ điều hành.
- Phiên bản phần mềm.
- Câu lệnh đã chạy.
- Bước đang thực hiện.
- Log lỗi đầy đủ.

Gói thông tin này được gửi cho mentor hoặc người hỗ trợ để kiểm tra thủ công.

---

# 5. Problem Card 3 — Kiểm tra bài nộp còn thiếu yêu cầu

## 5.1. Problem một câu

Học viên làm bài theo README hoặc worksheet dài có thể bỏ sót file, thư mục, heading, metric hoặc nội dung bắt buộc vì phải đối chiếu thủ công nhiều yêu cầu nằm rải rác trong tài liệu.

## 5.2. Actor

Học viên tham gia khóa học hoặc lab có bài nộp gồm nhiều file cá nhân, file nhóm và yêu cầu trình bày khác nhau.

## 5.3. Thời điểm / bối cảnh

Vấn đề xảy ra trước deadline, khi học viên đã làm gần xong bài và cần kiểm tra repository có đầy đủ yêu cầu hay chưa trước khi commit và push lên GitHub.

## 5.4. Current workflow

1. Đọc lại README.
2. Đọc lại worksheet.
3. Tự ghi nhớ hoặc tạo checklist.
4. Mở từng thư mục trong repository.
5. Mở từng file bài làm.
6. Đối chiếu từng file với từng yêu cầu.
7. Phát hiện và sửa nội dung còn thiếu.
8. Kiểm tra lại lần cuối.
9. Commit và push bài lên GitHub.

## 5.5. Bottleneck

Bottleneck nằm ở bước mở từng file và đối chiếu thủ công với nhiều yêu cầu khác nhau.

Người học phải nhớ:

- Cần có những thư mục nào.
- Tên file phải là gì.
- Mỗi file cần có những phần nào.
- Metric và boundary đã rõ chưa.
- Workflow trước và sau đã đầy đủ chưa.
- Phần nào là bài cá nhân và phần nào là bài nhóm.

## 5.6. Impact

- Có thể mất khoảng 20–30 phút để kiểm tra toàn bộ bài.
- Người học vẫn có nguy cơ nộp thiếu file hoặc thiếu một trường bắt buộc.
- Sát deadline, việc kiểm tra dễ được thực hiện qua loa.
- Nếu phát hiện lỗi muộn, người học phải sửa và push lại nhiều lần.
- Người phụ trách phải trả lời lặp lại các câu hỏi về cấu trúc bài nộp.

## 5.7. Success metric

- Giảm thời gian kiểm tra bài từ khoảng 25 phút xuống dưới 8 phút.
- Phát hiện 100% trường hợp thiếu file hoặc thư mục bắt buộc.
- Phát hiện ít nhất 90% heading hoặc field bắt buộc bị thiếu.
- Mỗi cảnh báo phải dẫn về đúng yêu cầu trong README hoặc worksheet.
- Không tự sửa, tự commit hoặc tự nộp bài khi chưa có xác nhận của học viên.

## 5.8. Non-AI alternative

- Tạo checklist thủ công.
- Cung cấp template repository chuẩn.
- Viết script kiểm tra tên file và cấu trúc thư mục.
- Dùng GitHub Actions để kiểm tra file bắt buộc.
- Dùng form nộp bài có validation.
- Đưa checklist cuối bài vào README.

## 5.9. AI hypothesis

Một workflow kết hợp Rule và AI có thể:

1. Nhận repository hoặc thư mục bài làm.
2. Dùng Rule kiểm tra tên thư mục, tên file và định dạng.
3. Trích xuất checklist từ README hoặc worksheet.
4. Dùng AI đọc nội dung từng file.
5. Đối chiếu các heading và field bắt buộc.
6. Tạo báo cáo gồm: đã đủ, còn thiếu và không chắc chắn.
7. Dẫn người học đến đúng yêu cầu gốc.
8. Để học viên tự kiểm tra và sửa.
9. Không tự commit, push hoặc nộp bài.

Rule phù hợp với yêu cầu cố định như tên file và cấu trúc thư mục. AI chỉ hỗ trợ phần kiểm tra nội dung bằng ngôn ngữ tự nhiên.

## 5.10. Quick gut

- [ ] No AI / Process fix
- [ ] Rule
- [x] Workflow
- [ ] Agent
- [ ] Chưa biết

## 5.11. Draft current workflow

```text
CURRENT STATE — khoảng 25 phút

[Đọc lại README: 5 phút]
        ↓
[Đọc lại worksheet: 5 phút]
        ↓
[Tự tạo hoặc ghi nhớ checklist]
        ↓
[Mở từng thư mục và từng file: 5 phút]
        ↓
[Đối chiếu thủ công từng yêu cầu: 7 phút]
        ↓
       Có thiếu?
       /      \
     Có       Không
      ↓          ↓
[Sửa bài]   [Kiểm tra lại lần cuối]
      ↓          ↓
[Kiểm tra lại] [Commit và push]

BOTTLENECK:
Mở từng file và đối chiếu thủ công
với nhiều yêu cầu nằm ở nhiều vị trí khác nhau.
```

## 5.12. Draft future workflow

```text
FUTURE STATE — khoảng 8 phút

[Chọn repository hoặc thư mục bài]
        ↓
[Rule kiểm tra cấu trúc thư mục]
        ↓
[Rule kiểm tra tên và định dạng file]
        ↓
[AI kiểm tra heading và nội dung bắt buộc]
        ↓
[Tạo báo cáo kiểm tra]
        ↓
 Kết quả thuộc loại nào?
   /          |           \
Đã đủ      Còn thiếu    Không chắc chắn
  ↓             ↓              ↓
[Học viên   [Hiển thị      [Đánh dấu cần
kiểm tra]   phần thiếu]    kiểm tra thủ công]
   \            |             /
        [Học viên kiểm tra]
                 ↓
          [Học viên sửa bài]
                 ↓
      [Học viên tự commit và push]

HUMAN BOUNDARY:
Học viên chịu trách nhiệm kiểm tra báo cáo,
sửa bài và quyết định nộp bài.
```

## 5.13. Fallback

Nếu AI không đọc được file hoặc không chắc chắn về một tiêu chí, hệ thống phải:

- Đánh dấu nội dung là “Cần kiểm tra thủ công”.
- Không kết luận rằng bài đã đầy đủ.
- Dẫn người học về đúng phần yêu cầu trong README hoặc worksheet.
- Để học viên tự đưa ra quyết định cuối cùng.

---

# 6. Card tôi muốn pitch nhất

## 6.1. Card được chọn

**Problem Card 1 — Người mới học AI/robotics khó tạo lộ trình học phù hợp từ JD và nhiều nguồn rời rạc.**

## 6.2. Vì sao tôi muốn pitch vấn đề này

Đây là vấn đề tôi đã trực tiếp gặp trong quá trình tìm hiểu các vị trí AI Engineer và Robotics Engineer.

Tôi có thể tìm được nhiều JD, roadmap, repository, video và khóa học nhưng vẫn khó xác định:

- Nội dung nào là kiến thức nền tảng.
- Nội dung nào cần ưu tiên.
- Nội dung nào quá nâng cao ở thời điểm hiện tại.
- Cần học đến mức nào là đủ để bắt đầu làm dự án hoặc ứng tuyển.

Vấn đề này có actor rõ, workflow hiện tại có thể mô tả, bottleneck cụ thể và có thể đo bằng thời gian tạo lộ trình, số lần phải sửa kế hoạch và mức độ thay đổi sau khi được mentor review.

Vấn đề cũng đáng để nhóm challenge vì có khả năng một roadmap hoặc checklist tốt đã giải quyết được phần lớn nhu cầu mà chưa cần AI.

## 6.3. Pitch ngắn

Người mới học AI/robotics thường mất khoảng 1–2 giờ đọc JD, tra thuật ngữ và tìm roadmap nhưng vẫn không biết nên học gì trước.

Bottleneck không phải là thiếu tài liệu mà là không biết chuyển nhiều yêu cầu rời rạc thành một lộ trình phù hợp với nền tảng, mục tiêu và thời gian cá nhân.

Tôi muốn kiểm tra xem một workflow kết hợp Rule, AI phân tích và human review có thể giảm thời gian tạo lộ trình xuống dưới 20 phút hay không.

## 6.4. Câu hỏi tôi muốn nhóm challenge

1. Actor hiện tại đã đủ cụ thể chưa, hay cần thu hẹp thành sinh viên năm cuối muốn ứng tuyển AI/robotics?
2. Baseline 90 phút có phản ánh nhiều người hay chỉ phản ánh trải nghiệm cá nhân của tôi?
3. Một roadmap và checklist cố định có thể giải quyết được 70–80% vấn đề không?
4. Phần nào thật sự cần AI, phần nào chỉ cần Rule hoặc template?
5. Làm thế nào đo được một lộ trình là phù hợp ngoài việc đo thời gian tạo lộ trình?
6. Dữ liệu đầu vào tối thiểu cần có là gì?
7. Rủi ro lớn nhất nếu AI đề xuất sai thứ tự học là gì?
8. Problem này có quá rộng cho một pilot nhỏ hay không?
