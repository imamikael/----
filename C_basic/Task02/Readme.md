# Báo cáo task 2
## Ngôn ngữ Markdown
+ Markdown là dạng ngôn ngữ lập trình được dựa trên 2 tiêu chí là dễ đọc, dễ hiểu
--> thuận tiện cho việc làm việc với các dạng văn bản dài dòng.

## Các cú pháp thường gặp trong Markdown

### 1.Tiêu đề
- ta dùng # để đánh dấu tiêu đề với mỗi dấu # là 1 cấp.

Cú pháp: `#~# nội dung tiêu đề` (với dấu # tối đa là 6 ~ 6 cấp tiêu đề)
ví dụ:

`## đây là cấp 2`
## đây là cấp 2
`## đây là cấp 4`
#### đây là cấp 4
`###### đây là cấp 6`
###### đây là cấp 6
### 2.Chèn link, ảnh
#### Chèn link
- Cú pháp: `[tên rút gọn](link)`

VD: `[xvideos](https://www.xvideos.com/)`

--> [xvideos](https://www.xvideos.com/)
hoặc là paste trực tiếp : 
`https://www.xvideos.com/`

--> https://www.xvideos.com/
#### Chèn ảnh
- Cú pháp: `<img src="link hình ảnh"`
VD: `<img src="https://i.imgur.com/IwtmUfE.png">`
<img src="https://i.imgur.com/IwtmUfE.png">
- Giống như chèn link nhưng thêm ! vào đầu đoạn

    `![superb](https://i.imgur.com/IwtmUfE.png)`

### 3.Bold, Italic

- Bold: `**nội dung**`
-	**nội dung**
- Italic:`*nội dung*`
-	*nội dung*

### 4.Trích dẫn, bo chữ

- dùng để làm nổi bật văn bản
Cú pháp:     

``` 
        `nội dung`    (cho 1 dòng văn bản)
```

-->     `nội dung`
- còn đối với 1 đoạn văn bản 
Cú pháp: 
```
    ```sh
    ~~~
    nội dung
    ~~~
    ```
```
VD:
```sh
~~~
nội dung
~~~
```
### 5.Gạch đầu dòng
Cú pháp:
```
- Gạch đầu dòng thứ nhất
  <ul>
  <li>Thụt với đầu dòng 1</li>
  <li>Thụt với đầu dòng 1</li>
  </ul>
- Gạch đầu dòng thứ hai
  <ul>
  <li>Thụt với đầu dòng 2</li>
  <li>Thụt với đầu dòng 2</li>
  </ul>
```
trở thành:
- Gạch đầu dòng thứ nhất
  <ul>
  <li>Thụt với đầu dòng 1</li>
  <li>Thụt với đầu dòng 1</li>
  </ul>
- Gạch đầu dòng thứ hai
  <ul>
  <li>Thụt với đầu dòng 2</li>
  <li>Thụt với đầu dòng 2</li>
  </ul>
