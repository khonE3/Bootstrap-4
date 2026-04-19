# 📘 Bootstrap 4 - รวมทุก Class Name Reference

> เว็บสาธิตการใช้งาน Bootstrap 4 ทุก Class Name พร้อมตัวอย่างจริง รองรับ Responsive ทุกขนาดหน้าจอ

## 📌 ข้อมูลโปรเจกต์

| รายการ | รายละเอียด |
|--------|-----------|
| **Framework** | Bootstrap 4.6.2 |
| **jQuery** | 3.5.1 (slim) |
| **Popper.js** | 1.16.1 |
| **Font** | Google Fonts - Prompt |
| **Images** | Lorem Picsum (picsum.photos) |
| **Responsive** | ✅ รองรับทุกขนาด (XS → XL) |

---

## 📐 1. Layout Classes

### Container
| Class | คำอธิบาย |
|-------|---------|
| `.container` | กล่องแบบ fixed-width ที่ responsive ตาม breakpoint |
| `.container-fluid` | กล่องเต็มความกว้างหน้าจอ 100% |

### Grid System
| Class | คำอธิบาย |
|-------|---------|
| `.row` | แถวของ grid (ใช้ flexbox) |
| `.col` | คอลัมน์แบบอัตโนมัติ (เท่าๆ กัน) |
| `.col-{1-12}` | คอลัมน์แบบกำหนดขนาด (ไม่ระบุ breakpoint = ทุกขนาด) |
| `.col-sm-{1-12}` | คอลัมน์สำหรับหน้าจอ ≥ 576px |
| `.col-md-{1-12}` | คอลัมน์สำหรับหน้าจอ ≥ 768px |
| `.col-lg-{1-12}` | คอลัมน์สำหรับหน้าจอ ≥ 992px |
| `.col-xl-{1-12}` | คอลัมน์สำหรับหน้าจอ ≥ 1200px |
| `.no-gutters` | เอา gutters (ช่องว่างระหว่าง column) ออก |
| `.offset-{breakpoint}-{1-11}` | เว้นระยะคอลัมน์ทางซ้าย |
| `.order-{1-12}` | เปลี่ยนลำดับการแสดงผลคอลัมน์ |

### Form Row
| Class | คำอธิบาย |
|-------|---------|
| `.form-row` | row สำหรับ form ที่มี gutter เล็กกว่าปกติ |

---

## 🔀 2. Flexbox Utilities

| Class | คำอธิบาย |
|-------|---------|
| `.d-flex` | เปิดใช้ flexbox |
| `.d-inline-flex` | flexbox แบบ inline |
| `.flex-row` | จัดเรียงแนวนอน (ค่าเริ่มต้น) |
| `.flex-column` | จัดเรียงแนวตั้ง |
| `.flex-md-row` | จัดแนวนอนตั้งแต่ขนาด md ขึ้นไป |
| `.flex-wrap` | ให้ item ห่อบรรทัดได้ |
| `.flex-fill` | ขยายให้เติมเต็มพื้นที่ |
| `.flex-grow-1` | ขยายตัว (grow factor = 1) |
| `.flex-shrink-0` | ไม่หดตัว |
| `.justify-content-start` | จัดชิดซ้าย |
| `.justify-content-center` | จัดกลาง |
| `.justify-content-end` | จัดชิดขวา |
| `.justify-content-between` | กระจายเท่าๆ กัน (ไม่มีขอบ) |
| `.justify-content-around` | กระจายเท่าๆ กัน (มีขอบ) |
| `.align-items-start` | จัดแนวตั้งชิดบน |
| `.align-items-center` | จัดแนวตั้งกลาง |
| `.align-items-end` | จัดแนวตั้งชิดล่าง |
| `.align-items-stretch` | ยืดเต็มความสูง |
| `.align-self-center` | จัดตัวเองกลางแนวตั้ง |

---

## 📺 3. Display Utilities

