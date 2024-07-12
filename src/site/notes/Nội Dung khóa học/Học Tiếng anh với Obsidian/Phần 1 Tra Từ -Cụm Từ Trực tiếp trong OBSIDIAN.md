---
{"dg-publish":true,"image":"https://images.unsplash.com/photo-1604391659919-0cb8c6bb0966?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3wzNjAwOTd8MHwxfHNlYXJjaHwyMXx8Zmxvd2VyfGVufDB8MHx8fDE3MjA3NjU2NzR8MA&ixlib=rb-4.0.3&q=80&w=1080","permalink":"/noi-dung-khoa-hoc/hoc-tieng-anh-voi-obsidian/phan-1-tra-tu-cum-tu-truc-tiep-trong-obsidian/","dgPassFrontmatter":true,"noteIcon":"2","created":"2024-07-12T12:00:41.627+07:00","updated":"2024-07-12T16:51:20.688+07:00"}
---



##  GIỚI THIỆU 

NOTE : 🚦BẠN KHÔNG CẦN LÀ MỘT MASTER OBSIDIAN ĐỂ DÙNG ỨNG DỤNG NÀY 

LLM Dictionary là một plugin trên OBSIDIAN hỗ trợ tra cứu. 

- Tác giả của Plugin : ℹ️[Nguyễn Thiện Nghĩa ](https://www.facebook.com/profile.php?id=100093832307685)
- Tra cứu từ vựng theo ngữ cảnh bằng AI. thay vì chỉ đưa ra các nghĩa cho sẵn trong từ điển. 
- LLM Dictionary đang hỗ trợ các ngôn ngữ sau : Anh, Trung, Nhật, Hàn, (Các ngôn ngữ khác sẽ được tác giả cập nhật nếu được bạn bè ủng hộ và động viên)
- Tra được từ trên PDF 😍 XỊN MỊN quá.
- Sau khi tra từ xong bạn chỉ nhấn nút là có thể xuất từ sang anki để học rồi. ( ai không dùng Anki thì có thể chỉ dùng để tra từ, phiên âm, cách đọc cũng đã là quá tốt rồi)
- Điểm cộng là còn tra được cả CỤM TỪ 💘 
- Ngoài các tính năng trên, nó còn tạo được LIÊN KẾT giữa file BÀI BÁO, sách mà bạn đọc và các TỪ MỚI  mà bạn tra cứu, tạo thành một mạng lưới từ để review về sau.
Workflow : Obsidian là nơi chứa từ vựng, tài liệu học tập> xuất từ vựng sang Anki để ôn tập.
 Bạn có thể đọc kỹ hơn về Plugin này ở link sau: https://github.com/Mrntn161/LLM-Dictionary-vn
 ## HƯỚNG DẪN CÀI ĐẶT VÀ SỬ DỤNG
### Bước 1-Cài đặt plugin
- Plugin BRAT là để chạy các Plugin chưa có trên community plugin
-![](https://i.imgur.com/oeYFmUV.png)
![](https://i.imgur.com/PJN3ubt.png)
![](https://i.imgur.com/XueW28l.png)

![](https://i.imgur.com/w0FqydN.png)
Đây là link github:  https://github.com/Mrntn161/LLM-Dictionary-vn
![](https://i.imgur.com/Op9x0yR.png)
![](https://i.imgur.com/WDhWcqe.png)
Xong rồi ; giờ thì tra từ thôi
### Bước 2- Tra Từ và Cụm Từ
#### Để tra từ nhanh, thì ta cài đặt phím tắt
Cùng mình cài phím tắt nhé.
![](https://i.imgur.com/fgx0RP7.png)
![](https://i.imgur.com/7FiQw6G.png)
![](https://i.imgur.com/HmKpkGb.png)
![](https://i.imgur.com/T1ihxcq.png)
![](https://i.imgur.com/J22eGpP.png)
#### Note: ngoài ra để tra từ nhanh thì còn có thể thêm icon vào tab bar 
![](https://i.imgur.com/NDGu6cF.png)

Phần 2 là export Note từ Obsidian sang Anki.
Video tác giả cũng làm cả rồi nè. ^^
#### Một số Câu hỏi và lỗi của các bạn trong quá trình dùng:

![](https://i.imgur.com/FzDUeJO.png)
##### Copy đoạn sau vào phần template nhé.

```---
source: "{{Source}}"
---
START
Vocab
{{ID}}
Term: {{Term}}
Definition: {{Definition}}
IPA: {{IPA}}
Audio: {{Audio}}
POS: {{Part_of_speech}}
Example:
- {{Example Audio 1}} {{Example 1}}
- {{Example Audio 2}} {{Example 2}}
- {{Example Audio 3}} {{Example 3}}

END

```
