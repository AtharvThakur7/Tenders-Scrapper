I Have a built a Data Pipeline to Extract Data from CPWD_tenders Website , Tranform the Data and Save final result as CSV file . I have use  Apache Airflow to Orchestrate and Automate the entire process . 
Steps to run the projects are :
1.Unzip Folder and open in code editor and just run "docker compose build" and 
after that run  "docker compose up"  it will start running Airflow, 2.use Airflow UI to login(Airflow = passowrd + username) and find cpwd_tender_scraper_dag and run it manually , all the task will run sucessfully and you will see final output(CSV File) in Data folder locally inisde your project directory .

Summary = 1.Output is store in Data Folder 2. scrap logic file  and Dag File  both are inside Dags/ Folder. I learn a Lot from this project and thanks for giving me this Oppurtunity .
