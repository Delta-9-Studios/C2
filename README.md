# Chat 2 (C2)
Delta 9 Studio / Systems
	snipe10090
	You are free to make the system better or customise it or steal it idrc.
	
	Some code for custom stuff
	MM:message("System","Hello  ",player,chat.templates.sys,"APM",PS:GetFromName("System"))
				Name    Message  Recipient   template 	   MessageType Profile
			
	Message Types:
	
	> "N" or nil Normal, message to all players
	MM:message(player,"Hello World",nil,nil,"N",profile)
	
	> "PM" Private Message, message to one player
	WIP
	
	
	> "A" Announcement/Admin, template message to all players with custom username(To create profile for custom name: PS:Create(NAME,FULLNAME,"Description",{Badges}))
	MM:message("System","Message",player,chat.templates.sys,"A",PS:GetFromName("System"))
	
	> "APM" Admin Private Message, template message to one player with custom username(To create profile for custom name: PS:Create(NAME,FULLNAME,"Description",{Badges}))
	MM:message("System","Message",player,chat.templates.sys,"APM",PS:GetFromName("System"))

	All messagetypes need a associated Profile
