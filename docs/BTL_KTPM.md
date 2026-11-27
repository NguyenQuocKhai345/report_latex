## ĐẠI HỌC QUỐC GIA THÀNH PHỐHỒCHÍ MINH **TRƯỜNG ĐẠI HỌC BÁCH KHOA KHOA KHOA HỌC & KỸTHUẬT MÁY TÍNH** 



<!-- Start of picture text -->
o<br><!-- End of picture text -->

**BÁO CÁO BÀI TẬP LỚN** 

**Kiến trúc phần mềm (CO3017)** 

**Hệthống chấm công và kiểm soát ra vào bằng QR Code** 

## **HỌC KỲ261** 

|**Giảng viên hướng dẫn:**|ThS. Lê Đình Thuận||
|---|---|---|
|**Sinh viên thực hiện:**|Nguyễn Quốc Khải|2311557|
||Trương Hoàng Thông|2313336|
||Đặng Ngọc Khiêu|2311572|
||Huỳnh A Dũng|2310545|
||Đặng Gia Bảo|2310210|



**TP. HồChí Minh, Ngày 19 tháng 10 năm 2026** 

# **Mục lục** 

|**Danh m**|**ục từviết tắt** . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . .<br>**i**|
|---|---|---|
|**Danh m**|**ục hình** . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . .<br>**ii**|
|**Danh m**|**ục bảng**<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . .<br>**iii**|
|**1**<br>**Giới**|**thiệu hệthống**. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . .<br>**1**|
|1.1|Đặt vấn đề. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . .<br>1|
|1.2|Bối cảnh hệthống . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . .<br>1|
|1.3|Mục tiêu dựán<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . .<br>1|
|1.4|Phạm vi hệthống . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . .<br>2|
|1.5|Các bên liên quan và tác nhân<br>. . . . . . . . . . . . . . . . . . . . . .|. . . .<br>3|
||1.5.1<br>Tác nhân tích hợp bên ngoài . . . . . . . . . . . . . . . . . . .|. . . .<br>4|
|1.6|Các chức năng chính của hệthống . . . . . . . . . . . . . . . . . . . .|. . . .<br>4|
|1.7|User story và tiêu chí chấp nhận<br>. . . . . . . . . . . . . . . . . . . . .|. . . .<br>5|
||1.7.1<br>Ràng buộc chất lượng áp dụng cho các user story . . . . . . . .|. . . .<br>8|
|**2**<br>**Yêu**|**cầu hệthống và ràng buộc thiết kế**<br>. . . . . . . . . . . . . . . . . . .|. . . .<br>**8**|
|2.1|Cơ sởvà cách phân loại yêu cầu . . . . . . . . . . . . . . . . . . . . .|. . . .<br>9|
|2.2|Yêu cầu chức năng<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . .<br>9|
|2.3|Yêu cầu phi chức năng và phép đo . . . . . . . . . . . . . . . . . . . .|. . . .<br>11|
|2.4|Ràng buộc và cơ sởthiết kế. . . . . . . . . . . . . . . . . . . . . . . .|. . . .<br>12|
|2.5|Phân tích khối lượng và khảnăng xửlý<br>. . . . . . . . . . . . . . . . .|. . . .<br>13|
|2.6|Ma trận quyền ởmức nghiệp vụ<br>. . . . . . . . . . . . . . . . . . . . .|. . . .<br>13|
|**3**<br>**Arch**|**itecture Characteristics**<br>. . . . . . . . . . . . . . . . . . . . . . . . .|. . . .<br>**14**|
|3.1|Quy trình xác định<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . .<br>15|
|3.2|Danh sách đặc tính ứng viên . . . . . . . . . . . . . . . . . . . . . . .|. . . .<br>15|
|3.3|Đặc tính được chọn và định nghĩa vận hành . . . . . . . . . . . . . . .|. . . .<br>16|
|3.4|Ma trận truy vết yêu cầu đến đặc tính. . . . . . . . . . . . . . . . . . .|. . . .<br>16|
|3.5|Xung đột và đánh đổi giữa các đặc tính. . . . . . . . . . . . . . . . . .|. . . .<br>17|
|**4**<br>**Stru**|**cture: lựa chọn và xây dựng kiến trúc** . . . . . . . . . . . . . . . . . .|. . . .<br>**18**|
|4.1|So sánh và lựa chọn phong cách kiến trúc . . . . . . . . . . . . . . . .|. . . .<br>19|
||4.1.1<br>Phương án và tiêu chí đánh giá . . . . . . . . . . . . . . . . . .|. . . .<br>19|
||4.1.2<br>Ma trận đánh giá có trọng số. . . . . . . . . . . . . . . . . . .|. . . .<br>19|
||4.1.3<br>Lựa chọn và phân tích độnhạy . . . . . . . . . . . . . . . . . .|. . . .<br>20|
|4.2|Kiến trúc logical: các bước xây dựng . . . . . . . . . . . . . . . . . . .|. . . .<br>20|
||4.2.1<br>Bước 1: xác định ranh giới và luồng nghiệp vụ<br>. . . . . . . . .|. . . .<br>21|
||4.2.2<br>Bước 2: nhận diện và gán trách nhiệm cho thành phần<br>. . . . .|. . . .<br>21|
||4.2.3<br>Bước 3: nhóm thành dịch vụvà xác định sởhữu dữliệu<br>. . . .|. . . .<br>23|



Mục lục 



||4.2.4|Bước 4: kiểm tra SRP và phân lớp . . . . . . . . . . . . . . . . . . .|.<br>24|
|---|---|---|---|
||4.2.5|Bước 5: tinh chỉnh theo các đặc tính chủđạo<br>. . . . . . . . . . . . .|.<br>24|
||4.2.6|Bước 6: xác định hợp đồng giao tiếp . . . . . . . . . . . . . . . . . .|.<br>25|
||4.2.7|Bước 7: mô hình dữliệu và định danh . . . . . . . . . . . . . . . . .|.<br>25|
||4.2.8|Bước 8: kiểm tra bằng kịch bản và tinh chỉnh . . . . . . . . . . . . .|.<br>26|
|4.3|Kiến tr|úc physical: các bước xây dựng . . . . . . . . . . . . . . . . . . . . .|.<br>26|
||4.3.1|Bước 1: xác định đơn vịtriển khai . . . . . . . . . . . . . . . . . . .|.<br>27|
||4.3.2|Bước 2: bốtrí theo vùng mạng và miền lỗi<br>. . . . . . . . . . . . . .|.<br>28|
||4.3.3|Bước 3: thiết kếlưu bền, HA và chống split-brain . . . . . . . . . . .|.<br>29|
||4.3.4|Bước 4: định cỡvà dựtoán lưu trữ. . . . . . . . . . . . . . . . . . .|.<br>29|
||4.3.5|Bước 5: lập ngân sách độtrễ. . . . . . . . . . . . . . . . . . . . . .|.<br>30|
||4.3.6|Bước 6: bảo vệdữliệu và vận hành an toàn . . . . . . . . . . . . . .|.<br>31|
||4.3.7|Bước 7: định nghĩa các chếđộlỗi . . . . . . . . . . . . . . . . . . .|.<br>31|
||4.3.8|Bước 8: lịch xuất, giám sát và kiểm chứng. . . . . . . . . . . . . . .|.<br>32|
|**5**<br>**Tổn**|**g hợp c**|**ác góc nhìn kiến trúc 4+1** . . . . . . . . . . . . . . . . . . . . . . . .|.<br>**32**|
|5.1|Logica|l view: thành phần và mô hình nghiệp vụ. . . . . . . . . . . . . . . .|.<br>33|
||5.1.1|Thành phần đường quét và các cổng phụthuộc . . . . . . . . . . . .|.<br>33|
||5.1.2|Mô hình miền và dữliệu quan hệ<br>. . . . . . . . . . . . . . . . . . .|.<br>35|
|5.2|Proces|s view: đồng thời, giao tiếp và phục hồi . . . . . . . . . . . . . . . . .|.<br>35|
||5.2.1|Trình tựquét QR trong trường hợp thành công<br>. . . . . . . . . . . .|.<br>35|
||5.2.2|Projection vòng đời và trạng thái chưa xác định . . . . . . . . . . . .|.<br>37|
||5.2.3|Đồng bộvà xửlý đồng thời<br>. . . . . . . . . . . . . . . . . . . . . .|.<br>37|
||5.2.4|Tiến trình xuất và đối soát tháng . . . . . . . . . . . . . . . . . . . .|.<br>38|
|5.3|Develo|pment view: tổchức mã và quy tắc phụthuộc<br>. . . . . . . . . . . . .|.<br>38|
|5.4|Physic|al view: ánh xạphần mềm lên hạtầng . . . . . . . . . . . . . . . . . .|.<br>40|
|5.5|Scenar|ios (+1): kiểm chứng xuyên góc nhìn . . . . . . . . . . . . . . . . . .|.<br>40|
|**6**<br>**Arch**|**itectur**|**e Decisions** . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|.<br>**41**|
|6.1|Quy tắ|c kiến trúc (Architecture rules)<br>. . . . . . . . . . . . . . . . . . . . .|.<br>42|
|6.2|Hồsơ|quyết định kiến trúc (ADR) . . . . . . . . . . . . . . . . . . . . . . .|.<br>43|
||6.2.1|ADR-01 – Kiến trúc dịch vụtheo miền kết hợp edge và sựkiện<br>. . .|.<br>43|
||6.2.2|ADR-02 – Ports và adapters bên trong mỗi miền<br>. . . . . . . . . . .|.<br>43|
||6.2.3|ADR-03 – Đưa xửlý cổng và kho sựkiện vềnhà máy<br>. . . . . . . .|.<br>44|
||6.2.4|ADR-04 – QR do máy chủký và có thời hạn<br>. . . . . . . . . . . . .|.<br>44|
||6.2.5|ADR-05 – Commit chứng cứtrước tác động thiết bị<br>. . . . . . . . .|.<br>44|
||6.2.6|ADR-06 – Transactional outbox và inbox khửtrùng. . . . . . . . . .|.<br>45|
||6.2.7|ADR-07 – Định danh ổn định cho lượt quét và lô . . . . . . . . . . .|.<br>45|
||6.2.8|ADR-08 – PostgreSQL theo schema, HA và RPO theo miền lỗi<br>. . .|.<br>45|
||6.2.9|ADR-09 – Xuất HR theo snapshot và lô có đối soát . . . . . . . . . .|.<br>46|



Mục lục 



||6.2.10|ADR-10 – Cô lập API cổng và xửlý timeout có nghĩa<br>. . . . .|. . . .<br>46|
|---|---|---|---|
||6.2.11|ADR-11 – RBAC kết hợp scope tại dịch vụ. . . . . . . . . . .|. . . .<br>46|
||6.2.12|ADR-12 – Audit chỉthêm với checkpoint độc lập . . . . . . . .|. . . .<br>47|
||6.2.13|ADR-13 – Bảo vệdữliệu theo mục đích và tối thiểu hóa . . . .|. . . .<br>47|
||6.2.14|ADR-14 – Quan sát và fitness function từthiết kế. . . . . . . .|. . . .<br>47|
||6.2.15|ADR-15 – Chếđộsuy giảm và giới hạn quyền offline. . . . . .|. . . .<br>48|
|**7**<br>**Desi**|**gn Prin**|**ciples** . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . .<br>**48**|
|7.1|Áp dụn|g SOLID . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . .<br>49|
||7.1.1|SRP và ranh giới thay đổi<br>. . . . . . . . . . . . . . . . . . . .|. . . .<br>49|
||7.1.2|OCP và mởrộng chính sách có kiểm soát . . . . . . . . . . . .|. . . .<br>50|
||7.1.3|LSP và hợp đồng adapter . . . . . . . . . . . . . . . . . . . . .|. . . .<br>50|
||7.1.4|ISP và quyền bảo mật là hai cơ chếkhác nhau . . . . . . . . . .|. . . .<br>50|
||7.1.5|DIP và minh họa điều phối . . . . . . . . . . . . . . . . . . . .|. . . .<br>51|
|7.2|Các ng|uyên tắc thiết kếbổsung<br>. . . . . . . . . . . . . . . . . . . . .|. . . .<br>51|
|7.3|Mẫu th|iết kếphục vụcác nguyên tắc . . . . . . . . . . . . . . . . . . .|. . . .<br>52|
|**8**<br>**Đán**|**h giá th**|**iết kếvà kếhoạch kiểm chứng** . . . . . . . . . . . . . . . . . .|. . . .<br>**52**|
|8.1|Mức đ|áp ứng Task 1<br>. . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . .<br>53|
|8.2|Kếhoạ|ch kiểm chứng có tiêu chí rõ ràng . . . . . . . . . . . . . . . . .|. . . .<br>53|
|8.3|Rủi ro|và biện pháp kiểm soát<br>. . . . . . . . . . . . . . . . . . . . . .|. . . .<br>54|
|8.4|Kết luậ|n . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . .<br>55|



# **– Danh mục từviết tắt** 

|**Từviết tắt / Ký hiệu**|**Diễn giải**|
|---|---|
|CN|Chức năng – Tiền tốmã nhóm chức năng, ví dụCN-01|
|FR|Functional Requirement – Yêu cầu chức năng|
|NFR|Non-functional Requirement – Yêu cầu phi chức năng|
|US|User Story – Câu chuyện người dùng; tiền tốmã user story, ví dụUS-01|
|TMC-AACS|TMC Attendance and Access Control System – Hệthống chấm công và kiểm<br>soát ra vào TMC|
|ICS|Identity and Credential Service – Dịch vụđịnh danh và QR|
|AAS|Access and Attendance Service – Dịch vụra vào và chấm công|
|GSS|Gate Station Service – Dịch vụquản lý trạm cổng|
|RIS|Reporting and Integration Service – Dịch vụbáo cáo và tích hợp|
|ADS|Administration and Audit Service – Dịch vụquản trịvà kiểm toán|
|ADR|Architecture Decision Record – Hồsơ quyết định kiến trúc|
|AR|Architecture Rule – Quy tắc kiến trúc|
|RBAC|Role-Based Access Control – Phân quyền theo vai trò|
|PII|Personally Identifiable Information – Thông tin định danh cá nhân|
|RPO|Recovery Point Objective – Mục tiêu điểm phục hồi dữliệu|
|RTO|Recovery Time Objective – Mục tiêu thời gian phục hồi|
|TTL|Time To Live – Thời hạn hiệu lực|
|mTLS|Mutual TLS – Xác thực kết nối TLS hai phía|
|WAL|Write-Ahead Log – Nhật ký ghi trước|
|LAN / WAN|Local / Wide Area Network – Mạng cục bộ/ diện rộng|



# **Danh sách hình vẽ** 

|1|Ngữcảnh TMC-AACS và các ranh giới tích hợp . . . . . . . . . . . .|. . . . . . . . .<br>21|
|---|---|---|
|2|Logical containers và giao tiếp giữa edge và central<br>. . . . . . . . . .|. . . . . . . . .<br>24|
|3|Topology physical và các miền dựphòng . . . . . . . . . . . . . . . .|. . . . . . . . .<br>29|
|4|Thành phần lõi tại edge theo ports và adapters<br>. . . . . . . . . . . . .|. . . . . . . . .<br>34|
|5|Mô hình khái niệm dữliệu và quan hệchính<br>. . . . . . . . . . . . . .|. . . . . . . . .<br>35|
|6|Trình tựquét và thứtựcommit trước tác động thiết bị<br>. . . . . . . . .|. . . . . . . . .<br>36|
|7|Projection trạng thái lượt quét từlịch sửchỉthêm . . . . . . . . . . . .|. . . . . . . . .<br>37|
|8|Tiến trình chốt snapshot, xuất và đối soát với HR . . . . . . . . . . . .|. . . . . . . . .<br>38|
|9|Phụthuộc mã nguồn hướng vào port và nghiệp vụ. . . . . . . . . . .|. . . . . . . . .<br>39|
|10|Hợp đồng thay thếadapter và hướng phụthuộc SOLID. . . . . . . . .|. . . . . . . . .<br>50|



ii 

# **Danh sách bảng** 

|1|Mục tiêu dựán và thước đo . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>2<br>|
|---|---|
|2|Phạm vi trong và ngoài hệthống . . . . . . . . . . . . . . . . . . . . . . . . .<br>2|
|3|Các bên liên quan, vai trò và phạm vi tương tác . . . . . . . . . . . . . . . . .<br>3|
|4|Tác nhân phần mềm bên ngoài và tương tác . . . . . . . . . . . . . . . . . . .<br>4|
|5|User story và tiêu chí chấp nhận theo vai trò . . . . . . . . . . . . . . . . . . .<br>5<br>|
|6|Yêu cầu chức năng và liên kết user story . . . . . . . . . . . . . . . . . . . . .<br>9|
|7|Yêu cầu phi chức năng và cách kiểm chứng . . . . . . . . . . . . . . . . . . .<br>11|
|8|Cơ sởthiết kếvà điều kiện vận hành . . . . . . . . . . . . . . . . . . . . . . .<br>12|
|9|Quyền theo vai trò và phạm vi dữliệu . . . . . . . . . . . . . . . . . . . . . .<br>14|
|10|Đặc tính ứng viên và mức ưu tiên. . . . . . . . . . . . . . . . . . . . . . . . .<br>15|
|11|Kịch bản chất lượng ưu tiên. . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>16|
|12|Truy vết đặc tính, quyết định và phép kiểm. . . . . . . . . . . . . . . . . . . .<br>17|
|13|Đánh đổi và giới hạn chấp nhận<br>. . . . . . . . . . . . . . . . . . . . . . . . .<br>17|
|14|Các phong cách được cân nhắc . . . . . . . . . . . . . . . . . . . . . . . . . .<br>19|
|15|So sánh định hướng các phương án kiến trúc . . . . . . . . . . . . . . . . . . .<br>20|
|16|Đầu vào và đầu ra của quy trình xây dựng logical . . . . . . . . . . . . . . . .<br>20|
|17|Danh mục thành phần và truy vết yêu cầu . . . . . . . . . . . . . . . . . . . .<br>22|
|18|Ranh giới dịch vụvà vùng dữliệu sởhữu<br>. . . . . . . . . . . . . . . . . . . .<br>23|
|19|Hợp đồng giao tiếp và xửlý lỗi . . . . . . . . . . . . . . . . . . . . . . . . . .<br>25|
|20|Thực thểdữliệu chính và bất biến . . . . . . . . . . . . . . . . . . . . . . . .<br>26|
|21|Đầu vào và đầu ra của quy trình xây dựng physical<br>. . . . . . . . . . . . . . .<br>27|
|22|Đơn vịtriển khai và vịtrí triển khai<br>. . . . . . . . . . . . . . . . . . . . . . .<br>27|
|23|Cấu hình khởi điểm đểthửnghiệm . . . . . . . . . . . . . . . . . . . . . . . .<br>30|
|24|Ngân sách độtrễdựkiến trên đường quét<br>. . . . . . . . . . . . . . . . . . . .<br>30|
|25|Hành vi vận hành khi có lỗi . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>31|
|26|Góc nhìn, đối tượng đọc và bằng chứng<br>. . . . . . . . . . . . . . . . . . . . .<br>33|
|27|Cấu trúc mã nguồn và phép kiểm kiến trúc . . . . . . . . . . . . . . . . . . . .<br>39|
|28|Ánh xạlogical sang physical và đường dữliệu . . . . . . . . . . . . . . . . . .<br>40|
|29|Kịch bản liên kết các góc nhìn và bằng chứng cần thu . . . . . . . . . . . . . .<br>40|
|30|Quy tắc triển khai và phép kiểm<br>. . . . . . . . . . . . . . . . . . . . . . . . .<br>42|
|31|Ánh xạSOLID vào TMC-AACS . . . . . . . . . . . . . . . . . . . . . . . . .<br>49|
|32|Nguyên tắc bổsung và cách áp dụng . . . . . . . . . . . . . . . . . . . . . . .<br>51|
|33|Mẫu thiết kếvà rủi ro nếu dùng sai . . . . . . . . . . . . . . . . . . . . . . . .<br>52|
|34|Đối chiếu nội dung bàn giao với yêu cầu Task 1 . . . . . . . . . . . . . . . . .<br>53|
|35|Kếhoạch kiểm chứng kiến trúc . . . . . . . . . . . . . . . . . . . . . . . . . .<br>54|
|36|Rủi ro kiến trúc và biện pháp kiểm soát<br>. . . . . . . . . . . . . . . . . . . . .<br>55|



iii 

1 Giới thiệu hệ thống 



# **Chương 1 – Giới thiệu hệthống** 

## **1.1 Đặt vấn đề** 

Kiểm soát ra vào và chấm công là hai nghiệp vụgắn liền với mỗi lượt nhân viên đi qua cổng nhà máy. Doanh nghiệp vừa cần bảo đảm người qua cổng có quyền truy cập, vừa cần dữ liệu chính xác đểxác định thời gian hiện diện và phục vụđối soát chấm công. Nếu các thông tin này được xửlý rời rạc, việc kiểm tra sai lệch và truy vết các trường hợp bất thường sẽkhó thực hiện nhất quán. 

Trong môi trường sản xuất, lượt ra vào thường tập trung vào giờgiao ca. Việc xửlý chậm tại cổng có thểgây ùn tắc, trong khi bỏsót hoặc ghi sai giao dịch sẽảnh hưởng đến dữliệu chấm công. Mỗi lượt quét vì vậy cần có kết quảrõ ràng, được ghi nhận đầy đủvà có thểkiểm tra lại khi phát sinh tranh chấp hoặc sựcố. 

