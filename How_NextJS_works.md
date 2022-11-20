- #### NextJS is a framework, which organize and optimize the application both in development and deployment process.
- #### There are 2 types of environment where our code works:
   ##### 1. Development: Running and building the application in the local system.
   ##### 2. Production(or deployment): The process where the application is available for end-users.
   
- #### In NextJS, the production optimization processs includes *Compilation*, *Bundling*, *Minifying* and *Code Splitting*
  ##### 1. *Compilation*: The operation of converting code in one language(that developers write) and outputting it in another version of that languange(browser compatible lannguage).

 *From the below image, it clearly demonstartes what Compilation is*

<img width="509" alt="next-4" src="https://user-images.githubusercontent.com/71059909/202891905-58c02bb1-9e37-4fdb-b7b1-118d4a61c5d9.PNG">

  ##### 2. *Minifying*: The process of removing unnecessary elements in the code (such as comments, spaces, indents and multiple line) without changing the code's functionality. In NextJS, JS & CSS files are automatically minified for production.

 *From the below image, it clearly demonstartes what Minifying is*

<img width="511" alt="next-5" src="https://user-images.githubusercontent.com/71059909/202906113-8917a957-b19c-41ac-851a-c71c3c1fc258.PNG">

##### 3. *Bundling*: The process of resolving the web of dependencies and merging the various files in an application into optimized bundles for the browser. The purpose of Bundling is to reduce the number of requests for files when a user visits a web page.

 *From the below image, it clearly demonstartes what Bundling is*

<img width="512" alt="next-6" src="https://user-images.githubusercontent.com/71059909/202906618-1f6508fe-6adc-4b48-8b64-3778576da67d.PNG">

##### 4. *Code Splitting*: Application comprises of multiple pages with respective different URLs. 
##### The process of splitting the application bundle  into smaller chunks in order to improve the application's initial load time by loading the threshold code required to run that page. 
##### NextJS splits the code in `pages/` directory into its JS bundle while building. 

 *From the below image, it clearly demonstartes what Code splitting is*

<img width="508" alt="next-7" src="https://user-images.githubusercontent.com/71059909/202914603-80f94289-7ed4-48c9-9217-7a98ff0b3ff7.PNG">




