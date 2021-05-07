# __<Markdown 사용법>__


## __목차__

>1. 제목</br>1-1. 대체 구문
>2. 단락</br>
>3. 줄바꿈( 개행 )</br>
>4. 강조</br>4-1. 볼드체</br>4-2. 이탤릭체</br>4-3. 볼드체 + 이탤릭체
>5. 인용구</br>
>6. 목록</br>6-1. 정렬목록</br>6-2. 비정렬목록</br>6-3. 목록에 추가할 수 있는 요소
>7. 수평선</br>
>8. 링크</br>8-1. 링크의 서식지정
>9. 이미지</br>9-1. 이미지에 링크 추가
>10. 이스케이프 문자</br>
>11. HTML</br>


<br>

---

---

+ ## __1-1. 대체 구문__
    ### 용도</br>
    + _**1. 제목**_ 과 마찬가지로 제목, 문단별 제목을 쓸때 활용한다.</br></br>
    ### 사용법 </br>
    + 큰 제목(문서 제목)밑 줄에 **==** 를 추가하고 작은제목(문서 부제목)부터는 밑 줄에 **--** 를 추가해주도록 한다.  </br>
    
>>Example 

    # TITLE
    ## TITLE
    ### TITLE
    #### TITLE
    ##### TITLE
    ###### TITLE

>>출력 결과
# TITLE
## TITLE
### TITLE
#### TITLE
##### TITLE
###### TITLE



___

___

</br></br>

> ## __2. 단락__

### 용도</br>
+ 단락을 만들고자 할 때 활용한다.</br></br>
    
### 사용법</br>
+ 단락을 만들기 위해서는 <u>빈 줄을 사용하여 하나 이상의 텍스트 줄을 분리</u>하도록 한다.</br>
>>Example 
    
    I really like using Markdown.

    I think I'll use it to format all of my documents from now on.

>>출력 결과

I really like using Markdown.

I think I'll use it to format all of my documents from now on.

___

___

</BR></BR>

>## __3. 줄 바꿈( 개행 )__
### 용도</br>
+ 줄을 바꾸고자 할 때 활용한다.</br></br>
    
### 사용법</br> 
1. <u>두개이상의 공백</u>( 띄어쓰기 활용 )을 만든다.
2. 또는 <u>``</br>``</u>이라는 html 태그를 이용한다.

>>Example 
    
    example sentence1(space)(space)(enter)example sentence2</br>example sentence3

>>출력 결과

example senetence1  
example sentence2</br>example sentence3


</BR></BR>
> ## __4. 강조__

### 용도</br>
+ 문장 내 강조하고 싶은 단어를 눈에 띄게 하고싶을때 활용한다.</br> 
볼드체(굵은 체), 이탤릭체(기울임 체)또는 이 둘의 특징을 합친 글씨체를 만들 수 있다.</br></br>
    
+ ## **4-1. 볼드체( 굵은 체 )**

    ### 사용법 </br>
    단어 또는 구문 앞뒤에 두 개의 * 또는 두개의 _을 추가해준다.

    >>Example 

        **I love you.**
        I **love** you.
        __I love you.__
        I __love__ you.
   

    >>출력 결과

    **I love you.**  
    I **love** you.  
    __I love you.__  
    I __love__ you.

     </br>
+ ## **4-2. 이탤릭체( 기울임 체 )**

    ### 사용법 </br>
        단어 또는 구문 앞뒤에 한 개의 * 또는 한개의 _을 추가해준다.

         >>Example 

        *I love you.*
        I *love* you.
        _I love you._
        I _love_ you.
   

    >>출력 결과

    *I love you.*  
    I *love* you.  
    _I love you._  
    I _love_ you.



    </br>

+ ## **4-3. 볼드체 + 이탤릭체( 혼용체 )**

    ### 사용법 </br>
    *과 _을 3개씩 쓰거나 
    " *의개수 " + "_의개수 " = 3 개
    가 되도록 활용한다. ( 앞 뒤 형식은 대칭이 되도록 맞춰 줄 것 )

    >>Example 

        ***I love you.***
        I ___love___ you.
        __*I love you.*__
        I **_love_** you.
   

    >>출력 결과

    ***I love you.***  
    I ___love___ you.  
    __*I love you.*__  
    I **_love_** you.
    
    
___

___

</BR></BR>

>## __5. 인용구__
### 용도</br>
+ 인용할 경우 또는 분위기 전환시에 활용한다.</br></br>
    
### 사용법</br> 
+   ``>``를 활용한다.

>>Example 
    
    >##example sentence1
    >
    >
    >
    >>example **sentence2**
    >>>_example sentence3_

>>출력 결과

>## example sentence1
>
>
>
>>example **sentence2**
>>>_example sentence3_


___
___

</BR></BR>

