# Đóng góp cho Sách OHDSI - Bản tiếng Việt

Trước tiên, cảm ơn bạn đã quan tâm đóng góp!

Tài liệu này hướng dẫn cách đóng góp cho bản dịch tiếng Việt của [The Book of OHDSI](https://github.com/OHDSI/TheBookOfOhdsi). Đây là bản dịch/bản địa hóa từ bản gốc tiếng Anh, dùng để hướng dẫn từng bước cách thực hiện một nghiên cứu bằng các công cụ OHDSI.

Đối với các thay đổi về **nội dung gốc** (không phải bản dịch), vui lòng đóng góp trực tiếp vào [repo gốc OHDSI/TheBookOfOhdsi](https://github.com/OHDSI/TheBookOfOhdsi).

# Hướng dẫn

## Cấu trúc chương

Mỗi chương thường theo cấu trúc:
	Giới thiệu
	Lý thuyết
	Thực hành
	Chủ đề nâng cao (nếu có)
	Bài tập

Mỗi chương có một hoặc nhiều người phụ trách chịu trách nhiệm về nội dung, rà soát và biên tập bản dịch. Tuy nhiên, mỗi chương có thể có nhiều người đóng góp.

## Quy trình làm việc

- Sách được viết bằng file [Quarto Markdown](https://quarto.org/docs/authoring/markdown-basics.html) (`.qmd`), dịch từ file R Markdown (`.Rmd`) gốc.
- Cài [Quarto CLI](https://quarto.org/docs/get-started/) để render và xem trước cục bộ bằng lệnh `quarto render` hoặc `quarto preview`.
- Tạo pull request về repo GitHub này.
- Khi pull request được chấp nhận và merge vào `main`, sách sẽ được cập nhật tự động trên trang xuất bản.

## Lưu ý khi dịch

- Giữ nguyên thuật ngữ kỹ thuật/tên riêng khi chưa có bản dịch tiếng Việt chuẩn (ví dụ: `cohort`, `concept set`, tên các công cụ OHDSI như ATLAS, ACHILLES...). Có thể chú thích tiếng Anh trong ngoặc khi cần.
- Đối chiếu với bản gốc tương ứng trong [OHDSI/TheBookOfOhdsi](https://github.com/OHDSI/TheBookOfOhdsi) để đảm bảo nội dung không bị sai lệch hoặc lạc hậu so với bản gốc.
- Hyperlink nên hiển thị URL thực để khi in ra vẫn đọc được đường link.
- Bảng và hình nên được thiết kế phù hợp với màn hình nhỏ.
- Tên file/phần mở rộng nên viết thường, ví dụ `hinh.png` chứ không phải `hinh.PNG`.
- Nhãn (label) của code chunk chỉ nên dùng ký tự chữ và số, ví dụ ` ```{r figure1} ` chứ không phải ` ```{r figure_1} `.
- Bảng và danh sách chỉ render đúng khi có một dòng trống phía trước.

# Mục lục sách

[Lời tựa](index.qmd)

**Phần I — Cộng đồng OHDSI**
- [Chương 1: Cộng đồng OHDSI](01_community.qmd)
- [Chương 2: Nơi bắt đầu](02_where_to_begin.qmd)
- [Chương 3: Khoa học mở](03_open_science.qmd)

**Phần II — Chuẩn hóa Dữ liệu**
- [Chương 4: Mô hình Dữ liệu Chung (CDM)](04_cdm.qmd)
- [Chương 5: Từ vựng Chuẩn hóa](05_vocabularies.qmd)
- [Chương 6: Trích xuất - Chuyển đổi - Nạp (ETL)](06_etl.qmd)

**Phần III — Phân tích Dữ liệu**
- [Chương 7: Các trường hợp sử dụng phân tích](07_use_cases.qmd)
- [Chương 8: Công cụ phân tích OHDSI](08_tools.qmd)
- [Chương 9: SQL và R](09_sql_and_r.qmd)
- [Chương 10: Định nghĩa nhóm thuần tập](10_cohort_definitions.qmd)
- [Chương 11: Đặc điểm hóa](11_characterization.qmd)
- [Chương 12: Ước tính cấp độ quần thể](12_population_level_estimation.qmd)
- [Chương 13: Dự đoán cấp độ bệnh nhân](13_patient_level_prediction.qmd)

**Phần IV — Chất lượng Bằng chứng**
- [Chương 14: Chất lượng dữ liệu](14_data_quality.qmd)
- [Chương 15: Tính hợp lệ lâm sàng](15_clinical_validity.qmd)
- [Chương 16: Tính hợp lệ của phần mềm](16_software_validity.qmd)
- [Chương 17: Tính hợp lệ của phương pháp](17_method_validity.qmd)

**Phần V — Các nghiên cứu OHDSI**
- [Chương 18: Các bước nghiên cứu](18_study_steps.qmd)
- [Chương 19: Nghiên cứu mạng lưới OHDSI](19_network_studies.qmd)

**Phần VI — Phụ lục & Tài liệu tham khảo**
- [Bảng thuật ngữ](20_glossary.qmd)
- [Phụ lục A: Định nghĩa nhóm thuần tập](21_cohort_definitions_appendix.qmd)
- [Phụ lục B: Các đối chứng âm tính](22_negative_controls.qmd)
- [Phụ lục C: Mẫu giao thức](23_protocol_template.qmd)
- [Phụ lục D: Gợi ý trả lời](24_hints.qmd)
- [Thư mục tài liệu tham khảo & Chỉ mục](25_references_and_index.qmd)

# Quy tắc ứng xử

**Chuyển thể từ Contributor Covenant, phiên bản 1.4**

Với tinh thần xây dựng một môi trường cởi mở và chào đón, chúng tôi — những người đóng góp và duy trì dự án — cam kết làm cho việc tham gia vào dự án và cộng đồng của chúng tôi trở thành trải nghiệm không có sự quấy rối cho tất cả mọi người, bất kể tuổi tác, ngoại hình, khuyết tật, dân tộc, bản dạng và biểu hiện giới, trình độ kinh nghiệm, quốc tịch, ngoại hình cá nhân, chủng tộc, tôn giáo, hoặc bản dạng và xu hướng tính dục.

## Tiêu chuẩn của chúng tôi

Các hành vi góp phần tạo ra môi trường tích cực bao gồm:

- Sử dụng ngôn ngữ chào đón và hòa nhập
- Tôn trọng các quan điểm và trải nghiệm khác biệt
- Chấp nhận góp ý mang tính xây dựng một cách cởi mở
- Tập trung vào những gì tốt nhất cho cộng đồng
- Thể hiện sự đồng cảm với các thành viên khác trong cộng đồng

Các hành vi không được chấp nhận bao gồm: ngôn ngữ hoặc hình ảnh mang tính khiêu dâm và sự chú ý/tiếp cận tình dục không mong muốn; công kích, xúc phạm/bình luận hạ thấp, và tấn công cá nhân hoặc chính trị; quấy rối công khai hoặc riêng tư; công bố thông tin cá nhân của người khác (địa chỉ vật lý hoặc điện tử) mà không có sự cho phép rõ ràng; hoặc các hành vi khác có thể được coi là không phù hợp trong môi trường chuyên nghiệp.

## Trách nhiệm của chúng tôi

Người duy trì dự án có trách nhiệm làm rõ các tiêu chuẩn về hành vi được chấp nhận và được kỳ vọng sẽ thực hiện các hành động khắc phục phù hợp và công bằng đối với bất kỳ hành vi không được chấp nhận nào.

## Phạm vi áp dụng

Quy tắc ứng xử này áp dụng cả trong không gian dự án lẫn không gian công cộng khi một cá nhân đại diện cho dự án hoặc cộng đồng của dự án.

## Thực thi

Các trường hợp hành vi lạm dụng, quấy rối, hoặc không được chấp nhận khác có thể được báo cáo bằng cách liên hệ với đội ngũ dự án qua kênh cộng đồng OHDSI Việt Nam hoặc [OHDSI Forums](https://forums.ohdsi.org/). Tất cả khiếu nại sẽ được xem xét và điều tra, dẫn đến phản hồi được cho là cần thiết và phù hợp với hoàn cảnh.

## Ghi công

Quy tắc ứng xử này được chuyển thể từ Contributor Covenant, phiên bản 1.4, có tại http://contributor-covenant.org/version/1/4
