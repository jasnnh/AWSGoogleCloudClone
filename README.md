# AWSGoogleCloudClone
Setup your own AWS/Google Cloud server and deploy your instances in PHP

I won't go into details of creating a login & register PHP script and will jump straight into the good details. The idea is to deploy a VM instance that would give our client access to the VPS server so that they have full access to their deployed instance. It's actually very easy in this demo I will be demonstrating this in Oracle's VM VirtualBox as it's my favorite application.

You can view the deploy.php for more information & it's very straight forward and easy to do.

In this example run the deploy.php script it will deploy a new instance and run the VM as a window or headless up to you to decide and then a user can connect to the instance via RDP (Remote Desktop Protocol) just like how Amazon AWS and Google cloud has theirs setup.

The PHP file first off clones a clean image or you can make it setup an entirely new image/settings but for this example it will clone one, then it will assign settings including user and password and RDP settings/port to connect then deploy it either in headless or window.

after it's deployed you can make a status update/checker that runs on the instance to update the database of it's status to update the webpanel and the user can connect with their account credentials.
