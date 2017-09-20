# Git 복습

---

## 2주차
### Git - 분산형/버전/관리/시스템

* **Linux명령어**
    * mkdir  디렉토리 생성
    * ls  파일리스트 보기(list)
    * ls -al  전체파일리스트 상세히보기
      (-a 숨김파일, -l 상세히보기)
    * cd  디렉토리 이동(change directory)
    * touch  빈파일 생성
    * vi  편집기상태로 들어감
    * :wq  편집기상태에서 나옴

* **Git명령어 1**
    * git init  디렉토리를 git환경으로 초기화
    * git status  현재 디렉토리의 git 상태를 알려줌
 	*빨강 : git에 추적되지않은(수정된)내용有*
     * git add .(file name)  추적하지 않고있는(수정된) 내용을 git이 추적
	*초록 : git이 추적하는 내용有*
    * git commit -m "커밋내용"  git에 반영
    * git remote add origin[URL]  디렉토리와 저장소를 연결
    * git push -u origin master  디렉토리의 git 내용을 저장소에 연동

### 3주차
* **Git명령어 2**
    * git branch  master branch는 모든 repository에 존재
    * git branch <branch_name>  생성
    * git checkout <branch_name>  이동
	(branch 생성 후 내용수정을 했다면 그 branch에 반영될 수 있도록 commit해줘야함)
    * git log  현재 directory branch의 git log를 보여줌
    * git merge <branch_name>  현재 branch와 병합
