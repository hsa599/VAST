# VAST Sample Video Ads
Simple VAST Video AdSystem

```xml
<VAST version="3.0">
	<Ad id="1">
		<InLine>
			<AdSystem>Vast Name</AdSystem>
			<AdTitle>Vast Title</AdTitle>
			<Description>Vast Desc</Description>
			<Creatives>
				<Creative sequence="1" id="1">
					<Linear skipoffset="00:00:05">
						<Duration>00:00:13</Duration>
						<TrackingEvents>
							<Tracking event="start">
								<![CDATA[https://tavoos.net/services/vast/v8hQilXv-e1KH-aDrJ-3BWV-LKnnTx5wvisf/382/campaigns/1598/contents/2390/61c2293534f3e/05OcBOhIWv/event/start]]>
							</Tracking>
							<Tracking event="progress" offset="00:00:05.000">
								<![CDATA[https://tavoos.net/services/vast/v8hQilXv-e1KH-aDrJ-3BWV-LKnnTx5wvisf/382/campaigns/1598/contents/2390/61c2293534f3e/05OcBOhIWv/time/midpoint]]>
							</Tracking>
							<Tracking event="firstQuartile">
								<![CDATA[https://tavoos.net/services/vast/v8hQilXv-e1KH-aDrJ-3BWV-LKnnTx5wvisf/382/campaigns/1598/contents/2390/61c2293534f3e/05OcBOhIWv/event/firstQuartile]]>
							</Tracking>
							<Tracking event="midpoint">
								<![CDATA[https://tavoos.net/services/vast/v8hQilXv-e1KH-aDrJ-3BWV-LKnnTx5wvisf/382/campaigns/1598/contents/2390/61c2293534f3e/05OcBOhIWv/event/midpoint]]>
							</Tracking>
							<Tracking event="thirdQuartile">
								<![CDATA[https://tavoos.net/services/vast/v8hQilXv-e1KH-aDrJ-3BWV-LKnnTx5wvisf/382/campaigns/1598/contents/2390/61c2293534f3e/05OcBOhIWv/event/thirdQuartile]]>
							</Tracking>
							<Tracking event="complete">
								<![CDATA[https://tavoos.net/services/vast/v8hQilXv-e1KH-aDrJ-3BWV-LKnnTx5wvisf/382/campaigns/1598/contents/2390/61c2293534f3e/05OcBOhIWv/event/complete]]>
							</Tracking>
						</TrackingEvents>
						<VideoClicks>
							<ClickThrough>
								<![CDATA[https://www.delgarm.com/framework/banners/click/68]]>
							</ClickThrough>
						</VideoClicks>
						<MediaFiles>
							<MediaFile delivery="" type="application/x-mpegURL">
								<![CDATA[https://cdn.delgarm.com/uploads/contentuploads/2022/01/05/J60SFpALVUN53zGwzYiU1pOtXCo1bRWpQQZWpnTK387-HLS.m3u8]]>
							</MediaFile>
							<MediaFile delivery="" type="video/mp4">
								<![CDATA[https://cdn.delgarm.com/uploads/contentuploads/2022/01/05/J60SFpALVUN53zGwzYiU1pOtXCo1bRWpQQZWpnTK355-vast.mp4]]>
							</MediaFile>
						</MediaFiles>
					</Linear>
				</Creative>
			</Creatives>
		</InLine>
	</Ad>
</VAST>
```

Demo in before video play: https://video.delgarm.com/v/ajn8o
