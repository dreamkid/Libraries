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
    new ShareAction(activity)
                    .setDisplayList(SHARE_MEDIA.QQ, SHARE_MEDIA.QZONE, SHARE_MEDIA.WEIXIN, SHARE_MEDIA.WEIXIN_CIRCLE, SHARE_MEDIA.SINA)
                    .withTitle(")
                    .withText("")
                    .withMedia("http://ooxx.img")
                    .withTargetUrl("http://ooxx.html").setCallback(umShareListener).open();

4.�������������ɣ�
