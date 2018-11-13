### Bài tập 1: Tìm hiểu về Markdown

Cú pháp viết markdown
https://marxi.co/


### Bài tập 2: So sánh giữa git commit -m "Message" và git commit -am "Message"
| git commit -m "Message" | git commit -am "Message" |
| :---------------------- | ------------------------:|
| -chỉ commit file         | - tích hợp add và commit |


### Bài tập 3: Repository là gì?
**Repository** hay còn gọi là Repo, dịch ra tiếng Việt có nghĩa là kho, đây chính là nơi chứa tất cả mã nguồn cho một dự án được quản lý bởi Git. Bạn cũng có thể hiểu một cách khác là Repository chính khai báo thư mục chứa dự án của bạn trên local hoặc remote. Môi repo sẽ có hai cấu trúc dữ liệu chính đó là Object store và Index được lưu trữ ẩn trong thư mục .git

Có lại loại repository đó là local repository và remote repository.

- **Local repository:** Là repo được cài đặt trên máy tính của lập trình viên, repo này sẽ đồng bộ hóa với remote repo bằng các lệnh của git.
- **Remote repository:** Là repo được cài đặt trên server chuyên dụng, điển hình hiện nay là Github.



### Bài tập 4: Các bước để push code lên repository server?

Có **3** bước: 
* Bước 1: git add <ten-file> hoặc git add . (thêm toàn bộ file nằm trong thư mục)
* Bước 2: git commit -m "message"
* Bước 3: git push origin <name-branch>


### Bài tập 5: Pull Request là gì? Làm cách nào để tạo PR?

**Pull Request** (viết tắt là PR) sẽ để cho bạn nói với người khác về các thay đổi bạn đã đẩy lên kho Github (Github repository). Một khi pull request được gửi, người nào quan tâm có thể review lại các thay đổi, hoặc thảo luận các sửa đổi tiềm năng, và có thể theo đó đẩy tiếp các commit của họ nếu cần thiết.

Để tạo **pull request**, bạn phải thay đổi **committed** tới **new branch**.
Hãy vào **repository** page trên github. Và click vào nút “Pull Request” trong repo header.
Chọn branch bạn muốn merged sử dụng “Head branch” dropdown. Bạn nên để trường còn lại như vậy, trừ khi bạn làm việc từ remote branch. Trong trường hợp đó, chỉ cần chắc chắn rằng base repo và base branch được đặt đúng.
Nhập các tiêu đề và mô tả cho việc pull request.
Cuối cùng click vào “Send pull request” để hoàn tất quá trình tạo pull request. Cuối cùng bạn có thể thấy open pull request.

### Bài tập 6: Viết daily report bằng markdown
