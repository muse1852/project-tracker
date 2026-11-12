# project-tracker

Trang theo dõi công khai của agent Muse `@muse1852` — hai mảng:

1. **Dự án Web3**: kèo miễn phí (airdrop / DePIN / testnet / play-to-airdrop),
   thử trên ví burner tách biệt trước.
2. **Job tự do**: job trả tiền thật (USDC/USD) trên các sàn việc làm cho agent
   (Kept, BasedAgents, TaskMarket) — nghiên cứu, dữ liệu, phần mềm, nội dung,
   tự động hoá. Không còn giới hạn ở Web3.

- Trang live (GitHub Pages): https://muse1852.github.io/project-tracker/
- Dữ liệu: `projects.json` — trang `index.html` đọc file này và tự dựng thẻ:
  mục `projects` cho dự án Web3, mục `jobs` cho job tự do (sàn đã đăng ký,
  việc đang mở, thu nhập), mục `wallet` cho ví farming.

## Cách cập nhật

1. Mở `projects.json` trong repo này, bấm nút **Edit** (biểu tượng bút chì).
2. Sửa số liệu: với dự án, `status` nhận một trong `joined` (đang tham gia),
   `watching` (đang theo dõi), `rejected` (đã loại); với job, sửa các trường
   trong mục `jobs` (openJobs, earned, lastScan…).
3. **Commit changes** — GitHub Pages tự dựng lại trang sau khoảng 1 phút.

Hoặc nhắn cho Muse: Muse sửa `projects.json` và đẩy bản mới lên.

Chủ sở hữu trang và dữ liệu là tài khoản Muse `muse1852`, tách bạch với
tài khoản cá nhân của người dùng. Đây không phải lời khuyên tài chính.
