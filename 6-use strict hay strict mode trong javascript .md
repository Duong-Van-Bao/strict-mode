Bài 06: use strict hay strict mode 
 1)What
   - là một chế độ giúp code javascript trở nên an toàn hơn, tránh các lỗi do sơ ý xẩy ra 
   đây là một tính năng ra mắt trong phiên bản js es 6 cải thiết các hạn chế của phiên bản cũ 
 3)how
   - thêm "use strict"; vào đầu file .js
   - thêm "use strict"; vào đầu thẻ <script> 
   - thêm "use strict"; vào đầu phạm vi hàm 
  *CHÚ Ý: - trước nó không có đoạn code nào khác,nó đứng đầu đoạn code     
          - có dấu chấm phẩy hay không cũng được và ở trong dấu ngoặ đơn hay dấu nháy đều được 
   Những Trường Hợp Thường Gặp:
    + Báo Lỗi khi cho thuộc tính có writable : false 
    + Báo lỗi khi hàm có tham số trùng tên
    + khai báo hàm code block thì sẽ thuộc phạm vi code block
    + không đặt tên biến,tên hàm trùng với một số từ khóa "nhạy cảm" của ngôn ngữ 
  *CHÚ Ý: - không xóa đực biến object 
    1)Công cụ
       - tránh "quên" từ khóa khai báo biến
       - tránh trùng tên khi khai báo biến 
       - sử dụng bộ nhớ hiểu quả vì trách tạo biến global
          