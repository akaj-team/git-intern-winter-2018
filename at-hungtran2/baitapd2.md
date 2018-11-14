### Bài 1: So sánh giữa `git merge` và `git rebase`
#### Giống nhau: 
Cả 2 câu lệnh đều được tạo ra để tích hợp những thay đổi từ 1 nhánh vào 1 nhánh khác.
#### Khác nhau:
`Git merge`: commit của `master` nằm phía trên commit mới nhất của `merge`, ngoài ra một commit `Merge branch` cũng được tạo ra.
`Git rebase`: commit của `rebase` nằm phía trên commit mới nhất của `master`


### Bài 2: Trường hợp nào thì `conflict` xảy ra.
`conflict` xảy ra khi 2 hay nhiều người cũng sửa 1 file, sau đó `pull request` khi `merge` request lại thì xảy ra lỗi `conflict` 

### Bài 3: Cách xử lý `conflict`
- b1: `git pull origin master` về nhánh mình vừa `pull request` xong nhưng bị lỗi `conflict`
- b2: Chỉnh sửa lại file
- b3: `git commit -am "message"` và `git push origin <nhanh-hien-tai>` -> `pull request`
### Bài 4: Viết daily report
- `git merge`
- `git rebase`
- khi nào xảy ra lỗi `conflict` và khắc phục lỗi

#### Một số từ khoá cần tìm hiểu

• `Git stash` : lưu lại thay đổi vào ngăn xếp
• `Git rebase`: là một cách thuận biện để áp dụng lại những commit mới trong một branch trên đỉnh của một branch khác.
• `Gộp commit`: dùng `git rebase` để gộp commit
• `Git cherry-pick`: là một cách để checkout một commit tại branch nhất định về branch hiện tại
• `Git tag`: liệt kê các tag hiện có trong g
