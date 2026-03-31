# R cho Khoa học Dữ liệu

<!-- badges: start -->

[![Render and Deploy Book](https://github.com/quan-nk/r4ds-vi/actions/workflows/build_book.yaml/badge.svg)](https://github.com/quan-nk/r4ds-vi/actions/workflows/build_book.yaml)

<!-- badges: end -->

<img src="cover.jpg" alt="Bìa sách R cho Khoa học Dữ liệu" width="250"/>

Repository này chứa mã nguồn của cuốn sách "R cho Khoa học Dữ liệu" của Hadley Wickham, Mine Çetinkaya-Rundel & Garrett Grolemund. Cuốn sách được xây dựng bằng [Quarto](https://quarto.org/). Cuốn sách này sẽ dạy bạn cách thực hiện khoa học dữ liệu với R: bạn sẽ học cách đưa dữ liệu vào R, chuyển đổi nó sang cấu trúc hữu ích nhất, biến đổi và trực quan hóa.

Trong cuốn sách này, bạn sẽ tìm thấy các bài thực hành kỹ năng khoa học dữ liệu. Cũng như một nhà hóa học học cách rửa ống nghiệm và chuẩn bị phòng thí nghiệm, bạn sẽ học cách làm sạch dữ liệu và vẽ biểu đồ — và nhiều thứ khác nữa. Đây là những kỹ năng cho phép khoa học dữ liệu tồn tại, và ở đây bạn sẽ tìm thấy các phương pháp tốt nhất để thực hiện từng việc đó với R. Bạn sẽ học cách sử dụng ngữ pháp đồ thị, lập trình có chú giải và nghiên cứu có thể tái tạo để tiết kiệm thời gian. Bạn cũng sẽ học cách quản lý nguồn lực nhận thức để hỗ trợ việc khám phá khi xử lý, trực quan hóa và khảo sát dữ liệu.

## Về bản dịch

Bản dịch tiếng Việt của "R cho Khoa học Dữ liệu" là dự án cá nhân của [Nguyễn Khởi Quân](https://github.com/quan-nk) với mục tiêu giúp việc học Khoa học Dữ liệu với R trở nên dễ tiếp cận hơn với người đọc tiếng Việt.

Lưu ý rằng đây là bản dịch của cuốn sách gốc, vì vậy khi các tác giả đề cập đến bản thân theo ngôi thứ nhất, đó là Hadley Wickham, Mine Çetinkaya-Rundel & Garrett Grolemund, không phải người dịch.

Nếu bạn phát hiện lỗi liên quan đến nội dung bản dịch, hãy [mở một issue](https://github.com/quan-nk/r4ds-vi/issues) hoặc [gửi pull request](https://github.com/quan-nk/r4ds-vi/pulls) trên repository này. Bạn cũng có thể liên hệ trực tiếp qua [email](mailto:nguyenkhoiquan@gmail.com).

## Về các phiên bản khác

- **Tiếng Anh (bản gốc):** [R for Data Science](https://r4ds.hadley.nz/)
- **Tiếng Tây Ban Nha:** [R para la Ciencia de Datos](https://es.r4ds.hadley.nz/)
- **Tiếng Thổ Nhĩ Kỳ:** [R for Data Science](https://tr.r4ds.hadley.nz/)
- **Tiếng Ý:** [R for Data Science - edizione italiana](https://it.r4ds.hadley.nz/)

## Bảng thuật ngữ

Tài liệu tham khảo cho bản dịch. Sử dụng tiếng Việt trước, tiếng Anh trong ngoặc đơn ở lần xuất hiện đầu tiên trong mỗi chương.

### Quy tắc chung

- Tên hàm R: KHÔNG dịch (`filter()`, `mutate()`, `ggplot()`)
- Tên gói R: KHÔNG dịch (`tidyverse`, `dplyr`, `ggplot2`)
- Tên tập dữ liệu: KHÔNG dịch (`flights`, `penguins`, `diamonds`)
- Tên cột/biến trong tập dữ liệu có sẵn: KHÔNG dịch (`carat`, `species`, `dep_delay`)
- Chú thích trong code: LUÔN dịch sang tiếng Việt

### Danh sách thuật ngữ

| English | Tiếng Việt | Ghi chú |
|---------|-----------|---------|
| argument | đối số | |
| assignment | phép gán | |
| aesthetic | thuộc tính thẩm mỹ (aesthetic) | Giữ "aesthetic" trong ngữ cảnh ggplot2 |
| bar chart | biểu đồ cột | |
| box plot | biểu đồ hộp | |
| chunk | khối mã | |
| column | cột | |
| console | bảng điều khiển (console) | |
| coordinate | hệ tọa độ | |
| data frame | khung dữ liệu (data frame) | |
| data science | khoa học dữ liệu | |
| dataset | tập dữ liệu | |
| double | số thực (double) | |
| environment | môi trường (environment) | |
| exercise | bài tập | |
| facet | facet | Giữ nguyên trong ngữ cảnh ggplot2 |
| factor | nhân tố (factor) | |
| filter | lọc | |
| function | hàm | |
| geom | geom | KHÔNG dịch (thuật ngữ ggplot2) |
| group by | nhóm theo | |
| histogram | biểu đồ tần suất | |
| import | nhập (dữ liệu) | |
| integer | số nguyên (integer) | |
| iteration | lặp | |
| join | nối (join) | |
| layer | lớp (layer) | |
| library | thư viện | |
| list | danh sách (list) | |
| logical | giá trị logic (logical) | |
| mapping | ánh xạ (mapping) | |
| missing value | giá trị khuyết (missing value) | |
| model | mô hình | |
| mutate | tạo biến mới / mutate | Giữ "mutate" khi nói về hàm |
| observation | quan sát | |
| package | gói (package) | |
| pipe | toán tử pipe | Giữ "pipe" |
| pivot | xoay (pivot) | |
| plot | biểu đồ | |
| prerequisite | điều kiện tiên quyết | |
| programming | lập trình | |
| recursion | đệ quy | |
| regular expression | biểu thức chính quy (regular expression) | |
| render | biên dịch (render) | |
| repository | kho lưu trữ (repository) | |
| row | hàng | |
| scale | thang đo (scale) | |
| scatter plot | biểu đồ phân tán | |
| script | tập lệnh (script) | |
| select | chọn | |
| string | chuỗi ký tự (string) | |
| summarize | tóm tắt | |
| tibble | tibble | KHÔNG dịch |
| tidy data | dữ liệu gọn gàng (tidy data) | |
| transformation | biến đổi | |
| value | giá trị | |
| variable | biến | |
| vector | vector | Giữ nguyên |
| visualization | trực quan hóa | |
| workspace | không gian làm việc (workspace) | |
| wrangle | xử lý dữ liệu (wrangle) | |

## Hình ảnh

### Bản vẽ Omnigraffle

-   Font: 12pt Guardian Sans Condensed / Ubuntu mono

-   Export dưới dạng png 300 dpi.

-   Font trên website là 18 px = 13.5 pt, nên điều chỉnh dpi để khớp kích thước font: 270 = 300 \* 12 / 13.5.
    (Tôi cũng đã xác minh thực nghiệm bằng cách chụp màn hình.)

    ``` r
    #| echo: FALSE
    #| out.width: NULL
    knitr::include_graphics("diagrams/transform.png", dpi = 270)
    ```

### Chụp màn hình

-   Đảm bảo bạn đang sử dụng giao diện sáng (light theme).
    Đối với các phần tử giao diện nhỏ (ví dụ thanh công cụ), zoom in hai lần.

-   Chụp màn hình bằng Cmd + Shift + 4.

-   Không cần đặt dpi:

    ``` r
    #| echo: FALSE
    #| out.width: NULL
    knitr::include_graphics("screenshots/rstudio-wg.png")
    ```

## O'Reilly

Để tạo sách cho O'Reilly, build sách rồi:

```{r}
# pak::pak("hadley/htmlbook")
htmlbook::convert_book()

html <- list.files("oreilly", pattern = "[.]html$", full.names = TRUE)
file.copy(html, "../r-for-data-science-2e/", overwrite = TRUE)

pngs <- list.files("oreilly", pattern = "[.]png$", full.names = TRUE, recursive = TRUE)
dest <- gsub("oreilly", "../r-for-data-science-2e/", pngs)
fs::dir_create(unique(dirname(dest)))
file.copy(pngs, dest, overwrite = TRUE)
```

Sau đó commit và push lên atlas.

## Quy tắc ứng xử

Lưu ý rằng r4ds tuân theo [Quy tắc Ứng xử của Người Đóng góp](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html).
Bằng việc đóng góp cho cuốn sách này, bạn đồng ý tuân thủ các điều khoản của nó.
