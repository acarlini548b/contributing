#Contributing to OSIsoft Open Source Projects

The information provided on this page complements information you can find in the [GitHub Guidelines on PI Square][5]. 

On this page you will find information to guide you when participating and contributing to OSIsoft Open Source Projects.  We do also encourage you to follow the same guidelines for projects issued from OSIsoft Users Community.

##OSIsoft Open Source Projects
The code hosted on GitHub under the OSIsoft Organization has several goals such as:  

- Demonstrate the usage of [PI Developer Technologies][15]
- Provide samples for OSIsoft's extensible products
- Provide scripts and tools to help administration of the PI System
- Have a space where developers can collaborate

The content in repositories under the OSIsoft organization on GitHub  is offered under the Apache License, Version 2.0. OSIsoft, LLC does not endorse or recommend any products, processes, or services or contributions made to its repositories. Therefore, mention of any products, processes, or services made by a third party cannot be construed as an endorsement or recommendation by OSIsoft, LLC.

##Projects Opened for Contributions

Knowing those different goals, it is important to say that not all projects may be opened for contributions under the OSIsoft organization. If they are, there should be statement in the project README that will explain how to contribute.  If there is not, you should try to contact the repository owner or you can send an email to <pidevclub@osisoft.com>; make sure to do so prior you work too  hard on it!  We really like to encourage community contributions and we will do our best to help you in your contribution effort.  Also Make sure to read the project's **README** to align with what is requested for your contribution to be accepted.

OSIsoft's Users Community may also have repositories where project have already started.  You may look on PI Square and search for [content identified with the GitHub Tag][7].


####Where can I provide my contributions? 
- On [OSIsoft repositories][6] who are inviting you to contribute, this should be stated in the README   
- On other repositories that are hosted by Other Community members [(you may look on PI Square for to find out existing repositories)][7].
- On your own personal GitHub repository

##Code of conduct
OSIsoft welcomes everyone to contribute to its open source projects and also encourages the community to create Open Source Projects for the PI System.  To provide the best atmosphere for contributors OSIsofts recommends that kindness, cooperation and understanding to be an integral part of your projects.  In order to provide a clear definition of what we expect from our community **please read our [Code of Conduct][1]**. We expect all our contributors to respect the code of conduct and report any violations at <pidevclub@osisoft.com>.

##Licensing under the OSIsoft Organization

Projects under the OSIsoft organization are licensed under the [Apache 2.0 license][8] which is a [very permissive license][9]. If you are contributing to projects under the OSIsoft organization, provided code has to be licensed under the Apache license 2.0. To apply the Apache license to your files, you should use the following text and put it in the header of each of your file(s). Replace `<NAME>` per your name. OSIsoft employees should put OSIsoft, LLC as name. And use the correct year.

    Copyright 2016 <NAME>
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
    <http://www.apache.org/licenses/LICENSE-2.0>
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

##Licensing Outside OSIsoft Organization
If you want to create your own open source project on GitHub, you should think about how others will use your work and consider adding a **LICENSE.MD** document to your repository so it explicitly tells others what they can do with the code, **if your repository has no license, the content will be under copyright and owned by you**.  No one would have right to do anything with the code without your permission.  This is why open source licenses were created! If you don't know what license to select we'd recommend you to use the same the one we selected: [Apache 2.0 license][8]. That will make any derivative work easier to integrate because not all licenses are compatible with each others.

##Contribution

###Basic Knowledge
It is much easier to participate and contribute to code if you have the basic knowledge of GitHub and Git.  We propose you few resources to get started that we think may help:

- [GitHub Flow (5m Read)][3]
- [Video Tutorials to understand GitHub][4]
- [Microsoft Tutorial for Visual Studio - (click the Visual Studio Button to show how to do it in VS)][10]


###GitHub Workflow 

There can be many applicable workflows when working with Git and with GitHub.  If you are uncertain how to proceed, check if the README provides information about it. You may also ask the team that maintains the repository by creating a new issue with the [GitHub Issues system][2].

 
- [Fork][10] the project
- Create a [new branch][11] for your changes.  This will isolate changes you make and allow you to keep in sync with the remote master on your local repository.
- make the changes in the new branch, [commit][12]
- Open a [pull request][12] when you are ready to inform you have worked on some changes.
- If the remote master has changed, [sync your local repository(fork)][17] with it, [merge][16] the master into your new branch to test that the latest changes in the remote master work with your new code.
- You can tell the project owner, by using the discussion of your Pull request, that you have completed your changes and they are ready to be merged.
- All changes may not be accepted, they may require re-work, be ready for it!


##Issues and Features Requests
[GitHub Issues system][2] should be used to report issues and ask new features.  

[1]:https://github.com/OSIsoft/contributing/blob/master/code-of-conduct.md   
[2]:https://guides.github.com/features/issues/
[3]:https://guides.github.com/introduction/flow/
[4]:https://www.youtube.com/results?search_query=github+tutorial
[5]:https://pisquare.osisoft.com/docs/DOC-1864
[6]:https://github.com/osisoft
[7]:https://pisquare.osisoft.com/tags#/?tags=github
[8]:https://opensource.org/licenses/Apache-2.0
[9]:https://tldrlegal.com/license/apache-license-2.0-(apache-2.0)
[10]:https://www.visualstudio.com/en-us/get-started/code/share-your-code-in-git-vs
[11]:https://help.github.com/articles/creating-a-pull-request/
[12]:https://www.visualstudio.com/en-us/get-started/code/git/commits
[13]:https://msdn.microsoft.com/en-us/library/jj190809.aspx#switch
[14]:https://msdn.microsoft.com/en-us/library/jj190809.aspx#create_from_published
[15]:https://techsupport.osisoft.com/Products/Developer-Technologies/
[16]:https://msdn.microsoft.com/en-us/library/jj190809.aspx#merge
[17]:https://help.github.com/articles/syncing-a-fork/