| Class | คำอธิบาย |
|-------|---------|
| `.d-none` | ซ่อน element |
| `.d-block` | แสดงเป็น block |
| `.d-inline` | แสดงเป็น inline |
| `.d-inline-block` | แสดงเป็น inline-block |
| `.d-flex` | แสดงเป็น flex |
| `.d-sm-block` | แสดงเป็น block ตั้งแต่ ≥ 576px |
| `.d-sm-flex` | แสดงเป็น flex ตั้งแต่ ≥ 576px |
| `.d-sm-none` | ซ่อนตั้งแต่ ≥ 576px |
| `.d-md-block` | แสดงเป็น block ตั้งแต่ ≥ 768px |
| `.d-md-none` | ซ่อนตั้งแต่ ≥ 768px |
| `.d-md-inline` | แสดงเป็น inline ตั้งแต่ ≥ 768px |
| `.d-lg-flex` | แสดงเป็น flex ตั้งแต่ ≥ 992px |

> **หมายเหตุ:** ใช้ได้กับทุก breakpoint: `sm`, `md`, `lg`, `xl`

---

## 📝 4. Typography

### Heading & Display
| Class | คำอธิบาย |
|-------|---------|
| `.h1` ~ `.h6` | ให้ element มี style เหมือน heading (ไม่ใช้ tag) |
| `.display-1` ~ `.display-4` | heading ขนาดใหญ่พิเศษ |
| `.lead` | ย่อหน้าเน้น (ตัวใหญ่กว่าปกติ) |
| `.small` | ข้อความเล็ก |

### Font Weight & Style
| Class | คำอธิบาย |
|-------|---------|
| `.font-weight-bold` | ตัวหนา |
| `.font-weight-normal` | น้ำหนักปกติ |
| `.font-weight-light` | ตัวบาง |
| `.font-italic` | ตัวเอียง |
| `.text-monospace` | ฟอนต์แบบ monospace |

### Text Transform
| Class | คำอธิบาย |
|-------|---------|
| `.text-uppercase` | ตัวพิมพ์ใหญ่ทั้งหมด |
| `.text-lowercase` | ตัวพิมพ์เล็กทั้งหมด |
| `.text-capitalize` | ตัวแรกของแต่ละคำเป็นพิมพ์ใหญ่ |

### Text Alignment
| Class | คำอธิบาย |
|-------|---------|
| `.text-left` | ชิดซ้าย |
| `.text-center` | กลาง |
| `.text-right` | ชิดขวา |
| `.text-md-center` | กลางตั้งแต่ ≥ 768px |
| `.text-lg-right` | ชิดขวาตั้งแต่ ≥ 992px |

### Text Misc
| Class | คำอธิบาย |
|-------|---------|
| `.text-truncate` | ตัดข้อความด้วย `...` เมื่อยาวเกิน |
| `.text-decoration-none` | เอา underline ออก |
| `.text-hide` | ซ่อนข้อความ (ใช้กับ background-image) |

### Blockquote
| Class | คำอธิบาย |
|-------|---------|
| `.blockquote` | ข้อความอ้างอิง |
| `.blockquote-footer` | แหล่งที่มาของ blockquote |

### Lists
| Class | คำอธิบาย |
|-------|---------|
| `.list-unstyled` | เอา bullet ออก |
| `.list-inline` | ทำ list แบบแนวนอน |
| `.list-inline-item` | item ใน inline list |

---

## 🎨 5. Colors

### Text Colors
| Class | คำอธิบาย |
|-------|---------|
| `.text-primary` | สีน้ำเงิน (primary) |
| `.text-secondary` | สีเทา (secondary) |
| `.text-success` | สีเขียว (success) |
| `.text-danger` | สีแดง (danger) |
| `.text-warning` | สีเหลือง (warning) |
| `.text-info` | สีฟ้า (info) |
| `.text-light` | สีขาวอ่อน |
| `.text-dark` | สีดำเข้ม |
| `.text-muted` | สีเทาจาง |
| `.text-white` | สีขาว |
| `.text-white-50` | สีขาว 50% opacity |

### Background Colors
| Class | คำอธิบาย |
|-------|---------|
| `.bg-primary` | พื้นหลังสี primary |
| `.bg-secondary` | พื้นหลังสี secondary |
| `.bg-success` | พื้นหลังสี success |
| `.bg-danger` | พื้นหลังสี danger |
| `.bg-warning` | พื้นหลังสี warning |
| `.bg-info` | พื้นหลังสี info |
| `.bg-light` | พื้นหลังสี light |
| `.bg-dark` | พื้นหลังสี dark |

