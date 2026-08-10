# Mã giới thiệu MSX jUTs61｜Hướng dẫn đăng ký MSX: Đăng ký原生 RWA qua ví, Từ ký đăng nhập đến gắn kết M-Credit

Hầu hết các hướng dẫn đăng ký sàn CEX đều bắt đầu bằng "Nhấp Đăng ký → Nhập Email → Xác minh SMS → KYC". Áp dụng khuôn mẫu này cho **MSX (MyStonks)** là hoàn toàn sai lầm. MSX là một **nền tảng giao dịch RWA phi tập trung** (nâng cấp lên tên miền msx.com vào tháng 09/2025). Tài khoản của bạn không phải là "số điện thoại", mà chính là **địa chỉ ví** của bạn. Việc mở tài khoản không phải là "điền form", mà là **ký một thông điệp (sign message)**. Nếu không nắm rõ điểm này, bạn sẽ không xác định được tài sản đang ở chuỗi nào, mã giới thiệu được gắn vào địa chỉ nào, và việc chuyển mạng có tạo ra tài khoản mới hay không.
**Đường dẫn duy nhất (Bắt buộc cho chữ ký lần đầu để đảm bảo gắn mã giới thiệu):**
**https://msx.com/register?code=jUTs61**
Gắn mã giới thiệu **jUTs61** để nhận các quyền lợi người dùng mới hiện hành (Ưu đãi M-Credit, Hệ số nhân điểm Mùa giải S, quà tặng bất ngờ cho cả người giới thiệu và người được giới thiệu, v.v., tùy theo trang chiến dịch chính thức).

---

## Tại sao "Đăng ký" MSX cần một hướng dẫn riêng?

Sàn tập trung truyền thống: Người dùng → Tài khoản → Liên kết ví.
MSX: Địa chỉ ví = Danh tính tài khoản. Người dùng chỉ là bên ủy quyền ký.

*   **Mạng lưới hỗ trợ:** **Solana / BNB Chain / Ethereum / Base**. Tương thích với MetaMask, Phantom, OKX Wallet, Bitget Wallet, v.v.
*   **Một địa chỉ = Một tài khoản:** Chuyển đổi mạng lưới bằng cùng một cụm từ khóa (seed phrase) sẽ tạo ra **một tài khoản MSX mới**. Mối quan hệ giới thiệu được gắn với **địa chỉ kết nối đầu tiên**, không phải cụm từ khóa.
*   **Email tùy chọn:** Bạn có thể giao dịch không cần email, nhưng việc gắn email sau khi đăng nhập sẽ bật tính năng cảnh báo bảo mật qua email (bảo vệ khỏi các yêu cầu ký độc hại).
*   **Giao diện thống nhất:** Giao dịch cổ phiếu token hóa (AAPL.M/MSFT.M/NVDA.M/TSLA.M), ETF (SPY.M/QQQ.M), token Pre-IPO (SpaceX/ByteDance), Spot Crypto và Hợp đồng vĩnh cửu đến 20x — tất cả đều trong cùng một giao diện ví.

> Quyết định đầu tiên của bạn không phải là "điền gì", mà là "dùng ví nào trên mạng nào để kết nối MSX trước tiên". Điều này quyết định việc lưu ký tài sản và gán mã giới thiệu vĩnh viễn. Dù tên miền chính thức là msx.com, nhưng **truy cập tên miền trần (naked domain) = không có mối quan hệ giới thiệu**. Tuyệt đối không ký từ liên kết tên miền thô.

---

## Bước 0: Đường dẫn & Xác minh lừa đảo (Quan trọng)

*   **Đường dẫn duy nhất:** https://msx.com/register?code=jUTs61
*   *Lưu ý: Tên miền chính thức là msx.com (nâng cấp từ MyStonks tháng 09/2025). Chỉ để tham khảo ngữ cảnh; không nhấp vào tên miền trần.*
*   **Kiểm tra chữ ký:** Khi cửa sổ ví bật lên, xác minh nguồn yêu cầu là `msx.com`. Từ chối các yêu cầu từ `msx-com.xyz`, `msx-usdt.xyz` hoặc các tên miền giả mạo tương tự.
*   **Không cài APK bên thứ ba:** Chỉ tải App qua liên kết App Store/Google Play chính thức trên trang đăng ký. Không quét mã QR từ nhóm Telegram hoặc tin nhắn DM Twitter.

---