>## __6. 목록__
### 용도</br>
+ 항목을 나열하고자 할때 활용한다.</br></br>
    
+ ## **6-1. 정렬 목록**

    ### 사용법 </br>
        숫자 뒤에 마침표( . )를 찍고 공백 한칸을 추가해준다.
         >>Example 

        1. example sentence1
        2. example sentence2
        3. example sentence3
    </br>
        
        1. example sentence1
        1. example sentence2
        1. example sentence3
    </br>
        
        1. example sentence1
        8. example sentence2
        3. example sentence3
    </br>

        1. example sentence1
        2. example sentence2
            1. example sentence2-1
            2. example sentence2-2
        3.example sentence3

    >>출력 결과

    1. example sentence1  
    2. example sentence2  
    3. example sentence3
    </br>

    ---

        
    1. example sentence1
    1. example sentence2
    1. example sentence3
    </br>

    ---
        
    1. example sentence1
    8. example sentence2
    3. example sentence3
    </br>

    ---

    1. example sentence1
    2. example sentence2
        1. example sentence2-1
        2. example sentence2-2  
    3. example sentence3



    </br>
+ ## **6-2. 정렬되지 않은 목록**

    ### 사용법 </br>
        정렬되지 않은 목록을 만들려면 라인 항목 앞에 대시( - ), 별표 ( * ), 또는 더하기( + )를 추가 한다. 
        중첩된 목록을 만들기 위해서는 하나 이상의 학목을 들여쓰기 해준다.
         >>Example 

        - example sentence1
        - example sentence2
        - example sentence3
    </br>
        
        - example sentence1
        + example sentence2
        * example sentence3
    </br>
        
        + example sentence1
        + example sentence2
            + example sentence2-1
            + example sentence2-2
        + example sentence3
    </br>

        + example sentence1
        * example sentence2
            + example sentence2-1
            - example sentence2-2
        - example sentence3

   

    >>출력 결과
    - example sentence1
    - example sentence2
    - example sentence3
    </br>

    ___

    - example sentence1
    + example sentence2
    * example sentence3
    </br>

    ___

    + example sentence1
    + example sentence2
        + example sentence2-1
        + example sentence2-2
    + example sentence3
    </br>

    ___

    + example sentence1
    * example sentence2
        + example sentence2-1
        - example sentence2-2
    - example sentence3

</BR></BR>

+   ## **6-3. 목록에 추가할 수 있는 요소**

    ### 1.  단락 </br>
     >>Example 

        + example sentence1
        + example sentence2

            > example element1

        + example sentence3

    >>출력 결과

    + example sentence1
    + example sentence2

        > example element1

    + example sentence3
    ___

    ### 2.  인용구 </br>
    >>Example 
        + example sentence1
        + example sentence2

            example element1

        + example sentence3

    >>출력 결과

    + example sentence1
    + example sentence2

        example element1

    + example sentence3
    ___

    ### 3. code block </br>
    + code block은 일반적으로 탭 1개로 들여쓰기해서 만들 수 있다.</br>
    + 하지만 목록에 code block을 추가하고자 할경우 탭 2개로 들여쓰기 한다.
     >>Example 
        1. example sentence1
        2. example sentence2

                 example element1
                    example element2

        3. example sentence3

    >>출력 결과

    1. example sentence1
    2. example sentence2

            example element1
                example elemtent2

    3. example sentence3
    ___

    ### 4. 그 외
        이미지, 링크를 활용할 수 있다. 이에관해서는 후에 배워보도록 하자.
        
    ___

    ___

    </BR></BR>
## __7. 수평선__
### 사용법</br> 
+   3개 이상의 별표(***), 대시(---) 또는 밑줄(___)을  한줄에 단독으로 사용한다.
>>Example 
    
    example sentence1

    ***

    example sentence2

    ___

    example senstence3

    _______________________

>>출력 결과

example sentence1

***

example sentence2

___

example senstence3

_______________________
___

___

</BR></BR>

