## Bài 1::
>So sánh giữa git merge và git rebase 
+ **git merge** có sinh ra commit
+ **git rebase** không sinh ra commit
## Bài 2:
>Trường hợp nào thì conflict xảy ra.
* conflict xảy ra khi nhiều người cùng pull code về giống nhau. Khi ta đang ở trên một nhánh khác, khi merge master, trong nhánh master có file cùng tên với nhánh master thì xảy ra conflic.
## Bài 3:
>Cách xử lý conflict
* **B1**: về nhánh master
* **B2**: `pull` dữ liệu từ nhánh master về
* **B3**: trở lại nhánh bị `conflic`. Chỉnh sửa file bị conflict này cho phù hợp.
* **B4**:  Lưu lại, add file, commit, push.
## Bài 4:
>Những thứ hôm nay đã được học
* Lấy dữ liệu từ các nhánh khác về nhánh của mình, để có thể sử dụng
* Hiện tượng `conflic`
* `Gitlog`: xem lịch sử commit
* `Git reset --hard <tên id commit>`: hủy bỏ dữ liệu đã thay đổi, quay về dữ liệu gốc
* `Git stash apply <tên id>`: lấy trong bộ nhớ đệm ra cái cần
* Đổi file sang nhánh khác
	* `git checkout .`
	* `git commit`
	* `Lưu trong bộ nhớ đệm`
* Git stash: Lưu file trong bộ nhớ đệm
* Git rebase: gộp các commit lại
* Gộp commit: sử dụng `git rebase`
* Git cherry-pick: là một cách để checkout một commit tại branch nhất định về branch hiện tại.
* Git tag: Liệt kê các tag hiện có trong Git



