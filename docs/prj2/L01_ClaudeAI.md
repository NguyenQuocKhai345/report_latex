## **ĐẠI HỌC QUỐC GIA TP. HỒCHÍ MINH TRƯỜNG ĐẠI HỌC BÁCH KHOA** 



<!-- Start of picture text -->
o<br><!-- End of picture text -->

# **BÁO CÁO BÀI TẬP LỚN 2 BLACK-BOX TESTING** 

Học kỳHK261 – Năm học 2026–2027 

**Kiểm thửhộp đen hệthống Moodle LMS Mã môn học: CO3015** 

**Giảng viên hướng dẫn:** Trần ThịNgọc Trâm 

### **Danh sách thành viên** 

|**STT**|**Họvà tên**|**MSSV**|
|---|---|---|
|1|Nguyễn Minh Phúc|2312701|
|2|HồTây Nguyên|2036076|
|3|Đặng Đình Thiên Quân|2312818|
|4|Đặng Ngọc Khiêu|2311572|
|5|Nguyễn Quốc Khải|2311557|



TP. HồChí Minh, 2026 



#### **VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

# **Mục lục** 

|**1**|**Phân công công việc (Team Workload & Member Contributions)**|**2**|
|---|---|---|
|**2**|**Feature 001: Add a Category – Nguyễn Quốc Khải**|**3**|
|**3**|**Feature 002: Create a Group in Course – Đặng Ngọc Khiêu**|**7**|
|**4**|**Feature 003: Add a New User – Đặng Đình Thiên Quân**|**13**|
|**5**|**Feature 004: Create Quiz – Nguyễn Minh Phúc**|**22**|
|**6**|**Feature 005: Add a New Course – HồTây Nguyên**|**28**|
|**7**|**Khai báo sửdụng công cụAI (AI Usage Declaration)**|**32**|



Page 1/33 

Project #2 Black-Box Testing – Moodle LMS 



**VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

# **1 Phân công công việc (Team Workload & Member Contributions)** 

Nhóm gồm năm thành viên. Nhóm thống nhất chia đều khối lượng đóng góp, tương ứng mỗi thành viên đóng góp 20% tổng khối lượng công việc. Phân công tính năng và nhiệm vụchi tiết được trình bày trong Bảng 1. 

- **1.1 Danh sách thành viên và phân công nhiệm vụ** 

- **1.2 Mức độđóng góp của từng thành viên (100% / chia đều)** 

Bảng 1: Phân công và mức độ đóng <u>góp</u> của các thành viên 

|**STT**|**Thành viên**|**Tính năng**|**Nhiệm vụchính**|**Đóng góp**|
|---|---|---|---|---|
|1|Nguyễn Minh Phúc<br>(2312701)|Feature 4: Create<br>Quiz|Đặc tảtính năng và<br>thiết kếcác kiểm<br>thử|20%|
|2|HồTây Nguyên<br>(2036076)|Feature 5: Add a<br>New Course|Đặc tảtính năng và<br>thiết kếcác kiểm<br>thử|20%|
|3|Đặng Đình Thiên<br>Quân (2312818)|Feature 3: Add a<br>New User|Đặc tảtính năng và<br>thiết kếcác kiểm<br>thử|20%|
|4|Đặng Ngọc Khiêu<br>(2311572)|Feature 2: Create a<br>Group in Course|Đặc tảtính năng và<br>thiết kếcác kiểm<br>thử|20%|
|5|Nguyễn Quốc Khải<br>(2311557)|Feature 1: Add a<br>Category|Đặc tảtính năng và<br>thiết kếcác kiểm<br>thử|20%|



Các công việc chung gồm thống nhất dữliệu kiểm thử, tổng hợp báo cáo, chuẩn bịvà dọn dẹp dữliệu, thực thi script Katalon Recorder, đồng thời kiểm tra chéo kết quả. Tổng tỷlệđóng góp của nhóm là 100%. 

Page 2/33 

Project #2 Black-Box Testing – Moodle LMS 



**VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

# **2 Feature 001: Add a Category – Nguyễn Quốc Khải** 

## **2.1 Đặc tảtính năng** 

### **2.1.1 Mô tảngắn gọn và hướng dẫn sửdụng** 

**Mô tả:** Chức năng Add a category cho phép người dùng có quyền quản lý hệthống hoặc khóa học (Administrator/Manager) tạo danh mục khóa học mới trong Moodle LMS. Biểu mẫu gồm Category name, Category ID number, Description và Parent category. Quyền và giới hạn dữliệu cần đối chiếu với cấu hình Moodle được kiểm thử. **Hướng dẫn sửdụng:** 

1. Đăng nhập bằng Administrator hoặc Manager có quyền quản lý danh mục. 

2. Truy cập biểu mẫu tại `course/editcategory.php?parent=0` . 

3. Nhập Category name (bắt buộc; giới hạn thiết kế255 ký tự), cùng Category ID number và Description nếu cần. 

4. Chọn Parent category là Top hoặc một danh mục cha có sẵn. 

5. Chọn _Create category_ ; xác minh danh mục mới trong cây phân cấp. 

### **2.1.2 Use Case (Ca sửdụng)** 

**Tên Use Case:** UC-001 – Add a New Category. 

**Tác nhân:** Administrator/Manager. 

**Điều kiện tiên quyết:** Người dùng đã đăng nhập với quyền quản lý danh mục và truy cập được biểu mẫu Add a category. **Luồng sựkiện chính:** 

1. Tác nhân mởbiểu mẫu Add a category. 

2. Chọn Parent category, nhập Category name hợp lệvà điền trường tùy chọn nếu cần. 

3. Nhấn _Create category_ ; hệthống xác thực và lưu danh mục. 

4. Xác minh danh mục mới xuất hiện trong cây phân cấp. 

### **Luồng thay thế/ngoại lệ:** 

1. A1 – Bỏtrống Name: không lưu và hiển thịlỗi bắt buộc (Required). 

Page 3/33 

Project #2 Black-Box Testing – Moodle LMS 



**VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

2. A2 – Name vượt 255 ký tự: dựkiến báo _Category name too long_ ; xác nhận thông báo thực tế. 

3. A3 – ID number trùng: dựkiến báo ID đã được sửdụng; xác nhận thông báo thực tế. 

4. A4 – Chọn _Cancel_ : rời biểu mẫu và không tạo category. 

**Hậu điều kiện:** Dữliệu hợp lệđược lưu; dữliệu sai hiển thịlỗi đểsửa; khi hủy không phát sinh category mới. 

### **2.1.3 Activity Diagram (Sơ đồhoạt động)** 

1. Bắt đầu; mởbiểu mẫu Add a category. 

2. Nhập Category name, Category ID number, Description và chọn Parent category. 

3. Kiểm tra Name có độdài 1–255 ký tự; nếu không hợp lệ, báo lỗi và quay lại biểu mẫu. 

4. Nếu có ID number, kiểm tra tính duy nhất; nếu trùng, báo lỗi và quay lại biểu mẫu. 

5. Nếu hợp lệ, lưu category, cập nhật cây phân cấp và kết thúc; nếu hủy, kết thúc mà không lưu. 

## **2.2 Thiết kếkiểm thử** 

### **2.2.1 Phân tích giá trịbiên (Boundary Value Analysis – BVA)** 

Category name có giới hạn thiết kế1–255 ký tự; kiểm tra rỗng, 254, 255, 256 và 300 ký tự. Category ID number có giới hạn giao diện dựkiến 100 ký tự; kiểm tra 99, 100 và 101 ký tự. Với dữliệu vượt biên, ghi nhận giao diện cắt bớt hay hệthống từchối. 

### **2.2.2 Phân hoạch tương đương (Equivalence Class Partitioning – ECP)** 

Các lớp đầu vào gồm: Category name rỗng, ASCII hợp lệ, tiếng Việt, ký tựđặc biệt, chỉkhoảng trắng, tên trùng và khoảng trắng đầu/cuối; Category ID number rỗng, dạng số, ký tựđặc biệt, chữ-số, trùng và chuỗi dài; Description rỗng, văn bản ASCII/tiếng Việt và rich text; Parent category là Top hoặc category có sẵn. Tên trùng dựkiến được cho phép; hành vi trim và tên chỉcó khoảng trắng cần xác nhận thực tế. 

Page 4/33 

Project #2 Black-Box Testing – Moodle LMS 



#### **VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

### **2.2.3 Danh sách 30 test case** 

Giá trịduy nhất cần được tạo theo mã test case. Với hành vi phụthuộc phiên bản/cấu hình Moodle, ghi nhận phản hồi thực tếthay vì xem giảđịnh là kết quảđã chạy. 

Bảng 2: Danh sách 30 test case cho Feature 1 – Add Category 

|**Mã TC**|**Kỹ**<br>**thuật**|**Mục tiêu kiểm thử**|**Dữliệu đầu vào chính**|**Kết quảmong đợi**|
|---|---|---|---|---|
|TC-001-<br>001|ECP|Tạo category tại Top|Name hợp lệ; ID duy nhất;<br>Description = test; Parent<br>= Top|Tạo thành công tại<br>cấp gốc.|
|TC-001-|ECP|Name bỏtrống|Name<br>rỗng;<br>ID<br>và|Báo Required; không|
|002|||Description rỗng|tạo category.|
|TC-001-<br>003|ECP|Name dài 200 ký tự|200 ký tựASCII; ID duy<br>nhất|Tạo thành công.|
|TC-001-<br>004|ECP|Name dài 250 ký tự|250 ký tựASCII; ID duy<br>nhất|Tạo thành công.|
|TC-001-|BVA|Name dài 254 ký tự|254 ký tựASCII|Nhận đủchuỗi và tạo|
|005||||thành công.|
|TC-001-|BVA|Name dài 255 ký tự|255 ký tựASCII|Nhận đủchuỗi và tạo|
|006||||thành công.|
|TC-001-|BVA|Name dài 256 ký tự|256 ký tựASCII|Dựkiến từchối với|
|007||||lỗi Name quá dài; ghi<br>nhận thực tế.|
|TC-001-|ECP|Name dài 300 ký tự|300 ký tựASCII|Dựkiến báo Name|
|008||||quá<br>dài;<br>ghi<br>nhận<br>thực tế.|
|TC-001-|ECP|Name có ký tựđặc|`Test & Development #1`|Tạo thành công; hiển|
|009||biệt||thịđúng ký tự.|
|TC-001-|ECP|Name<br>có<br>khoảng|`Category trim`|Ghi nhận hành vi|
|010||trắng đầu/cuối||trim khi lưu.|
|TC-001-|ECP|Name chỉcó khoảng|Name gồm 3 dấu cách|Ghi nhận hành vi|
|011||trắng||lưu/xác thực thực tế.|
|TC-001-|ECP|Tên category trùng|Name đã tồn tại; ID mới|Dựkiến cho phép tên|
|012|||duy nhất|trùng.|
|TC-001-|ECP|ID number rỗng|Name<br>duy<br>nhất;<br>ID<br>và|Tạo thành công; ID|
|013|||Description rỗng|không bắt buộc.|
|TC-001-<br>014|ECP|ID number dạng số|ID = 123456|Lưu ID thành công.|
|TC-001-|ECP|ID number có ký tự|ID = CAT-001|Lưu ID thành công.|
|015||đặc biệt|||
|TC-001-|ECP|ID number trùng|Dùng ID đã tồn tại|Báo lỗi ID đã được|
|016||||sửdụng; không tạo<br>category.|
|TC-001-<br>017|BVA|ID dài 99 ký tự|Chuỗi ASCII duy nhất dài<br>99|Nhận đủgiá trị.|



