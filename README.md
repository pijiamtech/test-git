# test-git
Test everything I want to know

# Git Push Test
Just Commit and Sync in Source Control

i want to test message commit and sync commit

# New Branches
## Command
git branch                       #ดู branch ทั้งหมดและเราอยู่ branch ไหน<br>
git branch {name_branch}         #สร้าง branch ชื่อ {name_branch}<br>
git checkout {name_branch}       #ย้ายตัวเองไปอยู่ที่ branch {name_branch}<br>
let's publish Branches

git checkout main                #ย้ายตัวเองไปอยู่ที่ branch main<br>
git merge {name_branch}          #รวมไฟล์ main กับ {name_branch} ไว้ในเครื่อง<br>
let's push into server

### add-ons
git branch -d {name_branch}      #ลบ branch {name_branch} ออกจากเครื่อง<br>
git push origin :{name_branch}   #ลบ branch {name_branch} ออกจาก Server

# **testing pull request!!!**

# To-do(PJ)-List
Computer vision about license plate of car (ocr, ner, opencv)??<br>
how to computer can solving equations??<br>
AI playing sudoku

# Today(23/7) I'm learn about robots.txt
/robot.txt เพื่อดูว่าส่วนไหนใช้บอทได้


# วิธีการสร้าง Virtual Environment
New Terminal >> command prompt

py -m venv .venv  //สร้าง Virtual Environment

.venv\Scripts\activate //ใช้งาน Virtual Environment

pip install -r requirements.txt

deactivate //ออกจาก Virtual Environment

pip freeze > requirements.txt //สร้าง requirements.txt จาก Environment ที่เราอยู่

# วิธีการใช้ .gitignore
New File >> rename = .gitignore

/namefolder // '/' เป็น folder

namefile // เป็นแต่ละ file

# วิธีใช้ git add
git add .gitignore // อยากเพิ่มไฟล์ .gitignore เข้า git

git commit -m "add .gitignore" // commit and comment ขึ้น git

git status //

git push //

## เสริม

git add --all

git commit -m "edit readme and add requirements.txt"

git log // ดูประวัติ กด q เพื่อออก

git push


# Note:
print(ord(" ")) # blank space is the decimal number 32
```
def unicode_table():
    for i in range(ord("ก"), ord("ฮ") + 1):
        print("{0} : {0:#x} : {0:c}".format(i))
unicode_table()
```
#ก - ฮ ( 3585 - 3630 )