### Gradient
| Class | คำอธิบาย |
|-------|---------|
| `.bg-gradient-primary` | พื้นหลังไล่สี primary |
| `.bg-gradient-success` | พื้นหลังไล่สี success |
| `.bg-gradient-danger` | พื้นหลังไล่สี danger |

---

## 📏 6. Spacing (Margin & Padding)

### รูปแบบ: `.{property}{sides}-{breakpoint}-{size}`

**Property:**
- `m` = margin
- `p` = padding

**Sides:**
- `t` = top, `b` = bottom, `l` = left, `r` = right
- `x` = left + right, `y` = top + bottom
- *(ว่าง)* = ทุกด้าน

**Size:** `0`, `1`, `2`, `3`, `4`, `5`, `auto`

| Class | คำอธิบาย |
|-------|---------|
| `.m-0` ~ `.m-5` | margin ทุกด้าน (0 = 0, 1 = 0.25rem, 2 = 0.5rem, 3 = 1rem, 4 = 1.5rem, 5 = 3rem) |
| `.mt-{0-5}` | margin-top |
| `.mb-{0-5}` | margin-bottom |
| `.ml-{0-5}` | margin-left |
| `.mr-{0-5}` | margin-right |
| `.mx-{0-5}` | margin ซ้าย + ขวา |
| `.my-{0-5}` | margin บน + ล่าง |
| `.mx-auto` | margin auto ซ้าย-ขวา (จัดกลาง) |
| `.p-0` ~ `.p-5` | padding ทุกด้าน |
| `.pt-{0-5}` | padding-top |
| `.pb-{0-5}` | padding-bottom |
| `.pl-{0-5}` | padding-left |
| `.pr-{0-5}` | padding-right |
| `.px-{0-5}` | padding ซ้าย + ขวา |
| `.py-{0-5}` | padding บน + ล่าง |

> **Responsive:** ใส่ breakpoint ได้ เช่น `.mt-md-3`, `.p-lg-5`

---

## 🖼️ 7. Images

| Class | คำอธิบาย |
|-------|---------|
| `.img-fluid` | รูปภาพ responsive (max-width: 100%) |
| `.img-thumbnail` | รูปภาพมีขอบกรอบ |
| `.rounded` | มุมมน |
| `.rounded-circle` | วงกลม |

---

## 📊 8. Tables

| Class | คำอธิบาย |
|-------|---------|
| `.table` | ตารางพื้นฐาน |
| `.table-dark` | ตารางโทนสีเข้ม |
| `.table-striped` | แถวสลับสี |
| `.table-bordered` | มีเส้นขอบทุกด้าน |
| `.table-hover` | เปลี่ยนสีเมื่อ hover แถว |
| `.table-sm` | ตารางขนาดเล็ก (compact) |
| `.table-responsive` | scroll แนวนอนได้บนมือถือ |
| `.table-active` | ไฮไลท์แถว/เซลล์ |
| `.thead-dark` | หัวตารางสีเข้ม |
| `.thead-light` | หัวตารางสีอ่อน |

---

## 🔘 9. Buttons

### สีปุ่ม
| Class | คำอธิบาย |
|-------|---------|
| `.btn` | Class พื้นฐาน (ต้องใช้เสมอ) |
| `.btn-primary` | ปุ่มสี primary |
| `.btn-secondary` | ปุ่มสี secondary |
| `.btn-success` | ปุ่มสี success |
| `.btn-danger` | ปุ่มสี danger |
| `.btn-warning` | ปุ่มสี warning |
| `.btn-info` | ปุ่มสี info |
| `.btn-light` | ปุ่มสี light |
| `.btn-dark` | ปุ่มสี dark |
| `.btn-link` | ปุ่มเป็นลิงก์ |

