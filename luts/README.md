# Danh mục bảng màu của CAM-Coach

App tải `index.json` rồi tải từng tệp `.cube` khai trong đó — chỉ khi người dùng
bấm "Tải thêm" trong thư viện bảng màu của chế độ Phim.

**Đừng sửa tay tệp nào ở đây.** `index.json` ghi cỡ và mã băm SHA-256 của từng
tệp; lệch một byte là app từ chối cả gói. Muốn thêm hay đổi bảng thì sửa
`tool/tao_goi_lut.py` ở repo `cam-coach` rồi chạy:

    python tool/tao_goi_lut.py ../cam-coach-web/luts

Các bảng ở đây là công thức do dự án tự viết, phát hành theo
[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/deed.vi). Chỉ đưa lên
đây những bảng được phép phân phối lại, và ghi rõ người làm cùng giấy phép trong
`index.json` — app hiện hai dòng ấy trên thẻ của từng gói.