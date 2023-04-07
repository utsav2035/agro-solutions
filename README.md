
# Agro Solutions

A platform to help farmers buy necessary commodities related to farming and sell their yield at MSP. Inform them about market prices and agriculture-related news to make farmers trend-ready.


Agro Solutions is built with Next.js for the frontend and backend. It uses APIs and web scraping to accomplish its objectives related to data collection.


Users can buy the necessary commodities required for a good yield and learn about the processes and techniques required to have a maximum yield. This yield can also be sold when signing up as a merchant. It shows agriculture sector news and also can tell rates in mandis for a particular district with a particular commodity.

<!-- 
## Demo

[Agro Solutions](https://youtu.be/3BvayDWLq-c) -->


## Installation

Clone the git repository:

```bash
  git clone https://github.com/STRYKER2403/agro_solutions.git
  cd agro_solutions
```
Install necessary dependencies:

```bash
  yarn add dependencies or yarn install
```
Create an .env file and set the following variables:

```bash
  MONGO_URI = mongodb://localhost:27017/agrosolutions
  NEXT_PUBLIC_HOST = http://localhost:3000
  NEXT_PUBLIC_PAYTM_HOST = ********
  NEXT_PUBLIC_PAYTM_MID = ********
  PAYTM_MKEY = ********
  AES_SECRET = ********
  JWT_SECRET = ********
  OUTLOOK_MAIL = ********
  OUTLOOK_PASSWORD = ********
  DATA_GOV_API_KEY = ********

```

Run development server:

```bash
  yarn both
```


## Usage

1. Navigate your site to ```/signup``` Create an account for yourself (create a merchant account to access all features).

2. From the Home page , navigation to four sections is possible:

- products - buy products.
- articles - latest agriculture news.
- learn - Market trends to know mandi rates.
        Crop plan for various crop information.
- Contact Us - contact section.    

3. My account, my orders, and my dashboard are accessible from the profile icon at the top right corner. Changing of passwords, viewing order summaries, and adding and updating products through the dashboard are available.

## Screenshots

Sign in page:
![Screenshot (182)](https://user-images.githubusercontent.com/75637474/230471758-2b62678e-b884-4a5a-b507-1e5fe30b9c13.png)

Product page:
![Screenshot (185)](https://user-images.githubusercontent.com/75637474/230472108-0f5d995f-a841-4889-8dea-481b82a4aeb4.png)

Home page:
![Screenshot (189)](https://user-images.githubusercontent.com/75637474/230472261-543354d6-4ffd-4055-a6ee-4b7db47ba1cb.png)

Shopping cart + checkout page: 
![Screenshot (202)](https://user-images.githubusercontent.com/75637474/230472293-876c007d-bee1-4657-94b0-a73d5e3ba0c8.png)

Paytm integration(payment gateway):
![Screenshot (186)](https://user-images.githubusercontent.com/75637474/230472148-9feb9bf5-5632-46bd-9782-24a613ed3e60.png)

My order page:
![Screenshot (203)](https://user-images.githubusercontent.com/75637474/230472300-37902e2e-5666-42d1-8008-94f4eaef89af.png)

Article section:
![Screenshot (205)](https://user-images.githubusercontent.com/75637474/230472316-e4df1784-fddc-47c5-9765-02b1a3b296ad.png)

