# korean SmileStyle Dataset
![logo](https://github.com/smilegate-ai/korean_smile_style_dataset/blob/main/smilestyle.png)
    
Smilegate AI에서 공개하는 한국어 문체 스타일 변환 "SmileStyle" 데이터셋입니다.  

## 주의
본 데이터셋은 Smilegate AI에서 구축한 **토이 데이터셋**으로, **오탈자**와 **스타일 변환 오류**를 내포하고 있습니다.   
데이터 이상을 발견하셨다면, issue로 알려주세요!   
     
## 1. 데이터셋 overview   
본 데이터셋은 동일한 멀티턴 대화 데이터에 대해 17개의 서로 다른 스타일로 문체를 변환시킨 데이터입니다.
각 스타일에 대한 설명은 아래와 같습니다.

- [formal]    
존댓말 스타일입니다. (e.g. 나이가 어떻게 되시는데요?)    
- [informal]    
반말 스타일입니다. (e.g. 몇 살이야?)    
- [android]    
로봇의 답변 스타일입니다. (e.g. 휴먼. 나이. 무엇.)    
- [azae]    
연장자 스타일입니다. (e.g. 거 나이가 어떻게 되나?)    
- [chat]    
챗봇의 채팅 스타일입니다. (e.g. 몇 살임?)    
- [choding]    
어린아이 말투 스타일입니다. (e.g. 몇 살임?)    
- [emoticon]    
반말 스타일에 이모티콘을 부착하였습니다. (e.g. 몇 살이야???? (´･ω･`)?)    
- [enfp]    
외향적인 스타일입니다. (e.g. 올해 몇살이양~?!?)    
- [gentle]    
극존칭의 예의 바른 스타일입니다. (e.g. 실례가 안된다면,, 나이가 어떻게 되시나요?)    
- [halbae]    
할아버지 스타일입니다. (e.g. 몇 살이신가?....)    
- [halmae]    
욕쟁이 할머니 스타일입니다. (e.g. 이 새끼 이거 몇살이여?)    
- [joongding]    
중2병 스타일입니다. (e.g. 나이몇개?)    
- [king]    
사극체 스타일입니다. 자신을 왕으로 지칭합니다. (e.g. 춘추가 어떻게 되는가?)    
- [naruto]    
특정 어미를 부착한 스타일입니다. (e.g. 몇 살이냐니깐!)    
- [seonbi]    
사극체 스타일입니다. (e.g. 몇 살인 것이오?)    
- [sosim]    
소심한 스타일입니다. (e.g. 혹시.. 몇살이야..?ㅠ)    
- [translator]    
번역기 스타일입니다. (e.g. 당신은 몇 년?)      
     
     
항목 | formal | informal | android | azae | chat | choding | emoticon | enfp | gentle | halbae | halmae | joongding | king | naruto | seonbi | sosim | translator
--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
대화 개수 | 235 | 235 | 123 | 74 | 235 | 235 | 125 | 117 | 118 | 125 | 70 | 235 | 123 | 125 | 125 | 123 | 104 |
문장 개수 | 3,470 | 3,470 | 1,775 | 1,025 | 3,470 | 3,470 | 1,797 | 1,689 | 1,703 | 1,794 | 1,013 | 3,470 | 1,775 | 1,797 | 1,797 | 1,775 | 1,504 |
    
    
## 2. 데이터셋 예제   
![example](https://github.com/smilegate-ai/korean_smile_style_dataset/blob/main/example.png)

    
## 3. Citation
```
@misc{SmilegateAI2022KoreanSmileStyleDataset,
  title         = {SmileStyle: Parallel Style-variant Corpus for Korean Multi-turn Chat Text Dataset},
  author        = {Seonghyun Kim},
  year          = {2022},
  howpublished  = {\url{https://github.com/smilegate-ai/korean_smile_style_dataset}},
}
```
    
## 4. License
Smilegate AI `SmileStyle`의 `데이터셋`은 [CC-BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) 라이선스 하에 공개되어 있습니다.   
데이터셋을 사용할 경우 라이선스 내용을 준수해 주십시오.    
데이터셋의 상업적 사용의 경우, `smilegate_ai@smilegate.com` 으로 문의 부탁드립니다.    
본 데이터셋의 내용은 Smilegate AI의 의견과 무관합니다. 
