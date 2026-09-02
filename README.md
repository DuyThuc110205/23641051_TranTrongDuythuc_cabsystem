# 23641051_TranTrongDuythuc_cabsystem

## 1/ Stakeholder
### BẢNG PHÂN TÍCH VÀ XÁC ĐỊNH STAKEHOLDERS (CAB SYSTEM)
| STT | Nhóm Stakeholder | Vai trò chi tiết | Vai trò & Kỳ vọng chính đối với hệ thống CAB |
|---:|---|---|---|
| 1 | **Ban giám đốc / Chủ doanh nghiệp** | Định hướng hoạt động kinh doanh, quyết định mục tiêu và phạm vi hệ thống | Muốn hệ thống vận hành ổn định, phục vụ số lượng lớn khách hàng và tài xế, kiểm soát doanh thu, hiệu quả hoạt động và có khả năng mở rộng |
| 2 | **Khách hàng** | Người sử dụng dịch vụ để đặt và sử dụng chuyến xe | Đăng ký/đăng nhập, đặt xe nhanh, theo dõi trạng thái chuyến, biết thông tin tài xế, thanh toán, xem lịch sử và đánh giá tài xế |
| 3 | **Tài xế** | Người nhận và trực tiếp thực hiện chuyến xe | Quản lý hồ sơ và phương tiện, cập nhật trạng thái sẵn sàng, nhận thông báo chuyến, chấp nhận/từ chối chuyến, cập nhật trạng thái và hoàn thành chuyến |
| 4 | **Nhân viên vận hành** | Theo dõi và điều phối hoạt động đặt xe hằng ngày | Theo dõi chuyến đang diễn ra, trạng thái tài xế, hỗ trợ xử lý chuyến lỗi, quản lý thông tin khách hàng, tài xế, phương tiện và tra cứu lịch sử |
| 5 | **Bộ phận Tài chính / Kế toán** | Theo dõi các khoản thanh toán, giao dịch và doanh thu từ chuyến xe | Tra cứu giao dịch, theo dõi số tiền phải thu, trạng thái thanh toán và doanh thu; đảm bảo dữ liệu tài chính chính xác |
| 6 | **Nhà cung cấp thanh toán bên ngoài** | Cung cấp dịch vụ xử lý thanh toán điện tử | Tiếp nhận yêu cầu thanh toán, xử lý giao dịch và trả kết quả cho CAB; không yêu cầu CAB lưu thông tin nhạy cảm của thẻ/tài khoản |
| 7 | **Nhà cung cấp dịch vụ thông báo** | Cung cấp các kênh gửi thông báo đến khách hàng và tài xế | Gửi thông báo về đặt xe, tài xế, chuyến đi và thanh toán; hỗ trợ khả năng bổ sung hoặc thay đổi kênh thông báo trong tương lai |
| 8 | **Bộ phận Kinh doanh & Marketing** | Phụ trách hoạt động kinh doanh, thu hút khách hàng và phát triển dịch vụ | Cần dữ liệu về số lượng chuyến, khách hàng và doanh thu để đánh giá hoạt động kinh doanh; kỳ vọng hệ thống hỗ trợ mở rộng dịch vụ và phát triển khách hàng |
| 9 | **Bộ phận Kỹ thuật / IT** | Quản lý hạ tầng kỹ thuật, vận hành và hỗ trợ hệ thống | Hệ thống ổn định, bảo mật, dễ bảo trì; các thành phần có thể mở rộng độc lập và có thể triển khai tính năng mới từng phần mà hạn chế ảnh hưởng hệ thống đang hoạt động |

## 2/ Stakeholder Power–Interest Matrix
### 2.1/ Phân loại Stakeholder theo Power – Interest
| Nhóm | Tên nhóm | Stakeholder | Chiến lược quản lý |
|---|---|---|---|
| **1** | **Quản lý chặt chẽ** | **Ban giám đốc / Chủ doanh nghiệp** | Tham gia thường xuyên, xác nhận phạm vi, yêu cầu và các quyết định quan trọng |
| | | **Nhân viên vận hành** | Làm việc trực tiếp, thu thập yêu cầu và lấy phản hồi thường xuyên |
| | | **Bộ phận Kỹ thuật / IT** | Phối hợp chặt chẽ về kỹ thuật, bảo mật, hiệu năng và khả năng mở rộng |
| **2** | **Duy trì sự hài lòng** | **Bộ phận Tài chính / Kế toán** | Đảm bảo các yêu cầu về thanh toán, giao dịch và doanh thu |
| | | **Bộ phận Kinh doanh & Marketing** | Đảm bảo có dữ liệu cần thiết để theo dõi hoạt động kinh doanh |
| **3** | **Cập nhật thông tin** | **Khách hàng** | Thu thập nhu cầu, phản hồi và ưu tiên trải nghiệm người dùng |
| | | **Tài xế** | Khảo sát quy trình thực tế và thu thập phản hồi |
| | | **Nhà cung cấp thanh toán bên ngoài** | Trao đổi yêu cầu tích hợp, trạng thái giao dịch và xử lý lỗi |
| | | **Nhà cung cấp dịch vụ thông báo** | Đảm bảo yêu cầu tích hợp và khả năng mở rộng kênh thông báo |
| **4** | **Theo dõi** | **Chưa xác định** | Chỉ cần theo dõi, không cần tham gia thường xuyên |

### 2.2/ Ma trận 2 chiều phân loại Stakeholder theo:
- **Trục X:** Mức độ quan tâm (Interest)
- **Trục Y:** Mức độ ảnh hưởng (Power)

```mermaid
quadrantChart
    title Stakeholder Power - Interest Matrix

    x-axis "Quan tâm thấp" --> "Quan tâm cao"
    y-axis "Ảnh hưởng thấp" --> "Ảnh hưởng cao"

    quadrant-1 "QUẢN LÝ CHẶT CHẼ"
    quadrant-2 "DUY TRÌ SỰ HÀI LÒNG"
    quadrant-3 "THEO DÕI"
    quadrant-4 "CẬP NHẬT THÔNG TIN"

    "Ban Giám đốc / Chủ doanh nghiệp": [0.95, 0.95]
    "Nhân viên vận hành": [0.85, 0.90]
    "Bộ phận Kỹ thuật / IT": [0.90, 0.88]

    "Bộ phận Tài chính / Kế toán": [0.50, 0.85]
    "Bộ phận Kinh doanh & Marketing": [0.55, 0.80]

    "Khách hàng": [0.90, 0.45]
    "Tài xế": [0.85, 0.40]
    "NCC thanh toán bên ngoài": [0.65, 0.45]
    "NCC dịch vụ thông báo": [0.60, 0.40]

    "Chưa xác định": [0.20, 0.20]
```

## 3/ Business goals
### BẢNG XÁC ĐỊNH MỤC TIÊU KINH DOANH (BUSINESS GOALS)
| STT | Business Goal | Mô tả | Kỳ vọng / Kết quả cần đạt |
|---:|---|---|---|
| 1 | **Nâng cao hiệu quả đặt xe** | Thay thế quy trình đặt xe và phân công tài xế thủ công bằng hệ thống CAB | Khách hàng có thể đặt xe nhanh, hệ thống tự động tiếp nhận và xử lý yêu cầu |
| 2 | **Tự động hóa việc tìm và phân công tài xế** | Tự động tìm tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và tiêu chí vận hành | Giảm thời gian điều phối, hạn chế phụ thuộc vào nhân viên vận hành |
| 3 | **Cải thiện trải nghiệm khách hàng** | Cung cấp thông tin rõ ràng trong toàn bộ quá trình sử dụng dịch vụ | Khách hàng biết trạng thái chuyến, tài xế, thời gian dự kiến đến, chi phí và kết quả thanh toán |
| 4 | **Nâng cao hiệu quả hoạt động của tài xế** | Hỗ trợ tài xế nhận và xử lý chuyến thông qua hệ thống | Tài xế dễ dàng nhận chuyến, cập nhật trạng thái và hoàn thành chuyến |
| 5 | **Quản lý tập trung dữ liệu vận hành** | Tập trung thông tin khách hàng, tài xế, phương tiện, chuyến đi và giao dịch | Nhân viên có thể tra cứu và quản lý dữ liệu từ một hệ thống thống nhất |
| 6 | **Quản lý thanh toán và doanh thu hiệu quả** | Tích hợp thanh toán điện tử và quản lý kết quả thanh toán | Theo dõi được số tiền phải trả, trạng thái giao dịch và doanh thu; không lưu thông tin thanh toán nhạy cảm |
| 7 | **Giảm tỷ lệ chuyến không được phân công** | Xây dựng cơ chế tiếp tục tìm tài xế khi tài xế được đề xuất không phản hồi hoặc từ chối | Tăng khả năng tìm được tài xế mà khách hàng không phải tạo lại yêu cầu |
| 8 | **Tăng khả năng kiểm soát hoạt động vận hành** | Cung cấp giao diện để nhân viên theo dõi chuyến và trạng thái tài xế | Nhân viên có thể phát hiện và xử lý nhanh các trường hợp bất thường |
| 9 | **Cung cấp dữ liệu phục vụ quản lý và ra quyết định** | Tổng hợp các chỉ số hoạt động chính | Ban lãnh đạo có thể theo dõi số chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả tài xế |
| 10 | **Đảm bảo an toàn và bảo mật dữ liệu** | Bảo vệ thông tin cá nhân, phương tiện, vị trí và giao dịch | Chỉ người có quyền mới được truy cập dữ liệu/chức năng phù hợp; các thao tác quan trọng được lưu vết |
| 11 | **Đảm bảo hệ thống hoạt động ổn định khi nhu cầu tăng cao** | Thiết kế hệ thống có khả năng mở rộng khi số lượng khách hàng và tài xế tăng | Hạn chế tình trạng hệ thống bị gián đoạn hoặc giảm hiệu năng trong giờ cao điểm |
| 12 | **Tạo nền tảng có khả năng mở rộng trong tương lai** | Xây dựng CAB không chỉ phục vụ MVP mà còn hỗ trợ phát triển thêm dịch vụ và tích hợp | Có thể bổ sung loại dịch vụ, phương thức thanh toán, kênh thông báo và thay đổi thành phần kỹ thuật mà không phải xây dựng lại toàn bộ hệ thống |


