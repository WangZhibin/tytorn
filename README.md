## Tytorn - A simple MVC framework based on tornado
һ������tornado�ļ�MVC���


### ����ص�
- �㹻�������߶ȿɶ��ƣ�û���κε�������������ֻҪ��װ��tornado����˳������
- ʵ����������������
- ����...

### ������
����ѧϰtornado����������tornado���Ŀ��python�����ߣ���Ȼ�ٷ��ṩ�ܶ�demo��������Щdemo��ֻ����Ϊ�ο�������Ӧ��ʵ�ʿ�����Ҫ������Ŀ����ֱ�Ӳ�����Ϊ�����Ļ�����ܡ�

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

##### 3.������Ŀ
���������½��뱾��Ŀ��ִ�����������
```
python server.py
```

It is ok, so easy!

###Ŀ¼�ṹ

������ README.md
������ handlers           //������վ�����handlerģ��
��   ������ main.py          //�������µ�handlers
��   ������ admin.py         //��̨ģ��
��   ������ ...
������ models         // ģ��
������ libs            //���ÿ�
������ static          //��̬��Դ
������ server.py       //����ļ�
������ urls.py         //·�������ļ�
������ application.py