# Danh sách Thuật ngữ Kỹ thuật - R4DS Tiếng Việt

## ✅ QUYẾT ĐỊNH ĐÃ THỰC HIỆN

**User decision (2026-03-30)**: "giữ tất cả trong tiếng anh" - Keep ALL technical terms in English.

**Implementation status**: ✅ COMPLETED - All ~3,498 replacements done across 7 batches.

Tất cả thuật ngữ kỹ thuật trong bản dịch R4DS tiếng Việt hiện đã sử dụng tiếng Anh.

## Chú giải
- **Tình trạng hiện tại**: Cách thuật ngữ đang được sử dụng trong bản dịch
- **Số lần xuất hiện**: Ước tính dựa trên grep search
- **Khuyến nghị**: Đề xuất ban đầu (cần chuyên gia quyết định cuối cùng)

---

## 1. CẤU TRÚC DỮ LIỆU (Data Structures)

### 1.1 Package
- **Tiếng Anh**: package
- **Tiếng Việt hiện tại**: gói mở rộng
- **Số lần xuất hiện**: ~100+ (đã thay thế từ "gói")
- **Ví dụ**: "Gói mở rộng tidyverse bao gồm nhiều gói mở rộng con..."
- **Khuyến nghị**: CẦN QUYẾT ĐỊNH - Có nên giữ "package" tiếng Anh không?
- **Lý do**: Thuật ngữ cơ bản, cộng đồng R Việt Nam đã quen với "package"

### 1.2 Data frame
- **Tiếng Anh**: data frame
- **Tiếng Việt hiện tại**: khung dữ liệu
- **Số lần xuất hiện**: ~200+
- **Ví dụ**: "Khung dữ liệu là cấu trúc dữ liệu cơ bản trong R..."
- **Tình trạng**: Dịch nhất quán
- **Khuyến nghị**: TIẾP TỤC DỊCH - Thuật ngữ này dễ hiểu và tự nhiên trong tiếng Việt

### 1.3 Tibble
- **Tiếng Anh**: tibble
- **Tiếng Việt hiện tại**: tibble (giữ nguyên)
- **Số lần xuất hiện**: ~50+
- **Tình trạng**: Giữ nguyên tiếng Anh
- **Khuyến nghị**: GIỮ NGUYÊN - Tên riêng của một kiểu dữ liệu cụ thể

### 1.4 Vector
- **Tiếng Anh**: vector
- **Tiếng Việt hiện tại**: vector (giữ nguyên)
- **Số lần xuất hiện**: ~150+
- **Tình trạng**: Giữ nguyên tiếng Anh
- **Khuyến nghị**: GIỮ NGUYÊN - Thuật ngữ toán học chuẩn

### 1.5 List
- **Tiếng Anh**: list
- **Tiếng Việt hiện tại**: danh sách
- **Số lần xuất hiện**: ~100+
- **Ví dụ**: "Danh sách là cấu trúc dữ liệu linh hoạt..."
- **Tình trạng**: Dịch nhất quán
- **Khuyến nghị**: CẦN QUYẾT ĐỊNH - "list" hay "danh sách"?

---

## 2. GGPLOT2 VÀ TRỰC QUAN HÓA (ggplot2 & Visualization)

### 2.1 Aesthetic / Aesthetic mapping
- **Tiếng Anh**: aesthetic, aesthetic mapping
- **Tiếng Việt hiện tại**: KHÔNG NHẤT QUÁN
  - Phần lớn: aesthetic (giữ nguyên)
  - Một số: thẩm mỹ, thuộc tính thẩm mỹ
  - Phổ biến: thuộc tính đồ họa, ánh xạ thuộc tính đồ họa
- **Số lần xuất hiện**: ~100+
- **Ví dụ**:
  - "Đối số mapping định nghĩa ánh xạ đến các thuộc tính đồ họa (aesthetic)"
  - "Thuộc tính thẩm mỹ này nhận giá trị từ 0 đến 1"
- **Tình trạng**: KHÔNG NHẤT QUÁN - Cần chuẩn hóa
- **Khuyến nghị**: CẦN QUYẾT ĐỊNH QUAN TRỌNG
  - Option A: Giữ "aesthetic" tiếng Anh
  - Option B: Dịch thống nhất là "thuộc tính đồ họa"
  - Option C: Dịch thống nhất là "thuộc tính thẩm mỹ"

### 2.2 Geom (geometric object)
- **Tiếng Anh**: geom
- **Tiếng Việt hiện tại**:
  - Trong tên hàm: geom_point(), geom_bar() (giữ nguyên)
  - Trong văn bản: đối tượng đồ họa (geoms)
