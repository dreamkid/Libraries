�ɸ߶�ui���Ʋ�����<br>
ʹ�÷���
1.�ڲ���������
    <com.android.tedcoder.wkvideoplayer.view.SuperVideoPlayer
                    android:id="@+id/video_player_item"
                    android:layout_width="match_parent"
                    android:layout_height="200dp"
                    />
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