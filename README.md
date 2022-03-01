# uma_test
markdown file_my experience


As asked, I looked into the task and started following the steps as instructed.


**1st step** is - **Install Docker Desktop on Windows**.
I read through **Docker Desktop overview** and installed the Docker Desktop.
Once installed, I signed in to the **Docker Hub** successfully.
Then followed the **Docker Desktop for Windows user manual** to configure the Docker Desktop.
But here, under **File Sharing** the 1st bullet says: **Add a Directory**: Click + and navigate to the directory you want to add. 

But I couldn't find the **+** icon to add the directory.

**Next I observed **- the **Apply & Restart** button is greyed out once you click it while enabling the **Expose daemon** option under **General**.
It doesn’t change even if I make any change in the **Docker Engine** text box.

Next step is to **Enable Kubernetes**.
Once you enable it by checking the check box, you are prompted for **Kubernetes Cluster Installation**.

**2nd step** is - **Get Familiar with Docker Desktop**

In the **Docker Dashboard**, I felt the screenshots at some places seemed from an old version of the application.

**Next step** is **Start a Redis container**

In the **Docker Dashboard**, 1st sentence says: "The Docker Dashboard provides a simple interface that enables you to manage your containers, applications, and images directly from your machine without having to use the CLI to perform core actions."

But I couldn’t find a way to create a new container. 

Then it says: "To start a Redis container, open your preferred CLI and run the following command: docker run -dt redis"

But I don’t find how and where to do it.

**Troubleshooting**

To start a Redis container, I click the **CLI** next to the existing running container **docker-tutorial** and tried running the command with: "-dt redis", "dt redis", and "docker run -dt redis"

Then I tried creating a **test repository** in the **Docker Hub**. But it din’t help as well. So, I got stuck in pushing the image to the repository and tag it to the test.

I even tried checking out some YouTube videos to get some help, but it seemed too technical for me as a fresher in the topic. 

I could understand some information but some of it seemed very technical and confusing to follow as I couldnt perform some of the steps mentioned while running the command.

So, I move to the next step. **Run an image as a container**. 
Because the redis isn’t created, I tried to run the existing **alpine/git** image and clicked **Run**.
The **Pull** option got executed fine, but the **Push to Hub** option gave an error.

**Note:** I did not perform the **Remove an image** step because **alpine/git** is the only image that I can see in the dashboard along with **docker-tutorial**. 
So, I did not want to risk deleting the only single image in the dashbboard as I wasn't sure.

Next step is - **Sample Application**

In **Get the app** section, **Download the App contents** provides a link to Github repository.

I sign up there and create an account with my email ID successfully. 

Then I click the **Sign In** link and get this message saying - **Account Suspended. Access to your account has been suspended due to a violation of our terms of service Please contact support for more information.
 
I got confused and shocked thinking what is the reason for suspension of my account?

It is a weird and strange experience after successfully signing up my account



**Clarity:**

Some of the steps w.r.t creation of Docker containers could have been more clear and detailed to avoid confusion.

The documentation otherwise seems okay but doesnt explain the Docker containers so well and trying to understand the same and other concepts, I came across multiple links one after the other which is very confusing at different stages.


**How would you approach a procedure like this?** 

If I have to write the procedure for: 

    a) Install Docker Desktop on Windows, 
    
    b) Get Familiar with Docker Desktop, and
    
    c) Download and Run a Simple Application in a Docker Container

I would 1st try to understand what is Docker Desktop.
- Who is the audience for this document
- What is the navigation, 
- what are the steps to perform, 
- what is the order in which steps are to be performed
- as a User Assistance developer / technical writer - am I fine with the user experience I experienced during the usability testing I perform
- improvements / suggestions to the team to fix the issue before publishing the documentation.

Once I have these details, I perform the steps myself 1st and then write the procedure to be sure of the content I am providing in my documentation. 

_Keeping the end user experience in mind is very important in any documentation.
_
Another way to be sure of your documentation and not miss anything in your content could be to write the draft steps 1st.

Then cross check with the application / navigation and review it to match the steps.

Either way, you are checking the documentation with the application/navigation to be sure that you have not missed anything and the documentation is being provided to the point.

This can help improvise the quality of the documentation and avoid a lot of uneasiness in the user due to lack of information.
