# Sách OHDSI - Bản tiếng Việt (The Book of OHDSI - Vietnamese Edition)

Đây là bản dịch tiếng Việt của [The Book of OHDSI](https://github.com/OHDSI/TheBookOfOhdsi), tài liệu chính thức của cộng đồng OHDSI (Observational Health Data Sciences and Informatics) về khoa học dữ liệu y tế quan sát và tin học mạng lưới. Bản gốc tiếng Anh được xuất bản tại [book.ohdsi.org](https://ohdsi.github.io/TheBookOfOhdsi/).

Dự án này được thực hiện bởi Cộng đồng OHDSI Việt Nam nhằm giúp cộng đồng nghiên cứu và y tế trong nước tiếp cận dễ dàng hơn với các khái niệm, công cụ và quy trình của OHDSI.

## Đọc sách trực tuyến

Bản dịch được build bằng [Quarto](https://quarto.org/) và xuất bản tại: https://thanh-phuc.github.io/the-book-of-ohdsi-vi/

## Cấu trúc dự án

Sách được viết bằng các file `.qmd` (Quarto Markdown), mỗi file tương ứng với một chương:

| File | Nội dung |
|---|---|
| `index.qmd` | Lời tựa & Giới thiệu |
| `01_community.qmd` – `03_open_science.qmd` | Phần I — Cộng đồng OHDSI |
| `04_cdm.qmd` – `06_etl.qmd` | Phần II — Chuẩn hóa Dữ liệu |
| `07_use_cases.qmd` – `13_patient_level_prediction.qmd` | Phần III — Phân tích Dữ liệu |
| `14_data_quality.qmd` – `17_method_validity.qmd` | Phần IV — Chất lượng Bằng chứng |
| `18_study_steps.qmd` – `19_network_studies.qmd` | Phần V — Các nghiên cứu OHDSI |
| `20_glossary.qmd` – `25_references_and_index.qmd` | Phần VI — Phụ lục & Tài liệu tham khảo |

Cấu hình build và mục lục nằm trong [`_quarto.yml`](_quarto.yml).

## Build cục bộ

Yêu cầu đã cài [Quarto CLI](https://quarto.org/docs/get-started/).

```bash
quarto render
```

Kết quả HTML sẽ được xuất ra thư mục `docs/`.

## Đóng góp

Xem hướng dẫn đóng góp tại [contributing.md](contributing.md).

## Giấy phép

Theo bản gốc, nội dung dịch được phát hành dưới giấy phép [CC0 1.0 Universal](LICENSE) — miền công cộng (public domain).

## Ghi nhận

- Bản gốc tiếng Anh: [OHDSI/TheBookOfOhdsi](https://github.com/OHDSI/TheBookOfOhdsi), thực hiện bởi Cộng đồng OHDSI toàn cầu.
- Bản dịch tiếng Việt: Cộng đồng OHDSI Việt Nam.

## Người phụ trách bản dịch tiếng Việt

**Phan Thanh-Phuc, PhD**
University Medical Center Ho Chi Minh City, Viet Nam
Email: phanthahphuc@ohdsi.org