## 4/ Scope
### BẢNG PHẠM VI CÔNG VIỆC THEO MODULE 
| STT | Module | Phạm vi công việc chính |
|---:|---|---|
| 1 | **Quản lý tài khoản & hồ sơ** | Đăng ký, đăng nhập, đăng xuất; cập nhật thông tin khách hàng và tài xế; quản lý trạng thái tài xế |
| 2 | **Đặt xe (Booking)** | Nhập điểm đón, điểm đến; lựa chọn loại xe; tạo và xác nhận yêu cầu đặt xe |
| 3 | **Tìm & phân công tài xế (Dispatch)** | Xác định tài xế phù hợp dựa trên vị trí và trạng thái sẵn sàng; gửi yêu cầu chuyến; tài xế chấp nhận hoặc từ chối; tiếp tục tìm tài xế khác khi không có phản hồi hoặc bị từ chối |
| 4 | **Quản lý & theo dõi chuyến đi** | Quản lý trạng thái chuyến từ khi tạo yêu cầu đến khi hoàn thành hoặc hủy; theo dõi thông tin tài xế, vị trí và thời gian dự kiến đến |
| 5 | **Quản lý tài xế & phương tiện** | Quản lý hồ sơ tài xế; thông tin phương tiện; trạng thái hoạt động; thông tin vị trí tài xế |
| 6 | **Tính cước & thanh toán** | Xác định số tiền phải trả; hỗ trợ thanh toán tiền mặt và điện tử; tích hợp nhà cung cấp thanh toán; xử lý và lưu trạng thái giao dịch |
| 7 | **Thông báo** | Gửi thông báo cho khách hàng và tài xế về đặt xe, nhận chuyến, tài xế đến, trạng thái chuyến và kết quả thanh toán |
| 8 | **Quản trị & vận hành** | Quản lý khách hàng, tài xế, phương tiện và chuyến đi; theo dõi chuyến đang diễn ra; xử lý chuyến lỗi; tra cứu giao dịch; phân quyền |
| 9 | **Báo cáo & giám sát** | Cung cấp báo cáo về số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả hoạt động của tài xế |


## 5/ Business Requirements
### **BẢNG YÊU CẦU NGHIỆP VỤ (BUSINESS REQUIREMENTS)**
| ID | Business Requirement | Mô tả |
|---|---|---|
| **BR-01** | Quản lý đặt xe | Hệ thống hỗ trợ đặt và thực hiện chuyến đi từ khi tạo yêu cầu đến khi hoàn thành hoặc hủy. |
| **BR-02** | Quản lý khách hàng | Hệ thống quản lý tài khoản và thông tin hồ sơ khách hàng. |
| **BR-03** | Quản lý tài xế | Hệ thống quản lý tài khoản, hồ sơ và trạng thái hoạt động của tài xế. |
| **BR-04** | Quản lý phương tiện | Hệ thống quản lý thông tin phương tiện phục vụ vận chuyển. |
| **BR-05** | Tìm và phân công tài xế | Hệ thống tự động tìm và phân công tài xế phù hợp dựa trên vị trí, trạng thái và tiêu chí vận hành. |
| **BR-06** | Xử lý tài xế không nhận chuyến | Hệ thống tự động tìm tài xế khác khi tài xế từ chối hoặc không phản hồi. |
| **BR-07** | Theo dõi chuyến đi | Hệ thống hỗ trợ theo dõi trạng thái, vị trí và thời gian dự kiến của chuyến đi. |
| **BR-08** | Tính cước và thanh toán | Hệ thống tính cước và hỗ trợ thanh toán tiền mặt hoặc thanh toán điện tử qua nhà cung cấp bên ngoài. |
| **BR-09** | Xử lý kết quả thanh toán | Hệ thống ghi nhận trạng thái giao dịch, thông báo kết quả và hỗ trợ xử lý lại khi thanh toán thất bại. |
| **BR-10** | Quản lý thông báo | Hệ thống gửi thông báo cho khách hàng và tài xế về các sự kiện quan trọng của chuyến đi. |
| **BR-11** | Hỗ trợ vận hành | Hệ thống hỗ trợ nhân viên vận hành theo dõi chuyến, trạng thái tài xế và xử lý sự cố. |
| **BR-12** | Quản lý và tra cứu dữ liệu | Hệ thống tập trung và hỗ trợ tra cứu dữ liệu khách hàng, tài xế, phương tiện, chuyến đi và giao dịch. |
| **BR-13** | Báo cáo hoạt động | Hệ thống cung cấp báo cáo về số chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả tài xế. |
| **BR-14** | Đánh giá dịch vụ | Hệ thống cho phép khách hàng đánh giá tài xế sau khi chuyến đi hoàn thành. |
| **BR-15** | Bảo mật và phân quyền | Hệ thống kiểm soát quyền truy cập và bảo vệ thông tin người dùng, phương tiện, vị trí và giao dịch. |
| **BR-16** | Lưu vết hoạt động | Hệ thống ghi nhận các thao tác quan trọng để kiểm tra và xử lý sự cố. |
| **BR-17** | Đảm bảo ổn định và mở rộng | Hệ thống phải hoạt động ổn định và có khả năng mở rộng khi số lượng người dùng và chuyến đi tăng. |


## 6/ Functional Requirements
### BẢNG PHÂN RÃ YÊU CẦU CHỨC NĂNG (FUNCTIONAL REQUIREMENTS)
| ID | Business Requirement | Functional Requirement |
|---|---|---|
| **FR-01.01** | **BR-01 Quản lý đặt xe** | Hệ thống cho phép khách hàng tạo, theo dõi và hủy yêu cầu/chuyến đi theo chính sách. |
| **FR-02.01** | **BR-02 Quản lý khách hàng** | Hệ thống cho phép khách hàng đăng ký, đăng nhập và cập nhật thông tin cá nhân. |
| **FR-02.02** | | Hệ thống lưu trữ và quản lý thông tin tài khoản khách hàng. |
| **FR-03.01** | **BR-03 Quản lý tài xế** | Hệ thống cho phép tạo tài khoản, cập nhật hồ sơ và trạng thái hoạt động của tài xế. |
| **FR-03.02** | | Hệ thống ghi nhận trạng thái sẵn sàng nhận chuyến của tài xế. |
| **FR-04.01** | **BR-04 Quản lý phương tiện** | Hệ thống cho phép nhân viên vận hành tạo và cập nhật thông tin phương tiện. |
| **FR-04.02** | | Hệ thống cho phép liên kết phương tiện với tài xế. |
| **FR-05.01** | **BR-05 Tìm và phân công tài xế** | Hệ thống xác định tài xế phù hợp dựa trên vị trí, trạng thái và tiêu chí vận hành. |
| **FR-05.02** | | Hệ thống ưu tiên và gửi yêu cầu chuyến đến tài xế phù hợp. |
| **FR-05.03** | | Hệ thống ghi nhận tài xế được phân công và nhận chuyến. |
| **FR-06.01** | **BR-06 Xử lý tài xế không nhận chuyến** | Hệ thống ghi nhận trường hợp tài xế từ chối hoặc không phản hồi. |
| **FR-06.02** | | Hệ thống tự động tìm và gửi yêu cầu đến tài xế phù hợp tiếp theo. |
| **FR-06.03** | | Hệ thống thông báo cho khách hàng khi không tìm được tài xế. |
| **FR-07.01** | **BR-07 Theo dõi chuyến đi** | Hệ thống tạo và cập nhật trạng thái chuyến đi từ khi nhận chuyến đến khi hoàn thành hoặc hủy. |
| **FR-07.02** | | Hệ thống lưu lịch sử và thông tin của chuyến đi. |
| **FR-08.01** | **BR-08 Theo dõi vị trí và ETA** | Hệ thống ghi nhận và cập nhật vị trí tài xế trong quá trình hoạt động. |
| **FR-08.02** | | Hệ thống sử dụng vị trí để hỗ trợ phân công tài xế và cung cấp ETA cho khách hàng. |
| **FR-09.01** | **BR-09 Tính cước** | Hệ thống xác định loại dịch vụ và thông tin cần thiết để tính cước. |
| **FR-09.02** | | Hệ thống tính và lưu số tiền khách hàng phải trả theo quy tắc cước. |
| **FR-10.01** | **BR-10 Thanh toán** | Hệ thống hỗ trợ thanh toán bằng tiền mặt và thanh toán điện tử. |
| **FR-10.02** | | Hệ thống gửi và nhận kết quả giao dịch thông qua nhà cung cấp thanh toán bên ngoài. |
| **FR-11.01** | **BR-11 Xử lý kết quả thanh toán** | Hệ thống ghi nhận trạng thái và thông báo kết quả giao dịch cho khách hàng. |
| **FR-11.02** | | Hệ thống hỗ trợ thực hiện lại giao dịch thất bại theo chính sách doanh nghiệp. |
| **FR-12.01** | **BR-12 Quản lý thông báo** | Hệ thống gửi thông báo cho khách hàng và tài xế về các sự kiện quan trọng của chuyến đi. |
| **FR-12.02** | | Hệ thống thông báo kết quả thanh toán và các thay đổi liên quan đến chuyến đi. |
| **FR-13.01** | **BR-13 Hỗ trợ vận hành** | Hệ thống cho phép nhân viên vận hành theo dõi chuyến đi và trạng thái tài xế. |
| **FR-13.02** | | Hệ thống hỗ trợ tra cứu thông tin, lịch sử chuyến và giao dịch. |
| **FR-13.03** | | Hệ thống hỗ trợ xử lý các trường hợp chuyến đi bị lỗi. |
| **FR-14.01** | **BR-14 Quản lý và tra cứu dữ liệu** | Hệ thống lưu trữ tập trung dữ liệu khách hàng, tài xế, phương tiện, chuyến đi và giao dịch. |
| **FR-14.02** | | Người dùng có quyền có thể tìm kiếm và tra cứu dữ liệu. |
| **FR-15.01** | **BR-15 Báo cáo hoạt động** | Hệ thống cung cấp báo cáo về số chuyến, doanh thu, tỷ lệ hoàn thành và tỷ lệ hủy. |
| **FR-15.02** | | Hệ thống cung cấp thông tin về hiệu quả hoạt động của tài xế. |
| **FR-16.01** | **BR-16 Đánh giá dịch vụ** | Hệ thống cho phép khách hàng đánh giá tài xế sau khi chuyến đi hoàn thành. |
| **FR-16.02** | | Hệ thống lưu trữ và hỗ trợ tra cứu kết quả đánh giá. |
| **FR-17.01** | **BR-17 Bảo mật và phân quyền** | Hệ thống xác thực người dùng và phân quyền truy cập theo vai trò. |
| **FR-17.02** | | Hệ thống bảo vệ thông tin cá nhân, phương tiện, vị trí và giao dịch. |
| **FR-17.03** | | Hệ thống ghi nhận các thao tác quan trọng để phục vụ kiểm tra và xử lý sự cố. |
| **FR-17.04** | | Hệ thống đảm bảo các thành phần hoạt động ổn định và có khả năng mở rộng khi quy mô sử dụng tăng. |