### ปุ่มเส้นขอบ (Outline)
| Class | คำอธิบาย |
|-------|---------|
| `.btn-outline-primary` | เส้นขอบ primary |
| `.btn-outline-secondary` | เส้นขอบ secondary |
| `.btn-outline-success` | เส้นขอบ success |
| `.btn-outline-danger` | เส้นขอบ danger |
| `.btn-outline-warning` | เส้นขอบ warning |
| `.btn-outline-info` | เส้นขอบ info |
| `.btn-outline-light` | เส้นขอบ light |

### ขนาดปุ่ม
| Class | คำอธิบาย |
|-------|---------|
| `.btn-lg` | ขนาดใหญ่ |
| `.btn-sm` | ขนาดเล็ก |
| `.btn-block` | เต็มความกว้าง |

### กลุ่มปุ่ม
| Class | คำอธิบาย |
|-------|---------|
| `.btn-group` | จัดกลุ่มปุ่ม |
| `.btn-toolbar` | แถบเครื่องมือ |

### สถานะปุ่ม
| Class | คำอธิบาย |
|-------|---------|
| `.active` | สถานะ active |
| `.disabled` | สถานะ disabled |

---

## ⚠️ 10. Alerts

| Class | คำอธิบาย |
|-------|---------|
| `.alert` | กล่องแจ้งเตือนพื้นฐาน |
| `.alert-primary` | แจ้งเตือนสี primary |
| `.alert-success` | แจ้งเตือนสี success |
| `.alert-danger` | แจ้งเตือนสี danger |
| `.alert-warning` | แจ้งเตือนสี warning |
| `.alert-info` | แจ้งเตือนสี info |
| `.alert-dismissible` | แจ้งเตือนที่กดปิดได้ |
| `.alert-link` | ลิงก์ภายใน alert |
| `.fade` | animation จางหาย |
| `.show` | แสดง (ใช้กับ .fade) |

---

## 🏷️ 11. Badges

| Class | คำอธิบาย |
|-------|---------|
| `.badge` | ป้าย/แท็กพื้นฐาน |
| `.badge-primary` | ป้ายสี primary |
| `.badge-secondary` | ป้ายสี secondary |
| `.badge-success` | ป้ายสี success |
| `.badge-danger` | ป้ายสี danger |
| `.badge-warning` | ป้ายสี warning |
| `.badge-info` | ป้ายสี info |
| `.badge-light` | ป้ายสี light |
| `.badge-dark` | ป้ายสี dark |
| `.badge-pill` | ป้ายทรงกลม (rounded pill) |

---

## 🃏 12. Cards

| Class | คำอธิบาย |
|-------|---------|
| `.card` | การ์ดพื้นฐาน |
| `.card-body` | เนื้อหาภายในการ์ด |
| `.card-title` | หัวข้อการ์ด |
| `.card-subtitle` | หัวข้อรอง |
| `.card-text` | เนื้อหาการ์ด |
| `.card-link` | ลิงก์ในการ์ด |
| `.card-header` | ส่วนหัวการ์ด |
| `.card-footer` | ส่วนท้ายการ์ด |
| `.card-img-top` | รูปด้านบนการ์ด |
| `.card-img` | รูปเต็มการ์ด |
| `.card-img-overlay` | เลเยอร์ข้อความทับรูป |
| `.card-deck` | จัดกลุ่มการ์ดแบบเท่ากัน |
| `.card-columns` | จัดกลุ่มการ์ดแบบ masonry |

---

## 🧭 13. Navbar

| Class | คำอธิบาย |
|-------|---------|
| `.navbar` | Navigation bar พื้นฐาน |
| `.navbar-expand-lg` | ขยายบน lg ขึ้นไป (พับบนมือถือ) |
| `.navbar-dark` | ธีมสีเข้ม (ข้อความสีขาว) |
| `.navbar-light` | ธีมสีอ่อน (ข้อความสีดำ) |
| `.navbar-brand` | โลโก้/ชื่อแบรนด์ |
| `.navbar-toggler` | ปุ่ม hamburger บนมือถือ |
| `.navbar-toggler-icon` | ไอคอน hamburger |
| `.navbar-nav` | รายการ nav ใน navbar |
| `.navbar-collapse` | ส่วนที่พับได้ |
| `.nav-item` | รายการ nav แต่ละอัน |
| `.nav-link` | ลิงก์ใน nav |
| `.collapse` | ส่วนที่พับ/ขยายได้ |

