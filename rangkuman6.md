# Rangkuman Video 6

<p>&nbsp;</p>

## Developer:
### 16521199 - Jazila Faza Aliyya Nurfauzi - STEI21

<p>&nbsp;</p>

# Git Branch & Merge
**BRANCH**
1. Menambahkan Branch
```
git branch <nama_branch>
```
2. Check branch
```
git branch
```
3. check history
```
git log
```
4. Menampulkan visualisasi branch 
```
git log --all --decorate --oneline --graph
```
5. Membuat alias
```
alis <nama>=<yang akan di aliaskan>
```
6. Berpindah Branch
```
git checkout <nama_branch>
```

**MERGE**

 Terdapat 2 jenis merge:
 - **Fast Forward**: terjadi ketika branch yang diingin berada di jalur langsung (direct path)

 - **Three-way Merge**: melakukan merge dengan commit
1. Melakukan Merge
```
git merge <nama_branch>
```
2. Menghapus branch
```
git branch -d <nama_branch>
```
3. Mengetahui branch yang sudah di merge
```
git branch --merged
```
