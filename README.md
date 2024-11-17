# nomadlouie
youtube downloader


See full documentation at  https://github.com/yt-dlp/yt-dlp#readme

windows arguements

download video save as title-id.mp4
yt-dlp -f mp4 -o %(title)s-%(id)s.%(ext)s https://www.youtube.com/shorts/ltFctTHpXPc

download playlist as mp4
yt-dlp -f mp4 -o "%(playlist)s/%(playlist_index)s - %(title)s.%(ext)s"  https://youtube.com/playlist?list=PLZZhRqYdKZSL__V5mgBS7Kzq4sBerHth0&si=oDhfnTuD5CwmPAUr




with subtitles: this one asks for authentication tho
yt-dlp -f mp4 --write-subs -subs-langs(en) -o %(title)s-%(id)s.%(ext)s https://www.youtube.com/watch?v=TBFO8DKpqCw&list=PLZZhRqYdKZSL__V5mgBS7Kzq4sBerHth0&index=17&pp=gAQBiAQB8AUB
