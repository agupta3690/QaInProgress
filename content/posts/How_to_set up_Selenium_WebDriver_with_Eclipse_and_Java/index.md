+++
title = 'How to set up Selenium WebDriver with Eclipse and Java?'
date = 2024-01-12T15:55:02+05:30
draft = false
author = 'Arun'
featuredImage = "/images/featured.jpeg"
featuredImagePreview = "/images/featured_preview.jpeg"

+++

This is the very first step towards writing a great automation framework using Selenium WebDriver. As already stated, we'll only cover the Selenium WebDriver tutorials with Java and Eclipse. Here's the step by step guide to set up Selenium WebDriver with Eclipse and Java:


Installing Java on a Windows machine

Assuming you have a windows machine, in order to have Java up and running on your system, you'll have to install JDK (Java Development kit). And in order to install it, you'll first have to download it from Java's official website here.





Click on the 'Download' button on Java and move on to the next page.





Here, accept the license agreement and click on the link of windows version (.exe) of JDK.

Once the file gets downloaded, save it and double click it to install. Just note that the JRE (Java Runtime Enviroment) comes bundled with this version of JDK. Hence, no need to install the JRE separately.

After the successful installation of JDK, open up Command Prompt (CMD) and type 'Java' on the console and hit enter to check if Java has been installed correctly into your machine or not. If you see the following screen after doing the aforementioned steps, you are good to go.





Installing Eclipse IDE on a windows machine

Now, when you have successfully installed Java into your machine, it's time to install the IDE where you'll write all your code to make use of the awesome tool called Selenium WebDriver. And for that, you'll have to head to Eclipse's official website and download Eclipse IDE for Java Developers here.





Once you click on the 'Download' button, an installer file will be downloaded. Just double-click the installer file and proceed with the installation. Click on 'Eclipse IDE for Java Developers' on the next screen.





Set the installation folder to 'C:/Eclipse' on the next screen and proceed with the installation.






Once the installation is complete, just click on 'Launch' button on the next screen. This will launch Eclipse Oxygen for you.

Download Selenium WebDriver

Now you have your basic set up ready with Eclipse and Java. Let's proceed towards our main character of the script which is none other than Selenium WebDriver. Download the .jar files here.





Remember, we are working with Java. Hence, download the zip folder for Java and extract it into any of the drives of your system. After you extract the zip folder, you'll get all the .jar files which you'll further need to import on Eclipse.


Configure Eclipse with Selenium WebDriver


Now, give a pat on your back for coming this far as you have all the powers of this world to automate your very first website. We'll now import the Selenium jars into Eclipse. So, follow the step by step guide below:

Launch the eclipse.exe file located at "C:/Eclipse" if you mentioned the same path for the Installation Folder as mentioned in this tutorial while downloading it.
Before the launch, Eclipse will ask you to choose a workplace. At this time, don't make any changes and click 'Launch' or 'OK' on the dialog box.



Once the Eclipse is launched, you'll see an empty Project Explorer window. Here, you have to make a new project. Click on File > New > Java Project.



A new panel will be popped-up to enter project details. Just enter the project name and leave rest of the options unchanged and click on 'Finish'.



After creating a new project, right-click on the project folder in the Project Explorer window and click on New > Package.



A new panel will be popped up. Just provide the name of the package into it and then click on 'Finish'.



Once the package is created, right-click on the package and click on New > Class.



Once you click on Class, a similar panel will pop-up which will ask you to enter the name of the class. Provide the name of the class in this panel and click on 'Finish'.



When you are finish with all the steps mentioned above, you see your first test class and the project structure like this.




Importing the Selenium WebDriver .jar files


We have set up the project and ready to import the Selenium .jar files into our project. Follow the step by step guide mentioned below in order to import the Selenium jars into the project.

Right-click on the project folder and click on the Build Path > Configure Build Path in the menu.



After following the aforementioned step, a panel will pop-up which will give you an option to import all external jars into the current project. Click on 'Add External JARs' button on this panel in order to browse to your Selenium WebDriver jars which you haves saved in one of your drives as mentioned above in the tutorial.



Once you successfully browse to the Selenium folder in your local drive, make sure to select all .jar files situated inside and outside the libs folder.






Once you import all .jar files, the panel will look something like this



Now click on 'Apply and Close' button to save the changes.
And that's it. Congratulations, you are done with setting up the Selenium WebDriver with Eclipse.
