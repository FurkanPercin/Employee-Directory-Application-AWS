### CourseraVpcStack
cdk synth --app "npx ts-node bin/coursera_project.ts" EmployeeVpcStack
cdk deploy --app "npx ts-node bin/coursera_project.ts" EmployeeVpcStack
cdk diff --app "npx ts-node bin/coursera_project.ts" EmployeeVpcStack


### EmployeeServerStack
cdk synth --app "npx ts-node bin/computing.ts" EmployeeServerStack
cdk deploy --app "npx ts-node bin/computing.ts" EmployeeServerStack
cdk diff --app "npx ts-node bin/computing.ts" EmployeeServerStack