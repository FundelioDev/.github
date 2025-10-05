# <span style="color:red;">🌊 Fundelio — Nền tảng gây quỹ cộng đồng cho startup dựa trên phần thưởng</span>

## <span style="color:red;">📚 Mục lục</span>

1. [<span style="color:red;">Tên dự án và chủ đề</span>](#1-tên-dự-án-và-chủ-đề)
2. [<span style="color:red;">Lý do lựa chọn dự án</span>](#2-lý-do-lựa-chọn-dự-án)
3. [<span style="color:red;">Công nghệ sử dụng</span>](#3-công-nghệ-sử-dụng)
4. [<span style="color:red;">Các tính năng chính</span>](#4-các-tính-năng-chính)
5. [<span style="color:red;">Hướng dẫn sử dụng & Demo</span>](#5-hướng-dẫn-sử-dụng--demo)
6. [<span style="color:red;">Nguyên tắc làm việc</span>](#6-nguyên-tắc-làm-việc)

---

## <span id="1-tên-dự-án-và-chủ-đề" style="color:red;">🚀 1. Tên dự án và chủ đề</span>

### 📌 Ý nghĩa tên **Fundelio**

**Fundelio** là từ ghép mang ý nghĩa rõ và giàu ẩn dụ:

* **Fund**: từ gốc *fundus* (La‑tinh) → **quỹ/nguồn vốn; cấp vốn** (*fund, funding, fundraising*).
* **Elio**: gợi âm **Helios** (Hy Lạp cổ) → **mặt trời/ánh sáng/soi đường**; phổ biến trong các tên Ý/TBN (*Aurelio, Cornelio*).

**Fund + Elio = Fundelio** → *“Nguồn vốn soi sáng con đường khởi nghiệp”*.

### 🎯 Sơ lược về dự án

**Fundelio** là nền tảng gây quỹ cộng đồng cho startup **dựa trên phần thưởng** (crowdfunding):

* Founder tạo **chiến dịch (campaign)** (mục tiêu tiền, thời hạn, nội dung/video, phần thưởng theo bậc).
* Backer **đóng góp/cam kết (pledge)** theo **mức phần thưởng (reward tier)** và **tùy chọn bổ sung (add‑ons)**.
* Nếu **đạt mục tiêu gây quỹ** thì chiến dịch thành công (**trừ 5% phí nền tảng đối với founder**). Nếu **không đạt mục tiêu** thì **hoàn tiền đầy đủ** cho backer.
* Giao diện thân thiện, **cập nhật bảng xếp hạng đóng góp theo thời gian thực**, phân quyền **Founder/Backer/Admin** rõ ràng.

---

## <span id="2-lý-do-lựa-chọn-dự-án" style="color:red;">🔥 2. Lý do lựa chọn dự án</span>

* **Thiết thực và có tác động đối với cộng đồng startup**: Hỗ trợ các ý tưởng sáng tạo nhận nguồn lực từ cộng đồng mà **không cần bán cổ phần**.
* **Tập trung vào minh bạch & tin cậy**: Quy tắc **all-or-nothing** (đạt mục tiêu gây quỹ thì hệ thống mới thu phí backer, founder) + **refund tự động cho backer** khi founder không đạt mục tiêu gây quỹ -> giúp xây dựng niềm tin.
* **Rèn kỹ năng web hiện đại**: Security (Auth JWT, RBAC), Laravel, MySQL, React.js, WebSocket,... và dễ demo trước lớp.

---

## <span id="3-công-nghệ-sử-dụng" style="color:red;">🛠️ 3. Công nghệ sử dụng</span>

### <span style="font-size:18px;">✨ Front-end</span>

<div align="left" style="margin: 15px 0 20px 0; display: flex; flex-wrap: wrap;">
  <img src="https://img.shields.io/badge/-JavaScript-000?style=for-the-badge&logo=javascript" alt="JavaScript" style="margin-right: 19px; margin-bottom: 12px;"/>
  <img src="https://img.shields.io/badge/-React.js-000?style=for-the-badge&logo=react" alt="React.js" style="margin-right: 19px; margin-bottom: 12px;"/>
  <img src="https://img.shields.io/badge/-Tailwind_CSS-000?style=for-the-badge&logo=tailwind-css" alt="Tailwind CSS" style="margin-right: 19px; margin-bottom: 12px;"/>
  <img src="https://img.shields.io/badge/-Axios-000?style=for-the-badge&logo=axios" alt="Axios" style="margin-right: 19px; margin-bottom: 12px;"/>
</div>

---

### <span style="font-size:18px;">🔧 Back-end</span>

<div align="left" style="margin: 15px 0 20px 0; display: flex; flex-wrap: wrap;">
  <img src="https://img.shields.io/badge/-PHP-000?style=for-the-badge&logo=php" alt="PHP" style="margin-right: 19px; margin-bottom: 12px;"/>
  <img src="https://img.shields.io/badge/-Laravel-000?style=for-the-badge&logo=laravel" alt="Laravel" style="margin-right: 19px; margin-bottom: 12px;"/>
  <img src="https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens" alt="Passport JWT" style="margin-right: 19px; margin-bottom: 12px;"/>
  <img src="https://img.shields.io/badge/-Eloquent_ORM-000?style=for-the-badge&logo=laravel" alt="Eloquent ORM" style="margin-right: 19px; margin-bottom: 12px;"/>
  <img src="https://img.shields.io/badge/-MySQL-000?style=for-the-badge&logo=mysql" alt="MySQL" style="margin-right: 19px; margin-bottom: 12px;"/>
</div>

---

### <span style="font-size:18px;">🌐 Others & Deploy</span>

<div align="left" style="margin: 15px 0 20px 0; display: flex; flex-wrap: wrap;">
    <img src="https://img.shields.io/badge/-Git-000?style=for-the-badge&logo=git" alt="Git" style="margin-right: 19px; margin-bottom: 12px;"/>
    <img src="https://img.shields.io/badge/-GitHub-000?style=for-the-badge&logo=github" alt="GitHub" style="margin-right: 19px; margin-bottom: 12px;"/>
    <img src="https://img.shields.io/badge/-Docker-000?style=for-the-badge&logo=docker" alt="Docker" style="margin-right: 19px; margin-bottom: 12px;"/>
    <img src="https://img.shields.io/badge/-GitHub_Actions_CI/CD-000?style=for-the-badge&logo=githubactions" alt="GitHub Actions" style="margin-right: 19px; margin-bottom: 12px;"/>
    <img src="https://img.shields.io/badge/-AWS_EC2-000?style=for-the-badge&logo=AmazonWebServices" alt="AWS EC2" style="margin-right: 19px; margin-bottom: 12px;"/>
    <img src="https://img.shields.io/badge/-AWS_S3-000?style=for-the-badge&logo=AmazonWebServices" alt="AWS S3" style="margin-right: 19px; margin-bottom: 12px;"/>
    <img src="https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white" style="margin-right: 19px; margin-bottom: 12px;"/>
</div>

---

## <span id="4-các-tính-năng-chính" style="color:red;">🎮 4. Các tính năng chính</span>

### 🛡️ Xác thực & Bảo mật *(triển khai với **Laravel Passport JWT**)*

* **Đăng ký tài khoản**: Người dùng đăng ký qua email hoặc số điện thoại; hệ thống gửi email xác thực để kích hoạt tài khoản *(áp dụng cho người dùng từ **18+**)*.
* **Xác thực email**: Sau khi đăng ký, người dùng nhận email xác thực để kích hoạt; hỗ trợ **gửi lại** email khi cần.
* **Đăng nhập**: Đăng nhập bằng email/số điện thoại và mật khẩu để nhận **JWT** truy cập API.
* **Lấy thông tin tài khoản (`Get me`)**: Xem thông tin cá nhân sau khi đăng nhập.
* **Làm mới token (`Get new token`)**: Tự động làm mới JWT khi token hiện tại hết hạn để đảm bảo trải nghiệm liền mạch.
* **Quên/Đặt lại mật khẩu**: Khôi phục mật khẩu qua email bằng liên kết đặt lại.
* **Bảo mật đa tầng**: Dùng **Passport JWT** để bảo vệ API, mã hóa dữ liệu, quản lý quyền truy cập và đảm bảo an toàn thông tin.

---

### 👥 Vai trò người dùng & Phân quyền

* **Founder**: Tạo/chỉnh sửa **campaign** của chính mình, xem thống kê, nhận thông báo pledge.
* **Backer**: Duyệt/tìm kiếm campaign, chọn **Reward tier**, **Add-ons**, sử dụng số dư wallet để pledge, xem lịch sử hỗ trợ.
* **Admin**: Duyệt/từ chối campaign, quản lý người dùng, giám sát thanh toán và thu phí nền tảng.

> Một người dùng có thể có **nhiều vai trò**. Hệ thống luôn **kiểm tra quyền hạn** trước mỗi hành động *(ví dụ: chỉ **Founder** mới có quyền tạo campaign)*.

---

### 📝 **Tạo & Duyệt Campaign**

* Founder bắt đầu bằng việc soạn nội dung giới thiệu chiến dịch qua các đề mục linh hoạt *(ví dụ: "Giới thiệu sản phẩm" với văn bản kết hợp in đậm/màu sắc/kích thước tùy chỉnh, ảnh minh họa, video demo và preview gift để tổng quan về sản phẩm)*, giúp backer hình dung rõ ràng ý tưởng.
* Tiếp theo, founder tạo các mốc reward cho chiến dịch ngay tại bước này: định nghĩa các tier phần thưởng tăng dần theo mức hỗ trợ *(ví dụ: tier cơ bản 10 USD với core item đơn giản, tier nâng cao 20 USD với add-ons tùy chọn, giới hạn số lượng sản xuất để tạo tính khẩn cấp)*, bao gồm mô tả, vận chuyển, thời gian giao, và vật phẩm chính/tùy chọn *(vật phẩm có thể dùng chung giữa các tier để tối ưu hóa)*.
* Founder có thể chọn "Preview" để xem trước toàn bộ trang chiến dịch *(bao gồm layout tab, nội dung, và các mốc reward)* trước khi công khai cho backer thấy.
* Campaign được lưu ở trạng thái chờ duyệt. Admin kiểm tra nội dung phù hợp quy định, sau đó phê duyệt hoặc từ chối kèm lý do.
* Khi được duyệt, campaign xuất hiện trên trang chủ dưới dạng nổi bật hoặc mới nhất, sẵn sàng cho tìm kiếm theo từ khóa hoặc loại.

> Trước khi tạo và công khai chiến dịch, hệ thống sẽ yêu cầu Founder đồng ý với điều khoản/điều kiện thì hệ thống mới thực hiện các bước tiếp theo (vấn đề pháp lý).

### 🔍 **Trang chủ & Tìm kiếm**

* Trang chủ hiển thị danh sách campaign dạng card trực quan: tiêu đề, mô tả ngắn, tiến độ đạt được *(ví dụ: 53.849/10.000 USD)*, số lượng backers *(ví dụ: 145 người)*, thời gian còn lại *(ví dụ: 29 ngày)*, và thumbnail video.
* Hỗ trợ sắp xếp theo ngày tải lên mới nhất, hoặc phổ biến (dựa trên backers).
* Tìm kiếm linh hoạt theo từ khóa *(ví dụ: “guitar pedal”)* hoặc lọc theo loại dự án, giúp người dùng dễ dàng khám phá.

### 📋 **Chi tiết Campaign & Rewards**

* Trang chi tiết campaign được chia thành 3 layout chính: bên trái hiển thị nội dung các mốc reward (danh sách tier với mô tả, giá, và số lượng còn lại), giữa là nội dung chi tiết chiến dịch qua các tab dễ cuộn *(ví dụ: "Giới thiệu dự án" dẫn đến văn bản phong phú với ảnh, video)*, bên phải là mục lục để nhanh chóng nhảy đến phần mong muốn.
* Phần thưởng (reward tiers) được sắp xếp tăng dần theo mức hỗ trợ tối thiểu *(ví dụ: 10 USD cho gói cơ bản, 20 USD cho nâng cao)*.
* Mỗi tier bao gồm: tiêu đề, mô tả, vùng vận chuyển *(ví dụ: toàn cầu)*, thời gian giao ước tính *(ví dụ: Tháng 12/2025)*, và số lượng giới hạn *(ví dụ: 110 gói, còn 36)*.
* Tier cấu thành từ vật phẩm chính (core items, ví dụ: 1 pedal, số lượng cố định không chỉnh sửa) và tùy chọn thêm (add-ons, ví dụ: cáp USB giá 5 USD, chọn từ 0–3 cái).
* Vật phẩm có thể dùng chung giữa các tier; nếu vật phẩm chính hết hàng *(dựa trên số lượng sản xuất founder khai báo)*, toàn bộ tier sẽ bị ẩn hoặc đánh dấu "Hết hàng" để tránh hỗ trợ không thực tế.

### 💳 **Pledge & Quản Lý Số Dư (Wallet)**

* Backer trước tiên cần nạp tiền vào wallet (tài khoản ảo/virtual account của hệ thống qua VNPAY) để có số dư sẵn sàng sử dụng, thay vì nạp trực tiếp cho các mốc reward của chiến dịch *(tương tự nạp coin trong game trước khi mua item)*.
* Backer chọn tier phần thưởng hoặc hỗ trợ thuần túy *(tối thiểu 1 USD)*.
* Kiểm tra số tiền: phải lớn hơn hoặc bằng mức tối thiểu của tier; nếu thấp hơn, hệ thống từ chối và gợi ý tier phù hợp.
* Hỗ trợ vượt mức (over-pledge, ví dụ: chọn 20 USD nhưng dùng 28 USD từ số dư) được chấp nhận, với phần dư coi như ủng hộ thêm cho dự án mà không thay đổi phần thưởng nhận được.
* Thêm add-ons tùy chọn *(ví dụ: 2 cáp = +10 USD)*; tổng số tiền = mức tier + giá trị add-ons.
* Hệ thống kiểm tra số dư wallet của backer có đủ không; nếu đủ, trừ ngay số dư và xác nhận pledge thành công.
* Thành công: Cập nhật tiến độ dự án *(tăng tổng hỗ trợ, số backers +1)*, giảm tồn kho *(core item -1 slot, add-on -số chọn)*, và gửi xác nhận.
* Thất bại (số dư không đủ): Hủy và thông báo để backer nạp thêm.

> Trước khi đóng góp gây quỹ cho startup, hệ thống sẽ yêu cầu Backer đồng ý với điều khoản/điều kiện thì hệ thống mới thực hiện các bước tiếp theo (vấn đề pháp lý).

### ⚡ **Realtime & Thông báo**

* Khi có pledge mới thành công, trang chi tiết cập nhật tức thì: thanh tiến độ % tăng với hiệu ứng animation mượt mà, bảng top 10 backers lớn nhất *(ẩn danh hoặc hiển thị tên, sắp xếp động với hiệu ứng lên/xuống khi thay đổi hạng)*, và popup thông báo "Ai đó vừa hỗ trợ 50 USD!".
* Founder nhận thông báo in-app hoặc email về hỗ trợ mới; backer nhận thông báo cập nhật trạng thái pledge của mình qua lịch sử cá nhân.

### 🏁 **Tổng kết chiến dịch**

* Khi đến ngày kết thúc campaign:
  * Nếu tổng hỗ trợ đạt mục tiêu → thành công: Chuyển số tiền cho founder *(trừ 5% phí nền tảng từ tổng pledged thành công)*.
  * Nếu không đạt → thất bại: Tự động hoàn tiền đầy đủ vào wallet của tất cả backers liên quan *(có thể trừ phí giao dịch nhỏ nếu áp dụng)*.
* Sau thành công, founder theo dõi fulfillment qua dashboard cơ bản *(xem danh sách backers, phần thưởng cần giao)*; nền tảng không quản lý vận chuyển trực tiếp mà chỉ hỗ trợ xuất báo cáo.

---

### ⚙️ Yêu cầu khác *(phi kỹ thuật)*

* **An toàn & tốc độ**: Kiểm tra quyền trước mọi hành động; mã hóa mật khẩu; chống spam *(limit pledge)*, chống lại các cuộc tấn công website thường gặp *(SQL injection, XSS, CSRF, DDoS)*; realtime bảng xếp hạng top 10 và thông báo mượt mà.
* **Giao diện**: **Responsive**, hỗ trợ **vi/eng**, **dark/light mode** *(Darkmode lấy mã màu: #1F1F22 và màu chủ đạo xanh dương #0894E2)*, **Font dùng chung cho toàn bộ website: Source Sans 3** *(https://fonts.google.com/specimen/Source+Sans+3)*, hình ảnh rõ nét, không lỗi chính tả.

---

## <span id="5-hướng-dẫn-sử-dụng--demo" style="color:red;">📽️ 5. Video hướng dẫn sử dụng nền tảng Fundelio</span>

Xem ngay video hướng dẫn sử dụng Fundelio: [https://www.youtube.com/watch?v=_XCsiVHKEoA](https://www.youtube.com/watch?v=_XCsiVHKEoA) 
   
---

## <span id="6-nguyên-tắc-làm-việc" style="color:red;">📏 6. Nguyên tắc làm việc</span>

### 🟢 **Commit Convention (Quy ước khi commit code lên GitHub):**

```
feat:      thêm một feature mới
fix:       sửa lỗi trong hệ thống
refactor:  sửa code mà không thêm tính năng hoặc fix bug
docs:      cập nhật hoặc thay đổi tài liệu
chore:     thay đổi nhỏ, không liên quan đến logic code
style:     thay đổi về giao diện, CSS/UI
perf:      cải thiện hiệu năng xử lý
vendor:    cập nhật phiên bản dependencies, packages
```

### 🔵 **Branch Naming Conventions (Quy ước đặt tên nhánh):**

```
feature/:  dành cho phát triển tính năng mới
bugfix/:   dành cho sửa lỗi

Quy ước:   Tên nhánh ngắn gọn, rõ ràng, không dùng ký tự đặc biệt hay viết hoa.
Ví dụ:     feature/add-friend-functionality, bugfix/chat-not-loading
```

### 🖼️ **Cấu hình Prettier**

```json
"editor.formatOnPaste": false,
"editor.formatOnSave": true,
"editor.defaultFormatter": "esbenp.prettier-vscode",
"prettier.singleQuote": true,
"prettier.semi": true
```

---