Đềtài **Hệthống chấm công và kiểm soát ra vào bằng QR Code** được xây dựng nhằm kết nối việc nhận diện, kiểm soát truy cập và ghi nhận chấm công trong một quy trình thống nhất. Dữliệu tạo ra từquá trình này giúp các bộphận có căn cứchung đểgiám sát, tổng hợp và đối soát. 

## **1.2 Bối cảnh hệthống** 

**Công ty Cổphần Sản xuất TMC** hiện có hai nhà máy: **Bình Dương với khoảng 800 nhân viên** và **Long An với khoảng 600 nhân viên** , tổng cộng khoảng 1.400 người. Mỗi nhân viên có điện thoại thông minh cá nhân và có thểtruy cập ứng dụng di động, cổng thông tin web hoặc email của công ty đểhiển thịmã QR. 

Tại trạm cổng, kiosk đọc mã QR đểhệthống kiểm tra danh tính và quyền ra vào. Khi yêu cầu hợp lệ, phần mềm gửi lệnh đến bộđiều khiển cổng quay; mỗi lượt vào hoặc ra được ghi nhận thành giao dịch chấm công. Dữliệu từhai nhà máy được tập hợp đểphục vụquản lý nhân sựvà theo dõi tình hình vận hành. 

TMC đã có hai hệthống cần kết nối: **HR/Payroll** , tiếp nhận dữliệu chấm công qua API đểđối soát và xửlý tiền lương; và **hệthống điều khiển cổng quay** , cung cấp API đóng/mở cổng cho từng lượt ra vào. Đây là các hệthống hiện hữu mà phần mềm mới phải phối hợp trong môi trường vận hành của công ty. 

## **1.3 Mục tiêu dựán** 

Mục tiêu của dựán là cung cấp khảnăng kiểm soát ra vào và dữliệu chấm công đáng tin cậy cho TMC. Các kết quảcần đạt được và thước đo đánh giá được xác định như sau. 

1 

1 Giới thiệu hệ thống 



**Bảng 1:** _Mục tiêu dựán và thước đo_ 

|**Mục tiêu**|**Thước đo**|
|---|---|
|Kiểm soát đúng quyền và truy vết<br>được các lượt ra vào|Chỉphát lệnh mởcổng khi mã QR và quyền truy cập hợp lệ;<br>tất cảlượt quét, kểcảbịtừchối, có kết quảvà dấu vết xửlý.|
|Chấm công tựđộng, chính xác từsự<br>kiện ra vào|Không phát sinh bản ghi trùng hoặc sai do xửlý của hệ<br>thống; các trường hợp thiếu lượt vào/ra được nhận diện để<br>kiểm tra.|
|Đáp ứng nhanh tại cổng trong giờ<br>cao điểm|Kiosk phản hồi_≤_2giây ởmức tải khoảng 800 giao dịch<br>trong 30 phút tại mỗi nhà máy.|
|Không mất dữliệu chấm công|Không mất bản ghi trong điều kiện vận hành bình thường;<br>kiểm tra được sựkhớp đúng giữa giao dịch đã ghi nhận và<br>dữliệu tổng hợp.|
|Dữliệu tháng sẵn sàng đúng hạn cho<br>HR/Payroll|Dữliệu được xuất qua API và sẵn sàng đối soát trước 12:00<br>trưa ngày đầu tiên của mỗi tháng; kết quảchuyển dữliệu có<br>thểkiểm tra.|
|Bảo vệdữliệu cá nhân và kiểm soát<br>trách nhiệm|Các thao tác truy cập được kiểm tra theo vai trò và phạm vi<br>dữliệu; thao tác nhạy cảm có nhật ký kiểm toán; kiểm thử<br>quyền truy cập và việc bảo vệdữliệu theo quy định áp dụng.|
|Dễbảo trì, mởrộng và tích hợp|Thêm trạm cổng qua cấu hình; thay đổi đầu kết nối<br>HR/Payroll hoặc cổng quay được khoanh vùng trong thành<br>phần tích hợp tương ứng; thiết kếcó trách nhiệm rõ ràng và<br>được rà soát theo SOLID.|



## **1.4 Phạm vi hệthống** 

Bảng sau xác định các hạng mục thuộc trách nhiệm của hệthống và các nội dung không được triển khai trong phạm vi đềtài. 

**Bảng 2:** _Phạm vi trong và ngoài hệthống_ 

|**Trong phạm vi**|**Ngoài phạm vi**|
|---|---|
|• Quản lý người dùng và mã QR: cấp, làm mới,|• Quản lý khách đến thăm (visitor management).|
|thu hồi mã.||
|• Quản lý trạm cổng (gate station): cổng, kiosk|• Tính lương (payroll calculation); hệthống chỉ|
|và ánh xạtới cổng quay (turnstile).|xuất dữliệu chấm công.|
|• Ghi nhận sựkiện ra/vào thành giao dịch chấm|• Thiết kếlại hoặc thay thếhệthống HR/Payroll|
|công.|và hệthống điều khiển cổng quay hiện có.|



2 

1 Giới thiệu hệ thống 



|**Trong phạm vi**|**Ngoài phạm vi**|
|---|---|
|• Báo cáo, đối soát và xuất dữliệu sang<br>HR/Payroll.|• Nhận diện bằng sinh trắc học như khuôn mặt<br>hoặc vân tay.|
|• Nhật ký kiểm toán (audit log), phân quyền theo<br>vai trò (RBAC) và quản trịhệthống.|• Quy tắc tính công, làm thêm giờvà phụcấp<br>phục vụnghiệp vụtiền lương; các nội dung này<br>thuộc HR/Payroll.|
|• Tích hợp qua API với HR/Payroll và hệthống<br>điều khiển cổng quay (Turnstile Control<br>System).||
|• Giao diện tương tác: ứng dụng di động, cổng<br>thông tin web và kiosk.||



Ranh giới trách nhiệm của phần mềm bao gồm xửlý lượt quét, ghi nhận chấm công và trao đổi dữliệu qua API. Việc vận hành cơ khí cổng quay và tính lương do các hệthống hiện có đảm nhiệm. 

## **1.5 Các bên liên quan và tác nhân** 

Mục này xác định ai sửdụng, chịu ảnh hưởng hoặc tham gia vận hành hệthống. Sáu nhóm người dùng trực tiếp cũng là các bên liên quan (stakeholders); các đầu mối phối hợp không mặc nhiên có tài khoản hoặc quyền thao tác trong phần mềm. 

**Bảng 3:** _Các bên liên quan, vai trò và phạm vi tương tác_ 

|**Bên liên quan**|**Vai trò / quan hệ**|**Mối quan tâm và phạm vi tương tác**|
|---|---|---|
|Nhân viên|Người dùng trực tiếp;<br>chủthểdữliệu|Sửdụng QR đểra/vào; cần được ghi nhận<br>chấm công đúng, phản hồi nhanh và bảo vệ<br>thông tin cá nhân. Chỉtra cứu dữliệu thuộc<br>quyền của mình.|
|Giám sát sản xuất|Người dùng trực tiếp;<br>quản lý đội/ca|Theo dõi hiện diện và phối hợp xác minh bất<br>thường của nhân viên thuộc phạm vi phụtrách<br>đểbốtrí hoạt động sản xuất.|
|Nhân viên nhân sự|Người dùng trực tiếp;<br>phụtrách chấm công|Quản lý thông tin nhận diện theo quyền; kiểm<br>tra, tổng hợp và đối soát chấm công; theo dõi<br>việc chuyển dữliệu sang HR/Payroll.|
|Nhân viên bảo vệ|Người dùng trực tiếp;<br>phụtrách cổng|Giám sát lượt ra vào, trường hợp bịtừchối và<br>sựcốtại trạm; hỗtrợxửlý theo thẩm quyền, có<br>lưu dấu vết.|



3 

1 Giới thiệu hệ thống 



|**Bên liên quan**|**Vai trò / quan hệ**|**Mối quan tâm và phạm vi tương tác**|
|---|---|---|
|Quản trịviên hệthống|Người dùng trực tiếp;<br>quản trịkỹthuật|Quản lý tài khoản, quyền và cấu hình trạm;<br>theo dõi vận hành, nhật ký, sao lưu và khôi<br>phục theo quyền được giao.|
|Ban điều hành TMC|Người dùng báo cáo;<br>bên quản lý|Quan tâm đến an ninh và hiệu quảvận hành;<br>xem báo cáo tổng hợp của các nhà máy theo<br>phạm vi được cấp.|
|IT và các đầu mối tích<br>hợp|Các bên phối hợp vận<br>hành|Phối hợp với đơn vịphụtrách HR/Payroll và<br>cổng quay đểthống nhất API, kiểm thửkết nối<br>và xửlý sựcố. Có thểkiêm nhiệm với vai trò<br>quản trịviên.|
|Đầu mối bảo vệdữliệu|Trách nhiệm phối hợp<br>được đềxuất|Rà soát việc thu thập, lưu giữvà khai thác dữ<br>liệu cá nhân. Cần phân công trách nhiệm cụthể;<br>không giảđịnh TMC có một phòng ban riêng.|



### **1.5.1 Tác nhân tích hợp bên ngoài** 

Hai tác nhân phần mềm dưới đây tương tác với hệthống qua API. Chúng được phân biệt với các cá nhân hoặc đơn vịphụtrách vận hành, tích hợp trong bảng trên. 

**Bảng 4:** _Tác nhân phần mềm bên ngoài và tương tác_ 

|**Tác nhân bên ngoài**|**Tương tác với hệthống**|
|---|---|
|HR/Payroll|Nhận dữliệu chấm công và phản hồi kết quảtiếp nhận để<br>phục vụđối soát. Nghiệp vụtính lương thuộc hệthống này.|
|Hệthống điều khiển cổng quay|Nhận lệnh đóng/mởcổng cho từng lượt ra vào và trảkết quả|
||xửlý; đảm nhiệm phần điều khiển cổng quay hiện hữu.|



Kiosk/máy quét QR là điểm tiếp nhận thao tác và phản hồi tại cổng, không phải một nhóm người dùng. 

- **1.6 Các chức năng chính của hệthống** 

Các chức năng được chia thành năm nhóm làm cơ sởliên kết nhu cầu của stakeholders với user story và yêu cầu chi tiết: 

1. **CN-01 – Quản lý người dùng và mã QR:** quản lý thông tin người dùng, trạng thái và quyền ra vào; cấp, làm mới và thu hồi mã QR đểnhân viên sửdụng tại cổng. 

2. **CN-02 – Quản lý trạm cổng:** quản lý nhà máy, kiosk, hướng vào/ra và ánh xạtới cổng quay; theo dõi trạng thái và hỗtrợxửlý sựcốtại trạm. 

4 

1 Giới thiệu hệ thống 



3. **CN-03 – Ghi nhận sựkiện chấm công:** tiếp nhận lượt quét, kiểm tra mã QR và quyền truy cập, phối hợp mởcổng và lưu giao dịch vào/ra. Các luồng xửlý ngoại lệcần giữdấu vết để đối soát. 

4. **CN-04 – Báo cáo và kiểm toán:** cung cấp dữliệu chấm công, báo cáo hiện diện, nhật ký kiểm toán; tổng hợp và truyền dữliệu sang HR/Payroll đúng hạn. 

5. **CN-05 – Quản trịhệthống:** quản lý tài khoản, vai trò, phạm vi quyền và các cấu hình vận hành; hỗtrợtheo dõi trạng thái, sao lưu và khôi phục dữliệu. 

## **1.7 User story và tiêu chí chấp nhận** 

User story mô tảmột nhu cầu cụthểtheo cấu trúc _“Là một [vai trò], tôi muốn [khảnăng] để[giá trịđạt được]”_ . Các story dưới đây được tổchức theo sáu nhóm người dùng và liên kết với các nhóm chức năng CN-01 đến CN-05. Tiêu chí chấp nhận nêu kết quảcó thểkiểm tra, làm cơ sởchi tiết hóa yêu cầu và xây dựng ca kiểm thử; chúng chưa mô tảgiải pháp kỹthuật hoặc khẳng định hệthống đã được triển khai. 

Các story được phân loại thành **cốt lõi** , cụthểhóa phạm vi đềbài, và **đềxuất bổsung** , cần được thống nhất trước khi đưa vào phạm vi triển khai. Nhãn cốt lõi không có nghĩa từng chi tiết trong tiêu chí chấp nhận đã được khách hàng phê duyệt. Khi có thay đổi yêu cầu, nội dung story và tiêu chí tương ứng cần được cập nhật cùng nhau. 

**Bảng 5:** _User story và tiêu chí chấp nhận theo vai trò_ 

|**Mã**|**User story**|**Tiêu chí chấp nhận**|
|---|---|---|
|**US-01**|Là một nhân viên, tôi muốn hiển thịmã QR cá<br>nhân qua kênh được công ty hỗtrợđểsửdụng<br>khi ra/vào nhà máy.<br>_Nhóm: CN-01. Cốt lõi._|Nhân viên được xác thực và chỉnhận<br>mã thuộc tài khoản của mình; mã đang<br>có hiệu lực có thểđược kiosk đọc; nhân<br>viên bịvô hiệu hóa không được cấp mã<br>mới.|
|**US-02**|Là một nhân viên, tôi muốn quét mã QR tại<br>cổng đểđược kiểm tra quyền ra/vào và ghi<br>nhận thời điểm chấm công.<br>_Nhóm: CN-03. Cốt lõi._|Mã hợp lệvà có quyền mới được phát<br>lệnh mởcổng; yêu cầu không hợp lệ<br>được từchối và ghi lý do. Giao dịch<br>được ghi nhận với nhân viên khi xác<br>định được, trạm cổng, thời điểm, hướng<br>và kết quả. Kiosk phản hồi không quá 2<br>giây ởtải đã nêu.|



5 

1 Giới thiệu hệ thống 



<!-- Start of picture text -->
xr BAI HOC QUOC GIA THANH PHO<br>G3 TRUONG BAI HOC BACH HO CHI KHOA MINH<br><!-- End of picture text -->

|**Mã**|**User story**|**Tiêu chí chấp nhận**|
|---|---|---|
|**US-03**|Là một nhân viên, tôi muốn xem lịch sửvào/ra<br>của bản thân đểkiểm tra dữliệu chấm công.<br>_Nhóm: CN-04. Đềxuất bổsung._|Lọc được theo khoảng thời gian; hiển<br>thịcác giao dịch đã ghi nhận; nhân viên<br>không xem được dữliệu của người khác<br>khi không có quyền.|
|**US-04**|Là một nhân viên, tôi muốn gửi giải trình cho<br>trường hợp thiếu hoặc sai lượt quét đểbộphận<br>có thẩm quyền kiểm tra.<br>_Nhóm: CN-03. Đềxuất bổsung._|Giải trình có ngày, nội dung và trạng<br>thái xửlý; nhân viên theo dõi được kết<br>quả; việc gửi giải trình không tựsửa<br>bản ghi chấm công gốc.|
|**US-05**|Là một giám sát sản xuất, tôi muốn xem tình<br>hình hiện diện của đội/ca phụtrách đểbốtrí<br>công việc.<br>_Nhóm: CN-04. Cốt lõi._|Lọc được theo ngày và nhóm phụtrách;<br>chỉxem nhân viên trong phạm vi được<br>cấp; thông tin dựa trên các sựkiện đã<br>ghi nhận và thểhiện thời điểm cập nhật.|
|**US-06**|Là một giám sát sản xuất, tôi muốn xác minh<br>giải trình của nhân viên trong đội đểnhân sự<br>có căn cứxửlý sai lệch.<br>_Nhóm: CN-03. Đềxuất bổsung._|Chỉxửlý giải trình thuộc phạm vi được<br>giao; lưu người xửlý, ý kiến và thời<br>điểm; nhân viên thấy được trạng thái;<br>không ghi đè lịch sửgiao dịch gốc.|
|**US-07**|Là một nhân viên nhân sự, tôi muốn quản lý<br>trạng thái nhân viên và quyền vào nhà máy để<br>việc cấp quyền phù hợp với hồsơ được duyệt.<br>_Nhóm: CN-01. Cốt lõi._|Chỉngười có quyền được cập nhật; thay<br>đổi hợp lệđược lưu và kiểm tra khi xử<br>lý lượt quét; ghi nhật ký ai thay đổi, nội<br>dung và thời điểm.|
|**US-08**|Là một nhân viên nhân sự, tôi muốn cấp, làm<br>mới hoặc thu hồi QR của nhân viên đểkiểm<br>soát việc sửdụng thông tin nhận diện.<br>_Nhóm: CN-01. Cốt lõi._|Mỗi thao tác kiểm tra quyền và trạng<br>thái nhân viên; mã hết hạn hoặc đã thu<br>hồi không được chấp nhận khi trạng thái<br>hiện hành đã được áp dụng tại trạm; lưu<br>người thao tác và thời điểm.|
|**US-09**|Là một nhân viên nhân sự, tôi muốn lập báo<br>cáo chấm công theo tháng đểkiểm tra và đối<br>soát dữliệu trước khi chuyển sang HR/Payroll.<br>_Nhóm: CN-04. Cốt lõi._|Chọn được kỳbáo cáo và nhà máy<br>trong phạm vi quyền; truy vết được từ<br>sốliệu tổng hợp vềcác sựkiện; các<br>trường hợp thiếu lượt vào/ra được thể<br>hiện đểkiểm tra.|
|**US-10**|Là một nhân viên nhân sự, tôi muốn điều<br>chỉnh dữliệu tổng hợp sau khi xác minh đểxử<br>lý sai lệch chấm công có kiểm soát.<br>_Nhóm: CN-03, CN-04. Đềxuất bổsung._|Ghi lý do và căn cứxác minh; chỉngười<br>có thẩm quyền phê duyệt mới được áp<br>dụng điều chỉnh; lưu giá trịtrước/sau,<br>người xửlý và thời điểm; không xóa sự<br>kiện gốc.|



6 

1 Giới thiệu hệ thống 



|**Mã**|**User story**|**Tiêu chí chấp nhận**|
|---|---|---|
|**US-11**|Là một nhân viên nhân sự, tôi muốn chuyển<br>dữliệu chấm công tháng sang HR/Payroll và<br>kiểm tra kết quảđểdữliệu sẵn sàng đối soát<br>đúng hạn.<br>_Nhóm: CN-04. Cốt lõi._|Dữliệu được chuyển qua API và sẵn<br>sàng đối soát trước 12:00 ngày đầu tiên<br>của tháng; hiển thịkỳ, kết quảgửi và<br>các lỗi; lần gửi thất bại không được báo<br>thành công; có thểđối chiếu dữliệu gửi<br>với dữliệu được xác nhận đã nhận.|
|**US-12**|Là một nhân viên bảo vệ, tôi muốn theo dõi<br>lượt ra vào và trạng thái trạm cổng đểphát<br>hiện, hỗtrợxửlý sựcố.<br>_Nhóm: CN-02, CN-03. Cốt lõi._|Xem được trạm và sựkiện thuộc nhà<br>máy được phân quyền; phân biệt lượt<br>được phép, bịtừchối và lỗi điều khiển<br>cổng; người không có quyền không truy<br>cập được màn hình giám sát.|
|**US-13**|Là một nhân viên bảo vệđược cấp quyền, tôi<br>muốn gửi yêu cầu mởcổng thủcông khi có sự<br>cốđểxửlý tình huống theo quy trình được<br>duyệt.<br>_Nhóm: CN-02, CN-03. Đềxuất bổsung._|Bắt buộc chọn trạm và nhập lý do; kiểm<br>tra quyền trước khi gửi lệnh; ghi người<br>yêu cầu, kết quảvà thời điểm; mởthủ<br>công không tựtạo giao dịch chấm công<br>hợp lệnếu chưa xác định được nhân<br>viên.|
|**US-14**|Là một quản trịviên hệthống, tôi muốn đăng<br>ký và cấu hình trạm cổng đểhệthống xác định<br>đúng nơi và hướng của từng lượt quét.<br>_Nhóm: CN-02. Cốt lõi._|Trạm có định danh, nhà máy, kiosk,<br>hướng và ánh xạcổng quay; kiểm tra dữ<br>liệu cấu hình; trạm bịvô hiệu hóa không<br>được xửlý như trạm đang hoạt động;<br>thay đổi được ghi nhật ký.|
|**US-15**|Là một quản trịviên hệthống, tôi muốn quản<br>lý vai trò và phạm vi quyền đểmỗi người chỉ<br>truy cập dữliệu, chức năng được giao.<br>_Nhóm: CN-05. Cốt lõi._|Mỗi thao tác bảo vệđược kiểm tra<br>quyền phía máy chủ; người dùng bịtừ<br>chối khi vượt vai trò hoặc phạm vi dữ<br>liệu; thay đổi quyền được ghi nhật ký và<br>kiểm thửvới tài khoản có/không có<br>quyền.|
|**US-16**|Là một quản trịviên được cấp quyền, tôi<br>muốn tra cứu nhật ký kiểm toán đểxác định ai<br>đã thao tác và hỗtrợđiều tra sựcố.<br>_Nhóm: CN-04, CN-05. Cốt lõi._|Lọc được theo thời gian, người thao tác<br>và loại hành động; các thao tác nhạy<br>cảm có đối tượng, thời điểm và kết quả;<br>người dùng thông thường không được<br>sửa hoặc xóa nhật ký qua chức năng<br>ứng dụng.|



7 

1 Giới thiệu hệ thống 