## 7/ Vẽ use case
## 7.1/ Xác định Actors
| STT | Actor | Vai trò |
| :---: | :--- | :--- |
| 1 | **Khách hàng** | Sử dụng dịch vụ đặt xe: đăng ký, đăng nhập, quản lý thông tin cá nhân, đặt xe, theo dõi chuyến, hủy chuyến, thanh toán, xem lịch sử và đánh giá tài xế. |
| 2 | **Tài xế** | Cung cấp dịch vụ vận chuyển: quản lý hồ sơ và phương tiện, cập nhật trạng thái hoạt động, nhận hoặc từ chối chuyến, cập nhật trạng thái chuyến và vị trí. |
| 3 | **Nhân viên vận hành** | Điều phối và giám sát hoạt động đặt xe; quản lý thông tin khách hàng, tài xế, phương tiện; theo dõi chuyến đi, hỗ trợ xử lý sự cố, tra cứu giao dịch và phân quyền theo chức năng được cấp. |
| 4 | **Ban giám đốc** | Theo dõi tình hình hoạt động và hiệu quả kinh doanh thông qua các báo cáo về số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả tài xế. |
| 5 | **Nhà cung cấp thanh toán** | Tiếp nhận và xử lý các giao dịch thanh toán điện tử, sau đó trả kết quả giao dịch cho hệ thống CAB. |
| 6 | **Nhà cung cấp thông báo** | Cung cấp dịch vụ gửi thông báo đến khách hàng và tài xế về các sự kiện trong quá trình đặt và thực hiện chuyến. |

## 7.2/ Sơ đồ use case
![CAB System Use Case Diagram](usecasediagram.jpg)

```mermaid
flowchart LR

%% =========================================================
%% CAB SYSTEM (Ranh giới hệ thống)
%% =========================================================
subgraph CAB_SYSTEM["CAB SYSTEM"]
    direction TB

    %% Chức năng của Khách hàng (Xanh dương)
    UC01(["UC01<br/>Đăng ký tài khoản"])
    UC02(["UC02<br/>Đăng nhập"])
    UC03_KH(["UC03<br/>Cập nhật hồ sơ"])
    UC05(["UC05<br/>Đặt xe"])
    UC08_KH(["UC08<br/>Theo dõi & cập nhật chuyến đi"])
    UC11(["UC11<br/>Thanh toán chuyến đi"])
    UC13(["UC13<br/>Xem lịch sử chuyến đi"])
    UC14(["UC14<br/>Đánh giá tài xế"])

    %% Chức năng hệ thống (Vàng)
    UC06(["UC06<br/>Tìm & phân công tài xế"])
    UC10(["UC10<br/>Tính cước chuyến đi"])
    UC12(["UC12<br/>Gửi & tiếp nhận thông báo"])

    %% Chức năng của Tài xế (Xanh lá)
    UC03_TX(["UC03<br/>Cập nhật hồ sơ"])
    UC04(["UC04<br/>Cập nhật thông tin phương tiện"])
    UC07(["UC07<br/>Nhận hoặc từ chối chuyến"])
    UC08_TX(["UC08<br/>Theo dõi & cập nhật chuyến đi"])
    UC09(["UC09<br/>Cập nhật vị trí tài xế"])

    %% Chức năng của Nhân viên vận hành & Ban giám đốc (Tím)
    UC15(["UC15<br/>Tra cứu & cập nhật thông tin đối tượng"])
    UC16(["UC16<br/>Hỗ trợ & xử lý chuyến"])
    UC17(["UC17<br/>Tra cứu giao dịch"])
    UC18(["UC18<br/>Xem báo cáo hoạt động"])
    UC19(["UC19<br/>Phân quyền người dùng"])
    UC20(["UC20<br/>Thiết lập cấu hình hệ thống"])

end

%% =========================================================
%% ACTORS (Tác nhân)
%% =========================================================
ACTOR_KH["👤 Khách hàng"]
ACTOR_TX["👤 Tài xế"]
ACTOR_NVVH["👤 Nhân viên vận hành"]
ACTOR_BGD["👤 Ban giám đốc"]
ACTOR_PAYMENT["🏛️ Nhà cung cấp thanh toán"]
ACTOR_NOTIF["✉️ Nhà cung cấp thông báo"]

%% =========================================================
%% LIÊN KẾT TÁC NHÂN -> USE CASE (Association)
%% =========================================================

%% Khách hàng
ACTOR_KH --- UC01
ACTOR_KH --- UC02
ACTOR_KH --- UC03_KH
ACTOR_KH --- UC05
ACTOR_KH --- UC08_KH
ACTOR_KH --- UC11
ACTOR_KH --- UC13
ACTOR_KH --- UC14

%% Tài xế
ACTOR_TX --- UC03_TX
ACTOR_TX --- UC04
ACTOR_TX --- UC07
ACTOR_TX --- UC08_TX
ACTOR_TX --- UC09

%% Nhân viên vận hành
ACTOR_NVVH --- UC15
ACTOR_NVVH --- UC16
ACTOR_NVVH --- UC17
ACTOR_NVVH --- UC18
ACTOR_NVVH --- UC19
ACTOR_NVVH --- UC20

%% Ban giám đốc
ACTOR_BGD --- UC18

%% Tác nhân bên ngoài
UC11 -. "Xử lý thanh toán điện tử" .-> ACTOR_PAYMENT
UC12 -. "Gửi thông báo" .-> ACTOR_NOTIF

%% =========================================================
%% MỐI QUAN HỆ GIỮA CÁC USE CASE (Include & Extend)
%% =========================================================
UC05 -. "include" .-> UC06
UC05 -. "include" .-> UC10
UC11 -. "include" .-> UC10
UC10 -. "include" .-> UC12
UC07 -. "extend" .-> UC06

%% =========================================================
%% STYLES (Định dạng màu sắc theo đúng chú thích trong ảnh)
%% =========================================================
classDef actorStyle fill:#ffffff,stroke:#333333,stroke-width:2px,color:#222222;
classDef externalStyle fill:#ffffff,stroke:#1d70b8,stroke-width:2px,color:#1d70b8;

classDef customerUC fill:#e8f0fe,stroke:#4285f4,stroke-width:1.5px,color:#1a73e8;
classDef driverUC fill:#e6f4ea,stroke:#34a853,stroke-width:1.5px,color:#137333;
classDef systemUC fill:#fef7e0,stroke:#fbbc04,stroke-width:1.5px,color:#b06000;
classDef adminUC fill:#fce8e6,stroke:#ea4335,stroke-width:1.5px,color:#c5221f;

%% Áp dụng Style
class ACTOR_KH,ACTOR_TX,ACTOR_NVVH,ACTOR_BGD actorStyle;
class ACTOR_PAYMENT,ACTOR_NOTIF externalStyle;

class UC01,UC02,UC03_KH,UC05,UC08_KH,UC11,UC13,UC14 customerUC;
class UC03_TX,UC04,UC07,UC08_TX,UC09 driverUC;
class UC06,UC10,UC12 systemUC;
class UC15,UC16,UC17,UC18,UC19,UC20 adminUC;
```


## 8/ Đặc tả use case
### 8.1/ Đặc tả use case Đăng ký tài khoản
| Thành phần | Nội dung | |
| :--- | :--- | :--- |
| **Tên Use Case** | Đăng ký tài khoản | |
| **Tiền điều kiện** | Người dùng chưa có tài khoản trên hệ thống và hệ thống đang hoạt động bình thường. | |
| **Hậu điều kiện** | Tài khoản được tạo thành công và thông tin tài khoản được lưu vào CSDL. Người dùng có thể sử dụng tài khoản để đăng nhập. | |
| **Actor chính** | Khách hàng | |
| **Actor phụ** | Không | |
| **Basic flow** | **Actor (Khách hàng)** | **System (Hệ thống)** |
| | 1. Chọn chức năng “Đăng ký tài khoản” | 2. Hiển thị biểu mẫu đăng ký tài khoản |
| | 3. Nhập họ tên, số điện thoại, email và mật khẩu | 4. Kiểm tra tính hợp lệ của thông tin đăng ký |
| | | 5. Kiểm tra số điện thoại và email chưa được sử dụng |
| | 6. Chọn “Đăng ký” | 7. Hiển thị yêu cầu xác nhận đăng ký |
| | 8. Chọn “Xác nhận” | 9. Tạo tài khoản mới và lưu thông tin |
| | | 10. Hiển thị thông báo “Đăng ký tài khoản thành công” |
| | | 11. Kết thúc Use Case |
| **Alternative flow** | **6.1 Khách hàng hủy đăng ký:** Khách hàng chọn “Hủy” → Hệ thống không tạo tài khoản → Quay về màn hình trước đó.<br>**8.1 Khách hàng hủy xác nhận:** Khách hàng chọn “Hủy” → Hệ thống không lưu thông tin đăng ký → Giữ nguyên biểu mẫu → Quay lại bước 6. | |
| **Exception** | **4.1 Thông tin đăng ký không hợp lệ:** Hệ thống phát hiện thông tin chưa đầy đủ hoặc sai định dạng → Thông báo lỗi → Khách hàng nhập lại thông tin → Quay lại bước 3.<br>**5.1 Số điện thoại hoặc email đã tồn tại:** Hệ thống phát hiện thông tin đã được sử dụng → Thông báo lỗi → Khách hàng nhập thông tin khác → Quay lại bước 3. | |

