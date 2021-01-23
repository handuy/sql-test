Thiết kế database cho 1 hệ thống học trực tuyến. Hệ thống bao gồm các thành phần sau:

**1. Khóa học**

Gồm các thông tin: 
- Tên khóa học
- Giới thiệu nội dung
- Ảnh thumbnail
- Thông tin giảng viên

**2. Chương**

Gồm các thông tin:
- Tên 
- Vị trí của chương trong khóa học

Mỗi khóa học được chia ra thành nhiều chương

**3. Bài học**

Gồm các thông tin: 
- Tên bài học
- Nội dung bài học
- Vị trí của bài học trong chương. 

Nội dung của mỗi bài học sẽ thuộc 1 trong 3 dạng sau: 
- Chỉ có lý thuyết dưới dạng text
- Chỉ có link video Youtube
- Vừa có lý thuyết text vừa có video Youtube

Mỗi chương gồm một hoặc nhiều bài học

**4. Học viên**

Gồm các thông tin: 
- họ tên
- email
- số điện thoại
- hiện đang học những khóa nào, với mỗi khóa thì đang học đến bài nào