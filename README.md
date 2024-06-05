# IaC

### IAM Policy for Github Workflow User
```yaml
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Effect": "Allow",
            "Action": [
                "eks:CreateCluster",
                "eks:DescribeCluster",
                "eks:ListClusters",
                "eks:DeleteCluster",
                "eks:CreateNodegroup",
                "eks:DescribeNodegroup",
                "eks:ListNodegroups",
                "eks:DeleteNodegroup",
                "ec2:DescribeVpcs",
                "ec2:DescribeSubnets",
                "ec2:DescribeSecurityGroups",
                "ec2:CreateSecurityGroup",
                "ec2:AuthorizeSecurityGroupIngress",
                "ec2:AuthorizeSecurityGroupEgress",
                "ec2:CreateVpcEndpoint",
                "ec2:DescribeRouteTables",
                "ec2:CreateRoute",
                "iam:GetRole",
                "iam:CreateRole",
                "iam:DeleteRole",
                "iam:DeleteRolePolicy",
                "iam:PassRole",
                "kms:CreateKey",
                "kms:DescribeKey",
                "kms:TagResource",
                "logs:CreateLogGroup",
                "logs:DescribeLogGroups",
                "logs:CreateLogStream",
                "logs:DescribeLogStreams",
                "logs:PutLogEvents",
                "logs:PutRetentionPolicy",
                "logs:DeleteLogGroup",
                "logs:DeleteLogStream",
                "s3:CreateBucket",
                "s3:DeleteBucket",
                "s3:GetBucketPolicy",
                "s3:PutBucketPolicy",
                "s3:ListBucket",
                "s3:ListAllMyBuckets",
                "s3:PutObject",
                "s3:GetObject",
                "s3:DeleteObject"
            ],
            "Resource": "*"
        }
    ]
}
```