|**Mã**|**User story**|**Tiêu chí chấp nhận**|
|---|---|---|
|**US-17**|Là một quản trịviên hệthống, tôi muốn theo<br>dõi trạng thái dịch vụvà thực hiện sao lưu,<br>khôi phục theo quyền đểduy trì vận hành.<br>_Nhóm: CN-05. Cốt lõi._|Hiển thịtrạng thái và lỗi cần xửlý; ghi<br>kết quảsao lưu; kiểm tra khôi phục bằng<br>dữliệu kiểm thửvà đối chiếu sốbản<br>ghi; thao tác quản trịđược ghi nhật ký.|
|**US-18**|Là một thành viên ban điều hành, tôi muốn<br>xem báo cáo tổng hợp của hai nhà máy đểtheo<br>dõi tình hình hiện diện và chấm công.<br>_Nhóm: CN-04. Cốt lõi._|Lọc được theo nhà máy và kỳbáo cáo<br>trong phạm vi được cấp; dữliệu truy về<br>cùng nguồn với báo cáo nhân sự; tài<br>khoản chỉcó quyền xem không được<br>sửa chấm công hoặc điều khiển cổng.|



### **1.7.1 Ràng buộc chất lượng áp dụng cho các user story** 

Các tiêu chí trong từng story được kiểm tra cùng với các yêu cầu phi chức năng chung. Luồng quét QR phải đáp ứng thời gian phản hồi kiosk không quá 2 giây khi có khoảng 800 giao dịch trong 30 phút tại mỗi nhà máy. Trong điều kiện vận hành bình thường, các giao dịch chấm công đã được ghi nhận không được mất; cần kiểm tra đối chiếu dữliệu ởđầu vào, lưu trữvà báo cáo. Các story liên quan truy cập dữliệu phải được kiểm thửcảtrường hợp có quyền và không có quyền, đồng thời kiểm tra nhật ký và việc bảo vệdữliệu cá nhân. 

Đối với tích hợp, phải phân biệt kết quảxác thực QR, kết quảgửi lệnh điều khiển và kết quảtrảvềtừcổng quay; lỗi điều khiển không được hiển thịnhư mởcổng thành công. Việc chuyển dữliệu sang HR/Payroll phải có bằng chứng vềkết quảnhận dữliệu đểphục vụđối soát. Các chi tiết chưa được xác định trong hợp đồng API, như quy tắc gửi lại và thời điểm áp dụng thu hồi QR tại trạm, cần được thống nhất khi đặc tảtích hợp. 

8 

2 Yêu cầu hệ thống và ràng buộc thiết kế 



# **Chương 2 – Yêu cầu hệthống và ràng buộc thiết kế** 

## **2.1 Cơ sởvà cách phân loại yêu cầu** 

Chương 1 xác định mục tiêu, phạm vi, stakeholders và 18 user story. Chương này chuyển chúng thành yêu cầu có mã đểtruy vết tới thành phần, quyết định và phép kiểm chứng. Ký hiệu **Đềbài** chỉyêu cầu bắt buộc được cung cấp; **Bổsung** chỉcác yêu cầu chi tiết hóa từmục tiêu và nghiệp vụhệthống. 

## **2.2 Yêu cầu chức năng** 

**Bảng 6:** _Yêu cầu chức năng và liên kết user story_ 

|**Mã / nhóm**|**Nguồn**|**Yêu cầu**|**Story**|
|---|---|---|---|
|FR-U1 / CN-01|Đềbài|Quản lý định danh, trạng thái và quyền ra vào của nhân<br>viên theo nhà máy; kiểm tra quyền trước khi cho phép<br>truy cập.|US-07|
|FR-U2 / CN-01|Đềbài|Cấp, làm mới và thu hồi mã QR; hỗtrợhiển thịtrên<br>điện thoại qua ứng dụng, web hoặc kênh email được hỗ<br>trợ.|US-01, 08|
|FR-U3 / CN-01|Bổsung|Dùng QR ký sốcó thời hạn; thu hồi được phân phối tới<br>trạm; không đưa họtên, thông tin liên hệvào mã.|US-01, 08|
|FR-U4 / CN-01|Bổsung|Đồng bộhồsơ tối thiểu từHR nếu có API được cấp;<br>không giảđịnh HR đã hỗtrợchiều đồng bộnày.|US-07|
|FR-G1 / CN-02|Đềbài|Đăng ký và cấu hình nhà máy, trạm, kiosk, hướng<br>vào/ra và ánh xạcổng quay; kích hoạt hoặc vô hiệu hóa<br>trạm.|US-14|
|FR-G2 / CN-02|Bổsung|Nhận heartbeat, theo dõi trạng thái kết nối và cảnh báo<br>trạm lỗi; lưu người thay đổi cấu hình.|US-12, 14|
|FR-G3 / CN-02|Bổsung|Cho bảo vệđược cấp quyền yêu cầu mởcổng thủcông,<br>bắt buộc lý do và lưu kết quả; không tựsinh công hợp<br>lệkhi chưa xác minh nhân viên.|US-13|
|FR-A1 / CN-03|Đềbài|Tiếp nhận lượt quét QR, kiểm tra mã và quyền ra vào,<br>trảquyết định cho phép/từchối tại trạm.|US-02|
|FR-A2 / CN-03|Đềbài|Gọi API hệthống điều khiển cổng quay cho từng lượt<br>được phép; ghi nhận riêng kết quảquyết định và kết<br>quảđiều khiển.|US-02|



9 

2 Yêu cầu hệ thống và ràng buộc thiết kế 



|**Mã / nhóm**|**Nguồn**|**Yêu cầu**|**Story**|
|---|---|---|---|
|FR-A3 / CN-03|Đềbài|Ghi lượt vào/ra thành giao dịch chấm công có định<br>danh nhân viên khi xác định được, trạm, hướng, thời<br>điểm và kết quả.|US-02, 09|
|FR-A4 / CN-03|Bổsung|Ghi cảlượt bịtừchối và lỗi thiết bị; cùng một scan_id<br>gửi lại không tạo thêm sựkiện hoặc lệnh mởcổng mới.|US-02, 12|
|FR-A5 / CN-03|Bổsung|Giữsựkiện gốc; hỗtrợgiải trình, xác minh và điều<br>chỉnh có thẩm quyền bằng bản ghi bổsung.|US-04, 06,<br>10|
|FR-A6 / CN-03|Bổsung|Khi mất WAN, lưu sựkiện tại nhà máy và chuyển tiếp<br>khi kết nối lại; chỉxửlý bằng chính sách còn đủhiệu<br>lực.|US-02, 17|
|FR-A7 / CN-03|Bổsung|Áp dụng chống phát lại QR và phát hiện lượt vào/ra<br>bất thường theo chính sách được phê duyệt; không gộp<br>nhầm một lượt quét mới với việc truyền lại.|US-02, 09|
|FR-R1 / CN-04|Đềbài|Lập báo cáo chấm công tháng và thông tin giám sát<br>theo nhân viên, đội/ca, nhà máy và phạm vi quyền.|US-05, 09,<br>18|
|FR-R2 / CN-04|Bổsung|Cho nhân viên xem lịch sửcá nhân; đánh dấu thiếu<br>lượt vào/ra và các kết quảchưa xác định đểkiểm tra.|US-03, 09|
|FR-R3 / CN-04|Đềbài|Xuất dữliệu chấm công qua API sang HR/Payroll, sẵn<br>sàng đối soát trước 12:00 ngày đầu tháng.|US-11|
|FR-R4 / CN-04|Bổsung|Quản lý kỳ, phiên bản snapshot và mã lô xuất; theo dõi<br>xác nhận, lỗi, gửi lại an toàn và đối soát phần thiếu.|US-09, 11|
|FR-R5 / CN-04|Đềbài|Ghi và tra cứu audit log cho hành động nhạy cảm: chủ<br>thể, hành động, đối tượng, thời điểm, kết quảvà nguồn<br>yêu cầu.|US-16|
|FR-S1 / CN-05|Đềbài|Quản lý tài khoản, vai trò và quyền theo RBAC; giới<br>hạn phạm vi nhà máy/đội/cá nhân ởphía máy chủ.|US-15|
|FR-S2 / CN-05|Bổsung|Quản lý cấu hình có phiên bản, tham sốhiệu lực QR,<br>chính sách offline và thời hạn lưu dữliệu theo quyền.|US-14, 15|
|FR-S3 / CN-05|Bổsung|Theo dõi dịch vụ, backlog, sao lưu và phục hồi; lưu<br>bằng chứng thực hiện và cảnh báo cần xửlý.|US-17|
|FR-S4 / CN-05|Bổsung|Hạn chếdữliệu được thu thập, phân quyền liên kết<br>danh tính và áp dụng chính sách lưu giữ/xóa hoặc ẩn<br>danh đã phê duyệt.|US-03, 15,<br>16|



10 

2 Yêu cầu hệ thống và ràng buộc thiết kế 



## **2.3 Yêu cầu phi chức năng và phép đo** 

Độtrễđược đo từkhi kiosk gửi yêu cầu quét đến khi nhận kết quảcó trạng thái rõ ràng; với lượt thành công, phản hồi phải thểhiện kết quảAPI điều khiển đã xác nhận. Thời gian đi qua cơ khí không thuộc khoảng đo phần mềm và cần khảo sát riêng. Bộdữliệu tải phải bao gồm lượt thành công, bịtừchối và lỗi thiết bị, không chỉluồng thuận lợi. 

**Bảng 7:** _Yêu cầu phi chức năng và cách kiểm chứng_ 

|**Mã**|**Nguồn**|**Chỉtiêu / ràng buộc**|**Kiểm chứng**|
|---|---|---|---|
|NFR-P1|Đềbài|Kiosk phản hồi không quá 2<br>giây ởkhoảng 800 giao dịch/30<br>phút/nhà máy.|Đo end-to-end, báo cáo sốmẫu vi<br>phạm, max, p95, p99; yêu cầu không<br>được diễn giải lại thành chỉp99 đạt 2<br>giây.|
|NFR-R1|Đềbài|Không mất bản ghi chấm công<br>trong vận hành bình thường.|Đối chiếu tập scan_id đã xác nhận<br>với kho sựkiện, dữliệu trung tâm và<br>báo cáo; sốthiếu phải bằng 0.|
|NFR-S1|Đềbài|RBAC và audit logging toàn<br>diện.|Kiểm tra tất cảthao tác bảo vệtheo<br>vai trò và phạm vi; hành động nhạy<br>cảm được ghi audit kểcảtừchối<br>quyền.|
|NFR-PR1|Đềbài|Bảo vệdữliệu cá nhân theo quy<br>định áp dụng.|Rà soát trường dữliệu, quyền, log,<br>lưu giữvà quy trình xửlý; đầu mối<br>phụtrách xác nhận chính sách.<br>Không coi mã hóa là đủđểkết luận<br>tuân thủ.|
|NFR-I1|Ràng buộc<br>đềbài|Tích hợp HR/Payroll và điều<br>khiển cổng qua API hiện hữu;<br>hạn dữliệu trước 12:00 ngày 01.|Kiểm thửhợp đồng và đối soát lô<br>được nhận; phân biệt gửi HTTP<br>thành công với dữliệu đã được tiếp<br>nhận nghiệp vụ.|
|NFR-R2|Bổsung|Gửi lại sựkiện không tạo tác<br>động nghiệp vụtrùng.|Lặp cùng scan_id/event_id, thay thứ<br>tựgiao, khởi động lại consumer; số<br>sựkiện và lệnh không tăng sai.|
|NFR-A1|Bổsung|Đường xửlý tại nhà máy sẵn<br>sàng 99,9%/tháng; central<br>99,5%.|Đo trong khung vận hành đã thống<br>nhất; tách downtime do từchối hợp<br>lệvà do hệthống. Mục tiêu phục hồi<br>edge 5 phút, central 60 phút cần thử<br>nghiệm.|



11 

2 Yêu cầu hệ thống và ràng buộc thiết kế 



|**Mã**|**Nguồn**|**Chỉtiêu / ràng buộc**|**Kiểm chứng**|
|---|---|---|---|
|NFR-P2|Bổsung|Thửtải burst 10 yêu<br>cầu/giây/nhà máy, vẫn theo dõi<br>giới hạn 2 giây.|Không coi burst là tải đềbài; chạy<br>đồng thời tác vụbáo cáo, ghi phân<br>phối độtrễvà mức sửdụng tài<br>nguyên.|
|NFR-M1|Bổsung|Cấu hình thêm trạm không sửa<br>mã lõi; thay adapter không sửa<br>nghiệp vụ.|Kiểm tra phụthuộc, thửadapter giả<br>lập và thêm cấu hình trạm; sơ đồ<br>thành phần và contract test là bằng<br>chứng.|
|NFR-O1|Bổsung|Phát hiện và cảnh báo trạm mất<br>kết nối, backlog, lỗi xuất trong<br>2 phút.|Heartbeat mỗi 20 giây, cảnh báo sau<br>3 lần thiếu là cấu hình ban đầu; thử<br>ngắt mạng, kiểm tra cảnh báo và<br>người nhận.|
|NFR-D1|Bổsung|Khôi phục được dữliệu và tái<br>hiện được phép kiểm kiến trúc.|Thửrestore trong môi trường riêng,<br>kiểm tra hash/tập ID; lưu báo cáo<br>kiểm thửquyền, tải, lỗi và phụthuộc.|
|NFR-S2|Bổsung|Mã hóa truyền/lưu, quản lý<br>khóa và audit có khảnăng phát<br>hiện can thiệp.|TLS/mTLS, quyền kho khóa, đối<br>chiếu checkpoint audit độc lập;<br>không khẳng định hash chain đơn lẻ<br>là bất biến tuyệt đối.|



## **2.4 Ràng buộc và cơ sởthiết kế** 

Hệthống tập trung vào nhân viên, quản lý ra vào và dữliệu chấm công; quản lý khách, sinh trắc học và tính lương nằm ngoài phạm vi. Các cơ sởthiết kếdưới đây xác định cấu hình hạtầng, hợp đồng tích hợp và chính sách vận hành. 

**Bảng 8:** _Cơ sởthiết kếvà điều kiện vận hành_ 

|**Mã**|**Cơ sởthiết kế**|**Điều kiện / tác động**|
|---|---|---|
|A-01|Bình Dương dựkiến 6 trạm (3 vào, 3 ra),<br>Long An 4 (2 vào, 2 ra).|Khảo sát lưu lượng, hàng chờvà hướng thực<br>tế; tải 800/30 phút không cho biết mức tập<br>trung tại từng cổng.|
|A-02|HR cung cấp API đọc hồsơ; hỗtrợđịnh<br>danh nhân viên ổn định.|Nếu không có, dùng nhập dữliệu được HR<br>duyệt; thiết kếkhông tựghi ngược hồsơ vào<br>HR.|
|A-03|API cổng có thểhỗtrợcommand_id và<br>truy vấn trạng thái.|Không tựretry lệnh có kết quảkhông rõ;<br>dùng GateOutcomeUnknown và đối soát.|



12 

2 Yêu cầu hệ thống và ràng buộc thiết kế 



|**Mã**|**Cơ sởthiết kế**|**Điều kiện / tác động**|
|---|---|---|
|A-04|HR nhận lô có batch_id và trảkết quảtheo<br>bản ghi.|Nếu không có idempotency hoặc truy vấn<br>kết quả, cần quy trình xác nhận/gửi bù,<br>không giảđịnh xuất đúng một lần.|
|A-05|LAN ổn định, có UPS, VPN giữa hai nhà<br>máy và vịtrí đặt central được chấp thuận.|Bình Dương là site central; Long An giữDR.<br>Điều kiện điện, mạng và ngân sách phải<br>khảo sát.|
|A-06|Dùng múi giờAsia/Ho_Chi_Minh; lưu<br>timestamp UTC cùng thời điểm nhận và<br>nguồn thời gian.|Làm rõ ca qua đêm, ngày công, điều chỉnh<br>sau chốt; HR quyết định quy tắc liên quan<br>lương.|
|A-07|Hai lượt đến bốn lượt quét/người/ngày, 26<br>ngày/tháng chỉdùng ước lượng.|Sửdụng đểtính dung lượng sựkiện, chỉmục<br>và lưu trữdựphòng.|
|A-08|Lưu sựkiện và audit dựkiến 5 năm; thời<br>gian giữtại edge 30 ngày sau đối soát.|Áp dụng chính sách lưu trữ, phân quyền, xóa<br>hoặc ẩn danh cho cảdữliệu chính và bản<br>sao lưu.|
|A-09|QR ứng dụng/web là token máy chủký,<br>TTL dựkiến 60 giây.|Email gửi liên kết truy cập QR ngắn hạn;<br>QR tĩnh theo ngày chỉlà lựa chọn bổsung<br>cần phê duyệt rủi ro.|
|A-10|Quyền/cấu hình offline có thời hạn tin cậy<br>tối đa 30 phút.|Hết thời hạn tin cậy: dừng cấp quyền tự<br>động, bảo vệxửlý theo quy trình; không ảnh<br>hưởng cơ chếthoát hiểm độc lập.|



## **2.5 Phân tích khối lượng và khảnăng xửlý** 

Tải trung bình trong khoảng giao ca là 800/(30 _×_ 60) _≈_ 0 _,_ 44 giao dịch/giây tại mỗi nhà máy. Đây là trung bình trong 30 phút, không mô tảcác đợt dồn vài giây. Hai nhà máy có thểgiao ca cùng lúc, vì vậy mô hình tải phải xét đồng thời và trạm lệch tải. Với giảđịnh 2–4 lượt/người/ngày, có khoảng 2.800–5.600 sựkiện/ngày và 72.800–145.600 sựkiện/tháng. Nếu tạm tính 1 KB/sựkiện, dữliệu thô khoảng 73–146 MB/tháng; chỉmục, lịch sửtrạng thái, audit, WAL và backup làm dung lượng thực lớn hơn và phải đo bằng mẫu dữliệu. 

Tải này không tựbiện minh cho hệthống xửlý dữliệu lớn hoặc microservices rất nhỏ. Các rủi ro chủyếu là độtrễtại cổng, ghi nhận bền vững, quyền offline và tích hợp ngoài. Biên tải kiểm chứng được đặt ởmức 10 yêu cầu/giây/nhà máy. Sốkiosk cần khảo sát thời gian thao tác và năng lực cơ khí; không suy ra giới hạn vật lý chỉtừ2 giây phản hồi phần mềm. 

- **2.6 Ma trận quyền ởmức nghiệp vụ** 

13 

2 Yêu cầu hệ thống và ràng buộc thiết kế 



<!-- Start of picture text -->
xr DAI HOC QUI 1A THANH PHO HO CHi MINH<br>G3 TRUONG BAI HOC BACH KHOA<br><!-- End of picture text -->

**Bảng 9:** _Quyền theo vai trò và phạm vi dữliệu_ 

|**Vai trò**|**Được phép**|**Giới hạn**|
|---|---|---|
|Nhân viên|Hiển thịQR, tra cứu cá nhân, gửi giải trình<br>nếu được duyệt phạm vi.|Chỉdữliệu của bản thân; không tựsửa<br>sựkiện hoặc mởcổng thủcông.|
|Giám sát|Xem đội/ca, xác minh giải trình.|Chỉđội/ca được giao; không tựcấp<br>quyền hệthống.|
|Nhân sự|Quản lý trạng thái nghiệp vụ, duyệt điều<br>chỉnh theo thẩm quyền, báo cáo/xuất HR.|Theo nhà máy được giao; cơ chế<br>người lập/người duyệt được cấu hình<br>và audit.|
|Bảo vệ|Giám sát cổng, xửlý ngoại lệtại trạm; mở<br>thủcông nếu có quyền.|Theo nhà máy/trạm; phải nhập lý do;<br>không tựxác nhận công nếu thiếu<br>danh tính.|
|Quản trị|Cấu hình kỹthuật, vai trò, trạm, kiểm tra<br>log và phục hồi.|Không mặc nhiên có quyền sửa chấm<br>công; quyền đặc quyền có kiểm soát<br>và audit riêng.|
|Ban điều hành|Xem báo cáo tổng hợp.|Chỉđọc trong phạm vi được cấp;<br>không điều khiển cổng hoặc điều<br>chỉnh công.|



14 

3 Architecture Characteristics 



# **Chương 3 – Architecture Characteristics** 

## **3.1 Quy trình xác định** 

Đặc tính kiến trúc là tiêu chí chất lượng chi phối cách phân chia, giao tiếp và triển khai hệthống. Nhóm thực hiện năm bước: (1) lấy NFR và hạn tích hợp từChương 2; (2) bổsung mối quan tâm của stakeholders và kịch bản lỗi; (3) dùng khối lượng đểloại giải pháp vượt nhu cầu; (4) ưu tiên theo tác động nếu không đạt; (5) chuyển mỗi đặc tính thành kịch bản đo và quyết định cấu trúc. Kết quảphải truy vết được, thay vì chọn danh sách thuật ngữchung cho mọi dự án. 

## **3.2 Danh sách đặc tính ứng viên** 

**Bảng 10:** _Đặc tính ứng viên và mức ưu tiên_ 