### 8.2/ Đặc tả use case Đăng nhập
| Thành phần | Nội dung | |
| :--- | :--- | :--- |
| **Tên Use Case** | Đăng nhập | |
| **Tiền điều kiện** | Người dùng đã có tài khoản và tài khoản đang ở trạng thái được phép đăng nhập. | |
| **Hậu điều kiện** | Người dùng đăng nhập thành công, hệ thống xác định vai trò và quyền truy cập, sau đó hiển thị giao diện phù hợp. | |
| **Actor chính** | Khách hàng / Tài xế / Nhân viên vận hành / Ban giám đốc | |
| **Actor phụ** | Không | |
| **Basic flow** | **Actor** | **System (Hệ thống)** |
| | 1. Chọn chức năng “Đăng nhập” | 2. Hiển thị biểu mẫu đăng nhập |
| | 3. Nhập số điện thoại/email và mật khẩu | 4. Kiểm tra tính hợp lệ của thông tin đăng nhập |
| | 5. Chọn “Đăng nhập” | 6. Xác thực tài khoản |
| | | 7. Xác định vai trò và quyền truy cập |
| | | 8. Tạo phiên đăng nhập |
| | | 9. Hiển thị giao diện phù hợp với vai trò |
| | | 10. Kết thúc Use Case |
| **Alternative flow** | **5.1 Người dùng hủy đăng nhập:** Người dùng chọn “Hủy” → Hệ thống không thực hiện đăng nhập → Quay về màn hình trước đó. | |
| **Exception** | **6.1 Thông tin đăng nhập không chính xác:** Hệ thống phát hiện thông tin không chính xác → Hiển thị thông báo lỗi → Người dùng nhập lại thông tin → Quay lại bước 3.<br>**6.2 Tài khoản bị khóa:** Hệ thống phát hiện tài khoản bị khóa → Thông báo tài khoản không được phép đăng nhập → Kết thúc Use Case. | |


### 8.3/ Đặc tả use case Cập nhật hồ sơ
| Thành phần | Nội dung | |
| :--- | :--- | :--- |
| **Tên Use Case** | Cập nhật hồ sơ | |
| **Tiền điều kiện** | Khách hàng hoặc tài xế đã đăng nhập thành công. | |
| **Hậu điều kiện** | Thông tin hồ sơ mới được lưu thành công vào CSDL và hiển thị thông tin mới trên hệ thống. | |
| **Actor chính** | Khách hàng / Tài xế | |
| **Actor phụ** | Không | |
| **Basic flow** | **Actor (Khách hàng / Tài xế)** | **System (Hệ thống)** |
| | 1. Chọn chức năng “Hồ sơ cá nhân” | 2. Hiển thị thông tin hồ sơ hiện tại |
| | 3. Chọn “Cập nhật hồ sơ” | 4. Hiển thị biểu mẫu cập nhật hồ sơ |
| | 5. Chỉnh sửa thông tin cần thay đổi | 6. Kiểm tra tính hợp lệ của thông tin |
| | 7. Chọn “Lưu” | 8. Hiển thị yêu cầu xác nhận cập nhật |
| | 9. Chọn “Xác nhận” | 10. Lưu thông tin hồ sơ mới |
| | | 11. Hiển thị thông báo “Cập nhật hồ sơ thành công” |
| | | 12. Kết thúc Use Case |
| **Alternative flow** | **9.1 Người dùng hủy cập nhật:** Người dùng chọn “Hủy” → Hệ thống không lưu thông tin mới → Giữ nguyên thông tin hồ sơ → Quay lại bước 2. | |
| **Exception** | **6.1 Thông tin hồ sơ không hợp lệ:** Hệ thống phát hiện thông tin không đúng định dạng hoặc chưa đầy đủ → Hiển thị thông báo lỗi → Người dùng nhập lại thông tin → Quay lại bước 5. | |

### 8.4/ Đặc tả use case Cập nhật thông tin phương tiện
| Thành phần | Nội dung | |
| :--- | :--- | :--- |
| **Tên Use Case** | Cập nhật thông tin phương tiện | |
| **Tiền điều kiện** | Tài xế hoặc nhân viên vận hành đã đăng nhập và có quyền cập nhật thông tin phương tiện. | |
| **Hậu điều kiện** | Thông tin phương tiện được cập nhật thành công và lưu vào CSDL. | |
| **Actor chính** | Tài xế | |
| **Actor phụ** | Nhân viên vận hành | |
| **Basic flow** | **Actor (Tài xế / Nhân viên vận hành)** | **System (Hệ thống)** |
| | 1. Chọn chức năng “Thông tin phương tiện” | 2. Hiển thị danh sách phương tiện |
| | 3. Chọn phương tiện cần cập nhật | 4. Hiển thị thông tin chi tiết phương tiện |
| | 5. Chọn “Cập nhật” | 6. Hiển thị biểu mẫu cập nhật |
| | 7. Nhập hoặc chỉnh sửa thông tin phương tiện | 8. Kiểm tra tính hợp lệ của thông tin |
| | 9. Chọn “Lưu” | 10. Hiển thị yêu cầu xác nhận |
| | 11. Chọn “Xác nhận” | 12. Lưu thông tin phương tiện |
| | | 13. Hiển thị thông báo “Cập nhật thông tin phương tiện thành công” |
| | | 14. Kết thúc Use Case |
| **Alternative flow** | **11.1 Actor hủy cập nhật:** Actor chọn “Hủy” → Hệ thống không lưu thông tin mới → Giữ nguyên thông tin phương tiện → Quay lại bước 4. | |
| **Exception** | **8.1 Thông tin phương tiện không hợp lệ:** Hệ thống phát hiện thông tin không đầy đủ hoặc sai định dạng → Thông báo lỗi → Actor nhập lại thông tin → Quay lại bước 7.<br>**8.2 Biển số xe đã tồn tại:** Hệ thống phát hiện biển số đã được đăng ký cho phương tiện khác → Thông báo lỗi → Actor nhập lại biển số → Quay lại bước 7. | |

### 8.5/ Đặc tả use case Đặt xe
| Thành phần | Nội dung | |
| :--- | :--- | :--- |
| **Tên Use Case** | Đặt xe | |
| **Tiền điều kiện** | Khách hàng đã đăng nhập thành công và dịch vụ đặt xe đang hoạt động. | |
| **Hậu điều kiện** | Yêu cầu đặt xe được tạo thành công. Hệ thống bắt đầu tìm và phân công tài xế, đồng thời cập nhật trạng thái cho khách hàng. | |
| **Actor chính** | Khách hàng | |
| **Actor phụ** | Không | |
| **Basic flow** | **Actor (Khách hàng)** | **System (Hệ thống)** |
| | 1. Chọn chức năng “Đặt xe” | 2. Hiển thị giao diện đặt xe |
| | 3. Nhập điểm đón và điểm đến | 4. Kiểm tra thông tin địa điểm |
| | 5. Chọn loại dịch vụ/loại xe | 6. Hiển thị thông tin chuyến và cước dự kiến |
| | 7. Kiểm tra thông tin đặt xe | 8. Hiển thị yêu cầu xác nhận đặt xe |
| | 9. Chọn “Xác nhận đặt xe” | 10. Tạo yêu cầu đặt xe |
| | | 11. Thực hiện UC06 – Tìm và phân công tài xế |
| | | 12. Hiển thị trạng thái tìm tài xế |
| | | 13. Gửi thông báo cho khách hàng khi có kết quả phân công |
| | | 14. Kết thúc Use Case |
| **Alternative flow** | **7.1 Khách hàng thay đổi thông tin đặt xe:** Khách hàng chỉnh sửa điểm đón, điểm đến hoặc loại xe → Hệ thống kiểm tra thông tin mới → Tính lại cước dự kiến → Quay lại bước 7.<br>**9.1 Khách hàng hủy đặt xe:** Khách hàng chọn “Hủy” → Hệ thống không tạo yêu cầu đặt xe → Quay về giao diện chính → Kết thúc Use Case. | |
| **Exception** | **4.1 Địa điểm không hợp lệ:** Hệ thống không xác định được điểm đón hoặc điểm đến → Hiển thị thông báo lỗi → Khách hàng nhập lại địa điểm → Quay lại bước 3.<br>**10.1 Không thể tạo yêu cầu đặt xe:** Hệ thống phát hiện lỗi khi lưu yêu cầu → Thông báo lỗi → Khách hàng thực hiện lại thao tác → Quay lại bước 7. | |

### 8.6/ Đặc tả use case Tìm và phân công tài xế
| Thành phần | Nội dung | |
| :--- | :--- | :--- |
| **Tên Use Case** | Tìm và phân công tài xế | |
| **Tiền điều kiện** | Có yêu cầu đặt xe hợp lệ và hệ thống có thông tin tài xế đang hoạt động. | |
| **Hậu điều kiện** | Nếu tìm được tài xế: yêu cầu được gửi đến tài xế phù hợp và chuyến được phân công khi tài xế chấp nhận. Nếu không tìm được: khách hàng được thông báo không có tài xế phù hợp. | |
| **Actor chính** | Hệ thống | |
| **Actor phụ** | Tài xế | |
| **Basic flow** | **Actor (Tài xế)** | **System (Hệ thống)** |
| | | 1. Tiếp nhận yêu cầu tìm tài xế |
| | | 2. Xác định các tài xế đang sẵn sàng nhận chuyến |
| | | 3. Lọc các tài xế phù hợp theo vị trí, trạng thái và loại xe |
| | | 4. Xác định tài xế phù hợp theo tiêu chí phân công |
| | | 5. Gửi yêu cầu nhận chuyến cho tài xế |
| | | 6. Hiển thị yêu cầu chuyến cho tài xế |
| | 7. Nhận yêu cầu và xem thông tin chuyến | 8. Chờ phản hồi của tài xế |
| | 9. Chọn “Nhận chuyến” | 10. Kiểm tra chuyến còn khả dụng |
| | | 11. Gán chuyến cho tài xế |
| | | 12. Cập nhật trạng thái tài xế thành “Đang có chuyến” |
| | | 13. Thông báo kết quả phân công cho khách hàng |
| | | 14. Kết thúc Use Case |
| **Alternative flow** | **9.1 Tài xế chọn “Từ chối”:** Hệ thống ghi nhận tài xế từ chối → Tìm tài xế phù hợp tiếp theo → Gửi yêu cầu cho tài xế tiếp theo → Quay lại bước 6.<br>**8.1 Tài xế không phản hồi:** Hệ thống xác định tài xế hết thời gian phản hồi → Ghi nhận trạng thái “Không phản hồi” → Tìm tài xế tiếp theo → Quay lại bước 5. | |
| **Exception** | **3.1 Không có tài xế phù hợp:** Hệ thống xác định không có tài xế đáp ứng điều kiện → Cập nhật trạng thái yêu cầu → Thông báo cho khách hàng → Kết thúc Use Case.<br>**10.1 Chuyến đã được tài xế khác nhận:** Hệ thống phát hiện chuyến không còn khả dụng → Thông báo cho tài xế → Kết thúc yêu cầu phân công đối với tài xế này. | |

