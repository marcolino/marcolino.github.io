# villaclaudia-web

# Nice related videos to youtube-dl and use:
 - 2krB5_xElIM
 - 9aouYDfSiFE

 # Command to remove bluish hue from video:
ffmpeg -i Portovenere\ vista\ da\ un\ drone\ -\ Portovenere\ Aerial\ Footage\ -\ Wonderful\ Italian\ Masterpiece\ Landscape-2krB5_xElIM.mkv -vf "colorbalance=bs=-.3:bm=-.3:bh=-.3" -pix_fmt yuv420p -ss 18 -t 3 -y PV2.mp4 && totem PV2.mp4
