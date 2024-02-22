# Aerialist
Videos Screensaver for Linux, FreeBSD, NetBSD etc. (xscreensaver plugin) using AppleTV + Youtube DL'd videos with collections supported by cron like switching as well as auto caching or online only mode. Will install itself with 'install' as first parameter.

FreeBSD/NetBSD/Darwin/Linux tested

Usage: Aerialist [cmd [parm]] ...

	Aerialist 1.27

	Video screensaver plugin for xscreensaver

		AppleTV online or cached videos
		YouTube/Dailymotion etc via yt-dlp/youtube-dl and Seasons

		Intermittent title/time overlay
		Resume where the video was last interrupted

		Crontab like selection of season
			See "STABLE" below
		(e.g. Fireplace at night in Winter, Places, Animals, Sports by weekday)

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
	season [p]	Force this season
	movies [p]	Use these videos - (no seasons)
	id [p]		Show video names & ids for a given path

	(For ATV primarily)
	online		Use ATV Videos via web only
		4k		Use 4k versions of ATVs
		hdr		Use HDR versions of ATVs
	offline		Use Cached videos only

	Call with no parameters to test with logging to terminal
	Normally called from xscreensaver to enhance your idle screen

TODO: Proper settings dialog with aerialist.xml for xscreensaver, Mac GUI
Will probably never get there.
