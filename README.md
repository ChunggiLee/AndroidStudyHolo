# AndroidStudyHolo

Android Holo Color Generator 를 이용한 안드로이드 layout

1. http://android-holo-colors.com/ 에 접속한다. </br>
접속 후 </br>
![Alt Text](https://github.com/ChunggiLee/AndroidStudyHolo/blob/master/Theme%20Name.png) </br>
그림과 같이 테마 창을 원하시는 이름으로 바꿉니다.</br>
저는 그냥 AppTheme으로 하겠습니다.

2. 원하시는 색깔로 바꿉니다.</br>
![Alt Text](https://github.com/ChunggiLee/AndroidStudyHolo/blob/master/Select%20Color.png) </br>
저는 #f90909 색상으로 하겠습니다.</br>

3. 원하시는 컴포넌트를 No 에서 Yes로 바꿉니다. </br>
![Alt Text](https://github.com/ChunggiLee/AndroidStudyHolo/blob/master/Check%20Component.png) </br>
저는 EditText, Button, CheckBox, Radio를 사용하겠습니다. </br>

4. 다운로드 버튼을 클릭합니다.</br>
![Alt Text](https://github.com/ChunggiLee/AndroidStudyHolo/blob/master/Download.png) </br>

5. android-holo-colors-apptheme .zip 파일이 생성됩니다. 그후 압축을 풀어줍니다.
(이미지)

6. 그림과 같은 파일들이 생성됩니다.
(이미지)

7. 이제 안드로이드 프로젝트를 생성합니다.
그후 안드로이드 스튜디오에 res/values 폴더 안에 colors.xml 파일을 생성합니다.
다운로드 받은 파일 안에서 values/colors_apptheme.xml 안에 내용을 복사합니다.
(복사한 이미지)

안드로이드 스튜디오에 res/values 폴더 안에 styles.xml 에 다운로드 받은 파일 안에서 values/styles_apptheme.xml 안에 내용을 복사합니다.
(복사한 이미지)

안드로이드 스튜디오에 res/values 폴더 안에 themes.xml 파일을 생성합니다.
다운로드 받은 파일 안에서 values/themes_apptheme.xml 안에 내용을 복사합니다.
(복사한 이미지)

8. styles.xml 파일에서 에러가 났는데 수정해보도록 하죠.
이 에러는 이미지 파일과 xml이 없어서 발생한 에러입니다.
다운로드 받은 파일 안에서 이 4개의 폴더를 (drawable-hdpi, drawable-mdpi, drawable-xhdpi, drawable-xxhdpi) control + c한 후 안드로이드 스튜디오 drawable 폴더에 control + v합니다.

9. 이제 drawable 폴더에 xml파일을 추가하다록 하죠.
다운로드 받은 폴더에서 drawable안에 있는 모든 xml 파일을 안드로이드 스튜디오 drawable에 추가해주면 됩니다.
xml 파일과 여기잇는 변수들과 이름이 같아야합니다.


