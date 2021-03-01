mvn clean package deploy -DskipMunitTests -DmuleDeploy -P cloudhub -Danypoint.username=%USER_CREDENTIALS_USR% -Danypoint.password=%USER_CREDENTIALS_PSW% -Dmule.env=dev -Dcloudhub.env=Sandbox -Danypoint.businessGroup=wipro -Dcloudhub.region=us-east-1 -Dcloudhub.workers=1 -Dcloudhub.workerType=MICRO
mvn clean package deploy -DskipMunitTests -DmuleDeploy -P cloudhub -Danypoint.username=%USER_CREDENTIALS_USR% -Danypoint.password=%USER_CREDENTIALS_PSW% -Dmule.env=dev -Dcloudhub.env=Sandbox -Danypoint.businessGroup=wipro -Dcloudhub.region=us-east-1 -Dcloudhub.workers=1 -Dcloudhub.workerType=MICRO





 bat '"C:\\Users\\Sujal Anand\\AppData\\Roaming\\npm\\"newman run "C:\\Users\\Sujal Anand\\Desktop\\CI-CD-Newman\\CI-CD-GetFlights-Jenkins.postman_collection.json"  -r htmlextra --reporter-htmlextra-export "C:\\Users\\Sujal Anand\\Desktop\\CI-CD-Newman" --reporter-htmlextra-darkTheme'
 bat 'anypoint-cli --username=%USER_CREDENTIALS_USR% --password=%USER_CREDENTIALS_PSW% runtime-mgr cloudhub-application describe --environment "Prod" Prod-cicd-demo-project'
 
 C:\\Users\\Administrator\\AppData\\Roaming\\npm\\
 C:\Users\Administrator\Desktop\Postman_Collection
 
 anypoint-cli --username=<<username>> --password=<<pwd>> runtime-mgr cloudhub-application deploy --environment "Prod" --runtime "4.3.0" --workers "1" --workerSize "0.1" --region "us-east-1" "Prod-cicd-demo-project" "cicd-demo-project-1.0.11-mule-application.jar" --property "mule.env:prod"