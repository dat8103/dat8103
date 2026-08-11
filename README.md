# Đặng Tuấn Đạt

**Backend / Full-stack Engineer** · Hải Phòng, Việt Nam

Tôi xây hệ thống cho doanh nghiệp vừa và nhỏ ở Việt Nam: ERP xưởng may, POS chạy offline cho tạp hoá, nền tảng SaaS cho trung tâm giáo dục, dây chuyền sinh video có AI, agent bảo mật đầu cuối viết bằng C++.

Mã nguồn của những hệ thống này thuộc sở hữu khách hàng nên không công khai được. Thay vào đó, mỗi dự án có một repo công khai **nhân nghiệp vụ chạy được thật** — thuật toán và quy tắc đã tách khỏi hạ tầng, kèm test và một bản demo tương tác chạy thẳng trong trình duyệt.

### ▶ [Trang tổng hợp cả chín dự án](https://dat8103.github.io/portfolio/)

Mở link demo là chạy được ngay, kể cả trên điện thoại. Không cần clone, không cần cài gì.

---

| Dự án | Điểm đáng xem | Demo |
|---|---|---|
| [`kvil-video-automation`](https://github.com/dat8103/kvil-video-automation) | Dây chuyền sinh video **học từ video mẫu**: thư viện motion, chấm điểm QC, bộ nhớ sửa lỗi | [▶](https://dat8103.github.io/kvil-video-automation/) |
| [`dms-endpoint-agent`](https://github.com/dat8103/dms-endpoint-agent) | Agent chống thất thoát dữ liệu, C++ đa nền tảng — mất mạng không được biến thành mở toang | [▶](https://dat8103.github.io/dms-endpoint-agent/) |
| [`eduai-platform`](https://github.com/dat8103/eduai-platform) | SaaS đa tenant, cô lập dữ liệu bằng RLS ở tầng database, BYOK qua Vault | [▶](https://dat8103.github.io/eduai-platform/) |
| [`koisan-ads-ai`](https://github.com/dat8103/koisan-ads-ai) | AI agent tool-use: model **phải gọi công cụ lấy số** trước khi đề xuất ngân sách | [▶](https://dat8103.github.io/koisan-ads-ai/) |
| [`kvil-erp`](https://github.com/dat8103/kvil-erp) | Gom batch sản xuất, nổ định mức, xếp lịch chuyền theo năng lực hữu hạn | [▶](https://dat8103.github.io/kvil-erp/) |
| [`mini-market-pos`](https://github.com/dat8103/mini-market-pos) | POS chạy offline hoàn toàn: công nợ, đơn vị quy đổi, in bill ESC/POS | [▶](https://dat8103.github.io/mini-market-pos/) |
| [`gara-network`](https://github.com/dat8103/gara-network) | Chọn garage đối tác bằng chấm điểm nhiều tiêu chí, quyết toán giữ lại bảo hành | [▶](https://dat8103.github.io/gara-network/) |
| [`vmu-grad-management`](https://github.com/dat8103/vmu-grad-management) | Phân quyền module × hành động × phạm vi, thù lao giảng dạy có vách thuế | [▶](https://dat8103.github.io/vmu-grad-management/) |
| [`internal-ops`](https://github.com/dat8103/internal-ops) | Chuỗi duyệt nhiều cấp theo hạn mức, chấm công GPS, bảng lương | [▶](https://dat8103.github.io/internal-ops/) |

**828 test** trên chín repo, CI chạy trước mỗi lần deploy demo.

---

### Cách tôi viết code

- **Docstring giải thích vì sao, không phải làm gì.** Tên hàm đã nói làm gì rồi — giá trị nằm ở ràng buộc nghiệp vụ, đánh đổi, và cái bẫy đã gặp.
- **Test khoá lại quyết định nghiệp vụ**, không chỉ kiểm tra hàm chạy. Tên test là quy tắc: `'đổi điểm áp dụng SAU giảm giá đơn, không cộng dồn ưu đãi'`.
- **Mỗi repo có `docs/decisions.md`** — đã cân nhắc gì, chọn gì, vì sao, và cái giá phải trả.
- **Đặt tên theo nghiệp vụ tiếng Việt** khi người dùng hệ thống nói tiếng Việt. `gomBatch`, `noDinhMuc`, `tinhQuyetToan` đọc đúng thứ mà người vận hành đang nói.

### Công nghệ

`Node.js` `NestJS` `Laravel` `Spring Boot` `C++` · `React` `Next.js` `TypeScript` · `PostgreSQL` `MySQL` `Redis` · `Claude / Gemini / OpenAI tool-use` · `Docker` `GitHub Actions`

### Liên hệ

📧 dangtuandat8103@gmail.com
