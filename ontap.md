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
  - font-family: import Google Fonts <br>
  - font-size:14px; (16px) <br>
  - font-weight:bold; (700): in đậm chữ (400 - chữ bình thường) <br>
- Căn lề đoạn text: <br>
  - text-align: center; <br>
  - text-decoration: none; ( bỏ gạch chân liên kết thẻ a) <br>
  - line-height: 20px (1: tỷ lệ): độ cao của chữ <br>
- Hệ màu <br>
  - color:“red”; text <br>
  - color:“rgb(255, 0, 0)”: max 255, min: 0 <br>
  - color:“#FF0000”: hex : 6 ký tự or 3 ký tự ( chữ + số) <br>
- Đơn vị đo <br>
  - px: 1px = 1 điểm ảnh <br>
  - %: 100%; <br>
  - rem, em: đơn vi đo đổi px 1rem = 16px, <br>
  - vh, vh: đơn chiều dài và chiều rộng của màn hình <br>
- Thẻ liên kết a: <br>
  - a:visited{}: link đã được kích <br>
  - a:active{}: home, blog: menu nổi bật lên -> khách hàng biết trang nào <br>
  - a:hover{}: di chuột vào thì nổi css ví dụ color, font-size <br>
- Class: có thể đặt nhiều tên class trong thẻ html <br>
- 3 Cách Selector: <br>
  - Thẻ html.ten_class: h1.red {}: style class <br>
  - Selector1 Selector2{}: chọn selector2 là con F1, F2, ... của cha Selector <br>
  - Selector1 > Selector2{}: chọn selector 2 là con F1 của Selector cha <br>
  - ten_classA, ten_classB {}: style chung cho nhiều class <br>

## Day 4:

- Dùng ul, li làm danh sách Menu <br>
- CSS xóa chấm tròn: list-style: none; <br>
- Thẻ HMML mới: <br>
- <br>: xuống dòng; <br>
- <span></span>: tách cụm từ để css <br>
- <div></div>: nhóm các phần tử để css toàn khối <br>
- <hr>: Vẽ 1 đường thẳng <br>
- Layout: <br>
  - <header></header>: Header chứa menu, logo ...(dùng chung tất cả trang) <br>
  - <nav></nav>: danh sách menu <br>
  - <main></main>: chứa content (thay đổi theo từng trang) <br>
  - <aside></aside>: sidebar bên trái hoặc bên phải (có thể có hoặc ko) <br>
  - <footer></footer>: Footer: chân trang chứa thông tin liên kết thêm ... (dùng chung tất cả trang) <br>
- Flexbox: <br>
- display: flex (tự động thành 1 hàng ) <br>
- justify-content: center; (căn giữa) : căn trái, căn phải, căn đều 2 bên ... <br>
- gap: 24px; (các phần tử cách nhau 24px) <br>
- Game thực hành flexbox: https://flexboxfroggy.com/ (LAb 2: Lv 1-> 10) <br>
- Flexbox: https://topdev.vn/blog/su-dung-bo-cuc-trang-flexbox-trong-css/ <br>

## Day 5:

- Box Model: <div></div> <br>
- border: tạo đường viền: 1px solid red; <br>
- border-radius: tạo bo góc khi có border: 20px <br>
- padding: Tạo khoảng cách giữa nội dung bên trong với border: Top - Right - Bottom -Left (chiều kim đồng hồ) <br>
- padding: 20px; // 1 giá trị OR 2 giá trị OR 3 giá trị OR 4 giá trị <br>
- margin ~ padding: tạo khoảng cách giữa các phần từ <br>
- Background: chìm nền <br>
- color: màu sắc <br>
- image: url('link_hinh_anh') <br>
- no-repeat: ko lặp lại hình ảnh <br>
- position: căn hình ảnh so với khung hình (center center) <br>

## Day 6:

- Figma
  - Chuyển sang devMode (góc trên cùng tay phải) để lấy CSS: padding, font-size <br>
