# Pulumi command Notes

pulumi config set aws:region "us-east-1"
pulumi config set ecs:ami "ami-0c3dda3deab25a563"
pulumi config set ecs:key_pair "devrel-angel-rivera"
pulumi config set ecs:ec2_type "t4g.medium"
pulumi config set ecs:iam_profile "ec2ECSRole"
pulumi config set ecs:asg_min 3
pulumi config set ecs:asg_max 5
pulumi config set ecs:asg_desired 3
pulumi config set ecs:ecs_desired_count 3
pulumi config set docker:image_name "ariv3ra/aws-circleci-modernization-workshop-code"
pulumi config set docker:image_tag "latest"
