BƯỚC 1 — MỞ THƯ MỤC LOCAL BẰNG VS CODE

Trong VS Code:

File → Open Folder → chọn thư mục Local:
📁 Harris-Hawks-Optimization-HHO-Python-Code

🚀 BƯỚC 2 — KHỞI TẠO GIT TRONG FOLDER LOCAL

Mở Terminal trong VS Code:

git init

🚀 BƯỚC 3 — KẾT NỐI FOLDER LOCAL VỚI REPO GITHUB

Chạy các lệnh:

git remote add origin https://github.com/vancv43/Harris-Hawks-Optimization-HHO-Python-Code.git
git branch -M main


Nếu báo remote đã tồn tại thì chạy:

git remote remove origin
git remote add origin https://github.com/vancv43/Harris-Hawks-Optimization-HHO-Python-Code.git

🚀 BƯỚC 4 — THÊM TẤT CẢ CODE VÀO GIT
git add .

🚀 BƯỚC 5 — TẠO COMMIT ĐẦU TIÊN
git commit -m "Initial upload - Harris Hawks Optimization code"

🚀 BƯỚC 6 — ĐẨY CODE LÊN GITHUB
git push -u origin main


Nếu Git yêu cầu đăng nhập → VS Code sẽ mở GitHub xác thực.

🎉 KẾT QUẢ

Truy cập lại repo của thầy:

👉 https://github.com/vancv43/Harris-Hawks-Optimization-HHO-Python-Code