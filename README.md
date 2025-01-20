# B-i-16-NH-D-NG-KHUNG
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bài 16: Định Dạng Khung</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }
        .title {
            text-align: center;
            font-size: 2em;
            font-weight: bold;
            margin-top: 20px;
            color: red;
        }
        
        .content {
            font-size: 1.2em;
            margin: 20px;
        }
    </style>
</head>
<body>
    <div class="title">BÀI 16: ĐỊNH DẠNG KHUNG</div>
    <div class="content">
        <!-- Nội dung bài học sẽ được chèn vào đây -->
    </div>
</body>
</html>

    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }
        .highlight {
            background-color: yellow;
            font-weight: bold;
        }
        .larger-text {
            font-size: 1.2em;
        }
    </style>
</head>
<body>
    <div class="larger-text">
        <p>Bài 1: Phần tử HTML có thể ẩn đi trên trang web được không? Nếu có thì dùng lệnh CSS gì?</p>
        <p>Có, phần tử HTML có thể được ẩn đi trên trang web bằng cách sử dụng lệnh CSS <span class="highlight">display: none;</span>.</p>

        <p>Bài 2: Hãy giải thích ý nghĩa định dạng sau:</p>
        <p>
            - <span class="highlight">test.test_more</span>: Đây là một bộ chọn đồng thời (class selector) áp dụng cho các phần tử có cả hai lớp tên là "test" và "test_more". Điều này có nghĩa là chỉ các phần tử có cả hai lớp tên này sẽ được áp dụng định dạng.
        </p>
        <p>
            - <span class="highlight">background-color: red;</span>: Đây là thuộc tính CSS được sử dụng để đặt màu nền (background-color) của các phần tử được chọn. Trong trường hợp này, màu nền của các phần tử có lớp tên "test" và "test_more" sẽ được đặt là đỏ (red).
        </p>

        <p>VẬN DỤNG:</p>

        <p>Bài 1: Giả sử nội dung trang web của em có rất nhiều thẻ p, trong đó có ba đoạn mà em thấy quan trọng nhất, kí hiệu các đoạn này là P1, P2, P3. Có cách nào thiết lập định dạng CSS để có thể định dạng P1 khác biệt, P2 và P3 có cùng kiểu và cũng khác biệt không? Tất cả các đoạn còn lại có định dạng giống nhau. Hãy nêu cách giải quyết vấn đề của em.</p>
        <p>Có. Cách giải quyết:</p>
        <ul>
            <li>Gắn một lớp tên riêng cho P1, ví dụ: <code>&lt;p class="important"&gt;Đoạn P1&lt;/p&gt;</code>. Đây là lớp tên dùng để định dạng đoạn P1.</li>
            <li>Gắn cùng một lớp tên cho P2 và P3, ví dụ: <code>&lt;p class="normal"&gt;Đoạn P2&lt;/p&gt;</code> và <code>&lt;p class="normal"&gt;Đoạn P3&lt;/p&gt;</code>. Đây là lớp tên dùng để định dạng đoạn P2 và P3.</li>
            <li>Sử dụng CSS để áp dụng các định dạng khác biệt cho các lớp tên tương ứng.</li>
        </ul>

        <p>Bài 2: Có thể thiết lập định dạng cho các khung với thông số khung, viền trên, dưới, trái, phải khác nhau được không? Em hãy tìm hiểu và trình bày cách thiết lập định dạng CSS cho các khung, viền như vậy.</p>
        <p>Có, bạn có thể thiết lập định dạng khác nhau cho các khung và viền trên, dưới, trái, phải bằng cách sử dụng thuộc tính CSS <span class="highlight">border</span> và các thuộc tính liên quan.</p>
        <p>Cách thiết lập định dạng CSS cho các khung và viền như vậy như sau:</p>
        <ul>
            <li>Sử dụng thuộc tính <span class="highlight">border</span> để định dạng viền của khung.</li>
            <li>Ví dụ: <code>border: 2px solid black;</code></li>
            <li>Để thiết lập viền khác nhau cho các cạnh, bạn có thể sử dụng các thuộc tính <span class="highlight">border-top</span>, <span class="highlight">border-bottom</span>, <span class="highlight">border-left</span> và <span class="highlight">border-right</span> để chỉ định viền cho từng cạnh riêng biệt.</li>
            <li>Ví dụ: <code>border-top: 2px solid red;</code></li>
        </ul>
    </div>
</body>
</html>
