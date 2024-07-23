# Grafana + Prometheus + MySQL

- Copy `.env` file from `.env.example` file and fill values for MySQL & MongoDB credential
- Copy `.config.my-cnf` file from `.config.my-cnf.example` file and fill values for MySQL & MongoDB credential

- Run stacks:

```sh
docker compose up -d
```
- Visit `http://localhost:3000` for Grafana Login UI. Default username and password are `admin` and `admin`. Grafana will ask you to change this in next step.

- In Grafana Homepage, click **Dashboard**. Click on **Create Dashboard**, then click on **Import dashboard** and type `14057` then click on **Load** and finally click on **Import**. You will see the MySQL dashboard with metrics/

- In Grafana Homepage, click **Dashboard**. Click on **Create Dashboard**, then click on **Import dashboard** and type `12079` then click on **Load** and finally click on **Import**. You will see the MongoDB dashboard with metrics/