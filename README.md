## Hi there 👋

I'm a full stack developer with expertise in NodeJS, Vue, Gulp, git, training, among other talents. Love NodeJS and the command-line. Prefer test driven design.

### want to work with

- Nice people
- NodeJS
- Vue3


## stuff I work(ed) with

### Dorsett Controls

2022 - Present

I work in a multiple respository Windows environment with git for windows and VS-Code. The product is installed on-prem with custom installers. My GH activity does appear on my profile but the company repositories are private.

<table>
 <tbody>
    <tr><td>Electron</td><td>Express</td><td>NodeJS</td><td>Grunt</td><td>Vue</td></tr>
    <tr><td>git</td><td>Sequelize</td><td>JSDoc</td><td>Typescript</td><td>Knockout</td></tr>
    <tr><td>GitHub</td><td>MariaDB</td><td>MongoDB</td><td>ESlint</td><td>Docker</td></tr>
    <tr><td>Mocha</td><td>Sinon</td><td>PowerShell</td></tr>
   </tbody>
 </table>

#### projects

- Dependency management (PowerShell, Git, NodeJS, Express)
- Deployment	& installation	automation	(Power Shell, Git, NodeJS, Express)
- Code	reviews, JSDoc, style guide, static analysis (GitHub, ESLint, SonarLint )
-	Unit	testing (Mocha, Sinon)
-	Developer	Documentation Wiki (GitHub, Markdown)


### East Carolina University

2017 - 2021

I worked in a multiple respository Windows environment with git for windows and VS-Code. Most of my commits are on the university GitHub Enterprise server without cloud support. :confounded:
  
  <table>
 <tbody>
    <tr><td>ColdFusion</td><td>NodeJS</td><td>Angular<br>(1,7+)</td><td>Gulp</td><td>BASH</td></tr>
    <tr><td>Mocha</td><td>Sinon</td><td>Jasmine</td><td>Karma</td><td>yargs</td></tr>
    <tr><td>GitHub</td><td>git</td><td>SQL</td><td>ESlint</td><td>MS Server</td></tr>
    <tr><td>Typescript</td><td>policy</td></tr>
   </tbody>
 </table>
 
#### cool stuff I created @ ECU

_Not publically available_

- centralized builders (NodeJS)
  - we have lots repositories which used to have individual build scripts (gulp). Making changes required numerous pull requests. By centralizing the building code into a single repository (currently a mono-repo with several builders) I've reduced maintenance significantly.
- release commits (TM 😄) (NodeJS)
  - with so many repositories, deployments used to involved running a build for each and then zipping up the result to be passed on to a deployment system. Even when running in parallel and an offline package mirror this took a long time. My solution was to build the repository targeting a folder in the repository itself. I then built tools for developers to create a release commit and another to copy a release commit into a web root or where ever. Deployments are super fast now. And PR reviewers no longer need to build a repository for functional review.
- yarn audit scanner (NodeJS, GH Rest API)
  - using the yarn 1.x audit function, download the package.json/yarn.lock for every deployable (denoted via repository tags) repository and run yarn audit dumping the result as json. Then procress these files to create issues in the impacted repositories. These issues contain a human readable component (of every dependency with a CVE) and a serialized compressed comment. Acting as a database, read these comments to detect changes between scanning runs so that tool knows to update, close, or create an issue.


<br><hr><br>

### looking to collaborate on

- blockchain (analytics) 
- electron (anything)

<hr>

[![spotify-github-profile](https://spotify-github-profile.vercel.app/api/view?uid=31bcnnv5e2tuh6whjl37ll3pl6ze&cover_image=true&theme=default&show_offline=true&background_color=121212&bar_color_cover=true)](https://spotify-github-profile.vercel.app/api/view?uid=31bcnnv5e2tuh6whjl37ll3pl6ze&redirect=true)