Còn tiếp ởtrang sau 

Page 5/33 

Project #2 Black-Box Testing – Moodle LMS 



#### **VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

|||Bảng|2 – tiếp theo||
|---|---|---|---|---|
|**Mã TC**|**Kỹ**<br>**thuật**|**Mục tiêu kiểm thử**|**Dữliệu đầu vào chính**|**Kết quảmong đợi**|
|TC-001-|BVA|ID dài 100 ký tự|Chuỗi ASCII duy nhất dài|Nhận đủgiá trịtại|
|018|||100|biên.|
|TC-001-<br>019|BVA|ID dài 101 ký tự|Dán 101 ký tựASCII|Giới hạn tại 100; xác<br>minh<br>giá<br>trị<br>được<br>lưu.|
|TC-001-|ECP|Description rỗng|Description = rỗng|Tạo category thành|
|020||||công.|
|TC-001-|ECP|Description dài 300|Văn bản ASCII dài 300|Lưu<br>Description|
|021||ký tự||thành công.|
|TC-001-|ECP|Description<br>tiếng|`Mô tảdanh mục kiểm`|Lưu và hiển thịđúng|
|022||Việt|`thử`|dấu.|
|TC-001-<br>023|ECP|Description rich text|Đoạn văn có chữin đậm|Lưu định dạng rich<br>text thành công.|
|TC-001-|ECP|Parent là Top|Parent = Top|Category mới thuộc|
|024||||cấp gốc.|
|TC-001-|ECP|Parent là category có|Chọn một category cha tồn|Category<br>mới<br>nằm|
|025||sẵn|tại|dưới đúng category<br>cha.|
|TC-001-|ECP|Chỉchọn một Parent|Chọn lần lượt các category|Tại một thời điểm|
|026|||trong selector|chỉmột Parent được<br>chọn.|
|TC-001-|ECP|Description<br>và<br>ID|Name<br>hợp<br>lệ;|Tạo category thành|
|027||rỗng|ID/Description rỗng|công.|
|TC-001-|ECP|Name và ID hợp lệ|Name<br>ASCII;<br>ID<br>chữ-số|Tạo thành công và|
|028|||duy nhất; Parent = Top|dữliệu được lưu.|
|TC-001-|Use-case|Hủy tạo category|Nhập<br>dữ<br>liệu<br>rồi<br>chọn|Không tạo category;|
|029|||_Cancel_|quay lại trang trước.|
|TC-001-|Use-case|Xác minh category|Tạo<br>mới<br>với|Tên, ID, Description|
|030||sau khi tạo|Name/ID/Description<br>đã biết|và Parent hiển thị<br>đúng.|



## **2.3 Triển khai Katalon Recorder** 

Có thểtổchức kịch bản trong suite `TS_001_Add_Category.krecorder` , với dữliệu riêng theo mã test case. Trước khi chạy, xác nhận quyền Administrator/Manager, chuẩn bịcategory cha và ID trùng dành riêng cho test. Cleanup chỉxóa category do bộtest tạo, không xóa category có sẵn hoặc category cha dùng chung. Xác minh thông báo và mởlại cây category đểđối chiếu Name, ID, Description, Parent. Ghi PASS/FAIL/NOT RUN cùng ảnh hoặc log sau khi thực thi; chưa chạy thì không đánh dấu PASS. 

Page 6/33 

Project #2 Black-Box Testing – Moodle LMS 



**VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

# **3 Feature 002: Create a Group in Course – Đặng Ngọc Khiêu** 

## **3.1 Đặc tảtính năng** 

### **3.1.1 Mô tảngắn gọn và hướng dẫn sửdụng** 

**Mô tả:** Create group in course cho phép người dùng có quyền quản lý khóa học (Teacher/Administrator) tạo nhóm trong một khóa học Moodle. Biểu mẫu gồm Group name, Group ID number, Description (hỗtrợHTML/TinyMCE), Enrolment key, Group membership visibility, tùy chọn hiển thị/tin nhắn nhóm và ảnh đại diện. Quyền, giới hạn và các tùy chọn cần đối chiếu với Moodle được kiểm thử. **Hướng dẫn sửdụng:** 

1. Đăng nhập bằng Teacher hoặc Administrator và mởkhóa học có sẵn (ví dụcourse id=2). 

2. Truy cập _Participants → Groups_ , sau đó chọn _Create group_ . 

3. Nhập Group name (bắt buộc; giới hạn thiết kế254–255 ký tự) và trường tùy chọn cần kiểm thử. 

4. Chọn Group membership visibility, cấu hình tùy chọn phụthuộc và tải ảnh nếu cần. 

5. Chọn _Save changes_ ; xác minh nhóm trong danh sách Groups của khóa học. 

### **3.1.2 Use Case (Ca sửdụng)** 

**Tên Use Case:** UC-002 – Create Group in Course. 

**Tác nhân:** Teacher/Administrator. 

**Điều kiện tiên quyết:** Người dùng đã đăng nhập với quyền quản lý khóa học; khóa học tồn tại và truy cập được trang Groups (ví dụ `group/index.php?id=2` ). **Luồng sựkiện chính:** 

1. Tác nhân chọn tạo nhóm mới trong khóa học. 

2. Hệthống hiển thịbiểu mẫu cấu hình nhóm. 

3. Tác nhân nhập Group name hợp lệvà các trường tùy chọn cần thiết. 

4. Tác nhân chọn _Save changes_ ; hệthống xác thực và lưu nhóm. 

5. Xác minh nhóm xuất hiện trong danh sách của khóa học. 

Page 7/33 

Project #2 Black-Box Testing – Moodle LMS 



#### **VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

### **Luồng thay thế/ngoại lệ:** 

1. E1 – Thiếu Group name: không lưu và hiển thịRequired. 

2. E2 – Enrolment key dài 253–255 ký tự: nguồn đầu vào ghi nhận khảnăng lỗi database _Data too long_ ; xác minh thực tế, không xem đây là hành vi chuẩn được bảo đảm. 

3. E3 – File ảnh không hợp lệhoặc ảnh hỏng: hệthống từchối/loại bỏfile hoặc cảnh báo; ghi nhận phản hồi thực tế. 

4. E4 – Chọn _Cancel_ : rời biểu mẫu mà không tạo nhóm. 

**Hậu điều kiện:** Nhóm hợp lệđược lưu; dữliệu sai hiển thịlỗi đểsửa; khi hủy, không tạo nhóm. 

### **3.1.3 Activity Diagram (Sơ đồhoạt động)** 

1. Bắt đầu; mởbiểu mẫu Create group. 

2. Nhập Group name, Group ID number, Description, Enrolment key; chọn Visibility và tải ảnh nếu cần. 

3. Kiểm tra Group name bắt buộc và giới hạn độdài; nếu không hợp lệ, báo lỗi và quay lại biểu mẫu. 

4. Nếu có ảnh, kiểm tra file; nếu không hợp lệ, ghi nhận lỗi/cảnh báo. 

5. Nếu dữliệu hợp lệ, lưu nhóm và cập nhật danh sách; nếu chọn Cancel, kết thúc mà không lưu. 

## **3.2 Thiết kếkiểm thử** 

### **3.2.1 Phân tích giá trịbiên (Boundary Value Analysis – BVA)** 

Group name: kiểm tra 0, 1, 2, 253, 254 và 255 ký tự; nguồn đầu vào nêu giới hạn 254–255 nên cần xác minh giá trịthực sựđược nhận/lưu. Group ID number: kiểm tra 0, 1, 2, 99, 100 và 101 ký tự(giới hạn giao diện dựkiến 100). Enrolment key: kiểm tra 0, 1, 2, 253, 254 và 255 ký tự; các trường hợp dài dùng đểtái hiện vấn đềdatabase đã nêu, không xem lỗi hệthống là hành vi chấp nhận được. 

Page 8/33 

Project #2 Black-Box Testing – Moodle LMS 



#### **VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

### **3.2.2 Phân hoạch tương đương (Equivalence Class Partitioning – ECP)** 

Các lớp đầu vào gồm: Group name rỗng, ASCII hợp lệvà tiếng Việt; Group ID number rỗng hoặc chuỗi hợp lệ; Description rỗng, tiếng Việt hoặc HTML rich text; Enrolment key rỗng hoặc có giá trị; Visibility gồm Visible, Only visible to members, Only see own membership và Hidden; ảnh không chọn, JPG/PNG hợp lệ, file .txt và ảnh hỏng. Các checkbox phụthuộc Visibility được xác minh trên giao diện và sau khi lưu. 

### **3.2.3 Decision Table** 

Kiểm tra tổhợp Group membership visibility với Show group và Group messaging: với Visible và Only visible to members, kiểm tra bốn tổhợp bật/tắt; với Only see own membership và Hidden, xác minh các điều khiển phụthuộc bịẩn như mô tảđầu vào. Hành vi cần xác nhận trên phiên bản Moodle thực tế. 

### **3.2.4 Danh sách 57 test case** 

Tạo tên nhóm duy nhất cho các trường hợp lưu thành công; chuẩn bịảnh JPG/PNG, file văn bản và ảnh hỏng. Với giới hạn độdài hoặc phản hồi phụthuộc phiên bản, ghi chính xác hành vi thực tế. 

Bảng 3: Danh sách 57 test case cho Feature 2 – Create Group in Course 

|**Mã TC**|**Kỹ**<br>**thuật**|**Mục tiêu kiểm thử**|**Dữliệu đầu vào chính**|**Kết quảmong đợi**|
|---|---|---|---|---|
|TC-002-|ECP|Group<br>name<br>bỏ|Bỏtrống Group name|Không<br>tạo<br>nhóm;|
|001||trống||hiện Required.|
|TC-002-|ECP|Tên ASCII hợp lệ|Group<br>name<br>=|Tạo một nhóm; tên|
|002|||`CG_ASCII_001`|giữnguyên.|
|TC-002-|ECP|Tên tiếng Việt|Group name = `Nhóm Kiểm`|Tạo nhóm; hiển thị|
|003|||`thử001`|đúng dấu.|
|TC-002-<br>004|ECP|Group ID đểtrống|Group ID number = rỗng|Tạo thành công; ID<br>trống khi mởlại.|
|TC-002-|ECP|Group<br>ID<br>thông|Group ID = `CG_ID_005`|Lưu thành công; mở|
|005||thường||lại đúng ID.|
|TC-002-<br>006|ECP|Description đểtrống|Description = rỗng|Tạo thành công; mô<br>tảtrống khi mởlại.|
|TC-002-|ECP|Description<br>tiếng|`Nhóm thực hành kiểm`|Lưu và hiển thịđúng|
|007||Việt|`thửphần mềm`|dấu.|
|TC-002-|ECP|Description HTML|Rich text gồm đoạn in đậm|Lưu và hiển thịđúng|
|008|||và đoạn thứhai|rich text.|
|TC-002-<br>009|ECP|Enrolment<br>key<br>để<br>trống|Enrolment key = rỗng|Lưu thành công; xác<br>nhận khóa trống.|