---

## 📑 14. Navs (Tabs & Pills)

| Class | คำอธิบาย |
|-------|---------|
| `.nav` | nav พื้นฐาน |
| `.nav-tabs` | แท็บ |
| `.nav-pills` | ปุ่มกลม (pills) |
| `.nav-fill` | กระจายเต็มความกว้าง |
| `.nav-justified` | ขนาดเท่ากันทุกอัน |
| `.tab-content` | กล่องเนื้อหาแท็บ |
| `.tab-pane` | เนื้อหาแต่ละแท็บ |

---

## 🍞 15. Breadcrumb

| Class | คำอธิบาย |
|-------|---------|
| `.breadcrumb` | แถบนำทาง (breadcrumb) |
| `.breadcrumb-item` | แต่ละรายการใน breadcrumb |

---

## 📄 16. Pagination

| Class | คำอธิบาย |
|-------|---------|
| `.pagination` | กลุ่มปุ่มแบ่งหน้า |
| `.page-item` | แต่ละปุ่ม |
| `.page-link` | ลิงก์ในปุ่ม |
| `.pagination-lg` | ขนาดใหญ่ |
| `.pagination-sm` | ขนาดเล็ก |

---

## 📢 17. Jumbotron

| Class | คำอธิบาย |
|-------|---------|
| `.jumbotron` | กล่องแสดงข้อมูลขนาดใหญ่ (hero) |
| `.jumbotron-fluid` | jumbotron เต็มความกว้าง |

---

## 📊 18. Progress Bars

| Class | คำอธิบาย |
|-------|---------|
| `.progress` | กล่อง progress bar |
| `.progress-bar` | แถบ progress |
| `.progress-bar-striped` | ลายทาง |
| `.progress-bar-animated` | animation เคลื่อนไหว |

---

## 📋 19. List Group

| Class | คำอธิบาย |
|-------|---------|
| `.list-group` | กลุ่มรายการ |
| `.list-group-item` | แต่ละรายการ |
| `.list-group-item-action` | คลิกได้ (มี hover effect) |
| `.list-group-flush` | ไม่มีขอบซ้าย-ขวา |
| `.list-group-horizontal` | แนวนอน |
| `.list-group-horizontal-sm` | แนวนอนตั้งแต่ ≥ 576px |

---

## 🔄 20. Spinners

| Class | คำอธิบาย |
|-------|---------|
| `.spinner-border` | spinner แบบวงกลมหมุน |
| `.spinner-border-sm` | spinner วงกลมขนาดเล็ก |
| `.spinner-grow` | spinner แบบกระเพื่อม |
| `.spinner-grow-sm` | spinner กระเพื่อมขนาดเล็ก |

---

## 🪗 21. Accordion / Collapse

| Class / Attribute | คำอธิบาย |
|-------------------|---------|
| `.accordion` | กล่อง accordion |
| `.collapse` | ส่วนที่พับได้ |
| `.collapse.show` | แสดง (เปิดอยู่) |
| `data-toggle="collapse"` | ตัวเปิด/ปิด collapse |
| `data-target="#id"` | เป้าหมายที่จะพับ |
| `data-parent="#id"` | ทำให้เปิดได้ทีละอัน |

---

## 🎠 22. Carousel

| Class | คำอธิบาย |
|-------|---------|
| `.carousel` | slider พื้นฐาน |
| `.carousel-inner` | กล่องเนื้อหา slide |
| `.carousel-item` | แต่ละ slide |
| `.carousel-control-prev` | ปุ่มก่อนหน้า |
| `.carousel-control-next` | ปุ่มถัดไป |
| `.carousel-control-prev-icon` | ไอคอนก่อนหน้า |
| `.carousel-control-next-icon` | ไอคอนถัดไป |
| `.carousel-indicators` | จุดบอกตำแหน่ง slide |
| `.carousel-caption` | ข้อความบน slide |
| `data-ride="carousel"` | เริ่มเลื่อนอัตโนมัติ |
| `data-slide="prev/next"` | ทิศทางเลื่อน |

---

## 💬 23. Tooltips & Popovers

