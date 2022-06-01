# terraformtraining
For Hashicorp Certfied terraform engineer associate

All training materials goes in here 


# Login to Azure Acocunt 

` Az login `

# Check Default Subscription on Account 

` Az account list --query "[?user.name=='ayandaezekiel@gmail.com'].{Name:name, ID:id, Default:isDefault}" --output Table `

# TO use a specific Azure subscription 

` az account set -subscription "<subscription_id_or_subscription_name>" `