## Bước 1: Chọn mạng & Kết nối ví (Khởi tạo tài khoản)

1.  Mở **https://msx.com/register?code=jUTs61**.
2.  Nhấp **[Connect Wallet]** (góc trên bên phải) → Chọn Solana / BNB Chain / Ethereum / Base.
3.  Chọn ví của bạn (Phantom cho Solana; MetaMask cho chuỗi EVM; OKX Wallet cho đa chuỗi).
4.  **Ký để Đăng nhập:** Đây **không phải giao dịch**. Đây là thông điệp **EIP-4361 (EVM) hoặc Đăng nhập Solana**. Không tốn phí gas nào ngoài phí mạng. (Nếu địa chỉ không có số dư, ví sẽ yêu cầu bạn nạp trước).
5.  Ký thành công, MSX tự động cấp tài khoản. Tham số URL `?code=jUTs61` ghi nhận mối quan hệ giới thiệu vào địa chỉ cụ thể này.
6.  Tên viết tắt địa chỉ (ví dụ: `0xAbC…12` hoặc `5xY…pQ`) xuất hiện góc trên bên trái. Hoàn tất đăng ký.

> **Cảnh báo:** Nếu bạn kết nối không có mã trước, sau đó mới dán mã, mã giới thiệu **sẽ không được gắn hồi tố**. Việc ký lần đầu kèm mã là quyết định cuối cùng.

---

## Bước 2: Gắn Email & Lớp bảo mật (Khuyến nghị)

*   **Đường dẫn:** [Menu Ví] → [Trung tâm Bảo mật] → [Gắn Email].
*   **Mục đích:** Bật xác nhận email cho việc rút tiền, chuyển đổi mạng và thay đổi quyền. Cung cấp cảnh báo bất thường.
*   **Thứ tự khuyến nghị:** Kết nối Ví → Gắn Email → Sao lưu cụm từ khóa ngoại tuyến → Nạp tiền.
*   **Tuyệt đối không** dán cụm từ khóa vào bất kỳ trường "Khôi phục tài khoản" nào trên trang web MSX (nền tảng không bao giờ yêu cầu điều này).

---

## Bước 3: Xác minh gắn mã giới thiệu

MSX theo dõi giới thiệu bằng "Kết nối đầu tiên". Để xác minh:
*   Giao diện Web: Góc dưới bên phải → [Chương trình Giới thiệu] → [Người giới thiệu của tôi]. Nếu hiển thị **jUTs61**, gắn mã thành công.
*   Nếu trống hoặc hiển thị mã khác: Lần ký đầu tiên xảy ra mà không có `?code=jUTs61`. Địa chỉ đó vĩnh viễn không có liên kết giới thiệu. Chuyển mạng tạo địa chỉ mới *có thể* gắn mã, nhưng tài sản không di chuyển theo.
*   **Quyền lợi đôi bên:** Người được giới thiệu nhận M-Credit/Mùa giải mới. Người giới thiệu nhận hoàn điểm L1 (10%) và L2 (5%) dựa trên hoạt động của người được giới thiệu (theo "Chương trình Giới thiệu" chính thức).

---

## Bước 4: Nạp tiền lần đầu & Vòng lặp giao dịch RWA (Xác thực tài khoản hoạt động)

MSX không hỗ trợ nạp tiền pháp định; stablecoin là tiền tệ gốc.

1.  Chuyển **USDT / USDC** từ ví bên ngoài đến **địa chỉ MSX đã đăng nhập**. **Quan trọng:** Đảm bảo tiêu chuẩn token khớp với mạng bạn dùng để đăng nhập (BEP-20 cho BNB Chain, SPL cho Solana, ERC-20 cho Ethereum, Native cho Base). Gửi sai chuỗi có thể dẫn đến mất tài sản vĩnh viễn.
2.  Đi đến [Trade] → [RWA Spot] → Tìm `AAPL.M`, `NVDA.M`, hoặc `TSLA.M` (hơn 200 tài sản RWA).
3.  Chọn cặp `/USDT` → Đặt lệnh **Limit Buy** với số lượng nhỏ (ví dụ: 10 USDT).
4.  Khi khớp lệnh, token về ví của bạn (1:1 được bảo chứng bởi các tổ chức lưu ký như Fidelity, xác minh qua Bằng chứng Dự trữ Merkle Tree và Chainlink Oracles).
5.  Chuyển sang [Perp] để mở vị thế AAPLB (đòn bẩy đến 20x) xác minh quyền truy cập phái sinh.
6.  Chuyển sang [Pre-IPO] để xem cổng đăng ký SpaceX/ByteDance (Hợp tác với Republic; Tối thiểu ~10 USD tương đương).