- **Số lần xuất hiện**: ~150+
- **Tình trạng**: Mixed - giữ trong code, dịch trong văn bản
- **Khuyến nghị**: CẦN QUYẾT ĐỊNH
  - Giữ "geom" trong cả văn bản?
  - Hay tiếp tục dùng "đối tượng đồ họa" khi giải thích?

### 2.3 Facet
- **Tiếng Anh**: facet, faceting
- **Tiếng Việt hiện tại**: facet (giữ nguyên trong hầu hết trường hợp)
- **Số lần xuất hiện**: ~60+
- **Tình trạng**: Giữ nguyên
- **Khuyến nghị**: GIỮ NGUYÊN

### 2.4 Layer
- **Tiếng Anh**: layer
- **Tiếng Việt hiện tại**: lớp (layer)
- **Số lần xuất hiện**: ~15+
- **Tình trạng**: Dịch
- **Khuyến nghị**: TIẾP TỤC DỊCH - "lớp" tự nhiên trong tiếng Việt

### 2.5 Scale
- **Tiếng Anh**: scale
- **Tiếng Việt hiện tại**: thang đo (đôi khi tỷ lệ)
- **Số lần xuất hiện**: ~150+
- **Ví dụ**: "Thang đo kiểm soát cách ánh xạ aesthetic hiển thị"
- **Tình trạng**: Dịch
- **Khuyến nghị**: TIẾP TỤC DỊCH - "thang đo" phù hợp

### 2.6 Theme
- **Tiếng Anh**: theme
- **Tiếng Việt hiện tại**: chủ đề
- **Số lần xuất hiện**: ~70+
- **Tình trạng**: Dịch
- **Khuyến nghị**: TIẾP TỤC DỊCH

### 2.7 Mapping
- **Tiếng Anh**: mapping
- **Tiếng Việt hiện tại**: ánh xạ
- **Số lần xuất hiện**: ~95+
- **Tình trạng**: Dịch nhất quán
- **Khuyến nghị**: TIẾP TỤC DỊCH - Thuật ngữ toán học có bản dịch chuẩn

### 2.8 Coordinate system
- **Tiếng Anh**: coordinate, coordinate system
- **Tiếng Việt hiện tại**: tọa độ, hệ tọa độ
- **Số lần xuất hiện**: ~15+
- **Tình trạng**: Dịch
- **Khuyến nghị**: TIẾP TỤC DỊCH

### 2.9 Stat
- **Tiếng Anh**: stat, statistical transformation
- **Tiếng Việt hiện tại**: Giữ "stat" trong tên hàm, dịch trong văn bản
- **Số lần xuất hiện**: ~90+
- **Khuyến nghị**: CẦN QUYẾT ĐỊNH

---

## 3. LẬP TRÌNH (Programming)

### 3.1 Function
- **Tiếng Anh**: function
- **Tiếng Việt hiện tại**: hàm
- **Số lần xuất hiện**: ~500+
- **Tình trạng**: Dịch nhất quán
- **Khuyến nghị**: TIẾP TỤC DỊCH - Thuật ngữ chuẩn trong lập trình

### 3.2 Argument
- **Tiếng Anh**: argument
- **Tiếng Việt hiện tại**: đối số
- **Số lần xuất hiện**: ~300+
- **Tình trạng**: Dịch nhất quán
- **Khuyến nghị**: TIẾP TỤC DỊCH - Thuật ngữ chuẩn

### 3.3 Parameter
- **Tiếng Anh**: parameter
- **Tiếng Việt hiện tại**: tham số
- **Số lần xuất hiện**: ~100+
- **Tình trạng**: Dịch nhất quán
- **Khuyến nghị**: TIẾP TỤC DỊCH - Thuật ngữ chuẩn

### 3.4 Pipe operator
- **Tiếng Anh**: pipe, pipe operator
- **Tiếng Việt hiện tại**: toán tử pipe (pipe)
- **Số lần xuất hiện**: ~50+
- **Ví dụ**: "toán tử pipe (pipe), một công cụ quan trọng..."
- **Tình trạng**: Mixed - giữ "pipe" + giải thích "toán tử pipe"
- **Khuyến nghị**: CẦN QUYẾT ĐỊNH
  - Giữ "pipe" hoàn toàn?
  - Hay dùng "toán tử pipe" rồi viết "pipe" từ lần sau?

### 3.5 Environment
- **Tiếng Anh**: environment
- **Tiếng Việt hiện tại**: môi trường
- **Số lần xuất hiện**: ~15+
- **Tình trạng**: Dịch
- **Khuyến nghị**: TIẾP TỤC DỊCH

