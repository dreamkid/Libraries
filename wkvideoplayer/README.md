�ɸ߶�ui���Ʋ�����<br>
ʹ�÷���<br>
1.�ڲ���������
<br>
    <com.android.tedcoder.wkvideoplayer.view.SuperVideoPlayer
                    android:id="@+id/video_player_item"<br>
                    android:layout_width="match_parent"<br>
                    android:layout_height="200dp"<br>
                    /><br>
2.��ʼ��������������Ƶ<br>
    video = new Video();<br>
    video.setVideoName(mTopicItem.getTitle());<br>
    VideoUrl videoUrl = new VideoUrl();<br>
    videoUrl.setFormatUrl(videoURL + ".f30.mp4");<br>

    ArrayList<VideoUrl> list = new ArrayList<>();<br>
    list.add(videoUrl);<br>

    video.setVideoUrl(list);<br>

    mSuperVideoPlayer.loadMultipleVideo(video);<br>

 3.ui�ɽ��и߶ȶ��ƣ��۳Ұɣ