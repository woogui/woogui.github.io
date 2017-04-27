---
layout: post
title: VMware에 설치된 Linux mint 초기설정
---

##VMwareTools 설치
1. **VMware**를 실행하여 **Linux Mint**가 설치된 **virtual Machine**을 실행한다.

2. 아직 초기설정을 하지 않은 상태라면 VMware실행창 밑에 다음과 같은 창이 붙어있을 것이다.

	![](http://i.imgur.com/ti4XLSI.png "title" "width:500px;")
    
	 **install Tools**를 클릭한다.
    
3. **install Tools**를 클릭하면 다음과 같은 폴더가 열릴 것이다.

	![](http://i.imgur.com/NoXq5Vd.png "title" "width:500px;")
    
    **VMwareTools-버전번호.tar.gz**파일을 홈 화면으로 복사 붙여넣기 한 후 창을 닫는다.
    
    ![](http://i.imgur.com/Nm9JUjK.png "title" "width:500px;")
    
4. **터미널**을 실행하고 **ls**를 입력해 홈 화면에 방금 옮겼던 **VMwareTools-버전번호.tar.gz**파일이 있는지 확인한다.

5. 파일이 존재하면 **$ tar zxf VMwareTools-버전번호.tar.gz**를 입력한다. ^압축풀기^

6. **ls**를 다시 입력하면 **vmware-tools-distrib**라는 폴더가 생긴것을 알 수 있다.

7. **$ cd vmware-tools-distrib/**를 입력하고 엔터키를 누른다.

8. **$ sudo ./vmware-install.pl**을 입력하고 엔터키를 누른다.

9. 계정 비밀번호를 입력한다음 처음 질문에 **y**를 입력하고 엔터키를 눌러준 다음 질문이 나올 때마다 엔터키를 눌러준다.

10. 설치가 완료되면 **$ sudo reboot**를 입력하여 재부팅을 한다.

11. 이제 **vmware**창 크기를 조절함에 따라 화면 크기가 변하게 된다.

##Linux Mint 초기설정
1. **터미널**을 실행한다.

2. **$ sudo apt-get update**를 입력하고 엔터키를 누른  계정 비밀번호를 입력한다.

3. 설치가 완료 되면 **$ sudo apt-get upgrade**를 입력하고 엔터키를 누른 후 계정 비밀번호를 입력한다.

4. 질문이 나오면 읽어보고 해당되는 항목에 따라 값을 입력한다.

5. **Linux Mint**의 **초기설정**을 완료 하였다.

##gcc, g++, vim, git설치
1. **터미널**을 실행한다.

2. **$ sudo apt-get install gcc g++ vim git -y**를 입력하고 엔터를 누른 후 계정 비밀번호를 입력한다.

3. **gcc**, **g++**, **vim**, **git**을 설치 하였다.

##한글 키보드 입력기 설치
1. **터미널**을 실행한다.

2. **$ sudo apt-get install uim uim-byeoru -y**를 입력하고 엔터를 누른 후 계정 비밀번호를 입력한다.

3. 설치가 완료되면 작업표시줄의 **메뉴**를 클릭한다.
 
4. 검색창에 다음과 같이 **uim**을 검색한다.

	![](http://i.imgur.com/le9Dr4x.png "title" "width:500px;")
    
5. 검색된 입력기 중 커서가 위치한 두번째 것을 클릭한다.

	![](http://i.imgur.com/BKVe6m2.png "title" "width:500px;")
    
6. **그룹-벼루 키 설정 1**에 들어가 **[벼루] 한글모드로** 에 **편집**을 클릭한다.

	![](http://i.imgur.com/XTwLTl9.png "title" "width:500px;")
    
7. **키** 항목에 커서를 대고 한글모드로 바꿀때 사용할 단축키나 커맨드 키를 입력한다.

	![](http://i.imgur.com/0dimKbj.png "title" "width:500px;)
    
    **추가**를 클릭하고 **닫기**를 클릭한다.
    
    ![](http://i.imgur.com/x0dnodU.png "title" "width:500px;)
    
8. **[벼루] 영문모드로** 항목도 위와 같이 반복하고 다음처럼 설정되면 **확인**을 클릭한다.

	![](http://i.imgur.com/XoJdEwE.png "title" "width:500px;")
    
9. 	이제 **Linux Mint**에서 **한글입력**이 가능하게 되었다.