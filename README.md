# POI Review Corpus for Sentiment Analysis v1.0

This is a POI review corpus dataset in the Korean language. Reviews were scraped from [Kakao Map](https://map.kakao.com). Each review is labeled with polarity - negative or positive.

## Data description

- Language: Korean
- Source: Kakao Map
- Columns: `id`, `content`, `label`
  - `id`: The review id
  - `content`: The actual review
  - `label`: The polarity of the review (0: negative, 1: positive)
  - Columns are delimited with tabs.

## Data distribution

- 100K reviews in total
  - 50K negative reviews (originally reviews of ratings 1~2)
  - 50K positive reviews (originally reviews of ratings 4~5)
  - Neutral reviews (originally reviews of ratings 3) are excluded.

## Quick peek

```
id      content label
139363  한번 가 봤는데 떡 식감이 너무 안좋았음. 떡볶이 쏘스도 별로였음. 단 참치 주먹밥은 먹을만 했음. 그 외에는 그냥 그냥 함   0
155416  싸고 맛있고 최고 분짜도 갠춘 다만 팟타이는 별로 1
148176  가격 감안해도 참 맛없음 0
143040  직원들 불친절함 바쁜건가?       0
71857   9/4 밤에 알바하시는 남자 알바분 엄청 불친절하고 손님이 와도 나와보지도 않아요&hellip; 게다가 다음 재료 뭐 넣을지 물어보지도 않고 말 안 하냐는 듯이 쳐다보기만 해서 무서웠어요   0
106816  다 정성이 들어간 느낌 ! 메뉴 모두 성공이에요    1
44078   미니리와 삼겹살 조합도 좋았고 반찬도 정갈하고 껍데기 서비스에 도시락도 좋았구요. 토욜 오후에 갔는데 무엇보다 직 원분 일하는 모습에 감동 제가 어디 사장이면 스카웃 하고 싶다는 ㅎㅎ      1
123452  깔끔하니 맛있는 순대국밥! 반찬도 맛있어요!      1
53617   분위기 좋고, 음식맛 최고였습니다. 직원분들 모두 친절하시고 좋았어요.    1
```

## License

<p xmlns:dct="http://purl.org/dc/terms/">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
</p>