|**Đặc tính**|**Căn cứTMC**|**Kết luận**|
|---|---|---|
|Reliability / Data<br>integrity|Sai hoặc thiếu dữliệu ảnh hưởng trực tiếp<br>chấm công và đối soát.|Chủđạo 1: ghi bền vững,<br>chống trùng và truy vết.|
|Performance /<br>Responsiveness|Kiosk không quá 2 giây vào giờgiao ca.|Chủđạo 2: đường xửlý ngắn,<br>chạy tại nhà máy.|
|Security / Privacy /<br>Auditability|RBAC, dữliệu cá nhân, truy vết thao tác.|Chủđạo 3: kiểm soát quyền,<br>giảm thiểu dữliệu, audit.|
|Availability / Fault<br>tolerance|Cổng phải có hành vi rõ khi WAN, thiết bị<br>hoặc node lỗi.|Hỗtrợcao; có giới hạn khi<br>không bảo đảm lưu bền hoặc<br>quyền còn hiệu lực.|
|Interoperability|Hai hệthống ngoài đã tồn tại, có hạn dữ<br>liệu tháng.|Hỗtrợcao; adapter, hợp đồng<br>và đối soát.|
|Maintainability /<br>Extensibility|SOLID và khảnăng bổsung nghiệp vụ,<br>cổng, nhà máy.|Hỗtrợ; phân miền và port rõ.|
|Observability /<br>Recoverability|Nhiều site, tác vụxuất nền và hàng đợi có<br>thểtồn đọng.|Hỗtrợ; trạng thái có thểđo và<br>có runbook.|
|Scalability / Elasticity|Tải bình quân vừa phải, cao điểm dựđoán<br>theo ca.|Mởrộng vừa phải; không ưu<br>tiên tựco giãn phức tạp khi<br>chưa có bằng chứng.|
|Simplicity / Cost|Đội phát triển và năng lực vận hành hữu<br>hạn.|Ràng buộc khi chọn style;<br>không loại bỏbảo mật hoặc độ<br>bền đểgiảm công sức.|



15 

3 Architecture Characteristics 



## **3.3 Đặc tính được chọn và định nghĩa vận hành** 

Mỗi kịch bản gồm nguồn kích thích, môi trường, đối tượng chịu tác động, phản ứng và thước đo. Các thước đo được sửdụng làm tiêu chí đánh giá chất lượng kiến trúc. 

**Bảng 11:** _Kịch bản chất lượng ưu tiên_ 

|**Mã / đặc tính**|**Kích thích và môi trường**|**Phản ứng và thước đo**|
|---|---|---|
|QS-01: toàn vẹn|Kiosk gửi một lượt quét hợp lệrồi<br>mất phản hồi, sau đó gửi lại cùng<br>mã.|Edge trảtrạng thái đã lưu hoặc đang đối<br>soát; central nhận lặp không nhân đôi; 1<br>scan_id và tối đa 1 command_id nghiệp vụ.|
|QS-02: hiệu năng|Mỗi nhà máy phát 800 lượt/30<br>phút, có burst và báo cáo đang<br>chạy.|Mỗi phản hồi đo được không quá 2 giây;<br>công bốsốvi phạm và phân vị. Timeout trả<br>trạng thái không rõ thay vì giảthành công.|
|QS-03: bảo mật|Nhân viên thửđọc lịch sửngười<br>khác hoặc sửa quyền.|Server từchối; dữliệu người khác không bị<br>lộ; có audit hành động nhạy cảm và kết quả<br>kiểm tra.|
|QS-04: sẵn sàng|WAN gián đoạn, LAN và kho<br>edge vẫn hoạt động.|Edge dùng chính sách còn hiệu lực, lưu<br>outbox; hết hạn tin cậy thì dừng cấp quyền<br>tựđộng. Khi mạng lại, chuyển bù và đối<br>soát không thiếu ID.|
|QS-05: tích hợp|HR trảlỗi, timeout hoặc chỉnhận<br>một phần lô.|Giữbatch_id/snapshot; đối soát và chỉgửi<br>phần cần thiết theo hợp đồng; cảnh báo<br>sớm, mục tiêu nội bộ08:00 và hạn ngoài<br>12:00 ngày 01.|
|QS-06: thay đổi|API cổng thay phiên bản hoặc<br>thêm một quy tắc truy cập.|Thay adapter hoặc strategy; nghiệp vụlõi<br>giữnguyên; bộcontract test phải chạy cho<br>adapter mới.|
|QS-07: phục hồi|Tắt một node edge trong lúc xửlý,<br>rồi phục hồi.|Chỉwriter có lease hợp lệđược phát lệnh;<br>bản ghi đã commit đồng bộkhông thiếu<br>trong phạm vi một node lỗi. Mục tiêu<br>chuyển vai trò 5 phút, cần diễn tập.|



**3.4 Ma trận truy vết yêu cầu đến đặc tính** 

16 

3 Architecture Characteristics 



**Bảng 12:** _Truy vết đặc tính, quyết định và phép kiểm_ 

|**Yêu cầu**|**Đặc tính / thành phần**|**Quyết định và phép kiểm**|
|---|---|---|
|NFR-R1, R2; FR-A3,<br>A4, A6|Reliability: C08 Recorder, C11<br>Forwarder, C12 Ingestor.|ADR-05/06/07/08; commit trước lệnh,<br>outbox và unique key. Kiểm tra tập ID, thử<br>crash ởtừng điểm commit/ack.|
|NFR-P1, P2; FR-A1,<br>A2|Performance: C05–C09 tại<br>edge.|ADR-03/10; không gọi central đồng bộ<br>trên đường quét. Thửtải và đo ngân sách<br>từng bước.|
|NFR-S1, PR1, S2;<br>FR-R5, S1, S4|Security/Privacy: C02, C06,<br>C23–C26.|ADR-04/11/12/13; kiểm tra token, quyền,<br>log và checkpoint audit. Không xem mã<br>giảdanh là dữliệu vô danh.|
|NFR-I1; FR-R3, R4|Interoperability: C20–C22.|ADR-09/10; batch và xác nhận nghiệp vụ;<br>thửlỗi một phần, gửi lại và điều chỉnh sau<br>chốt.|
|NFR-A1, O1; FR-G2,<br>A6|Availability: edge, GSS, kho<br>dữliệu.|ADR-03/08/15; fencing, chính sách<br>offline, heartbeat; diễn tập mất WAN, mất<br>node, đầy đĩa.|
|NFR-M1, D1; FR-S2,<br>S3|Maintainability/Recoverability:<br>ports, cấu hình, pipeline.|ADR-02/14; kiểm tra dependency, thay<br>simulator bằng HTTP adapter, thửrestore.|



## **3.5 Xung đột và đánh đổi giữa các đặc tính** 

**Bảng 13:** _Đánh đổi và giới hạn chấp nhận_ 

|**Xung đột**|**Quyết định cân bằng**|**Rủi ro còn lại**|
|---|---|---|
|Độbền và độtrễ|Commit cục bộtrước khi gửi lệnh; không<br>bỏfsync đểđạt đẹp chỉsố. Dành ngân<br>sách cho sao chép đồng bộ.|Nếu không đạt ngân sách, cần<br>tối ưu/đổi hạtầng hoặc điều<br>chỉnh mục tiêu với chủhệ<br>thống; không xác nhận dữliệu<br>chưa bền.|
|Sẵn sàng và quyền<br>mới nhất|Cho edge xửlý trong cửa sổtin cậy có<br>giới hạn; cập nhật thu hồi mục tiêu 60 giây<br>khi online.|Mất WAN vẫn có rủi ro quyền<br>cũ; hết 30 phút dựkiến thì<br>chuyển kiểm soát thủcông,<br>không duy trì vô hạn.|
|Sẵn sàng và RPO 0 khi<br>lỗi node|Hai bản dữliệu đồng bộtrong site; writer<br>có lease/fencing. Không tựhạsang<br>commit một bản khi standby mất.|Dừng ghi tựđộng đểbảo toàn<br>dữliệu; cần xửlý tại cổng theo<br>quy trình. Thảm họa mất cảsite<br>có RPO riêng.|



17 

3 Architecture Characteristics 



<!-- Start of picture text -->
xr DAI HOC QL IA THANH PF 410 CHI MINH<br>G3 TRUONG BAI HOC BACH KHOA<br><!-- End of picture text -->

|**Xung đột**|**Quyết định cân bằng**|**Rủi ro còn lại**|
|---|---|---|
|Bảo mật và thuận tiện<br>QR|QR ngắn hạn do máy chủký; email ưu<br>tiên gửi liên kết; chống phát lại trong<br>phạm vi edge.|Không ngăn tuyệt đối chụp màn<br>hình hoặc người dùng đưa điện<br>thoại cho người khác. Chống<br>phát lại liên nhà máy có độtrễ.|
|Kiểm toán và quyền<br>riêng tư|Log tối thiểu, dùng mã tham chiếu; chỉ<br>người có quyền mới liên kết danh tính;<br>checkpoint độc lập.|Mã giảdanh vẫn có thểliên kết<br>cá nhân; phải quản lý cảquyền<br>DBA và bản sao lưu.|
|Cô lập lỗi và đơn giản|Năm dịch vụmiền lớn, một nền tảng dữ<br>liệu có schema sởhữu; tách worker báo<br>cáo khỏi đường quét.|Cụm DB dùng chung vẫn là<br>miền lỗi chung; giới hạn tài<br>nguyên và đo tải là bắt buộc.|



18 

4 Structure: lựa chọn và xây dựng kiến trúc 



# **Chương 4 – Structure: lựa chọn và xây dựng kiến trúc** 

## **4.1 So sánh và lựa chọn phong cách kiến trúc** 

### **4.1.1 Phương án và tiêu chí đánh giá** 

Kiến trúc logical và vịtrí triển khai là hai quyết định liên quan nhưng không đồng nhất. Modular monolith ởcentral vẫn có thểkết hợp edge; không loại phương án này chỉvì nó là monolith. Tương tự, SOA không bắt buộc có một ESB đơn điểm lỗi, và microservices không tự bảo đảm sẵn sàng hoặc an toàn dữliệu. Việc so sánh dùng các phương án cụthểtrong bối cảnh TMC. 

**Bảng 14:** _Các phong cách được cân nhắc_ 

|**Phong cách**|**Lợi ích trong TMC**|**Giới hạn / vai trò**|
|---|---|---|
|Layered monolith tập<br>trung|Ít đơn vịvận hành; giao dịch dữ<br>liệu đơn giản.|Nếu toàn bộxửlý cổng ởcentral thì<br>WAN nằm trên đường găng; việc tách<br>edge sẽthay đổi phương án triển khai.|
|Modular monolith<br>central + edge|Module theo miền, chi phí vận<br>hành thấp; edge vẫn giải quyết độ<br>trễcục bộ.|Worker có thểtách tiến trình, nhưng<br>miền central vẫn gắn chung nhịp phát<br>hành; là phương án dựphòng thực tế.|
|Microkernel|Thay plugin chính sách hoặc loại<br>thiết bịthuận tiện.|Phù hợp bên trong policy engine, chưa<br>mô tảđủtích hợp và dựphòng toàn hệ<br>thống.|
|Service-based central +<br>edge|Một sốdịch vụmiền lớn; báo cáo,<br>quản trịvà ingestion có đơn vị<br>triển khai riêng.|Tăng công sức hợp đồng và nhất quán<br>cuối cùng; cơ sởdữliệu dùng chung<br>cần giới hạn sởhữu schema.|
|Event-driven làm<br>khung chính|Tách producer/consumer, xửlý<br>nền và phát lại tốt.|Nếu dùng bất đồng bộcho cảquyết<br>định cổng sẽkhó kiểm soát phản hồi;<br>chỉdùng cho đồng bộvà hậu xửlý.|
|Microservices chi tiết|Độc lập triển khai và mởrộng<br>từng dịch vụnhỏ.|Nhiều vận hành, quan sát, hợp đồng và<br>điểm lỗi; chưa có tải hoặc tổchức đội<br>đủđểbiện minh.|



### **4.1.2 Ma trận đánh giá có trọng số** 

Điểm 1–5 thểhiện mức phù hợp tương đối (5 tốt nhất), không phải kết quảbenchmark. Trọng sốđược suy ra từcác đặc tính ởChương 3. Ký hiệu L: layered; M: modular monolith + edge; K: microkernel; S: service-based + edge; E: event-driven làm khung chính; V: microservices. Điểm tổng bằng tổng của trọng sốnhân điểm từng tiêu chí, tối đa 160. 

19 

4 Structure: lựa chọn và xây dựng kiến trúc 



**Bảng 15:** _So sánh định hướng các phương án kiến trúc_ 

|**Tiêu chí (trọng số)**|**L**|**M**|**K**|**S**|**E**|**V**|
|---|---|---|---|---|---|---|
|Toàn vẹn / độtin cậy (5)|3|4|3|4|4|4|
|Độtrễtại cổng (4)|3|4|4|4|3|3|
|Bảo mật / kiểm toán (4)|3|4|3|4|3|4|
|Cô lập lỗi / sẵn sàng (5)|2|3|2|4|4|5|
|Tích hợp (3)|3|4|4|4|4|4|
|Bảo trì / thay đổi (3)|2|4|4|4|3|4|
|Đơn giản / vận hành (3)|5|4|3|3|2|1|
|Mởrộng quy mô (2)|2|3|2|3|5|5|
|Triển khai / kiểm thử(3)|3|4|3|4|3|4|
|Tổng|92|121|99|123|110|122|



### **4.1.3 Lựa chọn và phân tích độnhạy** 

Phương án S đạt 123/160, gần phương án V 122/160 và M 121/160. Chênh lệch nhỏ không chứng minh S luôn tốt hơn: nếu giảm trọng sốcô lập lỗi từ5 xuống 3 và tăng trọng số đơn giản từ3 lên 5, M đạt 123 còn S đạt 121. Vì vậy, nhóm chọn **Service-Based Architecture kết hợp Edge Access Agent và tích hợp hướng sựkiện** theo mục tiêu cô lập ingestion, báo cáo và quản trị; modular monolith central + edge là phương án giảm độphức tạp nếu năng lực vận hành hoặc thửnghiệm không ủng hộlựa chọn ban đầu. 

Central gồm năm dịch vụmiền ICS, AAS, GSS, RIS và ADS. AAS có phần edge và phần central, dùng cùng các khái niệm nghiệp vụnhưng là các đơn vịtriển khai khác nhau. Tích hợp sựkiện dùng outbox và consumer khửtrùng; luồng quyết định cổng là đồng bộtại nhà máy. Bên trong từng dịch vụ, ports và adapters tách nghiệp vụkhỏi HTTP, cơ sởdữliệu và thiết bị. Lựa chọn này không yêu cầu một database riêng cho từng dịch vụhoặc Kubernetes ngay từđầu. 

## **4.2 Kiến trúc logical: các bước xây dựng** 

**Bảng 16:** _Đầu vào và đầu ra của quy trình xây dựng logical_ 

|**Bước**|**Đầu vào**|**Đầu ra / kết quả**|
|---|---|---|
|1. Ranh giới|Stakeholders, phạm vi và hai|Sơ đồngữcảnh; tác nhân và trách nhiệm|
||luồng quét/xuất HR.|ngoài hệthống.|
|2. Thành phần|Hành động trong story và|Danh mục C01–C26, mỗi thành phần có|
||FR/NFR.|trách nhiệm và yêu cầu gốc.|



20 

4 Structure: lựa chọn và xây dựng kiến trúc 



|**Bước**|**Đầu vào**|**Đầu ra / kết quả**|
|---|---|---|
|3. Dịch vụ/ dữliệu|Thành phần và lý do thay đổi.|ICS/AAS/GSS/RIS/ADS; schema sởhữu và<br>hình thức AAS-Edge/Central.|
|4. Cohesion / SRP|Nhóm trách nhiệm và điểm biến<br>đổi.|Tách verifier, policy, recorder, commander;<br>port dùng chung transaction đúng chỗ.|
|5. Đặc tính|Độtrễ, dữliệu, quyền offline và<br>cô lập lỗi.|Placement logical edge/central; bỏ<br>HR/reporting khỏi đường quét.|
|6. Connector|Luồng và ranh giới dịch vụđã<br>chọn.|API/sựkiện có version, timeout, ack và quy<br>tắc retry.|
|7. Dữliệu / định<br>danh|Sựkiện, kết quảthiết bịvà báo<br>cáo.|scan_id/command_id/event_id/batch_id;<br>lịch sửvà snapshot có phiên bản.|
|8. Kiểm tra|Các mô hình và failure scenario.|Điểm thiếu/trùng trách nhiệm, phép kiểm và<br>điều chỉnh ADR.|



### **4.2.1 Bước 1: xác định ranh giới và luồng nghiệp vụ** 

Đầu vào là stakeholders, phạm vi và FR/NFR. Luồng A: nhân viên hiển thịQR, kiosk gửi yêu cầu, hệthống kiểm tra và lưu kết quả, gọi cổng khi được phép, sau đó tổng hợp công. Luồng B: nhân sựkiểm tra ngoại lệ, tạo snapshot kỳ, chuyển dữliệu cho HR và đối soát. Kết quảbước này là sơ đồngữcảnh và danh sách các điểm tích hợp, không đưa tiền lương hoặc điều khiển cơ khí vào miền nghiệp vụ. 



<!-- Start of picture text -->
Nhân viên Hệthống<br>cổng quay<br>QR trên điện thoại<br>API điều khiển<br>TMC-AACS<br>Kiểm soát ra<br>vào, chấm công<br>Bình Dương và Long An<br>Giám sát, HR/Payroll<br>HR, bảo vệ, Đối soát và<br>quản trị, điều hành tính lương<br>kiosk: lượt quét lệnh / kết quả<br>web: theo quyền lô công / xác nhận<br><!-- End of picture text -->

**Hình 1:** _Ngữcảnh TMC-AACS và các ranh giới tích hợp_ 

### **4.2.2 Bước 2: nhận diện và gán trách nhiệm cho thành phần** 

Từhành động trong các story và hai luồng trên, nhóm nhận diện 26 thành phần. Mỗi thành phần có trách nhiệm chính và mã yêu cầu; tránh tạo dịch vụchỉvì tên một màn hình hoặc một bảng dữliệu. 

21 

4 Structure: lựa chọn và xây dựng kiến trúc 



**Bảng 17:** _Danh mục thành phần và truy vết yêu cầu_ 

|**Mã**|**Thành phần**|**Trách nhiệm**|**Miền / yêu cầu**|
|---|---|---|---|
|C01|Employee Directory /<br>HR Reader|Hồsơ tối thiểu, quyền nhà máy; đọc<br>HR qua adapter nếu có.|ICS; FR-U1, U4|
|C02|Credential Manager|Cấp, thu hồi và phiên bản credential.|ICS; FR-U2, U3|
|C03|QR Token Issuer|Ký QR ngắn hạn phía máy chủ.|ICS; FR-U2, U3|
|C04|Notification Adapter|Gửi email/liên kết, theo dõi gửi thất<br>bại.|ICS; FR-U2|
|C05|Scan Endpoint|Nhận scan_id, xác thực kiosk, trảkết<br>quả.|AAS-Edge; FR-A1, A4|
|C06|QR Verifier|Kiểm tra chữký, issuer, audience,<br>hạn và key id.|AAS-Edge; FR-A1;<br>NFR-S2|
|C07|Access Policy Engine|Quyền nhà máy, trạng thái, phát lại<br>và quy tắc vào/ra.|AAS-Edge; FR-A1, A7|
|C08|Attendance Recorder|Transaction sựkiện, trạng thái, intent<br>và outbox.|AAS-Edge; FR-A3, A4;<br>NFR-R1|
|C09|Gate Commander|Điều phối command_id, gọi cổng và<br>ghi outcome.|AAS-Edge; FR-A2;<br>NFR-I1|
|C10|Policy / Credential<br>Sync|Bản sao quyền, khóa công khai và<br>cấu hình có phiên bản.|AAS-Edge; FR-U3, A6,<br>S2|
|C11|Event Forwarder|Gửi bù theo cursor, ack và backoff.|AAS-Edge; FR-A6;<br>NFR-R2|
|C12|Event Ingestor|Nhận lô, khửtrùng và commit sự<br>kiện trung tâm.|AAS-Central; FR-A3, A4,<br>A6|
|C13|Attendance Projector|Tổng hợp hiện diện và gắn cờngoại<br>lệ.|AAS-Central; FR-R1, R2|
|C14|Adjustment Workflow|Giải trình, xác minh, phê duyệt và<br>bản ghi bù.|AAS-Central; FR-A5|
|C15|Station Registry|Nhà máy, trạm, hướng và mapping<br>thiết bị.|GSS; FR-G1|
|C16|Station Health|Heartbeat, tình trạng và cảnh báo.|GSS; FR-G2; NFR-O1|
|C17|Manual Access<br>Coordinator|Yêu cầu thủcông có quyền và lý do,<br>chuyển tới edge.|GSS; FR-G3|
|C18|Report Builder|Báo cáo cá nhân, đội, nhà máy theo<br>quyền.|RIS; FR-R1, R2|
|C19|Dashboard Query|Mô hình đọc tổng hợp, thời điểm cập<br>nhật.|RIS; FR-R1|



22 

4 Structure: lựa chọn và xây dựng kiến trúc 



