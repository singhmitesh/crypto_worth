# crypto_worth
This is a Python script to calculate the total net-worth of cryptocurrency investment portfolio.

## Getting Started

There is only file you have to edit i.e the "feeder" file. Which is nothing but a python file with a python dictionary which contians the information about your holdings in different crypto currencies.

## Setup instructions

* 1. Clone this repository.

            git clone https://github.com/singhmitesh/crypto_worth.git

* 2. cd into the repository.

            cd crypto_worth



## Installing

* Run requirements file

        sudo pip install -r `requirements.py`


## Edit Feeder file

Open "feeder" file and edit it accordingly



    {
        "s_no":3,
        "currency": "ripple",
        "holding": 2266.55
    }

## Run

    python fetch.py



### NOTE : Holding is the "quantity" of the respective crypto currency you hold in your portfolio.



PS: Just edit the currency and holding field.
