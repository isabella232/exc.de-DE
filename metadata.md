---
cloud: Experience Cloud
product: experience cloud
solution: Experience Cloud
type: Documentation
git-repo: https://git.corp.adobe.com/AdobeDocs/exc.de-DE
index: false
source-git-commit: 6db89e7ff9957afb7749ca4e8ccd5ca6dd9aca33
workflow-type: tm+mt
source-wordcount: '157'
ht-degree: 100%

---


<!-- We need better links for Getting Started and Tutorials. We can do this after we hit stage -->

# Metadaten für die interne Verwendung

Die Datei metadata.md enthält Metadaten auf Repo-Ebene, die an die TOC.md-Dateien des Benutzerhandbuchs im Repo weitergegeben werden. Wenn Sie den Inhalt von metadata.md für ein Benutzerhandbuch ändern möchten, tun Sie dies in einer beliebigen TOC.md-Datei.

| metadata | was es macht |
|--- |--- |
| solution-title | Wird in der Artikelkopfzeile als Link verwendet |
| solution-hub-url | Öffnet die helpx-Hub-Seite |
| solution-icon | Zeigt Lösungssymbol neben dem Titel der Lösung an. Noch nicht implementiert |
| getting-started-title | Wird selten verwendet, wenn Übungen nicht geeignet sind |
| getting-started-url | Link zur Startseite Erste Schritte von helpx |
| tutorials-title | Wird selten verwendet, wenn Übungen nicht geeignet sind |
| tutorials-url | Link zu Video-Übungen – entweder Helpx-Übungen oder KT-Übungen |
| mini-toc-levels | Legt fest, wie viele Überschriftenebenen in der rechten Leiste angezeigt werden. Standardwert ist „2“ |
| git-repo | Gibt den Speicherort des Zusammenarbeits-Repo an. Verwenden Sie den github.com-Spiegel für Dokumente, die für die Öffentlichkeit zugänglich sind |
| Index | set index=no for soft launch |

In der Datei TOC.md

| Metadaten | was es macht |
|--- |--- |
| user-guide-title | Wird in der Artikelkopfzeile als Link verwendet |
| user-guide-url | Öffnet die helpx-Hub-Seite |
