# Image2Text

이미지의 텍스트를 쉽게 한국어, 영어, 일본어로 바꾸어주는 모듈
https://pypi.org/project/image2text/

### 설치법 How to install

> pip install image2text

### 사용법 How to use


> from image2text.statement import *

1. image file path -> text

> path_to_full_text(image_path, lang)

image_path : local file path
lang : 'ko', 'en', 'jp'(maybe test...)

2. image url -> text

> url_to_full_text(url, lang)

url : image url
lang : 'ko', 'en', 'jp'(maybe test...)