|**Mã**|**Thành phầ**|**n**|**Trách nhiệm**|**Miền / yêu cầu**|
|---|---|---|---|---|
|C20|Period / Sna<br>Manager|pshot|Khóa snapshot có phiên bản và phát<br>hiện nguồn chưa đủ.|RIS; FR-R4|
|C21|HR Export|Adapter|Ánh xạ, gửi lô và truy vấn kết quả<br>theo hợp đồng.|RIS; FR-R3, R4|
|C22|Reconciliati|on Service|So khớp tập ID, bản ghi được nhận<br>và phần thiếu.|RIS; FR-R4; NFR-R1|
|C23|Identity / A|uthorization|Tài khoản, vai trò, policy và scope.|ADS; FR-S1; NFR-S1|
|C24|Audit Write|r / Reader|Nhận audit, tra cứu và kiểm tra<br>checkpoint.|ADS; FR-R5|
|C25|Configurati|on Manager|Cấu hình có phiên bản và phân phối.|ADS; FR-S2|
|C26|Privacy / Re|tention|Chính sách dữliệu và yêu cầu xửlý<br>theo thẩm quyền.|ADS; FR-S4|
|**.2.3**<br> <br>**Dịch v**|**Bước 3: nhó**<br>**ụ**|**m thành dị**<br>**Bảng 18**<br>**Thành ph**|**ch vụvà xác định sởhữu dữliệu**<br>**:**_Ranh giới dịch vụvà vùng dữliệu sở_<br>**ần / dữliệu**<br>**Lý do**|_hữu_<br>**nhóm**|
|ICS: Id<br>Creden|entity and<br>tial|C01–C04;<br>credential,|employee, site_authorization,<br>signing_key_metadata.<br>Thay<br>và chí<br>nằm t<br>bảng t|đổi theo vòng đời nhân viên<br>nh sách QR. Khóa bí mật<br>rong kho khóa, không trong<br>hông thường.|
|AAS:<br>Attend|Access and<br>ance|C05–C14;<br>command_<br>central: ev<br>adjustment|edge: access_event,<br>intent, status_history, outbox;<br>ent replica, attendance_day,<br>.<br>Tách<br>công;<br>hợp đ|ghi sựkiện và chiếu chấm<br>hai vịtrí triển khai, cùng<br>ồng sựkiện.|
|GSS: G|ate Station|C15–C17;<br>heartbeat,|factory, station, mapping,<br>manual_request.<br>Cấu h<br>hành|ình thiết bịvà quy trình vận<br>cổng thay đổi riêng.|
|RIS: R<br>Integra|eporting and<br>tion|C18–C22;<br>export_bat|read models, period, snapshot,<br>ch, receipt.<br>Truy<br>khỏi x|vấn nặng và API HR tách<br>ửlý tại cổng.|
|ADS:||C23–C26;|account, role,<br>Chính|sách xuyên suốt có giao|
|Admin<br>Audit|istration and|scoped_per<br>retention_p|mission, config, audit,<br>olicy.<br>diện r<br>quyền|õ; kho audit được phân<br>riêng.|



### **4.2.3 Bước 3: nhóm thành dịch vụvà xác định sởhữu dữliệu** 

Central có thểdùng chung cụm PostgreSQL vật lý, nhưng mỗi dịch vụcó schema, tài khoản và migration riêng. Không join hoặc ghi chéo schema đểvượt API; dữliệu báo cáo được tạo bằng sựkiện/read model. Việc dùng chung máy không biến quyền sởhữu dữliệu thành dùng chung tùy ý. 

23 

4 Structure: lựa chọn và xây dựng kiến trúc 



### **4.2.4 Bước 4: kiểm tra SRP và phân lớp** 

C06 xác minh QR khác C07 quyết định quyền vì định dạng token và quy tắc ra vào thay đổi độc lập. C08 ghi dữliệu khác C09 tác động thiết bịvì lỗi API cổng không được xóa dấu vết đã ghi. Mỗi dịch vụcó lớp domain, application, ports và adapters; thành phần HTTP/SQL chỉ hiện thực port. Các miền chỉgiao tiếp qua hợp đồng, không import mã ứng dụng của nhau. 

### **4.2.5 Bước 5: tinh chỉnh theo các đặc tính chủđạo** 

C05–C11 chạy tại nhà máy, dùng chính sách và khóa đã đồng bộcòn hiệu lực; đường quét không gọi HR, RIS, ADS hoặc database central đồng bộ. C12–C14 hợp nhất sựkiện, xửlý công và điều chỉnh tại central. RIS và tác vụemail chạy nền. Quyền quản trịởcentral vẫn kiểm tra theo máy chủ; xác minh QR tại edge dùng snapshot được ký và có hạn tin cậy, không bỏqua kiểm tra quyền khi offline. 



<!-- Start of picture text -->
Mobile / Web Portal<br>6 nhóm người dùng<br>Gateway<br>xác thực / định tuyến<br>ICS AAS-Central GSS<br>C01–C04 C12–C14 C15–C17<br>RIS ADS<br>C18–C22 C23–C26<br>Broker central<br>Sựkiện nội bộ<br>outbox / inbox<br>Edge Bình Dương Edge Long An<br>C05–C11 + C05–C11 +<br>kho cục bộ kho cục bộ<br>LAN LAN<br>Kiosk / cổng Kiosk / cổng<br>quay BD quay LA<br>HTTPS batch / ack HTTPS batch / ack<br><!-- End of picture text -->

**Hình 2:** _Logical containers và giao tiếp giữa edge và central_ 

Sơ đồtrên tóm tắt quan hệlogical, không có nghĩa edge phát trực tiếp vào broker qua WAN: C11 gửi lô HTTPS đến C12; C12 commit dữliệu và outbox rồi phát sựkiện nội bộ. Quyền và cấu hình đi từICS/GSS/ADS đến C10 qua đồng bộcó phiên bản. Nét liền mô tảlời gọi; nét đứt mô tảtrao đổi nền. Mỗi miền có vùng dữliệu như Bảng 18. 

24 

4 Structure: lựa chọn và xây dựng kiến trúc 



### **4.2.6 Bước 6: xác định hợp đồng giao tiếp** 

**Bảng 19:** _Hợp đồng giao tiếp và xửlý lỗi_ 

|**Kết nối**|**Kiểu / dữliệu**|**Bảo đảm và lỗi**|
|---|---|---|
|Kiosk đến C05|HTTPS tại LAN; scan_id,<br>station_id, token, direction.|Kiosk được xác thực; cùng scan_id phải<br>giữnội dung. Đổi payload cùng ID bịtừ<br>chối; retry trảkết quảđã lưu.|
|C09 đến turnstile|HTTP(S) qua adapter;<br>command_id, gate_id, action.|Timeout 700 ms ban đầu. Mất phản hồi là<br>Unknown; chỉretry nếu có chống lặp<br>được xác nhận và còn ngân sách.|
|C11 đến C12|HTTPS mTLS theo lô; event_id,<br>scan_id, version, schema_version.|Ack sau commit trung tâm; unique key<br>cho từng envelope. Mất ack gửi lại không<br>tạo thêm tác động.|
|ICS/GSS/ADS đến<br>C10|Snapshot/delta có revision,<br>effective_at và expires_at.|Xác thực nguồn; không chấp nhận<br>revision cũ hơn. Thu hồi online mục tiêu<br>60 giây; quá hạn tin cậy dừng tựcấp<br>quyền.|
|Dịch vụcentral qua<br>broker|Sựkiện có event_id, owner,<br>version và correlation_id.|Outbox commit cùng dữliệu; consumer<br>inbox commit cùng cập nhật; lỗi độc<br>chuyển sang vùng xửlý lỗi có cảnh báo.|
|C21 đến HR/Payroll|API lô có batch_id, period,<br>snapshot_version, checksum.|Xác nhận nghiệp vụvà sốbản ghi; lô<br>không rõ kết quảphải được truy vấn/đối<br>soát trước khi gửi lại.|
|Web đến dịch vụ|HTTPS; access token, role và<br>scope.|Gateway kiểm tra bước đầu; mỗi dịch vụ<br>tựkiểm tra quyền. UI không phải lớp bảo<br>vệduy nhất.|



### **4.2.7 Bước 7: mô hình dữliệu và định danh** 

**scan_id** nhận diện một lần quét logic, do kiosk tạo và giữkhi truyền lại. **command_id** gắn duy nhất với ý định điều khiển cho scan đó. **event_id** nhận diện từng thông điệp bất biến (nhận quét, quyết định, kết quảcổng); cùng scan có thểcó nhiều phiên bản trạng thái, nhưng chỉ một bản sựkiện vào/ra gốc. **batch_id** nhận diện lần xuất của một snapshot kỳ. Khửtrùng theo các khóa này không đồng nghĩa chống dùng QR đã sao chép; nonce/policy giải quyết bài toán khác. 

25 

4 Structure: lựa chọn và xây dựng kiến trúc 



**Bảng 20:** _Thực thểdữliệu chính và bất biến_ 

|**Thực thể**|**Khóa / liên kết**|**Bất biến**|
|---|---|---|
|Employee / Credential|employee_ref; credential_id,<br>key_id, revision.|PII nằm tại ICS; employee_ref giảdanh<br>vẫn là dữliệu cần bảo vệ.|
|GateStation|station_id; factory_id, direction,<br>gate_id.|Cấu hình có revision; sựkiện lưu<br>revision đã dùng đểtruy vết.|
|AccessEvent|scan_id duy nhất; employee_ref<br>có thểnull khi QR không xác<br>định.|Ghi nhận thời điểm nhận tại edge và<br>thời điểm nguồn; không sửa sựkiện gốc.|
|GateIntent /<br>StatusHistory|command_id; scan_id;<br>sequence/version.|Intent lưu trước tác động; outcome ghi<br>bổsung. Unknown khác Failed và<br>Confirmed.|
|Outbox / Inbox|event_id duy nhất;<br>payload_version, ack_cursor.|Ghi cùng transaction nghiệp vụ; chưa<br>ack thì giữđểgửi bù. Không xóa chỉvì<br>đã gửi ra socket.|
|AttendanceDay /<br>Adjustment|employee_ref, local_date,<br>projection_version;<br>adjustment_id.|Dữliệu chiếu tái tạo được; điều chỉnh có<br>lý do/phê duyệt. Không tựtính lương<br>hoặc suy diễn làm thêm giờ.|
|PeriodSnapshot /<br>HrBatch|period, snapshot_version;<br>batch_id, receipt.|Snapshot đã xuất không bịghi đè âm<br>thầm; điều chỉnh sinh phiên bản/lô bổ<br>sung.|
|AuditRecord|audit_id; actor_ref, action,<br>object_ref, timestamp,<br>prev_hash.|Chỉthêm với tài khoản ứng dụng;<br>checkpoint độc lập đểphát hiện sửa<br>chuỗi.|



- **4.2.8 Bước 8: kiểm tra bằng kịch bản và tinh chỉnh** 

Chạy qua kịch bản quét hợp lệ, mất WAN, cổng timeout, node chết sau commit và xuất HR nhận một phần. Nếu không tìm được nơi giữintent hoặc kết quảchưa xác định, mô hình thiếu trách nhiệm. Nếu báo cáo phải join trực tiếp kho edge, ranh giới sai. Các kịch bản và phép kiểm được tổng hợp ởChương 5. 

- **4.3 Kiến trúc physical: các bước xây dựng** 

26 

4 Structure: lựa chọn và xây dựng kiến trúc 



**Bảng 21:** _Đầu vào và đầu ra của quy trình xây dựng physical_ 

|**Bước**|**Đầu vào**|**Đầu ra / kết quả**|
|---|---|---|
|1. Deployment<br>units|Miền và connector logical.|Kiosk, edge, các dịch vụcentral, DB, broker,<br>audit/backup.|
|2. Vùng / vịtrí|Miền lỗi, LAN/WAN và quyền<br>truy cập.|Site và vùng mạng, tuyến liên lạc, xác thực<br>thiết bị/mTLS.|
|3. Lưu bền / HA|NFR-R1, A1 và giảđịnh hạtầng.|Sync pair, lease/fencing, quorum ba node;<br>RPO/RTO có phạm vi.|
|4. Định cỡ|Workload và retention dựkiến.|Cấu hình thửnghiệm, dung lượng và những<br>phép đo phải thực hiện.|
|5. Ngân sách độtrễ|Giới hạn kiosk và thời gian API<br>ngoài.|Phân bổ1.600 ms, dựphòng 400 ms;<br>deadline tổng và phép thử.|
|6. Bảo mật|Dữliệu, thiết bịvà phạm vi<br>quyền.|Vịtrí khóa, token, quyền DB, mã hóa và dữ<br>liệu tối thiểu.|
|7. Failure modes|Các node/kênh/API có thểlỗi.|Hành vi suy giảm, cơ chếphục hồi và giới<br>hạn không thểche giấu.|
|8. Vận hành / kiểm<br>chứng|Deadline HR và các chỉtiêu chất<br>lượng.|Lịch snapshot/xuất/đối soát, metric, cảnh<br>báo và kếhoạch kiểm.|



### **4.3.1 Bước 1: xác định đơn vịtriển khai** 

**Bảng 22:** _Đơn vịtriển khai và vịtrí triển khai_ 

|**Đơn vị**|**Vịtrí / bản sao**|**Vai trò**|
|---|---|---|
|Mobile, web, kiosk|Điện thoại nhân viên; web tại<br>central; kiosk ởtrạm.|Mobile/web hiển thịQR và tác vụ<br>theo quyền; kiosk giữscan_id đang xử<br>lý và trảtrạng thái rõ.|
|Edge Access Agent|Hai host tại mỗi nhà máy, một<br>writer active.|C05–C11; kho PostgreSQL<br>primary/sync standby; giao tiếp LAN<br>với cổng.|
|Witness / quản lý leader|Một nút nhỏđộc lập tại mỗi nhà<br>máy, cùng hai edge tạo 3 thành<br>viên điều phối.|Giữlease/epoch và hỗtrợfencing.<br>Witness không thay thếbản sao dữ<br>liệu sựkiện.|
|ICS, AAS-Central,<br>GSS, RIS, ADS|Central ởBình Dương; mỗi dịch vụ<br>có thểhai instance.|Tách miền và worker. Hai instance<br>phải ởhost khác nhau; chưa khẳng<br>định HA chỉvì chạy hai container.|



27 

4 Structure: lựa chọn và xây dựng kiến trúc 



|**Đơn vị**|**Vịtrí / bản sao**|**Vai trò**|
|---|---|---|
|Central database|Primary + sync standby tại central;<br>DR bất đồng bộởLong An.|Schema sởhữu và tài khoản riêng.<br>Failover cần kiểm tra WAL, lease và<br>chặn primary cũ.|
|Broker|Ba node ởcác host central riêng,<br>quorum queue.|Cần đa số2/3 đểhoạt động; không<br>dùng cụm hai node như bảo đảm chịu<br>lỗi một node.|
|Audit / backup / khóa|Quyền quản trịtách; bản sao<br>backup ởsite khác.|Checkpoint ngoài kho ghi chính; mã<br>hóa và diễn tập restore; bí mật không<br>nằm trong repo hoặc QR.|



Topology sửdụng PostgreSQL, broker RabbitMQ và dịch vụTypeScript/NestJS; giao diện nghiệp vụkhông phụthuộc framework hoặc một phiên bản cụthể. 

### **4.3.2 Bước 2: bốtrí theo vùng mạng và miền lỗi** 

Kiosk, controller và edge ởLAN nhà máy; controller không được công khai Internet. Thiết bịchỉđược gọi endpoint cần thiết bằng danh tính trạm. Central có vùng tiếp nhận API, vùng ứng dụng và vùng dữliệu; web đi qua reverse proxy/gateway, còn DB và broker không mởcho người dùng. Edge và central xác thực mTLS qua VPN/kênh được bảo vệ. Hệthống cấp QR vẫn cần liên lạc central khi cấp mới; offline tại cổng không đồng nghĩa điện thoại luôn lấy được QR mới khi toàn bộmạng công ty mất. 

28 

4 Structure: lựa chọn và xây dựng kiến trúc 





<!-- Start of picture text -->
Nhà máy Bình Dương Nhà máy Long An<br>Kiosk – LAN – Controller Kiosk – LAN – Controller<br>Edge active + standby đồng bộ Edge active + standby đồng bộ<br>Witness / lease / fencing; UPS Witness / lease / fencing; UPS<br>mTLS; gửi bù / ack mTLS; gửi bù / ack<br>Central tại Bình Dương<br>Gateway + 5 dịch vụmiền trên các host ứng dụng<br>PostgreSQL primary / sync standby; tách schema<br>Broker quorum 3 node / đa số2; quan sát và kho khóa<br>Vùng mạng API – ứng dụng – dữliệu<br>WAL / backup; có độtrễ<br>Long An: replica DR bất đồng bộ<br>Backup mã hóa và checkpoint audit<br><!-- End of picture text -->

**Hình 3:** _Topology physical và các miền dựphòng_ 

### **4.3.3 Bước 3: thiết kếlưu bền, HA và chống split-brain** 

Tại edge, transaction quan trọng được xác nhận sau khi WAL đã lưu bền và standby đồng bộđã xác nhận theo cấu hình. Chỉmột writer sởhữu lease/epoch hợp lệđược phát command; khi chuyển vai trò phải cách ly writer cũ bằng fencing, không chỉđổi địa chỉIP. Cụm điều phối có ba thành viên trong site tránh phụthuộc WAN cho quorum. Nếu không có quyền leader hoặc không còn bản sao đồng bộcần thiết, dừng xửlý tựđộng thay vì âm thầm giảm bảo đảm dữliệu. 

RPO 0 được đặt là mục tiêu _cho giao dịch đã commit đồng bộkhi lỗi một node_ , không áp dụng vô điều kiện cho request chưa được chấp nhận hay mất cảnhà máy. Replica DR bất đồng bộcó cửa sổmất dữliệu; RPO site dựkiến không quá 5 phút phải được đo và có thểbù từedge còn tồn tại. Mất đồng thời cảnguồn và các bản sao nằm ngoài bảo đảm này. Mục tiêu khôi phục gồm RTO edge 5 phút, central 60 phút và DR 4 giờ. 

Broker chỉhỗtrợvận chuyển; outbox và kho nghiệp vụlà nguồn phát lại. RabbitMQ quorum queue cần đa số, do đó dùng 3 node thay cấu hình 2 node. Khi broker lỗi, ingress đã commit vẫn được giữtrong DB, báo cáo có thểtrễvà phải thểhiện watermark cập nhật. 

### **4.3.4 Bước 4: định cỡvà dựtoán lưu trữ** 

29 

4 Structure: lựa chọn và xây dựng kiến trúc 



**Bảng 23:** _Cấu hình khởi điểm đểthửnghiệm_ 

|**Thành phần**|**Đềxuất ban đầu**|**Phải đo trước khi chốt**|
|---|---|---|
|Mỗi edge host|2 vCPU, 4 GB RAM, SSD 120 GB;<br>UPS cho host/switch/controller theo<br>khảo sát.|Độtrễfsync và replication, tốc độ<br>controller, backlog khi mất WAN;<br>không suy ra năng lực từvCPU đơn<br>thuần.|
|Central app|2–4 vCPU, 4–8 GB RAM mỗi<br>instance miền; worker báo cáo<br>riêng.|CPU/memory khi tổng hợp, sốkết nối<br>DB và khảnăng cạnh tranh với<br>ingestion.|
|Central PostgreSQL|4 vCPU, 16 GB RAM, SSD 500 GB<br>mỗi node dữliệu.|Dung lượng chỉmục, lịch sửtrạng thái,<br>audit, WAL và backup; retention thực<br>tếdo chính sách quyết định.|
|Broker / witness|Broker 3 host/VM riêng; witness<br>nhỏ, độc lập với hai edge.|Tài nguyên, failure domain và năng lực<br>quản trị. Ba process trên cùng host<br>không chịu được lỗi host.|



### **4.3.5 Bước 5: lập ngân sách độtrễ** 

Ngân sách độtrễđược phân bổcho từng bước xửlý như sau. Tổng 1.600 ms đểdành 400 ms dựphòng so với hạn 2.000 ms. QR decode trước khi gửi được đo riêng đểtheo dõi trải nghiệm; không trừthời gian trong giao thức bằng cách đổi mốc đo sau khi đã chờthiết bị. 

**Bảng 24:** _Ngân sách độtrễdựkiến trên đường quét_ 

|**Bước**|**Ngân sách tối đa dự**<br>**kiến (ms)**|
|---|---|
|LAN, tiếp nhận và xác thực kiosk|100|
|Xác minh QR và snapshot quyền|100|
|Chính sách, chống trùng và xếp hàng|100|
|Commit bền vững và replication|250|
|API controller và chờkết quả|700|
|Ghi outcome và dựng phản hồi|250|
|LAN trảkết quả/ hiển thị|100|
|Tổng / dựphòng so với 2 giây|1.600 / 400|



Mỗi giới hạn là deadline trong tổng budget, không phải timeout độc lập cho phép cộng dồn vô hạn. Không tựthêm một lần gọi cổng 700 ms khi chỉcòn 400 ms. Nếu controller không đáp ứng hợp đồng thời gian, kiến trúc chưa thểđược kết luận đạt NFR-P1; cần đo sớm và thống nhất lại tích hợp. Trảlỗi hoặc Unknown trong 2 giây không thay thếbằng chứng luồng thành 

30 

4 Structure: lựa chọn và xây dựng kiến trúc 



công đạt chất lượng. 

### **4.3.6 Bước 6: bảo vệdữliệu và vận hành an toàn** 

QR dùng token máy chủký với issuer, audience, employee_ref, nonce, thời hạn và key_id; thiết bịchỉhiển thị, không được tựký thay máy chủ. Bản chụp màn hình vẫn có thểbịlợi dụng trong cửa sổhiệu lực; chống phát lại cục bộgiảm rủi ro, không chứng minh đúng người đang cầm điện thoại. Email ưu tiên chứa liên kết xác thực lấy QR mới; cơ chếQR dài hạn chỉlà đề xuất khác mức rủi ro, không âm thầm dùng chung với token 60 giây. 

