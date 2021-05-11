### Introduction
Programmers who have ever worked with the database are likely to have also worked with CRUD Operations. This operations are very important when a developer want to learn any web framework. In this article, we will learn how to operates CRUD using [YII 2 framework]() .

### What is CRUD?
CRUD is an acronym that stands for Create, Read, Update, Delete. Each letter in the acronym can refer to all functions executed in relational database applications.

Let us look at the function of each letter in details:

1. CREATE - Performs the INSERT operation to a new record.

2. READ - Reads and display the record based on the Primary key.

3. UPDATE - Execute an UPDATE statement in the table depending on the Primary key for a record within the WHERE condition.

4. Delete - Deletes a row in the WHERE condition.

### What Is GII ?
[GII]() is a YII module that generates code for CRUD, forms, models, and controllers. In YII 2 Framework GII is accessible by the localhost by default and the module is accessed in the browser.

Prerequisites
I will assume that you have:

1. Xampp installed in your machine. If not follow [this](https://www.section.io/engineering-education/maria-data-base/) steps to install. This will come along with PhpMyAdmin which we will use to manage our database record. 
2. YII 2 installed. If not refer [here](https://www.section.io/engineering-education/php-yii2-framework/) on how to install.

In this article we are going to:
1. Create a YII project named CRUD 
2. Create a simple database record using terminal 
3. Generate CRUD using GII
4. Store data in database using GII

Let's get started.

### Step 1 -- Create a YII CRUD project
After installing Xampp, a folder `/opt/lampp` will be created.
1. Navigate to to the folder where the YII archive file was downloaded. In my case it was downloaded in Downloads.  
2. Move this archive to `/opt/lampp/htdocs` . To move it, open the Downloads folder with terminal and type:

```bash
$ sudo mv yii-advanced-app-2.0.39.tgz /opt/lampp/htdocs
```

3. Now, open `/optlampp/htdocs` using teminal and type this command:
```
$ sudo tar -xvzf yii-advanced-'app-2.0.39.tgz
```
This command will unzip the Yii file and generate a folder `advanced`.

4. Using terminal open `/opt/lampp/htdocs/advanced` and run the command below:

```bash
php init
```
This command will initialize your project advanced. Choose option 0.

5. To rename this project to CRUD project, open `/opt/lampp/htdocs` and type:
```bash
$ sudo mv advanced CRUD
```

### Conclusion