### 8.7/ Đặc tả use case Nhận hoặc từ chối chuyến
| Thành phần | Nội dung | |
| :--- | :--- | :--- |
| **Tên Use Case** | Nhận hoặc từ chối chuyến | |
| **Tiền điều kiện** | Tài xế đã đăng nhập, đang ở trạng thái sẵn sàng nhận chuyến và có yêu cầu chuyến được gửi đến. | |
| **Hậu điều kiện** | Nếu nhận chuyến: chuyến được gán cho tài xế. Nếu từ chối: hệ thống ghi nhận từ chối và tiếp tục tìm tài xế khác. | |
| **Actor chính** | Tài xế | |
| **Actor phụ** | Không | |
| **Basic flow** | **Actor (Tài xế)** | **System (Hệ thống)** |
| | 1. Nhận thông báo có chuyến mới | 2. Hiển thị thông tin chuyến |
| | 3. Xem điểm đón, điểm đến và thông tin chuyến | 4. Hiển thị lựa chọn “Nhận chuyến” và “Từ chối” |
| | 5. Chọn “Nhận chuyến” | 6. Kiểm tra chuyến còn khả dụng |
| | | 7. Gán chuyến cho tài xế |
| | | 8. Cập nhật trạng thái tài xế thành “Đang có chuyến” |
| | | 9. Thông báo cho khách hàng |
| | | 10. Kết thúc Use Case |
| **Alternative flow** | **5.1 Tài xế chọn “Từ chối”:** Hệ thống ghi nhận tài xế từ chối → Cập nhật trạng thái yêu cầu → Thực hiện UC06 để tìm tài xế khác → Kết thúc Use Case. | |
| **Exception** | **6.1 Chuyến đã được tài xế khác nhận:** Hệ thống phát hiện chuyến không còn khả dụng → Thông báo cho tài xế → Cập nhật danh sách chuyến → Kết thúc Use Case. | |

### 8.8/ Đặc tả use case Theo dõi và cập nhật chuyến đi
| Thành phần | Nội dung | |
| :--- | :--- | :--- |
| **Tên Use Case** | Theo dõi và cập nhật chuyến đi | |
| **Tiền điều kiện** | Chuyến đã được tạo, phân công tài xế và tài xế đã nhận chuyến. | |
| **Hậu điều kiện** | Trạng thái chuyến được cập nhật chính xác. Khách hàng có thể theo dõi tiến trình chuyến. Khi hoàn thành, chuyến chuyển sang trạng thái “Hoàn thành”. | |
| **Actor chính** | Tài xế | |
| **Actor phụ** | Khách hàng / Nhân viên vận hành | |
| **Basic flow** | **Actor (Tài xế)** | **System (Hệ thống)** |
| | 1. Nhận chuyến | 2. Cập nhật trạng thái “Đã nhận chuyến” |
| | 3. Di chuyển đến điểm đón | 4. Cập nhật thông tin vị trí và trạng thái chuyến |
| | 5. Chọn “Đã đến điểm đón” | 6. Cập nhật trạng thái “Đã đến điểm đón” |
| | 7. Đón khách | 8. Cập nhật trạng thái “Đã đón khách” |
| | 9. Chọn “Bắt đầu chuyến” | 10. Cập nhật trạng thái “Đang thực hiện chuyến” |
| | 11. Di chuyển đến điểm đến | 12. Cập nhật tiến trình chuyến cho khách hàng |
| | 13. Chọn “Hoàn thành chuyến” | 14. Kiểm tra điều kiện hoàn thành chuyến |
| | | 15. Cập nhật trạng thái “Hoàn thành” |
| | | 16. Thực hiện UC10 – Tính cước chuyến đi |
| | | 17. Gửi thông báo kết quả cho khách hàng |
| | | 18. Kết thúc Use Case |
| **Alternative flow** | **5.1 Tài xế chưa thể đến điểm đón:** Tài xế tiếp tục di chuyển → Hệ thống giữ nguyên trạng thái chuyến → Khi đến điểm đón, quay lại bước 5.<br>**13.1 Tài xế chưa thể hoàn thành chuyến:** Tài xế tiếp tục thực hiện chuyến → Hệ thống giữ nguyên trạng thái “Đang thực hiện chuyến” → Khi đến điểm đến, quay lại bước 13. | |
| **Exception** | **14.1 Không đủ điều kiện hoàn thành chuyến:** Hệ thống phát hiện thông tin chuyến chưa đầy đủ → Hiển thị thông báo lỗi → Tài xế bổ sung thông tin → Quay lại bước 13. | |

### 8.9/ Đặc tả use case Cập nhật vị trí tài xế
| Thành phần | Nội dung | |
| :--- | :--- | :--- |
| **Tên Use Case** | Cập nhật vị trí tài xế | |
| **Tiền điều kiện** | Tài xế đã đăng nhập, cho phép hệ thống truy cập vị trí và đang hoạt động hoặc đang thực hiện chuyến. | |
| **Hậu điều kiện** | Vị trí mới nhất của tài xế được cập nhật. Khách hàng có thể theo dõi vị trí tài xế và hệ thống có dữ liệu để tính ETA. | |
| **Actor chính** | Tài xế | |
| **Actor phụ** | Không | |
| **Basic flow** | **Actor (Tài xế)** | **System (Hệ thống)** |
| | 1. Cho phép hệ thống truy cập vị trí | 2. Xác nhận quyền truy cập vị trí |
| | 3. Bắt đầu hoạt động hoặc thực hiện chuyến | 4. Nhận dữ liệu vị trí từ thiết bị |
| | | 5. Kiểm tra dữ liệu vị trí |
| | | 6. Cập nhật vị trí mới nhất của tài xế |
| | | 7. Tính toán ETA dự kiến |
| | | 8. Cập nhật vị trí và ETA cho khách hàng |
| | | 9. Tiếp tục nhận dữ liệu vị trí trong quá trình hoạt động |
| **Alternative flow** | **1.1 Tài xế chưa cho phép truy cập vị trí:** Hệ thống hiển thị yêu cầu cấp quyền → Tài xế cho phép truy cập → Hệ thống xác nhận quyền → Quay lại bước 3. | |
| **Exception** | **4.1 Không nhận được dữ liệu vị trí:** Hệ thống phát hiện dữ liệu vị trí bị gián đoạn → Ghi nhận trạng thái vị trí không khả dụng → Thông báo cho tài xế → Tiếp tục thử nhận dữ liệu vị trí. | |

### 8.10/ Đặc tả use case Tính cước chuyến đi
| Thành phần | Nội dung | |
| :--- | :--- | :--- |
| **Tên Use Case** | Tính cước chuyến đi | |
| **Tiền điều kiện** | Chuyến có đầy đủ thông tin cần thiết và hệ thống có cấu hình giá áp dụng. | |
| **Hậu điều kiện** | Cước chuyến đi được tính thành công và tổng tiền được lưu vào thông tin chuyến. | |
| **Actor chính** | Hệ thống | |
| **Actor phụ** | Không | |
| **Basic flow** | **Actor** | **System (Hệ thống)** |
| | | 1. Tiếp nhận thông tin chuyến đi |
| | | 2. Xác định loại dịch vụ và bảng giá áp dụng |
| | | 3. Xác định quãng đường và thời gian chuyến đi |
| | | 4. Tính cước theo cấu hình giá hiện hành |
| | | 5. Kiểm tra kết quả tính cước |
| | | 6. Lưu tổng cước vào thông tin chuyến |
| | | 7. Hiển thị tổng cước cho khách hàng |
| | | 8. Kết thúc Use Case |
| **Alternative flow** | **4.1 Hệ thống áp dụng phụ phí:** Hệ thống xác định chuyến thuộc trường hợp áp dụng phụ phí → Tính thêm phụ phí theo cấu hình → Cập nhật lại tổng cước → Quay lại bước 5. | |
| **Exception** | **2.1 Không có bảng giá phù hợp:** Hệ thống không tìm thấy bảng giá → Thông báo không thể tính cước → Không lưu kết quả → Kết thúc Use Case.<br>**5.1 Kết quả tính cước không hợp lệ:** Hệ thống phát hiện kết quả không hợp lệ → Ghi nhận lỗi → Thông báo không thể hoàn tất tính cước → Kết thúc Use Case. | |

### 8.11/ Đặc tả use case Thanh toán chuyến đi
| Thành phần | Nội dung | |
| :--- | :--- | :--- |
| **Tên Use Case** | Thanh toán chuyến đi | |
| **Tiền điều kiện** | Chuyến đã hoàn thành hoặc đủ điều kiện thanh toán và hệ thống đã xác định số tiền cần thanh toán. | |
| **Hậu điều kiện** | Nếu thanh toán thành công: giao dịch được ghi nhận và trạng thái thanh toán được cập nhật “Thành công”. Nếu thất bại: giao dịch được ghi nhận “Thất bại” và khách hàng được thông báo để thực hiện lại theo chính sách. | |
| **Actor chính** | Khách hàng | |
| **Actor phụ** | Nhà cung cấp thanh toán | |
| **Basic flow** | **Actor (Khách hàng)** | **System (Hệ thống)** |
| | 1. Chọn phương thức thanh toán điện tử | 2. Hiển thị số tiền cần thanh toán |
| | 3. Chọn “Thanh toán” | 4. Tạo yêu cầu thanh toán |
| | | 5. Gửi yêu cầu đến nhà cung cấp thanh toán |
| | | 6. Nhà cung cấp thanh toán xử lý giao dịch |
| | | 7. Nhận kết quả giao dịch |
| | | 8. Kiểm tra kết quả thanh toán |
| | | 9. Cập nhật trạng thái thanh toán “Thành công” |
| | | 10. Lưu thông tin giao dịch |
| | | 11. Hiển thị thông báo thanh toán thành công |
| | | 12. Kết thúc Use Case |
| **Alternative flow** | **1.1 Khách hàng chọn thanh toán tiền mặt:** Khách hàng chọn “Tiền mặt” → Hệ thống ghi nhận phương thức thanh toán → Cập nhật trạng thái thanh toán theo quy trình tiền mặt → Kết thúc Use Case.<br>**3.1 Khách hàng hủy thanh toán:** Khách hàng chọn “Hủy” → Hệ thống không gửi yêu cầu thanh toán → Giữ nguyên trạng thái thanh toán → Kết thúc Use Case. | |
| **Exception** | **7.1 Thanh toán thất bại:** Hệ thống nhận kết quả thất bại → Cập nhật trạng thái “Thất bại” → Lưu giao dịch → Thông báo cho khách hàng → Cho phép thanh toán lại theo chính sách.<br>**5.1 Nhà cung cấp thanh toán không phản hồi:** Hệ thống không nhận được kết quả → Ghi nhận giao dịch “Đang xử lý” → Thông báo cho khách hàng → Kết thúc Use Case. | |

