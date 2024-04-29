Clone the repository

    git clone https://github.com/andrewdwallo/erpsaas.git

Switch to the repo folder

    cd erpsaas

Install all the dependencies using Makefile

    make

If the migrations don't run, update the following variable in your .env

    DB_HOST=mysql

Now run 

    make migrate
