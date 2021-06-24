properties([parameters([string(defaultValue: 'mirit', name: 'NAME')]), pipelineTriggers([pollSCM('* * * * *')])])
node{
    stage("one"){
        git branch: 'main', url: 'https://github.com/mirittw/pycharm-repo.git'
        bat "more Name.txt"
    }
}
