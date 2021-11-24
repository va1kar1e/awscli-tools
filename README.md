# AWS Console Client Tools

Making AWS Cli Python Script with Boto3


## Configuration Setup

`~/.aws/credentials` (Linux & Mac) or `%USERPROFILE%\.aws\credentials` (Windows)

```plaintext
[default]
aws_access_key_id=<Default Access Key ID>
aws_secret_access_key=<Default Secret Access Key>

[user1]
aws_access_key_id=<User1 Access Key ID>
aws_secret_access_key=<User1 Secret Access Key>
```

`~/.aws/config` (Linux & Mac) or `%USERPROFILE%\.aws\config` (Windows)

```plaintext
[default]
region=ap-southeast-1
output=json

[profile user1]
region=us-east-1
output=text
```

Use command with parameter `--profile user1`

Or Config in Jupyter File

## Install Modules

```powershell
virtual env
env\Scripts\activate or env/bin/activate
python -m pip install boto3
```
