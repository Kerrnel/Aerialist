# Aerialist
Videos Screensaver for Linux, FreeBSD, NetBSD etc. (xscreensaver plugin) using AppleTV + Youtube DL'd videos with collections supported by "crontab" like switching as well as auto caching or online only mode. Will install itself with 'install' as first parameter.

FreeBSD/NetBSD/Darwin/Linux tested

Usage: Aerialist [cmd[parm]] ...

	Aerialist 1.2

	A rewrite of the Aerial screensaver

	Linux video screensaver gone wild - featuring
		AppleTV online or cached
		YouTube via youtube-dl and Seasons
		Resume where the video was last interrupted
		intermittent title/time overlay
		Install / pre-download of videos
			Run this same script with 'install' as a parameter
		Crontab like selection of season
			See "STABLE" below
		(e.g. Fireplace at night in Winter, Places, Animals by weekday)

	Parameters that are "fun" are up front
		Customize by putting overrides into ~/.config/aerialist
		in shell format

	* Usage - For Terminal invocation or called by xscreensaver

	aerialist [cmd[parm]]...
	
	Cmd			Action
	install		install into .xscreensaver file, offer to pre-cache videos
	set			Edit ~/.config/aerialist settings
	seasons		List seasons
	vid [seas]	List videos for a season
	cron		List time table for which videos to play, show current
	test [vid]	Run a test with just this video

	For xscreensaver primarily
	online		Use ATV Videos via web only
		4k		Use 4k versions of ATVs
		hdr		Use HDR versions of ATVs
	offline		Use Cached videos only
	sound [vol]	Set volume to this %age
	aerial		Path to find folders of videos (aka Seasons)
	movies		Path to videos - (no seasons)