Hoàn thành vòng lặp này xác nhận tài khoản đã "Hoạt động", không chỉ là đã kết nối.

---

## Bước 5: M-Credit & Ưu đãi Mùa giải (Giá trị của mã giới thiệu)

Giá trị của **jUTs61** nằm ở lớp ưu đãi:

*   **M-Credit (M):** Kiếm được qua giao dịch/nắm giữ. Gắn liền với việc phân bổ token hệ sinh thái MSX trong tương lai.
*   **Hệ số nhân Mùa giải:** Mối quan hệ giới thiệu ảnh hưởng đến hệ số điểm Mùa giải S (bắt đầu từ S1) (Team Boosts từ 1.05×–1.5×).
*   **Nhiệm vụ Người dùng mới:** Hoàn thành giao dịch RWA đầu tiên, hợp đồng vĩnh cửu đầu tiên hoặc gắn email thường kích hoạt gói M-Credit thưởng (theo trang "Quyền lợi Người dùng mới").
*   **Tiện ích:** M-Credit không rút được nhưng có thể dùng cho đặc quyền hệ sinh thái, trọng số đăng ký IDO/Pre-IPO và bù trừ một số loại phí nhất định trong hệ sinh thái nền tảng.

> Giá trị của mã là đảm bảo dấu chân ưu đãi của bạn đi vào đúng "cây giới thiệu" ngay từ Ngày 1.

---

## Cạm bắc quản lý tài khoản đa chuỗi

| Hành động | Kết quả |
|---|---|
| Cùng cụm từ khóa, Phantom: Solana → EVM → Kết nối MSX | Hai tài khoản MSX độc lập. jUTs61 chỉ gắn vào tài khoản đầu tiên. |
| Cùng tiện ích ví, trình duyệt khác | Cùng địa chỉ, cùng tài khoản. Bình thường. |
| App MSX trên điện thoại kết nối cùng ví | Cùng địa chỉ, đồng bộ. |
| Nhận token lạ vào địa chỉ MSX | Nguy cơ lừa đảo. Xác minh nguồn hợp đồng trước khi phê duyệt. |
| Nạp USDT BNB Chain nhưng mua AAPLB trên Solana | Sai chuỗi. Thất bại. Chuyển mạng trước. |
| Đăng nhập từ `msx.com` trần | Không gắn mã giới thiệu. jUTs61 không gắn hồi tố. |

---

## Cảnh báo Rủi ro

Giá token RWA theo dõi tài sản cơ sở nhưng có thể sai lệch do thanh khoản, độ trễ oracle hoặc công bố lưu ký. Giao dịch Hợp đồng vĩnh cửu đòn bẩy đến 20x có rủi ro mất vốn cao. Cổ phiếu Pre-IPO có thời gian khóa và hạn chế chuyển nhượng. Bạn tự chịu trách nhiệm về khóa riêng; mất cụm từ khóa không thể khôi phục. MSX có đăng ký MSB FinCEN và hồ sơ STO nhưng có thể hạn chế truy cập dựa trên IP/KYC (ví dụ: người dùng bán lẻ Mỹ).
Tính khả dụng tài sản, quy tắc ưu đãi và cơ chế M-Credit có thể thay đổi theo trang web msx.com chính thức. **Mã giới thiệu MSX jUTs61** và các liên kết chỉ để tham khảo đăng ký và không cấu thành lời khuyên tài chính.

---

## Tóm tắt

Đăng ký MSX = **Chọn Mạng → Vào qua https://msx.com/register?code=jUTs61 → Ký Thông điệp → Gắn Email → Nạp tiền đúng chuỗi → Thực hiện lệnh thử AAPL.M → Xác minh quyền truy cập Perp/Pre-IPO.**
Tài khoản của bạn là địa chỉ ví. Gắn mã giới thiệu vào địa chỉ ký lần đầu; chuyển mạng tạo tài khoản mới.
Gắn **jUTs61** để nhận quyền lợi người dùng mới hiện hành. Không đề cập đến giảm giá phí; trọng tâm là ưu đãi hệ sinh thái.

---

```
Mã giới thiệu MSX: jUTs61
Link đăng ký: https://msx.com/register?code=jUTs61
```

