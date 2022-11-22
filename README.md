# BANK-MARKETING-CAMPAIGN-PREDICTION

## BANK DATA
The data is related with direct marketing campaigns of a Portuguese banking institution.
The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be (or not) subscribed.

Pada kesempatan kali ini saya akan mencoba untuk melakukan eksplorasi data dari data Bank Portugis ini.
Tujuan eksplorasi data kali ini ialah untuk mencari tau pola dari client yg tidak berlangganan deposito berjangka.

Untuk eksplorasi data kali ini akan saya lakukan dalam beberapa tahapan dan akan saya lakukan berdasarkan kelompok data.
Eksplorasi awal ke target features - subscribed, lalu eksplorasi ke kelompok numerical dan terakhir ke kelompok categorical.

## FEATURE DESCRIPTION
Input variables:

Bank client data:

1 - age (numeric)<br>
2 - job : type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student",
                                   "blue-collar","self-employed","retired","technician","services") <br>
3 - marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)<br>
4 - education (categorical: "unknown","secondary","primary","tertiary")<br>
5 - default: has credit in default? (binary: "yes","no")<br>
6 - balance: average yearly balance, in euros (numeric)<br>
7 - housing: has housing loan? (binary: "yes","no")<br>
8 - loan: has personal loan? (binary: "yes","no")<br>

Related with the last contact of the current campaign:

9 - contact: contact communication type (categorical: "unknown","telephone","cellular")<br>
10 - day: last contact day of the month (numeric)<br>
11 - month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")<br>
12 - duration: last contact duration, in seconds (numeric)<br>

Other attributes:

13 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)<br>
14 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)<br>
15 - previous: number of contacts performed before this campaign and for this client (numeric)<br>
16 - poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")<br>

Output variable (desired target):

17 - y - has the client subscribed a term deposit? (binary: "yes","no")
