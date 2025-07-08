### 구성환경 설정하기

![img](https://blog.kakaocdn.net/dna/yLaYg/btrlsieFiNp/AAAAAAAAAAAAAAAAAAAAAMxDMnU9Lb8mFzY_YruR1ASB5VGtj0Asi3yXDutesi_O/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=EzQmwU6MYW1H%2F%2FYkCqEm2mlAbxs%3D)



\* 게시판 프로그램을 만들 예정 

 



![img](https://blog.kakaocdn.net/dna/LXppW/btrlmnB3sPO/AAAAAAAAAAAAAAAAAAAAAOBDNOoySFAHdYJkCbSDnLQ5o6AfaS3WIySBe_8Xl0oJ/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=3IwfNPWoWK%2FkIzYHUxl1LZSeAKU%3D)



\* EJB(환경설정에서 개발자들이 죽어남..?) -> Spring framework 연구

\* framework 와 library의 차이점

\- framework : 4세대 이상 객체지향 언어 (c#, java, python,tensorflow... ) - 의존성 주입언어 ex ) import ts as ...

\- library : 2세대 절차형 언어 (c언어 ...) 함수의 집합 ex ) function..

\* JAVA SPRING Framework(MVC)

\- 목표 :MVC구형 

\- exclusive : 로직을 배우기 위해서는 framework 이 좋다고 한다. 

\* spring boot 

\- 하나에서 다 구현 내장형 [편함 .. 자동 ,tomcat성능이 떨어짐]



![img](https://blog.kakaocdn.net/dna/cYMzMX/btrliNOxXpz/AAAAAAAAAAAAAAAAAAAAAI7qGVW84KbAH3eHrYtXUZ21MLk22QXbtDd8FU1rIdoE/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=g7%2BhsrjhFxyzGOv0KsC%2B18MGhB8%3D)



\* 용어를 꼭 기억해야 함 

\* 문서를 잘 만들어야 함 

 





![img](https://blog.kakaocdn.net/dna/vWpkm/btrlpclZ8us/AAAAAAAAAAAAAAAAAAAAAEEFzKVi_IQrPRTQVjSq9CKkUy9MgXxGqcW9h1kAbjUo/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=eWpOIGIy7ZcrJSpnLqcwIAn0T3k%3D)

 

\* 웹브라우저와 서버간의 데이터를 주고 받는 역할 

\* 프로그램의 주목적 : 요청을 받아서 db에 접속해서 화면에 뿌린다. 

\* DAO 용어 알기 

\* WAS에서 웹브라우저와 서버간의 데이터를 뿌려지는 용어 





![img](https://blog.kakaocdn.net/dna/qu3vk/btrlpcM2vMa/AAAAAAAAAAAAAAAAAAAAAD46omyVZ4HDWGIp1wTG7JdWYww3eJzj300lo_azWj39/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=Q6hHwXF7bfhogMweRH4MYRoEO6M%3D)

 

\* 본 호환으로 구성해야함 

![img](https://blog.kakaocdn.net/dna/ccHFMk/btrloyJCJJR/AAAAAAAAAAAAAAAAAAAAAM72tFKJxUxLMyM7LEdFtJmZsKFMKj2XdCpv1QR975ic/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=xvFe4XFC9BtbDNHjQD5yC36vWcE%3D)

\* vmware 는 클라우드 기능을 구현할 수 있는 공부를 해볼 것 

1.다운로드 및 설치

 \* JDK 다운로드 : https://www.oracle.com/java/technologies/javase-downloads.html

 \* JRE 다운로드 : https://java.com/ko/download

\- JDK의 경우 - Java/JRE : 1.8.0로 이미 설치가 되어 있다. 

\* 윈도우 "/" 리눅스 "\"

2. 환경변수 확인/추가

 \* 파일탐색기 실행 -> 내컴퓨터에서 오른쪽 마우스 클릭 -> 속성 -> 고급 시스템 설정

 \* 고급탭 클릭 -> 환경변수 클릭

 \* 시스템 변수 JAVA_HOME 경로 확인

 \* 시스템 변수 JRE_HOME 생성 : JRE 설치 경로 입력

 \* CLASSPATH 추가 : %java_HOME%\lib;

\* 리부팅

1.아파치 다운로드

  \* https://www.apachelounge.com/download/

버전 정보 : apache-tomcat-9.0.52



c드라이브에 압축 풀기&nbsp;

![img](https://blog.kakaocdn.net/dna/tYYj0/btrlqAzQiKY/AAAAAAAAAAAAAAAAAAAAAGVCNZWZqPIgPpuz1IvLGQmFPhMDIHXN3d-hGdSkkoeR/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=K0zNX9foKgqI1FfiaC7%2F%2FQCchPE%3D)

2. 아파치 환경설정 

[Apache_Home]/conf/httpd.conf 열기

응 ? 교수님이 주신 파일에 http.conf 파일이 없다... 

홈페이지로 이용하여 다시 다운로드 해줌 

 



![img](https://blog.kakaocdn.net/dna/bo8vhY/btrlpVK8Gyn/AAAAAAAAAAAAAAAAAAAAACS8HGdOuR_pe-XphpJb7M3pA_RkG6CTiVIdgONKBclZ/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=zGzmdVr6VvD%2FeYh9gfl0dGJDIDE%3D)



httpd-2.4.51-win64-VS16 다운로드

다시 c드라이브에 압축 풀기 

 

C:\httpd-2.4.51-win64-VS16\Apache24\conf 로 들어가니까 있다. 

![img](https://blog.kakaocdn.net/dna/lPUaT/btrlozaJptV/AAAAAAAAAAAAAAAAAAAAAJqIiWmc9G34ZHgz8kkg1c2qrgluKM4kkTmk31749BKp/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=sDp82E9YVnLksni%2BeojoO%2FvJc%2FA%3D)

*서버 루트 변경 : Define SRVROOT “[Apache_Home]"







\* 서버 네임 변경 : ServerName http://127.0.0.1

![img](https://blog.kakaocdn.net/dna/c6IZEn/btrlozV5CDu/AAAAAAAAAAAAAAAAAAAAANZ4-DhUi-p4EV25t78U-2GLoikNU0n8YOitpt7L4x_Y/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=%2FdxfvtaVp5hB7AvSuRqWyWxw9dY%3D)





\* 다큐먼트 루트 변경

\- 프로젝트는 D:\Spring Project 폴더를 생성해서 작업하고자 한다. 

 

​     DocumentRoot “[프로젝트 디렉토리]“

​    <Directory “[프로젝트 디렉토리]“>

​     ※ 반드시 \가 아닌 /로 입력



![img](https://blog.kakaocdn.net/dna/oaTXg/btrlpbgoSJZ/AAAAAAAAAAAAAAAAAAAAACJIVHRKV9Kr1FI-_JSEjn5JlJIxB7uBTjR_mtuVWpTD/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=VhYlJtru3O9MOar%2BW4G801iWMuc%3D)

![img](https://blog.kakaocdn.net/dna/bTdsBi/btrlgFQHqMU/AAAAAAAAAAAAAAAAAAAAABL7zVq6PKTh-pr50KFBA604Jv-6IAKpopvE-M8QQ_aI/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=TsqCt3AJ%2B3PYhQ1JUpEZ4aIECEM%3D)

\* 인코딩 코드 입력행 추가

​     AddDefaultCharset utf-8



![img](https://blog.kakaocdn.net/dna/r6zFJ/btrlqLVPn2n/AAAAAAAAAAAAAAAAAAAAAFaiB8ekD_jxV-fl_wIgXiOQzd87J9TzR9fE0C0HRd8Y/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=SESrMvqE301aTfuOOtEw5QPk0YE%3D)



3. 아파치 실행

  \* 관리자 권한으로 명령창 실행

  \* cd [Apache_Home]\bin

  \* httpd –k install(윈도우 서비스로 등록)

  \* 서비스 시작 : http –k restart

  \* 서비스 종료 : http –k stop



![img](https://blog.kakaocdn.net/dna/So8AO/btrlmnCc3Dk/AAAAAAAAAAAAAAAAAAAAAE8zKmAPJ8v_HOyYCsvXmpPlyEdR73CF-fZYcTI1h7jR/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=00dJ%2BDi0%2Bv69CaNzZiqie%2FnImJY%3D)



![img](https://blog.kakaocdn.net/dna/bg1EV9/btrlmoA5lxV/AAAAAAAAAAAAAAAAAAAAAA4vBtRIGTbEaTvL1Cd3LaV3MEuQJFnhR1gj-MMoGHFF/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=AEc14ZjO364klPDYTK1hmPjaStU%3D)

cd C:\httpd-2.4.51-win64-VS16\Apache24\bin



![img](https://blog.kakaocdn.net/dna/bCbAsY/btrlpdkZ1Tc/AAAAAAAAAAAAAAAAAAAAACarju1XgPHU_20HzyYlg1pQ9mhfY-4SuPRuF47mOUVW/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=36SHJqYKvghrAMvMmj3m82D2cns%3D)



\* httpd –k install(윈도우 서비스로 등록)

\* 서비스 시작 : httpd –k restart

에러뜬다.... 

원인 1. 이전에 깔려있던 Apache 가 충돌해서 오류 2. syntax 에러 .. 정말 황당 똑같았는데 다시 적어주니 된다. ** 중요 ! 카피하지 말고 다 일일이 적을 것 !!! 



![img](https://blog.kakaocdn.net/dna/vIrgO/btrlnSWhlkm/AAAAAAAAAAAAAAAAAAAAAAKDw7zyCwwEVu4mrl5-PQThimi0E1jnTA2da24224dz/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=rNe4gvx9lE%2FFHh837TaOmVC9CUs%3D)



실행 확인- Apache 끄기 *서비스 종료 : http –k stop

 

 

1.톰캣 다운로드

  *https://tomcat.apache.org/

\- WAS : Apache Tomcat/9.0.52

\* 프로젝트 들어가기 전에 호환성 반드시 확인할 것 

2. 톰캣 환경 설정

  \* [Tomcat_Home]\conf\server.xml 파일 수정

   <Connector protocol="AJP/1.3"

​        address="127.0.0.1"

​        port="8009"

​        redirectPort="8443“

​        secretRequired=“false”

   />

   <Host name="localhost" appBase=“[프로젝트 디렉토리]"

​       unpackWARs="true" autoDeploy=“true“ >

   <Context path=“/" docBase =“[프로젝트 디렉토리]"

​       unpackWARs="true" reloadble=“true" >

​    </Context>



![img](https://blog.kakaocdn.net/dna/cs7T94/btrlpbH4Y8m/AAAAAAAAAAAAAAAAAAAAAEsE4X8cqfVsJUeeTr1WJDiO9SpOGjxegyy_Y9kzlafB/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=NSpgoYYwUZAnJafTwFXH79X9bVA%3D)



![img](https://blog.kakaocdn.net/dna/cAepuG/btrlwJjeo4U/AAAAAAAAAAAAAAAAAAAAAOv-GtsDT9bRB1LMA5Z1_jMYg-rEtZWR4MdhafV3rrcN/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=3QM56KtjrWTfhX9zPGrFoUev9iM%3D)

\* 환경 변수 만들기 

  \* CATALINA_HOME,CATALINA_BASE 생성후 [Tomcat_Home]입력

  \* CATALINA_TMPDIR 생성후 [Tomcat_Home]\temp 입력 

  \* CLASSPTH 수정

   \- %java_HOME%\lib;.;%CATALINA_HOME%\lib;







 ![img](https://blog.kakaocdn.net/dna/m8OnU/btrlwJp1gqo/AAAAAAAAAAAAAAAAAAAAANJQhMtyaDZ8-2U019gc47zPwjrDuZjsVIaTR1lqHvE0/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=Scm1VqtMMururYcw%2BQup%2BOc2uYM%3D)



![img](https://blog.kakaocdn.net/dna/cAxehz/btrlozh84of/AAAAAAAAAAAAAAAAAAAAANZfQFNsi18zZLpTLMrj75Oax1-98uZ610ohNoRPwffb/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=%2BRq0AXB5lizCmyDKGm5aMbeBh4A%3D)



CATALINA_HOME,CATALINA_BASE 생성후 [Tomcat_Home]입력



![img](https://blog.kakaocdn.net/dna/BISod/btrlxgnlW1r/AAAAAAAAAAAAAAAAAAAAAB__sf89oMpSjNZG6v6hsN55kxYkPzZahugDzid4gz3X/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=8Zl0enfmSxhSj0xfCwdfT27Or7k%3D)



CATALINA_TMPDIR 생성후 [Tomcat_Home]\temp 입력 

\* CLASSPTH 추가 [원래는 JAVA 에서 만들어줘야 하는데 안 만들어서 추가해줌]

   \- %java_HOME%\lib;.;%CATALINA_HOME%\lib;



![img](https://blog.kakaocdn.net/dna/JavsH/btrlwwdfIhE/AAAAAAAAAAAAAAAAAAAAAC1B-Rl_3TL7Uq7Jrvo55UQy9zlMwfbgMHpC7lWae4eI/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=STd%2Fu%2Bi3fbmgYpHDRbTsdnEP8%2Bs%3D)



4. 톰캣 시작/중지

\* 명령 프롬프트에서 cd c:\apache-tomcat-9.0.52-windows-x64\apache-tomcat-9.0.52\bin

로 들어가서 startup.bat 실행 - tomcat 실행

shutdown - 중지



![img](https://blog.kakaocdn.net/dna/bwa7Wj/btrlpVLTrjT/AAAAAAAAAAAAAAAAAAAAAPH9dEto-v_ZFmbakJcLmxFD7tiT9mJpTqPOR-nSWlKi/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=6N5TXHdc%2FHc2eb4Dyvcu9SdAtAE%3D)



5. 톰캣 버전 확인

cd lib

java -cp catalina.jar org.apache.catalina.util.ServerInfo



![img](https://blog.kakaocdn.net/dna/AISSJ/btrlvCreuxX/AAAAAAAAAAAAAAAAAAAAAHdyVXNnBn3QIuHgqy7Rh-uHbRaILZpor7xNTDcwyYSA/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=PH9zigsSxz6Lj%2FirxqgPBm70Fa4%3D)



\* Servlet 환경 구성

1. 서블릿 디렉토리 생성

  \* [프로젝트 디렉토리] 하단에 WEB-INF 폴더 생성

  \* WEB-INF 디렉토리 하단에 classes, lib, src 폴더 생성

[TOMCAT_HOME]\webapps\ROOT\web.xml 파일을 [프로젝트 디렉토리]\WEB-INF 폴더 내로 복사   

 



![img](https://blog.kakaocdn.net/dna/c2T8Ae/btrloTgmCUF/AAAAAAAAAAAAAAAAAAAAAH4grI_w4dZncSQwFDBwr23wDIIgvmwJvF_6TtUQOzvZ/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=NWuLQd8KUHLEroz4%2B7m8vXug8Os%3D)폴더 생성



\- C:\apache-tomcat-9.0.52-windows-x64\apache-tomcat-9.0.52\webapps\ROOT\WEB-INF 이동

web.xml 복사 -> C:\SpringProject\WEB-INF 붙여넣기



![img](https://blog.kakaocdn.net/dna/2H01Q/btrlqCyrMjI/AAAAAAAAAAAAAAAAAAAAAH2MhgcFpKlDyq142NvjhX7jHLwBWIRHlsMsL78ycmuO/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=Sq2xqaviWn%2BHcrNq3XDvbJwWIm4%3D)



 



![img](https://blog.kakaocdn.net/dna/3UsGe/btrlw2bZBre/AAAAAAAAAAAAAAAAAAAAAH2N2ddE88cUeQQp7eNV5hirmsGMYTFioVkjJGC0YHfd/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=TILeeyPS5aL5947a8rPUGGroyy0%3D)



  ※ 톰캣 5.0 버전부터는 어플리케이션별로 디렉토리를 할당하는 다계층 구조로

​    구성이 가능하고 WAR로의 배포가 가능하도록 META-INF 구조를 지원

2. 클래스 생성 및 등록

  \* src 폴더에 서블릿 소스를 생성하고 컴파일

  예) javac –d ../classes HelloTest.java –encoding UTF-8



![img](https://blog.kakaocdn.net/dna/tpNi7/btrlpWD9Ef5/AAAAAAAAAAAAAAAAAAAAAK9vIP7VU_rpGoJMoZY_QoCWyxMwh7-rbtsVuDg8dJmx/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=pDJOaPWkpj3g%2BCi8La%2FNig3uVbg%3D)



```
public class Ex01 {
	public static void main(String[] ar) {
		System.out.println("Welcome to JAVA World~!!");
	}
}
```

명령 프롬프트에서 cd C:\SpringProject\WEB-INF\src [작업할 자바 파일 디렉토리 위치]

\* javac HelloTest.java

 



![img](https://blog.kakaocdn.net/dna/davSWJ/btrlwKvVl6j/AAAAAAAAAAAAAAAAAAAAAIT9YweDN2n-pywpy8nxUUAWYkfKwxP1JNEo9ysz88x1/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=Z3uNdF9C%2FxlyoBxGPEeM5MWtBpg%3D)

![img](https://blog.kakaocdn.net/dna/bLFDUm/btrlshA5h7A/AAAAAAAAAAAAAAAAAAAAANnEbA3SHX3vVcPX_FQXUikcijNoD0o-sczbWWcWBY-S/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=bficqPePUQnuXDwlnKRUS9PegWg%3D)



\* java HelloTest

// 결과 나옴 //



![img](https://blog.kakaocdn.net/dna/bLueou/btrlxGsOo5B/AAAAAAAAAAAAAAAAAAAAAMDsuUr0JZQnXBJXrrsicVcrAOGYbLfy1oHetLLrpOGX/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=EntVQ8DHjWQfJ55SSM89vTLFOXo%3D)



  \* 서블릿 클래스 등록

\- web.xml 이용

   WEB-INF 폴더 내 web.xml 파일에 서블릿 클래스 파일 등록 및 URL 매핑

```
  <servlet>
    <servlet-name>hello</servlet-name>
    <sevlet-class>com.test.HelloTest</servlet-class>
  </servlet>
  <servlet-mapping>
    <servlet-name>hello</servlet-name>
    <url-pattern>/hellojava</url-pattern>
  </servlet-mapping>
```

위의 코드 <web-app ... > </web-app> 사이에 입력

HelloTest.java 내용 수정

```
import java.io.IOException;
import java.io.PrintWriter;
import javax.servlet.http.HttpServlet;
import javax.servlet.http.HttpServletRequest;
import javax.servlet.http.HttpServletResponse;

public class HelloTest extends HttpServlet {

    public void doGet(HttpServletRequest req, HttpServletResponse resp)
        throws IOException {
        resp.setContentType("text/html; charset=UTF-8");

        PrintWriter out = resp.getWriter();
        
        out.println("<HTML><HEAD><TITLE>HelloServlet</TITLE></HEAD>");
        out.println("<BODY>");
        out.println("<h>안녕하세요? 서블릿 테스트 예제입니다.</h2>");
        out.println("<H2> Clinet IP: " + req.getRemoteAddr() + "</H2>");
        out.println("<H2> Client Host : " + req.getRemoteHost() + "</H2>");
        out.println("<H2> Request URI : " + req.getRequestURI() + "</H2>");
        out.println("</BODY></HTML>");
    }
}
```

톰캣 설치 디렉토리에서 sevlet-api.jar 라이브러리 복사 

jdk 설치 디렉토리의 jre / lib / ext 폴더에 붙여넣기

C:\apache-tomcat-9.0.52-windows-x64\apache-tomcat-9.0.52\lib

 --> C:\Program Files\Java\jdk1.8.0_144\jre\lib\ext



![img](https://blog.kakaocdn.net/dna/cZif9m/btrlwKv3aCv/AAAAAAAAAAAAAAAAAAAAAC4w-5rOL8I_p4di9C2ZwKPexu2L3MluTJeF68jtPy-G/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=fXziacHaKh6a%2FcM1LdmTrhhm5Ss%3D)

![img](https://blog.kakaocdn.net/dna/m6Qhc/btrlxLns8k4/AAAAAAAAAAAAAAAAAAAAAOZZVginJH_dtYZBUh2iXUEFHEPtdwDmpiIWq1SIh1Ts/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=DpOSrULREXfiXfDSjm35tjfAM%2Fk%3D)



명령 프롬프트에서 

cd [프로젝트 디렉토리]/WEB-INF/src

javac HelloTest.java 

입력해서 컴파일 하기 아무것도 뜨지 않고 넘어가면 컴파일 성공 



![img](https://blog.kakaocdn.net/dna/cvHmNU/btrlpKp6PAG/AAAAAAAAAAAAAAAAAAAAAIirI6axWNJYys3V3cP99xCWUjbJSUJvTCS966oFqc1x/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=CrMlVi30KyOqpS9HKZZUi3xMUTU%3D)



2. 클래스 생성 및 등록(계속)

  \* 서블릿 클래스 등록

  \- Annotation 이용

   WEB-INF 폴더 내 web.xml 파일을 이용해서 서블릿 클래스를 등록하지 않고

   자바 소스에 직접 URI를 기술하는 방식으로 web.xml 파일 내

   web-app 옵션 중 metadata-complete를 반드시 false로 바꿔줘야 함



![img](https://blog.kakaocdn.net/dna/b0bSmX/btrlvB7wWLz/AAAAAAAAAAAAAAAAAAAAAJyyxCfWSTQNEixSlgozSM_TgaD2EhcfoSqml-OetkSz/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=CigUmA8VzVU7yPL8iuNWda2TjYw%3D)



\* HelloTest.java 파일에 어노테이션 추가 

import javax.servlet.annotation.WebServlet;
@WebServlet("/hellojava")



![img](https://blog.kakaocdn.net/dna/EIgwh/btrlwJc9L8p/AAAAAAAAAAAAAAAAAAAAABkvu5tTZyYVgagfWHw1MboUCdtPGMmfDV-e2UzH4cMi/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=BOnrPojehhqov1%2FUmNWWR1Yz1Ps%3D)



\* 다시 명령 프롬프트를 실행해서 [프로젝트 디렉토리]로 이동한 후 컴파일을 실행한다. 

cd [프로젝트 디렉토리]/src

javac HelloTest.java



![img](https://blog.kakaocdn.net/dna/bi8Dl9/btrlpVyV53m/AAAAAAAAAAAAAAAAAAAAALoPn8v4yuCEFGIOlW6vFVKXzC-gHtzA_OWNlNPOCCcm/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=mJaaCRTbpwa7Uzpp0GjlHHgzgAQ%3D)



완료 되면 class 파일이 뜸

src에 생성된 class 파일을 C:\SpringProject\WEB-INF\classes 폴더로 이동시킨다. 



![img](https://blog.kakaocdn.net/dna/k6R04/btrlqLv3kDE/AAAAAAAAAAAAAAAAAAAAADuDolk-VSShWxFarPOtKXlpanxDnjifyJRk5GlWescn/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=OUj8rE6AXiavdJ0w9qFPetIci8A%3D)



\* 해당과정을 실행하는 동안은 tomcat 가동을 꺼놓을것 !! shutdown

\* tomcat 재가동 

cd [톰캣 경로 이동]/bin

startup.bat



![img](https://blog.kakaocdn.net/dna/bRbom3/btrlqNAG0k5/AAAAAAAAAAAAAAAAAAAAAFBxaC1-TAtPahc9uAKZ9StKRsuLcbWSR7hM812JTld8/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=M4Nd4fzcTyQGZxCHWa%2F2dA0D40s%3D)



http://127.0.0.1:8080/hellojava 

로 웹브라우저 입력하여 구동확인 



![img](https://blog.kakaocdn.net/dna/btWk1W/btrlyj5Dl96/AAAAAAAAAAAAAAAAAAAAAJOH_TC0fXf2GKCOkZDVHFi1Z9TNES4tg1J1alK9oyIn/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=%2FX%2BDmUTOuB8E6yrHFQkWdEbqxkI%3D) 화면



 

3. 서블릿 환경 구성 시 주의 사항

 \* 톰캣 버전 10부터는 Java EE 플랫폼을 이용하지 않고 톰캣 자체의

   Jakarta EE 9 플랫폼을 사용하는 관계로 과거 톰캣 버전에서 구동했던

   어플리케이션을 톰캣 10 환경하에서 사용하기 위해서는 별도의 변경 작업이 필요

 \* 자바, 톰캣 버전 간 호환 여부를 사전에 반드시 확인해야 하며,
   JDK와 JRE도 동일 버전을 사용해야 함



![img](https://blog.kakaocdn.net/dna/bwpSlQ/btrln9qDmds/AAAAAAAAAAAAAAAAAAAAAHZ8-IoK2trErzv5YQyywEiryzJeVXTomyawEa8S0acX/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1753973999&allow_ip=&allow_referer=&signature=yIRkePC2G2uU6seU0TaVHAb9hNw%3D) 예제 ) 톰캣 서버 , 서블릿 , JSP 버전을 확인하는 JSP 소스



 