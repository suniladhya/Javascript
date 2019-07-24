# Links
* [SCOOP](https://github.com/lukesampson/scoop), [YARN](https://yarnpkg.com/en/docs), [YARN dependencies](https://yarnpkg.com/blog/2018/06/04/yarn-import-package-lock/)
# Why Yarn
* Developed by collaboration of faceboo, Google, Tilde, Expo  for consistency, Seurity, performance
* Offline Caching, Offline Mirroring
# Scoop for installing Yarn:
* iex (new-object net.webclient).downloadstring('https://get.scoop.sh')
* scoop install yarn
* yarn --version
# Starting a new project
* yarn init /(generates a package.json file)
## Adding / upgraing / Removing Dependency
* yarn add [package]
* yarn upgrade
* yarn remove
* yarn / yarn install (for installing all the dependencies, generates a yarn.lock if not present)
* yarn install --network-timeout 1000000 // incase it shows a time out error
## Angular project with Yarn
* ng new 
