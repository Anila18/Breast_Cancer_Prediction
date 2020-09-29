# Breast_Cancer_Prediction
Application of Ensemble Machine Learning classification approach, with SVM, Logistic Regression, Decision Trees as sub Models.

{
    "summary": [
        {
            "groupName": null,
            "groupId": "sg-01822eed13474bcad",
            "account": "754249303703",
            "region": "us-east-1",
            "vpc": null
        },
        {
            "groupName": "POMS-internal",
            "groupId": "sg-01822eed13474bcad",
            "account": "754249303703",
            "region": "us-east-1",
            "vpc": "vpc-d966aca1"
        }
    ],
    "tags": [{
          "Key":"aws:cloudformation:stack-id",
          "Value":"arn:aws:cloudformation:us-east-1:754249303703:stack/POMS-provision-securitygroups-app/75e90b30-de6d-11ea-b114-0a34514375d1"
        },
        {
          "Key":"role",
          "Value":"arn:aws:sts::754249303703:assumed-role/JENKINS_POMS/d6127c2df64b4ebc961eaa58d7a27dbe"
        },
        {
          "Key":"AGS",
          "Value":"POMS"
        },
        {
          "Key":"aws:cloudformation:logical-id",
          "Value":"POMSinternal392481701"
        },
        {
          "Key":"aws:cloudformation:stack-name",
          "Value":"POMS-provision-securitygroups-app"
        },
        {
          "Key":"managedBy",
          "Value":"PORTUS"
        }],
    "inboundRules": [
        {
            "vpcid": null,
            "source": "sg-01822eed13474bcad",
            "protocol": "tcp",
            "port": 443
        },
        {
            "vpcid": null,
            "source": "sg-01822eed13474bcad",
            "protocol": "tcp",
            "port": 60999
        }
    ],
    "outboundRules": [
        {
            "vpcid": "vpc-d966aca1",
            "destination": "sg-01822eed13474bcad",
            "protocol": "tcp",
            "port": 443
        },
        {
            "vpcid": "vpc-d966aca1",
            "destination": "sg-01822eed13474bcad",
            "protocol": "tcp",
            "port": 60999
        },
        {
            "vpcid": null,
            "destination": "sg-02ee201d89f85028c",
            "protocol": "tcp",
            "port": 443
        },
        {
            "vpcid": null,
            "destination": "sg-01822eed13474bcad",
            "protocol": "tcp",
            "port": 443
        },
        {
            "vpcid": null,
            "destination": "sg-01822eed13474bcad",
            "protocol": "tcp",
            "port": 60999
        },
        {
            "vpcid": null,
            "destination": "sg-0c823f473c5f032df",
            "protocol": "tcp",
            "port": 5432
        },
        {
            "vpcid": null,
            "destination": "sg-02ee201d89f85028c",
            "protocol": "tcp",
            "port": 443
        },
        {
            "vpcid": "vpc-d966aca1",
            "destination": "sg-01822eed13474bcad",
            "protocol": "tcp",
            "port": 443
        },
        {
            "vpcid": null,
            "destination": "sg-01822eed13474bcad",
            "protocol": "tcp",
            "port": 443
        },
        {
            "vpcid": null,
            "destination": "sg-01822eed13474bcad",
            "protocol": "tcp",
            "port": 60999
        },
        {
            "vpcid": "vpc-d966aca1",
            "destination": "sg-01822eed13474bcad",
            "protocol": "tcp",
            "port": 60999
        },
        {
            "vpcid": null,
            "destination": "sg-0c823f473c5f032df",
            "protocol": "tcp",
            "port": 5432
        }
    ]
}
