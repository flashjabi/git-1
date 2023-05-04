# Khai niem

  - repository (repo): kho lưu trữ code 
  - client

# commands để làm việc vói git
  - download code lần đầu
  - update code
  - upload code

# thao tac voi 1 repository
  Bước 0: link đến một repo nào đấy (làm 1 lần duy nhất)
  git remote add origin [origin-url]

  Bước 1: khai bao sẽ upload những gì lên

  //kiem tra trạng thái code
  git status

  git add [options]
  git add .
  git add * 

  git add [path] (hay dùng)

  //bỏ cái gì đó ra khỏi add
  git reset [options]
  git reset [path]

  Bước 2: khai bao là mình đã làm những gì (vd: tao header cho homepage)
  git commit -m [message]

  Bước 3: Khi bị conflict
  - download code tren repo ve may, va chọn xem là nội dung nào mới là đúng
  git pull origin [branch_name]
  giai quyet conflict (resolve conflict)
  add phan vua resolve vao, sau do commit mot lan nua

  Bước 4: upload code lên
  git push origin [branch_name]

  ## cau lenh thay the cho pull
  -download code moi ve
  -merge code moi vao local

  ## fetch
  download code moi tu origin ve
  git fetch origin [branch_name]

  ## merge
  git merge [branch_A] [branch_B]

  origin origin/main
  local main

  git merge origin/main main
  git merge origin/main


## Tao 1 nhanh moi
buoc 1: di den nhanh muon lam node goc
git checkout [branch_name]

buoc 2: re nhanh moi tu nhanh dang dung
git checkout -b [branch_name]

## Tao pull request (merge request)


## xoa 1 nhanh tren local
* Phải đứng trên 1 nhánh khác để xóa 
git branch -d [branch_name]
git branch -D [branch_name]

