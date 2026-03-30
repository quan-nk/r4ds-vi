# R cho Khoa học Dữ liệu

<!-- badges: start -->

[![Render and deploy Book to Netlify](https://github.com/hadley/r4ds/actions/workflows/build_book.yaml/badge.svg)](https://github.com/hadley/r4ds/actions/workflows/build_book.yaml)

<!-- badges: end -->

Repository này chứa mã nguồn của cuốn sách [R for Data Science](http://r4ds.hadley.nz).
Cuốn sách được xây dựng bằng [Quarto](https://quarto.org/).

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

### O'Reilly

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
