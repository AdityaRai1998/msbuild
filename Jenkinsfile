// Defining Variable
def myVariable = "C:/ProgramData/Jenkins/.jenkins/workspace/unittestdemo/ConsoleApp"
pipeline 
{
		
    agent any
	stages 
	{
	    
        stage('build') // Building the Application
        {
            steps
            {
                bat "dotnet build ${myVariable} --configuration Release"
                //C:\ProgramData\Jenkins\.jenkins\workspace\demo1\aspnet-core-dotnet-core
            }
        }
        stage('Test')
        {
            steps
            {
                bat "dotnet test ${myVariable}"
                //C:\ProgramData\Jenkins\.jenkins\workspace\demo1\aspnet-core-dotnet-core
            }
        }
        
        
	}
}
