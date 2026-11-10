# 🎄 Thiệp Giáng Sinh 2 — SIU VIP Edition 💝

Thiệp Giáng sinh online **siu cấp VIP** dành tặng người yêu — phiên bản sang trọng, lãng mạn và lung linh hơn hẳn phần 1. Mở phong bì triện sáp và cả vũ trụ Giáng sinh sẽ mở ra cho người ấy 🌌

**Xem thiệp:** https://nhut0902.github.io/thiep-giang-sinh-2/

## ✨ Có gì trong bản SIU VIP này

- 💌 **Phong bì hoàng gia** — triện sáp đỏ in chữ cái đầu, chạm vào là nắp 3D mở ra, thư trượt lên, pháo hoa vàng nổ mừng
- 🌌 **Aurora bắc cực** — 3 dải lụa sáng xanh tím hồng lượn trên trời đêm
- 🌠 **Sao băng** tự bay ngang trời + sao lấp lánh + trăng đầy hào quang
- 🎄 **Cây thông 4 tầng** — tuyết phủ mép lá, dây đèn vàng uốn quanh cây, quả cầu treo 4 màu, sao đỉnh xoay tia
- ⛄ **Người tuyết cặp đôi** — chàng đội mũ nồi, nàng đội mũ ông Noel, giữa hai người có trái tim đập thình thịch 💓 (nàng còn biết nháy mắt!)
- 🎁 **Pháo hoa trái tim** — chạm màn hình bất kỳ đâu là nổ, nút ❤️ bắn đại tiệc 3 nổ + mưa tim
- 🔔 **Nhạc hộp Jingle Bells** — tự tổng hợp bằng WebAudio (không cần file), bật tắt được
- 📜 **Thư tình tự gõ** — từng chữ hiện dần, tự căn cỡ chữ vừa màn hình
- 🎅 **Đếm ngược Giáng Sinh** realtime trên chip đầu trang
- 📱 **Parallax nghiêng máy** — nghiêng điện thoại là cả khung cảnh dịch chuyển (desktop: di chuột)
- ✨ Ốc sáng vàng bay theo con trỏ, tuyết rơi nhiều tầng, đom đóm vàng

## 🛠️ Đổi tên / lời nhắn (30 giây)

Mở `index.html`, tìm `CFG` ở đầu phần `<script>`:

```js
const CFG={
  name:'Bé Yêu',              // 👉 ĐỔI TÊN NY VÀO ĐÂY
  to:'Gửi em, người con gái anh yêu nhất',   // lời chào đầu thư
  seal:'N',                   // chữ trên triện sáp (chữ cái đầu tên bạn)
  text:'...',                 // 👉 THƯ TÌNH — sửa thoải mái
  sign:'— Nhut, người yêu em nhiều nhất trên đời 🎄',
  music:true                  // bật/tắt nhạc hộp
};
```

Lưu lại, gửi link cho ny là xong! Trên điện thoại cứ nghiêng máy ngắm cảnh nhé 😉

## 🚀 Chạy local

```bash
python3 -m http.server 8080
# mở http://localhost:8080
```

---

Code By **NhutCoder Team** ❤ | Bản 1: [thiep-giang-sinh](https://nhut0902.github.io/thiep-giang-sinh/)
