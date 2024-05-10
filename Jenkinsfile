pipeline 
{
    agent any

   
    stages 
    {
        stage('Build') 
        {
            steps 
            {
                echo "Building the code"
            }
        }
        stage('Test') 
        {
            steps 
            {
                echo "Testing the code"
            }

        }
        stage(package)
        {
            steps
            {
                echo "packing the code"
            }
        }
    }
}