### 8.12/ Đặc tả use case Gửi và tiếp nhận thông báo
| Thành phần | Nội dung | |
| :--- | :--- | :--- |
| **Tên Use Case** | Gửi và tiếp nhận thông báo | |
| **Tiền điều kiện** | Có sự kiện cần gửi thông báo, hệ thống có thông tin người nhận và dịch vụ thông báo đang hoạt động. | |
| **Hậu điều kiện** | Thông báo được gửi đến người nhận và kết quả gửi thông báo được ghi nhận vào hệ thống. | |
| **Actor chính** | Hệ thống | |
| **Actor phụ** | Nhà cung cấp thông báo | |
| **Basic flow** | **Actor (Nhà cung cấp thông báo)** | **System (Hệ thống)** |
| | | 1. Phát sinh sự kiện cần gửi thông báo |
| | | 2. Xác định nội dung và người nhận |
| | | 3. Tạo yêu cầu gửi thông báo |
| | | 4. Gửi yêu cầu đến nhà cung cấp thông báo |
| | 5. Tiếp nhận yêu cầu gửi thông báo | 6. Chờ kết quả gửi thông báo |
| | 7. Thực hiện gửi thông báo | 8. Nhận kết quả gửi thông báo |
| | | 9. Lưu kết quả gửi thông báo |
| | | 10. Cập nhật trạng thái thông báo |
| | | 11. Kết thúc Use Case |
| **Alternative flow** | **7.1 Hệ thống thực hiện gửi lại thông báo:** Hệ thống phát hiện thông báo chưa được gửi thành công → Tạo yêu cầu gửi lại → Nhà cung cấp tiếp nhận → Hệ thống cập nhật kết quả gửi. | |
| **Exception** | **8.1 Nhà cung cấp thông báo không phản hồi:** Hệ thống không nhận được kết quả gửi → Ghi nhận trạng thái “Không xác định” → Ghi log sự kiện → Kết thúc Use Case. | |

### 8.13/ Đặc tả use case Xem lịch sử chuyến đi
| Thành phần | Nội dung | |
| :--- | :--- | :--- |
| **Tên Use Case** | Xem lịch sử chuyến đi | |
| **Tiền điều kiện** | Khách hàng đã đăng nhập thành công. | |
| **Hậu điều kiện** | Danh sách lịch sử chuyến đi được hiển thị và khách hàng có thể xem chi tiết các chuyến đã thực hiện. | |
| **Actor chính** | Khách hàng | |
| **Actor phụ** | Không | |
| **Basic flow** | **Actor (Khách hàng)** | **System (Hệ thống)** |
| | 1. Chọn chức năng “Lịch sử chuyến đi” | 2. Truy xuất lịch sử chuyến đi |
| | | 3. Hiển thị danh sách các chuyến đi |
| | 4. Chọn điều kiện lọc nếu cần | 5. Lọc danh sách theo điều kiện |
| | 6. Chọn một chuyến muốn xem | 7. Hiển thị thông tin chi tiết chuyến đi |
| | | 8. Kết thúc Use Case |
| **Alternative flow** | **4.1 Khách hàng không sử dụng bộ lọc:** Hệ thống giữ nguyên danh sách lịch sử → Khách hàng chọn chuyến cần xem → Quay lại bước 6. | |
| **Exception** | **2.1 Không có lịch sử chuyến đi:** Hệ thống không tìm thấy chuyến đi → Hiển thị thông báo “Chưa có lịch sử chuyến đi” → Kết thúc Use Case. | |

### 8.14/ Đặc tả use case Đánh giá tài xế
| Thành phần | Nội dung | |
| :--- | :--- | :--- |
| **Tên Use Case** | Đánh giá tài xế | |
| **Tiền điều kiện** | Khách hàng đã đăng nhập, chuyến đi đã hoàn thành và chuyến chưa được đánh giá. | |
| **Hậu điều kiện** | Đánh giá được lưu thành công và liên kết với chuyến đi và tài xế. | |
| **Actor chính** | Khách hàng | |
| **Actor phụ** | Không | |
| **Basic flow** | **Actor (Khách hàng)** | **System (Hệ thống)** |
| | 1. Chọn chuyến đã hoàn thành | 2. Kiểm tra chuyến đủ điều kiện đánh giá |
| | 3. Chọn “Đánh giá tài xế” | 4. Hiển thị biểu mẫu đánh giá |
| | 5. Chọn mức đánh giá và nhập nhận xét nếu cần | 6. Kiểm tra thông tin đánh giá |
| | 7. Chọn “Gửi đánh giá” | 8. Hiển thị yêu cầu xác nhận |
| | 9. Chọn “Xác nhận” | 10. Lưu đánh giá |
| | | 11. Hiển thị thông báo “Đánh giá thành công” |
| | | 12. Kết thúc Use Case |
| **Alternative flow** | **9.1 Khách hàng hủy đánh giá:** Khách hàng chọn “Hủy” → Hệ thống không lưu đánh giá → Quay lại thông tin chuyến → Kết thúc Use Case. | |
| **Exception** | **6.1 Mức đánh giá không hợp lệ:** Hệ thống phát hiện chưa chọn mức đánh giá → Hiển thị thông báo lỗi → Khách hàng chọn lại mức đánh giá → Quay lại bước 5.<br>**10.1 Không thể lưu đánh giá:** Hệ thống phát hiện lỗi khi lưu → Thông báo lỗi → Khách hàng thực hiện lại → Quay lại bước 7. | |

### 8.15/ Đặc tả use case Tra cứu và cập nhật thông tin đối tượng
| Thành phần | Nội dung | |
| :--- | :--- | :--- |
| **Tên Use Case** | Tra cứu và cập nhật thông tin đối tượng | |
| **Tiền điều kiện** | Nhân viên vận hành đã đăng nhập và có quyền thực hiện chức năng. | |
| **Hậu điều kiện** | Thông tin khách hàng, tài xế hoặc phương tiện được tra cứu/cập nhật thành công. Các thay đổi được lưu vào CSDL và ghi nhận lịch sử. | |
| **Actor chính** | Nhân viên vận hành | |
| **Actor phụ** | Không | |
| **Basic flow** | **Actor (Nhân viên vận hành)** | **System (Hệ thống)** |
| | 1. Chọn chức năng “Thông tin đối tượng” | 2. Hiển thị các loại đối tượng: khách hàng, tài xế, phương tiện |
| | 3. Chọn loại đối tượng cần tra cứu | 4. Hiển thị danh sách tương ứng |
| | 5. Nhập điều kiện tìm kiếm | 6. Tìm kiếm và hiển thị kết quả |
| | 7. Chọn đối tượng cần xem | 8. Hiển thị thông tin chi tiết |
| | 9. Chọn “Cập nhật” nếu cần | 10. Hiển thị biểu mẫu chỉnh sửa |
| | 11. Chỉnh sửa thông tin | 12. Kiểm tra tính hợp lệ của dữ liệu |
| | 13. Chọn “Lưu” | 14. Hiển thị yêu cầu xác nhận |
| | 15. Chọn “Xác nhận” | 16. Lưu thông tin mới |
| | | 17. Ghi nhận lịch sử thay đổi |
| | | 18. Hiển thị thông báo cập nhật thành công |
| | | 19. Kết thúc Use Case |
| **Alternative flow** | **5.1 Nhân viên không nhập điều kiện tìm kiếm:** Hệ thống hiển thị danh sách đối tượng theo mặc định → Nhân viên chọn đối tượng cần xem → Quay lại bước 7.<br>**15.1 Nhân viên hủy cập nhật:** Nhân viên chọn “Hủy” → Hệ thống không lưu thông tin mới → Giữ nguyên dữ liệu hiện tại → Quay lại bước 8. | |
| **Exception** | **6.1 Không tìm thấy đối tượng:** Hệ thống không tìm thấy dữ liệu phù hợp → Hiển thị thông báo “Không tìm thấy dữ liệu” → Nhân viên nhập lại điều kiện → Quay lại bước 5.<br>**12.1 Thông tin cập nhật không hợp lệ:** Hệ thống phát hiện thông tin không hợp lệ → Hiển thị thông báo lỗi → Nhân viên chỉnh sửa → Quay lại bước 11. | |

### 8.16/ Đặc tả use case Hỗ trợ và xử lý chuyến
| Thành phần | Nội dung | |
| :--- | :--- | :--- |
| **Tên Use Case** | Hỗ trợ và xử lý chuyến | |
| **Tiền điều kiện** | Nhân viên vận hành đã đăng nhập và có chuyến đang hoạt động hoặc phát sinh vấn đề cần hỗ trợ. | |
| **Hậu điều kiện** | Vấn đề của chuyến được xử lý hoặc ghi nhận. Kết quả xử lý và lịch sử hỗ trợ được lưu vào hệ thống. | |
| **Actor chính** | Nhân viên vận hành | |
| **Actor phụ** | Khách hàng / Tài xế | |
| **Basic flow** | **Actor (Nhân viên vận hành)** | **System (Hệ thống)** |
| | 1. Chọn chức năng “Hỗ trợ và xử lý chuyến” | 2. Hiển thị danh sách chuyến đang hoạt động/cần hỗ trợ |
| | 3. Tìm kiếm chuyến cần xử lý | 4. Hiển thị thông tin chuyến |
| | 5. Kiểm tra tình trạng chuyến | 6. Hiển thị thông tin khách hàng, tài xế và trạng thái chuyến |
| | 7. Chọn phương án xử lý | 8. Kiểm tra quyền thực hiện thao tác |
| | 9. Xác nhận xử lý | 10. Cập nhật trạng thái chuyến |
| | | 11. Ghi nhận nội dung xử lý |
| | | 12. Gửi thông báo cho bên liên quan nếu cần |
| | | 13. Kết thúc Use Case |
| **Alternative flow** | **7.1 Nhân viên chỉ ghi nhận sự cố:** Nhân viên nhập nội dung sự cố → Hệ thống lưu thông tin sự cố → Giữ nguyên trạng thái chuyến → Kết thúc Use Case.<br>**9.1 Nhân viên hủy xử lý:** Nhân viên chọn “Hủy” → Hệ thống không thay đổi trạng thái chuyến → Giữ nguyên thông tin hiện tại → Kết thúc Use Case. | |
| **Exception** | **8.1 Nhân viên không có quyền xử lý:** Hệ thống phát hiện không có quyền → Từ chối thao tác → Hiển thị thông báo lỗi → Ghi log → Kết thúc Use Case.<br>**10.1 Không thể cập nhật trạng thái chuyến:** Hệ thống phát hiện lỗi → Không lưu thay đổi → Thông báo lỗi → Nhân viên thực hiện lại → Quay lại bước 7. | |

