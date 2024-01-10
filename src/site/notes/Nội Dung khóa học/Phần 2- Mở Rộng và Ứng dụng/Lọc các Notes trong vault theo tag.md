---
{"dg-publish":true,"permalink":"/noi-dung-khoa-hoc/phan-2-mo-rong-va-ung-dung/loc-cac-notes-trong-vault-theo-tag/","dgPassFrontmatter":true,"noteIcon":"1"}
---


#dataview #filter #obsidian2Share 

# Giả sử bạn muốn lọc các note trong tài liệu có ký hiệu là #tag1 thì làm như thế nào?

Bạn gõ cấu trúc như sau
 >[!note]
> Có thể thay table bằng **list** Các bạn thử xem nhé.
```
| File |
| ---- |

{ .block-language-dataview}

```

{ .block-language-dataview}

## Nếu kết hợp 2 tag thì sao nhỉ


```

{ .block-language-dataview}
## Nếu có tag này hoặc tag kia thì sao nhỉ

```dataview
list
from #tip1 or #tip2
