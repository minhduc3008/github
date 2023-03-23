Step1: khởi tạo repo dưới local

    git init

Step2: tạo 1 nhánh mới tên là develop

    git checkout -b develop

Step3: commit code

    git add filename -> add 1 file
    git add .  -> add tất cả
    git commit -m "Massage"  -> commit code trong đó "Message" là nội dung muốn commit

Step4: add remote
    git remote add origin https://github.com/minhduc3008/github.git
    git remote -v xem các remote

Step5: push code

    git push origin develop

Các câu lệnh git cơ bản:

    git branch -d tên-nhánh -> xóa 1 nhánh
    git checkout -b tên-nhánh -> thêm 1 nhánh
    git branch -> xem danh xách nhánh
    git checkout tên-nhánh -> chuyển nhánh
    git remote add tên-remote link-repo -> thêm mới 1 remote 
    git add filename -> add 1 file
    git add .  -> add tất cả
    git commit -m "Massage"  -> commit code trong đó "Message" là nội dung muốn commit
    git push origin tên-nhánh -> đẩy code lên nhánh trong đó origin là tên  remote mà chúng ta đặt
    