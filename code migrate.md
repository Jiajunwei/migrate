#### 1.在github或gitlab上新建仓库

#### 2.将新仓库拉到本地

```shell
git clone https://github.com/xxx/xxx.git
```



#### 3.进入本地仓库，将要迁移的文件放到该文件夹下

```shell
cd xxx
#git status
#git add .(提交被修改的和新建的文件，但不包括被删除的文件)
#git add /src （提交文件或文件夹）
git add .
git commit -m "Add KXXX-1 first commit"
git push
```

