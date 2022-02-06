# ytvd 

A Tool To Browse/Search, Stream and Download YouTube Videos From Terminal. The script uses <a href="https://github.com/iv-org/documentation"> Invidious API </a> for fetching Information/Videos from YouTube.

# Showcase

<img width="100%" src="/assets/preview.gif" >

## Dependencies

1. curl
2. jq
3. mpv
4. fzf
5. ffmpeg

# Basic Installation

		git clone https://github.com/sidmaz666/ytvd.git
		cd ytvd
		sudo cp ytvd /usr/bin
###
		sudo curl -Ls https://raw.githubusercontent.com/Sidmaz666/ytvd/main/ytvd -O > /usr/bin/ytvd


# What Does the Script Provide?

1. Search On YouTube.
2. Go To Next Page/Previous Page.
3. Search Again After Search.
4. Show Recommended Videos Based on the Selected Video.
5. Download, Play Multiple Video Formats or Show Video/Audio URLS.

# How To Sort Videos?

To Sort Videos According to <b>Upload Dates</b>. Enter the following accordingly along with the search query.

1. date:hour  
2. date:today
3. date:week
4. date:month
5. date:year

To sort Videos According to <b>Duration</b>

1. duration:short
2. duration:long

Sort By <b><i>Relevance, Rating, Upload Date & Views</i></b>

1. sort:relevance
2. sort:rating
3. sort:date
4. sort:views

## Example

		ytvd "richard stallmen date:year duration:short sort:views"

# Annoyance

Some Geo Restricted/Age Restricted Videos URL doesn't doesn't work, can't Stream or Download. 🙂

# Is there any need of this script?

<i><b>(Talking My Mind Here... 🧠)</b></i>

Yes, because I'm using it and it is personalized to my liking. Most of the features I would want from YouTube while using it from a GUI Web Browser is present here. I know <b>ytfzf</b> exists, it's a great script no doubt, but I'm a student learning on web, Linux about computer in general and so though it would be nice to make one script personalized to mine needs so I don't have to worry about changing of variables in <i>config</i> file.