### 3.6 Script
- **Tiếng Anh**: script
- **Tiếng Việt hiện tại**: kịch bản (script)
- **Số lần xuất hiện**: ~30+
- **Tình trạng**: Dịch nhưng giữ tiếng Anh trong ngoặc
- **Khuyến nghị**: CẦN QUYẾT ĐỊNH - "script" hay "kịch bản"?

### 3.7 Console
- **Tiếng Anh**: console
- **Tiếng Việt hiện tại**: bảng điều khiển
- **Số lần xuất hiện**: ~30+
- **Tình trạng**: Dịch
- **Khuyến nghị**: TIẾP TỤC DỊCH

### 3.8 Comment
- **Tiếng Anh**: comment
- **Tiếng Việt hiện tại**: chú thích
- **Số lần xuất hiện**: ~55+
- **Tình trạng**: Dịch
- **Khuyến nghị**: TIẾP TỤC DỊCH

### 3.9 Loop
- **Tiếng Anh**: loop, for loop
- **Tiếng Việt hiện tại**: vòng lặp
- **Số lần xuất hiện**: ~15+
- **Tình trạng**: Dịch
- **Khuyến nghị**: TIẾP TỤC DỊCH

### 3.10 Iteration / Iterate
- **Tiếng Anh**: iterate, iteration
- **Tiếng Việt hiện tại**: lặp
- **Số lần xuất hiện**: ~85+
- **Tình trạng**: Dịch
- **Khuyến nghị**: TIẾP TỤC DỊCH

---

## 4. KIỂU DỮ LIỆU (Data Types)

### 4.1 String
- **Tiếng Anh**: string, character
- **Tiếng Việt hiện tại**: chuỗi (string), chuỗi ký tự
- **Số lần xuất hiện**: ~300+
- **Tình trạng**: Dịch
- **Khuyến nghị**: TIẾP TỤC DỊCH - "chuỗi" tự nhiên và ngắn gọn

### 4.2 Numeric / Number
- **Tiếng Anh**: numeric, number
- **Tiếng Việt hiện tại**: số
- **Số lần xuất hiện**: ~200+
- **Tình trạng**: Dịch
- **Khuyến nghị**: TIẾP TỤC DỊCH

### 4.3 Logical / Boolean
- **Tiếng Anh**: logical, boolean
- **Tiếng Việt hiện tại**: logic (logical)
- **Số lần xuất hiện**: ~150+
- **Tình trạng**: Giữ "logic" hoặc "logical"
- **Khuyến nghị**: GIỮ NGUYÊN - Thuật ngữ lập trình chuẩn

### 4.4 Factor
- **Tiếng Anh**: factor
- **Tiếng Việt hiện tại**: nhân tố (factor)
- **Số lần xuất hiện**: ~100+
- **Tình trạng**: Dịch
- **Khuyến nghị**: CẦN QUYẾT ĐỊNH
  - "factor" (giữ nguyên)?
  - "nhân tố" (tiếp tục dịch)?

### 4.5 Date / Datetime
- **Tiếng Anh**: date, datetime, date-time
- **Tiếng Việt hiện tại**: ngày, ngày-giờ
- **Số lần xuất hiện**: ~150+
- **Tình trạng**: Dịch
- **Khuyến nghị**: TIẾP TỤC DỊCH

### 4.6 Missing value
- **Tiếng Anh**: missing value, NA
- **Tiếng Việt hiện tại**: giá trị khuyết
- **Số lần xuất hiện**: ~85+
- **Tình trạng**: Dịch
- **Khuyến nghị**: TIẾP TỤC DỊCH - Tự nhiên và chính xác

---

## 5. THAO TÁC DỮ LIỆU (Data Manipulation)

### 5.1 Column / Row
- **Tiếng Anh**: column, row
- **Tiếng Việt hiện tại**: cột, hàng
- **Số lần xuất hiện**: ~400+ (column), ~390+ (row)
- **Tình trạng**: Dịch nhất quán
- **Khuyến nghị**: TIẾP TỤC DỊCH - Cơ bản và tự nhiên

### 5.2 Filter
- **Tiếng Anh**: filter
- **Tiếng Việt hiện tại**:
  - Tên hàm: `filter()` (giữ nguyên)
  - Văn bản: lọc
- **Số lần xuất hiện**: ~200+
- **Tình trạng**: Giữ tên hàm, dịch động từ
- **Khuyến nghị**: TIẾP TỤC DỊCH động từ "lọc"

