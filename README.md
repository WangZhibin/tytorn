## Tytorn - A simple MVC framework based on tornado
һ������tornado�ļ�MVC���


### ����ص�
- �Ѻõ�����ע��
- �㹻�������߶ȿɶ���
- ʵ����������������
- ��װ����־��¼��postgresql��session��web�����������ܣ�������רעҵ���߼�
- ������restful api �ӿ�
- ʵ����postgre sql���첽���ݿ����
- ����...

### ������
����ѧϰtornado����������tornado���Ŀ��python�����ߣ���Ȼ�ٷ��ṩ�ܶ�demo��������Щdemo��ֻ����Ϊ�ο�������Ӧ��ʵ�ʿ�����Ҫ��
����Ŀ����ֱ�Ӳ�����Ϊ�����Ļ�����ܡ�

###��������

##### 1.��װtornado

[�˽�tornado](https://github.com/tornadoweb/tornado "�˽�tornado")

```shell
pip install tornado
```

##### 2.��¡����Ŀ
������Ѿ���װ��git��Ϊ��İ汾����ϵͳ,����ִ�����������
```
git clone https://github.com/tornadoweb/tornado
```
���û�а�װgit,�������ر���Ŀ��ѹ����

####  3.��װ��Ŀ������
```
pip install -r requirements.txt
```

####   4.�������ݿ�����
�޸�config.pyĿ¼��Ķ�Ӧ��
```
DB_HOST = '127.0.0.1'
DB_PORT = 5432
DB_DATABASE = 'your database'
DB_USER = 'tytorn'
DB_PASSWORD = '123456'
DB_ASYNC_MAXCONN = 33  # ����첽������
DB_SYNC_MAXCONN = 10  # ���ͬ��������
```
#####  5.������Ŀ
���������½��뱾��Ŀ��ִ�����������
```
python server.py
```

It is ok, so easy!

###Ŀ¼�ṹ
```
������ README.md
������ requirements.txt   //������
������ handlers           //������վ�����handlerģ��
��   ������ api              //rest api ģ��
��   ������ main.py          //�������µ�handlers
��   ������ admin.py         //��̨ģ��
��   ������ ...
������ models         // ģ��
������ libs            //���õ�������
������ static          //��̬��Դ
������ utils           //��Ŀ�ײ��
��   ������ log.py           //��־������
��   ������ postgredb        //���ݿ������
��   ������ session.py       //session������
��   ������ tools.py         //���߿�
��   ������ httpresponse.py  //rest api��Ӧ���ݹ淶
������ server.py       //����ļ�
������ urls.py         //·�������ļ�
������ config.py         //��Ŀ�����ļ�
������ app.py          //applicationʵ��
```
###Credit
��Ŀ�ۺ���guthub����ͬ�ʵ�һЩ����Ȼ����ԸĽ���ɵģ��ڴ���л
����sessionģ���ǲ��õ�[REDIS -TORNADO -SESSION](https://github.com/zs1621/tornado-redis-session)
restful�����ǲ��õ�[tornado-rest](https://github.com/rancavil/tornado-rest)