# Truong Van Dinh Team Android

#22 W1 - D2 - Git Basic
## Bài 1: So sánh giữa `git merge` và `git rebase`
* Git merge: sinh ra các merge commit
* Git rebase: không sinh ra các marge commit
## Bài 2:Trường hợp nào thì `conflict` xảy ra.
Conflict chỉ xảy ra khi gộp file bị thay đổi cùng một dòng. Do vậy các thao tác như merge branch, rebase branch hay pull file, push file,… gây ảnh hưởng trực tiếp tạo ra việc gộp file đều có khả năng xảy ra conflict. 

## Bài 3: Cách xử lý `conflict`
Git đã cung cấp đầy đủ tên file cũng như đánh dấu lại những chỗ bị conflict. Tất cả những gì phải làm đó là chỉnh sửa file bị conflict này cho phù hợp.
Ta giữ lại nội dung file cần, rồi sau đó commit.

## Bài 4: Viết daily report
* Quay trở lại commit phía trước
        * git reset --hard idcomit :chuyển tới commit có idcommit rồi xóa commit 
        * git reset --soft idcommit : chuyển tới commit có idcommit
* Git rebase
* Git merge
 
### Một số từ khoá cần tìm hiểu

* **Git stash** được sử dụng khi muốn lưu lại các thay đổi chưa commit, thường rất hữu dụng khi bạn muốn đổi sang 1 branch khác mà lại đang làm dở ở branch hiện tại.
* **Git rebase** là một cách thuận biện để áp dụng lại những commit mới trong một branch trên đỉnh của một branch khác.
* **Gộp commit** dùng git rebase để gộp commit.
* **Git cherry-pick** là một cách để checkout một commit tại branch nhất định về branch hiện tại.
* **Git tag** là chức năng đặt tên một cách dễ hiểu để có thể dễ dàng tham chiếu commit.
Trên Git có thể sử dụng 2 loại tag là lightweigh tag và annotated tag. Thêm nữa, tag đã đính kèm một lần là cố định, vị trí không di chuyển được như branch.
        * Lightweigh tag
        * Annotated tag
	
