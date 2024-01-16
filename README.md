
<img width="222" alt="Screen Shot 2024-01-13 at 4 02 07 PM" src="https://github.com/mathcsnerd/cse15l-lab-reports/assets/153144074/fe3d9957-b7af-4ef8-a056-1a56eb9a24bc">
The working directory is initially /home/lecture1/ when I ran ALL the commands below.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

1.) NO ARGUMENTS (cd, ls, cat)

When we pass in no argument for the cd command, the directory doesn't change, and hence, nothing is printed (NO ERROR!)

<img width="195" alt="Screen Shot 2024-01-13 at 4 02 32 PM" src="https://github.com/mathcsnerd/cse15l-lab-reports/assets/153144074/b849d395-7383-4934-a2f5-8c628266d22e">


When we pass in no argument for the ls command, it will just list the folders in the current working directory. As shown in the first picture, the main folder in /home is lecture1. (NO ERROR!)

<img width="207" alt="Screen Shot 2024-01-13 at 4 13 08 PM" src="https://github.com/mathcsnerd/cse15l-lab-reports/assets/153144074/e80a846f-5075-48ac-a80b-9825fd14099b">


When we pass in no argument for the cat command, it by default reads from the terminal and so nothing is printed. (NO ERROR!)

<img width="226" alt="Screen Shot 2024-01-14 at 1 05 28 PM" src="https://github.com/mathcsnerd/cse15l-lab-reports/assets/153144074/6378777a-4047-498c-a2f7-73dcfb7a397f">

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

2.) Using the command with a path to a directory as an argument (cd, ls, cat)

   If we pass in /home/lecture1/messages/ as argument for cd command, the directory will shift from /home/lecture1/ to /home/lecture1/messages/ (NO ERROR!)

<img width="412" alt="Screen Shot 2024-01-13 at 4 31 22 PM" src="https://github.com/mathcsnerd/cse15l-lab-reports/assets/153144074/61790945-9e56-45ff-967d-da1ff4a1a3e5">

  
  If we pass in /home/lecture1/messages/ as argument for ls command, the names of all the files in messages will be displayed (NO ERROR!)
  
<img width="422" alt="Screen Shot 2024-01-16 at 12 44 22 PM" src="https://github.com/mathcsnerd/cse15l-lab-reports/assets/153144074/71d53097-7311-463d-af37-814c5e6b96d1">


  If we pass in /home/lecture1/messages/ as argument for cat command, an error message will be produced. The cat command is designed to read a file or file interface, so using the directory as an argument will result in an error message

  <img width="737" alt="Screen Shot 2024-01-16 at 12 49 18 PM" src="https://github.com/mathcsnerd/cse15l-lab-reports/assets/153144074/82596370-87dd-4d9a-b86b-6b1f635d1a43">


----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

3.) using the command with a path to a file as an argument.

   If we pass in /home/lecture1/README as argument for cd command, an error message will be produced. This is because we can't change the directory to a single file. 

   
  <img width="478" alt="Screen Shot 2024-01-16 at 12 33 39 PM" src="https://github.com/mathcsnerd/cse15l-lab-reports/assets/153144074/cfdad4b0-c4f8-4f11-b20c-4464b8e7086f">


   If we pass in /home/lecture1/README as argument for the ls command, it will just read that file name and display that. (NO ERROR!)

  <img width="396" alt="Screen Shot 2024-01-16 at 12 29 54 PM" src="https://github.com/mathcsnerd/cse15l-lab-reports/assets/153144074/9e253170-6513-49af-8f21-8a7ce37f701e">
  

  If we pass in /home/lecture1/README as argument for the cat command, we will receive information about the README file. (NO ERROR!)
  
  <img width="408" alt="Screen Shot 2024-01-16 at 12 51 19 PM" src="https://github.com/mathcsnerd/cse15l-lab-reports/assets/153144074/2bf56339-97a7-4075-aaad-ac69b93a4689">





----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
