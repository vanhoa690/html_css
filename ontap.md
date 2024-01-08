## Day 1:

- tạo file index.html <br>
- Shif 1 chọn ! <br>
- Sửa title website <br>
- Body: <br>
<> thẻ mở <br>
Nội dung hiển thị website <br>
</>: thẻ đóng <br>
<h1>Nội dung tiêu đề h1</h1> <br>
heading: h1 -> h6 <br>
thẻ p: đoạn văn <br>
thẻ img: src="đường dẫn img" alt="mo ta hinh anh" <br>

## Day 2:

- a: thẻ liên kết sang url mới: href="src_link" targer="\_blank" <br>

### Style css: html xây nhà, css trang trí nội thất bên trong <br>

- Có 3 cách: nhúng css <br>
- style inline: css trực tiếp trong html (ít hạn): <br> VD: <h1 style="color: red">Xin chao cac ban</h1> <br>
- Nhúng css trong <head></head>: (ít dụng): ko tái sử dụng <br>
  <style>
       h2 {
         color: blue;
       }
     </style>
     <br>
- Code file style.css: code toàn bộ css trong file <br>
  Liên kết vào html: <link href="./style.css" rel="stylesheet" /> <br>

  ### Sử dụng css: qua Selector <br>

  - Dùng class: \*dùng thường xuyên: đặt tên thẻ html class-name: <br>
    (tiếng anh, chọn danh từ đặt tên nối với -) <br>
    VD: class="content-product" <br>
    - Tham khảo quy chuẩn BEM - Code CSS sử dụng class: .ten_class <br>
    - VD: .intro {
      color: blueviolet;
      }

- Dùng ID: (mỗi ID duy nhất - cccd 1 id) - javascript: DOM HTML <br>
  <h3 id="address">Dia chi: Ha Noi</h3> <br>
    - Sử dung: #ten_id <br>
    - VD: #address {
      color: red;
      } <br>

      - Code CSS chồng chéo: css sau đè css trước <br>
      - Độ ưu tiên CSS: !impotant > inline css > id css > class > html <br>

      - Dùng thẻ HTML làm Selector: <br>
      h3 {
        color: green;
        } <br>
