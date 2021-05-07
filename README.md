https://github.com/syeon0726/Github-Repository.git

# Git 사용법 및 MarkDown Project 작성 보고서 
   + Git Bash와 GitHub를 사용하는 과정을 명시적으로 보여줌으로써 사용법을 쉽게 익히고 이와 동시에 project를 진행하는 과정도 동시에 포함한다.
   
   목차
   ---
   
   1. Project 시작 전 준비단계</br>
    1-1. git config</br>1-2. git init</br>1-3. git remote</br>1-4. git status
   2. 본격적인 Project 시작 단계</br>
    2-1. touch</br>2-2. git add & git commit & git push</br>2-3. git clone & git branch & git checkout
   
---


# 1. Project 시작 전 준비단계
    git commit에 사용될 사용자를 등록하고 git bash를 본격적으로 사용할 준비를 완료한다


---
    



## _**git config**_
### git config -- global user.name "username"
### git config -- global user.eamil "useremail"
![1](https://user-images.githubusercontent.com/78208821/117092855-5f472900-ad9a-11eb-8d53-2b1f66d2b88d.jpg)
> git commit에 사용될 username과 email을 등록해준다.</br>최초 1번만 실행한다.
### git config --list
![2](https://user-images.githubusercontent.com/78208821/117092858-60785600-ad9a-11eb-8b39-50a143817ac7.jpg)
> git config --list를 통해 설정한 내용을 확인 할 수 있다.</br> 맨 마지막 두줄을 보면 알 수 있다시피 사용될 username과 email이 옳바르게 등록되었음을 알 수 있다.

---


## _**git init**_
![3](https://user-images.githubusercontent.com/78208821/117093539-34f66b00-ad9c-11eb-9a1d-50b0387b59ca.png)
> git init을 통해 현재 위치해있는 디렉토리를 로컬저장소로 설정해준다.</br>(master) branch로 보이면 성공했음을 의미한다

---

## _**git remote**_

### git remote add origin 원격저장소주소
![4](https://user-images.githubusercontent.com/78208821/117094908-f367bf00-ad9f-11eb-8d89-acb9551f767f.png)
> GitHub 원격저장소와 내 로컬저장소를 연결해준다.</br>이 때 origin은

### git remote -v
![5](https://user-images.githubusercontent.com/78208821/117094926-f95da000-ad9f-11eb-81f5-185be0f99b4e.png)
>원격저장소가 제대로 연결되어있는지 확인할 수 있다.

---

## _**git status**_
![6](https://user-images.githubusercontent.com/78208821/117097064-a25ac980-ada5-11eb-9f9b-4b60ee33d557.png)
> 로컬 저장소의 현재 상태를 보여준다.</br>현재 아무런 commit을 날려준적이 없기 때문에 Not commits yet이라는 문장이 출력된다.

---

# 2. 본격적인 Project 시작 단계
    MarkDownProject file을 생성하고 새로운 branch 생성을 통해 Project file을 관리하도록 한다.
    
 ## _**touch**_
 
 ![7](https://user-images.githubusercontent.com/78208821/117097900-e18a1a00-ada7-11eb-91a1-1fbfd48661b8.png)
 > touch라는 명령어를 통해 MarkDownProject.md file을 생성해준다
 >>Result
 >>![8](https://user-images.githubusercontent.com/78208821/117097907-e5b63780-ada7-11eb-933e-0e08311c092f.png)
 >>> 현재 directory에 MarkDownProject.md 가 생성되었음을 확인 할 수 있다.
 
 
 ---
 
 ## _**git add & git commit & git push**_
 
 ### git add filename
![9]( https://user-images.githubusercontent.com/78208821/117115738-7c92ec00-adc8-11eb-9644-b96cff45f85e.png)
> MarkDownProject.md file을 *준비영역(Statiting Area)* 로 옮겨준다. </br>GitHub와 연동하려면 git remote로 원격 저장소와 연결해주는 과정이 필수이다.

### git commit -m "message"
![10](https://user-images.githubusercontent.com/78208821/117115748-80267300-adc8-11eb-9d66-8ffb414c57f6.png)
> *준비영역(Stating Area)* 의 file을 **로컬저장소**에 저장을 해준다.</br>간단한 커밋 메시지를 입력후 커밋을 하는것을 추천한다.

### git push origin master
![11](https://user-images.githubusercontent.com/78208821/117115761-83216380-adc8-11eb-89a1-7587bb30733c.png)
> 로컬 저장소에 저장되있는 file들을  **원격저장소(Git Hub)**에 저장해준다
>>Result
>>![12](https://user-images.githubusercontent.com/78208821/117121003-05148b00-adcf-11eb-9f8f-22d46e79dfdd.png)
>>> 현재 원격저장소의 default branch는 **main**이기 때문에 master branch가 생성됨과 동시에 master branch에 MarkdownProject가 업로드 되었음을 확인 할 수 있다.



 ## _**git clone & git branch & git checkout**_
 
 + 이제 project를 따로 관리할 branch를 생성하고 우리가 만들었던 MarkDownProject.md라는 file을 가져오는 작업을 하도록 한다. 
 
 ### git clone
 ![12](https://user-images.githubusercontent.com/78208821/117156018-3d7c8f00-adf8-11eb-9515-d64ba87cc3b8.png)
 > 먼저 기존에 올려두었던 github의 project를 clone이라는 명령어를 통해 가져온다.
 >>Result</br>
 >>![13](https://user-images.githubusercontent.com/78208821/117158353-4bcbaa80-adfa-11eb-85af-86cdb924a962.png)
 >>>현재 작업 directory에 원격저장소의 내용들이 그대로 저장되어 있음을 확인할 수 있다.
 
 ### git branch branchname
 ![14](https://user-images.githubusercontent.com/78208821/117156119-5422e600-adf8-11eb-84ff-bb78479adb25.png)
 >새로운 branch를 생성하는 명령어이다.</br> 이전에 commit한 이력이 없다면 새로운 branch를 생성하는게 불가능하다.
 
 ### git checkout branchname
 ![15](https://user-images.githubusercontent.com/78208821/117156119-5422e600-adf8-11eb-84ff-bb78479adb25.png)
 >내가 지정한 branch로 이동하는 명령어이다.</br> git branch 라는 명령어를 통해 현재 내 branch list들을 확인해주도록 하자.
 ></br>git checkout -b branchname 을 할경우 새로운 branch를 생성해줌과 동시에 자동으로 그 branch로 이동한다.
 
 ### git push --set-upstream origin branchname
 ![16](https://user-images.githubusercontent.com/78208821/117156150-5c7b2100-adf8-11eb-9ee0-ca89f1145859.png)
 > 원격 저장소에 해당 branch에 해당하는 정보를 update 해주는 명령어이다.
 >>Result</br>
 >>![17](https://user-images.githubusercontent.com/78208821/117156180-643ac580-adf8-11eb-8e28-e2e398bde2c7.png)
 >>> 원격 저장소에 정보가 저장되어있음을 확인할수 있다.
 
 
 ---
 
 # 3. 본격적인 Project 수행
 ## project 진행과정
 1. 목차 작성
 2. project 내용 작성
 3. 수정(보완) 부분 파악
 4. 수정 및 병함
 5. main branch로 최종 file 업로드

---
### 1. 목차 작성

### git pull
![18](https://user-images.githubusercontent.com/78208821/117242501-5aed3f80-ae70-11eb-8255-f8c0c1ed0941.png)
>remote에 있는 내용을 local 저장소에 받는 과정이다.</br>이때 현재 자신의 branch가 어디인지 확인을 잘 하고 pull하도록 한다.</br>만약 자신의 local에 변경사항이 있다면 oull할 시 error가 나므로 add, commit을 진행을 한 후 pull하거나 stash하여 자신의 변경사항을 다른곳에 저장한 후 pull하도록 한다.</br> local 작업 시작 전에 무조건 pull을 해준다.</br>remote 저장소에 변경된 사항이 있을 수 있기 때문이다.
>>Result</br>
>>![19](https://user-images.githubusercontent.com/78208821/117242513-5e80c680-ae70-11eb-8af0-fe7f58547cdc.png)
>>>내 directory에 file이 올라와있음을 확인할 수 있다.

---

![19](https://user-images.githubusercontent.com/78208821/117431996-d16b6980-af64-11eb-8c92-195b37dac3e0.png)
>원격 저장소에서 받아온 file의 목차를 작성해준뒤 저장해준다

![20](https://user-images.githubusercontent.com/78208821/117432046-dfb98580-af64-11eb-8d2d-778e2eddd077.png)
>아까전과 똑같은 작업을 반복해준다.</br> git add로 준비 영역(Stating Area)에 file을 업로드 한 뒤 git commit을 사용해 로컬 저장소에 file을 저장해준다.</br>마지막으로 git push를 이용해원격저장소에 file을 upload해준다.
>>Result</br>
>>![21](https://user-images.githubusercontent.com/78208821/117432051-e34d0c80-af64-11eb-9d28-fdc1763a258d.png)</br>
>>![22](https://user-images.githubusercontent.com/78208821/117432091-ecd67480-af64-11eb-9f25-eede70da3c65.png)
>>commit message를 확인할 수 있다.</br> 그리고 변경사항이 원격저장소에 잘 반영되있음을 확인 할 수 있다.

---

### git log
![22](https://user-images.githubusercontent.com/78208821/117432064-e7792a00-af64-11eb-9c6c-2f5b1910c4a9.png)
> 로컬 저장소의 commit 이력을 확인할 수 있다.</br>


 
 
 
 
 
 


