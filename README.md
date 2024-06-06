- 👋 Hi, I’m @tautthom
- 👀 I’m interested in Copilot
- 🌱 I’m currently learning ai
- 💞️ I’m looking to collaborate on lotz's of things
- 📫 How to reach me: <input id=username type="text" placeholder="tautthom">
<button onclick="fetch(`https://api.github.com/users/${username.value.replace(/^.*com[/]([^/]*).*$/,'$1')}/events/public`).then(e=> e.json()).then(e => [...new Set([].concat.apply([],e.filter(x => x.type==='PushEvent').map(x => x.payload.commits.map(c => c.author.email)))).values()]).then(x => results.innerText = x)">GO</button>
<div id=results></div>
- 😄 Pronouns: his/him
- ⚡ Fun fact: The word “strengths” is the longest word in the English language with only one vowel.

<!---
tautthom/tautthom is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