| Attribute | คำอธิบาย |
|-----------|---------|
| `data-toggle="tooltip"` | เปิด tooltip |
| `data-placement="top/right/bottom/left"` | ตำแหน่ง tooltip |
| `title="..."` | ข้อความ tooltip |
| `data-toggle="popover"` | เปิด popover |
| `data-content="..."` | เนื้อหา popover |
| `data-trigger="hover/click/focus"` | วิธีเปิด popover |

---

## 🪟 24. Modals

| Class | คำอธิบาย |
|-------|---------|
| `.modal` | modal พื้นฐาน |
| `.modal-dialog` | กล่อง dialog |
| `.modal-content` | เนื้อหา modal |
| `.modal-header` | ส่วนหัว |
| `.modal-body` | เนื้อหา |
| `.modal-footer` | ส่วนท้าย |
| `.modal-title` | หัวข้อ modal |
| `.modal-lg` | ขนาดใหญ่ |
| `.modal-sm` | ขนาดเล็ก |
| `.modal-dialog-centered` | จัดกลางหน้าจอ |
| `.modal-dialog-scrollable` | scroll ได้ |
| `.fade` | animation |
| `data-toggle="modal"` | ปุ่มเปิด modal |
| `data-target="#id"` | เป้าหมาย modal |
| `data-dismiss="modal"` | ปุ่มปิด modal |

---

## 🔔 25. Toast

| Class | คำอธิบาย |
|-------|---------|
| `.toast` | toast notification |
| `.toast-header` | ส่วนหัว toast |
| `.toast-body` | เนื้อหา toast |

---

## 📋 26. Forms

### Form Structure
| Class | คำอธิบาย |
|-------|---------|
| `.form-group` | กลุ่ม label + input |
| `.form-control` | input/select/textarea พื้นฐาน |
| `.form-control-lg` | input ขนาดใหญ่ |
| `.form-control-sm` | input ขนาดเล็ก |
| `.form-control-plaintext` | input แบบข้อความธรรมดา (ไม่มีกรอบ) |
| `.form-text` | ข้อความอธิบายใต้ input |
| `.form-row` | row สำหรับ form |
| `.form-inline` | form แบบแนวนอน |

### Checkboxes & Radios
| Class | คำอธิบาย |
|-------|---------|
| `.form-check` | กลุ่ม checkbox/radio |
| `.form-check-input` | input checkbox/radio |
| `.form-check-label` | label |
| `.form-check-inline` | แนวนอน |

### Custom Controls
| Class | คำอธิบาย |
|-------|---------|
| `.custom-control` | custom control พื้นฐาน |
| `.custom-control-input` | custom input |
| `.custom-control-label` | custom label |
| `.custom-checkbox` | custom checkbox |
| `.custom-radio` | custom radio |
| `.custom-switch` | toggle switch |
| `.custom-select` | custom select dropdown |
| `.custom-range` | custom range slider |
| `.custom-file` | custom file input |
| `.custom-file-input` | file input element |
| `.custom-file-label` | file label |

### Input Group
| Class | คำอธิบาย |
|-------|---------|
| `.input-group` | กลุ่ม input + addon |
| `.input-group-prepend` | addon ด้านหน้า |
| `.input-group-append` | addon ด้านหลัง |
| `.input-group-text` | ข้อความใน addon |

### Validation
| Class | คำอธิบาย |
|-------|---------|
| `.is-valid` | สถานะถูกต้อง (ขอบเขียว) |
| `.is-invalid` | สถานะผิดพลาด (ขอบแดง) |
| `.valid-feedback` | ข้อความเมื่อถูกต้อง |
| `.invalid-feedback` | ข้อความเมื่อผิดพลาด |
| `.was-validated` | เปิด validation state |

---

## 🔲 27. Borders & Rounded

