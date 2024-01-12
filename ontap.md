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

## Day 3:

- Font chữ: <br>
  - font-family: import Google Fonts  <br>
  - font-size:14px; (16px)  <br>
  - font-weight:bold; (700): in đậm chữ (400 - chữ bình thường)  <br>
- Căn lề đoạn text:  <br>
  - text-align: center;  <br>
  - text-decoration: none; ( bỏ gạch chân liên kết thẻ a)  <br>
  - line-height: 20px (1: tỷ lệ): độ cao của chữ  <br>
- Hệ màu  <br>
  - color:“red”; text  <br>
  - color:“rgb(255, 0, 0)”: max 255, min: 0  <br>
  - color:“#FF0000”: hex : 6 ký tự or 3 ký tự ( chữ + số)  <br>
- Đơn vị đo  <br>
  - px: 1px = 1 điểm ảnh  <br>
  - %: 100%;  <br>
  - rem, em: đơn vi đo đổi px 1rem = 16px,  <br>
  - vh, vh: đơn chiều dài và chiều rộng của màn hình  <br>
- Thẻ liên kết a:  <br>
  - a:visited{}: link đã được kích  <br>
  - a:active{}: home, blog: menu nổi bật lên -> khách hàng biết trang nào  <br>
  - a:hover{}: di chuột vào thì nổi css ví dụ color, font-size  <br>
- Class: có thể đặt nhiều tên class trong thẻ html  <br>
- 3 Cách Selector:  <br>
  - Thẻ html.ten_class: h1.red {}: style class  <br>
  - Selector1 Selector2{}: chọn selector2 là con F1, F2, ... của cha Selector  <br>
  - Selector1 > Selector2{}: chọn selector 2 là con F1 của Selector cha  <br>
  - ten_classA, ten_classB {}: style chung cho nhiều class  <br>


## Day 4: 
- Flexbox: 
- display: flex (tự động thành 1 hàng )
- justify-content: center; (căn giữa) : căn trái, căn phải, căn đều 2 bên ...
- gap: 24px; (các phần tử cách nhau 24px)
- Game thực hành flexbox: https://flexboxfroggy.com/ (LAb 2: Lv 1-> 10)
- Flexbox: https://topdev.vn/blog/su-dung-bo-cuc-trang-flexbox-trong-css/