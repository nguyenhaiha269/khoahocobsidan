---
{"dg-publish":true,"permalink":"/ii-cac-video-va-bai-giang-chia-se/huong-dan-dung-pandoc-de-xuat-ban-note-sang-word-epub-va-cac-dinh-dang-khac/","dgPassFrontmatter":true,"created":"","updated":""}
---


# [[HOME PAGE\|👈 QUAY LẠI]]

Bước 1: ở obsidian cài plugin “ Obsidian pandoc”

Bước 2: cài phần mềm pandoc trên máy tính

<div style="display: flex; justify-content: center; cursor: pointer;"> <a href="https://pandoc.org/installing.html" target="_blank"> <button style=" font-size: 28px; padding: 10px; height: fit-content; margin-top: 50px; background: var(--text-accent); font-weight: 300; color: var(--text-on-accent); "> Tải pandoc ở đây</button> </a> </div>

---
Sau khi cài xong bước 1 và 2 ta vào obsidian, tìm đến plugin “ Obsidian pandoc” Ta 
thấy có Thông báo đỏ như này có nghĩa là đang bị lỗi nên chưa xuất file được. ta cần 
làm  một vài bước để fix lỗi này. cách làm như sau
![](https://i.imgur.com/ZX4oHgZ.png)

**Cách Fix lỗi;**
Máy Window: gõ phím” Window +X “ sẽ hiện ra bảng sau:
![](https://i.imgur.com/N0k4KJE.png)
Chọn vào Windows powershell hiện ra bảng như thế này
![](https://i.imgur.com/h659D5s.png)
Gõ chữ : “Get-command pandoc” như hình sau Rồi nhấn enter
![](https://i.imgur.com/iqmrhvI.png)
Thu được kết quả như sau: copy phần bôi vàng và trở lại obsidian
![](https://i.imgur.com/ecFgG7y.png)
Paste phần bôi vào vào ô số 2; ô số 1 là Nơi ta dự định xuất ra, nếu không cài thì nó sẽ 
chạy mặc định vào vault
![](https://i.imgur.com/nT3t6lq.png)
SAu khi paste thì khởi động lại OBSIDIAN -SẼ mất chữ mầu đỏ
Xuất file thôi: 
gõ ctrl P để hiện lệnh pandoc 

![](https://i.imgur.com/yxSDNSu.png)
Lưu ý : nếu báo fail không xuất được thì khởi động lại Obsidian, và xóa nội dung số 2 ở 
đây đi và khởi động lại lần nữa là ok
![](https://i.imgur.com/EE7SQr8.png)
