# Workshop Landing — OpenClaw · AI Agents VN

Landing page (một file HTML self-contained) cho workshop "X3 năng suất bán hàng nhờ AI".

- **Preview:** https://bichoanh201698-collab.github.io/workshop-landing/
- `index.html` — **file duy nhất để sửa**. Mọi CSS/JS/ảnh/font đều nhúng trong đó.
- `assets/` — bản gốc của các asset đã nhúng (logo SVG, ảnh chân dung, font subset).

## Cập nhật trang

Sửa trực tiếp `index.html`, rồi:

```bash
git add index.html && git commit -m "Update landing page" && git push
```

GitHub Pages tự build lại sau khoảng 30–60 giây.

> Lưu ý: thư mục này nằm trong OneDrive và đã từng bị OneDrive khôi phục file về bản cũ.
> Git là bản chuẩn — nếu `index.html` bỗng mất thay đổi, lấy lại bằng `git checkout -- index.html`.
