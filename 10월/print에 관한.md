# print

print 하나로 여러 개의 값을 출력하는 방법과 출력 형태를 설정하는 방법을 알아보자.


print에는 변수나 값 여러 개를 ,(콤마)로 구분하여 넣을 수 있음.

![image](https://user-images.githubusercontent.com/80689330/137737445-467071a2-e68c-4ad1-adfc-00333515bec5.png)

print에 변수나 값을 콤마로 구분해서 넣으면 각 값이 공백으로 띄워져서 한 줄로 출력됨. 

----------------------
값 사이에 공백이 아닌 다른 문자를 넣을땐 print의 sep에 문자 또는 문자열을 지정하자.

![image](https://user-images.githubusercontent.com/80689330/137739060-728f1f8d-cc2a-42c0-88ff-70c07ecca09d.png)


--------------------------------
이번엔 줄바꿈을 활용해보자

![image](https://user-images.githubusercontent.com/80689330/137739093-e821562e-4444-4c6b-82b2-93a92878ab87.png)

-------------------------
여기서 역슬래쉬를 표현하기 위해선

![image](https://user-images.githubusercontent.com/80689330/137739251-7903937c-b8a3-44da-a2ba-8677398e5379.png)

글꼴을 georgia로 바꿔주면

원화 표시를 역슬래쉬로 바꿔줄 수 있다.   보통 프로그램 언어로는 역슬래쉬 쓰니 참고하자.

![image](https://user-images.githubusercontent.com/80689330/137739294-dadbf6a6-b804-47d6-8932-02ef7ed1f110.png)

--------------------
\n은 값을 다음 줄에 출력하게 만드는 제어 문자. 

따라서 sep에 \n을 지정하면 1 2 3 사이에 \n이 들어가므로

1을 출력한 뒤 다음 줄에 2를 출력하고 다시 다음 줄에 3을 출력하게 됨. 

단, \n 자체는 제어 문자이므로 화면에 출력되지 않음.

![image](https://user-images.githubusercontent.com/80689330/137740423-7864f672-0691-4bca-8c00-9c5c12f15bec.png)


-------------
# 제어문자 종류

\n: 다음 줄로 이동하며 개행이라고도 부름

\t: 탭 문자, 키보드의 Tab 키와 같으며 여러 칸을 띄움

\\: \ 문자 자체를 출력할 때는 \를 두 번 써야 함.

---------------------
# end

![image](https://user-images.githubusercontent.com/80689330/137740595-8a93b6d6-c86a-4c4d-a8d2-a36472f64b14.png)


![image](https://user-images.githubusercontent.com/80689330/137740607-81c8034c-9a28-4651-8323-772ba9affc70.png)


기본적으로 print의 end에 \n이 지정된 상태인데 

빈 문자열을 지정하면 강제로 \n을 지워주기 때문

![image](https://user-images.githubusercontent.com/80689330/137740646-4da7e3e8-e891-43e6-b818-b1a87efe8a36.png)

공백을 주게 되면 띄어쓰기 됨.

