<p align="center">
<img src="https://imgur.com/EVhaRNV.png" alt="Azure Logo" Width="600px" Height="200px">
  
</p>
<h1>Microsoft Azure - Set Up and Getting Started</h1>
<h3>Microsoft Azure is a cloud platform that helps you build, run, and manage applications and services through Microsoft’s data centers.</h3>
<h2>This tutorial outlines the following ;</h2>
<ul>
  
<li><a href="#intro">The setup and introduction to Microsoft Azure</a></li>
<li><a href="#resource">Creating a Resource Group</a></li>
<li><a href="#storage">Creating a Storage Account</a></li>
<li><a href="#files">Working With Files</a></li>
<li><a href="#vm">Creating a Virtual Machine and Logging In</a></li>
<li><a href="#manage">Managing Virtual Machine when not in use</a></li>
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


<h1 id="intro">The setup and introduction to Microsoft Azure: Step By Step</h1>

<h2>Navigating to Azure Website and Creating an Account</h2>

<p>
<img src="https://github.com/mchajdecki/Microsoft-Azure/blob/9bf61889a6455155c96763c825d094ca4c46459b/images/1.png" alt="Starting With Azure - Slide_1"/>
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
<img src="https://github.com/mchajdecki/Microsoft-Azure/blob/d029c1fa1397bb8afe2dea0bac099b65a08a735a/images/2.png" alt="Creating An Account - Slide_2"/>
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
<img src="https://github.com/mchajdecki/Microsoft-Azure/blob/6bc9799d5f6ae5a0b0366015fcdc6adb71dbf0cf/images/Slide-3.jpg" alt="Creating An Account - Slide_3"/>
</p>
<p>
<ol type="1">
  <li>Enter the verification details for your Microsoft Account.</li>
  <li>Continue through the steps to finish the Set Up.</li>
</ol>
<br />

<h2>Azure Verification Steps Prior To Signing In</h2>


<p>
<img src="https://github.com/mchajdecki/Microsoft-Azure/blob/ba10361ffbf2a2eaf0ec5d8bb20cac0157bbb9be/images/Slide-4.jpg" alt="Creating An Account - Slide_4"/>
</p>
<p>
<ol type="1">
  <li>Enter the verification details for your chosen Azure Account.</li>
  <li>Continue through the steps to finish the Verification and account set Up.</li>
</ol>
<br />

<h2>Azure Home Page Breakdown</h2>


<p>
<img src="https://github.com/mchajdecki/Microsoft-Azure/blob/a482d0c2d7e895dc4a95ed80be6b646379264302/images/Slide-5.jpg" alt="Creating An Account - Slide_5"/>
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

<h1 id="resource">Creating a Resource Group</h1>
<h2>A Resource Group is a folder in the cloud that holds virtual machines, virtual networks, storage accounts and other created services.</h2>

<p>
<img src="https://github.com/mchajdecki/Microsoft-Azure/blob/a482d0c2d7e895dc4a95ed80be6b646379264302/images/Slide-6.jpg" alt="Creating a Resource Group - Slide_6"/>
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
<img src="https://github.com/mchajdecki/Microsoft-Azure/blob/561c97d4a67f30e836fcdb2d0c3fd40904d72cc8/images/Slide-7.jpg" alt="Creating a Resource Group - Slide_7"/>
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
<img src="https://github.com/mchajdecki/Microsoft-Azure/blob/561c97d4a67f30e836fcdb2d0c3fd40904d72cc8/images/Slide-8.jpg" alt="Creating a Resource Group - Slide_8"/>
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
<img src="https://github.com/mchajdecki/Microsoft-Azure/blob/561c97d4a67f30e836fcdb2d0c3fd40904d72cc8/images/Slide-9.jpg" alt="Creating a Resource Group - Slide_9"/>
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

<h1 id="storage">Creating a Storage Account</h1>
<h2>A storage account is a service that provides a secure place to store data like files, queues, blobs, tables, and disks, is used to manage and access different types of cloud storage in one place.</h2>

