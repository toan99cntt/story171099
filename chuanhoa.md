Điều kiện thỏa mãn chuẩn hóa dạng 1NF: 
- các trường thuộc tính phải là nguyên tố, không được chứa giá trị phức
- Không chứa cascc thuộc tính gây lặp
- Không chứa thuộc tính có thể tính toán từ thuộc tính khác
- Xác định dc trường thuộc tính khóa chính
Điều kiện thỏa mãn chuẩn hóa dạng 2NF:
- Phải đạt điều kiện dạng chuẩn 1NF
- các trường thuộc tính không phải là khóa chính, phải phụ thuộc hoàn toàn vào khóa chính, không được phụ thuộc vào một phần của khóa chính
vd: 
- bảng chưa thỏa mãn dạng chuẩn 2NF:
	mãsv   hoten   mamonhoc   tenmonhoc         diemthi
	sv1		Nam     AI       trí tuệ nhân tạo 	 6.5
	sv1		Nam     KHMT     khoa học máy tính 	 5.5
- bảng thỏa mãn dạng chuẩn 2NF:
	mãsv      mamonhoc     diemthi
	sv1		    AI        	 6.5
	sv1		    KHMT     	 5.5
Điều kiện thỏa mãn chuẩn hóa dạng 3NF:
- Phải đạt điều kiện dạng chuẩn 2NF
- các trường thuộc tính không phải là khóa chính, phải phụ thuộc trực tiếp vào khóa chính, không được phụ thuộc bắc cầu thông qua thuộc tính khác.
-sdsd