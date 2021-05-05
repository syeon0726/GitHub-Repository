# Git 사용법 및 MarkDown Project 작성 보고서 
    git bash와 git을 사용하는 과정을 명시적으로 보여줌으로써 사용법을 쉽게 익히고 이와 동시에 project를 진행하는 과정도 동시에 포함한다.
---


# 1. Project 시작 전 준비단계
    git commit에 사용될 사용자를 등록하고 git bash를 본격적으로 사용할 준비를 완료한다

    



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
    MarkDownProject file을 생성하고 branch를 통해 file을 관리하도록 한다.
    
 ## _**touch**_
 
 ![7](https://user-images.githubusercontent.com/78208821/117097900-e18a1a00-ada7-11eb-91a1-1fbfd48661b8.png)
 > touch라는 명령어를 통해 MarkDownProject.md file을 생성해준다
 >>Result
 >>![8](https://user-images.githubusercontent.com/78208821/117097907-e5b63780-ada7-11eb-933e-0e08311c092f.png)
 >>> 현재 directory에 MarkDownProject.md 가 생성되었음을 확인 할 수 있다.
 
 
 ---
 
 ## _**git add & git commit & git push**_
 
 ### git add filenae
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