## __8. 링크__
### 사용법</br> 
+   링크 텍스트를 대괄호[  ]로 묶어준 뒤 바로 뒤에 있는 URL을 ( )로 묶어준다.
+ 바로 링크를 추가해주고자 할 경우에는 < >로 묶어준다.
+ 링크를 강조하는 것도 가능하다.
>>Example 
    
    GO TO [GOOGLE](https://www.google.co.kr).

    <https://www.google.co.kr>

    GO TO *[GOOGLE](https://www.google.co.kr)*.

    **<https://www.google.co.kr>**

>>출력 결과

GO TO [GOOGLE](https://www.google.co.kr)

<https://www.google.co.kr>

GO TO *[GOOGLE](https://www.google.co.kr)*.

**<https://www.google.co.kr>**

+ ## **8-1. 링크의 서식 지정**

    + 참조 스타일 링크 </br>
        + 참조 스타일 링크는 Markdown에서 URL을 더 쉽게 표시하고 읽을 수 있게 해주는 특수한 링크이다.
         >>Example1 ( 링크의 첫 번째 부분 서식 지정)
        + 첫번째 [ ]에는 링크 텍스트를 작성한다.
        + 두번째 [ ]에는 레이블을 표시한다.


        [google-link][1]

    >>Example2 ( 링크의 두 번째 부분 서식 지정)
    + 레이블이 표시된 두번째 [ ] <u>바로 뒤에 콜론( ; )을 붙이고 하나이상의 공백</u>을 만든다.<br>그리고 링크를 달아준뒤 뒤에 선택적으로 제목을 달아줄 수 있다.

            [1]: https://www.google.co.kr
            [1]: <https://www.google.co.kr>

            >>두 번째 서식을 지정하는 다양한 방법<<

            [1]: https://www.google.co.kr 'google'
            [1]: https://www.google.co.kr "google"
            [1]: https://www.google.co.kr (google)

            [1]: <https://www.google.co.kr> 'google'
            [1]: <https://www.google.co.kr> "google"
            [1]: <https://www.google.co.kr> (google)

    >>Example3 ( 활용 )

            GO TO [google-link][1]

            [1]:  https://www.google.co.kr

            GO TO [google][2]

            [2]: <https://www.google.co.kr> "google"




    >>출력 결과

    GO TO [google-link][1]  

    [1]:  https://www.google.co.kr

    GO TO [google][2]

    [2]: <https://www.google.co.kr> "google"


 ___

___

</br></br>

## __9. 이미지__
### 사용법</br> 
+   느낌표 ( ! )를 찍고 바로 뒤 [ ]안에 대체 텍스트를 삽입후 바로뒤 ( ) 안에 이미지의 경로 또는 URL을 추가한다. 선택적으로 괄호 안의 URL 뒤에 제목을 추가 할 수도 있다.
>>Example 
    
    ![Kuromi](https://i.pinimg.com/originals/fa/b8/2e/fab82edb5148c4899272d767d2b8b6b1.gif )

    ![Kuromi](https://i.pinimg.com/originals/0e/39/db/0e39db6b419a3cb9fbc81b2b41a42b4a.gif "cute Kuromi")

    
    

>>출력 결과

![Kuromi](https://i.pinimg.com/originals/fa/b8/2e/fab82edb5148c4899272d767d2b8b6b1.gif)

![Kuromi](https://i.pinimg.com/originals/0e/39/db/0e39db6b419a3cb9fbc81b2b41a42b4a.gif "cute Kuromi")
___
+ ## **9-1. 이미지에 링크 추가**

    + 사용법
      + 이미지의 Markdown을 [ ]로 묶어준 뒤 바로 뒤에 ( )를 추가해 괄호안에 링크를 추가해준다.
       >>Example

            [![Kuromi](https://i.pinimg.com/originals/bd/76/5d/bd765def594d116af21de47493771cf6.gif
            )](https://i.pinimg.com/originals/bd/76/5d/bd765def594d116af21de47493771cf6.gif)
        

    >>출력 결과

    [![Kuromi](https://i.pinimg.com/originals/bd/76/5d/bd765def594d116af21de47493771cf6.gif)](https://i.pinimg.com/originals/bd/76/5d/bd765def594d116af21de47493771cf6.gif)


      ___

___

</br></br>
## __10. 이스케이프 문자__
### 사용법</br> 
+   Markdown 문서에서 텍스트 서식을 지정하는 데 사용되는 리터럴 문자를 표시하려면 문자 백슬러시( \ )를 추가한다 .
>>Example 

    원래문장
    **example sentence1**
    _example sentence_

    백 슬래시를 추가해줄경우
    \*\*example sentence1\*\*
    \_example sentence\_
   

>>출력 결과

원래문장

**example sentence1**  
_example sentence_

백 슬래시를 추가해줄경우  
\*\*example sentence1\*\*  
\_example sentence\_

___

___

</br></br>

## __11. HTML__

 수많은 Markdown 응용 프로그램을 사용하면 Markdown 형식의 텍스트에서 HTML tag를 사용할 수 있다.</br>
HTML을 사용하려면 Markdown 형식 파일의 텍스트에 HTML tag를 배치하도록 한다.
>>Example 

    원래문장
    ## example sentence 
    ( 미리보기시 변환 X )

    HTML tag 사용 문장
    <h2>example sentence</h2> 
    ( 미리보기시 변환 O)
   

>>출력 결과

원래문장
## example sentence 
( 미리보기시 변환 X)

HTML tag 사용 문장
<h2>example sentence</h2> 
( 미리보기시 변환 X )

