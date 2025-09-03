### **1. Chuẩn bị môi trường**

> 🗂 ** Cài đặt Python và thư viện**

1. Cài **Python 3.8+**
2. Cài thư viện cần thiết:

```bash
pip install eth-account
```

---

### **2. Cấu trúc thư mục**

> 🗂 ** Tổ chức file**

```
/thu_muc_chay/
│-- creat_vi.py          # script tạo ví
```

---

### **3. Chạy script**

> 🗂 ** Tạo ví Ethereum**

```bash
python creat_vi.py
```

* Chương trình sẽ hỏi:

```
How many wallets to create?
```

Nhập số lượng ví bạn muốn tạo, ví dụ `10`.

---

### **4. Kết quả sau khi chạy**

> 🗂 ** File kết quả**

Sau khi chạy, script sẽ tạo ra 3 file:

* `ETH_wallet.txt` – Chứa địa chỉ ví.
* `ETH_Seed.txt` – Chứa seed phrase (câu khôi phục 12 từ).
* `PrivateKey.txt` – Chứa private key (có tiền tố `0x`).

---

### **5. Cấu trúc dữ liệu ví**

Mỗi ví bao gồm:

* **Seed Phrase**: 12 từ dùng để khôi phục ví.
* **Private Key**: Khóa riêng bắt đầu bằng `0x`.
* **Public Address**: Địa chỉ ví Ethereum.

---

### **6. Bảo mật**

> 🗂 ** Cảnh báo bảo mật**

* Không chia sẻ **Seed Phrase** và **Private Key**.
* Chỉ dùng trên **testnet** nếu đang thử nghiệm.
* Nếu dùng mainnet, cần bảo mật nghiêm ngặt.