Khóa ký lưu trong kho bí mật, xoay có giai đoạn chồng khóa công khai; edge không nhận khóa riêng. TLS/mTLS bảo vệtruyền, mã hóa và phân quyền bảo vệlưu trữ; không log raw QR hoặc mật khẩu. employee_ref giảdanh vẫn là dữliệu cá nhân khi có thểliên kết ngược. Quyền truy cập, mục đích xửlý và retention được quản lý bằng chính sách dữliệu, kết hợp quy trình kiểm soát của TMC. 

### **4.3.7 Bước 7: định nghĩa các chếđộlỗi** 

**Bảng 25:** _Hành vi vận hành khi có lỗi_ 

|**Sựcố**|**Hành vi tựđộng**|**Khôi phục / giới hạn**|
|---|---|---|
|Mất WAN|Tiếp tục tại edge nếu quyền, khóa và<br>policy còn trong cửa sổtin cậy; outbox<br>tích lũy.|Hết 30 phút: ngừng cấp quyền tự<br>động, cảnh báo và quy trình bảo vệ;<br>không tiếp tục vô hạn.|
|Timeout cổng|Giữintent và outcome Unknown, phản<br>hồi không thành công giả.|Tra cứu cùng command_id nếu API có<br>hỗtrợ; không retry mù hoặc tựtính<br>công.|
|Edge active chết|Standby chỉđược nhận vai trò sau<br>lease/fencing và kiểm tra dữliệu.|Nếu không có sync copy/quorum cần<br>thiết thì dừng tựđộng; ca kiểm thử<br>phải đo RTO/RPO.|
|Đầy đĩa / lỗi ghi|Không gửi lệnh mởcổng tựđộng khi<br>không lưu được intent.|Cảnh báo dung lượng sớm; bảo vệxử<br>lý có nhật ký dựphòng; không gọi đây<br>là vận hành bình thường không mất dữ<br>liệu.|
|Central / broker lỗi|Edge vẫn xửlý trong giới hạn; dữliệu<br>và outbox chưa ack được giữ.|Replay có khửtrùng; read model hiển<br>thịđộtrễ; không xóa backlog vì gửi<br>mạng thành công.|
|HR lỗi hoặc nhận<br>một phần|Giữbatch và receipt, cảnh báo ngay,<br>backoff có giới hạn.|Mục tiêu đối soát 08:00; leo thang<br>trước 12:00. Không thểbảo đảm hạn<br>nếu HR ngừng vượt deadline.|



31 

4 Structure: lựa chọn và xây dựng kiến trúc 



<!-- Start of picture text -->
pa AI HO! IA THAN 4 MIN<br>@53 TRUONG DAI HOC BACH KHOA<br><!-- End of picture text -->

|**Sựcố**|**Hành vi tựđộng**|**Khôi phục / giới hạn**|
|---|---|---|
|Mất điện / an toàn|Khôi phục theo UPS và runbook;|Thoát hiểm do phần cứng/quy trình an|
|con người|không tựmởcổng do lỗi phần mềm.|toàn độc lập; chính sách an toàn cần|
|||đơn vịquản lý cổng xác nhận.|



Nếu central không truy cập được, chức năng C17 trên web trung tâm không được coi là vẫn hoạt động. Quy trình bảo vệdựphòng phải được TMC duyệt riêng, có cách xác minh danh tính và nhật ký tại chỗ(chẳng hạn biểu mẫu giấy được kiểm soát). Khi hệthống phục hồi, nhân sựnhập bản ghi bổsung có thẩm quyền; không tạo ngược một sựkiện quét QR chưa từng xảy ra. Quy trình này không thay thếcơ chếthoát hiểm độc lập. 

### **4.3.8 Bước 8: lịch xuất, giám sát và kiểm chứng** 

Lịch vận hành: đối soát sựkiện hằng ngày, kiểm tra ngoại lệtừngày 25; tạo snapshot lúc 00:30 ngày 01, xuất 01:00–04:00 và đối soát 04:00–06:00. Mục tiêu nội bộhoàn tất trước 08:00 dành đệm 4 giờcho hạn bắt buộc 12:00. Không chờđến 08:00 mới cảnh báo lỗi. 

Trước chốt phải kiểm tra watermark của các trạm và edge. Nếu nguồn còn thiếu, snapshot đánh dấu chưa đầy đủvà có người xửlý; không xuất lô rồi tuyên bốhoàn tất vì đã nhận HTTP 200. Điều chỉnh sau chốt tạo phiên bản hoặc lô bổsung theo hợp đồng HR; không ghi đè dữliệu đã xác nhận. Theo dõi max/p95/p99, sốvi phạm 2 giây, backlog theo tuổi, lag thu hồi, lỗi cổng Unknown, độtrễheartbeat và trạng thái batch. Việc kiểm thửtải, lỗi, restore và hợp đồng được lập kếhoạch ởChương 8, gắn với các tiêu chí chất lượng tương ứng. 

32 

5 Tổng hợp các góc nhìn kiến trúc 4+1 



# **Chương 5 – Tổng hợp các góc nhìn kiến trúc 4+1** 

Mô hình 4+1 dùng bốn góc nhìn logical, process, development, physical và các kịch bản (+1) đểkiểm tra cùng một thiết kế. C4 được dùng ởmức ngữcảnh/container/thành phần khi hữu ích; không đồng nhất bốn mức C4 với bốn góc nhìn 4+1. Sơ đồphysical được trình bày ở Hình 3; chương này bổsung hành vi, mô hình nghiệp vụvà phụthuộc mã nguồn. 

**Bảng 26:** _Góc nhìn, đối tượng đọc và bằng chứng_ 

|**Góc nhìn**|**Câu hỏi cần trảlời**|**Bằng chứng trong báo cáo**|
|---|---|---|
|Logical|Hệthống có trách nhiệm, đối tượng<br>và quan hệnào?|Hình ngữcảnh/container ởChương 4; sơ đồ<br>thành phần và mô hình dữliệu trong mục<br>5.1; Bảng thành phần C01–C26.|
|Process|Các tiến trình phối hợp, lưu bền và<br>phục hồi thếnào?|Trình tựquét, projection trạng thái, đồng bộ<br>và xuất HR ởmục 5.2.|
|Development|Mã nguồn được chia và được phép<br>phụthuộc thếnào?|Sơ đồphụthuộc, cấu trúc thư mục và phép<br>kiểm ởmục 5.3.|
|Physical|Đơn vịphần mềm chạy ởđâu, chịu<br>được miền lỗi nào?|Topology và Bảng đơn vịtriển khai ở<br>Chương 4; ma trận phân bổởmục 5.4.|
|Scenarios (+1)|Các góc nhìn có giải quyết cùng<br>một kịch bản không?|Ma trận kịch bản SC-01–SC-08 ởmục 5.5,<br>nối FR/NFR với thành phần và dữliệu.|



## **5.1 Logical view: thành phần và mô hình nghiệp vụ** 

### **5.1.1 Thành phần đường quét và các cổng phụthuộc** 

ScanHandler là điều phối ứng dụng, không chứa mã SQL hoặc HTTP controller. Nó dùng QR verifier, policy và các port đểnhận thời gian, ghi transaction và tác động cổng. Ghi sựkiện và intent/outbox phải có một Unit of Work; việc tách port nhỏkhông cho phép ghi chúng bằng các transaction rời nhau. Các adapter bên ngoài hiện thực hợp đồng do application/domain sở hữu. 

33 

5 Tổng hợp các góc nhìn kiến trúc 4+1 





<!-- Start of picture text -->
Kiosk adapter<br>HTTPS / danh<br>tính thiết bị<br>ScanHandler (C05)<br>Điều phối use case<br>QR Verifier C06 Policy Engine C07<br>TokenVerifier AccessPolicy /<br>/ ClockPort SnapshotReader<br>snapshot<br>EventUnitOfWorkPort C10 / C11<br>TurnstileGatewayPort<br>C08: event + in- Sync policy /<br>C09: command / outcome<br>tent + outbox forward event<br>hiện thực hiện thực<br>PostgreSQL<br>HTTP adapter Central adapters<br>adapter<br>/ Simulator mTLS / batch<br>kho cục bộ<br>API cổng quay / revision<br>/ transaction<br><!-- End of picture text -->

**Hình 4:** _Thành phần lõi tại edge theo ports và adapters_ 

34 

5 Tổng hợp các góc nhìn kiến trúc 4+1 



Mũi tên từadapter lên port là phụthuộc thiết kế, không phải hướng truyền dữliệu mạng. C10 cung cấp snapshot cho policy; C11 đọc outbox đã commit và gửi tới central độc lập với ScanHandler. Hai worker này không được phép gửi lệnh cổng thay C09. C09 có TurnstileSimulator đểkiểm tra các kết quảConfirmed, Rejected, Unknown với cùng hợp đồng. 

### **5.1.2 Mô hình miền và dữliệu quan hệ** 



<!-- Start of picture text -->
Employee Credential GateStation<br>1 đến nhiều<br>employee_ref; credential_id; station_id;<br>PII tại ICS revision factory; hướng<br>0..1 tham chiếu trạm phát sinh<br>AccessEvent<br>scan_id duy nhất<br>employee_ref có thểnull<br>1 đến nhiều chiếu / tổng hợp<br>StatusHistory<br>Outbox / Inbox AttendanceDay<br>/ GateIntent<br>event_id; projection /<br>command_id;<br>schema version Adjustment<br>version<br>PeriodSnapshot<br>AuditRecord<br>/ HrBatch<br>actor; action;<br>period; phiên bản<br>checkpoint<br>receipt<br><!-- End of picture text -->

**Hình 5:** _Mô hình khái niệm dữliệu và quan hệchính_ 

Các quan hệxuyên schema là tham chiếu logic qua hợp đồng; sơ đồkhông yêu cầu foreign key hoặc join trực tiếp giữa mọi dịch vụ. Sựkiện nhận quét, quyết định và kết quảđiều khiển được giữlàm chứng cứ; AttendanceDay là dữliệu chiếu có thểtái tạo. Chính sách nghiệp vụsửdụng kết quảmởcổng đã xác nhận và điều chỉnh được duyệt đểtạo ứng viên công. Không suy luận nhân viên đã đi qua cơ khí chỉtừphản hồi API nếu không có tín hiệu cảm biến. Khi thiết bịcung cấp passage_id/cảm biến, bổsung sựkiện xác nhận đi qua mà không sửa lịch sử gốc. 

- **5.2 Process view: đồng thời, giao tiếp và phục hồi** 

- **5.2.1 Trình tựquét QR trong trường hợp thành công** 

35 

5 Tổng hợp các góc nhìn kiến trúc 4+1 



<!-- Start of picture text -->
xr DAI HOC QUOC GIA THANH PHO<br>G3 TRUONG BAI HOC BACH HO CHI KHOA MINH<br><!-- End of picture text -->



<!-- Start of picture text -->
Kiosk Edge Event Store Turnstile<br>1. scan_id + QR + station<br>a a<br>2. verifier + policy + chống trùng<br>3. event + intent + outbox<br>rr<br>4. commit bền vững<br>5. mởcổng với command_id<br>et<br>6. kết quảxác nhận / timeout<br>7. append outcome + outbox<br>nr<br>commit<br>8. trảkết quả; không quá 2 giây<br>Ngoài đường găng: C11 gửi bù đến C12; ack sau commit;<br>C13/RIS cập nhật read model, ADS nhận audit qua sựkiện.<br><!-- End of picture text -->

**Hình 6:** _Trình tựquét và thứtựcommit trước tác động thiết bị_ 

36 

5 Tổng hợp các góc nhìn kiến trúc 4+1 



Lượt bịtừchối vẫn ghi quyết định và lý do nhưng không tạo lệnh mởcổng. Nếu ghi intent thất bại, không gọi thiết bị. Nếu node chết sau bước 4, recovery đọc intent và xác minh trạng thái trước khi tiếp tục. Nếu cổng đã mởnhưng ghi outcome lỗi, intent vẫn còn đểđối soát; không tạo một command mới. Cùng scan_id được khóa/unique trong transaction; hai request đồng thời cho cùng ID nhận cùng một trạng thái, không cùng phát hai lệnh. 

### **5.2.2 Projection vòng đời và trạng thái chưa xác định** 



<!-- Start of picture text -->
RECEIVED<br>không hợp lệ<br>AUTHORIZED<br>DENIED<br>INTENT<br>không gọi cổng<br>COMMITTED<br>COMMAND<br>SENT<br>từchối rõ<br>đã xác nhận mở mất phản hồi<br>GATE REJECTED<br>GATE OUTCOME / FAILED<br>CONFIRMED UNKNOWN có xác nhận<br>thất bại<br>xác nhận<br>xác nhận<br>RECONCILIATION<br>Tra cứu theo command_id hoặc xửlý có thẩm quyền;<br>append kết quả, không ghi đè lịch sử.<br><!-- End of picture text -->

**Hình 7:** _Projection trạng thái lượt quét từlịch sửchỉthêm_ 

Các trạng thái là projection dựng từlịch sử, không phải sửa trực tiếp sựkiện gốc. Timeout có thểxảy ra trước hoặc sau khi controller thực hiện, nên không gán Failed chỉtừtimeout. Nếu API chỉxác nhận nhận lệnh, giữPending/Unknown đến khi có xác nhận kết quả; không đánh đồng HTTP 200 với đã mởcơ khí. Kết quảđối soát sau đó gắn lại scan_id/command_id cũ và không đếm hai lần trong tổng hợp. 

### **5.2.3 Đồng bộvà xửlý đồng thời** 

Mỗi edge duy trì một writer cho kho/luồng điều khiển, nhưng có thểxửlý các scan độc lập đồng thời theo cổng. Ràng buộc unique cho scan_id và command_id, transaction kiểm tra 

37 

5 Tổng hợp các góc nhìn kiến trúc 4+1 



nonce/trạng thái bảo vệkhi hai request đến cùng lúc. Anti-passback theo người/nhà máy cần khóa hoặc cập nhật có điều kiện; khi mất WAN phạm vi chống vào lại được giới hạn tại từng nhà máy. Không giữtransaction DB trong suốt lời gọi mạng: intent commit trước gọi, outcome được ghi bằng transaction tiếp theo. 

C11 gửi từng lô lịch sửcó cursor; C12 commit sựkiện và inbox/outbox trước ack. Consumer central xửlý lại an toàn; đến sai thứtựthì giữphiên bản hoặc chờphần thiếu, không để trạng thái cũ ghi đè mới. Retry có backoff và jitter, giới hạn tốc độđểkhi mạng lại không gây tắc ingestion. Mỗi read model có watermark và có thểrebuild từsựkiện gốc cộng adjustment. 

### **5.2.4 Tiến trình xuất và đối soát tháng** 



<!-- Start of picture text -->
1. Kiểm tra watermark<br>2. Snapshot kỳcó phiên bản<br>và ngoại lệ<br>00:30 ngày 01<br>Nguồn thiếu: chưa hoàn tất<br>4. Nhận receipt và đối soát 3. Tạo batch_id + checksum<br>Không chỉkiểm HTTP status Gửi qua HR adapter<br>chưa khớp<br>5. Sai / thiếu / Unknown<br>6. Đủvà được xác nhận<br>Tra cứu, gửi bù<br>Mục tiêu 08:00; hạn 12:00<br>an toàn, cảnh báo<br>khớp<br><!-- End of picture text -->

**Hình 8:** _Tiến trình chốt snapshot, xuất và đối soát với HR_ 

Receipt ghi rõ những bản ghi được nhận, từchối và chưa biết. Sốlượng bằng nhau chưa chứng minh cùng dữliệu: dùng khóa nghiệp vụ, phiên bản và checksum/tập ID theo hợp đồng. Snapshot nhận thêm sựkiện muộn hoặc điều chỉnh phải tạo phiên bản/lô bổsung; không sửa lại chứng cứlô đã gửi. Cảnh báo nêu cụthểnguồn thiếu hoặc lỗi HR đểnhân sựxửlý; cam kết deadline phụthuộc khảnăng cung cấp API của bên nhận. 

## **5.3 Development view: tổchức mã và quy tắc phụthuộc** 

38 

5 Tổng hợp các góc nhìn kiến trúc 4+1 





<!-- Start of picture text -->
Domain<br>quy tắc / value objects<br>phụthuộc<br>Application + Ports<br>use case / hợp đồng<br>Turnstile /<br>HTTP / UI adapter Persistence adapter<br>HR adapter<br><!-- End of picture text -->



<!-- Start of picture text -->
Chỉcomposition root biết concrete adapter.<br>Các dịch vụkhác trao đổi API/sựkiện,<br>không import application của nhau.<br><!-- End of picture text -->

**Hình 9:** _Phụthuộc mã nguồn hướng vào port và nghiệp vụ_ 

**Bảng 27:** _Cấu trúc mã nguồn và phép kiểm kiến trúc_ 

|**Vùng mã**|**Nội dung**|**Quy tắc kiểm**|
|---|---|---|
|apps/mobile, web, kiosk|Các giao diện và adapter đầu vào.|Không chứa quy tắc chấm công<br>dùng chung hoặc kết nối SQL trực<br>tiếp.|
|services/identity, access,<br>station, reporting, admin|Mỗi dịch vụcó domain, application,<br>ports, adapters và composition root.|Domain không import<br>framework/SQL; services không<br>import application hoặc ORM của<br>miền khác.|
|services/access/edge và<br>central|Đóng gói phần ghi/điều khiển và<br>phần ingestion/projection riêng.|Core chung chỉchứa quy<br>tắc/contract ổn định; không tạo<br>shared mutable state giữa hai<br>deployment.|
|contracts/events và<br>adapters|Schema sựkiện có phiên bản,<br>turnstile HTTP/simulator, HR<br>export.|Kiểm thửtương thích; adapter<br>phải chạy cùng bộcontract test, kể<br>cảUnknown và timeout.|
|deploy, tests, runbooks|Manifest, migrations, cấu hình mẫu,<br>kịch bản lỗi và phục hồi.|Không đưa khóa thật vào repo;<br>thửmigration/restore và kiểm tra<br>phụthuộc trong pipeline.|



39 

5 Tổng hợp các góc nhìn kiến trúc 4+1 



Migration do miền sởhữu; phiên bản hợp đồng phải tương thích trong lúc rolling upgrade. Thư viện chung chỉchứa ID, hợp đồng và tiện ích ổn định; không dùng “shared” đểchia sẻtoàn bộentity/ORM, làm mất ranh giới dịch vụ. 

## **5.4 Physical view: ánh xạphần mềm lên hạtầng** 

**Bảng 28:** _Ánh xạlogical sang physical và đường dữliệu_ 

|**Miền / thành phần**|**Nút và dữliệu**|**Liên lạc / lý do**|
|---|---|---|
|C05–C11|Edge của từng nhà máy, local DB<br>primary/sync standby và witness điều<br>phối.|LAN tới kiosk/controller; không<br>cần central trên đường găng;<br>HTTPS mTLS gửi nền.|
|C01–C04, C12–C26|Ứng dụng central; schema riêng trên<br>cụm DB; worker báo cáo riêng.|Gateway cho UI; broker cho sự<br>kiện; API tới HR; quota đểbáo cáo<br>không lấn ingestion.|
|Audit / checkpoint /<br>backup|Kho phân quyền và bản<br>sao/checkpoint độc lập; DR ởLong<br>An.|Phục hồi và phát hiện can thiệp;<br>bản sao cùng site không đủcho<br>thảm họa site.|
|Kiosk / điện thoại /<br>controller|Thiết bịhiện trường và điện thoại cá<br>nhân.|Điện thoại hiển thịQR; kiosk là<br>client xác thực; controller thực<br>hiện cơ khí. Không đặt khóa ký<br>máy chủởđiện thoại.|



Topology ởHình 3 là physical view chính; bảng trên làm rõ ánh xạtrách nhiệm. Đưa một thành phần vào host khác không tựtạo ranh giới nghiệp vụ; ngược lại, hai schema trên cùng DB vẫn có quyền sởhữu khác nhau. Các kiểm tra HA phải gây lỗi đúng miền (process, host, mạng, site), không chỉrestart container rồi suy ra chịu được mất site. 

## **5.5 Scenarios (+1): kiểm chứng xuyên góc nhìn** 

**Bảng 29:** _Kịch bản liên kết các góc nhìn và bằng chứng cần thu_ 

|**Mã / truy vết**|**Kịch bản**|**Luồng / trách nhiệm**|**Bằng chứng cần có**|
|---|---|---|---|
|SC-01; US-02;|QR hợp lệtrong|C05–C09 tại edge; event/intent|Tập scan/command|
|FR-A1–A4;|giờgiao ca.|commit trước lệnh; outcome xác|không trùng; trace và|
|NFR-P1, R1||nhận, phản hồi trong budget;<br>C11/C12 đồng bộ.|độtrễtừng bước.|



40 

5 Tổng hợp các góc nhìn kiến trúc 4+1 



