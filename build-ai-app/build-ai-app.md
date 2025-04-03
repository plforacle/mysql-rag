# Build MySQL AI Application

## Introduction

MySQL Enterprise Edition integrates seamlessly with the LAMP (Linux, Apache, MySQL, PHP) stack, enhancing open-source capabilities with enterprise features. MySQL EE works with the LAMP stack by:

After installing the LAMP Stack , you will Deploy and test the "Sakila Film Library with Time Converter" web application. This application displays the Sakila.Film data while providing a time conversion tool. Users can enter seconds and convert them to either HH:MM:SS format or written time descriptions using MySQL Enterprise Edition's JavaScript function. This LAMP-based application demonstrates practical use of database features within MySQL Enterprise Edition.

**Note:** The application code in this lab is intended for educational purposes only. It is designed to help developers learn and practice application development skills with MySQL Enterprise Edition. The code is not designed to be used in a production environment

_Estimated Lab Time:_ 15 minutes

### Objectives

In this lab, you will be guided through the following tasks:

- Install Apache and PHP
- Learn to create PHP / MYSQL Connect Application
- Deploy the Sample LAMP WEB Application

### Prerequisites

- An Oracle Trial or Paid Cloud Account
- Some Experience with MySQL SQL and  PHP
- Completed Lab 5



## Task 1: Deploy MySQL Chatbot / RAG Application  

1. Go to the development folder

    ```bash
    <copy>cd /var/www/html</copy>
    ```


2. Download application code

    ```bash
    <copy> sudo wget https://objectstorage.us-ashburn-1.oraclecloud.com/p/3OoFNkSBu-odiaGYWalLY0L0s7xPw99x-pIcgC28w5wrH5DLrrwpsWtulHUJaPsd/n/idazzjlcjqzj/b/Applications/o/my-web-app.zip</copy>
    ```

3. unzip Application code

    ```bash
    <copy>sudo unzip my-web-app.zip</copy>
    ```

    ```bash
    <copy>cd my-web-ap</copy>
    ```

4. Run the application as follows (Use your coupute IP address):

    http://127.0.0.../my-web-ap/

    ![MySQL Rag App](./images/my-web-app.png "MySQL Rag App")

5. Test the application by clicking the "Sample Prompts" menu. Select a prompt and hit *Send*


## Learn More

- [Install Apache and PHP on an Oracle Linux Instance](https://docs.oracle.com/en-us/iaas/developer-tutorials/tutorials/apache-on-oracle-linux/01-summary.htm)


## Acknowledgements

- **Author** - Craig Shallahamer, Applied AI Scientist, Viscosity North America
- **Contributor** - Perside Foster, MySQL Solution Engineering 
- **Last Updated By/Date** - Craig Shallahamer, Applied AI Scientist, Viscosity North America, April 2025