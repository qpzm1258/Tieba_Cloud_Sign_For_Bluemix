#�ٶ�������ǩ��
Դ���ַ��https://git.oschina.net/kenvix/Tieba-Cloud-Sign.git
�ڷ����������úþ���������κβ��������ʵ�����ɵ�ȫ�Զ�ǩ����     
��ϲ��ʹ�û���ʵ���ƹ�ˮ�����ޡ������ɾ�������ȹ��ܡ�     
��ȡ������̳̣���չ�����ϵ���ǰ��Wiki [Git@OSC](https://git.oschina.net/kenvix/Tieba-Cloud-Sign/wikis/home) [GitHub](https://github.com/MoeNetwork/Tieba-Cloud-Sign/wiki)              
##������
������ǩ����һ�����ŵĿ�Դ��Ŀ���κ��˾��ɲ��뿪����Pull Request�����ύ���޸ĵĴ���     
Pull Request��Issue���ύ�� Git@OSC ����⣬������������ύ���ܲ��ᱻ����     
������뿪��������ϵ @Kenvix 
###�������б�
####��Ҫ
@Kenvix [kenvix@qq.com]     
####Э��
@mokeyjay [i@mokeyjay.com]     
@fyy99 [fyod@qq.com]
####���Ĺ�����
���¼�λ����/����˳���Ĳ���֮�����ش˸�л     
@Ver4 [i@v4.hk]     
@kirainmoe [kotori@wo.cn]     
@VFleaKing [liuhaotian0520@163.com]     
@superxzr [a457418121@gmail.com]         
û����ҵ�棡û����ҵ�棡û����ҵ�棡  

##��������������
�������󲿷��˰�װ�����һ��Ӧ���ǣ�û����������ˣ�һ���ǳ�����ˡ�
#####1.��ΰ�װ����
�ϴ��˳���������վ��Ȼ�����������վ
#####2.��ο��� MySQL ���ӷ�ʽǿ�ƹ���
������ݿ�������ȷ�����������ݿ�ʧ�ܣ�������� 20XX������ʹ�ô˷���     
��   mysql_autoload.php     
�ҵ�   define('SQLMODE', 'mysqli');     
�滻Ϊ define('SQLMODE', 'mysql');
#####3.��ο������ݿⳤ����
��   mysql_autoload.php     
�ҵ�   define('LONGSQL', false);     
�滻Ϊ define('LONGSQL', true); 
#####4.����ֶ��޸����ݿ�����
�� config.php �����������ע���޸�     
����ʹ�ü��±��༭��������򽫲��ܹ���
#####5.����ֶ��������ݿ�
�� /setup/install.template.sql �����������ע���޸�
#####6.��ΰ�װ�°汾
��1���Զ����£�ǰ�� ������ ���³��򼴿�     
��2���ֶ����£�ֱ������ Zip��ɾ��ѹ�����ڵ� config.php ��Ȼ���ϴ���������վ����     
���⣬ÿһ����汾������һ�������ű���������������     
���ļ���һ��Ϊ update�ɰ汾to�°汾.php ������ update1.0to2.0.php��

##Bluemix�������ø�ע
###[bluemix php��������](https://www.ibm.com/developerworks/cn/cloud/library/cl-bluemix-fundamentals-create-and-deploy-a-php-app-to-the-cloud/index.html)

###composer.json
��������php�����Լ�extensionģ��
```
    {
        "require": {
            "ģ������": "�汾�ţ�*Ϊ��ָ���汾��"
        }
    }
```
�ο�[composer�����ĵ�](https://getcomposer.org/doc/04-schema.md)
###.env.example
�����������л�����[�ο��ĵ�](https://console.ng.bluemix.net/docs/manageapps/depapps.html#app_env)
###manifest.yml
App�����ļ�,[�ο��ĵ�](https://console.ng.bluemix.net/docs/manageapps/depapps.html#appmanifest)