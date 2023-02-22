# Local development environment for python data projects, with Docker



To run the code, you will need docker , docker-compose.  I use a makefile to run the entire process


```bash
cd local_dev
make up
make ci # run tests and format code
make run-etl # run the ETL process
make down # spins down the containers
```

