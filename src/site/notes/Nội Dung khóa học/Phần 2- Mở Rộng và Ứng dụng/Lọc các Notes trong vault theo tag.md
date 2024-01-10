---
{"dg-publish":true,"permalink":"/noi-dung-khoa-hoc/phan-2-mo-rong-va-ung-dung/loc-cac-notes-trong-vault-theo-tag/","dgPassFrontmatter":true,"noteIcon":"1"}
---


#dataview #filter #obsidian2Share 
![](https://i.imgur.com/T8AxtSx.png)
## Giả sử bạn muốn lọc các note trong tài liệu có tag là #tag1 thì làm như thế nào?

Bạn gõ cấu trúc như sau

```
| File                                                                                                                        |
| --------------------------------------------------------------------------------------------------------------------------- |
| [[Nội Dung khóa học/Phần 2- Mở Rộng và Ứng dụng/Lọc các Notes trong vault theo tag.md\|Lọc các Notes trong vault theo tag]] |

{ .block-language-dataview}
**hoặc**
```
- [[Nội Dung khóa học/Phần 2- Mở Rộng và Ứng dụng/Lọc các Notes trong vault theo tag\|Lọc các Notes trong vault theo tag]]

{ .block-language-dataview}

## Nếu kết hợp 2 tag thì sao nhỉ


```

{ .block-language-dataview}
## Nếu có tag1  ==hoặc== tag2 kia thì sao nhỉ

```dataview
list
from #tag1 or #tag2
