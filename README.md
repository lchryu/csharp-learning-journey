# C# Learning Journey

Repo này lưu lại lộ trình dự kiến học C# thực chiến trong 10 buổi. Mục tiêu không chỉ là học cú pháp, mà là mỗi buổi đều có sản phẩm nhỏ để hiểu cách C# được dùng trong console app, desktop app, API, database và web.

Lộ trình này có thể thay đổi trong quá trình học. Kiến thức nào quá khó, quá rộng hoặc chưa cần thiết ở thời điểm hiện tại thì tạm bỏ qua, chỉ ghi chú lại để quay lại sau.

## Mục tiêu dự kiến

Sau 10 buổi, người học có thể:

- Viết C# cơ bản và hiểu flow chương trình.
- Dùng Git để quản lý source code.
- Hiểu OOP, LINQ, clean code và cách tách project.
- Làm CRUD với database (Create, Read, Update, Delete: thêm, xem, sửa, xóa dữ liệu).
- Xây desktop app bằng WPF.
- Viết ASP.NET Core API.
- Kết nối frontend với backend.
- Có nền tảng để học sâu hơn về ASP.NET, Unity hoặc backend development.

## Cách học

- Học nhanh phần lý thuyết cần thiết.
- Code ngay project nhỏ trong từng buổi.
- Commit code sau mỗi phần hoàn thành.
- Ghi lại lỗi gặp phải và cách sửa.
- Dùng AI Agent như một trợ lý học tập, không dùng để chép code mù quáng.
- Nếu phần nào quá phức tạp, ưu tiên hiểu ý tưởng chính và làm được project trước.
- Không bắt buộc học hết tất cả keyword/kỹ thuật trong một buổi.

## Nguyên tắc bỏ qua tạm thời

Một số kiến thức có thể tạm bỏ qua nếu đang làm chậm tiến độ:

- Thuật toán quá nặng hoặc phân tích complexity quá sâu.
- OOP nâng cao nếu chưa hiểu class/object cơ bản.
- Clean Architecture đầy đủ nếu project còn nhỏ.
- JWT/auth nếu chưa viết API CRUD ổn.
- Deploy nếu final project chưa chạy tốt ở local.
- WPF binding nâng cao nếu chưa hiểu event và layout cơ bản.

Khi bỏ qua, chỉ cần ghi chú:

```txt
Tạm bỏ qua: [tên kiến thức]
Lý do: quá khó/chưa cần cho project hiện tại
Sẽ quay lại sau: [buổi hoặc giai đoạn phù hợp]
```

## AI Agent trong repo này

Khuyến khích dùng các AI Agent như:

- Codex CLI
- Gemini CLI
- ChatGPT
- GitHub Copilot
- Các agent hỗ trợ đọc repo, sửa code, giải thích lỗi và viết test

AI Agent có thể hỗ trợ:

- Giải thích khái niệm C# bằng ví dụ ngắn.
- Review code sau mỗi buổi học.
- Gợi ý refactor khi code bắt đầu rối.
- Giải thích lỗi compiler/runtime.
- Sinh bài tập thêm theo đúng level hiện tại.
- Viết README, ghi chú học tập và checklist.
- Hỗ trợ tạo test case cho project.

Mỗi buổi nên có ít nhất một bước dùng AI Agent:

- Trước khi học: hỏi AI tóm tắt kiến thức buổi đó.
- Trong khi code: hỏi AI giải thích lỗi compiler/runtime.
- Sau khi code: nhờ AI review code và đề xuất refactor đơn giản.
- Sau khi xong buổi: nhờ AI tạo bài tập thêm hoặc checklist ôn tập.

Nguyên tắc sử dụng AI:

- Tự viết trước, hỏi AI sau.
- Luôn đọc và hiểu code AI đề xuất.
- Không paste code nếu chưa giải thích lại được.
- Dùng AI để tăng tốc học, không thay thế việc luyện tập.

Ví dụ prompt hữu ích:

```txt
Giải thích lỗi C# này theo cách dễ hiểu cho người mới học.
```

```txt
Review file Program.cs và chỉ ra phần nào nên tách thành function/class.
```

```txt
Tạo thêm 5 bài tập nhỏ về List, Dictionary và class/object trong C#.
```

```txt
Đề xuất cách refactor project Console App này theo clean code.
```

## Lộ trình dự kiến 10 buổi

### Buổi 1 - C# Core và Console App đầu tiên

Học:

- Biến
- Input/output
- `if/else`
- Vòng lặp
- Function
- `List`

