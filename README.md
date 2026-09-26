# VCAM Pro v1

MVP dashboard quản lý dịch vụ và tài khoản mạng xã hội.

## Chạy local

Yêu cầu Node.js 18.17+.

```bash
npm install
npm run dev
```

Mở http://localhost:3000

API kiểm tra:
`GET /api/health`

## Cấu trúc

- `app/page.tsx` — Dashboard
- `app/globals.css` — giao diện
- `app/api/health/route.ts` — API mẫu

## Bước tiếp theo

1. PostgreSQL + Prisma
2. Đăng nhập và phân quyền
3. CRUD khách hàng / tài khoản / đơn hàng
4. Audit log
5. Kết nối API chính thức của các nền tảng khi được cấp quyền
6. Triển khai production

Không lưu mật khẩu hoặc token đăng nhập mạng xã hội của khách hàng trong dữ liệu ứng dụng.