### Borders
| Class | คำอธิบาย |
|-------|---------|
| `.border` | เส้นขอบทุกด้าน |
| `.border-top` | เส้นขอบบน |
| `.border-right` | เส้นขอบขวา |
| `.border-bottom` | เส้นขอบล่าง |
| `.border-left` | เส้นขอบซ้าย |
| `.border-0` | เอาเส้นขอบออก |
| `.border-primary` | สีเส้นขอบ primary |
| `.border-secondary` | สีเส้นขอบ secondary |
| `.border-success` | สีเส้นขอบ success |
| `.border-danger` | สีเส้นขอบ danger |
| `.border-warning` | สีเส้นขอบ warning |
| `.border-info` | สีเส้นขอบ info |
| `.border-light` | สีเส้นขอบ light |

### Rounded
| Class | คำอธิบาย |
|-------|---------|
| `.rounded` | มุมมน (ค่าเริ่มต้น) |
| `.rounded-top` | มุมมนบน |
| `.rounded-right` | มุมมนขวา |
| `.rounded-bottom` | มุมมนล่าง |
| `.rounded-left` | มุมมนซ้าย |
| `.rounded-circle` | วงกลม |
| `.rounded-pill` | pill shape (capsule) |
| `.rounded-0` | ไม่มุมมน |
| `.rounded-sm` | มุมมนเล็ก |
| `.rounded-lg` | มุมมนใหญ่ |

---

## 🌑 28. Shadows

| Class | คำอธิบาย |
|-------|---------|
| `.shadow-none` | ไม่มีเงา |
| `.shadow-sm` | เงาเล็ก |
| `.shadow` | เงาปกติ |
| `.shadow-lg` | เงาใหญ่ |

---

## 📐 29. Sizing

| Class | คำอธิบาย |
|-------|---------|
| `.w-25` | กว้าง 25% |
| `.w-50` | กว้าง 50% |
| `.w-75` | กว้าง 75% |
| `.w-100` | กว้าง 100% |
| `.w-auto` | กว้างอัตโนมัติ |
| `.h-25` ~ `.h-100` | ความสูง 25% - 100% |
| `.mw-100` | max-width: 100% |
| `.mh-100` | max-height: 100% |
| `.vw-100` | 100vw (เต็มความกว้างหน้าจอ) |
| `.vh-100` | 100vh (เต็มความสูงหน้าจอ) |

---

## 📍 30. Position

| Class | คำอธิบาย |
|-------|---------|
| `.position-static` | ตำแหน่งปกติ |
| `.position-relative` | ตำแหน่งสัมพันธ์ |
| `.position-absolute` | ตำแหน่งสัมบูรณ์ |
| `.position-fixed` | ตำแหน่งคงที่ (ติดหน้าจอ) |
| `.position-sticky` | ตำแหน่ง sticky |
| `.fixed-top` | ติดด้านบนหน้าจอ |
| `.fixed-bottom` | ติดด้านล่างหน้าจอ |
| `.sticky-top` | sticky ด้านบน |

---

## 🔄 31. Float & Clear

| Class | คำอธิบาย |
|-------|---------|
| `.float-left` | ลอยซ้าย |
| `.float-right` | ลอยขวา |
| `.float-none` | ไม่ลอย |
| `.clearfix` | ล้าง float |

---

## 👁️ 32. Visibility

| Class | คำอธิบาย |
|-------|---------|
| `.visible` | มองเห็น |
| `.invisible` | มองไม่เห็น (แต่ยังกินพื้นที่) |
| `.sr-only` | ซ่อนแต่ screen reader อ่านได้ |

---

## 🎥 33. Embed Responsive

| Class | คำอธิบาย |
|-------|---------|
| `.embed-responsive` | กล่อง embed responsive |
| `.embed-responsive-21by9` | อัตราส่วน 21:9 |
| `.embed-responsive-16by9` | อัตราส่วน 16:9 |
| `.embed-responsive-4by3` | อัตราส่วน 4:3 |
| `.embed-responsive-1by1` | อัตราส่วน 1:1 |
| `.embed-responsive-item` | item ภายใน |

---

## 📰 34. Media Object

| Class | คำอธิบาย |
|-------|---------|
| `.media` | media object (รูป + เนื้อหา) |
| `.media-body` | เนื้อหาข้าง media |

---

## 🔗 35. Misc Utilities