Project: Quản lý học sinh Console App

Tính năng:

- Thêm học sinh
- Xem danh sách
- Tìm kiếm
- Xóa học sinh
- Tính điểm trung bình

Bài tập thêm:

- Tính BMI
- Kiểm tra số nguyên tố
- Kiểm tra palindrome
- In bảng cửu chương

Output:

- Viết được console app có menu.
- Biết đọc lỗi cơ bản.
- Bắt đầu biết chia nhỏ logic thành function.

AI Agent:

- Nhờ AI giải thích lỗi C# gặp trong lúc chạy app.
- Nhờ AI review xem function đã tách hợp lý chưa.

### Buổi 2 - Array, String, OOP nhẹ và Git

Học:

- Array
- String
- `Dictionary`
- Class/object cơ bản
- Git cơ bản: `init`, `add`, `commit`, `push`

Project: Quản lý chi tiêu mini

Tính năng:

- Thêm khoản thu/chi
- Tính tổng tiền
- Lọc theo thu/chi
- Lưu dữ liệu bằng `List`

Mini task frontend:

- Làm UI HTML/CSS đơn giản cho Expense Tracker gồm ô nhập, nút add và danh sách dữ liệu.

Output:

- Hiểu class/object.
- Biết commit code lên GitHub.
- Có app quản lý thứ hai.
- Chạm nhẹ vào HTML/CSS.

AI Agent:

- Nhờ AI giải thích class/object bằng ví dụ từ project quản lý chi tiêu.
- Nhờ AI gợi ý message commit rõ ràng.

### Buổi 3 - C# nâng cao nhẹ, LINQ, Lambda và thuật toán cơ bản

Học:

- Complexity cơ bản
- Sorting
- Searching
- Lambda
- LINQ: `Where`, `Select`, `OrderBy`, `FirstOrDefault`, `Any`
- C# nâng cao nhẹ: `var`, nullable, enum, object initializer, exception cơ bản

Tạm bỏ qua nếu quá khó:

- Complexity chi tiết.
- Thuật toán nâng cao.
- LINQ phức tạp nhiều tầng.
- Generic nâng cao.

Project: Expense Analytics

Tính năng:

- Lọc giao dịch
- Tìm top khoản chi
- Thống kê theo tháng
- Sort theo số tiền

Bài tập thuật toán:

- Prime
- Fibonacci
- Max/min
- Frequency count

Output:

- Hiểu cách xử lý data bằng C# hiện đại.
- Biết dùng LINQ để code gọn hơn.

AI Agent:

- Nhờ AI chuyển một đoạn `for` sang LINQ và giải thích từng bước.
- Nhờ AI tạo thêm bài tập về LINQ theo level hiện tại.

### Buổi 4 - OOP, Clean Code và Project Structure

Học:

- Encapsulation
- Inheritance
- Polymorphism
- Abstract class
- Interface
- Naming
- Folder structure
- Service class

Project: Hệ thống nhân vật game

Object mẫu:

- Player
- Enemy
- Boss
- NPC

Tính năng:

- Attack
- HP
- Skill
- Inventory

Output:

- Hiểu OOP thực tế hơn.
- Biết tách logic thay vì viết tất cả trong `Program.cs`.

Tạm bỏ qua nếu quá khó:

- Polymorphism nâng cao.
- Abstract/interface nếu chưa hiểu class/object.
- Design pattern.

AI Agent:

- Nhờ AI review project và gợi ý class nào nên tách ra.
- Nhờ AI giải thích khác nhau giữa abstract class và interface bằng ví dụ đơn giản.

### Buổi 5 - Database, SQL và CRUD

Học:

- SQL cơ bản
- Table
- Relation
- Primary key
- `SELECT`, `INSERT`, `UPDATE`, `DELETE`
- SQLite hoặc SQL Server

Project: Expense Database

Table gợi ý:

- Users
- Transactions
- Categories

Tính năng:

- Thêm giao dịch
- Sửa giao dịch
- Xóa giao dịch
- Lọc theo category

Output:

- Hiểu database dùng để làm gì.
- Biết CRUD dữ liệu thật thay vì chỉ lưu trong RAM.

Tạm bỏ qua nếu quá khó:

- Relation phức tạp.
- Query tối ưu hiệu năng.
- Stored procedure.

AI Agent:

- Nhờ AI giải thích SQL query đang viết.
- Nhờ AI gợi ý schema đơn giản cho project Expense Database.

### Buổi 6 - WPF cơ bản và Desktop App

