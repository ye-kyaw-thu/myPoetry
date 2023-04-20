# myPoetry
myPoetry corpus is especially suited to applications in creative computational Burmese poetic text generation.

PLEASE WAIT ... 

Latest Version: [Version 1.0](https://github.com/ye-kyaw-thu/myPoetry/tree/main/corpus/version1.0)  

## Corpus Information
### Version 1.0  

- Number of poets: 398  
- Number of unique poems: 1,943  
- Number of sentences: 46,933  

### Corpus Files

- [mypoetry-corpus-ver1.0.txt](https://github.com/ye-kyaw-thu/myPoetry/blob/main/corpus/version1.0/mypoetry-corpus-ver1.0.txt)  
- [mypoetry-corpus-notitle-ver1.0.txt](https://github.com/ye-kyaw-thu/myPoetry/blob/main/corpus/version1.0/mypoetry-corpus-notitle-ver1.0.txt)  

### Format

```
$ head -n 40 ./kabyar-corpus-ver1.0.txt 
Title: တက်လူ့တေးသံ
By: ဇော်ဂျီ
ကြက်ဖ သာလျှင်
အာရုဏ်ရောင်လှ ၊ ဝင်းဝါကြ၏ ။
ဥဩ သာလျှင်
ရာသီနွေလ ၊ ဖူးပွင့်ကြ၏ ။
ဖားငယ် သာလျှင်
အာကာမိုးက ၊ မိုးရွာကြ၏ ။
တက်လူ သာလျှင်
မြန်မာပြည်လှ ၊ အားသစ်ရ၍
ဇေယျအောင်လံ ထူမည်တည်း ။

Title: ဤနေရာ
By: ဇော်ဂျီ
ဤနေရာတွင်
ညောင်ညိုပင်၏ ၊ မြေပြင်ခြေရင်း
မြစ်ပါးပျဉ်းသည် ၊ သက်ဆင်းလူးလွန့်
မြွေသို့တွန့်၏ ။
ဤနေရာတွင်
ပိန္နဲ့ပင်ဝယ် ၊ ရှဉ့်ရင်ပေါ့ပါး
မြီးဖားဖားသည် ၊ ရွက်ကြားခက်လက်
လျှပ်သို့လက်၏ ။
ဤနေရာတွင်
ထန်းနှစ်ပင်သည် ၊ တူယှဉ်ပြိုင်မြင့်
ရွက်ဝန်းဖွင့်၍ ၊ အကျင့်သိက္ခာ
ရှင်သို့သာတည့် ။
ဤနေရာတွင်
စေတီရှင်သည် ၊ ဖြူစင်မောက်မို့
ကြားဖူးသို့တည့် ။
ဤနေရာတွင်
ထက်ကောင်းကင်ဝယ် ၊ လေညင်ခတ်တီး
စေတီထီးမှ ၊ ဆည်းလည်းသံရွှင်
မိုးကျသွင်တည့် ။
ဤသို့သံသာ ၊ ဤရုပ်ဝါသည်
ငါ့မှာသတိ မြဲခဲ့၏ ။
```

### Format Without Title and Poet's Name

```
$ head -n 40 ./kabyar-corpus-notitle-ver1.0.txt 
ကြက်ဖ သာလျှင်
အာရုဏ်ရောင်လှ ၊ ဝင်းဝါကြ၏ ။
ဥဩ သာလျှင်
ရာသီနွေလ ၊ ဖူးပွင့်ကြ၏ ။
ဖားငယ် သာလျှင်
အာကာမိုးက ၊ မိုးရွာကြ၏ ။
တက်လူ သာလျှင်
မြန်မာပြည်လှ ၊ အားသစ်ရ၍
ဇေယျအောင်လံ ထူမည်တည်း ။

ဤနေရာတွင်
ညောင်ညိုပင်၏ ၊ မြေပြင်ခြေရင်း
မြစ်ပါးပျဉ်းသည် ၊ သက်ဆင်းလူးလွန့်
မြွေသို့တွန့်၏ ။
ဤနေရာတွင်
ပိန္နဲ့ပင်ဝယ် ၊ ရှဉ့်ရင်ပေါ့ပါး
မြီးဖားဖားသည် ၊ ရွက်ကြားခက်လက်
လျှပ်သို့လက်၏ ။
ဤနေရာတွင်
ထန်းနှစ်ပင်သည် ၊ တူယှဉ်ပြိုင်မြင့်
ရွက်ဝန်းဖွင့်၍ ၊ အကျင့်သိက္ခာ
ရှင်သို့သာတည့် ။
ဤနေရာတွင်
စေတီရှင်သည် ၊ ဖြူစင်မောက်မို့
ကြားဖူးသို့တည့် ။
ဤနေရာတွင်
ထက်ကောင်းကင်ဝယ် ၊ လေညင်ခတ်တီး
စေတီထီးမှ ၊ ဆည်းလည်းသံရွှင်
မိုးကျသွင်တည့် ။
ဤသို့သံသာ ၊ ဤရုပ်ဝါသည်
ငါ့မှာသတိ မြဲခဲ့၏ ။
```

## How myPoetry Corpus Was Made

The corpus contains only "title," "poet's name," and "lines of poetry," mainly from publicly available Burmese poetry scanned-PDF books, and a few sentences are from online resources such as Facebook. Therefore, we manually typed and checked almost all lines of the corpus.  

## Contributors

[Ye Kyaw Thu](https://sites.google.com/site/yekyawthunlp/) (Design, Data checking, Modeling)   
Khaing Hsu Wai (Design, Data preparation)  
Thazin Myint Oo (Data preparation)  
Myint Myint Htay (Data preparation)   
Naing Linn Phyo (Data preparation)  

## License

Creative Commons Attribution-NonCommercial-Share Alike 4.0 International (CC BY-NC-SA 4.0) License.  
[Details Info of License](https://creativecommons.org/licenses/by-nc-sa/4.0/)

## Questions, comments and suggestions?

Please email: yktnlp@gmail.com  

## Citation

If you use any of the resources listed here, please cite:  

