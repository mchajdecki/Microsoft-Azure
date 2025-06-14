<p align="center">
<img src="https://imgur.com/EVhaRNV.png" alt="Azure Logo" Width="600px" Height="200px">
  
</p>

<h1>Microsoft Azure - Set Up and Getting Started</h1>
<h3>Microsoft Azure is a cloud platform that helps you build, run, and manage applications and services through Microsoft’s data centers.</h3>
This tutorial outlines the following ;
<ul style="list-style: none;">
<li>The setup and introduction to Microsoft Azure</li>
<li>Creating a Resource Group</li>
<li>Creating a Storage Account and Working With Files</li>
<li>Creating a Virtual Machine</li>
<li>Logging into and Using a Virtual Machine</li>
<li>Managing Resource Group and VM when not in use</li>
</ul>
<br />

<h2>Video Demonstration</h2>

- ### [YouTube: Getting Started With Microsoft Azure](https://youtu.be/PIO0gmaMXCg)

<h2>Environments and Technologies Used</h2>

- MacBook Air - Windows 10 on Virtual Machine 
- Internet Browser (Google Chrome) for Mac - (Microsoft Edge) Windows VM
- Microsoft Azure

<h2>Operating Systems Used </h2>

- Windows 10 Pro, version 22H2 - x64 Gen2

<h2>List of Prerequisites</h2>

- Windows PC or Mac / Laptop/Desktop 
- Internet Access
- Microsoft Account
- Payment Method
  <br/>

<hr>


<h1><strong>The setup and introduction to Microsoft Azure</strong></h1>

<h2>Navigating to Azure Website and Creating an Account</h2>

<p>
<img src="https://imgur.com/E3TihXF.png" height="80%" width="80%" alt="Starting With Azure"/>
</p>
<p>
  <ol type="1">
    <li>Search on google or navigate in a browser to the <a href="https://azure.microsoft.com/en-us">Azure Website</a> and click Get Started With Azure located in a blue box.</li>
    <li>Once you click Get Started With Azure you will be prompted to select either (Try Azure For Free) or (Pay As You Go Option). </li>
    <li>Read over the account that's right for you and select it to continue. </li>
  </ol>
</p>
<br />

<h2>Signing Into Microsoft or Creating a New Microsoft Account</h2>


<p>
<img src="https://imgur.com/xhmypmU.png" height="80%" width="80%" alt="Creating An Account"/>
</p>
<p>
<ol type="1">
  <li>Select the right Azure account for you.</li>
  <li>Log into an existing microsoft account if you have one.</li>
  <li>If you dont have an existing microsoft account, create one here.</li>
</ol>
<br />

<h2>Microsoft Verification Steps Prior To Signing In</h2>


<p>
<img src="https://imgur.com/lSgOFx8.jpeg" height="80%" width="80%" alt="Creating An Account"/>
</p>
<p>
<ol type="1">
  <li>Enter the verification details for your Microsoft Account.</li>
  <li>Continue through the steps to finish the Set Up.</li>
</ol>
<br />

<h2>Azure Verification Steps Prior To Signing In</h2>


<p>
<img src="https://imgur.com/4n5Rvik.jpg" height="100%" width="80%" alt="Creating An Account"/>
</p>
<p>
<ol type="1">
  <li>Enter the verification details for your chosen Azure Account.</li>
  <li>Continue through the steps to finish the Verification and account set Up.</li>
</ol>
<br />

<h2>Azure Home Page Breakdown</h2>


<p>
<img src="https://imgur.com/pOC3Kk1.png" height="80%" width="80%" alt="Creating An Account"/>
</p>
<p>
  <h4>Once the account has been created and you are logged in the Azure main page will look like this.
  Familiarize yourself with the features and navigation of Azure main portal</h4>
<ol type="1">
  <li><strong>Portal menu.</strong>This global element can help you to navigate between services. Here, the portal menu is in flyout mode, so it's hidden until you select the menu icon.</li>
   <li><strong>Breadcrumb. </strong>Use the breadcrumb links to move back a level in your workflow.</li>
   <li><strong>Page header.</strong>Appears at the top of every portal page and holds global elements.</li>
   <li><strong>Global search. </strong>Use the search bar in the page header to quickly find a specific resource, a service, or documentation.</li>
   <li><strong>Copilot.</strong></srrogn> Provides quick access to Microsoft Copilot in Azure (preview).</li>
   <li><strong>Global controls.</strong> These controls for common tasks persist in the page header: Cloud Shell, Notifications, Settings, Support + Troubleshooting, and Feedback.</li>
   <li><strong>Your account. </strong>View information about your account, switch directories, sign out, or sign in with a different account.</li>
  <li><strong>Command bar.</strong> A group of controls that are contextual to your current focus.</li>
  <li><strong>Service menu.</strong> A menu with commands that are contextual to the service or resource that you're working with. Sometimes referred to as the resource menu.</li>
  <li><strong>Working pane.</strong> Displays details about the resource or service that's currently in focus.</li>
  </ol>
