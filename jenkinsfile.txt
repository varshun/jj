pipeline
{
    agent any
    git 'https://github.com/varshun/jj.git'
    stages
    {
        stage("compile")
        {
             bat label: '', script: 'mvn compile'
        }
    }
}
