# huawei-cloud-initial-case-patika
huawei cloud practicum technical case

# Huawei Cloud Technical Case ☁ 


## Case: Communicate VPCs Each Other

You are expected to set up a network structure by using HUAWEI CLOUD’s basic services. This application will consist of VPC, VPC-Peering, ECS and RDS. 

### Step 1. Create three VPCs with different IP pool.
<img src="https://user-images.githubusercontent.com/79975486/204030298-1420c604-2082-4c27-bcb1-9b20f0b98cf9.png">

### Step 2. Create a Security Group and allow this security group for every incoming request.
<img src="https://user-images.githubusercontent.com/79975486/204030516-89828f05-15c6-47af-b4b3-853093d6173b.png">

### Step 3. Create two ECS’, one in 1. VPC one in 2. VPC
<img src="https://user-images.githubusercontent.com/79975486/204030732-15ff659f-1dde-4c99-b02a-2d9dbf505a5e.png">

### Step 4. Create database (use RDS for mysql) in 3.VPC
<img src="https://user-images.githubusercontent.com/79975486/204030871-d5c569ec-910a-4d25-87e3-cb346c0a4761.png">
<img src="https://user-images.githubusercontent.com/79975486/204030979-28a87b87-d129-4c5f-b93b-81509d4f6c08.png">

### Step 5. Create VPC-Peering between 1.VPC-2.VPC, 1.VPC-3.VPC and 2.VPC-3.VPC
<img src="https://user-images.githubusercontent.com/79975486/204031055-9db88742-6284-4317-b6d5-81abb124782f.png">
<img src="https://user-images.githubusercontent.com/79975486/204031384-165d8ce7-670a-49d7-9ce3-b6d6a73e397a.png">

### Step 6. Add routing rules to use VPC-Peerings.
<img src="https://user-images.githubusercontent.com/79975486/204031826-907ac7b3-8b6a-4202-b0e6-c140836ffeca.png">

### Step 7. Use “Remote Login” for ECS’ and try to ping other ECS and RDS again.
<img src="https://user-images.githubusercontent.com/79975486/204031466-656511d1-0771-42a1-9efa-f1e146f685aa.png">
