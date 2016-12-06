# 9일차 정리


## Animation
* android 의 View 들은 여러가지 Animation 효과를 가질 수 있음.
* Animation 속성은 res/anim 디렉토리에 xml 파일로 지정할 수 있음
* 2개 이상의 animation 을 중첩하고자 할 때는 set 태그를 사용함
* 서서히 사라지거나 나타나게 하는 효과는 alpha 태그로 지정할 수 있음
* 회전하는 효과는 rotate 태그로 지정할 수 있음
* 확대/축소하는 효과는 scale 태그로 지정할 수 있음


### ObjectAnimator
* JellyBean 때부터 ObjectAnimator 가 나왔음
* XML 대신 Java 코드로 애니메이션 효과들을 기술할 수 있음

