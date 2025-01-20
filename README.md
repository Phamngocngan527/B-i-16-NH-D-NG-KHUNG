<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bài 16 - Định Dạng Khung</title>
    <style>
        /* Bài 1: Ẩn phần tử HTML */
        .hidden {
            display: none;
        }

        /* Bài 2: Định dạng test.test_more */
        .test.test_more {
            background-color: red;
        }

        /* VẬN DỤNG Bài 1 */
        .important {
            font-weight: bold;
            color: blue;
        }
        .normal {
            font-style: italic;
            color: green;
        }

        /* VẬN DỤNG Bài 2 */
        .custom-border {
            border-top: 2px solid red;
            border-bottom: 2px dashed blue;
            border-left: 2px dotted green;
            border-right: 2px double purple;
        }

        /* Bài 17: Mức độ ưu tiên của bộ chọn */
        #p123 + p {
            background-color: yellow;
        }
        h2#p123 + p {
            background-color: lightblue;
        }

        /* VẬN DỤNG Bài 2: Định dạng tên riêng */
        .name {
            border: 1px solid black;
            font-style: italic;
            padding: 5px;
        }

        /* VẬN DỤNG Bài 1: Pseudo-class */
        .hover-effect:hover {
            color: red;
        }
        .active-effect:active {
            background-color: yellow;
        }
        .focus-effect:focus {
            outline: 2px solid blue;
        }
        .nth-child-effect:nth-child(odd) {
            background-color: lightgrey;
        }

        /* VẬN DỤNG Bài 2: Pseudo-element */
        .before-effect::before {
            content: "\2605 ";
            color: gold;
        }
        .after-effect::after {
            content: " \2605";
            color: gold;
        }
        .first-line-effect::first-line {
            font-weight: bold;
        }
    </style>
</head>
<body>
    <h1>Bài 16: Định Dạng Khung</h1>

    <h2>LUYỆN TẬP</h2>
    <h3>Bài 1</h3>
    <p class="hidden">Phần tử này bị ẩn.</p>

    <h3>Bài 2</h3>
    <div class="test test_more">Định dạng này sẽ có nền đỏ.</div>

    <h2>VẬN DỤNG</h2>
    <h3>Bài 1</h3>
    <p class="important">P1: Đây là đoạn P1 quan trọng nhất.</p>
    <p class="normal">P2: Đây là đoạn P2.</p>
    <p class="normal">P3: Đây là đoạn P3.</p>

    <h3>Bài 2</h3>
    <div class="custom-border">Đây là khung có viền khác nhau cho từng cạnh.</div>

    <h1>Bài 17: CÁC MỪC ĐỘ ƯU TIÊN CỦA BỘ CHỈN</h1>
    <h2>LUYỆN TẬP</h2>
    <h3>Bài 1</h3>
    <h2 id="p123">Heading 2</h2>
    <p>Phần tử p này sẽ được định dạng khác biệt.</p>

    <h3>Bài 2</h3>
    <p class="name">Nguyễn Văn A</p>
    <p class="name">Công ty XYZ</p>

    <h2>VẬN DỤNG</h2>
    <h3>Bài 1</h3>
    <a href="#" class="hover-effect">Hover me!</a><br>
    <button class="active-effect">Click me!</button><br>
    <input type="text" class="focus-effect" placeholder="Focus me!"><br>
    <ul>
        <li class="nth-child-effect">Item 1</li>
        <li class="nth-child-effect">Item 2</li>
        <li class="nth-child-effect">Item 3</li>
    </ul>

    <h3>Bài 2</h3>
    <p class="before-effect">Trước khi thêm pseudo-element.</p>
    <p class="after-effect">Sau khi thêm pseudo-element.</p>
    <p class="first-line-effect">Đây là một đoạn văn bản ví dụ. Dòng đầu tiên sẽ được bôi đậm.</p>
</body>
</html>
