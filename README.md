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
<li>Creating a Virtual Machine and Working With it</li>
<li>Managing Resource Group and VM when not in use</li>
</ul>
<br />

<h2>A Video Break Down Of Everything Discussed In This Tutorial.</h2>

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


<h1><strong>The setup and introduction to Microsoft Azure: Step By Step.</strong></h1>

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

<h2>Creating a Resource Group</h2>

<p>
<img src="https://imgur.com/ooPR3KF.jpg" height="80%" width="80%" alt="Creating a Resource Group"/>
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

<h2>Creating a Resource Group</h2>


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

<h2>Creating a Resource Group</h2>


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

<h2>Creating a Storage Account</h2>

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

<h2>Creating a Storage Account</h2>

<p>
  <img src="https://imgur.com/ooPR3KF.jpg" height="80%" width="80%" alt="Creating a Storage Account and Working With Files">
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

<h2>Creating a Storage Account</h2>

<p>
<img src="https://imgur.com/UGZemL4.jpg" height="80%" width="80%" alt="Creating a Storage Account and Working With Files">
</p>
<p>
  <ol type="1">
    <li>Click create to finish creating the Storage Account.</li>
  </ol>
</p>
<br />
<hr>

<h2>Creating a Storage Account</h2>

<p>
<img src="https://imgur.com/91TLQf0.jpg" height="80%" width="80%" alt="Creating a Storage Account and Working With Files">
</p>
<p>
  <ol type="1">
    <li>A display message and notification of “Your deployment is complete” will display when the storage account creation is successfull.</li>
  </ol>
</p>
<br />
<hr>

<h2>Creating a Storage Account</h2>

<p>
<img src="https://imgur.com/dcK2s5T.jpg" height="80%" width="80%" alt="Creating a Storage Account and Working With Files">
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
<h2>These steps will show how to create a simple text file and upload it to the created Storage Account from the previous step.</h2>
<h3>Locate and select the appropriate software to create a text file.</h3>

<p>
<img src="https://imgur.com/Yu26Pe5.jpg" height="100%" width="100%" alt="WorkingWithFiles"/>
</p>
<p>
  <ol type="1">
    <li>Locate Notepad on Windows or the Text Edit software on a Mac computer.</li>
    <li>Open the software where we will create a simple text file.</li>
  </ol>
</p>
<br/>
<hr>

<h3>Creating Text File</h3>

<p>
<img src="https://imgur.com/DLpShVh.jpg" height="80%" width="80%" alt="WorkingWithFiles"/>
</p>
<p>
 <ol type="1">
   <li>Create a simple text file.</li>
   <li>Save it on desktop as a .txt file for easy access.</li>
 </ol>
</p>
<br/>
<hr>

<h2>Uploading The Created Text File</h2>

<p>
  <img src="https://imgur.com/rwmLFIW.jpg" height="80%" width="80%" alt="WorkingWithFiles">
</p>
<p>
  <ol type="1">
    <li>Locate the storage account created in the previous steps - Azure • Home • Storage Account.</li>
    <li>Find the data storage option and click on containers.</li>
  </ol>
</p>
<br/>
<hr>

<h2>Uploading The Created Text File</h2>

<p>
<img src="https://imgur.com/0fuL5di.jpg" height="80%" width="80%" alt="WorkingWithFiles">
</p>
<p>
  <ol type="1">
    <li>Click on Container option in the Data Storage drop down and a new Container box will display to the right of the screen.</li>
    <li>Type in name for the newly created Container.</li>
    <li>Click Create.</li>
  </ol>
</p>
<br/>
<hr>

<h2>Uploading The Created Text File</h2>

<p>
<img src="https://imgur.com/jxKmHrP.jpg" height="80%" width="80%" alt="WorkingWithFiles">
</p>
<p>
  <ol type="1">
    <li>Once you are inside the newly created container click on the upload option.</li>
    <li>An upload box will display to the right hand side of the screen where the file will be uploaded into.</li>
    <li>Drag and drop the created text file into the upload box.</li>
  </ol>
