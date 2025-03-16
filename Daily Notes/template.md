<%*
const files = app.vault.getFiles().filter(file => file.path.contains("Tarot"))
const random = Math.floor(Math.random() * (files.length - 1))
const randomNote = files[random]
tR += `![[${randomNote.path}|no-title]]\n`
%>