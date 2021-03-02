# SwiftCrawlingRnD

## firstKorea 프로젝트 RnD


유튜브 구독자수 , 순위 크롤링 

[참고사이트](https://kr.noxinfluencer.com/youtube-channel-rank/top-100-kr-all-youtuber-sorted-by-subs-weekly)

------

### 1.
우선 크롤링 할 수 있는 사이트 인지 URL에 robots.txt를 쳐본 후 가능한지 확인한다.
크롤링이 가능하면 Swift 내에 있는 크롤링을 써주는데, pod를 추가 후

    
 ``` java
   pod 'Kanna','~>5.0.0'
```
이렇게 kanna를 설치 해준다.

------

### 2.

import kanna를 해준뒤 사이트를 가서 개발자도구로 크롤링할곳을 copy to Xpath를 해주고 
소스에 옮겨와 정리를 해준다.

----

### 3. 

tableView에 연동 시켜준다. 