Học:

- Grid
- StackPanel
- Button
- TextBox
- ListView
- Event: `Click`, `TextChanged`
- Data binding cơ bản

Project: Expense Manager Desktop

Tính năng:

- Thêm giao dịch
- Hiển thị danh sách
- Filter
- Thống kê tổng tiền

Output:

- Làm được desktop app cơ bản bằng C#.
- Hiểu event-driven programming.

Tạm bỏ qua nếu quá khó:

- Data binding nâng cao.
- MVVM đầy đủ.
- Custom control.

AI Agent:

- Nhờ AI giải thích lỗi XAML.
- Nhờ AI gợi ý layout WPF đơn giản, dễ code.

### Buổi 7 - ASP.NET Core API

Học:

- Controller
- Route
- JSON
- Request/response
- HTTP methods: `GET`, `POST`, `PUT`, `DELETE`
- Swagger
- Postman

API cần build:

```txt
GET    /transactions
POST   /transactions
PUT    /transactions/{id}
DELETE /transactions/{id}
```

Output:

- Viết được backend API cơ bản.
- Biết test API bằng Swagger/Postman.

Tạm bỏ qua nếu quá khó:

- Middleware nâng cao.
- Filter pipeline.
- Hosting/deploy API.

AI Agent:

- Nhờ AI giải thích route/controller/action.
- Nhờ AI review API endpoint đã đúng REST cơ bản chưa.

### Buổi 8 - Web Frontend nhẹ và Connect API

Học:

- HTML
- CSS
- JavaScript cơ bản
- `fetch`
- `async/await`
- JSON

Project: Expense Tracker Web

Tính năng:

- Gọi API
- Render danh sách giao dịch
- Thêm transaction
- Xóa transaction

Output:

- Hiểu frontend và backend giao tiếp với nhau như thế nào.

Tạm bỏ qua nếu quá khó:

- Framework frontend như React/Vue.
- State management nâng cao.
- UI quá phức tạp.

AI Agent:

- Nhờ AI giải thích lỗi `fetch`.
- Nhờ AI tạo HTML/CSS đơn giản để test API.

### Buổi 9 - Auth, JWT và Clean Architecture

Học:

- Login/register
- JWT
- Authorize
- DTO
- Dependency Injection
- Exception handling

Architecture gợi ý:

```txt
Controller
Service
Repository
Database
```

Output:

- Backend giống project thật hơn.
- Biết tách layer và bảo vệ API bằng auth.

Tạm bỏ qua nếu quá khó:

- Refresh token.
- Role/permission phức tạp.
- Clean Architecture quá đầy đủ.

AI Agent:

- Nhờ AI giải thích JWT flow bằng sơ đồ chữ.
- Nhờ AI review cách tách Controller, Service, Repository.

### Buổi 10 - Final Project và Deploy

Final project: Family Expense Manager

Tính năng:

- Login/register
- CRUD giao dịch
- Analytics
- Filter
- Tag theo người dùng
- Database
- Backend API
- Web frontend hoặc desktop app

Deploy gợi ý:

- Azure
- Render
- Railway

Output cuối khóa:

- Có một project hoàn chỉnh để demo.
- Hiểu flow fullstack cơ bản.
- Có nền tảng để học ASP.NET sâu hơn, học Unity hoặc đi theo hướng backend intern.

Tạm bỏ qua nếu quá khó:

- Deploy production đầy đủ.
- CI/CD.
- Monitoring/logging nâng cao.

AI Agent:

- Nhờ AI review toàn bộ project final.
- Nhờ AI tạo checklist bug cần sửa trước khi demo.
- Nhờ AI viết README cho final project.

## Cấu trúc repo đề xuất

```txt
csharp-learning-journey/
├── buoi-01-console-core/
├── buoi-02-oop-git/
├── buoi-03-linq-lambda/
├── buoi-04-oop-clean-code/
├── buoi-05-database-crud/
├── buoi-06-wpf-desktop/
├── buoi-07-aspnet-api/
├── buoi-08-web-connect-api/
├── buoi-09-auth-jwt/
├── buoi-10-final-project/
└── README.md
```

## Checklist mỗi buổi

- Đọc mục tiêu buổi học.
- Code project chính.
- Làm ít nhất 1 bài tập thêm.
- Commit code lên Git.
- Ghi lại lỗi hoặc điều mới học.
- Nhờ AI Agent review lại code và tự sửa phần chưa ổn.
- Ghi chú phần nào đã tạm bỏ qua và lý do.