|**Mã / truy vết**|**Kịch bản**|**Luồng / trách nhiệm**|**Bằng chứng cần có**|
|---|---|---|---|
|SC-02; US-02;<br>FR-A6; NFR-A1|WAN mất và<br>quyền offline dần<br>hết hạn.|C10 kiểm revision/expiry;<br>C08/C11 lưu bù. Hết cửa sổtin<br>cậy thì ngừng cấp quyền tựđộng,<br>bảo vệxửlý.|Không mất ID đã<br>commit; log chuyển<br>chếđộ, thửcả<br>trước/sau hạn 30 phút.|
|SC-03; US-02, 12;<br>NFR-I1|Cổng đã thực<br>hiện nhưng phản<br>hồi bịmất.|C09 giữcommand_id; outcome<br>Unknown; tra cứu/đối soát, không<br>tựmởlại.|Simulator áp dụng một<br>lệnh nhưng cắt phản<br>hồi; tổng lần tác động<br>không tăng sai.|
|SC-04; US-08;<br>FR-U3; NFR-S1|Nhân viên bịthu<br>hồi quyền.|ICS đổi revision, C10 nhận delta,<br>C07 từchối. Offline áp dụng hạn<br>tin cậy và cảnh báo rủi ro quyền<br>cũ.|Đo lag online mục tiêu<br>60 giây; không tuyên<br>bốcập nhật tức thì khi<br>mất WAN.|
|SC-05; US-11;<br>FR-R3, R4|HR nhận một<br>phần lô hoặc mất<br>ack.|RIS giữsnapshot/batch; C21/C22<br>truy vấn receipt và chỉgửi bù theo<br>hợp đồng.|Tập khóa nghiệp vụ<br>được nhận khớp<br>snapshot; không chốt<br>thành công khi nguồn<br>thiếu.|
|SC-06; US-15, 16;<br>NFR-S1, PR1|Người dùng đọc<br>dữliệu ngoài<br>scope hoặc sửa<br>audit.|C23 kiểm quyền phía dịch vụ;<br>C24 log hành động; quyền DB và<br>checkpoint chặn/phát hiện can<br>thiệp.|Kiểm thửâm theo ma<br>trận RBAC; quét<br>QR/log không lộdữ<br>liệu định danh trực<br>tiếp.|
|SC-07; US-17;<br>NFR-R1, A1|Edge active chết<br>ngay sau commit<br>intent.|Standby được promote sau<br>fencing và đồng bộ; recovery<br>dùng intent cũ, không sinh<br>command mới.|Mục tiêu RTO và RPO<br>một-node được đo;<br>nếu thiếu quorum/sync<br>copy phải dừng an<br>toàn.|
|SC-08; US-14;<br>NFR-M1|Thêm nhà<br>máy/cổng hoặc<br>đổi controller.|Thêm cấu hình/edge và adapter<br>tương thích; policy và use case<br>không sửa theo hãng thiết bị.|Contract test và test<br>phụthuộc; cần bổ<br>sung hạtầng, không<br>hứa thêm nhà máy mà<br>không triển khai gì.|



Các kịch bản liên kết các góc nhìn kiến trúc và kiểm tra tính đầy đủcủa trách nhiệm xử lý. Chương 8 tổng hợp tiêu chí kiểm chứng và biện pháp quản lý rủi ro cho các luồng nghiệp vụ này. 

41 

6 Architecture Decisions 



# **Chương 6 – Architecture Decisions** 

Quyết định kiến trúc ghi lại lựa chọn có tác động lớn, bối cảnh và hệquả. Các hồsơ dưới đây xác định các lựa chọn kiến trúc của hệthống. Khi bằng chứng thực nghiệm hoặc yêu cầu thay đổi, cập nhật ADR và các phần truy vết liên quan, không sửa riêng sơ đồ. 

## **6.1 Quy tắc kiến trúc (Architecture rules)** 

Quy tắc kiến trúc là ràng buộc xuyên suốt quá trình xây dựng và vận hành hệthống. Mỗi quy tắc có cách kiểm; nếu cần ngoại lệphải ghi quyết định và phạm vi, không âm thầm bỏqua đểlàm đẹp sốđo. 

**Bảng 30:** _Quy tắc triển khai và phép kiểm_ 

|**Mã**|**Quy tắc**|**Truy vết / kiểm tra**|
|---|---|---|
|AR-01|Đường quét không chờHR, báo cáo hoặc DB<br>central.|ADR-03; kiểm thửmất WAN và<br>kiểm tra trace dependency.|
|AR-02|Lưu bền sựkiện, intent và outbox trước khi gửi lệnh<br>mởcổng.|ADR-05; thửlỗi tại điểm trước/sau<br>commit, xác nhận thứtựside<br>effect.|
|AR-03|Giữscan_id/command_id/event_id qua truyền lại;<br>không retry lệnh cổng chưa rõ kết quảkhi thiếu bảo<br>đảm chống lặp.|ADR-07/10; test mất ack và cổng<br>đã tác động.|
|AR-04|Dịch vụchỉtruy cập schema sởhữu, trao đổi qua<br>API/sựkiện; domain không import hạtầng.|ADR-02/08; phân quyền DB và<br>kiểm tra import trong pipeline.|
|AR-05|Dữliệu nghiệp vụvà outbox/inbox liên quan<br>commit cùng transaction.|ADR-06; test crash giữa ghi dữ<br>liệu, phát sựkiện, ack.|
|AR-06|QR không chứa định danh trực tiếp; khóa ký không<br>ởkiosk/điện thoại; mã giảdanh vẫn được bảo vệ.|ADR-04/13; kiểm tra payload, log<br>và quyền kho khóa.|
|AR-07|Mọi endpoint bảo vệtựkiểm tra vai trò và scope<br>phía máy chủ; hành động nhạy cảm có audit.|ADR-11/12; ma trận quyền và<br>kiểm thửtruy cập ngoài phạm vi.|
|AR-08|Sựkiện gốc và audit chỉthêm; sửa công bằng<br>adjustment có thẩm quyền; snapshot xuất có phiên<br>bản.|ADR-05/09/12; kiểm tra quyền ghi<br>và lịch sửtrước/sau.|
|AR-09|Một writer có lease hợp lệ; failover phải fencing;<br>không tựhạchuẩn commit đồng bộ.|ADR-03/08/15; test partition, stale<br>leader, mất standby.|
|AR-10|Kết nối được bảo vệbằng TLS; edge–central xác<br>thực mTLS; bí mật không nằm trong source.|ADR-13; test chứng chỉsai, hết<br>hạn và quét bí mật.|



42 

6 Architecture Decisions 



|**Mã**|**Quy tắc**|**Truy vết / kiểm tra**|
|---|---|---|
|AR-11|Cấu hình nhà máy, trạm, policy và retention có|ADR-01/15; thửrevision cũ, cấu|
||phiên bản, quyền và audit.|hình lỗi và thao tác vượt quyền.|
|AR-12|Không đánh đồng scan hợp lệ, command accepted,|ADR-05/10; kiểm hợp đồng trạng|
||gate opened và người đã đi qua.|thái và điều kiện tổng hợp công.|



## **6.2 Hồsơ quyết định kiến trúc (ADR)** 

Mỗi hồsơ có bối cảnh, lựa chọn, phương án khác, hệquảvà cách xác minh. Điều kiện áp dụng và phương pháp kiểm chứng được gắn trực tiếp với từng quyết định. 

### **6.2.1 ADR-01 – Kiến trúc dịch vụtheo miền kết hợp edge và sựkiện** 

**Bối cảnh.** Khoảng 1.400 nhân viên tại hai nhà máy; luồng cổng cần nhanh, báo cáo và xuất HR có thểxửlý nền. 

**Quyết định.** Chọn năm dịch vụICS, AAS, GSS, RIS, ADS; AAS-Edge tại nhà máy, AASCentral hợp nhất; giao tiếp nền qua outbox/sựkiện. Schema có chủsởhữu rõ. 

**Phương án khác.** Modular monolith central + edge được giữlà phương án đơn giản hơn; microservices nhỏchưa phù hợp chi phí vận hành. 

**Hệquảvà đánh đổi.** Cô lập ingestion, báo cáo và quản trị; đổi lại tăng hợp đồng và quan sát. Shared DB vẫn là miền lỗi chung, không đạt cô lập tuyệt đối. 

**Truy vết và kiểm chứng.** FR-A1–A6, R1–R4; NFR-P1, A1, M1. Kiểm tra điểm số, độnhạy và thửnghiệm hai đường quét/báo cáo đồng thời. 

### **6.2.2 ADR-02 – Ports và adapters bên trong mỗi miền** 

**Bối cảnh.** Controller, HR, database hoặc framework có thểđổi; nghiệp vụkhông nên bịviết lại theo nhà cung cấp. 

**Quyết định.** Application sởhữu các port hẹp; domain chứa quy tắc; adapter HTTP, PostgreSQL, đồng hồvà simulator được lắp ởcomposition root. 

**Phương án khác.** Không gọi API hoặc SQL trực tiếp trong policy/use case. Kiến trúc nhiều lớp đơn thuần chỉđạt mục tiêu nếu vẫn giữhướng phụthuộc vào trong. 

**Hệquảvà đánh đổi.** Tăng khảnăng thay thếvà kiểm thử; thêm abstraction cần thiết, tránh tạo interface cho từng lớp không có điểm thay đổi. 

**Truy vết và kiểm chứng.** NFR-M1; AR-04. Kiểm tra import và chạy cùng contract test cho adapter thật/giảlập. 

43 

6 Architecture Decisions 



### **6.2.3 ADR-03 – Đưa xửlý cổng và kho sựkiện vềnhà máy** 

**Bối cảnh.** WAN hoặc central có thểgián đoạn; thời gian phản hồi cổng không được phụthuộc tác vụởsite khác. 

**Quyết định.** C05–C11 chạy edge; hai host active/standby, local DB đồng bộ, witness/lease/fencing. Chỉdùng snapshot quyền và cấu hình còn hiệu lực. 

**Phương án khác.** Central-only đơn giản nhưng phụthuộc WAN; full-stack độc lập từng nhà máy tăng công hợp nhất. Edge vẫn tương thích phương án modular monolith central. 

**Hệquảvà đánh đổi.** Tăng khảnăng xửlý cục bộnhưng thêm vận hành, dữliệu quyền có độ trễ. Khi mất nơi ghi bền hoặc quyền hết hạn, không tiếp tục tựđộng. 

**Truy vết và kiểm chứng.** FR-A6; NFR-P1, R1, A1; A-05/10. Thửmất WAN, mất leader, hết hạn policy và mất standby. 

### **6.2.4 ADR-04 – QR do máy chủký và có thời hạn** 

**Bối cảnh.** QR có thểbịchụp/chia sẻ; edge cần xác minh mà không hỏi central mỗi lần. **Quyết định.** Ứng dụng/web lấy token ký sốngắn hạn, dựkiến 60 giây; payload có issuer, audience, employee_ref, nonce, key_id và thời hạn. Email ưu tiên gửi liên kết lấy QR mới. Edge giữkhóa công khai, không giữkhóa ký. 

**Phương án khác.** Không chọn QR tĩnh chứa mã nhân viên làm cơ chếchính. Vé theo ngày qua email là lựa chọn rủi ro cao hơn, chỉđưa vào khi có phê duyệt riêng. 

**Hệquảvà đánh đổi.** Giảm lộPII và sửa payload; không ngăn tuyệt đối đưa điện thoại hoặc QR mới cho người khác. Cần chống phát lại và đồng bộkhóa/đồng hồ. 

**Truy vết và kiểm chứng.** FR-U2/U3, A7; NFR-PR1/S2. Test token sửa nội dung, hết hạn, sai audience, khóa cũ và nonce dùng lại. 

### **6.2.5 ADR-05 – Commit chứng cứtrước tác động thiết bị** 

**Bối cảnh.** Mởcổng trước khi lưu có thểđểlại một tác động không có bản ghi; lỗi sau lệnh cũng có thểlàm kết quảkhông rõ. 

**Quyết định.** Commit event, quyết định, intent và outbox trước khi gửi lệnh; append outcome sau phản hồi. GiữUnknown khi không biết, không tựcoi thành công hoặc thất bại. Điều kiện tính công phải được HR xác nhận. 

**Phương án khác.** Không chọn mởrồi ghi sau; không dùng trạng thái QR hợp lệlàm bằng chứng người đã qua cổng. Cảm biến nếu có sẽphát sựkiện riêng. 

**Hệquảvà đánh đổi.** Tăng độtrễghi nhưng có chứng cứphục hồi. Intent không đủkết luận mở cổng thành công; cần đối soát theo command_id. 

**Truy vết và kiểm chứng.** FR-A2/A3; NFR-R1/P1. Crash trước commit không được có lệnh; 

44 

6 Architecture Decisions 



crash sau lệnh phải còn intent và đường recovery. 

### **6.2.6 ADR-06 – Transactional outbox và inbox khửtrùng** 

**Bối cảnh.** Dual write DB và broker riêng rẽcó thểthiếu sựkiện; nhận lặp có thểnhân đôi tổng hợp. 

**Quyết định.** Ghi outbox cùng transaction nghiệp vụ. Relay giao ít nhất một lần; consumer ghi inbox cùng cập nhật nghiệp vụrồi ack. Mã event_id và phiên bản bảo vệkhửtrùng/thứtự. **Phương án khác.** Không publish một lần rồi bỏqua lỗi; chưa chọn transaction phân tán hai pha cho các hệthống ngoài. 

**Hệquảvà đánh đổi.** Có thểreplay sau sựcố, đổi lại nhất quán cuối cùng và vận hành backlog/dead-letter. Không bảo đảm exactly-once trên mạng hay controller chỉbằng outbox. 

**Truy vết và kiểm chứng.** FR-A6/R4; NFR-R1/R2. Test commit nhưng chưa publish, publish nhưng mất ack và consumer crash trước/sau commit. 

### **6.2.7 ADR-07 – Định danh ổn định cho lượt quét và lô** 

**Bối cảnh.** Kiosk, relay và HR adapter có thểgửi lại do mất phản hồi; một ID dùng cho payload khác sẽtạo sai lệch. 

**Quyết định.** scan_id giữnguyên qua retry; command_id gắn intent; mỗi envelope có event_id; batch_id gắn snapshot. Unique key và fingerprint từchối cùng ID khác nội dung. Nonce QR là khóa bảo vệphát lại riêng. 

**Phương án khác.** Không khửtrùng chỉtheo timestamp/người dùng; không cấp ID mới cho mỗi lần truyền lại. Không gộp hai lượt quét thật khác nhau. 

**Hệquảvà đánh đổi.** Tạo được tác động nghiệp vụduy nhất trong vùng kiểm soát; phải giữ khóa đủlâu và đồng bộversion. Controller/HR cần hợp đồng riêng cho chống lặp. 

**Truy vết và kiểm chứng.** FR-A4/A7/R4; NFR-R2. Test gửi song song cùng ID, khác payload và retry sau restart. 

### **6.2.8 ADR-08 – PostgreSQL theo schema, HA và RPO theo miền lỗi** 

**Bối cảnh.** Dữliệu cần giao dịch, unique key và phục hồi; lỗi node khác mất toàn site. 

**Quyết định.** Dùng schema/tài khoản riêng trên PostgreSQL central; primary/sync standby tại site, DR bất đồng bộởsite khác. Edge commit đồng bộvà chỉmột writer có lease; failover fencing trước promote. Broker dùng quorum ba node. 

**Phương án khác.** Không xem replica bất đồng bộlà RPO 0. Không dùng cụm broker hai node đểtuyên bốchịu lỗi một node; chưa tách DB vật lý cho từng dịch vụ. 

**Hệquảvà đánh đổi.** RPO 0 chỉlà mục tiêu cho commit đồng bộkhi lỗi một node. Mất standby có thểdừng ghi; DR có cửa sổmất dữliệu, cần đo và phục hồi từedge nếu còn. 

45 

6 Architecture Decisions 



**Truy vết và kiểm chứng.** NFR-R1/A1/D1; A-05. Thửcrash/promotion, phân vùng mạng, đầy đĩa, restore và đối chiếu tập sựkiện. 

### **6.2.9 ADR-09 – Xuất HR theo snapshot và lô có đối soát** 

**Bối cảnh.** Hạn bắt buộc 12:00 ngày 01; API nhận lô, giới hạn dữliệu và cách chống trùng còn cần xác nhận. 

**Quyết định.** RIS tạo snapshot có version và batch_id, lưu receipt và đối soát theo khóa/checksum. Lịch chốt 00:30, xuất 01:00–04:00, đối soát trước 08:00; cảnh báo sớm khi lỗi. Điều chỉnh tạo phiên bản/lô bổsung. 

**Phương án khác.** Không dồn một lô sát 12:00; không ghi trực tiếp DB HR hoặc đánh dấu hoàn tất từHTTP 200. Gửi gia tăng hằng ngày chỉkhi HR hỗtrợ. 

**Hệquảvà đánh đổi.** Có bằng chứng nguồn và nhận, cần thống nhất schema, upsert và late adjustment. Khi HR gián đoạn kéo dài, kích hoạt cảnh báo và quy trình đối soát dựphòng. 

**Truy vết và kiểm chứng.** FR-R3/R4; NFR-I1. Test nhận một phần, mất receipt, gửi bù, nguồn edge thiếu và sửa sau snapshot. 

### **6.2.10 ADR-10 – Cô lập API cổng và xửlý timeout có nghĩa** 

**Bối cảnh.** Cổng có thểthực hiện lệnh rồi mất phản hồi; retry mù tạo rủi ro mởthêm. 

**Quyết định.** Gọi qua TurnstileGatewayPort; timeout dựkiến 700 ms trong budget chung. Kết quảkiểu Confirmed/Rejected/Unknown; query trạng thái là khảnăng riêng. Chỉthửlại nếu controller có idempotency xác nhận và còn thời gian. 

**Phương án khác.** Không coi mọi timeout là Failed hoặc retry cốđịnh mọi lỗi. Không đểsimulator luôn thành công. 

**Hệquảvà đánh đổi.** Phụthuộc thiết bịđược khoanh vùng; nhiều trường hợp cần bảo vệđối soát. Nếu API không xác nhận kết quảtrong budget, NFR-P1 chưa có bằng chứng đáp ứng. **Truy vết và kiểm chứng.** FR-A2; NFR-I1/P1; A-03. Contract test success, reject, accepted-only, applied-but-lost-response và circuit breaker. 

### **6.2.11 ADR-11 – RBAC kết hợp scope tại dịch vụ** 

**Bối cảnh.** Cùng vai trò có thểchỉđược nhìn một nhà máy/đội; ẩn nút UI không ngăn gọi API. **Quyết định.** Kiểm tra danh tính, hành động và scope ởgateway và endpoint dịch vụ; least privilege. Token/snapshot có thời hạn và version; quản trịkỹthuật không tựcó quyền sửa công. **Phương án khác.** Không chỉkiểm quyền ởgiao diện hoặc tin tham sốemployee_ref/factory_id do client gửi. Quyền người lập/người duyệt được tách khi chính sách yêu cầu. 

**Hệquảvà đánh đổi.** Giới hạn lộdữliệu và lạm quyền; cần kiểm tra scope trong truy vấn, quản lý vòng đời quyền và audit đặc quyền. 

46 

6 Architecture Decisions 



**Truy vết và kiểm chứng.** FR-S1; NFR-S1/PR1. Test dọc theo từng vai trò và ngang giữa nhà máy, đội, cá nhân. 

### **6.2.12 ADR-12 – Audit chỉthêm với checkpoint độc lập** 

**Bối cảnh.** Log kỹthuật có thểbịxoay/xóa; hash chain trong cùng kho không ngăn DBA viết lại toàn chuỗi. 

**Quyết định.** Transaction nghiệp vụghi audit outbox; ADS lưu append-only, liên kết hash theo stream, phân quyền ứng dụng chỉthêm/đọc. Lưu checkpoint định kỳởnơi có quyền quản trị tách biệt và kiểm tra thiếu sequence. 

**Phương án khác.** Không gọi một bảng audit thường là bất biến tuyệt đối; không chỉgiữlog stdout. Không lưu raw QR/PII dư thừa trong audit. 

**Hệquảvà đánh đổi.** Tăng khảnăng phát hiện can thiệp và truy vết; phải bảo vệcheckpoint, backup và ghi cảhoạt động của quản trịkho. 

**Truy vết và kiểm chứng.** FR-R5; NFR-S1/S2. Test quyền update/delete, sửa bản ghi và đối chiếu checkpoint độc lập. 

### **6.2.13 ADR-13 – Bảo vệdữliệu theo mục đích và tối thiểu hóa** 

**Bối cảnh.** Định danh gắn với thời gian và địa điểm ra vào có thểảnh hưởng quyền riêng tư của người lao động. 

**Quyết định.** Tách PII tại ICS, dùng employee_ref có kiểm soát liên kết; TLS/mTLS, mã hóa lưu trữ, quản lý khóa và log tối thiểu. Retention/xóa hoặc ẩn danh theo chính sách được phê duyệt, bao gồm backup và read model. 

**Phương án khác.** Không coi mã giảdanh là vô danh; không lưu vô hạn hoặc sao chép hồsơ vào mọi sựkiện. Không tựsuy ra đủtuân thủchỉvì đặt máy chủtrong nước. 

**Hệquảvà đánh đổi.** Giảm phạm vi dữliệu lan truyền; cần quyền truy nguyên danh tính và quy trình tổchức. Thời hạn lưu 5 năm được quản lý theo chính sách lưu trữvà vòng đời dữliệu. 

**Truy vết và kiểm chứng.** FR-S4; NFR-PR1/S2; A-08. Lập data inventory, kiểm tra quyền/retention và rà soát bởi đầu mối phụtrách. 

### **6.2.14 ADR-14 – Quan sát và fitness function từthiết kế** 

**Bối cảnh.** Các thay đổi vềmã nguồn, migration hoặc adapter có thểảnh hưởng đến chỉtiêu chất lượng và tính nhất quán kiến trúc. 

**Quyết định.** Thu metrics, log có correlation_id, trace; kiểm tra dependency, contract, replay, scope và latency trong pipeline. Lưu dữliệu thử/cấu hình và báo cáo kết quả; restore/chaos chạy ởmôi trường riêng. 

**Phương án khác.** Không chỉxem p99 rồi bỏsốmẫu vượt 2 giây; không công bốbenchmark 

47 

6 Architecture Decisions 