Còn tiếp ởtrang sau 

Page 9/33 

Project #2 Black-Box Testing – Moodle LMS 



#### **VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

|||Bảng|3 – tiếp theo|||
|---|---|---|---|---|---|
|**Mã TC**|**Kỹ**<br>**thuật**|**Mục tiêu kiểm thử**|**Dữliệu đầu vào chí**|**nh**|**Kết quảmong đợi**|
|TC-002-<br>010|ECP|Enrolment key có giá<br>trị|`CGkey010!`||Lưu<br>thành<br>công;<br>Reveal hiển thịđúng<br>khóa.|
|TC-002-|ECP|Visibility Visible|Chọn Visible||Tạo<br>thành<br>công;|
|011|||||kiểm tra Show group<br>và Group messaging.|
|TC-002-<br>012|ECP|Only<br>visible<br>to<br>members|Chọn<br>Only<br>visible<br>members|to|Tạo<br>thành<br>công;<br>kiểm tra điều khiển<br>phụthuộc.|
|TC-002-<br>013|ECP|Only<br>see<br>own<br>membership|Chọn<br>Only<br>see<br>membership|own|Show<br>group<br>và<br>Group messaging bị<br>ẩn theo đặc tả.|
|TC-002-<br>014|ECP|Visibility Hidden|Chọn Hidden||Show<br>group<br>và<br>Group messaging bị<br>ẩn theo đặc tả.|
|TC-002-<br>015|ECP|Show group bật|Visible; Show group =|On|Lưu<br>thành<br>công;<br>checkbox bật khi mở<br>lại.|
|TC-002-<br>016|ECP|Show group tắt|Visible; Show group =|Off|Lưu<br>thành<br>công;<br>checkbox tắt khi mở<br>lại.|
|TC-002-<br>017|ECP|Group messaging =<br>No|Visible; Messaging =|No|Lưu thành công; mở<br>lại hiển thịNo.|
|TC-002-|ECP|Group messaging =|Visible; Messaging =|Yes|Lưu thành công; mở|
|018||Yes|||lại hiển thịYes.|
|TC-002-<br>019|ECP|Không tải ảnh|Không chọn New pict|ure|Tạo<br>nhóm<br>thành<br>công; không có ảnh<br>tùy chỉnh.|
|TC-002-|ECP|Ảnh JPG hợp lệ|New<br>picture|=|Lưu nhóm; ảnh đầu|
|020|||`testcase20.jpg`||ra 100_×_100 pixel.|
|TC-002-|ECP|Ảnh PNG hợp lệ|New<br>picture|=|Lưu nhóm; ảnh đầu|
|021|||`testcase21.png`||ra 100_×_100 pixel.|
|TC-002-|ECP|File không phải ảnh|New<br>picture|=|File bịtừchối/loại|
|022|||`testcase22.txt`||bỏ; ghi nhận cảnh<br>báo.|
|TC-002-<br>023|ECP|Ảnh hỏng nội dung|New<br>picture<br>`testcase23.png`<br>hỏng)|=<br>(file|Không có ảnh nhóm<br>hợp lệsau xửlý.|
|TC-002-<br>024|ECP|Hủy chọn ảnh|Mởfile picker rồi <br>không chọn file|đóng,|Tạo nhóm không có<br>ảnh.|
|TC-002-|BVA|Group name 0 ký tự|Name rỗng||Không<br>tạo<br>nhóm;|
|025|||||hiện Required.|
|TC-002-<br>026|BVA|Group name 1 ký tự|Name = `N`||Lưu thành công; mở<br>lại đúng 1 ký tự.|



Còn tiếp ởtrang sau 

Page 10/33 

Project #2 Black-Box Testing – Moodle LMS 



#### **VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

|||Bảng|3 – tiếp theo||
|---|---|---|---|---|
|**Mã TC**|**Kỹ**<br>**thuật**|**Mục tiêu kiểm thử**|**Dữliệu đầu vào chính**|**Kết quảmong đợi**|
|TC-002-|BVA|Group name 2 ký tự|Name = `NN`|Lưu thành công; mở|
|027||||lại đúng 2 ký tự.|
|TC-002-|BVA|Group name 253 ký|Chuỗi 253 ký tựN|Lưu thành công; mở|
|028||tự||lại đủ253 ký tự.|
|TC-002-|BVA|Group name 254 ký|Chuỗi 254 ký tựN|Lưu thành công; mở|
|029||tự||lại đủ254 ký tự.|
|TC-002-|BVA|Group name 255 ký|Nhập 255 ký tựASCII|Nguồn dựkiến UI|
|030||tự||giữtối đa 254; xác<br>minh giá trịlưu.|
|TC-002-|BVA|Group ID 0 ký tự|Group ID = rỗng|Lưu thành công.|
|031|||||
|TC-002-|BVA|Group ID 1 ký tự|Group ID = `I`|Lưu thành công.|
|032|||||
|TC-002-<br>033|BVA|Group ID 2 ký tự|Group ID = `II`|Lưu thành công.|
|TC-002-<br>034|BVA|Group ID 99 ký tự|Chuỗi 99 ký tựI|Lưu thành công.|
|TC-002-|BVA|Group ID 100 ký tự|Chuỗi 100 ký tựI|Lưu thành công.|
|035|||||
|TC-002-|BVA|Group ID 101 ký tự|Nhập 101 ký tựASCII|Nguồn dựkiến UI|
|036||||giữtối đa 100; xác<br>minh giá trịlưu.|
|TC-002-|BVA|Enrolment key 0 ký|Key = rỗng|Lưu thành công.|
|037||tự|||
|TC-002-|BVA|Enrolment key 1 ký|Key = `K`|Lưu thành công.|
|038||tự|||
|TC-002-|BVA|Enrolment key 2 ký|Key = `KK`|Lưu thành công.|
|039||tự|||
|TC-002-|BVA|Key dài 253 ký tự|Nhập khóa 253 ký tự|Tái hiện lỗi DB đã|
|040||||nêu nếu xảy ra; ghi<br>nhận nguyên văn.|
|TC-002-|BVA|Key dài 254 ký tự|Nhập khóa 254 ký tự|Tái hiện lỗi DB đã|
|041||||nêu nếu xảy ra; ghi<br>nhận nguyên văn.|
|TC-002-|BVA|Key dài 255 ký tự|Nhập khóa 255 ký tự|Tái hiện lỗi DB đã|
|042||||nêu nếu xảy ra; ghi<br>nhận nguyên văn.|
|TC-002-|Decision|R01: Visible, Show|Chọn<br>Visible;<br>Show<br>On;|Lưu cấu hình thành|
|043|Table|On, Msg No|Messaging No|công.|
|TC-002-|Decision|R02: Visible, Show|Chọn<br>Visible;<br>Show<br>On;|Lưu cấu hình thành|
|044|Table|On, Msg Yes|Messaging Yes|công.|
|TC-002-|Decision|R03: Visible, Show|Chọn Visible; Show Off;|Lưu cấu hình thành|
|045|Table|Off, Msg No|Messaging No|công.|
|TC-002-|Decision|R04: Visible, Show|Chọn Visible; Show Off;|Lưu cấu hình thành|
|046|Table|Off, Msg Yes|Messaging Yes|công.|



Còn tiếp ởtrang sau 

Page 11/33 

Project #2 Black-Box Testing – Moodle LMS 



#### **VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

|||Bảng|3 – tiếp theo||||
|---|---|---|---|---|---|---|
|**Mã TC**|**Kỹ**<br>**thuật**|**Mục tiêu kiểm thử**|**Dữliệu đầu **|**vào chí**|**nh**|**Kết quảmong đợi**|
|TC-002-<br>047|Decision<br>Table|R05: Members only,<br>Show On, Msg No|Chọn<br>Only<br>members; On;|visible<br> No|to|Lưu cấu hình thành<br>công.|
|TC-002-<br>048|Decision<br>Table|R06: Members only,<br>Show On, Msg Yes|Chọn<br>Only<br>members; On;|visible<br> Yes|to|Lưu cấu hình thành<br>công.|
|TC-002-<br>049|Decision<br>Table|R07: Members only,<br>Show Off, Msg No|Chọn<br>Only<br>members; Off;|visible<br> No|to|Lưu cấu hình thành<br>công.|
|TC-002-<br>050|Decision<br>Table|R08: Members only,<br>Show Off, Msg Yes|Chọn<br>Only<br>members; Off;|visible<br> Yes|to|Lưu cấu hình thành<br>công.|
|TC-002-<br>051|Decision<br>Table|R09:<br>Only<br>own<br>membership|Chọn<br>Only<br>membership|see|own|Kiểm tra Show group<br>và Messaging bịẩn.|
|TC-002-<br>052|Decision<br>Table|R10: Hidden|Chọn Hidden|||Kiểm tra Show group<br>và Messaging bịẩn.|
|TC-002-<br>053|Use-case|Luồng<br>chính<br>tối<br>thiểu|Chỉnhập Gro<br>nhất; trường k|up name <br>hác mặc|duy<br>định|Tạo<br>nhóm<br>thành<br>công, chưa có thành<br>viên.|
|TC-002-<br>054|Use-case|Sửa lỗi Required|Lần đầu bỏ<br>nhập<br>`CG_UC_`<br>lưu|trống n<br>`RECOVER`|ame;<br>rồi|Lượt<br>đầu<br>báo<br>Required;<br>lượt<br>sau<br>lưu thành công.|
|TC-002-<br>055|Use-case|Hủy form trống|Chọn<br>Cancel<br>trống|trên<br>|form|Quay<br>về<br>Groups;<br>không có nhóm mới.|
|TC-002-<br>056|Use-case|Hủy sau khi nhập|Nhập<br>dữ<br>liệ<br>Cancel|u<br>rồi<br>|chọn|Không<br>tạo<br>nhóm,<br>không lưu dữliệu.|
|TC-002-<br>057|Use-case|Thay đổi Visibility|Visible<br>_→_<br>Visible; chỉlưu|Hidden<br> cuối|_→_|Lưu thành công cấu<br>hình<br>Visible<br>cuối<br>cùng.|



## **3.3 Triển khai Katalon Recorder** 

Có thểtổchức kịch bản trong suite `TS_002_Create_Group.krecorder` . Trước khi chạy, xác nhận Teacher/Administrator có quyền chỉnh sửa khóa học, khóa học kiểm thửtồn tại và chuẩn bịfixture ảnh hợp lệ, file .txt cùng ảnh hỏng. Dùng tên nhóm duy nhất theo mã test case; cleanup chỉxóa nhóm do bộtest tạo trong khóa học kiểm thử. Xác minh thông báo, nhóm trong danh sách, giá trịlưu khi mởlại và trạng thái ảnh/visibility. Ghi lỗi database do Enrolment key quá dài như lỗi quan sát, không xem là PASS chức năng. Ghi PASS/FAIL/NOT RUN và ảnh/log sau khi thực thi. 

Page 12/33 

Project #2 Black-Box Testing – Moodle LMS 



**VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

# **4 Feature 003: Add a New User – Đặng Đình Thiên Quân** 

## **4.1 Đặc tảtính năng** 

### **4.1.1 Mô tảngắn gọn và hướng dẫn sửdụng** 

**Tên chức năng:** Add a new user – Thêm người dùng mới. **Hệthống:** MuTMS / Moodle LMS. 

Chức năng cho phép Admin tạo tài khoản Moodle bằng các thông tin định danh như Username, Password, First name, Last name và Email address. Admin có thểbổsung City/town, Country, Timezone, Language, Description, ảnh đại diện, thông tin liên hệvà các trường hồsơ khác. Ngoài ra, biểu mẫu có các thuộc tính tài khoản như Authentication method, Email display, Suspended account và Force password change. Moodle kiểm tra tính bắt buộc, định dạng, độdài, tính duy nhất và các ràng buộc được cấu hình trước khi lưu. 

**Hướng dẫn sửdụng:** 

1. Đăng nhập bằng tài khoản Admin có quyền tạo người dùng. 

2. Truy cập _Site administration → Users → Accounts → Add a new user_ . 

3. Nhập Username, Password, First name, Last name và Email address; nhập các thông tin tùy chọn nếu cần. 

4. Chọn Authentication method, Email display và các thuộc tính tài khoản cần kiểm thử. 

5. Nhấn _Create user_ ; nếu tạo thành công, mở _Browse list of users_ đểtìm và kiểm tra hồsơ vừa tạo. 

### **4.1.2 Use Case (Ca sửdụng)** 

**Tác nhân chính:** Admin. Moodle LMS tiếp nhận, kiểm tra, lưu dữliệu và phản hồi kết quả. Dịch vụemail chỉcó thểtham gia khi chọn tạo mật khẩu tựđộng và thông báo cho người dùng; việc gửi/nhận email không thuộc phạm vi xác minh của bộtest hiện tại. 

**Tiền điều kiện:** Moodle và cơ sởdữliệu hoạt động; Admin đã đăng nhập và có quyền tạo người dùng; các Username/Email dùng đểtạo mới chưa tồn tại; dữliệu hoặc file fixture cần thiết đã được chuẩn bị. Các trường không thuộc phạm vi test giữgiá trị hợp lệ/mặc định. **Luồng chính:** 

Page 13/33 

Project #2 Black-Box Testing – Moodle LMS 



#### **VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

1. Admin đăng nhập và mở _Add a new user_ từSite administration. 

2. Moodle hiển thịbiểu mẫu tạo người dùng. 

3. Admin nhập các trường bắt buộc và, tùy test case, các trường tùy chọn/thuộc tính tài khoản. 

4. Admin nhấn _Create user_ . 

5. Moodle xác thực dữliệu; nếu hợp lệ, lưu tài khoản và hiển thịkết quảtạo thành công. 

6. Admin mở _Browse list of users_ hoặc hồsơ đểxác minh thông tin đã lưu. 

### **Luồng thay thế/ngoại lệ:** 

1. Bỏtrống trường bắt buộc: hiển thị _Required_ , không tạo tài khoản. 

2. Username đã tồn tại hoặc chứa ký tựkhông hợp lệ: từchối và hiển thịthông báo tương ứng. 

3. Email sai định dạng hoặc đã tồn tại: hiển thịlỗi xác thực, không lưu. 

4. Mật khẩu không đáp ứng chính sách: xửlý theo chính sách cấu hình; cần ghi nhận thông báo thực tế. 

5. Dữliệu vượt giới hạn: kiểm tra hành vi giới hạn ký tựhoặc thông báo lỗi của từng trường. 

6. File ảnh không hợp lệ: không chấp nhận file văn bản/file không phải ảnh làm ảnh đại diện. 

7. Admin chọn tạo mật khẩu tựđộng: Moodle tạo mật khẩu và có thểgửi thông báo; chỉkiểm tra hành vi gửi khi có môi trường email phù hợp. 

8. Admin nhấn _Cancel_ : thoát biểu mẫu, không phát sinh tài khoản mới. 

**Hậu điều kiện:** Nếu hợp lệ, tài khoản và thuộc tính được lưu, xuất hiện trong Browse list of users và có thểmởhồsơ đểkiểm tra. Nếu không hợp lệ, không tạo tài khoản, biểu mẫu cùng thông báo lỗi được giữlại. Nếu hủy, không tạo tài khoản. 

### **4.1.3 Activity Diagram (Sơ đồhoạt động)** 

1. Start _→_ Admin mởbiểu mẫu Add a new user. 

2. Nhập thông tin bắt buộc, thông tin tùy chọn và thuộc tính tài khoản. 

Page 14/33 

Project #2 Black-Box Testing – Moodle LMS 



**VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

3. Chọn Create user; Moodle kiểm tra dữliệu. 

4. Nếu thiếu trường, trùng/sai Username hoặc Email, mật khẩu không đạt chính sách, dữliệu vượt giới hạn hay file ảnh không hợp lệ: hiển thịlỗi tương ứng, quay lại biểu mẫu đểsửa. 

5. Nếu hợp lệ: lưu tài khoản, hiển thịxác nhận, Admin kiểm tra trong Browse list of users _→_ End. 

6. Nếu Admin chọn Cancel: thoát biểu mẫu mà không tạo tài khoản _→_ End. 

Page 15/33 

Project #2 Black-Box Testing – Moodle LMS 



#### **VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

## **4.2 Thiết kếkiểm thử** 

Bộtest case Feature 3 có 25 mã TC-003-001–TC-003-025, thiết kếtheo ECP, BVA, Decision Table và Use-case Testing. Các giới hạn độdài dưới đây là giới hạn dùng trong tài liệu nguồn; cần kiểm chứng với giao diện/cấu hình Moodle thực tế. Một test case có thểliên quan nhiều kỹthuật nhưng được thống kê theo nhóm chính. 

### **4.2.1 Equivalence Class Partitioning (ECP)** 

Bảng 4: Các lớp tương đương cho Add a new user 

|**Trường**|**Lớp hợp lệ**|**Lớp không hợp lệ**|
|---|---|---|
|Username|Chưa tồn tại, chỉdùng ký<br>tựđược phép|Bỏtrống; đã tồn tại; chứa<br>khoảng trắng|
|First name / Last name|Có giá trịhợp lệ|Bỏtrống|
|Email address|Đúng định dạng, chưa được<br>dùng|Bỏtrống; sai định dạng; đã<br>tồn tại|
|New password|Đáp ứng chính sách Moodle|Không đạt chính sách|
|Authentication method|Phương thức được hỗtrợ, ví<br>dụNo login|Không xét lớp sai trong<br>phạm vi hiện tại|
|Email display|Một lựa chọn hợp lệ|Không xét lớp sai trong<br>phạm vi hiện tại|
|New picture|File ảnh hợp lệ|File văn bản hoặc file không<br>phải ảnh|
|Trường tùy chọn|Giá trịhợp lệtrong giới hạn|Vượt giới hạn độdài|



Các test case ECP chính là TC-003-001–TC-003-012: lần lượt kiểm tra Username rỗng/trùng/có khoảng trắng; First name rỗng; Last name rỗng; Email rỗng/sai định dạng/trùng; mật khẩu không đạt chính sách; Authentication method = No login; Email display = Allow everyone to see my email address; và file ảnh .txt không hợp lệ. TC003-022 cũng đại diện cho lớp dữliệu hợp lệcủa các trường tùy chọn. 

### **4.2.2 Boundary Value Analysis (BVA)** 

BVA tập trung vào độdài tối thiểu/tối đa của các trường bắt buộc và giới hạn của 12 trường tùy chọn. Các độdài được kiểm thửbằng cách nhập/dán qua giao diện (không gán trực tiếp thuộc tính HTML); sau khi lưu thành công, mởlại hồsơ đểso sánh dữ liệu thực tế. 

Page 16/33 

Project #2 Black-Box Testing – Moodle LMS 



#### **VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

Bảng 5: Giới hạn đầu vào trong thiết kếBVA Feature 3 

|**Trường**|**Giới hạn thiết kế**|**Giá trịcần kiểm tra**|
|---|---|---|
|Username|100 ký tự|1, 100, 101|
|First name|100 ký tự|1, 100, 101|
|Last name|100 ký tự|1, 100, 101|
|Email address|100 ký tự|Email hợp lệngắn nhất được chọn, 100, 101|
|City/town|120 ký tự|120, 121|
|MoodleNet profile ID|255 ký tự|255, 256|
|First name – phonetic|255 ký tự|255, 256|
|Last name – phonetic|255 ký tự|255, 256|
|Middle name|255 ký tự|255, 256|
|Alternate name|255 ký tự|255, 256|
|ID number|255 ký tự|255, 256|
|Institution|255 ký tự|255, 256|
|Department|255 ký tự|255, 256|
|Phone|20 ký tự|20, 21|
|Mobile phone|20 ký tự|20, 21|
|Address|255 ký tự|255, 256|



Các test case BVA chính: TC-003-013 (giá trịnhỏnhất trường bắt buộc), TC-003-014 (100 ký tựởtrường bắt buộc), TC-003-015 (Username 101 ký tự), TC-003-016 (First name, Last name, Email 101 ký tự), TC-003-017 (12 trường tùy chọn tại giới hạn tối đa) và TC-003-018 (12 trường tùy chọn vượt một ký tự). Ghi nhận riêng trường hợp giao diện cắt bớt dữliệu và trường hợp từchối/lưu lỗi. 

### **4.2.3 Decision Table Testing** 

Bảng 6: Các <u>quy</u> tắc <u>quyết</u> định cho Add a new user 

|**Quy tắc**|**Điều kiện**|**Kết quảmong đợi**|
|---|---|---|
|R01|Các trường bắt buộc đều hợp lệ|Tạo người dùng thành công|
|R02|Username bỏtrống|Không tạo; báo Required|
|R03|First name bỏtrống|Không tạo; báo Required|
|R04|Last name bỏtrống|Không tạo; báo Required|
|R05|Email sai định dạng|Không tạo; báo Invalid email<br>address|
|R06|Username đã tồn tại và Email sai<br>định dạng|Báo đồng thời hai lỗi; không tạo|
|R07|Mật khẩu không đạt chính sách|Ghi nhận phản hồi xác thực cấu<br>hình|
|R08|Suspended account và Force<br>password change cùng bật|Tạo thành công và lưu cảhai thuộc<br>tính|



Page 17/33 

Project #2 Black-Box Testing – Moodle LMS 



#### **VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

Các test case Decision Table chính: TC-003-019 kiểm tra R06; TC-003-020 kiểm tra R08. R02–R05 và R07 được bao phủđồng thời bởi các test case ECP; R01 được bao phủbởi TC-003-021. 

### **4.2.4 Use-case Testing** 

Các luồng kiểm thửgồm tạo người dùng tối thiểu, tạo đầy đủthông tin, sửa dữliệu sau lỗi Required, dùng Generate password and notify user, và hủy sau khi nhập. Chúng tương ứng với TC-003-021–TC-003-025 trong bảng tổng hợp dưới đây. Việc gửi/nhận email không được xem là đã xác minh nếu chưa có hộp thư kiểm thử. 

### **4.2.5 Danh sách test case, dữliệu và kết quảmong đợi Feature 3** 

Các trường không thuộc mục tiêu của test case dùng dữliệu hợp lệtheo môi trường; Username/Email mới dùng hậu tốtương ứng mã test case (XXX), trừtest trùng. Mật khẩu kiểm thửphải tuân thủchính sách cấu hình và được lưu ngoài báo cáo. Với các trường vượt giới hạn, xác minh dữliệu không được lưu quá giới hạn; ghi lại chính xác giao diện cắt bớt hay từchối. 

Bảng 7: Test case Feature 3 với dữliệu và kết quảmong đợi 

|**Test ID**|**Kỹthuật**|**Dữliệu/điều kiện và thao**<br>**tác**|**Kết quảmong đợi và **<br>**minh**|**xác**|
|---|---|---|---|---|
|TC-003-|ECP|Username<br>để<br>trống;<br>các|Không<br>tạo<br>user;<br>hiển|thị|
|001||trường<br>khác<br>hợp<br>lệ;<br>nhấn<br>Create user.|Required tại Username; kiểm<br>user không có trong danh sá|tra<br>ch.|
|TC-003-|ECP|Username =`au_exist`; Email|Từchối Username trùng và|giữ|
|002||mới hợp lệ; nhấn Create user.|biểu mẫu; xác minh thông <br>lỗi, không phát sinh user mớ|báo<br>i.|
|TC-003-|ECP|Username chứa khoảng trắng|Từchối ký tựkhông hợp lệ|theo|
|003||(ví dụ`user test`); các trường<br>khác hợp lệ.|phản hồi Moodle; không tạo|user.|
|TC-003-|ECP|First<br>name<br>để<br>trống;|Không<br>tạo<br>user;<br>hiển|thị|
|004||Username,<br>Last<br>name,<br>Email hợp lệ.|Required tại First name.||
|TC-003-|ECP|Last<br>name<br>để<br>trống;|Không<br>tạo<br>user;<br>hiển|thị|
|005||Username,<br>First<br>name,<br>Email hợp lệ.|Required tại Last name.||
|TC-003-|ECP|Email<br>address<br>để<br>trống;|Không<br>tạo<br>user;<br>hiển|thị|
|006||Username và tên hợp lệ.|Required tại Email address.||



Còn tiếp ởtrang sau 

Page 18/33 

Project #2 Black-Box Testing – Moodle LMS 



#### **VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

Bảng 7 – tiếp theo 

|**Test ID**|**Kỹthuật**|**Dữliệu/điều kiện và thao**<br>**tác**|**Kết quảmong đợi và xác**<br>**minh**|
|---|---|---|---|
|TC-003-|ECP|Email<br>address<br>=|Không tạo user; hiển thịlỗi định|
|007||`not-an-email`;<br>các<br>trường<br>khác hợp lệ.|dạng email (ví dụInvalid email<br>address).|
|TC-003-|ECP|Email<br>=|Từchối Email trùng; xác minh|
|008||`au_exist@example.com`;<br>Username mới hợp lệ.|lỗi và không tạo user.|
|TC-003-|ECP|Dùng mật khẩu thửnghiệm|Nếu chính sách được áp dụng,|
|009||không đáp ứng chính sách đã<br>cấu hình; các trường khác hợp<br>lệ.|không tạo user và hiển thịlỗi<br>chính sách; ghi đúng phản hồi<br>thực tế.|
|TC-003-|ECP|Chọn Authentication method|Tạo user nếu cấu hình Moodle|
|010||= _No login_; nhập các trường<br>bắt buộc còn lại hợp lệ; lưu.|cho phép; mởlại hồsơ và xác<br>minh Authentication method đã<br>lưu là No login.|
|TC-003-|ECP|Chọn Email display = _Allow_|Tạo user; mởhồsơ và xác minh|
|011||_everyone_<br>_to_<br>_see_<br>_my_<br>_email_<br>_address_; lưu user hợp lệ.|đúng lựa chọn Email display.|
|TC-003-|ECP|Tải fixture `testcase12.txt`|File .txt không được chấp nhận|
|012||làm ảnh đại diện rồi gửi biểu<br>mẫu.|làm ảnh; ghi nhận thông báo,<br>không kết luận việc upload thành<br>công.|
|TC-003-|BVA|Username/First<br>name/Last|Tạo user; mởhồsơ và xác minh|
|013||name mỗi trường 1 ký tự;<br>Email là địa chỉhợp lệ, duy<br>nhất ngắn nhất đã chuẩn bị.|nguyên vẹn các giá trịbiên dưới.|
|TC-003-|BVA|Username, First name, Last|Tạo user nếu giới hạn thiết kế|
|014||name dài 100 ký tự; Email hợp<br>lệ, duy nhất dài 100 ký tự.|được xác nhận; kiểm tra đủ100<br>ký tựsau khi lưu.|
|TC-003-|BVA|Username dài 101 ký tự; các|Không lưu Username dài hơn 100|
|015||trường khác hợp lệ.|ký tự: giao diện từchối hoặc cắt<br>còn tối đa 100; ghi nhận hành vi<br>và xác minh hồsơ.|
|TC-003-|BVA|First name, Last name và|Từng giá trịvượt giới hạn không|
|016||Email lần lượt dài 101 ký tự;|được lưu quá 100 ký tự; ghi nhận|
|||chạy từng trường, các trường<br>còn lại hợp lệ.|cắt bớt/từchối và thông báo<br>thực tế.|



Còn tiếp ởtrang sau 

Page 19/33 

Project #2 Black-Box Testing – Moodle LMS 



#### **VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

Bảng 7 – tiếp theo 

|**Test ID**|**Kỹthuật**|**Dữliệu/điều kiện và thao**<br>**tác**|**Kết quảmong đợi và xác**<br>**minh**|
|---|---|---|---|
|TC-003-<br>017|BVA|Nhập 12 trường tùy chọn tại<br>giới hạn trong Bảng 5: City<br>120; Phone/Mobile 20; các<br>trường còn lại 255 ký tự.|Lưu được dữliệu biên hợp lệ; mở<br>hồsơ và so sánh độdài/nội dung<br>của từng trường.|
|TC-003-|BVA|Với từng 12 trường tùy chọn,|Không lưu giá trịdài quá giới|
|018||nhập giá trịdài hơn giới hạn<br>1 ký tựtheo Bảng 5.|hạn; ghi nhận trường hợp bịcắt<br>hay bịtừchối, kiểm tra lại hồsơ.|
|TC-003-|Decision|R06: Username = `au_exist`,|Hiển thịcảlỗi Username trùng và|
|019|Table|Email<br>sai<br>định<br>dạng;<br>các<br>trường<br>khác<br>hợp<br>lệ;<br>nhấn<br>Create user.|Email sai định dạng; không tạo<br>user.|
|TC-003-|Decision|Các<br>trường<br>bắt<br>buộc<br>hợp|Tạo<br>user;<br>mở<br>hồ<br>sơ<br>và<br>xác|
|020|Table|lệ; bật đồng thời Suspended<br>account và Force password<br>change; lưu.|minh cảhai thuộc tính đều được<br>lưu/bật.|
|TC-003-|Use-case|Chỉnhập các trường bắt buộc|Tạo thành công; user xuất hiện|
|021||hợp lệ, dùng Username/Email<br>mới; các trường tùy chọn để<br>mặc định; nhấn Create user.|trong Browse list of users và mở<br>được hồsơ.|
|TC-003-<br>022|Use-case|Nhập các trường bắt buộc<br>và tùy chọn hợp lệ; tải ảnh<br>fixture `testcase22.png`; lưu.|Tạo user; hồsơ hiển thịđúng dữ<br>liệu và ảnh; kiểm tra các trường<br>tùy chọn đã lưu.|
|TC-003-|Use-case|Đểtrống một trường bắt buộc|Lượt đầu báo Required và không|
|023||(ví dụFirst name), gửi form;<br>nhập giá trịhợp lệrồi gửi lại.|tạo user; sau khi sửa, tạo thành<br>công và dữliệu đúng trong hồsơ.|
|TC-003-|Use-case|Chọn _Generate password and_|Xác<br>minh<br>user<br>được<br>tạo<br>và|
|024||_notify user_, nhập các dữliệu<br>bắt buộc hợp lệvà lưu.|luồng tạo mật khẩu được chấp<br>nhận; không khẳng định email đã<br>gửi/nhận nếu thiếu hộp thư test.|
|TC-003-|Use-case|Nhập<br>Username/Email<br>mới|Thoát<br>biểu<br>mẫu;<br>xác<br>minh|
|025||cùng dữliệu hợp lệ, sau đó<br>nhấn Cancel.|Username không xuất hiện trong<br>danh sách và user không được<br>tạo.|



### **4.2.6 Ví dụtest case chi tiết: TC-003-001** 

**Mục tiêu:** kiểm tra Moodle từchối tạo người dùng khi Username bỏtrống và hiển thị Required. Các trường còn lại sửdụng dữliệu hợp lệtheo chính sách Moodle; Username đểtrống; Email dùng địa chỉchưa tồn tại được tạo theo hậu tốtest case. Không ghi 

Page 20/33 

Project #2 Black-Box Testing – Moodle LMS 



#### **VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

mật khẩu vào báo cáo. 

Test case PASS khi không phát sinh tài khoản và thông báo Required xuất hiện cạnh 

Bảng 8: Các bước và kết <u>quảmong</u> đợi của TC-003-001 

|**Bước**|**Thao tác**|**Kết quảmong đợi**|
|---|---|---|
|1|Đăng nhập Admin và mởAdd a new<br>user|Biểu mẫu tạo người dùng hiển thị.|
|2|Nhập dữliệu hợp lệcho các trường<br>khác, đểtrống Username|Dữliệu nhập đúng theo test case.|
|3|Nhấn Create user|Không tạo tài khoản; Username hiển|
|||thịRequired; biểu mẫu vẫn mở.|



Username; nếu không, ghi FAIL cùng bằng chứng thực tế. 

## **4.3 Triển khai Katalon Recorder** 

Các kịch bản Feature 3 nên được tổchức trong suite riêng, ví dụ `TS_003_Add_New_ User.krecorder` . Trước khi chạy, xác nhận Admin có quyền tạo user, chuẩn bịtài khoản trùng `au_exist` và các fixture; Username/Email mới cần duy nhất theo mã test case. Không lưu mật khẩu dạng rõ trong báo cáo hoặc tệp xuất. **Chuẩn bịvà dọn dẹp:** giữcác trường ngoài phạm vi ởgiá trịhợp lệ; chuẩn bị `testcase12.txt` và ảnh `testcase22.png` . Cleanup chỉxóa user do bộtest tạo, giữlại `au_exist` . **Xác minh:** dùng `verifyText` cho thông báo, `verifyValue` cho dữliệu trường và `verifyElementPresent` cho user/hồsơ. Ghi PASS/FAIL/NOT RUN và bằng chứng sau khi thực thi; không coi email đã gửi/nhận nếu chưa có hộp thư kiểm thử. 

Page 21/33 

Project #2 Black-Box Testing – Moodle LMS 



**VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

# **5 Feature 004: Create Quiz – Nguyễn Minh Phúc** 

## **5.1 Đặc tảtính năng** 

### **5.1.1 Mô tảngắn gọn và hướng dẫn sửdụng** 

**Mô tả:** Create Quiz cho phép người dùng có quyền quản lý/chỉnh sửa khóa học (Teacher hoặc Admin) tạo hoạt động Quiz trong một chủđềcủa khóa học Moodle. Biểu mẫu cấu hình gồm tên và mô tả, thời gian mở/đóng, giới hạn thời gian làm bài, điểm đạt, sốlần làm bài và phương thức tính điểm. Các quyền và giới hạn cụthểcần được đối chiếu với Moodle được cấp. 

**Hướng dẫn sửdụng:** 

1. Đăng nhập bằng tài khoản Teacher hoặc Admin và mởmột khóa học có sẵn. 

2. Bật _Edit mode_ nếu chưa bật; tại chủđềcần thêm hoạt động, chọn _Add an activity or resource_ rồi chọn _Quiz_ . 

3. Trong biểu mẫu _Adding a new Quiz_ , nhập _Name_ (bắt buộc, tối đa 255 ký tựtheo đặc tảđược cung cấp) và có thểnhập _Description_ . 

4. Cấu hình _Timing_ : bật/tắt các trường _Open the quiz_ , _Close the quiz_ , _Time limit_ ; khi bật cảhai mốc mở/đóng, thời gian đóng phải sau thời gian mở. Khi bật giới hạn thời gian, nhập giá trịdương. 

5. Cấu hình _Grade_ : nhập _Grade to pass_ trong miền 0.00–10.00 theo thang điểm mặc định đang dùng; chọn _Attempts allowed_ (Unlimited hoặc 1–10) và _Grading method_ (Highest grade, Average grade, First attempt hoặc Last attempt). Phương thức tính điểm chỉcó ý nghĩa/kích hoạt khi sốlần làm bài khác 1. 

6. Chọn _Save and return to course_ hoặc _Save and display_ ; kiểm tra Quiz được lưu và hiển thịđúng. 

### **5.1.2 Use Case (Ca sửdụng)** 

**Tên Use Case:** UC-004 – Create a New Quiz 

**Tác nhân:** Teacher / Manager / Administrator 

**Điều kiện tiên quyết:** Người dùng đã đăng nhập và có quyền chỉnh sửa khóa học; khóa học đã tồn tại; Edit mode đang bật. 

**Luồng sựkiện chính:** 

1. Tác nhân chọn thêm hoạt động mới trong khóa học và chọn _Quiz_ . 

Page 22/33 

Project #2 Black-Box Testing – Moodle LMS 



#### **VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

2. Hệthống hiển thịbiểu mẫu _Adding a new Quiz_ . 

3. Tác nhân nhập Name hợp lệvà cấu hình các trường Timing, Grade cần thiết. 

4. Tác nhân chọn _Save and return to course_ . 

5. Hệthống xác thực dữliệu, lưu Quiz và hiển thịhoạt động mới trong khóa học. 

### **Luồng thay thế/ngoại lệ:** 

- **E1 – Thiếu Name:** đểtrống Name; hệthống không lưu và hiển thịlỗi _Required_ tại trường Name. 

- **E2 – Sai logic thời gian:** khi cảhai mốc được bật, đặt Close nhỏhơn hoặc bằng Open; hệthống báo _The quiz close date must be after the open date_ . 

- **E3 – Sai Time limit:** nhập 0, sốâm hoặc dữliệu không phải số; hệthống từchối và hiển thịlỗi xác thực tương ứng. 

- **E4 – Sai Grade to pass:** nhập sốâm, giá trịlớn hơn 10.00 hoặc dữliệu không phải số; hệthống từchối và hiển thịlỗi xác thực tương ứng. 

- **E5 – Hủy:** chọn Cancel; hệthống rời biểu mẫu mà không tạo Quiz mới. 

**Hậu điều kiện:** Quiz hợp lệđược lưu và hiển thịtrong khóa học; nếu dữliệu không hợp lệ, hệthống giữbiểu mẫu và hiển thịlỗi đểngười dùng sửa. 

### **5.1.3 Activity Diagram (Sơ đồhoạt động)** 

1. Bắt đầu; mởbiểu mẫu _Adding a new Quiz_ . 

2. Nhập Name, Timing và Grade; chọn Save. 

3. Kiểm tra Name có độdài 1–255 ký tự. Nếu không, báo lỗi Required/độdài tối đa và quay lại biểu mẫu. 

4. Kiểm tra Timing: nếu bật cảOpen và Close thì Close phải lớn hơn Open; nếu Time limit được bật thì giá trịphải dương. Nếu không hợp lệ, báo lỗi và quay lại biểu mẫu. 

5. Kiểm tra Grade to pass thuộc miền 0–10 theo cấu hình; nếu không hợp lệ, báo lỗi và quay lại biểu mẫu. 

6. Nếu tất cảđiều kiện hợp lệ, lưu Quiz, hiển thịtheo lựa chọn Save and return to course/Save and display, rồi kết thúc. 

Page 23/33 

Project #2 Black-Box Testing – Moodle LMS 



**VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

- **5.2 Kỹthuật Phân tích giá trịbiên (Boundary Value Analysis – BVA)** 

- **5.2.1 Biến đầu vào và các giá trịbiên của Feature 4** 

- **Quiz Name:** độdài hợp lệtừ1 đến 255 ký tự; kiểm tra 0, 1, 2, 254, 255 và 256 ký tự. 

- **Time limit:** khi bật Enable, giá trịphút phải lớn hơn hoặc bằng 1; kiểm tra 0 và 1. 

- **Grade to pass:** theo thang điểm mặc định 0.00–10.00; kiểm tra -0.01, 0.00, 10.00 và 10.01. Các giới hạn phải được đối chiếu với điểm tối đa thực tếcủa Quiz. 

- **Open/Close:** khi cảhai được bật, điều kiện nghiệp vụlà Close > Open; kiểm tra Close < Open, Close = Open và Close > Open. 

### **5.2.2 Các test case BVA** 

Các mã TC-004-001 đến TC-004-009 trong Bảng 10 là nhóm BVA. TC-004-009 dùng cùng mã cho hai lượt dữliệu biên điểm (-0.01 và 10.01); ghi nhận riêng kết quảcủa từng lượt khi thực thi. 

## **5.3 Kỹthuật Phân hoạch tương đương (Equivalence Class Partitioning – ECP)** 

- **5.3.1 Các lớp tương đương của Feature 4** 

- **EC1 – Quiz Name hợp lệ:** chuỗi 1–255 ký tự; ví dụ _Midterm Quiz 1_ . 

- **EC2 – Quiz Name hợp lệcó dấu/ký tựđặc biệt:** ví dụ _Kiểm tra giữa kỳ#1 @2026_ . 

- **EC3 – Quiz Name không hợp lệ:** chuỗi chỉgồm khoảng trắng. 

- **EC4 – Time limit hợp lệ:** sốnguyên dương; ví dụ45 phút. 

- **EC5 – Time limit không hợp lệ:** sốâm hoặc dữliệu không phải số; ví dụ-15 hoặc abc. 

- **EC6 – Grade to pass hợp lệ:** sốtrong miền 0–10; ví dụ5.5. 

- **EC7 – Grade to pass không hợp lệ:** dữliệu không phải số; ví dụabc. 

Page 24/33 

Project #2 Black-Box Testing – Moodle LMS 



#### **VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

### **5.3.2 Các test case ECP** 

Các mã TC-004-010 đến TC-004-014 trong Bảng 10 đại diện cho các lớp trên. Một số lớp hợp lệcũng xuất hiện trong các test case khác, ví dụName hợp lệởBVA/use-case và Grade hợp lệtrong luồng tạo Quiz thành công. 

## **5.4 Kỹthuật Bảng quyết định (Decision Table Technique – Phần Bonus)** 

### **5.4.1 Bảng quyết định cho Timing và Attempts** 

Bảng 9 xét trạng thái bật Open/Close, thứtựthời gian và sốlần làm bài. Dấu – biểu thịđiều kiện không ảnh hưởng đến quy tắc. 

Bảng 9: Bảng <u>quyết</u> định cho Feature 4 

|**Điều kiện/Hành động**|**Rule 1**|**Rule 2**|**Rule 3**|**Rule 4**|
|---|---|---|---|---|
|Open the quiz được bật|Không|Có|Có|Có|
|Close the quiz được bật|Không|Có|Có|Có|
|Close > Open|–|Có|Không|Có|
|Attempts allowed > 1 hoặc Unlimited|Không (1)|Có (3)|Có (3)|Không (1)|
|Cho phép lưu thành công|Có|Có|Không|Có|
|Báo lỗi ngày đóng phải sau ngày mở|Không|Không|Có|Không|
|Grading method khảdụng|Không|Có|Có|Không|



### **5.4.2 Các test case Decision Table** 

Các mã TC-004-015 đến TC-004-018 trong Bảng 10 lần lượt kiểm thửRule 1–4. Rule 3 xác nhận hệthống từchối ngày đóng nhỏhơn hoặc bằng ngày mở. 

## **5.5 Kỹthuật Kiểm thửUse-case (Use-Case Testing Technique)** 

### **5.5.1 Các kịch bản kiểm thử(Test Scenarios / Paths)** 

1. **Scenario 1 – Luồng chuẩn:** tạo Quiz hợp lệ, chọn Save and return to course. 

2. **Scenario 2 – Save and display:** tạo Quiz hợp lệvà mởtrang chi tiết Quiz để tiếp tục thêm câu hỏi. 

3. **Scenario 3 – Cancel:** nhập thông tin rồi hủy; không tạo Quiz. 

Page 25/33 

Project #2 Black-Box Testing – Moodle LMS 



#### **VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

4. **Scenario 4 – Nhiều lỗi xác thực:** đểtrống Name và nhập Grade to pass vượt giới hạn; hệthống hiển thịlỗi tương ứng ởcác trường. 

### **5.5.2 Tổng hợp danh sách 22 test case Feature 4** 

Bảng 10 tóm tắt mục tiêu, dữliệu đầu vào và kết quảmong đợi của 22 mã test case. TC-004-022 được đặt theo kịch bản nhiều lỗi (Name rỗng và Grade to pass = 10.01); giá trịnày thống nhất với mô tảScenario 4. Kết quảmong đợi cần được xác nhận trên Moodle trước khi điền kết quảthực tế. 

Bảng 10: Danh sách 22 test case cho Feature 4 – Create Quiz 

|**Mã TC**|**Kỹthuật**|**Mục**<br>**tiêu**<br>**kiểm**<br>**thử**|**Dữliệu đầu vào chính**|**Kết quảmong đợi**|
|---|---|---|---|---|
|TC-004-|BVA|Name rỗng (0 ký|Name đểtrống|Không lưu; hiển thịlỗi|
|001||tự)||_Required_ tại Name.|
|TC-004-|BVA|Biên dưới hợp lệ|Name: Q|Tạo thành công; Quiz|
|002||Name (1 ký tự)||tên Q xuất hiện trong<br>khóa học.|
|TC-004-|BVA|Cận dưới Name (2|Name: Q1|Tạo thành công; Quiz|
|003||ký tự)||tên Q1 xuất hiện trong<br>khóa học.|
|TC-004-|BVA|Cận<br>trên<br>Name|Name gồm 254 ký tựA|Tạo thành công; lưu đủ|
|004||(254 ký tự)||254 ký tự.|
|TC-004-|BVA|Biên<br>trên<br>Name|Name gồm 255 ký tựB|Tạo thành công; lưu đủ|
|005||(255 ký tự)||255 ký tự.|
|TC-004-|BVA|Vượt<br>biên<br>Name|Name gồm 256 ký tựC|Không lưu hoặc báo lỗi|
|006||(256 ký tự)||vượt giới hạn 255 ký tự.|
|TC-004-|BVA|Time limit bằng 0|Name: Quiz BVA 07; bật|Báo lỗi giá trịTime|
|007|||Time limit; nhập 0 phút|limit phải lớn hơn 0.|
|TC-004-|BVA|Time limit bằng 1|Name: Quiz BVA 08; bật|Tạo<br>thành<br>công<br>với|
|008||phút|Time limit; nhập 1 phút|Time limit là 1 phút.|
|TC-004-|BVA|Grade to pass ngoài|Name:<br>Quiz<br>BVA<br>09;|Mỗi lượt bịtừchối; hiển|
|009||biên dưới/trên|chạy lần lượt Grade to<br>pass = -0.01 và 10.01|thịlỗi điểm đạt ngoài<br>miền 0.00–10.00.|
|TC-004-|ECP|Name<br>hợp<br>lệ<br>có|Name: Kiểm tra Chương|Tạo thành công; hiển thị|
|010||tiếng<br>Việt/ký<br>tự<br>đặc biệt|1 - Đợt #1 @2026|đúng dấu và ký tự.|
|TC-004-|ECP|Name<br>chỉ<br>chứa|Name gồm 5 dấu cách|Từchối lưu; hiển thịlỗi|
|011||khoảng trắng||Required.|
|TC-004-|ECP|Time limit hợp lệ|Name: Quiz ECP 12; bật|Tạo thành công; hiển thị|
|012|||Time limit; nhập 45 phút|Time limit: 45 mins.|
|TC-004-|ECP|Time limit không|Name:<br>Quiz<br>ECP<br>13;|Từchối; báo định dạng|
|013||hợp lệ|bật Time limit; nhập -15<br>hoặc abc|sốkhông hợp lệ.|



Còn tiếp ởtrang sau 

Page 26/33 

Project #2 Black-Box Testing – Moodle LMS 



#### **VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

|||Bảng|10 – tiếp theo||
|---|---|---|---|---|
|**Mã TC**|**Kỹthuật**|**Mục**<br>**tiêu**<br>**kiểm**<br>**thử**|**Dữliệu đầu vào chính**|**Kết quảmong đợi**|
|TC-004-|ECP|Grade<br>to<br>pass|Name:<br>Quiz<br>ECP<br>14;|Từchối; báo cần nhập|
|014||không phải số|Grade to pass: abc|giá trịsố.|
|TC-004-|Decision|Rule<br>1:<br>không|Open/Close<br>tắt;|Quiz lưu thành công;|
|015|Table|bật<br>Open/Close,<br>Attempts = 1|Attempts = 1|Grading method bịvô<br>hiệu hóa.|
|TC-004-|Decision|Rule 2: thời gian|Open: 15/11/2026 08:00;|Grading<br>method<br>khả|
|016|Table|hợp lệ, Attempts =<br>3|Close: 15/11/2026 10:00;<br>Attempts = 3; Average<br>grade|dụng; Quiz lưu đủcấu<br>hình.|
|TC-004-|Decision|Rule 3: Close không|Open: 15/11/2026 10:00;|Không lưu; báo Close|
|017|Table|sau Open|Close: 15/11/2026 08:00|date must be after the<br>open date.|
|TC-004-|Decision|Rule 4: thời gian|Open: 15/11/2026 08:00;|Quiz lưu thành công;|
|018|Table|hợp lệ, Attempts =<br>1|Close: 15/11/2026 10:00;<br>Attempts = 1|Grading method bịvô<br>hiệu hóa.|
|TC-004-|Use-case|Tạo<br>thành<br>công,|Name:<br>Final<br>Exam;|Trởvềkhóa học; hoạt|
|019||Save and return to<br>course|Grade<br>to<br>pass:<br>5.00;<br>chọn Save and return to<br>course|động Final Exam xuất<br>hiện.|
|TC-004-<br>020|Use-case|Tạo<br>thành<br>công,<br>Save and display|Name:<br>Practice<br>Quiz;<br>chọn Save and display|Mở<br>trang<br>chi<br>tiết<br>Practice Quiz, có thao<br>tác Add question.|
|TC-004-<br>021|Use-case|Hủy tạo Quiz bằng<br>Cancel|Name: Temp Quiz; chọn<br>Cancel|Trởvềkhóa học; Temp<br>Quiz không được tạo.|
|TC-004-<br>022|Use-case|Nhiều lỗi xác thực<br>cùng lúc|Name đểtrống; Grade to<br>pass = 10.01|Không lưu; hiển thịlỗi<br>Required cho Name và<br>lỗi<br>miền<br>giá<br>trị<br>cho<br>Grade to pass.|



## **5.6 Triển khai Katalon Recorder** 

Các script Feature 4 được tổchức trong Test Suite `TS_004_Create_Quiz.krecorder` . TC-004-000_Setup đăng nhập Teacher, mởkhóa học mẫu và bật Edit mode. TC-004999_Cleanup chỉdọn Quiz nhận diện được bằng tiền tốtest, không xóa hoạt động có sẵn. **Xác minh:** dùng `verifyTextPresent` cho thông báo và `verifyElementPresent` cho trạng thái Quiz; ghi kết quảvà ảnh/log minh chứng sau khi chạy. 

Page 27/33 

Project #2 Black-Box Testing – Moodle LMS 



**VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

# **6 Feature 005: Add a New Course – HồTây Nguyên** 

## **6.1 Đặc tảtính năng** 

### **6.1.1 Mô tảngắn gọn và hướng dẫn sửdụng** 

**Mô tả:** Chức năng Add a new course cho phép người dùng có quyền quản trịhệ thống (Administrator) tạo khóa học mới trong Moodle LMS. Biểu mẫu gồm Course full name, Course short name, Course ID number, Course category, Course visibility, ngày bắt đầu/kết thúc, Course summary, định dạng khóa học và hình ảnh. Các quyền và giới hạn cần được đối chiếu với cấu hình Moodle thực tế. 

**Hướng dẫn sửdụng:** 

1. Đăng nhập tài khoản Admin vào Moodle (ví dụmôi trường cục bộtại `http://127. 0.0.1:9501/` ). 

2. Truy cập _Site administration → Courses → Add a new course_ , hoặc mở `course/edit.php?category=0` . 

3. Nhập Course full name (bắt buộc; giới hạn thiết kế1333 ký tự) và Course short name (bắt buộc, phải duy nhất). 

4. Chọn Course category và cấu hình các trường tùy chọn như ID number, visibility, thời gian, summary, định dạng và hình ảnh. 

5. Chọn _Save and display_ hoặc _Save and return_ ; xác minh khóa học trong trang chi tiết hoặc danh sách quản lý. 

### **6.1.2 Use Case (Ca sửdụng)** 

**Tên Use Case:** UC-005 – Add a New Course. 

**Tác nhân:** Administrator/Manager. 

**Điều kiện tiên quyết:** Người dùng đã đăng nhập và có quyền tạo khóa học; category cần dùng đã tồn tại; Course short name và ID number dựkiến chưa được sửdụng. **Luồng sựkiện chính:** 

1. Tác nhân mởchức năng Add a new course. 

2. Hệthống hiển thịbiểu mẫu cấu hình khóa học. 

3. Tác nhân nhập Course full name, Course short name và các trường tùy chọn cần thiết. 

Page 28/33 

Project #2 Black-Box Testing – Moodle LMS 



#### **VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

4. Tác nhân chọn _Save and display_ . 

5. Hệthống xác thực và lưu khóa học, sau đó mởtrang chi tiết khóa học mới. 

6. Tác nhân xác minh khóa học trong Manage courses and categories. 

### **Luồng thay thế/ngoại lệ:** 

1. E1 – Thiếu Course full name: chặn lưu và hiển thịlỗi Missing full name/Required. 

2. E2 – Thiếu Course short name: chặn lưu và hiển thịlỗi Missing short name. 

3. E3 – Short name trùng: từchối lưu và báo lỗi trùng lặp. 

4. E4 – ID number trùng: báo lỗi xác thực tính duy nhất. 

5. E5 – Không chọn category: dựkiến từchối lưu; cần xác nhận theo cấu hình Moodle. 

6. E6 – Chọn _Cancel_ : rời biểu mẫu và không tạo khóa học. 

**Hậu điều kiện:** Khóa học hợp lệđược lưu và xuất hiện trong danh sách quản lý; nếu dữliệu sai, biểu mẫu hiển thịlỗi đểsửa; nếu hủy, không phát sinh khóa học mới. 

### **6.1.3 Activity Diagram (Sơ đồhoạt động)** 

1. Bắt đầu; mởbiểu mẫu Add a new course. 

2. Nhập Course full name, Course short name, category, ID number, summary, thiết lập thời gian và visibility. 

3. Kiểm tra Course full name không rỗng và không vượt giới hạn thiết kế1333 ký tự; kiểm tra Course short name không rỗng và duy nhất. 

4. Nếu có ID number, kiểm tra tính duy nhất; nếu category bắt buộc nhưng chưa chọn, hiển thịlỗi và quay lại biểu mẫu. 

5. Nếu có trường không hợp lệ, hiển thịlỗi tại trường tương ứng và cho phép sửa. 

6. Nếu hợp lệ, lưu khóa học và chuyển đến trang chi tiết/danh sách quản lý; nếu Cancel, thoát mà không lưu. 

Page 29/33 

Project #2 Black-Box Testing – Moodle LMS 

**VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 



## **6.2 Thiết kếkiểm thử** 

### **6.2.1 Phân tích giá trịbiên (Boundary Value Analysis – BVA)** 

Course full name có giới hạn thiết kếtối đa 1333 ký tựtheo biểu mẫu; kiểm tra độdài 0, 1, 2, 1332, 1333 và 1334 ký tự. Hành vi ở1334 ký tựcó thểlà từchối hoặc cắt bớt; cần xác minh trên giao diện và dữliệu lưu. Course short name là trường bắt buộc và duy nhất; kiểm thửgiá trịrỗng, hợp lệvà trùng lặp, không giảđịnh giới hạn độdài nếu chưa xác nhận cấu hình. Course ID number và Summary được kiểm tra giới hạn theo cấu hình Moodle. Start date/End date kiểm tra các quan hệEnd date nhỏhơn, bằng và lớn hơn Start date. 

### **6.2.2 Phân hoạch tương đương (Equivalence Class Partitioning – ECP)** 

Các lớp đầu vào gồm: Course full name hợp lệ(1–1333 ký tự, gồm tiếng Việt/ký tựđặc biệt), rỗng hoặc vượt giới hạn; Course short name duy nhất, rỗng hoặc trùng; Course category được chọn hoặc không chọn; Course visibility là Show hoặc Hide; Course summary rỗng, văn bản thuần hoặc HTML rich text. Các giới hạn và hành vi phụ thuộc cấu hình được ghi nhận theo môi trường kiểm thử. 

### **6.2.3 Danh sách test case tiêu biểu** 

Bảng 11 tập hợp 15 test case được cung cấp. Các mã không liên tiếp được giữnguyên theo tài liệu đầu vào; các trường chưa nêu giữgiá trịhợp lệ/mặc định. Short name và ID cần được chuẩn bịsao cho các ca kiểm thửtrùng lặp có sẵn dữliệu đối chứng. 

Bảng 11: Test case tiêu biểu cho Feature 5 – Add a New Course 

|**Mã TC**|**Kỹ**<br>**thuật**|**Mục**<br>**tiêu**<br>**kiểm**<br>**thử**|**Dữliệu đầu vào chính**|**Kết quảmong đợi**|
|---|---|---|---|---|
|TC-005-<br>001|ECP<br><br>Use-case|/<br>Tạo course hợp lệ|Full name: Software Testing<br>101; Short name: ST101;<br>ID: ID101; Summary có nội<br>dung|Tạo<br>thành<br>công;<br>chuyển đến trang chi<br>tiết course.|
|TC-005-<br>002|ECP<br><br>BVA|/<br>Full name đểtrống|Full name rỗng; Short name<br>hợp lệ: FN-EMPTY|Không<br>tạo<br>course;<br>báo lỗi yêu cầu nhập<br>tên.|
|TC-005-|BVA|Full name 1 ký tự|Full name = `A`|Tạo<br>course<br>thành|
|003||||công với tên 1 ký tự.|
|TC-005-|BVA|Full name 1332 ký|Chuỗi 1332 ký tự`a`|Tạo thành công; lưu|
|005||tự||đủđộdài.|



Còn tiếp ởtrang sau 

Page 30/33 

Project #2 Black-Box Testing – Moodle LMS 



#### **VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

|||Bảng 1|1 – tiếp theo||
|---|---|---|---|---|
|**Mã TC**|**Kỹ**<br>**thuật**|**Mục**<br>**tiêu**<br>**kiểm**<br>**thử**|**Dữliệu đầu vào chính**|**Kết quảmong đợi**|
|TC-005-|BVA|Full name 1333 ký|Chuỗi 1333 ký tự`a`|Tạo thành công tại|
|006||tự||biên<br>thiết<br>kế;<br>xác<br>minh độdài đã lưu.|
|TC-005-|BVA|Full name 1334 ký|Chuỗi 1334 ký tự`a`|Không lưu quá 1333|
|007||tự||ký tự; ghi nhận bịtừ<br>chối hay cắt bớt.|
|TC-005-|ECP|Full name chỉgồm|Full name gồm 3 dấu cách|Theo<br>dữ<br>liệu<br>đầu|
|008||khoảng trắng||vào, hệthống chấp<br>nhận; ghi nhận và<br>xác<br>minh<br>hành<br>vi<br>thực tế.|
|TC-005-|ECP|Full name có dấu/ký|`Kiểm thửphần mềm @#&`|Lưu và hiển thịđúng|
|009||tựđặc biệt|`2026`|dấu, ký tựđặc biệt.|
|TC-005-<br>010|ECP|Short name đểtrống|Short name rỗng|Không<br>tạo<br>course;<br>báo lỗi thiếu short<br>name.|
|TC-005-|ECP|Short name trùng|Dùng short name `ST101` đã|Từchối lưu và báo|
|016|||tồn tại|lỗi trùng short name.|
|TC-005-<br>020|ECP|Course visibility =<br>Hide|Chọn trạng thái Hide|Tạo course ởtrạng<br>thái ẩn đối với học<br>viên.|
|TC-005-|ECP|ID number trùng|Dùng ID number `ID101` đã|Từchối lưu và báo|
|037|||tồn tại|lỗi trùng ID number.|
|TC-005-|ECP|Summary rich text|Summary nhiều dòng, có từ|Lưu<br>và<br>hiển<br>thị|
|038|||khóa in đậm|đúng<br>định<br>dạng<br>HTML/rich text.|
|TC-005-<br>043|Use-case|Hủy tạo course|Nhập dữliệu hợp lệrồi chọn<br>_Cancel_|Thoát<br>biểu<br>mẫu;<br>không<br>tạo<br>course<br>mới.|
|TC-005-|Use-case|Tìm<br>course<br>trong|Tạo course hợp lệrồi tìm|Course<br>xuất<br>hiện|
|044||trang quản lý|trong Manage courses and<br>categories|đúng<br>trong<br>danh<br>mục quản lý tương<br>ứng.|



## **6.3 Triển khai Katalon Recorder** 

Trước khi chạy, xác nhận tài khoản Admin có quyền tạo course, chuẩn bịcategory đích và dữliệu course đối chứng. Đểchạy TC-005-016 và TC-005-037, bảo đảm short name `ST101` và ID `ID101` đã tồn tại; tránh đểTC-005-001 hoặc cleanup xóa dữliệu đối chứng trước các ca trùng lặp. Dùng short name/ID riêng cho ca tạo mới. Cleanup chỉxóa course do suite tạo, không xóa category hay course fixture. Xác minh lỗi trên biểu mẫu, trạng thái visibility, dữliệu summary và course trong Manage courses and categories; ghi PASS/FAIL/NOT RUN cùng ảnh/log sau khi thực thi. 

Page 31/33 

Project #2 Black-Box Testing – Moodle LMS 



**VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

- **7 Khai báo sử dụng công cụ AI (AI Usage Declaration)** 

- **7.1 Công cụAI đã sửdụng (hoặc xác nhận không sửdụng AI)** 

Trong quá trình thực hiện đồán kiểm thửMoodle LMS, nhóm đã sửdụng ChatGPT (OpenAI) đểhỗtrợphân tích các nguyên nhân có thểkhiến bước nhập liệu (lệnh `type` ) trong Katalon Recorder hoạt động sai khi phát lại script dù nhập liệu thủcông bình thường; tham khảo hướng xửlý như chờtrang tải ( `pause` ), dùng `sendKeys` hoặc xửlý sựkiện của form; soạn tiểu mục vềkinh nghiệm xửlý lỗi tựđộng hóa kiểm thửform; hướng dẫn tổchức data preparation và cleanup cho các test case BVA/ECP đểhạn chế dữliệu trùng lặp hoặc còn sót; và hỗtrợxây dựng cấu trúc, trình bày báo cáo bằng LaTeX. Các phản hồi của AI chỉlà gợi ý tham khảo, không phải bằng chứng rằng lỗi đã được khắc phục hoặc test case đã chạy thành công. Nhóm có trách nhiệm kiểm tra tính phù hợp với môi trường Moodle/Katalon Recorder thực tế, tựthiết kếvà thực thi kiểm thử, xác nhận kết quảmong đợi/thực tế, đồng thời bổsung bằng chứng. Không đưa thông tin đăng nhập hoặc dữliệu nhạy cảm vào prompt. 

## **7.2 Các câu lệnh (prompts) đã cung cấp cho AI (nếu có)** 

Các prompt đã cung cấp trong quá trình chuẩn bịbáo cáo: 

- **Prompt 1 – Khắc phục lỗi nhập liệu khi chạy Katalon Recorder:** “Tôi đang dùng Katalon Recorder đểtest Moodle LMS cho đồán. Gặp tình trạng khi tôi Record tay thì nhập liệu bình thường, nhưng bấm Play đểchạy tựđộng thì test case lại bị lỗi ởbước type (nhập giá trịvào ô input). Hãy giải thích các nguyên nhân phổbiến (như độtrễload trang, xung đột JavaScript/AJAX, hay bịdính dữliệu cũ) và cho tôi cách khắc phục chi tiết đểviết vào báo cáo đồán.” 

- **Prompt 2 – Viết mục kinh nghiệm xửlý lỗi:** “Hãy viết giúp tôi một tiểu mục ngắn gọn bằng tiếng Việt với tiêu đề’Kinh nghiệm xửlý lỗi tựđộng hóa kiểm thử form trên Moodle bằng Katalon Recorder’ đểđưa vào báo cáo đồán kiểm thử. Nội dung cần tập trung vào vấn đề: Tại sao các giá trịnhập vào (BVA/ECP test cases) đôi khi bịlỗi khi Play script tựđộng, các nguyên nhân kỹthuật và giải pháp xửlý thực tế(như dùng pause, sendKeys, hoặc xửlý sựkiện form).” 

- **Prompt 3 – Data preparation và cleanup:** “Theo yêu cầu đồán kiểm thử Moodle, tôi cần viết các script chuẩn bịdữliệu (data preparation) và dọn dẹp (cleanup) trước và sau khi chạy test case tựđộng trên Katalon Recorder. Hãy hướng 

Page 32/33 

Project #2 Black-Box Testing – Moodle LMS 



#### **VIETNAM NATIONAL UNIVERSITY HO CHI MINH CITY HO CHI MINH CITY UNIVERSITY OF TECHNOLOGY** 

dẫn tôi cách tổchức các bước này sao cho khi chạy các test case BVA/ECP không bịtrùng lặp dữliệu hoặc bịlỗi do dữliệu cũ còn sót lại.” 

- **Prompt 4 – Bổsung Feature 1 và Feature 2:** “Thêm nội dung đặc tả, kỹthuật kiểm thửvà danh sách test case cho hai feature Add Category và Create Group in Course vào báo cáo; giữtên người phụtrách theo bảng workload và thống nhất bố cục mục lục giữa các feature.” 

Page 33/33 

Project #2 Black-Box Testing – Moodle LMS 