<br />
<hr>

<h1><strong>Creating a Resource Group</strong></h1>
<h2>A Resource Group is a folder in the cloud that holds virtual machines, virtual networks, storage accounts and other created services.</h2>

<p>
<img src="https://imgur.com/gLnGejh.png" height="80%" width="80%" alt="Creating a Resource Group"/>
</p>
<p>
  <ol type="1">
    <li>Find the Resource Group Option on the home page of the Azure Portal or type in the search box.</li>
    <li>Click on the Resource Group Option to Continue.</li>
  </ol>
</p>
<br />
<hr>

<p>
<img src="https://imgur.com/b6PUbSN.jpg" height="80%" width="80%" alt="Creating a Resource Group"/>
</p>
<p>
  <ol type="1">
    <li>Select the Subscription you are currently using.</li>
    <li>Name the Resource Group.</li>
    <li>Select the appropriate time zone you are located in.</li>
    <li>Click Review + Create on the bottom of the page to continue.</li>
  </ol>
</p>
<br />
<hr>

<p>
<img src="https://imgur.com/LoKrnO4.jpg" height="80%" width="80%" alt="Creating a Resource Group"/>
</p>
<p>
  <ol type="1">
    <li>Click create again to continue.</li>
  </ol>
</p>
<br/>
<hr>

<p>
<img src="https://imgur.com/QnMuRr7.jpg" height="80%" width="80%" alt="Creating a Resource Group"/>
</p>
<p>
  <ol type="1">
    <li>A prompt message will display that the resource group has been successfully created.</li>
    <li>The Resource Group that you create will show in the Resource Group folder with the chosen name - in this example it is named (New_Group).</li>
    <li>The Resource Group has been created.</li>  
  </ol>
</p>
<br/>
<hr>

<h1><strong>Creating a Storage Account and Working With Files</strong></h1>
<h2>A storage account is a service that provides a secure place to store data like files, queues, blobs, tables, and disks, is used to manage and access different types of cloud storage in one place.</h2>

<p>
<img src="https://imgur.com/ribCc8C.jpg" height="80%" width="80%" alt="Creating a Storage Account and Working With Files"/>
</p>
<p>
  <ol type="1">
    <li>Locate the storage account on the main azure home page portal or search box.</li>
    <li>Click on storage accounts option to continue.</li>
  </ol>
</p>
<br />
<hr>

<p>
<img src="https://imgur.com/UPZU49c.jpg" height="80%" width="80%" alt="Creating a Storage Account and Working With Files"/>
</p>
<p>
  <ol type="1">
    <li>Click create in the top left corner of the page or the option in the blue box below to continue.</li>
  </ol>
</p>
<br />
<hr>

<p>
<img src="https://imgur.com/9KRBOuX.jpg" height="80%" width="80%" alt="Creating a Storage Account and Working With Files"/>
</p>
<p>
  <ol type="1">
    <li>Select the current subscription you are using.</li>
    <li>Select the resoure group created in the previous step to put your storage account into.</li>
    <li>Name the storage account.</li>
    <li>Select the time zone appropriate for your location.</li>
    <li>Since we will only be storing a text file in this tutorial select the (Locally-redundant storage (LRS)) - which keeps your data safe by storing multiple copies within a single data center.</li>
  </ol>
</p>
<br />
<hr>

<p>
<img src="https://imgur.com/HjtPQHx.jpg" height="80%" width="80%" alt="Creating a Storage Account and Working With Files"/>
</p>
<p>
  <ol type="1">
    <li>Click create to finish creating the Storage Account.</li>
  </ol>
</p>
<br />
<hr>

<p>
<img src="https://imgur.com/gjG0yVw.jpg" height="80%" width="80%" alt="Creating a Storage Account and Working With Files"/>
</p>
<p>
  <ol type="1">
    <li>A display message and notification of “Your deployment is complete” will display when the storage account creation is successfull.</li>
  </ol>
</p>
<br />
<hr>

<p>
<img src="https://imgur.com/8q7Jlx2.jpg" height="80%" width="80%" alt="Creating a Storage Account and Working With Files"/>
</p>
<p>
  <ol type="1">
    <li>The created storage account will be located in the appropriate resource group selected in the previous steps.</li>
    <li>The storage account has been created successfully.</li>
  </ol>
</p>
<br />
<hr>

<h1><strong>Working With Files</strong></h1>
<h2>These steps will show how to create a simple text file and upload it to our created Storage Account.</h2></h2>


<p>
<img src="https://imgur.com/QqiZ3ac.jpg" height="80%" width="80%" alt="Workingwihfiles"/>
</p>
<p>
  <ol type="1">
    <li></li>
    <li></li>
  </ol>
</p>
<br />
<hr>


