# NOVA TECH — Thực hành Tuần 5 & Tuần 6

Sinh viên: Huỳnh Tấn Tài — MSSV: 2274802010764  
Môn học: Lập trình Web nâng cao — Văn Lang University

Repository này lưu **mã nguồn của hai bài thực hành** ở dạng tệp ZIP tải xuống. Mỗi tệp chứa mã nguồn, README hướng dẫn chạy và các tệp cần thiết; hãy giải nén để xem các thư mục dự án.

| Bài thực hành | Công nghệ | Tải mã nguồn |
| --- | --- | --- |
| Tuần 5 — Website bán hàng NOVA TECH | ExpressJS, MongoDB, EJS, Session, Postman | [SourceCode_Tuan5_Express_MongoDB_EJS.zip](./SourceCode_Tuan5_Express_MongoDB_EJS.zip) |
| Tuần 6 — Website bán hàng NOVA TECH | ReactJS, ExpressJS REST API, MongoDB, giỏ hàng | [SourceCode_Tuan6_ReactJS_Express_MongoDB.zip](./SourceCode_Tuan6_ReactJS_Express_MongoDB.zip) |

## Tuần 5 — Cách chạy

1. Tải ZIP Tuần 5, giải nén và mở thư mục `Code_Tuan5_NOVA_TECH/backend`.
2. Sao chép `.env.example` thành `.env` và cấu hình `MONGO_URI`, `SESSION_SECRET` trên máy riêng.
3. Chạy `npm install`, `npm run seed` (lần đầu), rồi `npm start`.
4. Mở `http://localhost:3000/products`.
5. Có bộ Postman ở `postman/Tuan5_CRUD_Cart.postman_collection.json` để kiểm tra API `/api/products`.

## Tuần 6 — Cách chạy

1. Tải ZIP Tuần 6, giải nén.
2. Terminal thứ nhất: vào `Code_Tuan6_NOVA_TECH/backend`, tạo `.env` từ `.env.example`, chạy `npm install`, `npm run seed` (nếu database chưa có dữ liệu), `npm start`.
3. Terminal thứ hai: vào `Code_Tuan6_NOVA_TECH/frontend-react`, chạy `npm install` và `npm run dev`.
4. Mở `http://localhost:5173/products`.

**Lưu ý:** `.env` và `node_modules` không nằm trong các ZIP; tuyệt đối không đăng thông tin đăng nhập MongoDB hoặc SESSION_SECRET thật lên GitHub.

**Cách nộp:** Mỗi báo cáo Word có link repository này và link tới đúng ZIP của bài. Các file ZIP tải xuống chứa source để giảng viên giải nén, kiểm tra và chạy; mã nguồn chưa được bung ra thành file thư mục trực tiếp trên trang GitHub.
