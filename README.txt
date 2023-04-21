
https://git-scm.com/

$ git init
$ git config --global --list
$ git config --global user.name "xxxx"
$ git config --global user.email "yyyy@gmail.com"
$ git config --global core.autocrlf false


STATUS
$ git status
$ git log


CHANGE to STAGE
				  (in change)   <-- git restore .
$ git add .                   (in stage)    <-- git restore --staged .
$ git commit -m "xxx"         (in commit)   <-- git reset อักษร commit 6หลัก


กลับไป ณ จุดที่ commit
$ git checkout อักษร commit 6หลัก


REMOTE to Github.com
$ git remote -v
$ git remote add origin https://github.com/likit123/xxxx.git
$ git push -u origin (main/master)


PULL
$ git pull


BRANCE
$ git branch (ใช้แสดงรายชื่อ branch ทั้งหมด)
$ git branch branch_name (สร้าง branch ใหม่)
$ git checkout ชื่อbranch  
$ git checkout master
$ git checkout branch_name (สลับไปใช้งาน branch ที่ระบุ)
$ git merge branch_name (ใช้รวมไฟล์จาก branch ที่ระบุ มายัง branch ปัจจุบัน)
$ git branch -d branch_name (ลบ branch ที่ระบุ)


