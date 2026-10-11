# Git Workflow for Light_Novel Project

## Cấu trúc
- **Local:** `/home/veldora/Documents/Veldachi-Lore/Light_Novel/` (chứa .git)
- **GitHub:** Files ở root repo (KHÔNG có folder Light_Novel) vì tên repo đã là `Light_Novel_fanfic_Veldachi_a_True_Dragon`

## Quy tắc push/pull
```bash
# LUÔN cd vào folder Light_Novel trước
cd /home/veldora/Documents/Veldachi-Lore/Light_Novel

# Push
git add .
git commit -m "Message"
git push

# Pull
git pull
```

## KHÔNG BAO GIỜ
- ❌ Chạy git ở `/home/veldora/Documents/Veldachi-Lore/`
- ❌ `mv Light_Novel/* .` - xóa folder local
- ❌ Init git ở thư mục cha

## Git Config (local repo)
```bash
git config user.name "?? idk"
git config user.email "fbf4355@gmail.com"
```

## Remote
```bash
git remote -v
# origin  https://github.com/HieuPythonBeginner/Light_Novel_fanfic_Veldachi_a_True_Dragon (fetch)
# origin  https://github.com/HieuPythonBeginner/Light_Novel_fanfic_Veldachi_a_True_Dragon (push)
```