| Class | คำอธิบาย |
|-------|---------|
| `.stretched-link` | ทำให้ทั้ง container คลิกได้ |
| `.close` | ปุ่มกากบาท (×) |
| `.overflow-auto` | scroll อัตโนมัติเมื่อเนื้อหาเกิน |
| `.overflow-hidden` | ซ่อนเนื้อหาที่เกิน |

---

## 🔧 36. Data Attributes (JavaScript)

| Attribute | คำอธิบาย |
|-----------|---------|
| `data-toggle="collapse"` | เปิด/ปิด collapse |
| `data-toggle="tab"` | สลับ tab |
| `data-toggle="modal"` | เปิด modal |
| `data-toggle="dropdown"` | เปิด dropdown |
| `data-toggle="tooltip"` | แสดง tooltip |
| `data-toggle="popover"` | แสดง popover |
| `data-target="#id"` | ระบุเป้าหมาย |
| `data-dismiss="modal"` | ปิด modal |
| `data-dismiss="alert"` | ปิด alert |
| `data-dismiss="toast"` | ปิด toast |
| `data-ride="carousel"` | เริ่ม carousel auto |
| `data-slide="prev/next"` | เลื่อน slide |
| `data-slide-to="0"` | ไปที่ slide เป้าหมาย |
| `data-delay="5000"` | หน่วงเวลา (ms) |
| `data-parent="#id"` | ระบุ parent (accordion) |

---

## 📱 37. Responsive Breakpoints

| Breakpoint | ขนาดหน้าจอ | Infix |
|------------|-----------|-------|
| Extra small | < 576px | *(ไม่มี)* |
| Small | ≥ 576px | `sm` |
| Medium | ≥ 768px | `md` |
| Large | ≥ 992px | `lg` |
| Extra large | ≥ 1200px | `xl` |

### ตัวอย่างการใช้ Responsive
```html
<!-- Grid -->
<div class="col-12 col-sm-6 col-md-4 col-lg-3">

<!-- Display -->
<div class="d-none d-md-block">

<!-- Spacing -->
<div class="p-2 p-md-4 mb-3 mb-lg-5">

<!-- Text alignment -->
<p class="text-center text-md-left">

<!-- Flex direction -->
<div class="d-flex flex-column flex-md-row">
```

---

## 📊 สรุปจำนวน Class ทั้งหมด

| หมวดหมู่ | จำนวน (ประมาณ) |
|---------|---------------|
| Layout & Grid | 12+ |
| Flexbox | 20+ |
| Display | 12+ |
| Typography | 20+ |
| Colors | 25+ |
| Spacing | 30+ |
| Images | 4 |
| Tables | 10 |
| Buttons | 25+ |
| Alerts | 10 |
| Badges | 10 |
| Cards | 13 |
| Navbar | 12 |
| Navs (Tabs/Pills) | 7 |
| Breadcrumb | 2 |
| Pagination | 5 |
| Jumbotron | 2 |
| Progress | 4 |
| List Group | 6 |
| Spinners | 4 |
| Collapse/Accordion | 3 |
| Carousel | 10 |
| Modals | 11 |
| Toast | 3 |
| Forms | 30+ |
| Borders & Rounded | 20+ |
| Shadows | 4 |
| Sizing | 10 |
| Position | 8 |
| Float | 4 |
| Visibility | 3 |
| Embed | 6 |
| Media Object | 2 |
| Misc | 4 |
| Data Attributes | 15 |
| **รวมทั้งหมด** | **~350+ Class Names** |

---

## 🚀 วิธีใช้งาน

1. เปิดไฟล์ `index.html` ในเบราว์เซอร์
2. เลื่อนดูทุกหมวดหมู่พร้อมตัวอย่าง
3. กดปุ่มต่างๆ เพื่อทดสอบ Modal, Toast, Tooltip, Popover
4. ย่อ/ขยายหน้าจอเพื่อดู Responsive behavior

## 📚 อ้างอิง

- [Bootstrap 4 Official Documentation](https://getbootstrap.com/docs/4.6/)
- [Bootstrap 4 CDN](https://www.bootstrapcdn.com/)
- [Lorem Picsum - Free Images](https://picsum.photos/)

---

> สร้างด้วย ❤️ เพื่อการเรียนรู้ Bootstrap 4
