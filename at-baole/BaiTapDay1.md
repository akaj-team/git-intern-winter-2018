## Bài tập 1: Tìm hiểu về Markdown

* Cú pháp viết markdown
   https://marxi.co/

## Bài tập 2: So sánh giữa git commit -m "Message" và git commit -am "Message"

| git commit -m |    git commit -am   |
| :--------     |            --------:|
|   Chỉ commit   | vừa add vừa commit |

## Bài tập 3: Repository là gì?

	**Repository** (nhà kho) hay được gọi tắt là Repo đơn giản là nơi chứa/cơ sở dữ liệu (database) tất cả những thông tin cần thiết để duy trì và quản lý các sửa đổi và lịch sử của dự án.

	Trong Repo có 2 cấu trúc dữ liệu chính là Object Store và Index. Tất cả dữ liệu của Repo đều được chứa trong thư mục bạn đang làm việc dưới dạng folder ẩn có tên là .git (không có phần tên trước dấu chấm).

## Bài tập 4: Các bước để push code lên repository server

	1. git add <tên file> (push 1 file cụ thể) hoặc git add . (push tất cả các file nằm trong folder hiên tại)
	2. git commit -m "nội dung commit"
	3. git push origin <tên nhánh>

## Bài tập 5: Pull Request là gì? Làm cách nào để tạo PR

	**Pull Request** (viết tắt là PR) sẽ để cho bạn nói với người khác về các thay đổi bạn đã đẩy lên kho Github (Github repository). Một khi pull request được gửi, người nào quan tâm có thể review lại các thay đổi, hoặc thảo luận các sửa đổi tiềm năng, và có thể theo đó đẩy tiếp các commit của họ nếu cần thiết.

	Để tạo **pull request**, bạn phải thay đổi committed tới new branch.
	Hãy vào repository page trên github. Và click vào nút “Pull Request” trong repo header.
	Chọn branch bạn muốn merged sử dụng “Head branch” dropdown. Bạn nên để trường còn lại như vậy, trừ khi bạn làm việc từ remote branch. Trong trường hợp đó, chỉ cần chắc chắn rằng base repo và base branch được đặt đúng.
	Nhập các tiêu đề và mô tả cho việc pull request.
Cuối cùng click vào “Send pull request” để hoàn tất quá trình tạo pull request. Cuối cùng bạn có thể thấy open pull request.

## Bài tập 6: Viết daily report bằng markdown

