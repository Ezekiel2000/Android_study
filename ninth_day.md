# 9일차 정리


## Animation
* android 의 View 들은 여러가지 Animation 효과를 가질 수 있음.
* Animation 속성은 res/anim 디렉토리에 xml 파일로 지정할 수 있음
* 2개 이상의 animation 을 중첩하고자 할 때는 set 태그를 사용함
* 서서히 사라지거나 나타나게 하는 효과는 alpha 태그로 지정할 수 있음
* 회전하는 효과는 rotate 태그로 지정할 수 있음
* 확대/축소하는 효과는 scale 태그로 지정할 수 있음
* Animation 효과가 바로 적용되는 것이 아니라 onClick 메서드가 리턴되고 나서 main thread 가 처리해줌


### ObjectAnimator
* JellyBean 때부터 ObjectAnimator 가 나왔음
* XML 대신 Java 코드로 애니메이션 효과들을 기술할 수 있음
* AnimatorSet 을 사용하여 Animation 효과들의 속성을 설정할 수 있음



## Shape / Selector / Style
* Shape : View 의 테두리 모양을 정의하는 기능
* Selector : View 의 상태에 따라 달리 적용할 Drawable 의 리스트를 정의하는 기능
* Style : View 의 속성을 별도로 모아서 이름을 부여해서 재활용해서 쓸 수 있는 기능


## Scrolling
* App Bar 구조에 CollapsingToolbarLayout 이 추가되어서 Toolbar 와 다른 View 를 관리
* CollapsingToolbarLayout 은 AppBarLayout, scrollable view(RecyclerView), FAB 을 자식 View로 두면서 이들을 Coordinate함.
* 스크롤 플래그로는 여러가지 것들이 있는데 이것들을 조합하여 스크롤 되게 함








