node
{
    stage('gitextrat')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/TCQuantum/DevopsLinux.git']]])
    }
    stage('shallscript')
    {
        echo 'hellow'
    }
    stage('shalldate')
    {
        sh 'date'
    }
}
