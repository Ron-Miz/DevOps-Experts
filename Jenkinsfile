properties(pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("1") {
        git branch: "master", url: "https://github.com/Ron-Miz/DevOps-Experts.git"
        bat "python githubtest.py"
    }
}
