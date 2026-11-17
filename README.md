# AN TOPLAP – Website bán linh kiện máy tính

Website tĩnh HTML5/CSS3 giới thiệu cửa hàng linh kiện RAM, SSD, HDD (chủ đề Dịch vụ), làm cho bài A3 "Từ ý tưởng đến bàn giao".

- **Sinh viên:** Trần Phúc An – MSSV 2071020001 – lớp 20-02
- **Môn học:** Thiết kế web và triển khai phần mềm
- **Website:** https://phucantran616-droid.github.io/a3-an-toplap/
- **Repository:** https://github.com/phucantran616-droid/a3-an-toplap
- **Phiên bản nộp:** v1.0 (tag `v1.0`)

## Nội dung
4 trang: Trang chủ, Sản phẩm (11 sản phẩm chia 3 nhóm RAM, SSD, HDD), Chính sách, Liên hệ. Giao diện responsive cho màn hình rộng và hẹp .

## Cấu trúc thư mục
```
├── index.html, san-pham.html, chinh-sach.html, lien-he.html
├── styles.css
├── images/        ảnh SVG minh họa 
├── docs/          yeu-cau.md, thiet-ke.md, san-pham.md, kiem-thu.md
├── evidence/      ảnh minh chứng kiểm thử
├── AGENTS.md      quy tắc cho công cụ AI
└── AI_LOG.md      nhật ký sử dụng AI
```

## Cách chạy trên máy
Mở thư mục bằng VS Code, cài extension Live Server, bấm Go Live. Hoặc mở trực tiếp `index.html` bằng trình duyệt.

## Phạm vi và giới hạn
- Không có giỏ hàng, thanh toán hay lưu đơn hàng. Đặt mua qua thông tin ở trang Liên hệ.
- Form ở trang Liên hệ chỉ minh họa giao diện, không gửi dữ liệu đi đâu.
- Giá, sản phẩm, số điện thoại, email và địa chỉ đều là dữ liệu minh họa.

## Kiểm thử
Bảng kiểm thử và ảnh minh chứng: `docs/kiem-thu.md`, thư mục `evidence/`. 

## Khai báo sử dụng AI
Dự án dùng Codex trong VS Code để hỗ trợ viết mã. Prompt, kết quả và cách kiểm tra từng lần ghi trong `AI_LOG.md`. 

## Nguồn ảnh

Ảnh sản phẩm được lưu trong các thư mục `images/ram/`, `images/ssd/` và `images/hdd/`. Nguồn ảnh của từng sản phẩm đang hiển thị trên website:

| Sản phẩm | Nguồn ảnh |
|---|---|
| RAM Laptop DDR4 8GB | [Mexx](https://mexx-img-2019.s3.amazonaws.com/Memoria-Ram-SODIMM-DDR4-8Gb-3200-Mhz-Kingston_49320_1.jpeg) |
| RAM Laptop DDR4 16GB | [eBay](https://i.ebayimg.com/images/g/uX8AAeSwcdNp1Zjx/s-l1600.jpg) |
| RAM Laptop DDR5 16GB | [ROZETKA](https://content2.rozetka.com.ua/goods/images/big/361186262.jpg) |
| RAM PC DDR4 8GB | [Overclockers.ua](https://www.overclockers.ua/memory/crucial-ballistix-bl32g32c16u4wl-ct8g4dfra32a/10-crucial-ct8g4dfra32a.jpg) |
| RAM PC DDR5 16GB | [Cavuca](https://images.tcdn.com.br/img/img_prod/591628/memoria_16gb_crucial_ddr5_5600mhz_cl46_ct16g56c46u5_40113_1_cafa3ee3f4e3a993a42151b04c623def.jpg) |
| SSD SATA 256GB | [Ảnh gốc](https://cdn11.bigcommerce.com/s-23fyjn725n/images/stencil/1280x1280/products/109715/115368/MZ-7PC256D-WW__65488.1711840157.jpg?c=2) |
| SSD SATA 512GB | [Ảnh gốc](https://5b0988e595225.cdn.sohucs.com/images/20190728/bdabad87d03d4fd8bc206c90331985c0.png) |
| SSD NVMe 512GB | [Computer Bild](https://i.computer-bild.de/imgs/6/4/6/3/2/9/7/Samsung-970-Pro-512GB-1024x576-1ec9d213ae42298d.jpg?impolicy=image_gallery_desktop) |
| SSD NVMe 1TB | [eBay](https://i.ebayimg.com/images/g/QBwAAeSw9O9pvBCw/s-l1600.jpg) |
| HDD Laptop 1TB | [eBay](https://i.ebayimg.com/images/g/uOoAAOSwFI9oOS-U/s-l1200.jpg) |
| HDD PC 2TB | [eBay](https://i.ebayimg.com/images/g/nAUAAeSwHBlojNyo/s-l1200.jpg) |

