- git: dùng để lưu trữ lịch sử của source code
- github: 
# Mở termiral
-ctrl + `
# Tạo lịch sử với git (Khởi tạo repository)
-git init
# git add 
- git add <tenfile> ghi từng file vào lịch sử
- git add . : lưu tất cả
----------------
# git commit
-thêm chú thích cho những file mà mình đã làm vào
```bash
git commit -m"thong tin lich su"
```
# Hiển thị log
```bash
git log
```
# Hiển thị ra 1 dòng 
git log --oneline 

# Thao tác
- add -> edit -> add -> commit

# git reset
```bash
#không mất code
git reset --soft HEAĐ~1 # xoá message trước đó
```

# git remote 
```bash
git push origin <tennhanh>
```
```bash
git branch -v #kiểm tra mìnhd dang ở nhánh nào
```


# git clone
download source code về
```bash
git clone <duong_dan_source_code>
```
# Edit
# Edit 2
# Edit 3
# Edit 4
# Edit 5
# Mai Dang Huy đã ở đây
# Edit 6
#Edit 7 kiet
```bash
git config --global pull.rebase false # merge
```