# Trương Văn Định Team Android

## Bài tập 2: So sánh giữa git commit -m "Message" và git commit -am "Message"
   * git commit -m "Message": chỉ commit
   * git commit -am "Message": vừa add vừa commit
## Bài tập 3: Repository là gì?
   * **Repository** hay còn gọi là Repo, dịch ra tiếng Việt có nghĩa là kho, đây chính là nơi chứa tất cả mã nguồn cho một dự án được quản lý bởi Git. Bạn cũng có thể hiểu một cách khác là Repository chính khai báo thư mục chứa dự án của bạn trên local hoặc remote. Môi repo sẽ có hai cấu trúc dữ liệu chính đó là Object store và Index được lưu trữ ẩn trong thư mục .git

   * Có 2 loại repository đó là local repository và remote repository.

        * **Local repository**: Là repo được cài đặt trên máy tính của lập trình viên, repo này sẽ đồng bộ hóa với remote repo bằng các lệnh của git.
        * **Remote repository**: Là repo được cài đặt trên server chuyên dụng, điển hình hiện nay là Github.


## Bài tập 4: Các bước để push code lên repository server?
   * **Bước 1**: Pull dữ liệu về nếu có thay đổi
   * **Bước 2**: git add . hoặc git add file-name
   * **Bước 3**: git commit -m "message"
   * **Bước 4**: git push origin branch-name

## Bài tập 5: Pull Request là gì? Làm cách nào để tạo PR?
   * Khi người dùng khác tham gia phát triển phần mềm và đã phát triển xong một tính năng, họ muốn merge tính năng của họ vào phần mềm của mình thì lúc này họ sẽ gửi một Pull request/Merge request để mình chọn chấp nhận hay không.
   * Các bước tạo Pull Request
        * **B1**: Push nội dung mới nhất lên branch của mình
        * **B2**: Truy cập vào project ban đầu (không phải trong tài khoản của mình)
        * **B3**: Nhấp chuột vào nút “Compare & pull request” để tiến hành tạo pull request. Sẽ có một mục nhập hiện ra, ta chủ yếu mô tả những gì mình làm và lý do cần làm, ta điền nội dung vào form đó, rồi click Create pull request để hoàn tất.

## Bài tập 6: Viết daily report bằng markdown
### Các nội dung được học ngày hôm nay
   * Responsitory:
        * Đã có sourcecode: git clone
        * Chưa có source : git init
   * Branch:
        * Tạo nhánh: git checkout -b branch-name
        * Kiểm tra nhánh hiện tại : git branch
        * Chuyển nhánh : git checkout branch_name
   * Pull: git pull origin branch-n
   * Push:
        * git add .
        * git commit -m "message"
        * git push origin branch-name

   * Git remove add
        * Đổi định danh origin: git remove add Dinh github
   * Tạo SSH key
        * ssh-keygen -t rsa
        * cat /home/dinhtruong/.ssh/id_rsa.pub
        * ssh-rsa key
