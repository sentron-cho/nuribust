# nuribust
버킷 리스트 웹사이트

## node module install
  npm install

## client run
  npm run client

## server run
  npm run dev

## storybook run
  npm run start


## submodule object add
  git submodule add https://github.com/sentron-cho/object.git
or
  git submodule add --force https://github.com/sentron-cho/object.git ./object

## submodule object commit
  cd object
  git commit -am 'update object'
  git push
  cd ../
  git commit -am "update submodule"
  git push

## submodule object update
  cd object
  git pull
  cd ../
  git commit -am "update submodule"
  git push

## submodule object update
  git submodule update
  //git submodule update --remote --merge

## git detached HEAD 해결 방법
  git checkout -b <new branch name>

## git log & graph
  git reflog
  git log --graph --decorate $(git rev-list -g --all)