### 5.3 Mutate
- **Tiếng Anh**: mutate
- **Tiếng Việt hiện tại**:
  - Tên hàm: `mutate()` (giữ nguyên)
  - Văn bản: biến đổi (nhưng có thể nhầm với "transform")
- **Số lần xuất hiện**: ~225+
- **Tình trạng**: Giữ tên hàm
- **Khuyến nghị**: CẦN QUYẾT ĐỊNH - Cách giải thích `mutate()` trong văn bản

### 5.4 Summarize / Summarise
- **Tiếng Anh**: summarize, summarise
- **Tiếng Việt hiện tại**:
  - Tên hàm: `summarize()` (giữ nguyên)
  - Văn bản: tóm tắt
- **Số lần xuất hiện**: ~210+
- **Tình trạng**: Giữ tên hàm, dịch động từ
- **Khuyến nghị**: TIẾP TỤC DỊCH động từ "tóm tắt"

### 5.5 Join
- **Tiếng Anh**: join (inner join, left join, etc.)
- **Tiếng Việt hiện tại**: nối
- **Số lần xuất hiện**: ~240+
- **Tình trạng**: Dịch
- **Khuyến nghị**: TIẾP TỤC DỊCH - "nối" tự nhiên

### 5.6 Transform
- **Tiếng Anh**: transform, transformation
- **Tiếng Việt hiện tại**: biến đổi
- **Số lần xuất hiện**: ~95+
- **Tình trạng**: Dịch
- **Khuyến nghị**: TIẾP TỤC DỊCH

### 5.7 Wrangle
- **Tiếng Anh**: wrangle, data wrangling
- **Tiếng Việt hiện tại**: xử lý (dữ liệu)
- **Số lần xuất hiện**: ~65+
- **Tình trạng**: Dịch
- **Khuyến nghị**: TIẾP TỤC DỊCH

---

## 6. KHÁI NIỆM KHOA HỌC DỮ LIỆU (Data Science Concepts)

### 6.1 Tidy data
- **Tiếng Anh**: tidy data
- **Tiếng Việt hiện tại**: dữ liệu gọn gàng, dữ liệu gọn
- **Số lần xuất hiện**: ~25+
- **Tình trạng**: Dịch
- **Khuyến nghị**: CẦN QUYẾT ĐỊNH
  - Giữ "tidy data"?
  - Hay tiếp tục dùng "dữ liệu gọn"?

### 6.2 Visualization
- **Tiếng Anh**: visualization, data visualization
- **Tiếng Việt hiện tại**: trực quan hóa
- **Số lần xuất hiện**: ~140+
- **Tình trạng**: Dịch
- **Khuyến nghị**: TIẾP TỤC DỊCH - Thuật ngữ chuẩn

### 6.3 Workflow
- **Tiếng Anh**: workflow
- **Tiếng Việt hiện tại**: quy trình (làm việc)
- **Số lần xuất hiện**: ~45+
- **Tình trạng**: Dịch
- **Khuyến nghị**: TIẾP TỤC DỊCH

### 6.4 Import / Export
- **Tiếng Anh**: import, export
- **Tiếng Việt hiện tại**: nhập, xuất
- **Số lần xuất hiện**: ~75+
- **Tình trạng**: Dịch
- **Khuyến nghị**: TIẾP TỤC DỊCH

### 6.5 Spreadsheet
- **Tiếng Anh**: spreadsheet
- **Tiếng Việt hiện tại**: bảng tính
- **Số lần xuất hiện**: ~70+
- **Tình trạng**: Dịch
- **Khuyến nghị**: TIẾP TỤC DỊCH - Thuật ngữ phổ thông

### 6.6 Database
- **Tiếng Anh**: database
- **Tiếng Việt hiện tại**: cơ sở dữ liệu
- **Số lần xuất hiện**: ~80+
- **Tình trạng**: Dịch
- **Khuyến nghị**: TIẾP TỤC DỊCH - Thuật ngữ chuẩn

### 6.7 Regular expression
- **Tiếng Anh**: regular expression, regex
- **Tiếng Việt hiện tại**: biểu thức chính quy
- **Số lần xuất hiện**: ~55+
- **Tình trạng**: Dịch
- **Khuyến nghị**: TIẾP TỤC DỊCH - Thuật ngữ có bản dịch chuẩn

---

## 7. THUẬT NGỮ CẦN QUYẾT ĐỊNH ƯU TIÊN CAO

### Danh sách các thuật ngữ CẦN quyết định ngay:

1. **package** - Hiện dịch: "gói mở rộng"
   - Ảnh hưởng: ~100+ lần xuất hiện
   - Đề xuất: Giữ "package" tiếng Anh

