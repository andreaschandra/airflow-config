# airflow-config
Airflow Configuration for Single and Multi Nodes

## Things to pay attention

```
executor = CeleryExecutor
sql_alchemy_conn = postgresql+psycopg2://airflow@localhost:5432/airflow

load_examples = False

load_default_connections = True

broker_url = amqp://admin:admin@localhost:5672/myvhost
result_backend = db+postgresql://airflow@localhost/airflow
```