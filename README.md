# papagotrans
## 설치 방법
```sh
pip install papagotrans
```
## 사용법
```py
import papagotrans

result = papagotrans.translate(text = '안녕하세요', source = 'ko', target  = 'en')

text = result['translatedText']
src = result['srcLangType']
tar = result['tarLangType']
print(f'{text} | {src} 언어에서 {tar} 언어로 번역됨') # Hello | ko 언어에서 en 언어로 번역됨
```
