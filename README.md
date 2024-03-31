# Gan_nhan_de_ERD
## Quy tắc
1. Duplicate file **De_xxx_tach_cau.txt** thành một file riêng để thực hiện gán nhãn trên file đó. Đặt tên file là **De_xxx_gan_nhan_TenNguoiGan.txt**
2. Các loại nhãn:
  - Thực thể: E (Entity)
  - Khóa chính: PK (Primary Key)
  - Thuộc tính của thực thể: AE (Attribute of Entity)
  - Mối kết hợp: R (Relationship)
  - Thuộc tính của mối kết hợp: AR (Attribute of Relationship)
  - Dấu chấm: F
  - Lượng từ "1", "một": O (One)
  - Lượng từ "nhiều", "một số",...: M (Many) <br>
<ins>**Lưu ý:**</ins> Chỉ gán nhãn lượng từ khi đó là lượng từ thể hiện các mối quan hệ giữa các thực thể. Còn lượng từ kiểu "Mỗi báo có **một** mã báo duy nhất" thì "**một**" ở đây không thể hiện mối quan hệ giữa các thực thể mà là thể hiện thực thể gồm những thuộc tính nào, nên ta không cần phải gán.
3. Khi thực hiện gán nhãn, phải phân tách giữa 2 cột với nhau bằng <ins>duy nhất 1 dấu Tab</ins>. Bất kể là dòng đó không có nhãn gì để gán cũng phải thực hiện Tab 1 cái, để sau này đọc data máy biết phần data ở cột 2 sẽ là data rỗng.
## Ví dụ
Xem ở file [De_001_gan_nhan_Quyen.txt](https://github.com/quyen20520296/Gan_nhan_de_ERD/blob/master/De_001/De_001_gan_nhan_Quyen.txt) <br>
![image](https://github.com/quyen20520296/Gan_nhan_de_ERD/assets/105615873/bb770cb4-80b9-4191-b39c-e2cf5be259bb)
