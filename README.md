# py-papago
## 설치 방법
```sh
pip install papagotrans
```
## 사용법
```py
import papagotrans

result = papagotrans.translate(text = '안녕하세요', source = 'ko', target  = 'en')

print(f'{result['translatedText']} | {result['srcLangType']} 언어에서 {result['tarLangType']} 언어로 번역됨') # Hello | ko 언어에서 en 언어로 번역됨
```