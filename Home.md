
---
cssclass: dashboard
banner: "![[Hive Banner.gif]]"
banner_y: 0.494
banner_x: 0.5

---
<div class="title" style="color:#FFC300"; text-shadow: 0 0 10px rgba(255, 195, 0, 0.8);>Hive Mind Dashboard</div>


# Vault Info


- 🔖 Tagged:  favorite 
 `$=dv.list(dv.pages('#favorite').sort(f=>f.file.name,"desc").limit(4).file.link)`
- 〽️ Stats
	-  File Count: `$=dv.pages().length`
	

- 🗄️ Recent file updates
 `$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(11).file.link)`


# The List
- 💻 Dev Quest
	- [ ] [[Dev Roadmaps By Priority#Main Long Quest | Main Quest]]
	- [ ] [[Dev Roadmaps By Priority#New Path | New Path of Exploration]]
	- [ ] [[Dev Roadmaps By Priority#Side Quest Revist |  Side Quest]]


