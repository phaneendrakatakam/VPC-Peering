# Creating-an-EC2-Instance

Task Description: Create 2 Virtual networks and subnets in each along with VM’s in 2 different regions and try to ping the VM’s.
Here I’m using AWS cloud for my task
Step1: Create 2 different VPCs in 2 different locations

![image](https://github.com/phaneendrakatakam/Creating-an-EC2-Instance/assets/145963393/64c8ac36-eaa2-490d-a7a7-fa6b5d20f72c)

![image](https://github.com/phaneendrakatakam/Creating-an-EC2-Instance/assets/145963393/74e574e2-96c2-4a63-8316-cb5130fd1e58)

Step2: Navigate to the “Peering Connections” option 

![image](https://github.com/phaneendrakatakam/Creating-an-EC2-Instance/assets/145963393/2f9788e8-ae85-457d-8af2-c808a673ecba)

Step3: Name the peering connection, Select the Requester VPC ID

![image](https://github.com/phaneendrakatakam/Creating-an-EC2-Instance/assets/145963393/05c9c0d9-c25b-4d24-b7c2-473c31cf4375)

Step4: Select the VPC ID and the location of Acceptor VPC and “Create Peering Connection”.

![image](https://github.com/phaneendrakatakam/Creating-an-EC2-Instance/assets/145963393/41dfb5b8-0c7a-4074-ae9a-730792fcc162)

A notification like this will appear after successful request.

![image](https://github.com/phaneendrakatakam/Creating-an-EC2-Instance/assets/145963393/e0651c1e-2d8f-42d5-b8a3-d7548d0d848f)

Step 6: A request notification will appear on acceptor side.

![image](https://github.com/phaneendrakatakam/Creating-an-EC2-Instance/assets/145963393/2e1e79b6-c94c-4536-aaf6-e5e0489229b8)

Accept the Request

![image](https://github.com/phaneendrakatakam/Creating-an-EC2-Instance/assets/145963393/afae9bf4-ec20-4efa-b097-5bf105b41d19)

Step 7: Created 2 EC2 Instances in each region.

![image](https://github.com/phaneendrakatakam/Creating-an-EC2-Instance/assets/145963393/91e7e937-2ba9-42b0-a438-9380d140d9f8)

![image](https://github.com/phaneendrakatakam/Creating-an-EC2-Instance/assets/145963393/35a135a7-ed4f-4d90-b0be-ac538b322b4c)

Step 8: Edited Inbound Rules for both instances by clicking security groups.

![image](https://github.com/phaneendrakatakam/Creating-an-EC2-Instance/assets/145963393/ca476e88-61e1-4086-b377-e8596c95f474)

![image](https://github.com/phaneendrakatakam/Creating-an-EC2-Instance/assets/145963393/8b90476a-3ad5-4125-879e-45882f068bd5)

![image](https://github.com/phaneendrakatakam/Creating-an-EC2-Instance/assets/145963393/9812e934-beb5-4fc4-b50f-8e7a135b53cb)

Step 9: Connect to both instances using SSH client method.

![image](https://github.com/phaneendrakatakam/Creating-an-EC2-Instance/assets/145963393/d32d0e58-cf5c-4184-a138-53607ae77bd5)

![image](https://github.com/phaneendrakatakam/Creating-an-EC2-Instance/assets/145963393/7c30b326-971a-44fd-b527-e7d3a67d07e7)

Step 10: Noted down the private IP address of one instance.

![image](https://github.com/phaneendrakatakam/Creating-an-EC2-Instance/assets/145963393/35a58279-241a-4330-a2aa-919db4e2895f)

Checked its ping

![image](https://github.com/phaneendrakatakam/Creating-an-EC2-Instance/assets/145963393/728ae8b8-bb8b-4b9f-a53b-a72f4dad0f5f)

If ping is ok, it will show like this

![image](https://github.com/phaneendrakatakam/Creating-an-EC2-Instance/assets/145963393/5c831edd-fcaf-4053-ab5c-9f08296308da)
