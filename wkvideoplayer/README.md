�ɸ߶�ui���Ʋ�����
ʹ�÷���
1.�ڲ���������
    <com.android.tedcoder.wkvideoplayer.view.SuperVideoPlayer
                    android:id="@+id/video_player_item"
                    android:layout_width="match_parent"
                    android:layout_height="200dp"
                    >
2.��ʼ��������������Ƶ
    video = new Video();
    video.setVideoName(mTopicItem.getTitle());
    VideoUrl videoUrl = new VideoUrl();
    videoUrl.setFormatUrl(videoURL + ".f30.mp4");

    ArrayList<VideoUrl> list = new ArrayList<>();
    list.add(videoUrl);

    video.setVideoUrl(list);

    mSuperVideoPlayer.loadMultipleVideo(video);

 3.ui�ɽ��и߶ȶ��ƣ��۳Ұɣ