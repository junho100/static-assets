# static-assets

Static Assets like images

# Directory Guide

## provider

Each provider have their own directory. Inside each provider directory.

Default providers:

https://github.com/cloudforet-io/identity/tree/master/src/spaceone/identity/managed_resource/provider

# Example AWS

```
└── providers
    ├── aws
    │   ├── ami.svg             # AWS AMI (cloud service type: ami)
    │   ├── cloudwatch.svg
    │   ├── instance.svg        # AWS EC2 (cloud service type: instance)
    │   └── logo.svg            # AWS provider image
            ...
```

# Direct URL

Github file can be directly accessed using the following URL format:

```
https://raw.githubusercontent.com/cloudforet-io/static-assets/master/providers/{provider name}/{file name}
```

## For example

| File Name | Direct URL |
| --- | --- |
| aws logo | https://raw.githubusercontent.com/cloudforet-io/static-assets/master/providers/aws/logo.svg |
| aws EC2 | https://raw.githubusercontent.com/cloudforet-io/static-assets/master/providers/aws/instance.svg |
| aws AMI | https://raw.githubusercontent.com/cloudforet-io/static-assets/master/providers/aws/ami.svg |