- Import Font chữ: Lấy từ fonts.google <br>
- Nhúng font chữ vào head: <link
      href="https://fonts.googleapis.com/css2?family=Genos:ital@0;1&family=Montserrat:wght@400;500;700&family=Roboto:wght@400;500;700&family=Tektur:wght@400;500;600;700&display=swap"
      rel="stylesheet"
    /> <br>
- CSS: body { font-family: "Montserrat", sans-serif; } <br>
- Reseting margin default: \* {margin: 0; padding: 0} <br>
- Header: <br>
  - img src logo: tạo folder images : src="./image/logo.png" <br>
- Tạo Menu List: <ul>
  <li>
  <a href="#">Ten_Menu_Item</a>
  </li>
  </ul>
- CSS Menu: xóa gạch chân thẻ a: a { text-decoration: none; color: black;} <br>
- Chia Layout: Flexbox <br>
- Menu-list: dislay: flex thành 1 hàng <br>
- Header: 1 hàng: display: flex <br>

# Day 7

- Ext VSCode

  - Auto close tag: đóng tác nhanh
  - Auto Rename Tag: tự đóng thẻ html
  - HTML CSS Support: hỗ trợ code HTML CSS
  - link:css tab ra link nhúng css
    div tab
    div.class tab
    div#id tab

  - CSS:
    - max-with: giới hạn chiều dài đoạn text
    - color, font-size, font-weight
    - <button></button>: Tạo nút bấm
    - CSS button: padding, color, backgroud-color, font-size, font-weight
    - Căn giữa session: .container {
      max-width: 1248px;
      margin: 0 auto;
      }
      background-image:
      height: ?px

# Day 8

- Form HTML: gửi thông tin lên Backend
<!-- https://www.w3schools.com/html/html_form_input_types.asp -->
- Nhập dữ liệu: input
  - type: text: nhập text
  - type: number: nhập số
  - type: email: nhập email
  - typeL password: nhập password
  - type: radio: chọn 1 option
  - type: checkbox : chọn nhiều option
  - type: file : upload file lên
- Textarea: nhập nhiều dòng thông tin
- Select: (option): chọn option theo drop down
- label: nhãn cho input
- button: type submit: action send nội dung

- Kênh Video Youtube: HTML - CSS
- Easy Frontend : https://www.youtube.com/playlist?list=PLeS7aZkL6GOvpkUu6FHFaivFA1xEnRCod
- Evondev: https://www.youtube.com/playlist?list=PLd8OdiciAE1SwMCtd6XgYp-ei1or6sb1r
- Traversy Media: https://www.youtube.com/playlist?list=PLillGF-RfqbZTASqIqdvm1R5mLrQq79CU

- 1 hàng row: display: flex
- 1 cột column: display: flex; flex-direction: column; (row)

# Day 9

- Thiết kế website HTML - CSS (Đề thi / Lab / ASM):
- Folder: (LAB4)
- 1.  index.html
- 2.  style.css
- 3.  Folder: images (chứa hình ảnh)
- I. HTML: (index.html):
  - title: <title>LAB4 HTML</title>
  - link:css (tab) : nhúng file css (./style.css)
  - link:font-family
  - code: body (ko code ngoài body)
- II. CSS (style.css)
  - 1. Reset CSS Default:
  * {
    padding: 0;
    margin: 0;
    }
  2. Tìm Font family (fonts.google.com): Theo thiết kế
  - body : {
    font-family: '',
    }
  3. a: bỏ gạch chân
  4. ul, li: bỏ nút chấm tròn
  5. button: color, background, padding, font-size
  6. chuyển cột => 1 dòng: display: flex
  7. chuyển dòng => 1 cột : display: flex; flex-direction: column
  8. căn giữa section: .container : {max-width: 1000px , margin: 0 auto}
  9. xóa border: border: none;
  10. Có 2 phần tử trở lên: muốn css nên nhóm 1 div.class : display: flex: cột, dòng

# Day 10:

- https://www.w3schools.com/css/css_positioning.asp
- Position CSS: cho 2 phần từ nó xếp chồng lên nhau (1 dưới, 1 trên)
- Dưới: position: relative (cha)
- Trên: position: absolute (con - phụ thuộc vào cha)
