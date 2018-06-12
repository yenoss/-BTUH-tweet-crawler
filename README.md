# BTUH-tweet-crawler

## Introduction

* BTUH(BetterThanYourHands)-tweet-crawler 
* 트위터 api는 비싸고!
* Http 따보려니 암호화 되있고!
* 직접 손으로 긁는게 나을 것 같아 만들었습니다.



>  손으로 긁는 것 보단 낫습니다..



## Installation

- [Chrome Web Driver](http://chromedriver.chromium.org/downloads)



##  Run

- 현재 날자 ~ {%Y-%m-%d-%H:%M:%S}  까지 데이터를 크롤링합니다.

```
python3 tweetCrawler.py {keyword} {%Y-%m-%d-%H:%M:%S}
```

* data는 json형태로 out폴더 내부에 저장됩니다.



## Default json Set

* 기본 저장 셋은 다음과 같습니다.

~~~
{
    "data": [
        {
            "comment_cnt": 0,
            "data_id": "1006403615009878016",
            "like_cnt": "59",
            "published_date": "2018-06-12 07:11:34",
            "retweet_cnt": "69",
            "text": "바코드 통일 예스 !\n포스터 지관통 예스 !\n발매일 180626",
            "time": 1528755094.0,
            "user_id": "@artist_nuest",
            "user_nick": "뉴티스트"
        }
    ],
    "data_length": 1,
    "end_time": "2018-06-12 15:51:58",
    "search_word": "통일",
    "start_time": "2018-06-12 15:51:52"
}
~~~