</p>
</br>
<hr>

<h2>Uploading The Created Text File</h2>

<p>
  <img src="https://imgur.com/VD4cmZW.jpg" height="80%" width="80%" alt="WorkingWithFiles">
</p>
<p>
  <ol type="1">
    <li>Once the text file has uploaded, click on the three dots on the right hand side and an option box will display.</li>
    <li>Click the view/edit option to preview the uploaded text file.</li>
  </ol>
</p>
</br>
<hr>

<h2>Uploading The Created Text File</h2>

<p>
  <img src="https://imgur.com/4v584Uz.jpg" height="80%" width="80%" alt="WorkingWithFiles">
</p>
<p>
  <ol type="1">
    <li>After clicking on view/edit option the uploaded file will display a box.</li>
    <li>Here you can edit - save - download the uploaded text file after any change has been made.</li>
    <li>You have succesfully created and uploaded a Text File into the storage account on the Azure platform.</li>
  </ol>
</p>
</br>
<hr>

<h1><strong>Creating a Virtual Machine and Working With it</strong></h1>
<h2>An Azure Virutal Machine (VM) is a cloud-based virtual computer you can run and manage in Microsoft Azure.</h2>
<h3>In this tutorial the following will be covered.</h3>
<ol type="1">
<li>Creating a Virtual Machine.</li>
<li>Logging into the Virtual Machine.</li>
<li>Logging out of the VM and managing when not in use.</li>
</ol>
</br>
<hr>

<h2>Creating a Virtual Machine</h2>
<p>
  <img src="https://imgur.com/L7iX6Ku.jpg" height="80%" width="80%" alt="CreatingaVirtualMachine">
</p>
<p>
  <ol type="1">
    <li>Go to the home page on the Azure platform and locate Virtual Machines.</li>
    <li>Click on Virutal Machine option to get started.</li>
  </ol>
</p>
</br>
<hr>

<h2>Creating a Virtual Machine</h2>

<p>
  <img src="https://imgur.com/UAegncY.jpg" height="80%" width="80%" alt="CreatingaVirtualMachine">
</p>
<p>
  <ol type="1">
    <li>Click create in either place on the Virtual Machines page.</li>
    <li>Select and click on Virtual Machine from the drop down menu.</li>
      </ol>
</p>
</br>
<hr>

<h2>Creating a Virtual Machine</h2>

<p>
  <img src="https://imgur.com/78l3CZn.jpg" height="80%" width="80%" alt="CreatingaVirtualMachine">
</p>
<p>
  <ol type="1">
    <li>Select the subscription you are using.</li>
    <li>Select the Resource Group previously created to store the VM into.</li>
    <li>Name the Virtual Machine.</li>
    <li>Select the appropriate region you are using the VM from.</li>
    <li>Here is where you will select the type of VM you want to use - etc. Windows Fro - Linux. For testing purposes select Windows 10 Pro version 22H2 - x64 Gen.</li>
    <li>Create a username and password *Remeber these credentials as you will be usingthem to log into the actual Virtual Machine once
created.</li>
    <li>Keep certain options at their default setting.</li>
     <li>Make sure the box for Licensing is checked before proceeding.</li>
     <li>Click Review + Create.</li>
  </ol>
</p>
</br>
<hr>

<h2>Creatng a Virtual Machine</h2>
<p>
  <img src="https://imgur.com/TxxRBtk.jpg" height="80%" width="80%" alt="CreatingaVirtualMachine">
</p>
<p> 
  <ol type="1">
    <li>A message will display that the Validation has passed.</li>
    <li>Click create on the bottom of the page to continue in creating the Virtual Machine.</li>
    <li>The Virtual Machine has been successfully create.</li>
  </ol>
</p>
</br>
<hr>
  

<h2>Logging Into a Virtual Machine</h2>
<h3>The virtual machine that is accessed in this tutorial is from a Mac computer to a windows. Towards the end of the logging in tutorial the version of Windows to Mac will be presented</h3>
<p>
  
</p>
