<<<<<<< HEAD
���˵�һ����������<br>
���ټ��ɷ��������<br>

ʹ�÷���<br>
1.���嵥�ļ�Menifest������UMENG_CHANNEL��UMENG_MESSAGE_SECRET<br>
2.��Application��oncrete����������Ҫ����ĸ�ƽ̨��key��screte key�Լ��ض���url������<br>
    PlatformConfig.setWeixin("", "");<br>
    PlatformConfig.setQQZone("", "");<br>
    PlatformConfig.setSinaWeibo("", "");<br>
    Config.REDIRECT_URL = "http://sns.ooxx.com/sina2/callback";<br>
3.����<br>
    ���ñ��⡢�����⡢��ʾͼƬ���򿪺��h5����<br>
=======
友盟的一个分享工具类
快速集成分享的利器

使用方法
1.在清单文件Menifest中配置UMENG_CHANNEL和UMENG_MESSAGE_SECRET
2.在Application的oncrete方法中配置要分享的各平台的key和screte key以及重定向url，例如
    PlatformConfig.setWeixin("", "");
    PlatformConfig.setQQZone("", "");
    PlatformConfig.setSinaWeibo("", "");
    Config.REDIRECT_URL = "http://sns.ooxx.com/sina2/callback";
3.分享
    设置标题、副标题、显示图片、打开后的h5连接
>>>>>>> b53cbf01d63f20fdd69df36d8817d86dc7a10001
    new ShareAction(activity)
                    .setDisplayList(SHARE_MEDIA.QQ, SHARE_MEDIA.QZONE, SHARE_MEDIA.WEIXIN, SHARE_MEDIA.WEIXIN_CIRCLE, SHARE_MEDIA.SINA)
                    .withTitle(")
                    .withText("")
                    .withMedia("http://ooxx.img")
                    .withTargetUrl("http://ooxx.html").setCallback(umShareListener).open();
<<<<<<< HEAD
                    <br>
4.�������������ɣ�
=======
4.结束，尽情分享吧！
>>>>>>> b53cbf01d63f20fdd69df36d8817d86dc7a10001
