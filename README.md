### Hi! 👋 Welcome to my playground.

```bash
wget "https://about.me/info/basic"
```
```json
{
	"name":"Myles",
	"languages":{
		"spoken":["English"],
		"development":["JavaScript", "TypeScript", "Python"]
	},
	"loc":"Somerset, UK",
	"hobbies":["Photography", "Aerial Videography"],
	"socials":{
		"linkedIn":"https://www.linkedin.com/in/myles-hunt",
		"gitHub":"https://github.com/myles3850"
	}
}
```
I'm Myles, a developer that's passionate about the data driven world we live in, and it's relationship between our physical and digital lives.

I love all things open source, and aspire to help build data driven technology that can assist those who need it.

Now you know a bit about me, let me quickly save that response we just got.👨🏽‍💻

```sql
START TRANSACTION;
SET @userId = (
	SELECT id FROM developer WHERE name = response.name
);

INSERT INTO profile (user_id, languages, hobbies, links) 
VALUES (@userId, languages, hobbies, socials);
COMMIT;
```
Much better! Now we have that stored, lets see just how far we can go. 🛫
<!--
**myles3850/myles3850** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

*** 87%
-->
