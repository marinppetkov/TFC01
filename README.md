# TFC01
Doing a Markdown
## Random text using Styling
_This is a dummy text written in italic. Inside we might have ~mistakes~ or/and ***important messages***_<br>

## Random text with subscript and superscript
This text use superscript like 1<sup>st</sup>, 2<sup>nd</sup> and 3<sup>rd</sup> and also subscripts like H<sub>2</sub>O
## Basic git commands using quoting
We can create empty git repo with `git init` or clone existing from external source with `git clone`
Once we have our repo we can add files from working dir to staging area with `git add` and commit the changes with `git commit -m <message>` or just `git commit -a -m <message>` for all tracked files that have been changed since last commit. 
```
touch file1 file2 file3
git init
git add .
git commit -m "commiting new changes"
```
> Live long and prosper
## Main public clouds
- This [link](https://aws.amazon.com/) redirect us to AWS ☁️<br>
  - some services
    1. EC2 Instance
    2. S3
    3. ECS
- This [link](https://azure.microsoft.com/en-us) redirect us to Azure ☁️<br>
  - some services
    1. Virtual machine
    2. Blob Storage
    3. Container Service 
- This [link](https://cloud.google.com/) redirect us to GCP ☁️<br>
  - some services
    1. Compute Engine VMs
    2. Cloud Stroage
    3. Container Engine

AWS, GCP and Azure are using the following Hypervisors:
1. XenServer 
1. KVM
1. Hyper-V

![main cloud providers](/images/aws-azure-google.png)[^1]

- [x] Plan
- [ ] Prepare
- [ ] Monitor
- [ ] Evaluate

> [!WARNING]
> Cloud consumption comes at a cost

## Conversations
During conversation you can triger notification to respective teams or person by mentioning their teams or names like this `@github/teamname` `@username` <br>
Referencing to issues or PR is made by typing # eg `#123` 

## Hidden comments
\<!-- sample text -->[^2]
 <!-- This is hidden comment for internal use -->

### Additional stuffs
**Adding new line** 
** Line2 **

[^1]: Image is located in /images
[^2]: This line is ignored with \\ so this text is visible
