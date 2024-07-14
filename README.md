# Rush monorepo

## rush 命令

build vs rebuild 是否增量构建

rush rebuild --to <project> 重新构建该 project 及其依赖的项目

rush rebuild --from <project> 重新构建该 project 以及所有依赖该 project 的项目

rush update --purge

rush add -p lodash
rush add -p @types/lodash --dev
