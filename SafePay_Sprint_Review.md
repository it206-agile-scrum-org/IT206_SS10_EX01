# Bài thực hành 1: Sprint Review cho ứng dụng SafePay

## Nhiệm vụ 1: Xác định nội dung được trình diễn

| Mã     | Trình diễn như Increment hoàn thành? | Lý do dựa trên dữ liệu                                                                                                                                   |
| ------ | ------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| PBI-01 | Có                                   | Acceptance Criteria đạt 4/4 và Definition of Done đạt 5/5; đã tích hợp.                                                                                  |
| PBI-02 | Có                                   | Acceptance Criteria đạt 5/5 và Definition of Done đạt 5/5; đã tích hợp.                                                                                  |
| PBI-03 | Có                                   | Acceptance Criteria đạt 3/3 và Definition of Done đạt 5/5; đã tích hợp.                                                                                  |
| PBI-04 | Không                                | Acceptance Criteria mới đạt 2/4 (thiếu xóa lịch sử và lọc theo loại), Definition of Done chưa đạt. Chỉ nhắc minh bạch là chưa xong.                      |
| PBI-05 | Không                                | Acceptance Criteria đạt 3/3 nhưng Definition of Done chỉ đạt 2/5, vì chưa review chéo và chưa kiểm thử trên điện thoại. Chỉ nhắc minh bạch là chưa Done. |

## Nhiệm vụ 2: Kế hoạch Sprint Review (35 phút)

| STT | Hoạt động                                                                                             | Người phụ trách                               | Thời lượng | Kết quả mong đợi                                                                           |
| --- | ----------------------------------------------------------------------------------------------------- | --------------------------------------------- | ---------- | ------------------------------------------------------------------------------------------ |
| 1   | Mở đầu: nêu Sprint Goal, kết quả Sprint (3/5 PBI Done, 2 PBI chưa Done) và tình trạng Product Backlog | Product Owner (Ngọc Hương)                    | 5 phút     | Mọi người hiểu mục tiêu và kết quả Sprint một cách minh bạch.                              |
| 2   | Trình diễn Increment hoàn thành: PBI-01, PBI-02, PBI-03 trên sản phẩm chạy thật                       | Developers (Thu An, Gia Bình, Mai Lan)        | 12 phút    | Stakeholders thấy và dùng thử được Increment; các câu hỏi về kết quả Sprint được giải đáp. |
| 3   | Thảo luận và thu thập phản hồi, ghi theo mã FB-xx                                                     | Stakeholders phản hồi; Scrum Master điều phối | 12 phút    | Có danh sách phản hồi rõ ràng, được ghi nhận đầy đủ, chưa cam kết gì.                      |
| 4   | Rà soát Product Backlog và hướng đi tiếp theo (gồm PBI-04, PBI-05 chưa xong)                          | Product Owner                                 | 6 phút     | Product Owner có đầu vào để điều chỉnh, sắp xếp lại Product Backlog.                       |

**Mục tiêu buổi Review:** Stakeholders và Scrum Team cùng xem xét Increment thực tế, trao đổi hai chiều và có đầu vào để Product Owner điều chỉnh Product Backlog theo Product Goal.

**Cách thu nhận phản hồi:** Phản hồi được nêu trực tiếp hoặc qua chat trong lúc trình diễn. Một Developer ghi vào bảng chung theo mã FB-01…FB-05, ghi rõ người nêu và nội dung. Phản hồi chỉ được ghi nhận, chưa hứa làm; Product Owner phân loại và quyết định sau.

## Nhiệm vụ 3: Phân định vai trò các bên

| Vai trò       | Việc nên thực hiện                                                                                        | Việc không nên thực hiện                                                |
| ------------- | --------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| Product Owner | Nêu Sprint Goal, giải thích tình trạng Product Backlog, lắng nghe phản hồi và xem xét điều chỉnh backlog. | Hứa chắc chắn đưa mọi phản hồi vào Sprint tiếp theo ngay tại buổi họp.  |
| Scrum Master  | Đảm bảo sự kiện đúng mục tiêu, đúng thời gian; khuyến khích mọi người trao đổi.                           | Quyết định thay Product Owner về nội dung hoặc thứ tự ưu tiên backlog.  |
| Developers    | Trình diễn Increment đã Done, trả lời câu hỏi về kết quả Sprint, nói rõ mục nào chưa Done.                | Giới thiệu mục chưa đạt Definition of Done như đã hoàn thành.           |
| Stakeholders  | Dùng thử, đặt câu hỏi, phản hồi từ góc nhìn sử dụng và nghiệp vụ.                                         | Coi phản hồi của mình là yêu cầu bắt buộc, hoặc ra lệnh cho Developers. |

## Nhiệm vụ 4: Xử lý phản hồi và đề xuất cập nhật Product Backlog

| Mã    | Nhóm             | Cách xử lý                                                                                                                                         | Cập nhật Product Backlog?          | Ưu tiên    |
| ----- | ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------- | ---------- |
| FB-01 | Đề xuất cải tiến | Đơn giản hóa từ ngữ ba mức cảnh báo, kèm gợi ý hành động tiếp theo dễ hiểu. Thử với người lớn tuổi.                                                | Có (cải tiến cho các PBI cảnh báo) | Cao        |
| FB-02 | Đề xuất cải tiến | Gắn vào PBI-05 (đang dở): bổ sung nút hướng dẫn liên hệ ngân hàng và hoàn thiện Definition of Done của PBI-05.                                     | Có (cập nhật PBI-05)               | Cao        |
| FB-03 | Ý tưởng mới      | Ghi nhận thành PBI mới ở dạng ý tưởng, nằm ngoài Sprint Goal hiện tại. Product Owner cân nhắc sau, chưa cam kết.                                   | Có (thêm item mới)                 | Thấp       |
| FB-04 | Cần làm rõ       | Product Owner làm rõ thời gian lưu báo cáo với Stakeholders và bên liên quan. Sau khi rõ, bổ sung vào Acceptance Criteria hoặc ghi chú của PBI-03. | Chưa, chỉ cập nhật sau khi làm rõ  | Trung bình |
| FB-05 | Lỗi cần xem xét  | Tái hiện lỗi trên nhiều cỡ màn hình điện thoại, rồi sửa bố cục để nút "Kiểm tra" luôn hiển thị.                                                    | Có (thêm mục lỗi)                  | Cao        |

_Tất cả chỉ là đề xuất để Product Owner xem xét, không phải cam kết cho Sprint tiếp theo._

## Nhiệm vụ 5: Sửa cách tổ chức chưa phù hợp

| Mã    | Điểm chưa phù hợp                                                                                                              | Cách sửa đề xuất                                                                                                         |
| ----- | ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------ |
| RV-01 | Giới hạn Stakeholders chỉ nói trong 3 phút cuối khiến Review thành buổi trình bày một chiều, trong khi cần trao đổi hai chiều. | Khuyến khích phản hồi xuyên suốt buổi họp và dành khoảng thời gian thảo luận riêng (như 12 phút ở kế hoạch trên).        |
| RV-02 | PBI-05 chưa đạt Definition of Done (2/5) nhưng được giới thiệu là đã hoàn thành, thiếu minh bạch.                              | Không trình diễn như Increment hoàn thành. Nếu nhắc đến, nói rõ chưa Done và còn thiếu review chéo, kiểm thử điện thoại. |
| RV-03 | Scrum Master quyết định thay Product Owner, và biến phản hồi thành cam kết.                                                    | Scrum Master chỉ điều phối. Product Owner xem xét FB-03, quyết định có đưa vào Product Backlog và xếp ưu tiên ra sao.    |
