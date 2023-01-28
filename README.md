
# Proje Başlığı

Bu proje, Natural Language Toolkit (nltk) ve pickle kullanarak bir film öneri sistemini eğitmek için TMDB-5000 film veri kümesini kullanır. Veri kümesi, önce nltk kullanılarak ön işleme tabi tutulan ve daha sonra modeli eğitmek için kullanılan bir CSV dosyası biçimindedir. Eğitilen model daha sonra pickle kullanılarak daha sonra kullanılmak üzere kaydedilir. Son olarak, model Python'daki streamlit kitaplığı kullanılarak gösterilmiştir.


# Gereksinimler

-pandas

-numpy

-nltk

-sklearn

-streamlit

-ast

-pickle


# Kullanım


1- tmdb_5000_credits.csv ve tmdb_5000_movies.csv dosyalarını önceden işlemek ve modeli eğitmek için bu dosyaları train.py ile aynı dizine getirdikten sonra scripti run edin. Bu, proje dizininde similarity.pkl dosyası yaratacaktır.

2-Bir film başlığı girmenize ve benzer filmler için önerileri görmenize izin verecek olan akıcı uygulamayı başlatmak için app.py'yi çalıştırın.


