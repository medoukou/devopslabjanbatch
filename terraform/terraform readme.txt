main-----you will have main code which will cerate the resources
variables.tf-----what type of input you want from the user whether it will accept, or take input in which format
string
int
decimal
bool
variables.tfvars---- the actual value which you want to pass while creating up the resources is passed in this file
locals.tf
outputs.tf: i will out put the details of the resources created
console output
provider.tf: this will contain configuration of terraform code




different type of blocks in terraform
resource: it creates the resources
data: it bring the value and pass it to the template
module: it is used to give refernce of the folder/ reource/ module which you want to create


depends on: it is used to pass the parent child relation, mens until the parent resource is created. child code should not be executed.