## Hi there 👋

I'm a full stack developer with East Carolina University.

Most of my commits are on the university Github Enterprise server without cloud support. :confounded: 

I work in a multiple respository Windows environment with git for windows and VS-Code. Love NodeJS and the command-line.

### stuff I work with
  
  -  ColdFusion (2018, CFScript, coldbox, testbox)
  -  NodeJS (streams, events, child process)
  -  Angular JS & 11/12
  -  Gulp
  -  BASH (git hooks, aliases, gnu tools)
  -  Mocha / Sinon / Jasmine
  -  yargs ( I create lot of command-line tools )
  -  git (intermediate user, trainer, bit of plumbing)
  -  SQL (oracle)
  -  TDD (when possible)
  -  Documentation (lots)
  -  GitHub Enterprise


### currently learning

   - More about NodeJS
   - More about JavaScript


### looking to collaborate on

  - blockchain   


### cool stuff I've created

_Not publically available_

- auto-node picker (library, NodeJS)
  - finds an installed version of nodeJS suitable for a repository based on it's engines property. Requires NVM (windows or Linux).
  - allows developers to be running multiple versions of NodeJS in multiple shells without having to be concerned about what a repository might support
  - I realize that there are open source tools that can do some of this but this does everything I need.
- NodeJS Launchers (NodeJS)
  - using the above picker, have created launchers for yarn, gulp, angular-cli. For instance, yarn by itself operates on current working directory, but with this tool can run any yarn command in any path `yn -p /some/where -c <command> -v <optional node version including just a major or major.minor> -o <optional flag to select oldest installed satisfying version> -- <params for yarn>` (yn is a shell alias)
- centralized builders (NodeJS)
  - we have lots repositories which used to have individual build scripts (gulp). Making changes required numerous pull requests. By centralizing the building code into a single repository (currently a mono-repo with several builders) I've reduced maintenance significantly.
- release commits (TM 😄) (NodeJS)
  - with so many repositories, deployments used to involved running a build for each and then zipping up the result to be passed on to a deployment system. Even when running in parallel and an offline package mirror this a long time. My solution was to build the repository targeting a folder in the repository itself. I then built tools for developers to create a release commit and another to copy a release commit into a web root or where ever. Deployments are super fast now.
- yarn audit scanner (NodeJS, GH Rest API)
  - using the yarn 1.x audit function, download the package.json/yarn.lock for every deployable (denoted via repository tags) repository and run yarn audit dumping the result as json. Then procress these files to create issues in the impacted repositories. These issues contain a human readable component (of every dependency with a CVE) and a serialized compressed comment. Acting as a database, read these comments to detect changes between scanning runs so that tool knows to update, close, or create an issue.