2. **aesthetic** - KHÔNG NHẤT QUÁN (aesthetic / thẩm mỹ / thuộc tính đồ họa)
   - Ảnh hưởng: ~100+ lần xuất hiện
   - Đề xuất: CẦN CHUẨN HÓA NGAY
   - Options:
     - A: Giữ "aesthetic"
     - B: "thuộc tính đồ họa" nhất quán
     - C: "thuộc tính thẩm mỹ" nhất quán

3. **geom** - Hiện: giữ trong code, dịch "đối tượng đồ họa" trong văn bản
   - Ảnh hưởng: ~150+ lần xuất hiện
   - Đề xuất: Quyết định cách giải thích trong văn bản

4. **pipe** - Hiện: "toán tử pipe"
   - Ảnh hưởng: ~50+ lần xuất hiện
   - Đề xuất: Giữ "pipe" hoàn toàn

5. **tidy data** - Hiện: "dữ liệu gọn"
   - Ảnh hưởng: ~25+ lần xuất hiện
   - Đề xuất: Giữ "tidy data" hoặc quyết định rõ ràng

6. **factor** - Hiện: "nhân tố"
   - Ảnh hưởng: ~100+ lần xuất hiện
   - Đề xuất: Giữ "factor"

7. **script** - Hiện: "kịch bản"
   - Ảnh hưởng: ~30+ lần xuất hiện
   - Đề xuất: Giữ "script"

8. **list** - Hiện: "danh sách"
   - Ảnh hưởng: ~100+ lần xuất hiện
   - Đề xuất: Cần quyết định

---

## 8. THUẬT NGỮ NÊN TIẾP TỤC DỊCH (Đồng thuận cao)

Các thuật ngữ sau đã được dịch tốt và nên TIẾP TỤC DỊCH:

1. **data frame** → khung dữ liệu
2. **function** → hàm
3. **argument** → đối số
4. **parameter** → tham số
5. **string** → chuỗi (ký tự)
6. **column/row** → cột/hàng
7. **missing value** → giá trị khuyết
8. **database** → cơ sở dữ liệu
9. **spreadsheet** → bảng tính
10. **visualization** → trực quan hóa
11. **regular expression** → biểu thức chính quy
12. **filter** (động từ) → lọc
13. **join** → nối
14. **scale** → thang đo
15. **theme** → chủ đề

---

## 9. THUẬT NGỮ NÊN GIỮ NGUYÊN TIẾNG ANH (Đồng thuận cao)

Các thuật ngữ sau nên GIỮ NGUYÊN tiếng Anh:

1. **tibble** - Tên riêng
2. **vector** - Thuật ngữ toán học chuẩn
3. **logical** - Kiểu dữ liệu chuẩn
4. **facet** - Thuật ngữ ggplot2
5. **NA** - Ký hiệu chuẩn

---

## HƯỚNG DẪN CHO CHUYÊN GIA HIỆU ĐÍNH

Vui lòng xem xét từng thuật ngữ và quyết định:

1. **GIỮ NGUYÊN** tiếng Anh
2. **TIẾP TỤC DỊCH** sang tiếng Việt
3. **CHUẨN HÓA** (nếu hiện không nhất quán)

### Tiêu chí đề xuất:

**Nên GIỮ NGUYÊN tiếng Anh khi:**
- Là tên riêng của hàm/gói mở rộng/kiểu dữ liệu
- Cộng đồng R Việt Nam đã quen thuộc với thuật ngữ tiếng Anh
- Bản dịch tiếng Việt gây khó hiểu hoặc quá dài
- Là thuật ngữ xuất hiện trong code (ví dụ: tên đối số)

**Nên TIẾP TỤC DỊCH khi:**
- Có bản dịch tiếng Việt chuẩn, tự nhiên
- Giúp người mới học dễ hiểu hơn
- Không gây nhầm lẫn với code
- Bản dịch ngắn gọn và chính xác

---

## BƯỚC TIẾP THEO

Sau khi chuyên gia quyết định, chúng ta sẽ:

1. Chuẩn hóa tất cả thuật ngữ theo quyết định
2. Với thuật ngữ GIỮ TIẾNG ANH:
   - Lần đầu: "thuật ngữ tiếng Anh (giải thích tiếng Việt nếu cần)"
   - Từ lần sau: chỉ dùng tiếng Anh
3. Với thuật ngữ TIẾP TỤC DỊCH:
   - Lần đầu: "bản dịch tiếng Việt (thuật ngữ tiếng Anh)"
   - Từ lần sau: chỉ dùng tiếng Việt
4. Cập nhật glossary.md
5. Commit và push tất cả thay đổi
