
��Ʊ�г������ı�����ϵͳ 
===

### China Stock Market Text Sentiment Anlysis

���Ʊ�ҵ��ƴ浵��������������Ӷ����Ƹ��ɰ��Զ���ȡ�ı����ݣ�ʹ��jieba�ִʡ���Ҷ˹�㷨������з����������г������ɵ���������������ʹ��MySQL�洢���ݣ�ʹ��Django��ECharts���п��ӻ�չʾ��

## ����
> Python>=3.6.0  
> Django>=2.1.0  
> requests>=2.19.0  
> scikit-learn>=0.19  
> tushare  
> jieba  
> mysqlclient  


## �ļ�Ŀ¼
```
������ data  
��   ������ clf                  #��Ҷ˹ģ��  
��   ������ tfidf                #TF-IDFģ��  
��   ������ vect                 #��Ƶģ��  
��   ������ worddict             #�û��ʵ�  
��   ������ stop_words.txt       #ͣ�ôʴʵ�   
������ InvisibleHand  
��   ������ settings.py          #��Ŀ����  
��   ������ urls.py              #��Ŀ·�ɶ���  
��   ������ wsgi.py              #HTTP�������Ľӿ�  
������ Sentiment  
    ������ templates            #��ҳ��̬�ļ�Ŀ¼
        ������ Sentiment  
            ������ home.js      #��ҳ�ű�  
            ������ 404.js       #δ�ҵ�ҳ��ű�  
            ������ search.js    #����ҳ�ű�  
            ������ hot.js       #�����ȵ�ҳ��ű�  
            ������ text.js      #�ı�����ҳ��ű�   
            ������ detial.js    #��������ҳ��ű�  
            ������ global.js    #��վȫ�ֽű�  
            ������ global.css   #��վȫ����ʽ  
    ������ static               #��ҳ��̬�ļ�Ŀ¼  
        ������ Sentiment   
            ������ home.html    #��ҳģ��  
            ������ 404.html     #δ�ҵ�ҳ��ģ��  
            ������ search.html  #����ҳģ��  
            ������ hot.html     #�����ȵ�ҳ��ģ��  
            ������ text.html    #�ı�����ҳ��ģ��   
            ������ detail.html  #��������ҳ��ģ��  
    ������ admin.py             #Django��̨�Ĺ���ҳ��  
    ������ apps.py              #Ӧ������  
    ������ models.py            #����ģ�Ͷ���  
    ������ urls.py              #·������  
    ������ views.py             #Django��ͼ  
    ������ tests.py             #��Ԫ����  
    ������ front_utils.py       #���ݷ���ģ�顢�����ı��㷨  
```