# Extract-Load-Transform-and-Notify-using-Airflow
Automating data extraction, transformation, and delivery across systems 🌐, ensuring seamless data integration, analysis, and timely reporting 📊, while notifying stakeholders via email 📧 to make data-driven decisions faster and more efficiently.


### Step : 1- Apache Airflow Setup 🚀

- Install Airflow via pip:
You can install Apache Airflow using `pip`
```bash
pip install apache-airflow
```

- Check the Airflow Version
```bash
airflow version
```

- Verify airflow commands
```bash
airflow info
```

- Initialize Airflow:
Apache Airflow uses a metadata database. By default, it uses SQLite.
```bash
  airflow db init
```

- Add users in Apache Airflow
```bash
airflow users create \
  --username anowerhossain \
  --firstname Anower \
  --lastname Hossain \
  --email anowerhossain97@gmail.com \
  --role Admin \
  --password "newpassword"
```
- To verify users is added run

```bash
airflow users list
```


- Start Airflow web server and scheduler:
```bash
airflow webserver -p 8080
airflow scheduler
```
Access the Airflow UI at `http://localhost:8080`
