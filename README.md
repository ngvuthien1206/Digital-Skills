# Tạo file README.md với nội dung tiêu đề
echo "# Digital Skills" > README.md

# Thêm dòng thông tin cá nhân vào file
echo "[Mã sinh viên] - [Họ và tên]" >> README.md
echo "Đây là repository đầu tiên." >> README.md

# Đưa file vào trạng thái theo dõi (Staging area)
git add README.md

# Lưu lại thay đổi (Commit)
git commit -m "Create README.md with student info"
