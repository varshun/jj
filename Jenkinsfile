pipeline
{
    agent any
    git 'https://github.com/varshun/jj.git'
    stages
    {
        stage("compile")
        {
            steps
            {
             bat label: '', script: 'mvn compile'
            }
        }
    }
}
