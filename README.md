# Aerialist
Videos Screensaver for Linux, FreeBSD, NetBSD etc. (xscreensaver plugin) using AppleTV + Youtube DL'd videos with collections supported by "crontab" like switching as well as auto caching or online only mode. Will install itself with 'install' as first parameter.

FreeBSD/NetBSD/Darwin/Linux tested

Usage: Aerialist [cmd[parm]] ...

	Aerialist 1.24

	Video screensaver plugin for xscreensaver

		AppleTV online or cached videos
		YouTube/Dailymotion etc via yt-dlp/youtube-dl and Seasons

		Intermittent title/time overlay
		Resume where the video was last interrupted

		Crontab like selection of season
			See "STABLE" below
		(e.g. Fireplace at night in Winter, Places, Animals by weekday)

	* Usage - For Terminal invocation or called by xscreensaver

	aerialist [cmds][parameters]...
	
	Cmd			Action
	---			------
	install		install into .xscreensaver file, offer to pre-cache videos
	set			Edit ~/.config/aerialist settings
	seasons		List seasons
	vid [s]		List videos for a season
	cron		List time table for which videos to play, show current
	test [p]	Run a test with just this video

	sound [v]	Set volume to this %age
	aerial [p]	Path to find folders of videos (aka Seasons)
	movies [p]	Path to videos - (no seasons)
	id [p]		Show video names & ids for a given path

	(For xscreensaver primarily)
	online		Use ATV Videos via web only
		4k		Use 4k versions of ATVs
		hdr		Use HDR versions of ATVs
	offline		Use Cached videos only

	Call with no parameters to test with logging to terminal
	Normally called from xscreensaver to enhance your idle screen