### 8.17/ Đặc tả use case Tra cứu giao dịch
| Thành phần | Nội dung | |
| :--- | :--- | :--- |
| **Tên Use Case** | Tra cứu giao dịch | |
| **Tiền điều kiện** | Nhân viên vận hành đã đăng nhập và có quyền tra cứu giao dịch. | |
| **Hậu điều kiện** | Thông tin giao dịch phù hợp được hiển thị và nhân viên có thể xem chi tiết giao dịch. | |
| **Actor chính** | Nhân viên vận hành | |
| **Actor phụ** | Không | |
| **Basic flow** | **Actor (Nhân viên vận hành)** | **System (Hệ thống)** |
| | 1. Chọn chức năng “Tra cứu giao dịch” | 2. Hiển thị giao diện tìm kiếm giao dịch |
| | 3. Nhập mã giao dịch, mã chuyến hoặc khoảng thời gian | 4. Kiểm tra điều kiện tìm kiếm |
| | 5. Chọn “Tìm kiếm” | 6. Truy xuất dữ liệu giao dịch |
| | | 7. Hiển thị danh sách kết quả |
| | 8. Chọn giao dịch cần xem | 9. Hiển thị thông tin chi tiết giao dịch |
| | | 10. Kết thúc Use Case |
| **Alternative flow** | **5.1 Nhân viên thay đổi điều kiện tìm kiếm:** Nhân viên nhập lại điều kiện → Hệ thống thực hiện tìm kiếm theo điều kiện mới → Quay lại bước 7. | |
| **Exception** | **6.1 Không tìm thấy giao dịch:** Hệ thống không tìm thấy giao dịch phù hợp → Hiển thị thông báo “Không tìm thấy giao dịch” → Nhân viên nhập lại điều kiện → Quay lại bước 3.<br>**6.2 Lỗi truy xuất dữ liệu:** Hệ thống phát hiện lỗi → Hiển thị thông báo lỗi → Ghi nhận lỗi vào log → Kết thúc Use Case. | |

### 8.18/ Đặc tả use case Xem báo cáo hoạt động
| Thành phần | Nội dung | |
| :--- | :--- | :--- |
| **Tên Use Case** | Xem báo cáo hoạt động | |
| **Tiền điều kiện** | Ban giám đốc hoặc nhân viên vận hành đã đăng nhập, có quyền xem báo cáo và hệ thống có dữ liệu hoạt động. | |
| **Hậu điều kiện** | Báo cáo được tổng hợp và hiển thị, bao gồm các chỉ số về chuyến đi, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả tài xế. | |
| **Actor chính** | Ban giám đốc | |
| **Actor phụ** | Nhân viên vận hành | |
| **Basic flow** | **Actor (Ban giám đốc / Nhân viên vận hành)** | **System (Hệ thống)** |
| | 1. Chọn chức năng “Báo cáo hoạt động” | 2. Hiển thị các loại báo cáo |
| | 3. Chọn loại báo cáo cần xem | 4. Hiển thị bộ điều kiện lọc |
| | 5. Chọn khoảng thời gian và điều kiện cần thiết | 6. Tổng hợp dữ liệu theo điều kiện |
| | 7. Chọn “Xem báo cáo” | 8. Hiển thị báo cáo |
| | 9. Xem các chỉ số báo cáo | 10. Hiển thị dữ liệu tương ứng |
| | | 11. Kết thúc Use Case |
| **Alternative flow** | **5.1 Actor thay đổi điều kiện báo cáo:** Actor thay đổi khoảng thời gian hoặc điều kiện lọc → Hệ thống tổng hợp lại dữ liệu → Quay lại bước 7. | |
| **Exception** | **6.1 Không có dữ liệu phù hợp:** Hệ thống không tìm thấy dữ liệu → Hiển thị thông báo “Không có dữ liệu phù hợp” → Actor thay đổi điều kiện → Quay lại bước 5.<br>**6.2 Lỗi tổng hợp dữ liệu:** Hệ thống phát hiện lỗi → Thông báo không thể tạo báo cáo → Ghi nhận lỗi → Kết thúc Use Case. | |

### 8.19/ Đặc tả use case Phân quyền người dùng
| Thành phần | Nội dung | |
| :--- | :--- | :--- |
| **Tên Use Case** | Phân quyền người dùng | |
| **Tiền điều kiện** | Nhân viên vận hành đã đăng nhập và có quyền thực hiện chức năng phân quyền. | |
| **Hậu điều kiện** | Quyền của người dùng được cập nhật thành công, hệ thống áp dụng quyền mới và ghi nhận lịch sử thay đổi quyền. | |
| **Actor chính** | Nhân viên vận hành | |
| **Actor phụ** | Không | |
| **Basic flow** | **Actor (Nhân viên vận hành)** | **System (Hệ thống)** |
| | 1. Chọn chức năng “Phân quyền người dùng” | 2. Hiển thị danh sách người dùng và vai trò |
| | 3. Chọn người dùng cần phân quyền | 4. Hiển thị quyền hiện tại |
| | 5. Chọn vai trò hoặc quyền cần cấp/thay đổi | 6. Kiểm tra quyền của nhân viên thực hiện |
| | 7. Chọn “Lưu” | 8. Hiển thị yêu cầu xác nhận thay đổi quyền |
| | 9. Chọn “Xác nhận” | 10. Cập nhật quyền người dùng |
| | | 11. Ghi nhận lịch sử thay đổi quyền |
| | | 12. Hiển thị thông báo “Phân quyền thành công” |
| | | 13. Kết thúc Use Case |
| **Alternative flow** | **9.1 Nhân viên hủy thay đổi quyền:** Nhân viên chọn “Hủy” → Hệ thống không cập nhật quyền → Giữ nguyên quyền hiện tại → Kết thúc Use Case. | |
| **Exception** | **6.1 Nhân viên không có quyền phân quyền:** Hệ thống phát hiện nhân viên không có quyền → Từ chối thao tác → Hiển thị thông báo lỗi → Ghi nhận sự kiện vào log → Kết thúc Use Case.<br>**10.1 Không thể cập nhật quyền:** Hệ thống phát hiện lỗi khi lưu → Không cập nhật quyền mới → Hiển thị thông báo lỗi → Nhân viên thực hiện lại → Quay lại bước 5. | |

### 8.20/ Đặc tả use case Thiết lập cấu hình hệ thống
| Thành phần | Nội dung | |
| :--- | :--- | :--- |
| **Tên Use Case** | Thiết lập cấu hình hệ thống | |
| **Tiền điều kiện** | Nhân viên vận hành đã đăng nhập và có quyền cấu hình hệ thống. | |
| **Hậu điều kiện** | Cấu hình mới được lưu thành công, hệ thống áp dụng cấu hình mới và ghi nhận lịch sử thay đổi cấu hình. | |
| **Actor chính** | Nhân viên vận hành | |
| **Actor phụ** | Không | |
| **Basic flow** | **Actor (Nhân viên vận hành)** | **System (Hệ thống)** |
| | 1. Chọn chức năng “Thiết lập cấu hình hệ thống” | 2. Hiển thị các nhóm cấu hình |
| | 3. Chọn nhóm cấu hình cần thay đổi | 4. Hiển thị các giá trị cấu hình hiện tại |
| | 5. Nhập giá trị cấu hình mới | 6. Kiểm tra tính hợp lệ của giá trị |
| | 7. Chọn “Lưu” | 8. Hiển thị yêu cầu xác nhận thay đổi |
| | 9. Chọn “Xác nhận” | 10. Lưu cấu hình mới |
| | | 11. Áp dụng cấu hình mới theo quy định |
| | | 12. Ghi nhận lịch sử thay đổi cấu hình |
| | | 13. Hiển thị thông báo “Cập nhật cấu hình thành công” |
| | | 14. Kết thúc Use Case |
| **Alternative flow** | **9.1 Nhân viên hủy thay đổi cấu hình:** Nhân viên chọn “Hủy” → Hệ thống không lưu cấu hình mới → Giữ nguyên cấu hình hiện tại → Kết thúc Use Case. | |
| **Exception** | **6.1 Giá trị cấu hình không hợp lệ:** Hệ thống phát hiện giá trị không nằm trong phạm vi cho phép → Hiển thị thông báo lỗi → Nhân viên nhập lại giá trị → Quay lại bước 5.<br>**10.1 Không thể lưu cấu hình:** Hệ thống phát hiện lỗi khi lưu → Không áp dụng cấu hình mới → Hiển thị thông báo lỗi → Nhân viên thực hiện lại → Quay lại bước 7. | |

## 9/ Phân tích quy trình nghiệp vụ (Business Project)
![Business Project](BusinessProject.jpg)

