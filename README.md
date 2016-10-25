閱讀 @fulkuball 文章 [如何使用 JIEBA 結巴中文分詞程式](http://blog.fukuball.com/ru-he-shi-yong-jieba-jie-ba-zhong-wen-fen-ci-cheng-shi/) 時練習用的 docker 環境，裡面包含結巴套件以及文章內的 demo code。

## Usage

Build image

```sh
docker build --force-rm  -t fukuball-jieba-demo .
```

Run container

```sh
docker run -it --name fukuball-jieba-demo fukuball-jieba-demo
```

Run demo code

```python
python jieba_cut_lyric_zh_tw_custom.py
```

demo code list
* jieba-default-mode.py
* jieba_cut_lyric.py
* jieba_cut_lyric_zh.py
* jieba_cut_lyric_zh_flag.py
* jieba_cut_lyric_zh_keyword.py
* jieba_cut_lyric_zh_tokenize.py
* jieba_cut_lyric_zh_tw.py
* jieba_cut_lyric_zh_tw_custom.py
