#### ���̽�__init.py__ ####
package �ʱ�ȭ ������ �ϴ� ����, package���� __init.py__�� �־���Ѵ�.

package ?  
- ����� ����  

package�̸��� �ǹ̴�?  
- ����� ��Ƶ� ���丮�� �̸� 

init.py ?
- __all__ : import *�� ���� ��, ���Ե� ������ �̸�  
- __version__ : package�� ����


Ȱ�� �ϴ� ����� ?
1. �׷��ٸ� ������ ���� ���� ������ �Ǿ��ְ�,  
```
myItems - __init.py__  
        - phone.py  
        - mic.py
```


2. home>__init.py�� ������ ���� ���ԵǾ��ִٸ�,  
```
__all__=["phone", "mic"]
```

3. from home import *�� ������ __all__�� ���ǵ� phone.py�� mic.py�� ����Ʈ �ȴ�.