```mermaid
flowchart TD

%% =========================================================
%% GIAO ĐOẠN QUY TRÌNH (STAGES)
%% =========================================================
subgraph STAGES["PHÂN TÍCH QUY TRÌNH NGHIỆP VỤ (BUSINESS PROJECT) - CAB SYSTEM"]
direction LR
    ST1["1. ĐẶT XE"]
    ST2["2. TÌM VÀ PHÂN CÔNG TÀI XẾ"]
    ST3["3. THỰC HIỆN CHUYẾN ĐI"]
    ST4["4. THANH TOÁN"]
    ST5["5. HOÀN THÀNH & ĐÁNH GIÁ"]
    ST1 ---> ST2 ---> ST3 ---> ST4 ---> ST5
end

%% =========================================================
%% SWIMLANES (LÀN TÁC NHÂN)
%% =========================================================

%% 1. KHÁCH HÀNG
subgraph LANE_CUSTOMER["👤 KHÁCH HÀNG"]
    direction LR
    N1_1["1.1 Đăng ký/Đăng nhập"]
    N1_2["1.2 Nhập thông tin đặt xe<br/>(điểm đón, điểm đến, loại xe)"]
    N1_3["1.3 Xem tài xế được gợi ý<br/>và thời gian dự kiến"]
    N1_4["1.4 Hủy chuyến<br/>(nếu cần)"]
    N1_5["1.5 Theo dõi vị trí tài xế<br/>và trạng thái chuyến"]
    N1_10["1.10 Thanh toán chuyến đi"]
    N1_11["1.11 Xem lịch sử chuyến"]
    N1_12["1.12 Đánh giá tài xế"]
end

%% 2. TÀI XẾ
subgraph LANE_DRIVER["🚘 TÀI XẾ"]
    direction LR
    N2_1["2.1 Nhận yêu cầu chuyến"]
    N2_2{"2.2 Chấp nhận chuyến?"}
    N2_3["2.3 Từ chối chuyến"]
    N2_4["2.4 Nhận chuyến"]
    N2_5["2.5 Di chuyển tới điểm đón"]
    N2_6_1["2.6 Đón khách"]
    N2_6_2["2.6 Di chuyển tới điểm đến"]
    N2_7["2.7 Hoàn thành chuyến"]
    N2_9["2.9 Cập nhật trạng thái<br/>chuyến và vị trí"]
end

%% 3. NHÂN VIÊN VẬN HÀNH
subgraph LANE_OPERATOR["🎧 NHÂN VIÊN VẬN HÀNH"]
    direction LR
    N3_1["3.1 Hỗ trợ tìm tài xế<br/>khi hệ thống không tìm được"]
    N3_2["3.2 Theo dõi chuyến đi,<br/>trạng thái tài xế"]
    N3_3["3.3 Xử lý sự cố, hỗ trợ<br/>khách hàng/tài xế"]
    N3_4["3.4 Tra cứu giao dịch,<br/>kiểm tra thanh toán"]
end

%% 4. BAN GIÁM ĐỐC
subgraph LANE_BOARD["📊 BAN GIÁM ĐỐC"]
    direction LR
    N4_1["4.1 Xem báo cáo hoạt động<br/>(doanh thu, số chuyến, tỷ lệ hoàn thành, hủy...)"]
end

%% =========================================================
%% LUỒNG NGHIỆP VỤ & LIÊN KẾT (FLOWS & CONNECTIONS)
%% =========================================================

%% Làn Khách hàng
N1_1 --> N1_2
N1_2 -.-> N2_1
N1_3 -.-> N1_4
N1_10 --> N1_11
N1_10 --> N1_12

%% Làn Tài xế
N2_1 --> N2_2
N2_2 -- "Không" --> N2_3
N2_2 -- "Có" --> N2_4
N2_3 -.-> N3_1
N2_4 -.-> N1_3
N2_4 --> N2_5
N2_5 --> N2_6_1
N2_6_1 --> N2_6_2
N2_6_2 --> N2_7

%% Cập nhật vị trí & trạng thái
N2_5 -.-> N2_9
N2_6_1 -.-> N2_9
N2_6_2 -.-> N2_9
N2_9 -.-> N1_5

%% Làn Nhân viên Vận hành
N3_1 -.-> N1_3
N3_2 --> N3_3
N2_9 -.-> N3_2
N2_7 -.-> N3_4
N1_10 -.-> N3_4

%% Làn Ban Giám đốc
N2_7 -.-> N4_1
N1_12 -.-> N4_1

%% Chuyển giao qua Thanh toán
N2_7 -.-> N1_10

%% =========================================================
%% STYLES & COLORS
%% =========================================================
classDef stageStyle fill:#f1f3f4,stroke:#5f6368,stroke-width:1px,color:#202124,font-weight:bold;
classDef custStyle fill:#e8f0fe,stroke:#4285f4,stroke-width:1.5px,color:#174ea6;
classDef drivStyle fill:#e6f4ea,stroke:#34a853,stroke-width:1.5px,color:#0d652d;
classDef operStyle fill:#f3e8fd,stroke:#9333ea,stroke-width:1.5px,color:#581c87;
classDef boardStyle fill:#fef7e0,stroke:#fbbc04,stroke-width:1.5px,color:#b06000;

class ST1,ST2,ST3,ST4,ST5 stageStyle;
class N1_1,N1_2,N1_3,N1_4,N1_5,N1_10,N1_11,N1_12 custStyle;
class N2_1,N2_2,N2_3,N2_4,N2_5,N2_6_1,N2_6_2,N2_7,N2_9 drivStyle;
class N3_1,N3_2,N3_3,N3_4 operStyle;
class N4_1 boardStyle;
```


## 10/ Phân tích quy tắc nghiệp vụ (Business Rules)
| ID | Business Rule | Mô tả |
|---|---|---|
| **BUS-R01** | Đăng nhập trước khi sử dụng chức năng | Người dùng phải đăng nhập và được xác thực trước khi sử dụng các chức năng yêu cầu tài khoản. |
| **BUS-R02** | Thông tin đặt xe bắt buộc | Yêu cầu đặt xe phải có tối thiểu **điểm đón, điểm đến và loại xe/dịch vụ**. |
| **BUS-R03** | Chuyến đi phải có trạng thái | Mỗi chuyến đi phải có trạng thái để phản ánh quá trình xử lý, như: Đang tìm tài xế, Đã nhận, Đang thực hiện, Hoàn thành, Đã hủy. |
| **BUS-R04** | Chỉ tài xế phù hợp mới được nhận chuyến | Tài xế phải đang **sẵn sàng nhận chuyến**, có phương tiện hợp lệ và phù hợp với loại dịch vụ được yêu cầu. |
| **BUS-R05** | Ưu tiên tài xế phù hợp và gần điểm đón | Hệ thống ưu tiên tài xế dựa trên vị trí và các tiêu chí vận hành do doanh nghiệp quy định. |
| **BUS-R06** | Tài xế phải phản hồi yêu cầu chuyến | Tài xế phải chấp nhận hoặc từ chối yêu cầu trong thời gian quy định. |
| **BUS-R07** | Từ chối hoặc không phản hồi thì tìm tài xế khác | Khi tài xế từ chối hoặc không phản hồi, hệ thống tiếp tục tìm tài xế phù hợp khác mà không yêu cầu khách hàng đặt lại chuyến. |
| **BUS-R08** | Không tìm được tài xế phải thông báo | Nếu không tìm được tài xế phù hợp, hệ thống phải thông báo rõ ràng cho khách hàng. |
| **BUS-R09** | Một chuyến chỉ được phân công cho một tài xế | Tại một thời điểm, một chuyến chỉ được xác nhận cho một tài xế. |
| **BUS-R10** | Trạng thái chuyến phải tuân theo trình tự | Chuyến đi phải được cập nhật theo trình tự nghiệp vụ hợp lệ: **Đã nhận → Đã đến điểm đón → Đã đón khách → Đang di chuyển → Hoàn thành**. |
| **BUS-R11** | Chỉ tài xế được phân công mới được cập nhật chuyến | Chỉ tài xế được hệ thống phân công mới có quyền cập nhật trạng thái của chuyến tương ứng. |
| **BUS-R12** | Sử dụng vị trí tài xế trong quá trình vận hành | Hệ thống sử dụng vị trí mới nhất của tài xế để hỗ trợ phân công, theo dõi chuyến và cung cấp thời gian dự kiến đến cho khách hàng. |
| **BUS-R13** | Chuyến hoàn thành mới xác định cước cuối cùng | Cước cuối cùng được xác định dựa trên thông tin thực tế của chuyến sau khi chuyến hoàn thành. |
| **BUS-R14** | Cước phụ thuộc vào loại dịch vụ và thông tin chuyến | Số tiền phải trả được tính dựa trên loại dịch vụ và các thông tin liên quan của chuyến theo chính sách giá của doanh nghiệp. |
| **BUS-R15** | Chỉ sử dụng phương thức thanh toán được hỗ trợ | Khách hàng chỉ được sử dụng các phương thức thanh toán đã được doanh nghiệp cấu hình và cho phép. |
| **BUS-R16** | Không lưu thông tin thanh toán nhạy cảm | CAB không lưu trực tiếp thông tin nhạy cảm của thẻ/tài khoản; thanh toán điện tử được xử lý thông qua nhà cung cấp thanh toán bên ngoài. |
| **BUS-R17** | Giao dịch thanh toán phải có trạng thái | Mỗi giao dịch phải được ghi nhận trạng thái như: **Chờ xử lý, Thành công, Thất bại**. |
| **BUS-R18** | Thanh toán thất bại phải được thông báo | Khi thanh toán điện tử thất bại, hệ thống phải thông báo cho khách hàng và cho phép thực hiện lại theo chính sách. |
| **BUS-R19** | Gửi thông báo khi có sự kiện quan trọng | Hệ thống phải thông báo các sự kiện quan trọng như tài xế nhận chuyến, tài xế đến điểm đón, chuyến hoàn thành và kết quả thanh toán. |
| **BUS-R20** | Lỗi dịch vụ thông báo không làm dừng nghiệp vụ chính | Khi dịch vụ thông báo gặp lỗi, các chức năng cốt lõi như đặt xe và xử lý chuyến vẫn phải tiếp tục hoạt động trong phạm vi cho phép. |
| **BUS-R21** | Truy cập chức năng theo quyền | Người dùng và nhân viên vận hành chỉ được truy cập các chức năng và dữ liệu phù hợp với quyền được cấp. |
| **BUS-R22** | Dữ liệu và thao tác quan trọng phải được bảo vệ, lưu vết | Thông tin cá nhân, phương tiện, vị trí và giao dịch phải được bảo vệ; các thao tác quan trọng phải được ghi nhận để phục vụ kiểm tra và xử lý sự cố. |
| **BUS-R23** | Chỉ đánh giá sau khi chuyến hoàn thành | Khách hàng chỉ được đánh giá tài xế đối với chuyến đã hoàn thành và mỗi chuyến chỉ có một đánh giá của khách hàng. |
| **BUS-R24** | Dữ liệu báo cáo phải dựa trên dữ liệu thực tế | Báo cáo về số chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả tài xế phải được tổng hợp từ dữ liệu chuyến và giao dịch thực tế. |
| **BUS-R25** | Dữ liệu và dịch vụ phải có khả năng mở rộng | Hệ thống phải hỗ trợ mở rộng dịch vụ, phương thức thanh toán và nhà cung cấp thông báo trong tương lai mà hạn chế ảnh hưởng đến các chức năng cốt lõi. |
