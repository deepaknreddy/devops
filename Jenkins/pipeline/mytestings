#! groovy
pipeline
{
    agent any
    stages
    {
        stage("display branch name")
        {
            steps
            {
                scripts
                {
                    echo "branch name is $BRANCH_NAME"
                }
            }
        }
    }
}
