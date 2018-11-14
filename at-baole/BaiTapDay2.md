## Bài 1: So sánh giữa `git merge` và `git rebase`.

#### Giống nhau:
Cả 2 câu lệnh đều được tạo ra để tích hợp những thay đổi từ 1 nhánh vào 1 nhánh khác.

#### Khác nhau:

1. Câu lệnh `git merge`:
- Câu lệnh `git merge` sẽ tạo ra một `merge commit` mới trên branch feature bao gồm lịch sử của cả 2 branch.
- Merging không làm thay đổi hệ thống. Những nhánh đang tồn tại sẽ không bị ảnh hưởng gì cả.
- Nhược điểm: Branch Feature sẽ có thêm 1 `commit merge` mỗi lần bạn cần tích hợp những thay đổi từ các nhánh khác vào nó. Nếu `branch master` liên tục bị thay đổi thì lịch sử `commit` của `branch Feature` sẽ rất khó nhìn. Nó sẽ gây rất nhiều khó khăn trong việc xem lại lịch sử `commit` của dự án.

2. Câu lệnh `git rebase`:
- Câu lệnh `git rebase` sẽ bê toàn bộ `branch feature` lên đầu của `branch master`. Nhưng thay vì dùng một `commit merge`, nó sẽ viết lại lịch sử của project bằng cách tạo các `commit` hoàn toàn mới cho mỗi `commit` ở nhánh ban đầu.
- Lợi ích chính của việc rebasing này là lịch sử project sẽ gọn gàng & sạch sẽ hơn. Đầu tiên, nó sẽ loại bỏ những `commit merge` không cần thiết mà được sinh ra bởi `git merge`.

## Bài 2: Trường hợp nào thì `conflict` xảy ra?

- Khi 2 hoặc nhiều nhánh cùng sửa 1 file, sau đó `pull request`, rồi khi `merge` các `request` lại với nhau sẽ xảy ra `conflict` (xung đột) do hệ thống không biết được sẽ dùng phiên bản nào.

## Bài 3: Cách xử lý conflict.

#### Để xử lý `conflict`, ta làm theo các bước sau:
1. `Pul origin master` về nhánh đang làm việc để thấy được những chỉnh sửa vừa xảy ra trên file.
2. Chỉnh sửa lại sao cho phù hợp.
3. `git add`, `git commit`, `git push origin <tên nhánh đang làm việc>`

## Bài 4: Viết daily report.

#### Daily report Day2:
- Khi nào xảy ra `conflict` và cách giải quyết.
- Tìm hiểu `git merge` và `git rebase`.
- Tìm hiểu một số từ khóa `git`.
- Biết về `Instant app` thông qua buổi họp team Android.

## Một số từ khoá cần tìm hiểu

- `Git stash`: lưu vào vùng nhớ đệm là ngăn xếp.
- `Git rebase`: tích hợp những thay đổi từ 1 nhánh vào 1 nhánh khác. Tạo các `commit` hoàn toàn mới cho mỗi `commit` ở nhánh ban đầu.
- Gộp commit: tích hợp những thay đổi từ 1 nhánh vào 1 nhánh khác. Có thêm 1 `commit merge` mỗi lần bạn cần tích hợp những thay đổi từ các `branch` khác vào nó.
- `Git cherry-pick`: `cherry-pick` thực chất là một cách để checkout một `commit` tại `branch` nhất định về `branch` hiện tại. Hay nói một cách dân dã thì `cherry-pick` dùng để bưng các thay đổi trong một `commit` trên một nhánh nào đó áp dụng về nhánh hiện tại.
- `Git tag`: Liệt kê các tag hiện có trong Git.
