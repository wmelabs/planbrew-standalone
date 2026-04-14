<img src="logo.png" alt="logo" width="200px"/>  

**Composable Text Templating**

*Standalone (Offline) Version* v1.0.1


---

<table>
<tr>

<td align="center" valign="top">
<img src="main.png" alt="Fragment Library" width="100%"/>
<br/><strong>PlanBrew</strong>
</td>
<td align="center" valign="top">
<img src="main2.png" alt="Blueprint Editor" width="100%"/>
<br/> Live app: <br> https://wmelabs.github.io/planbrew-standalone
</td>

</tr>
</table>

PlanBrew is a text editing system built around composable **fragments** (pieces of text) and **blueprints** (templates that combine fragments to generate final output).

PlanBrew can be used to edit prompts for agentic AI routines, posts on social media, emails, essays, or any task where organizing and keeping track of composable text pieces is paramount.

Fragments can be temporarily or permanently combined and re-ordered with drag and drop. Embed fragments within fragments using a simple {{fragment-id}} notation. PlanBrew automatically keeps track of how fragments link to fragments and blueprints, and shows you where fragments are used. Use tags, folders, favorites and search to keep track of fragments.

Fragments are set into a blueprint, where you can easily switch between a continuous view of the fragments or view each fragment separately. Swap fragments in and out using the fragment palette. Once the blueprint is composed, one button copies the combined text.

Keep projects separated in the project manager. Export and import projects to file (JSON only in the standalone version), or backup the whole database. Many future features are planned. All updates will be backward compatible with prior databases and backups.

## Standalone Mode

Standalone mode is a fully self-contained HTML file with only one external dependency: **Monaco Editor**, loaded from an online CDN.

No server is required to run PlanBrew standalone — it runs entirely in the browser using IndexedDB for local storage.

PlanBrew will be open sourced in the near future. 