<p>
<img src="https://github.com/mchajdecki/Microsoft-Azure/blob/561c97d4a67f30e836fcdb2d0c3fd40904d72cc8/images/Slide_10.jpg" alt="Creating a Storage Account and Working With Files - Slide_10"/>
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
<img src="https://github.com/mchajdecki/Microsoft-Azure/blob/561c97d4a67f30e836fcdb2d0c3fd40904d72cc8/images/Slide_11.jpg" alt="Creating a Storage Account and Working With Files - Slide_11"/>
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
  <img src="https://github.com/mchajdecki/Microsoft-Azure/blob/a76cff76dfdf816f07ff269d7babf85f3df735ec/images/Slide_12.jpg" alt="Creating a Storage Account and Working With Files - Slide_12">
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
<img src="https://github.com/mchajdecki/Microsoft-Azure/blob/a76cff76dfdf816f07ff269d7babf85f3df735ec/images/Slide_13.jpg" alt="Creating a Storage Account and Working With Files - Slide_13">
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
<img src="https://github.com/mchajdecki/Microsoft-Azure/blob/a76cff76dfdf816f07ff269d7babf85f3df735ec/images/Slide_14.jpg" alt="Creating a Storage Account and Working With Files - Slide_14">
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
<img src="https://github.com/mchajdecki/Microsoft-Azure/blob/a76cff76dfdf816f07ff269d7babf85f3df735ec/images/Slide_15.jpg" alt="Creating a Storage Account and Working With Files - Slide_15">
</p>
<p>
  <ol type="1">
    <li>The created storage account will be located in the appropriate resource group selected in the previous steps.</li>
    <li>The storage account has been created successfully.</li>
  </ol>
</p>
<br />
<hr>

<h1 id="files">Working With Files</h1>
<h2>These steps will show how to create a simple text file and upload it to the created Storage Account from the previous step.</h2>
<h3>Locate and select the appropriate software to create a text file.</h3>

<p>
<img src="https://github.com/mchajdecki/Microsoft-Azure/blob/a76cff76dfdf816f07ff269d7babf85f3df735ec/images/Slide_16.jpg" alt="WorkingWithFiles - Slide_16"/>
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
<img src="https://github.com/mchajdecki/Microsoft-Azure/blob/a76cff76dfdf816f07ff269d7babf85f3df735ec/images/Slide_17.jpg" alt="WorkingWithFiles - Slide_17"/>
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
  <img src="https://github.com/mchajdecki/Microsoft-Azure/blob/a76cff76dfdf816f07ff269d7babf85f3df735ec/images/Slide_18.jpg" alt="WorkingWithFiles - Slide_18">
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
<img src="https://github.com/mchajdecki/Microsoft-Azure/blob/a76cff76dfdf816f07ff269d7babf85f3df735ec/images/Slide_19.jpg" alt="WorkingWithFiles - Slide_19">
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
<img src="https://github.com/mchajdecki/Microsoft-Azure/blob/a76cff76dfdf816f07ff269d7babf85f3df735ec/images/Slide_20.jpg" alt="WorkingWithFiles - Slide_20">
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
  <img src="https://github.com/mchajdecki/Microsoft-Azure/blob/a76cff76dfdf816f07ff269d7babf85f3df735ec/images/Slide_21.jpg" alt="WorkingWithFiles - Slide_21">
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
  <img src="https://github.com/mchajdecki/Microsoft-Azure/blob/a76cff76dfdf816f07ff269d7babf85f3df735ec/images/Slide_22.jpg" alt="WorkingWithFiles - Slide_22">
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