của máy khác như kết quảTMC. Công cụquan sát được chọn theo năng lực đội. 

**Hệquảvà đánh đổi.** Có bằng chứng đểphát hiện hồi quy; thêm công sức duy trì dữliệu/kịch bản, người trực cảnh báo và ngưỡng phù hợp. 

**Truy vết và kiểm chứng.** NFR-O1/D1/M1/P1. Pipeline và diễn tập phải có tiêu chí pass/fail, không chỉchecklist tên công cụ. 

### **6.2.15 ADR-15 – Chếđộsuy giảm và giới hạn quyền offline** 

**Bối cảnh.** Mất WAN, quyền cũ, lỗi ghi và lỗi thiết bịcần phản ứng khác nhau; duy trì mởcổng vô hạn khi mất đồng bộtạo rủi ro. 

**Quyết định.** Edge xửlý tựđộng trong hạn tin cậy dựkiến 30 phút khi còn local durable store. Hết hạn/thiếu quorum/lỗi ghi thì ngừng tựcấp quyền và dùng quy trình bảo vệcó dấu vết. Thoát hiểm độc lập phần mềm. 

**Phương án khác.** Không tựmởtất cảcổng đểche giấu lỗi; không xem LAN còn sống là đủđể dùng quyền cũ vô hạn. Ngoại lệcần người có thẩm quyền và audit. 

**Hệquảvà đánh đổi.** Giảm lệthuộc WAN có giới hạn an ninh rõ; đổi lại có thểgián đoạn tự động. Quyền thu hồi liên site không tức thời khi offline; cần TMC duyệt rủi ro và quy trình. **Truy vết và kiểm chứng.** FR-A6/G3; NFR-A1/S1/O1; A-10. Test thời điểm trước/sau expiry, mất đồng hồtin cậy và quy trình bảo vệ. 

48 

7 Design Principles 



# **Chương 7 – Design Principles** 

Nguyên tắc thiết kếhướng dẫn cách xây dựng các thành phần, trong khi architecture rules là các ràng buộc phải kiểm tra. SOLID không đồng nghĩa chia càng nhiều dịch vụcàng tốt; áp dụng ởmức trách nhiệm lớp/module và hợp đồng thay thế. Các ví dụdưới đây cụthểhóa cách áp dụng từng nguyên tắc trong hệthống TMC. 

## **7.1 Áp dụng SOLID** 

**Bảng 31:** _Ánh xạSOLID vào TMC-AACS_ 

|**Nguyên tắc**|**Áp dụng cụthể**|**Bằng chứng kiểm chứng**|
|---|---|---|
|S: Single<br>Responsibility|C06 xác minh token; C07 quyết định<br>quyền; C08 transaction sựkiện; C09 điều<br>khiển cổng.|Thay định dạng QR chỉtác động<br>verifier/issuer; đổi API cổng không<br>sửa policy hoặc projector.|
|O: Open/Closed|AccessPolicy là strategy; TokenVerifier<br>và adapter có registry được kiểm soát.|Thêm quy tắc khung giờbằng<br>implementation mới và cấu hình<br>được duyệt; không rải if theo hãng<br>cổng trong ScanHandler.|
|L: Liskov<br>Substitution|TurnstileHttpAdapter và Simulator cùng<br>trảGateOutcome và tuân<br>deadline/idempotency đã khai báo.|Chạy cùng contract test cho<br>Confirmed, Rejected, Unknown;<br>implementation không được tăng<br>điều kiện đầu vào hoặc giảthành<br>công khi timeout.|
|I: Interface<br>Segregation|Tách CredentialReader,<br>EventUnitOfWork, EventReader,<br>GateCommandPort và GateStatusReader.|Edge chỉđọc snapshot; báo cáo<br>không được quyền append sựkiện;<br>adapter không có query trạng thái<br>không bịép giảlập query thành<br>công.|
|D: Dependency<br>Inversion|ScanHandler phụthuộc port nghiệp vụ,<br>ClockPort và policy; hạtầng hiện thực<br>các port.|Unit test thay clock, store, gateway<br>không cần DB/controller thật;<br>dependency check cấm import<br>framework trong domain.|



### **7.1.1 SRP và ranh giới thay đổi** 

ScanHandler chỉđiều phối thứtự; nó không vừa ký QR, viết SQL, tính công và gửi email. GateCommander chịu trách nhiệm chính sách tác động cổng, khác HR exporter vì hợp đồng, lỗi và nhịp thay đổi khác nhau. EventUnitOfWork vẫn phải commit nguyên tửevent, intent và 

49 

7 Design Principles 



outbox: SRP không phải lý do tách transaction thành nhiều chỗrồi làm mất tính toàn vẹn. Audit và thông báo được phát từoutbox đểtác vụchậm không kéo dài transaction mạng. 

### **7.1.2 OCP và mởrộng chính sách có kiểm soát** 

AccessPolicy trảquyết định cùng lý do và policy_version; composition root chọn tập quy tắc được phê duyệt. Thêm TimeWindowPolicy hoặc chính sách một nhà máy mới không sửa điều phối luồng quét. Không nạp plugin tùy ý từngười dùng hoặc cho quản trịvô hiệu hóa kiểm tra chữký bằng cấu hình. Quy tắc bắt buộc, schema cấu hình, version và quyền thay đổi là hàng rào của khảnăng mởrộng. 

### **7.1.3 LSP và hợp đồng adapter** 

TurnstileGatewayPort nhận command có ID ổn định, gate_id, action và deadline; trả Confirmed, Rejected hoặc Unknown kèm dữliệu đối soát. Confirmed chỉđược trảkhi hợp đồng thiết bịxác nhận kết quảtương ứng. Adapter HTTP không được trảthành công giảkhi timeout; simulator phải tái hiện cảtrường hợp đã tác động nhưng mất phản hồi. Tính năng query và chống lặp được khai báo qua capability hoặc port riêng, không giảđịnh mọi controller có chức năng này. 



<!-- Start of picture text -->
interface<br>ScanHandler phụthuộc trừu tượng TurnstileGatewayPort<br>handle(scan): ScanResult execute(command, deadline)<br>: GateOutcome<br>hiện thực hiện thực<br>interface TurnstileHttpAdapter TurnstileSimulator<br>EventUnitOfWorkPort Confirmed / Rejected cùng hợp đồng;<br>commit(event, intent, outbox) Unknown lỗi có kiểm soát<br><!-- End of picture text -->

**Hình 10:** _Hợp đồng thay thếadapter và hướng phụthuộc SOLID_ 

### **7.1.4 ISP và quyền bảo mật là hai cơ chếkhác nhau** 

CredentialReader cung cấp snapshot cần thiết cho edge; CredentialWriter thuộc ICS. EventAppender được dùng trong transaction ghi; báo cáo dùng một read model reader riêng. GateStatusReader là khảnăng bổsung nếu thiết bịhỗtrợ. Tách interface giúp client không phụ thuộc hàm không cần; nó không thay thếRBAC, scope và quyền DB. Một người có thểgọi API ngoài giao diện nên kiểm tra quyền vẫn phải ởmáy chủ. 

50 

7 Design Principles 



### **7.1.5 DIP và minh họa điều phối** 

Mã giảsau thểhiện hướng phụthuộc và thứtựside effect. Các port xác định hợp đồng giữa lớp nghiệp vụvà các adapter hạtầng. 

- 1 **async function** handle(scan, ports, policy, deadline) { 

- 2 **const** prior = **await** ports.eventStore.findByScanId(scan.id); 

- 3 **if** (prior) **return** prior.safeResult; 

- 4 **const** decision = **await** policy.evaluate(scan, ports.clock); 

- 5 **const** intent = **await** ports.eventStore.commitDecisionAndIntent( 

- 6 scan, decision); _// event + optional intent + outbox, atomic_ 

- 7 **if** (!decision.allowed) **return** intent.deniedResult; 

- 8 **const** outcome = **await** ports.gate.execute(intent.command, deadline); 

- 9 **await** ports.eventStore.appendOutcomeAndOutbox(intent, outcome); 

- 10 **return** toScanResult(outcome); _// Unknown is never Success_ 

- 11 } 

**Mã nguồn 1:** _Mã giảđiều phối qua port_ 

Việc find trước commit không đủchống race; implementation kho phải có unique constraint và transaction trảlại intent đã tồn tại khi hai request cùng scan_id. Nếu append outcome thất bại sau tác động, recovery giữintent cũ và đối soát; không gọi lại tựđộng chỉvì client nhận lỗi. Lỗi, deadline, lease và phân quyền phải được xửlý trong đặc tảthực thi và contract test. 

## **7.2 Các nguyên tắc thiết kếbổsung** 

**Bảng 32:** _Nguyên tắc bổsung và cách áp dụng_ 

|**Nguyên tắc**|**Hướng dẫn cho TMC**|**Liên kết**|
|---|---|---|
|Separation of Concerns|Tách nhận diện, quyết định truy cập, ghi dữliệu<br>và tích hợp; trách nhiệm sởhữu schema rõ.|ADR-01/02; C01–C26.|
|Design for failure|Mọi I/O ngoài đều có deadline và kết quảcó<br>nghĩa; chếđộsuy giảm được mô tảtrước.|ADR-03/10/15;<br>SC-02/03/07.|
|Idempotency|Cùng ID và payload trảcùng trạng thái; duplicate<br>không nhân đôi tác động; khác payload cùng ID<br>bịtừchối.|ADR-06/07; NFR-R2.|
|Append-only /<br>versioning|Không sửa chứng cứ; projection có thểrebuild,<br>điều chỉnh và snapshot có phiên bản.|ADR-05/09/12.|
|Least privilege /|Giới hạn vai trò, scope, tài khoản DB và quyền|ADR-11/13.|
|defense in depth|kho khóa; kiểm tra ởnhiều ranh giới.||



51 

7 Design Principles 



|**Nguyên tắc**|**Hướng dẫn cho TMC**|**Liên kết**|
|---|---|---|
|Privacy by design|Chỉthu thập dữliệu cần; mã giảdanh vẫn có<br>quyền truy cập/retention; không log token.|ADR-04/13; NFR-PR1.|
|Fail-secure và an toàn<br>con người|Không tựmởcổng do lỗi; thoát hiểm và quy trình<br>an toàn không phụthuộc ứng dụng.|ADR-15; xác nhận với<br>đơn vịcổng.|
|Configuration over<br>code|Cấu hình trạm/quy tắc có schema, version và<br>audit; cấu hình thêm nhà máy vẫn cần hạtầng<br>mới.|AR-11; NFR-M1.|
|Contract-first|Version cho API, event và trạng thái; thống nhất<br>retry, partial receipt, Unknown trước khi viết<br>adapter.|FR-R4; ADR-07/09/10.|
|Observability by<br>default|Truy vết bằng scan_id/command_id/batch_id; đo<br>vi phạm và độtrễnguồn; có người xửlý cảnh báo.|ADR-14; NFR-O1.|
|KISS / YAGNI|Không thêm nhiều database, discovery hoặc<br>Kubernetes chỉvì phổbiến; giữmodular monolith<br>+ edge như phương án dựphòng.|So sánh style ởChương<br>4.|
|Evolutionary<br>architecture|Bảo vệquyết định bằng fitness function; cập nhật<br>ADR khi đổi ranh giới hoặc ngưỡng, không sửa<br>một nơi duy nhất.|NFR-D1/M1; AR-04.|



## **7.3 Mẫu thiết kếphục vụcác nguyên tắc** 

**Bảng 33:** _Mẫu thiết kếvà rủi ro nếu dùng sai_ 

|**Mẫu**|**Nơi áp dụng**|**Điều kiện sửdụng đúng**|
|---|---|---|
|Strategy|C07; chính sách truy cập.|Quy tắc được duyệt, thứtựáp dụng xác định và<br>kếtquảcó lýdo/version.|
|Adapter / anti-corruption<br>layer|C09, C21 và inbound HR của<br>C01.|Không đưa mã lỗi/hợp đồng nhà cung cấp vào<br>entitynghiệpvụ.|
|Outbox / inbox|C08, C11, C12 và các miền<br>phát sựkiện.|Transaction nguyên tử, ack sau commit, unique<br>event_id; không hứa exactly-once ngoài vùng<br>kiểm soát.|
|Circuit breaker / timeout /<br>backoff|API HR và controller.|Breaker không làm biến mất nghĩa vụđối soát;<br>retrychỉkhi an toàn và còn budget.|
|State machine|Projection trạng thái scan, kỳ<br>và batch.|Unknown là trạng thái thật; sựkiện muộn tạo<br>lịch sử/phiên bản, không ghi đè.|
|CQRS-lite / projection|C13, C18, C19.|Kho ghi và read model có watermark, có thể<br>rebuild; khôngcần tách database vật lýngay.|
|Repository / Unit of Work|Ghi access event và<br>intent/outbox.|Port hẹp nhưng cùng transaction; domain không<br>biết ORM hoặc isolation framework.|



52 

8 Đánh giá thiết kếvà kếhoạch kiểm chứng 



# **Chương 8 – Đánh giá thiết kếvà kếhoạch kiểm chứng** 

## **8.1 Mức đáp ứng Task 1** 

Báo cáo trình bày bối cảnh TMC, mục tiêu đo được, phạm vi, stakeholders và user story; đặc tảFR/NFR, giảđịnh và workload; xác định đặc tính kiến trúc; so sánh style; xây dựng logical và physical theo từng bước; tổng hợp 4+1; ghi các rules/ADR và áp dụng SOLID. Mỗi lớp quyết định có mã và liên kết đến yêu cầu hoặc kịch bản kiểm chứng. 

**Bảng 34:** _Đối chiếu nội dung bàn giao với yêu cầu Task 1_ 

|**Yêu cầu**|**Nội dung đáp ứng**|**Trọng tâm thiết kế**|
|---|---|---|
|Bối cảnh, mục tiêu,<br>phạm vi, FR/NFR|Chương 1–2: sáu vai trò, user story; FR<br>theo năm nhóm, NFR và giảđịnh.|Phân biệt nguồn yêu cầu, xác<br>định cơ sởthiết kếvà các hợp<br>đồng tích hợp.|
|Architecture<br>Characteristics|Chương 3: quy trình, ứng viên, ưu tiên,<br>kịch bản, truy vết và trade-off.|Ưu tiên toàn vẹn dữliệu, hiệu<br>năng tại cổng và bảo mật; lượng<br>hóa bằng các kịch bản chất<br>lượng.|
|Structure|Chương 4: so sánh sáu phong cách và độ<br>nhạy; 8 bước logical, 8 bước physical.|Phân bổthành phần, miền lỗi,<br>ngân sách độtrễvà dung lượng<br>theo tải nghiệp vụ.|
|Nhiều góc nhìn|Chương 5: logical, process, development,<br>physical và 8 scenarios.|Không đồng nhất C4 với 4+1;<br>các sơ đồthống nhất C01–C26<br>và cùng miền dữliệu.|
|Architecture Decisions|Chương 6: 12 rules và 15 ADR.|Mỗi quyết định có bối cảnh,<br>phương án thay thế, hệquảvà<br>phương pháp kiểm chứng.|
|Design Principles|Chương 7: SOLID, mẫu thiết kế, hợp đồng<br>và mã giả.|Cụthểhóa trách nhiệm, hợp<br>đồng thay thếvà hướng phụ<br>thuộc bằng thành phần và mã<br>giả.|



## **8.2 Kếhoạch kiểm chứng có tiêu chí rõ ràng** 

53 

8 Đánh giá thiết kếvà kếhoạch kiểm chứng 



**Bảng 35:** _Kếhoạch kiểm chứng kiến trúc_ 

|**Phép kiểm**|**Truy vết**|**Thiết lập**|**Bằng chứng / tiêu chí**|
|---|---|---|---|
|T-01: luồng quét /<br>tải|SC-01;<br>NFR-P1/P2|800 lượt/30 phút/nhà máy và<br>burst, đồng thời báo cáo; đủ<br>luồng thành công/từchối/lỗi.|Đo mọi mẫu, max/p95/p99 và<br>sốvượt 2 giây; tách latency<br>phần mềm và thời gian cơ khí.|
|T-02: crash và<br>outbox|SC-01/07;<br>NFR-R1/R2|Crash trước commit, sau<br>commit trước gọi, sau gọi<br>trước outcome, sau publish<br>trước ack.|Không thiếu scan_id đã<br>commit; không phát<br>command mới cho retry;<br>Unknown được giữvà đối<br>soát.|
|T-03: mất WAN /<br>quyền cũ|SC-02/04; FR-A6|Ngắt WAN, thu hồi quyền tại<br>central, thửtrước/sau expiry<br>policy, kết nối lại.|Hành vi offline đúng cấu<br>hình; replay không thiếu ID;<br>thu hồi quyền có hiệu lực theo<br>thời hạn snapshot offline.|
|T-04: contract<br>cổng|SC-03; NFR-I1|Simulator và sandbox:<br>rejected, timeout trước/sau<br>tác động, accepted-only,<br>duplicate command.|Adapter cùng ngữnghĩa;<br>không retry mù; Confirmed<br>phải có bằng chứng theo API.|
|T-05: xuất HR|SC-05; FR-R3/R4|API lỗi, partial receipt,<br>duplicate batch, dữliệu<br>nguồn đến muộn và<br>adjustment.|Đối chiếu<br>khóa/version/checksum; lỗi<br>không đánh dấu hoàn tất;<br>timeline có cảnh báo trước<br>hạn.|
|T-06: quyền / dữ<br>liệu|SC-06;<br>NFR-S1/PR1|Ma trận vai trò và scope; sửa<br>request đọc người/nhà máy<br>khác; kiểm log/token.|Không lộdữliệu ngoài quyền;<br>audit đầy đủhành động nhạy<br>cảm; không lưu raw QR.|
|T-07: HA / DR /<br>backup|SC-07;<br>NFR-A1/D1|Lỗi process, host, standby,<br>witness, partition; restore<br>bản sao ởmôi trường tách.|Đo RTO/RPO theo miền; chỉ<br>một writer; kiểm tập ID và<br>checkpoint sau restore.|
|T-08: tiến hóa /<br>phụthuộc|SC-08; NFR-M1|Thay controller adapter,<br>thêm policy và station; kiểm<br>static dependency.|Không sửa use case theo<br>hãng; domain không import<br>hạtầng; contract tương thích.|



Mỗi lần thực hiện phải lưu phiên bản phần mềm, cấu hình, đặc điểm máy/mạng, tập dữ liệu, timestamp, log và kết quả. Kết quảđược đối chiếu với tiêu chí chấp nhận; sai lệch là đầu vào đểcập nhật ADR, chỉtiêu và sizing. 

- **8.3 Rủi ro và biện pháp kiểm soát** 

54 

8 Đánh giá thiết kếvà kếhoạch kiểm chứng 



**Bảng 36:** _Rủi ro kiến trúc và biện pháp kiểm soát_ 

|**Mã**|**Vấn đề**|**Hành động / người phối hợp**|
|---|---|---|
|R-01|API cổng có thểkhác nhau vềđộtrễ,<br>idempotency, query và cảm biến<br>passage.|Ưu tiên khảo sát/sandbox với đơn vịcổng; đây<br>là điều kiện chốt budget và ngữnghĩa<br>attendance.|
|R-02|Khác biệt hợp đồng HR vềschema,<br>partial receipt, cập nhật lô và quyền<br>đọc hồsơ.|Nhân sựvà đầu mối HR thống nhất contract, dữ<br>liệu mẫu, thời điểm cut-off và xửlý ca qua đêm.|
|R-03|Chính sách offline có rủi ro thu hồi<br>chậm và chống vào lại liên site.|Bảo vệ, quản trịvà nhân sựduyệt cửa sổtin cậy,<br>chếđộthủcông, mục tiêu lag và lịch diễn tập.|
|R-04|Thiếu host/quorum/UPS hoặc DB đồng<br>bộchậm.|IT xác nhận miền lỗi và ngân sách; so sánh với<br>phương án central modular monolith + edge<br>trước khi tăng độphức tạp.|
|R-05|Chính sách retention và bảo vệdữliệu<br>có thểthay đổi.|Đầu mối phụtrách xác nhận mục đích, quyền,<br>thời hạn, xửlý yêu cầu và bảo vệbackup; cập<br>nhật cấu hình lưu trữtheo chính sách.|
|R-06|QR ký sốvẫn có thểđược chia sẻtrong<br>cửa sổhiệu lực.|Thống nhất mức rủi ro chấp nhận và quy trình<br>bảo vệ; không bổsung sinh trắc học ngoài<br>phạm vi.|
|R-07|Nguồn edge hoặc HR dừng lâu có thể<br>làm trễhạn tháng.|Giám sát watermark/backlog, cảnh báo sớm và<br>quy trình đối soát dựphòng.|



## **8.4 Kết luận** 

Thiết kếưu tiên toàn vẹn dữliệu, phản hồi cổng và bảo mật hơn mởrộng quy mô cực lớn. Phần xửlý ra vào chạy tại nhà máy; central quản lý, hợp nhất và tích hợp HR. Outbox, định danh ổn định, snapshot có phiên bản, RBAC theo scope và ADR tạo cơ sởđểtriển khai có thể kiểm tra. 

Kiến trúc đáp ứng phạm vi phân tích và thiết kếcủa Task 1, bao quát từyêu cầu đến cấu trúc, hành vi, quyết định và nguyên tắc thiết kế. Ma trận truy vết và các tiêu chí kiểm chứng bảo đảm sựnhất quán giữa mục tiêu nghiệp vụ, đặc tính chất lượng và trách nhiệm của từng thành phần. 

55 

