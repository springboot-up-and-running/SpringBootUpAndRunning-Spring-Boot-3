# SpringBootUpAndRunning: Spring-Boot Version 3

# 2024.1.28 Update
롬복 디펜던시에 업데이트가 필요해서 스프링 애플리케이션 구동이 안 되는 것을 확인했습니다. 4, 6, 8 브랜치에 업데이트를 했지만, 혹시 다른 브랜치에서 스프랭 앱 구동이 안되면, 롬복 최신 버전을 설치해주세요. 
그리고 맥북 M 시리즈 쓰시는 분 중에 아래 관련 오류가 발생하면, 다음 디펜던시를 추가해주세요.

'Unable to load io.netty.resolver.dns.macos.MacOSDnsServerAddressStreamProvider, fallback to system defaults. This may result in incorrect DNS resolutions on MacOS. Check whether you have a dependency on 'io.netty:netty-resolver-dns-native-macos'. Use DEBUG level to see the full stack: java.lang.UnsatisfiedLinkError: failed to load the required native library'

<dependency>
			<groupId>io.netty</groupId>
			<artifactId>netty-all</artifactId>
</dependency>

--------------------------

SpringBootUpAndRunning
SpringBootUpAndRunning 한글번역책 실습코드

원본 실습코드 https://github.com/mkheck/SpringBootUpAndRunning (SpringBoot 2.4, Java 11)

번역판 실습코드는 SpringBoot 3.0.2와 Java 17 로 구성되어있습니다.

실습 중 질문이 있으면 dev[at]syoh.net 혹은 jungdaesuh1221[at]gmail.com 이메일 주시면 감사하겠습니다. 
