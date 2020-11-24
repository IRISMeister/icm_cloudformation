# icm_cloudformation
deploy ICM via CloudFormation
Please visit https://jp.community.intersystems.com/node/480741/ .

# EC2InstanceのステータスがCREATE_FAILEDした場合
状況の理由  
Security group sg-XXXXXXX and subnet subnet-YYYYYY belong to different networks.  
対処  
パラメータで指定したInstanceSecurityGroupParameterとSubnetIdParameterが同じVPCに属しているか確認してください。  
