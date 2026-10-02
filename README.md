# MT5 Manager — quản lý nhiều tài khoản MT5 trên một màn hình · MIỄN PHÍ

**MT5 Manager** là công cụ trên Windows giúp bạn theo dõi và điều khiển **nhiều tài khoản MetaTrader 5 cùng lúc**: một bảng cho mọi số dư, equity, lãi lỗ và vị thế; đặt lệnh hàng loạt; copy lệnh giữa các tài khoản; quản lý vốn tự động; và điều khiển từ xa bằng điện thoại.

> 🎁 **Miễn phí cho cộng đồng** — đăng ký một tài khoản tradingauto.org là dùng được, **không cần key**.

### 👉 [Tải bản mới nhất](https://github.com/xahoapro/mt5manager-releases/releases/latest) · [Đăng ký tài khoản](https://tradingauto.org/register) · [Giới thiệu tool](https://tradingauto.org/toolintroduce/mt5manager) · [Hướng dẫn cài đặt](https://tradingauto.org/guilde/mt5manager)

---

## ✨ Tính năng

**📊 Một bảng cho tất cả**
- Số dư, equity, lãi lỗ, vị thế đang mở của mọi tài khoản — cập nhật khoảng mỗi giây.
- Không giới hạn số tài khoản MT5. App tự nhân bản terminal cho từng tài khoản và chạy ẩn.
- Thấy ngay EA đang gắn, symbol và khung thời gian trên từng tài khoản.

**🎯 Quản lý lệnh**
- Đặt lệnh hàng loạt cho nhiều tài khoản cùng lúc.
- Đóng một phần (giữ nguyên magic và comment), đặt SL/TP theo giá hoặc theo số tiền.
- Tự dời hoà vốn (break-even) và trailing stop.
- Lọc nhanh theo lời / lỗ, symbol, magic.

**🔁 Copy lệnh nội bộ**
- Tài khoản nguồn → nhiều tài khoản đích trên cùng máy, kể cả **khác sàn** (tự khớp tên symbol).
- Copy chéo giữa nhiều máy cài MT5 Manager.

**🛡️ Quản lý vốn**
- Ngưỡng lỗ trong ngày, sụt giảm từ đỉnh, mức margin.
- Ba mức phản ứng: chỉ cảnh báo · đóng hết lệnh · đóng hết và tắt tài khoản. Ghi nhật ký đầy đủ.

**🤖 EA & tool có sẵn**
- Gắn EA hàng loạt cho nhiều tài khoản (symbol, khung, file cài đặt).
- Kho tool của hệ thống (Smart DCA, TradePanel…) cài sẵn vào mọi terminal và tự cập nhật.
- Nút **Chỉnh cài đặt MT5** để lưu URL WebRequest, quyền EA… mà không bị mất khi bật lại.

**📡 Tín hiệu**
- **TradingView → MT5**: nhận alert TradingView vào lệnh tự động; tạo sẵn nội dung message cho alert ngay trong app.
- **VIPTREND**: nhận tín hiệu theo kênh.
- Tài khoản demo và tài khoản thuộc danh sách IB dùng miễn phí bằng key `vipmember`.

**📱 Điều khiển từ xa**
- Bảng điều khiển riêng tại `service.tradingauto.org/<tên-của-bạn>` — mở bằng điện thoại ở bất cứ đâu, không cần mở cổng router.
- Bảo mật nhiều lớp: mật khẩu riêng, mã 2 bước (Google Authenticator), mật khẩu **chỉ xem** để chia sẻ cho người theo dõi, tự chặn IP dò mật khẩu, tự đăng xuất khi bỏ không.
- **Thiết bị tin cậy**: máy / điện thoại của riêng bạn vào thẳng, không cần gõ mật khẩu; mỗi lần vào đều báo Telegram.

**📈 Thống kê & cảnh báo**
- Lãi lỗ theo ngày, tháng, thứ trong tuần; biểu đồ luỹ kế; xuất CSV.
- Cảnh báo Telegram gửi thẳng từ máy của bạn.

## 🚀 Bắt đầu trong 3 bước

1. **[Đăng ký tài khoản tradingauto.org](https://tradingauto.org/register)** — miễn phí, không cần key.
2. **[Tải bộ cài](https://github.com/xahoapro/mt5manager-releases/releases/latest)**: tải file `MT5Manager-<phiên bản>-setup.zip`, giải nén vào một thư mục (vd `C:\MT5Manager`), chạy `MT5Manager.exe`.
3. **Đăng nhập** bằng tài khoản vừa đăng ký → **+ Thêm tài khoản** (số tài khoản MT5, mật khẩu, server) → app tự dựng terminal và kết nối.

Xem hướng dẫn chi tiết từng bước: **[tradingauto.org/guilde/mt5manager](https://tradingauto.org/guilde/mt5manager)**

## 💻 Yêu cầu

- Windows 10 / 11 (Windows Server 2012 R2 trở lên cũng chạy được).
- Đã cài MetaTrader 5 trên máy — MT5 Manager điều khiển terminal thật, không thay thế nó.
- Máy phải bật và có mạng thì app mới làm việc (dùng VPS Windows để chạy 24/7).

## 🔄 Cập nhật

App tự báo khi có bản mới, bấm là tải và cài. Gói cập nhật được ký số — app chỉ nhận bản chính thức.
Các file `MT5Manager-<phiên bản>-update.zip` trong mục Releases là gói cho cơ chế tự cập nhật — khách mới hãy tải file **`-setup.zip`**.

## 💬 Hỗ trợ & cộng đồng

- Website: **[tradingauto.org](https://tradingauto.org)**
- Nhóm Zalo: [zalo.me/g/scuqhg283](https://zalo.me/g/scuqhg283) · Nhóm Telegram: [t.me/autotradingfreeall](https://t.me/autotradingfreeall)
- Các tool khác: [Copytrade Online](https://tradingauto.org/toolintroduce/copytrade) · [TradingView → MT5](https://tradingauto.org/toolintroduce/tradingview) · [Smart DCA](https://tradingauto.org/toolintroduce/dcabot) · [Copy Signal → MT5](https://tradingauto.org/toolintroduce/signaltrader)

> ⚠️ MT5 Manager là công cụ quản lý — **không dự đoán thị trường và không bảo đảm lợi nhuận**. Giao dịch ngoại hối / CFD có rủi ro cao.

---

## 🇬🇧 English

**MT5 Manager** is a free Windows tool to monitor and control **many MetaTrader 5 accounts at once**: one dashboard for every balance, equity, P/L and open position; batch orders; copy trading between accounts (even across brokers); automatic money management; TradingView → MT5 signals; and remote control from your phone at `service.tradingauto.org/<your-name>` with password, 2-step verification and trusted devices.

**Get started:** [register a free tradingauto.org account](https://tradingauto.org/register) → [download the latest `-setup.zip`](https://github.com/xahoapro/mt5manager-releases/releases/latest), unzip, run `MT5Manager.exe` → sign in with your account and add your MT5 accounts. Requires Windows 10/11 and MetaTrader 5. [Introduction](https://tradingauto.org/toolintroduce/mt5manager) · [Install guide](https://tradingauto.org/guilde/mt5manager)

This repository only hosts release builds — it contains no source code. © [tradingauto.org](https://tradingauto.org)
