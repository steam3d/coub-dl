# coub-dl
Module for python to download videos from coub.com

	from coub_dl import Coub
	
	coub = Coub()
	
	coub.video(url,addlink = False)
	coub.audio(url,addlink = True)
`addlink` appends to file name a shrot link **iyd2d** (coub.com/view/**iyd2d**). If your OS does not support UTF-8 then use `addlink = 'no utf-8'`
