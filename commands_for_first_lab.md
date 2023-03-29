#### commands ran for lab168
    
    1  python --version
    2  pip --version
    3  sudo yum install -y wget
    4  wget http://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm
    5  sudo rpm -ivh epel-release-latest-7.noarch.rpm
    6  pip --version
    7  sudo yum install -y python-pip
    8  pip --version
    9  pip install awscli --upgrade --user
    10  aws help
    11  aws configure
    12  aws iam list-users
    13  iam
    14  list-users
    15  aws iam
    16  aws iam list-users
    17  aws iam list-policies
    18  aws iam list-users
    19  aws iam list-users
    20  aws iam list-policies | grep "arn:aws:iam::arn:aws:iam::"
    21  aws iam list-users | grep "arn:aws:iam::485219448625"
    22  aws iam list-policies | grep "arn:aws:iam::485219448625"
    23  get-policy
    24  aws iam get_policy --policy-arn arn:aws:iam::485219448625:policy/lab_policy
    25  aws iam get-policy --policy-arn arn:aws:iam::485219448625:policy/lab_policy
    26  aws sts get-caller-identity
    27  aws iam list-policies | grep "arn:aws:iam::485219448625"
    28  clear
    29  aws iam list-policies help
    30  aws iam list-policies --max-items 2
    31  aws iam list-policies help
    32  aws iam help
    33* aws iam get-group-policy --group-name arn:aws:iam::485219448625:policy/lab_policy
    34  aws iam get-policy lab_policy
    35  aws iam get-user-policy --user-name awsstudent --policy-name lab_policy
    36  aws iam get-user-policy --user-name awsstudent --policy-arn arn:aws:iam::485219448625:policy/lab_policy
    37  aws iam get-user-policy --policy-arn arn:aws:iam::485219448625:policy/lab_policy
    38  history
    39  history37
    40  aws iam get-policy --policy-arn arn:aws:iam::485219448625:policy/lab_policy
    41  aws --version
    42  pip --version
    43  pin uninstall awscli
    44  pip uninstall awscli
    45  pip3 install awscli
    46  cat ~/.aws/credentials
    47  history
    48  aws iam get-user-policy --user-name awsstudent --policy-name lab_policy
    49  aws sts get-caller-identity
    50  aws iam list-policies --max-items 2
    51  aws cli --version
    52  aws --version
    53  pip3 uninstall aws
    54  pip uninstall aws
    55  history
    56  pip uninstall awscli
    57  pip3 uninstall awscli
     58  curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o
    59  curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscli.zip"
    60  ls
    61  unzip awscli.zip
    62  sudo ./aws/install
    63  aws --version
    64  python3 --version
    65  AWS AMI --version
    66  describe-images
    67  aws ec2 describe-image
    68  aws ec2 describe-images
    69  aws ec2 --describe-images
    70* aws ec2 -describe-images --
    71  aws ec2 describe-images     --region us-east-1       --image-ids ami-1234567890EXAMPLE
    72  aws ec2 describe-images     --region us-west-2     --image-ids ami-001e91409ff66b7b0
    73  aws ec2 describe-images \    --filters "Name=tag:Name,Values=web-server-2" \    --query 'Images[*].[ImageId]' \    --output text