<h1 id="vm">Creating a Virtual Machine and Logging In</h1>
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
  <img src="https://github.com/mchajdecki/Microsoft-Azure/blob/a76cff76dfdf816f07ff269d7babf85f3df735ec/images/Slide_23.jpg"  alt="CreatingaVirtualMachine _ Slide_23">
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
  <img src="https://github.com/mchajdecki/Microsoft-Azure/blob/a76cff76dfdf816f07ff269d7babf85f3df735ec/images/Slide_24.jpg" alt="CreatingaVirtualMachine - Slide_24">
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
  <img src="https://github.com/mchajdecki/Microsoft-Azure/blob/a76cff76dfdf816f07ff269d7babf85f3df735ec/images/Slide_25.jpg" alt="CreatingaVirtualMachine - Slide_25">
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

<h2>Creating a Virtual Machine</h2>
<p>
  <img src="https://github.com/mchajdecki/Microsoft-Azure/blob/95a413af6ef9b1e1154c1f15583ceb2f53785d92/images/Slide_26.jpg" alt="CreatingaVirtualMachine - Slide_26">
</p>
<p> 
  <ol type="1">
    <li>A message will display that the Validation has passed.</li>
    <li>Click create on the bottom of the page to continue in creating the Virtual Machine.</li>
    <li>The Virtual Machine has been successfully created.</li>
  </ol>
</p>
</br>
<hr>
  

<h2>Logging Into a Virtual Machine</h2>
<h3>Prior to logging into the Virtual Machine gather the log in credentials created and the public IP address associated with Virtual Machine.</h3>
<p>
  <img src="https://github.com/mchajdecki/Microsoft-Azure/blob/95a413af6ef9b1e1154c1f15583ceb2f53785d92/images/Slide_27.jpg" alt="LoggingIntoAVirtualMachine - Slide_27">
</p>
<p>
  <ol type="1">
    <li>Prior to logging into the Virtual Machine gather the log in credentials created and the public IP address associated with Virtual Machine. </li>
    <li>This information can be found in the created VM - head over to Virtual Machine and click on Connect.</li>
    <li>Copy the Public IP Address as you will need it for the Log In</li>
  </ol>
</p>
</br>
<hr>


<h2>Logging Into a Virtual Machine</h2>
<h3>The Virtual Machine that is accessed in this tutorial is from a Mac Computer to a Windows PC. Towards the end of the logging in tutorial the version of Windows PC to Mac Computer will be presented</h3>
<p>
<img src="https://github.com/mchajdecki/Microsoft-Azure/blob/95a413af6ef9b1e1154c1f15583ceb2f53785d92/images/Slide_28.jpg" alt="LoggingIntoAVirtualMachine - Slide_28">
</p>
<p>
  <ol type="1">
    <li>In the App Store on a Mac device search for the Windows App software.</li>
    <li>Proceed to download the software at it is necessary in order to log into the created Virtual Machine.</li>
    <li>Open the Windows App software.</li>
  </ol>
</p>
</br>
<hr>

<h2>Logging Into a Virtual Machine</h2>
<p>
  <img src="https://github.com/mchajdecki/Microsoft-Azure/blob/95a413af6ef9b1e1154c1f15583ceb2f53785d92/images/Slide_29.jpg" alt="LoggingIntoAVirtualMachine - Slide_29">
</p>
<p>
  <ol type="1">
    <li>Click on the + sign in the right hand corner of the Windows App and observe a drop dowm menu appear.</li>
    <li>From the drop down menu click on Add PC to continue the log in process.</li>
  </ol>
</p>
</br>
<hr>

<h2>Logging Into a Virtual Machine</h2>
<p>
  <img src="https://github.com/mchajdecki/Microsoft-Azure/blob/a9a63e5d632c2c84c56179cfeae2338a93bbe86b/images/Slide_30.jpg" alt="LoggingIntoAVirtualMachine - Slide_30">
</p>
<p>
  <ol type="1">
    <li>Add PC box will display.</li>
    <li>Copy and Paste The Public IP address that was created in the Virtual Machine.</li>
    <li>The add option will be available to click after typing in the IP address.</li>
  </ol>
</p>
</br>
<hr>
